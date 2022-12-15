---
title: "[TUTORIAL] Random Number Generation through predicates"
keywords: 
sidebar: home_sidebar
toc: true
last_updated: 27/Nov/2022
permalink: rng_predicates.html
published: true
summary: "Tutorial to generate random numbers with Minecraft commands through the RBG method via random chance predicates."
---

<br/>
{% include comments/note.html content='This is a backup of [this post I made on Reddit](https://www.reddit.com/r/MinecraftCommands/comments/z5ct4s/random_number_generator_using_predicates_w/)' %}

## Random Bit Generation

_(I recommend knowing a bit about binary numbers)_

The main concept is: since any number can be expressed as a combination of 1s and 0s, and we have a built-in way of checking for a 50% chance (predicate), **we can use a 50% chance predicate for each bit of a number in order to generate a random number solely using Minecraft's RNG**.

The formula for a number, given its bits, is:

_x = a<sub>0</sub> * 2<sup>0</sup> + a<sub>1</sub> * 2<sup>1</sup> + a<sub>2</sub> * 2<sup>2</sup> + a_<sub>3</sub> * 2<sup>3</sup> + ... (etc.)_

So this concept is easily implemented through scoreboard commands as:

    scoreboard objectives add random_number dummy
    scoreboard players set #RNG random_number 0
    execute if predicate random:50pc run scoreboard players add #RNG random_number 1
    execute if predicate random:50pc run scoreboard players add #RNG random_number 2
    execute if predicate random:50pc run scoreboard players add #RNG random_number 4
    execute if predicate random:50pc run scoreboard players add #RNG random_number 8
    # (etc.)

where `random:50pc` is a simple `random_chance` predicate with `"chance":0.5`.

The above script succesfully generates a random number from 0 to 2^n -1 (accesible through `scoreboard players get #RNG random_number`), where "n" is the number of predicate lines you use (the above code outputs a number between 0 and 15).

### Advantages

- It's a very simple and intuitive method to implement.
- Relies entirely on Minecraft's RNG.
- For a number of bits fewer than 8 (0-255 range), this method is actually faster than LCG (according to my tests, see below for the results), which is the first method suggested in [the Minecraft Commands' wiki](https://www.reddit.com/r/MinecraftCommands/wiki/questions/randomnumber/).

### Disadvantages

- As is, only draws a number from 2^n choices, which means that if the size of your range is not a power of 2, you need to adapt the algorithm for your specific range (see below por possible solutions).

### Conclusions

- **I believe this method is best for generating numbers in small ranges (size of range < 256), while bigger ranges are more efficient with other algorithms such as LCG.**
- For ranges whose size is not a power of 2, this method can still be applied in the following ways:
  - If the size of your range is small, you can just use a division to scale the generated range down to your desired range with `scoreboard players operation #RNG random_number *= <size of your range>` and then `scoreboard players operation #RNG random_number /= <size of the generated range>`, the result should still be fairly random (the bigger your range is, the worse the result will be).
  - If you are comfortable doing some maths, the method can be extended to other bases different than 2, although the script becomes more complex and not so straight-forward.

---

## Performance test: this method vs. LCG

I tested the performance (using F3+L and checking the generated files) of computing 1000 random numbers using this method and using LCG (code directly taken from [this post](https://www.reddit.com/r/MinecraftCommands/comments/vv68n6/tutorial_random_number_generator_by_scoreboard/)) for different ranges. Here are the times it took the server to run 1000 RNGs:

|       Range       | RBG time (ms) | LCG time (ms) |
|:-----------------:|:-------------:|:-------------:|
|   0-15 (4 bits)   |     0.045     |     0.070     |
|   0-255 (8 bits)  |     0.065     |     0.070     |
|  0-1023 (10 bits) |     0.075     |     0.065     |
| 0-65535 (16 bits) |     0.120     |     0.065     |

- As expected, LCG's performance doesn't care about the range, since it's only taken into account in a single command with a modulus operation.
- RBG (this method) scales ~linearly with the range, also as expected (more range, more number of predicates being run).
- Both methods seem to give the same performance at 8 bits. I reran the tests multiple times in that range obtaining an average of 0.067 ms for both methods.
- Overall, I don't think the difference with LCG in bigger ranges is so big as to cause performance issues in occasional usage (remember that these are 1000 RNGs run in the same tick, that will hopefully never happen in a regular datapack), so if one wants to avoid using LCG, using this method with <16 bits and then scaling the output down to the desired range seems like a good option for most usecases where you don't need a very big range.