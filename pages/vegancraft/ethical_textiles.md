---
title: Ethical Textiles
keywords: minecraft, datapack, vegan, veganism, plant-based, pacifist, clothes, clothing
tags: [datapack, vegancraft, standalone, crafting]
sidebar: home_sidebar
toc: true
last_updated: 05/Nov/2022
permalink: ethical_textiles.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/ethical-textiles-plant-string-and-leather/
first_release: ["15","Oct","2022"]
last_release: ["15","Oct","2022"]
logo: vegancraft/ethical_textiles/pack.png
intro: "A datapack that adds plant-based alternatives to leather, string, and wool.<br/><br/>You will need my <a href=acacia_gum.html>Acacia Gum datapack</a> in order to have a vegan leather option (but it's not required to use this datapack)."
abstract: "Plant-based alternatives for string, leather, and beds. Use together with <i>Acacia Gum</i> to have fully vegan leather."
priority: 4
index: 12
---

## Downloads
{% include dp_badges.html supports="1.17%2B" tested="1.17.1%2C%201.18.2%2C%201.19.2" %}

{% include dp_download.html version="v1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/ethical_textiles_v1.zip" pmc-url="https://www.planetminecraft.com/data-pack/ethical-textiles-plant-string-and-leather/download/file/16157350/" rp-version="v1d" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/vegancraft-RP_v1d.zip" %}

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

### New recipes

{% include comments/important.html content="These recipes will output a knowledge book, the knowledge book will convert automatically into the desired item once you click on it. ***Not compatible with recipe unlockers***." %}

#### Faux Leather

Crafted with 3 slime balls and either 3 of the following ingredients:
- Cactus
- Dark oak log or wood

or 6:
- Bamboo
- Paper
- Dried kelp.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/leather.gif" alt="Faux leather recipes" align="center" width="300" %}

#### Rudimentary beds
**Beds** can be crafted with 3 wooden planks and 3 hay, or 6 jungle leaves or grass.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/bed.gif" alt="Rudimentary bed recipes" align="center" width="300" %}

#### Plant-based string
Vines, sugar cane, and dripleaves can be used to craft **string**. Use 4 of these strings to craft vegan "wool".

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/string.gif" alt="Plant string recipes" align="center" width="200" %}

#### Synthetic cobwebs
**Cobwebs** can be crafted with 8 strings and a slime ball.

### Custom textures
Faux leather and plant string have their own texture. Here they are compared to their vanilla counterparts:

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/texture_comparison.png" alt="Texture comparison" align="center" width="120" %}

The [Vegancraft Resourcepack](#downloads) is required to see this texture in-game.

{% include comments/important.html content="Due to the way I coded the recipes, sometimes the output will show the actual vanilla item instead of the knowledge book. If you want the custom item name and texture, just change the position of any ingredient and the output will change to the knowledge book. I decided to do it this way so the recipes show up in the in-game recipe book, instead of having to memorize them. Here is an example, the recipe shows a vanilla bed, and changing the position of one ingredient outputs the knowledge book:" %}

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/swap_ingredients.gif" alt="Swapping the position of two ingredients will change the output to a knowledge book, if it was not already" align="center" width="300" %}

### Vegancraft

This is a standalone datapack, but was designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

As part of its integration on Vegancraft, this datapack includes the following additional features:

- A custom advancement tree.
- Some xp will be awarded when crafting faux leather and plant string. For leather, the amount of xp is equivalent to that you would get by getting it the "regular" way (breeding and killing cows). For string, it is only 0.1 XP, since it's very easy to get.
- Vegan ingredients detection: the datapack will try to determine if you are using vegan ingredients or not when crafting these items, labelling them if they are not vegan. Vegan and non-vegan items do not stack.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/slime_leather.png" alt="Faux leather with animal slime" align="center" width="200" %}

If, for any reason, you want to remove these features, you can use the command **<code>/function dnv.vegancraft:toggle</code>** to disable them. You can also use that command to turn them on again.

### Future features

In the future, I might consider:

- Improving the existing recipes and advancements.
- Adding a recipe for plant-based "feathers", it would likely involve strings and paper or leaves, so it would fit within this datapack.
- Improving the vegan advancement tree.

## Reasoning for the recipes

- Faux leather is based on real-world alternatives for leather, dark oak representing tree bark. Slime represents the plastic substances which are often used in their manufacture.
- Rudimentary beds: I just found it weird how in the early game you need to find sheep in order to sleep, and thought it would make sense to be able to craft beds with more rudimentary materials.
- String: since the most common real-world plants that produce fibers are not in the game (cotton, linen, flax...) I just decided to take the vanilla plants that looked more "stringy" and also sugar cane, because in-game it is already implied that it produces fiber since you make paper from it.
- Since cobweb is rarely used in the game, I just added a simple recipe which represents strings covered in slime to make them sticky.
- I considered adding a recipe for rabbit hides but, since they are only used to craft bundles, which are not yet officially in the game, I didn't do it. If you want to craft bundles without killing rabbits, I suggest using [Vanilla Tweaks' Craftable Bundles (Leather)](https://vanillatweaks.net/picker/crafting-tweaks/){:target="_blank"}.
- I didn't create a "vegan wool" item because of how many color variants there are and the difficult/cumbersome it would be to have a vegan variant for each one of them.

## Known issues and solutions
- As mentioned before, some recipes in the in-game recipe book will show the vanilla item instead of the custom one. This is on purpose since it is the only way (to my knowledge) of making them appear on the recipe book. The recipes of the custom items are shapeless, so you can just change the position of any ingredient and the output will change to the knowledge book, which will convert to the custom item. You can also use this to your advantage if you already have vanilla items in your inventory and you want to stack on them instead of having custom items on a separate stack. However, this is not consistent and sometimes the knowledge book is the only possible output.
- Vegan ingredients detection can fail if you drop or pick up vegan items while having the crafting table UI open. This will not be fixed as it is a very rare occurrence and easily avoidable, and the solution would be very difficult to code with datapack functionalities, if not impossible.
