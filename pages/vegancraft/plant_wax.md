---
title: Plant Wax
keywords: minecraft, datapack, vegan, veganism, plant-based, pacifist, bees, honeycomb, wax, candles
tags: [datapack, vegancraft, standalone, crafting, simple]
sidebar: home_sidebar
toc: true
last_updated: 08/Nov/2024
permalink: plant_wax.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/plant-wax/
first_release: ["15","Dec","2022"]
last_release: ["08","Nov","2024"]
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
    <li class="active"><a href="#1-21" data-toggle="tab">1.21–1.21.3</a></li>
    <li><a href="#1-20-5" data-toggle="tab">1.20.5–1.20.6</a></li>
    <li><a href="#legacy1-20" data-toggle="tab">1.20–1.20.4</a></li>
    <li><a href="#legacy" data-toggle="tab">1.18–1.19.4</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="1-21">
        <p>
            {% include dp_badges.html supports="1.21–1.21.3" tested="1.21.3" %}
            <br/>
            {% include dp_download.html version="v2.0.2" pmc-url="https://www.planetminecraft.com/data-pack/plant-wax/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2.2/plant_wax_v2.0.2.zip" rp-version="v1.2.2" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2.2/vegancraft-RP_v1.2.2.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-20-5">
        <p>
            {% include dp_badges.html supports="1.20.5–1.20.6" tested="1.20.6" %}
            <br/>
            {% include dp_download.html version="v2.0" pmc-url="https://www.planetminecraft.com/data-pack/plant-wax/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.1-pre2/plant_wax_v2.0.zip" rp-version="v1.1" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.1-pre2/vegancraft-RP_v1.1.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy1-20">
        <p>
            {% include dp_badges.html supports="1.20–1.20.4" tested="1.20, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/plant_wax_v1.1.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" discontinued=true %}
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

### Vegancraft

This is a standalone datapack, but was designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

When playing using the full Vegancraft datapack instead of the standalone Plant-based Foods datapack, the following features are enabled:

- Some custom advancements.

## Reasoning for the recipes

- In general, I tried to find recipes that have an analogue in real life and that I think are balanced in the game. Both recipes need shears to obtain the needed ingredient, same as to obtain honeycomb, and they force you to find certain biomes in order to get wax.
- The dead bush recipe is based on certain real-life bushes found in hot biomes –mainly [candelilla wax](https://en.wikipedia.org/wiki/Candelilla_wax)– whose leaves produce wax. Since dead bushes are not renewable and primarily appear in deserts, I thought this was appropiate and balanced.
- The jungle leaves recipe is based on certain real-life tropical trees –mainly [palm wax](https://en.wikipedia.org/wiki/Carnauba_wax)– whose leaves produce wax. Jungle leaves are renewable, but they are quite a pain to farm, so I thought they are still balanced.
- In both these cases, as far as I know, the wax is extracted heating the leaves (either drying them or boiling them), hence why I implemented them as furnace recipes.
