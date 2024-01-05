---
title: Plant Wax
keywords: minecraft, datapack, vegan, veganism, plant-based, pacifist, bees, honeycomb, wax, candles
tags: [datapack, vegancraft, standalone, crafting, simple]
sidebar: home_sidebar
toc: true
last_updated: 05/Jan/2024
permalink: plant_wax.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/plant-wax/
first_release: ["15","Dec","2022"]
last_release: ["05","Jun","2023"]
logo: vegancraft/plant_wax/pack.png
thumbnail: vegancraft/plant_wax/thumbnail.png
intro: "A datapack that adds Plant Wax (a retextured honeycomb), obtainable by smelting dead bushes or jungle leaves."
abstract: "A plant-based alternative for honeycomb. Wax copper and craft candles without using bees!"
priority: 3
index: 14
gallery: [images/vegancraft/plant_wax/thumbnail.png]
---

## Downloads
Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.20+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.18–1.19.4</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.20+" tested="1.20, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.1" pmc-url="https://www.planetminecraft.com/data-pack/plant-wax/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/plant_wax_v1.1.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.18–1.19.4" tested="1.18.2, 1.19.3" %}
            <br/>
            {% include dp_download.html version="v1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/plant_wax_v1.zip" rp-version="v1e" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/vegancraft-RP_v1e.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

### New smelting recipe: Plant Wax

You can obtain Plant Wax by smelting **Jungle Leaves** or **Dead Bushes** in a regular furnace (does not work in blast furnaces and smokers).

This recipe needs 10 seconds to cook (same as any other furnace recipe), and provides 0.1 xp.

<p align=center>
{% include image/basic.html src="vegancraft/plant_wax/screenshots/jungle_wax.png" alt="Wax from jungle leaves" width="280" %}
{% include image/basic.html src="vegancraft/plant_wax/screenshots/bush_wax.png" alt="Wax from dead bushes" width="280" %}
</p>
{% include comments/important.html content='The [Vegancraft Resourcepack](#downloads) is required to see this texture in-game.' %}

### Uninstallation

Since this datapack uses permanent marker entities and scheduled functions, an uninstall function is available through the command `/function dnv.plant_wax:uninstall`, in case you want to stop using this datapack. Using this command will kill all entity markers, scheduled functions, and scoreboards used by this datapack. Use this function before deleting the datapack files, so no unused stuff remains in your world.

### Vegancraft

This is a standalone datapack, but was designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

As part of its integration on Vegancraft, this datapack includes the following additional features:

- A custom advancement tree.

If, for any reason, you want to remove these features, you can use the command **<code>/function dnv.vegancraft:toggle</code>** to disable them. You can also use that command to turn them on again.

## Reasoning for the recipes

- In general, I tried to find recipes that have an analogue in real life and that I think are balanced in the game. Both recipes need shears to obtain the needed ingredient, same as to obtain honeycomb, and they force you to find certain biomes in order to get wax.
- The dead bush recipe is based on certain real-life bushes found in hot biomes –mainly [candelilla wax](https://en.wikipedia.org/wiki/Candelilla_wax)– whose leaves produce wax. Since dead bushes are not renewable and primarily appear in deserts, I thought this was appropiate and balanced.
- The jungle leaves recipe is based on certain real-life tropical trees –mainly [palm wax](https://en.wikipedia.org/wiki/Carnauba_wax)– whose leaves produce wax. Jungle leaves are renewable, but they are quite a pain to farm, so I thought they are still balanced.
- In both these cases, as far as I know, the wax is extracted heating the leaves (either drying them or boiling them), hence why I implemented them as furnace recipes.

## Known issues and solutions
- These custom smelting recipes are implemented through a system of marker entities placed on each furnace. If you detect that one of these recipes is not working, try simply placing the furnace again (this never happened in the testing process, though). The performance of this system was stress-tested by using 100 furnaces simultaneously with these custom recipes, and no noticeable performance losses were found.
