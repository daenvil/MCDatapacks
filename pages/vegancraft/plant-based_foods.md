---
title: Plant-based Foods
keywords: minecraft, datapack, baking, cooking, food, vegan, veganism, plant-based, pacifist
tags: [datapack, vegancraft, standalone, crafting, food]
sidebar: home_sidebar
toc: true
last_updated: 05/Jan/2024
permalink: plant-based_foods.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/plant-based-foods/
first_release: ["17","Jun","2022"]
last_release: ["05","Jun","2023"]
logo: vegancraft/vegan_food/pack.png
thumbnail: vegancraft/vegan_food/thumbnail.png
intro: "A datapack that adds vegan alternatives to dairy, eggs, honey, and meat."
abstract: "Vegan alternatives to dairy, eggs, honey, and meat."
priotity: 1
index: 7
gallery: [images/vegancraft/vegan_food/thumbnail.png]
---

## Downloads
Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.20+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.16.2–1.19.4</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.20+" tested="1.20, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.1" pmc-url="https://www.planetminecraft.com/data-pack/plant-based-foods/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/plant-based_foods_v1.1.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.16.2–1.19.4" tested="1.16.5, 1.17.1, 1.18.2, 1.19.2" %}
            <br/>
            {% include dp_download.html version="v1.0.1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1c/plant-based_foods_v1.0.1.zip" rp-version="v1d" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/vegancraft-RP_v1d.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

- _[Youtube video showcasing all the features of this datapack (recorded in older version):](https://youtu.be/0FibGt2cS10){:target="_blank"}_

<iframe width="560" height="315" src="https://www.youtube.com/embed/0FibGt2cS10" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### New recipes

{% include comments/important.html content="These recipes will output a knowledge book, the knowledge book will convert automatically into the desired item once you click on it. If using the resourcepack, the knowledge book will display as a question mark named \"Custom Item\"." %}

#### Plant-based milk
Crafted with a water bucket, an empty bucket, and 6 wheat seeds, pumpkin seeds, potatoes, or sunflowers. *Behaves as a milk bucket*.

{% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/milk.gif" alt="Plant milk recipe" align="center" width="300" %}

#### Egg baking alternatives
**Pumpkin pies** and **cakes** can be crafted by replacing the egg in the vanilla recipe with wheat or a potato.


<p align="center">
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/pie.gif" alt="Pumpkin pie recipe" width="300" %}
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/cake.gif" alt="Cake recipe" width="300" %}
</p>

#### Vegan honey
Crafted in two ways:
- A water bucket, an empty bottle, and 6 flowers.
- An empty bottle and 4 apples.

*Behaves as a honey bottle*.

<p align="center">
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/flower_honey.gif" alt="Flower honey recipe" width="300" %}
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/apple_honey.png" alt="Apple honey recipe" width="300" %}
</p>

#### Seitan steak
Crafted with a water bucket, 3 wheat, and either mushroom stew or beetroot soup. *Behaves as a steak*.

{% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/seitan.gif" alt="Seitan steak recipe" align="center" width="300" %}

Alternatively, use hay bales instead of wheat to produce seitan more efficiently:

{% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/seitan_hay.gif" alt="Seitan steak recipe with hay bale instead of wheat" align="center" width="300" %}

#### Not-fish fillet
Crafted with a (seitan) steak and 3 kelp. *Behaves as raw cod (so you can attract cats with it and tame them)*.

{% include image/basic.html src="vegancraft/vegan_food/screenshots/recipes/fillet.png" alt="Not-fish fillet recipe" align="center" width="300" %}

### Custom textures
Each of the new food items has its own texture. Here they are compared to their vanilla counterparts:

{% include image/basic.html src="vegancraft/vegan_food/screenshots/texture_comparison.png" alt="Texture comparison" align="center" width="240" %}

The [Vegancraft Resourcepack](#downloads) is required to see these textures in-game.

### Recipe book integration

This datapack is designed so you can take full advantage of the in-game recipe book, instead of having to memorize the recipes. The recipes will show up twice: one as the vanilla item output, and another one as a question mark (re-textured knowledge book). **You can right-click the question mark in the recipe book to view all the custom recipes**. Here is how you will see it in-game:

{% include image/basic.html src="vegancraft/vegan_food/screenshots/recipe_book.gif" alt="Example of the in-game view of the recipe book" width="480" align="center" caption="Example: here I click the vanilla entry of the recipes, and then the question mark, where all the custom recipes are visible." %}

{% include comments/important.html content="Due to the way I coded the recipes, sometimes the output will show the actual vanilla item. If you want the custom item name and texture, just change the position of any ingredient and the output will change to the knowledge book (a question mark, when using the resourcepack). I decided to do it this way so the the vanilla counterpart of the output shows up in the in-game recipe book, instead of having to remember what the recipes do. Here is an example, the recipe shows a vanilla honey bottle, and changing the position of one ingredient outputs the custom item:" %}

{% include image/basic.html src="vegancraft/vegan_food/screenshots/swap_ingredients.gif" alt="In-game example of swapping the position of two ingredients" width="300" align="center" caption="Swapping the position of two ingredients will change the output to a knowledge book, if it was not already" %}

### Vegancraft

This is a standalone datapack, but was designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

As part of its integration on Vegancraft, this datapack includes the following additional features:

- A custom advancement tree.
- Vegan ingredients detection: since you can craft cakes with cow milk and not-fish fillets with cow meat, the datapack will detect if you are using vegan ingredients or not when crafting these items, labelling them if they are not vegan. Vegan and non-vegan items do not stack.
<p align="center">
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/milk_cake.png" alt="Egg-free cake with milk" width="200" %}
  {% include image/basic.html src="vegancraft/vegan_food/screenshots/meat_fillet.png" alt="Not-fish fillet with meat" width="200" %}
</p>

- Cats and wolves tamed with vegan food will have a green collar by default, instead of the usual red (check out my *[Omnivorous Pets](omnivorous_pets.html)* datapack if you want to tame wolves and cats with more kinds of foods).
- Some xp will be awarded when crafting seitan steaks and not-fish fillets. The amount of xp is equivalent to that you would get by getting those items the "regular" way (breeding and killing cows/fishing cod).

If, for any reason, you want to remove these features, you can use the command **<code>/function dnv.vegancraft:toggle</code>** to disable them. You can also use that command to turn them on again.

## Reasoning for the recipes

- All of the plant milk recipes are based on real plant-based milks (the sunflower representing sunflower seeds).
- The egg replacements --wheat and potato-- represent wheat flour and potato starch, respectively, both used in real-life egg-free baking.
- Flower honey represents a kind of vegan honey that can be made by boiling flowers in water. Apple honey represents apple syrup, as there are also recipes for vegan honey made from apple syrup or juice.
- Seitan is made by soaking wheat flour in water and filtering it. The stew/soup represents a marinade to give the seitan steak flavour.
- Not-fish fillet is based on real recipes for "vegan fish", although in real life it is more common to use tofu for this.

## Known issues and solutions
- As mentioned before, some recipes in the in-game recipe book will show the vanilla item instead of the custom one. This is on purpose since I think it's more clear and user-friendly to have the actual outputs show up in the recipe book. The recipes of the custom items are shapeless, so you can just change the position of any ingredient and the output will change to the custom item, which will convert to the custom item. You can also use this to your advantage if you already have vanilla items in your inventory and you want to stack on them instead of having custom items on a separate stack. However, this is not consistent and sometimes the custom item is the only possible output.

## Notes for developers
If you are creating a datapack that adds custom food and you want your custom food to be recognized by this datapack, just do the following:
- If it is a vegan food retexturing a non-vegan food item, just include the tag <code>dnv.Vegan:1b</code> in the NBT tags of the item.
- If it is a non-vegan food retexturing a vegan food item, just include the tag <code>dnv.Vegan:0b</code> in the NBT tags of the item.
