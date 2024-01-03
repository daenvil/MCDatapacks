---
title: Better Stonecutter
keywords: minecraft, datapack
tags: [datapack, recyclecraft, standalone, QoL, crafting]
sidebar: home_sidebar
toc: true
last_updated: 03/Jan/2024
permalink: better_stonecutter.html
published: true
pmc: https://www.planetminecraft.com/data-pack/better-stonecutter-5432526/
first_release: ["05","Jan","2022"]
last_release: ["27","Mar","2023"]
logo: recyclecraft/better_stonecutter/pack.png
intro: "A datapack that adds more recipes to the stonecutter, allowing you to change more easily between block variants and waste less resources."
abstract: "Adds more recipes to the stonecutter, allowing you to change more easily between block variants and waste less resources."
priority: 3
index: 4
downloads: 3834
downloads_str: "&gt;3.8k"
thumbnail: recyclecraft/better_stonecutter/thumbnail.png
gallery: [images/recyclecraft/better_stonecutter/thumbnail.png,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262629-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262638-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262628-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2023/526/16630269_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262630-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262552-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262637-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262633-screenshot-at_l.webp,https://static.planetminecraft.com/files/image/minecraft/data-pack/2022/526/15262632-screenshot-at_l.webp]
---

## Downloads

Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.19+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.17–1.18.2</a></li>
    <li><a href="#legacy2" data-toggle="tab">1.16.x</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.19%2B" tested="1.19.4, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.1.2" pmc-url="https://www.planetminecraft.com/data-pack/better-stonecutter-5432526/download/file/16628279/" dropbox-url="https://www.dropbox.com/s/llacu0cs85nwtkh/better_stonecutter_v1.1.2.zip?dl=1" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.17–1.18.2" tested="1.17.1%2C%201.18.2" %}
            <br/>
            {% include dp_download.html version="v1.0.1-mc1.17-1.18.2" dropbox-url="https://www.dropbox.com/s/xk0alnifv4phlqj/better_stonecutter_v1.0.1-mc1.17-1.18.2.zip?dl=1" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy2">
        <p>
            {% include dp_badges.html supports="1.16.x" tested="1.16.5" %}
            <br/>
            {% include dp_download.html version="v1-mc1.16.x" dropbox-url="https://www.dropbox.com/s/13yvc3a8txfhs0u/better_stonecutter_v1-mc1.16.x.zip?dl=1" discontinued=true %}
        </p>
    </div>
</div>

{% include installation.html %}

## Features

Products of stonecutting are given recipes so they can be cut again into smaller or equal-size items (for example, stairs into slabs).

- Some items can now be obtained through stonecutting:
    - Stone/blackstone &#x21D2; pressure plates, buttons
    - Nether Bricks &#x21D2; Nether Brick fence, Nether brick
    - Quartz &#x21D2; Nether quartz
    - Sandstone &#x21D2; sand
    - Copper &#x21D2; copper ingots
    - Iron &#x21D2; doors, pressure plates, iron bars, iron ingots
    - Gold &#x21D2; pressure plates, gold ingots
    - Prismarine &#x21D2; prismarine shards
    - Amethyst blocks or clusters &#x21D2; amethyst shards
    - Mud bricks &#x21D2; Packed mud
  
{% include comments/important.html content='Some of these recipes alter the vanilla balance by adding new ways to obtain certain items (for example, sand from sandstone or amethyst shards from blocks). I added them because I thought it made sense, but if you don\'t like it, it\'s possible to remove these recipes by simply going into the datapack\'s <code>data/dnv.recyclecraft/recipes/stonecutter/</code> folder and removing the recipes that you don\'t want (they are organized in subfolders, so it is easy to identify them and bulk-remove them).' %}

- You can switch between stone types (and their products) more easily:
    - Stone can be cut into: smooth stone, stone bricks, cobblestone
    - Stone bricks can be cut into cobblestone
    - Mossy cobblestone can be cut into cobblestone
    - Mossy stone bricks can be cut into: mossy cobblestone, regular stone bricks, cobblestone
    - Smooth and polished variants can be cut into their regular counterparts
    - Prismarine bricks can be cut into prismarine
    - Cracked brick variants can be obtained from their regular counterparts
    - Deepslate can be cut into all deepslate variants (*deepslate doesn't make much sense right now but it is how they decided to do it in vanilla for some reason, at least now you can use full deepslate in the stonecutter, instead of having to manually mine it for its cobbled variant*)

- To avoid flooding the stonecutter UI, some blocks with a lot of variants (deepslate, stone, blackstone) are not given all possible recipes directly. Instead, they are only given the recipes for the smaller blocks of the same variant and the equivalent blocks of other variants, which you can cut then into smaller blocks if desired.

- Copper can be deoxidized and dewaxed with the stonecutter. Copper blocks can be cut into 5 stairs instead of 4, which makes more sense.

## Considerations

- As noted above, this datapack might make it easier to obtain certain types of blocks, but you have the option to remove those recipes manually.
- The recipes were designed taking into account [Vanilla Tweak's _Back to Blocks_ datapack](https://vanillatweaks.net/picker/crafting-tweaks/){:target="_blank"}, I recommend using that datapack along with this one to make the most efficient use of blocks.
- The [_Cuttable Wood_](cuttable_wood.html) datapack extends this same philosophy to wooden blocks. I recommend using them together.
