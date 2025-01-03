---
title: Magnet Fishing
keywords: minecraft, datapack, fishing, iron, junk, scrap, vegan, veganism, pacifist
tags: [datapack, vegancraft, standalone, simple]
sidebar: home_sidebar
toc: true
last_updated: 03/Jan/2025
permalink: magnet_fishing.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/magnet-fishing/
first_release: ["16","Apr","2023"]
last_release: ["03","Jan","2025"]
logo: vegancraft/magnet_fishing/pack.png
thumbnail: vegancraft/magnet_fishing/thumbnail.png
intro: "A datapack that adds a magnet fishing rod, with which you can fish iron and iron items."
abstract: "Craft a magnet fishing rod and fish out iron and iron items from the water!"
priority: 3
index: 15
gallery: [images/vegancraft/magnet_fishing/thumbnail.png,images/vegancraft/magnet_fishing/screenshots/recipe.png,images/vegancraft/magnet_fishing/loot.png]
---

## Downloads
Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#1-21-4" data-toggle="tab">1.21.4</a></li>
    <li><a href="#1-21" data-toggle="tab">1.21–1.21.3</a></li>
    <li><a href="#1-20-5" data-toggle="tab">1.20.5–1.20.6</a></li>
    <li><a href="#legacy1-20" data-toggle="tab">1.20–1.20.4</a></li>
    <li><a href="#legacy" data-toggle="tab">1.19.4</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="1-21-4">
        <p>
            {% include dp_badges.html supports="1.21.4" tested="1.21.4" %}
            <br/>
            {% include dp_download.html version="v2.1" pmc-url="https://www.planetminecraft.com/data-pack/magnet-fishing/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.3/magnet_fishing_v2.1.zip" rp-version="v1.3" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.3/vegancraft-RP_v1.3.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-21">
        <p>
            {% include dp_badges.html supports="1.21–1.21.3" tested="1.21.3" %}
            <br/>
            {% include dp_download.html version="v2.0.2" pmc-url="https://www.planetminecraft.com/data-pack/magnet-fishing/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2.2/magnet_fishing_v2.0.2.zip" rp-version="v1.2.2, OPTIONAL" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2.2/vegancraft-RP_v1.2.2.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-20-5">
        <p>
            {% include dp_badges.html supports="1.20.5–1.20.6" tested="1.20.6" %}
            <br/>
            {% include dp_download.html version="v2.0" pmc-url="https://www.planetminecraft.com/data-pack/magnet-fishing/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.1-pre3/magnet_fishing_v2.0.zip" rp-version="v1.1, OPTIONAL" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.1-pre3/vegancraft-RP_v1.1.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy1-20">
        <p>
            {% include dp_badges.html supports="1.20–1.20.4" tested="1.20, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/magnet_fishing_v1.1.zip" rp-version="v1.0, OPTIONAL" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.19.4" tested="1.19.4" %}
            <br/>
            {% include dp_download.html version="v1" dropbox-url="https://www.dropbox.com/s/obs3ri4hgtfms7g/magnet_fishing_v1.zip?dl=1" rp-version="v1.0, OPTIONAL" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

### Crafting a magnet fishing rod

Craft a magnet rod with a regular **fishing rod**, an **iron ingot**, and **redstone dust**.

{% include comments/warning.html content="When crafting a magnet rod, <b>any enchantment that the regular fishing rod has will be lost!</b> A newly crafted magnet rod is always unenchanted." %}

{% include image/basic.html src="vegancraft/magnet_fishing/screenshots/recipe.png" alt="Magnet rod crafting recipe" align="center" width="300" %}

### Using the magnet rod

You can use the magnet rod just like you would use a regular fishing rod. The only difference is in the items that you will receive. You can find a list of the loot tables below. The **fishing enchantments** (*Lure* and *Luck of the sea*) **also work with this magnet rod**!

{% include image/basic.html src="vegancraft/magnet_fishing/screenshots/example.gif" alt="Example of the magnet rod being used" align="center" width="480" %}

{% include collapsible.html id="loot-list" title="List of loot items" content="<ul><li><b>Main catches</b>: raw iron (70%), iron ingot (20%), iron ore (10%).</li><li><b>Junk</b> (all items are damaged if possible): iron tools and weapons, chainmail armor, bucket, compass, chain, lantern, tripwire hook, rail, iron bars.</li><li><b>Treasure</b> (all items are damaged and enchanted if possible): Damaged anvil, iron armor, shield, iron tools and weapons, crossbow, bow, fishing rod, name tag.</li></ul><p align=center><img class=\"docimage\" src=\"images/vegancraft/magnet_fishing/loot.png\" alt=\"Loot items\" style=\"max-width:600px;\" /></p>" %}

**To repair a magnet fishing rod,**, combine it with any other fishing rod **in an anvil** (a crafting table won't work!).

<!-- ### Custom texture
The resourcepack (downloadable above) is **optional**. If not installed, the magnet rod will look just like a regular fishing rod but renamed. -->

### Vegancraft
This is a standalone datapack, but was originally designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features. Check out my *[Plant-based Foods](plant-based_foods.html)* datapack if you also want to cook fish substitutes, and some additional features.

{% include comments/tip.html content="Did you know? fishing is the number one cause for ocean pollution. Over 75% of the trash in the Great Pacific Garbage Patch is from fishing [theoceancleanup.com]. [Watch Seaspiracy](https://www.youtube.com/watch?v=1Q5CXN7soQg\){:target=\"_blank\"}" %}

## Special thanks

This datapack was originally created as a commission for Nora from the [Vegan Minecraft Server](https://veganminecraft.com/){:target="_blank"}.
