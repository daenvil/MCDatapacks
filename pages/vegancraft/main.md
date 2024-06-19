---
title: Daenvil's Vegancraft
keywords: minecraft, datapack, baking, cooking, food, vegan, veganism, plant-based, pacifist, brewing
tags: [datapack, vegancraft, collection, crafting, food, info]
sidebar: home_sidebar
toc: true
last_updated: 19/Jun/2024
permalink: vegancraft.html
published: true
github: https://github.com/daenvil/vegancraft
pmc-collection: https://www.planetminecraft.com/collection/162672/daenvil-s-vegancraft/
first_release: ["17","Jun","2022"]
last_release: ["19","Jun","2024"]
logo: vegancraft/pack.png
intro: "Vegancraft is a semi-modular datapack which makes a vegan gamestyle possible in a vanilla-like way without missing any game features. Tired of killing cows to make books and item frames? Tired of using sheep to make beds? This datapack is for you.<br/><br/>You can either download the full thing as a single datapack or <a href=#features>download some single features as individual datapacks</a>."
abstract: "A merged version of every Vegancraft datapack, plus some additional features. Makes a vegan gamestyle possible in a vanilla-like way without missing any game features."
index: 16
---

## Full datapack download

Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#1-21" data-toggle="tab">1.21+</a></li>
    <li><a href="#1-20-5" data-toggle="tab">1.20.5–1.20.6</a></li>
    <li><a href="#legacy1-20" data-toggle="tab">1.20–1.20.4</a></li>
    <li><a href="#legacy" data-toggle="tab">1.19.x</a></li>
    <li><a href="#legacy2" data-toggle="tab">1.17–1.18.2</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="1-21">
        <p>
            {% include dp_badges.html supports="1.21+" tested="1.21" %}
            <br/>
            {% include dp_download.html version="v1.2" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2/vegancraft-DP_v1.2.zip" rp-version="v1.2" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2/vegancraft-RP_v1.2.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-20-5">
        <p>
            {% include dp_badges.html supports="1.20.5–1.20.6" tested="1.20.6" %}
            <br/>
            {% include dp_download.html version="v1.2" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2/vegancraft-DP_v1.2-MC1.20.5-1.20.6.zip" rp-version="v1.2" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.2/vegancraft-RP_v1.2.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy1-20">
        <p>
            {% include dp_badges.html supports="1.20–1.20.4" tested="1.20, 1.20.4" %}
            <br/>
            {% include dp_download.html version="v1.0.1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0.1/vegancraft-DP_v1.0.1.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.19.x" tested="1.19.3" %}
            <br/>
            {% include dp_download.html version="v1e" github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/vegancraft-DP_v1e.zip" rp-version="v1e" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/vegancraft-RP_v1e.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy2">
        <p>
            {% include dp_badges.html supports="1.17--1.18.2" tested="1.17.1%2C%201.18.2" %}
            <br/>
            {% include dp_download.html version="v1d-mc1.17-1.18.2" github-url="https://github.com/daenvil/vegancraft/releases/download/v1d-mc1.17-1.18.2/vegancraft-DP_v1d-mc1.17-1.18.2.zip" rp-version="v1d" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1d-mc1.17-1.18.2/vegancraft-RP_v1d.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="Both datapack and resourcepack were tested on the mentioned versions; and also on multiplayer." %}
{% include installation.html resourcepack=true %}

## Features
This datapack aims to make any vanilla feature available without hurting or using any mob. Some of the features are also available as individual datapacks, which are listed below. Check their individual pages to see their features.

<div class="row">
    <div class="col-lg-12">
        <h3 class="page-header">Included datapacks</h3>
    </div>
    {% assign sorted_pages = site.pages | sort: 'index' %}
    {% for page in sorted_pages %}
    {% if page.tags contains "vegancraft" %}
    {% if page.tags contains "datapack" %}
    {% if page.tags contains "standalone" %}
    <div class="col-md-4 col-sm-6">
        <div class="panel panel-default text-center">
            <div class="panel-heading">
                {% if page.thumbnail %}
                {% capture var_thumbnail %}
                images/{{page.thumbnail}}
                {% endcapture %}
                {% include image/basic.html full-src=var_thumbnail align='center' style='max-width:100%;' %}
                {% elsif page.logo %}
                {% capture var_logo %}
                images/{{page.logo}}
                {% endcapture %}
                {% include image/basic.html full-src=var_logo align='center' style='max-width:100%;' nn=true %}
                {% endif %}
            </div>
            <div class="panel-body">
                <p style="font-size:18px;color:#587545;"><b><i>{{page.title}}</i></b></p>
                <p>{{page.abstract}}</p>
                <a href="{{page.permalink}}" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>
    {% endif %}
    {% endif %}
    {% endif %}
    {% endfor %}
</div>

***

### Exclusive features

The following features are not available as standalone datapacks and are exclusive to this full version.

#### Vegan Brewing

A ton of new items are added as alternatives for animal-based brewing ingredients. 

- **Blazing Powder**: an alternative to blaze powder. Crafted using a magma block and 4 glowstone dust.
- **Blazing Rod**: an alternative to blaze rods. Crafted using a lightning rod and 2 blazing powder.
- **Breezy Rod**: an alternative to breeze rods. Crafted using a blaze rod and dragon's breath.
- **Gunpowder** is craftable from any coal + redstone + glowstone dust.
- **Poisonous Sprout**: an alternative to spider eyes. Crafted from poisonous potatoes.
- **Fermented Sprout**: an alternative to fermented spider eyes. Crafted in the same way but from poisonous sprouts.
- **Hardened Seagrass**: an alternative to turtle scutes. Crafted from seagrass and wax.
- **End's Mist**: an alternative to dragon's breath. Crafted from a bottle o' enchanting, blazing powder, and a chorus flower.
- **Bouncy Boot**: an alternative to rabbit's feet. Crafted from leather boots surrounded by slimeballs (or acacia gum).
- **Puffer Bubble**: an alternative to pufferfish. Crafted from a heart of the sea and soul sand.
- **Feathery Membrane**: an alternative to phantom membranes. Crafted from feathers and wax.

Sniffer plants also drop some brewing ingredients, including a ghast tear alternative, see [Sniffer Plants](#sniffer-plants) for details.

Other animal brewing ingredients can already be obtained in a vegan way through other features:
- Magma cream and slime blocks by substituting slime balls with acacia gum.
- Synthetic cobwebs can be crafted using acacia gum and plant string.

#### XP from farming plants

A new feature that rewards players with experience for farming crops. Just as killing and breeding animals gives XP, this datapack makes it so harvesting plants also drops XP.

- Each plant has a certain chance to drop 1 XP. This chance is calculated based on how hard it is to reproduce and grow the plant and was balanced to be as equivalent as possible to farming animals.
  - Certain plants do not drop any XP, either because of how easy they are to produce & harvest or because of other balance concerns. These are: bamboo, flowers, dripleaves, seagrass, vines, melons, and pumpkins. Mushrooms also are also not included for this reason. As for trees, breaking their leaves manually is the only way to obtain XP from them.
- XP is only dropped when a player breaks the block. It's not dropped if the block is broken by explosions, pistons, etc.
  - In the case of sweet and glow berries, XP is also obtained by harvesting them with right click.
  - Only the block mentioned above drops XP, not any other block in the plant. For example, breaking a chorus plant does not drop XP, only directly breaking the flower does so.
  - Cactus and sugar cane do not currently drop any XP because of a bug in the game related to their block states. They will work correctly when Mojang fixes that bug.
  - (Vegancraft only) In the case of sniffer plants (torchflower and pitcher plant), they will not drop XP from harvesting the plant with silk touch or shears. They will only do so if broken with any other tool.
- XP is NOT dropped from player-placed blocks. Some plants, like kelp or chorus flowers, are planted by placing the block, but they will only drop XP after they have grown. In summary: **you can't farm XP by repeteadly placing and breaking the same block**, you will have to at least wait for the plant to grow.
- To prevent exploiting this mechanic by using fast semi-automatic farms or spamming bone meal, **if a player gains a lot of XP in a small period of time, the chances for XP to drop will decrease for that player** until enough time has passed. The chances start decreasing at 200 gained XP and will drop to zero at 600 XP; from there, it will take ~6 minutes for the chances to recover their regular values. This system would cap at 64 XP/minute in an ideal ultra-fast farm (probably lower in a real case), which is still lower than most mob farms.

{% include image/figure.html src='vegancraft/xp_per_crop.png' align='center' style='max-width:100%;' caption='Chance that each crop has to drop 1 XP. Note that XP is only dropped when a block is directly broken by a player.'%}

#### Copper Horns

Same as the goat horn, just a different texture and way of obtaining.

- A horn with the "ponder" sound can be crafted using copper ingots and wax.
- All the other sounds are made in the smithing table, by combining an existing horn with a trim smithing template and a copper ingot. Each sound comes from different templates:
  - "ponder": from trim templates: "wayfinder", "raiser", "shaper", "host"
  - "sing": from trim templates: "coast", "dune"
  - "seek": from trim templates: "sentry", "vex"
  - "feel": from trim template: "wild"
  - "admire": from trim templates: "ward", "silence"
  - "call": from trim templates: "eye", "spire"
  - "yearn": from trim template: "snout"
  - "dream": from trim template: "rib"

#### Inks and Dyes

Some dyes are usually obtained from mobs, this adds alternative sources for them. Ink sacs are the only way of making signs glow/not glow, so alternative recipes for them were also added.

- **Black dye** is craftable from any coal.
- **Ink sacs** are craftable from black dye.
- A **book and pencil** (same as a "book and quill") is craftable using a book, a stick, and any coal.
- **Black and white dyes** are craftable from dark oak and birch logs/wood, respectively, by using the stonecutter (this simulates grinding their bark).
- **Glow ink sacs** are craftable from glowstone dust, glow berries, or glow lichen.
- **Glow item frames** are craftable by using glowstone dust, glow berries, or glow lichen instead of a glow ink sac.

#### Mob heads

Some heads, like creeper and wither skeleton heads are used for banner patterns and for fireworks, so alternatives for them were needed. Since there also are more mob heads which can be used on note block, I added all of them:

- Most heads are crafted from a carved pumpkin surrounded by dyes and items related to the mob:
  - **Creeper head**: carved pumpkin surrounded by green dyes and gunpowder (see the brewing section for vegan gunpowder).
  - **Skeleton skull**: carved pumpkin surrounded by white dyes and bone blocks.
  - **Zombie head**: carved pumpkin surrounded by fermented spider eyes (see the brewing section for alternatives to spider eyes).
- Then, the heads from the harder mobs are made using a template so you have to actually go to the mobs' locations and face some challenge:
  - **Piglin head**: carved pumpkin + pink dye + nether gold ore + either the "snout" trim smithing template or the piglin banner pattern.
  - **Wither skeleton skull**: skeleton skull + black dye + netherite ingot + "rib" trim smithing template

#### Froglights

Froglights are craftable with a shroomlight block, prismarine crystals, and a dye related to the froglight color:

- Yellow dye: ochre froglight
- Magenta dye: pearlescent froglight
- Green dye: verdant froglight

A shroomlight is used due to it being an organic glowing block like the froglight and also being obtained in the nether. Prismarine crystals are used because of their relation to water and the more crystaline look of froglights.

#### New banner patterns

There are two new banner patterns available in the loom:

- The "sprout" pattern (🌱), which requires the flower charge pattern (craftable with flowers).
- The "circled V" pattern (ⓥ), which requires the globe pattern (obtained from cartographer villagers).

These do not replace any vanilla patterns, they are just extras.

#### Sniffer Plants

- Torchflower and pitcher seeds are obtainable in ocean ruins from brushing suspicious sand and gravel, respectively. These replace the wooden hoe in these blocks' loot tables so, whenever you would get a wooden hoe (2/15 chance), you get a sniffer seed instead.
 - Sniffer seeds are also farmable: when breaking a fully grown torchflower or pitcher plant, they will drop 1–2 of their seeds instead of dropping themselves (increased with Fortune enchantment). You can still collect the plant itself by using shears or any tool with silk touch*. In addition:
   - Torchflowers have a small chance to drop **blazing powder** (see brewing section).
   - Pitcher plants have a small chance to drop "**pitcher fluid drops**" (a ghast tear alternative). 

{% include comments/warning.html content="due to how pitcher plants are made, you will need to break the <b>lower half of the plant</b> with shears or silk touch in order to obtain the plant itself. Breaking the upper half of the plant will result in the regular drops (seeds)." %}

#### Other recipes

The following recipes are experimental and some of them will probably change in future updates due to balance concerns:

- Prismarine shard: from smelting amethyst shards
- Prismarine crystals: from smelting prismarine shards
- Trident: 3 diamonds swords, a blaze rod, and 3 prismarine crystals
- Totem of undying: 1 gold block, 2 emeralds, and 1 echo shard
- Wither rose: 4 wither roses from a rose bush, a netherite ingot, and a soul sand or soil block
- Nether star: a netherite block surrounded by 4 diamonds and 4 blaze powder
- Ender pearl: a chorus fruit + an emerald
- Shulker box: a chest surrounded by 4 ender pearls and 4 popped chorus fruits

### Resourcepack

Most of these features contain custom textures and item names. The Vegancraft resourcepack is needed in order to view them properly. For simplicity, this resourcepack is also the same for all sub-datapacks, and is available on the [Downloads](#full-datapack-download) section or in the page of any single datapack that uses it.

## Future Features
Planned features that may arrive in future versions...

### Pacifist story progression

In the future, non-violent ways to progress in the "story" of Minecraft (i.e. beating the bosses and going to the End) will be added. Or at least alternatives for their related items will be added, like nether stars, wither roses, shulker shells, etc.

## Contributing

If you wish to contribute in any way to the development of Vegancraft, you can [contact me](contact.html) on any platform, I will gladly welcome feature suggestions or even collaborators.

You can also [create an issue](https://github.com/daenvil/vegancraft/issues/new/choose){:target="_blank"} on this project's GitHub repository for bug reports, feature requests, contributions, or any question you may have.

### Translations

If you wish to translate this datapack to your language(s) (or fix any already existing one), just use the "lang" files you can find inside the resorcepack as template, and send your version to me either via a pull request or an issue. I will credit you as translator on here, on the corresponding datapacks' PlanetMinecraft pages, and on the README file of the resourcepack.