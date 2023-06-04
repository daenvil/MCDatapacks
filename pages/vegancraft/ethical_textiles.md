---
title: Ethical Textiles
keywords: minecraft, datapack, vegan, veganism, plant-based, pacifist, clothes, clothing
tags: [datapack, vegancraft, standalone, crafting]
sidebar: home_sidebar
toc: true
last_updated: 05/Jun/2023
permalink: ethical_textiles.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/ethical-textiles-plant-string-and-leather/
first_release: ["15","Oct","2022"]
last_release: ["05","Jun","2023"]
logo: vegancraft/ethical_textiles/pack.png
thumbnail: vegancraft/ethical_textiles/thumbnail.png
intro: "A datapack that adds plant-based alternatives to leather, string, wool, and feathers.<br/><br/>You will need my <a href=acacia_gum.html>Acacia Gum datapack</a> in order to have a vegan leather option (but it's not required to use this datapack)."
abstract: "Plant-based alternatives for string, leather, beds, and feathers. Use together with <i>Acacia Gum</i> to have fully vegan leather."
priority: 4
index: 12
gallery: [images/vegancraft/ethical_textiles/thumbnail.png,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/359/16162473-advancements_l.webp]
---

## Downloads
Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.20+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.17–1.19.4</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.20+" tested="1.20--rc1" %}
            <br/>
            {% include dp_download.html version="v1.1" pmc-url="https://www.planetminecraft.com/data-pack/ethical-textiles-plant-string-and-leather/" github-url="TBR" rp-version="v1.0" rp-github-url="TBR" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.17–1.19.4" tested="1.17.1, 1.18.2, 1.19.2" %}
            <br/>
            {% include dp_download.html version="v1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/ethical_textiles_v1.zip" rp-version="v1d" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/vegancraft-RP_v1d.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

### New recipes

{% include comments/important.html content="These recipes will output a knowledge book, the knowledge book will convert automatically into the desired item once you click on it. If using the resourcepack, the knowledge book will display as a question mark named \"Custom Item\"." %}

#### Faux Leather

Crafted with 3 slime balls and either 3 of the following ingredients:
- Cactus
- Dark oak log or wood
- Bamboo block

or 6:
- Paper
- Dried kelp.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/leather.gif" alt="Faux leather recipes" align="center" width="300" %}

#### Rudimentary beds
**Beds** can be crafted with 3 wooden planks and 3 hay, or 6 jungle leaves or grass.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/bed.gif" alt="Rudimentary bed recipes" align="center" width="300" %}

#### Plant-based string
Vines, sugar cane, and dripleaves can be used to craft **string**. Use 4 of these strings to craft vegan "wool".

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/string.gif" alt="Plant string recipes" align="center" width="200" %}

#### Faux feathers
Craft faux **feathers** with a stick, two strings, and one of any leaves.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/recipes/feather.gif" alt="Faux Feather recipe" align="center" width="200" %}

#### Synthetic cobwebs
**Cobwebs** can be crafted with 8 strings and a slime ball.

### Custom textures
Faux leather and plant string have their own texture. Here they are compared to their vanilla counterparts:

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/texture_comparison.png" alt="Texture comparison" align="center" width="180" %}

The [Vegancraft Resourcepack](#downloads) is required to see these textures in-game.

{% include comments/important.html content="Due to the way I coded the recipes, sometimes the output will show the actual vanilla item. If you want the custom item name and texture, just change the position of any ingredient and the output will change to the knowledge book (a question mark, when using the resourcepack). I decided to do it this way so the the vanilla counterpart of the output shows up in the in-game recipe book, instead of having to remember what the recipes do. Here is an example, the recipe shows a vanilla bed, and changing the position of one ingredient outputs the custom item:" %}

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/swap_ingredients.gif" alt="Swapping the position of two ingredients will change the output to a knowledge book, if it was not already" align="center" width="300" %}

### Vegancraft

This is a standalone datapack, but was designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

As part of its integration on Vegancraft, this datapack includes the following additional features:

- A custom advancement tree.
- Some xp will be awarded when crafting faux leather, plant string, and faux feathers. For leather/feathers, the amount of xp is somewhat equivalent to what you would get by getting it the "regular" way (breeding and killing cows/chickens). For string, it is only 0.1 XP, since it's very easy to get.
- Vegan ingredients detection: the datapack will determine if you are using vegan ingredients or not when crafting these items, labelling them if they are not vegan. Vegan and non-vegan items do not stack.

{% include image/basic.html src="vegancraft/ethical_textiles/screenshots/slime_leather.png" alt="Faux leather with animal slime" align="center" width="200" %}

If, for any reason, you want to remove these features, you can use the command **<code>/function dnv.vegancraft:toggle</code>** to disable them. You can also use that command to turn them on again.

### Future features

In the future, I might consider:

- Improving the existing recipes and advancements.
- Improving the vegan advancement tree.

## Reasoning for the recipes

- Faux leather is based on real-world alternatives for leather, dark oak representing tree bark. Slime represents the plastic substances which are often used in their manufacture.
- Rudimentary beds: I just found it weird how in the early game you need to find sheep in order to sleep, and thought it would make sense to be able to craft beds with more rudimentary materials.
- String: since the most common real-world plants that produce fibers are not in the game (cotton, linen, flax...) I just decided to take the vanilla plants that looked more "stringy" and also sugar cane, because in-game it is already implied that it produces fiber since you make paper from it.
- Faux feathers can be crafted in real life using cloth or leaves. I decided to use leaves for this recipe since they already have a similar shape and can be used to craft arrows, whil using wool would make them very easy to get (since you can craft wool from string). The recipe represents leaves sewn together to a small stick in a feather-like shape.
- Since cobweb is rarely used in the game, I just added a simple recipe which represents strings covered in slime to make them sticky.
- I considered adding a recipe for rabbit hides but, since they are only used to craft bundles, which are not yet officially in the game, I didn't do it. If you want to craft bundles without killing rabbits, I suggest using [Vanilla Tweaks' Craftable Bundles (Leather)](https://vanillatweaks.net/picker/crafting-tweaks/){:target="_blank"} or my own [Scrap Leather](scrap_leather.html), which allows you to convert leather to rabbit hides.
- I didn't create a "vegan wool" item because of how many color variants there are and the difficult/cumbersome it would be to have a vegan variant for each one of them.

## Known issues and solutions
- As mentioned before, some recipes in the in-game recipe book will show the vanilla item instead of the custom one. This is on purpose since I think it's more clear and user-friendly to have the actual outputs show up in the recipe book. The recipes of the custom items are shapeless, so you can just change the position of any ingredient and the output will change to the custom item, which will convert to the custom item. You can also use this to your advantage if you already have vanilla items in your inventory and you want to stack on them instead of having custom items on a separate stack. However, this is not consistent and sometimes the custom item is the only possible output.
