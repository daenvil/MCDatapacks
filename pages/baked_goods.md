---
title: Daenvil's Baked Goods (TBR)
keywords: minecraft, datapack, baking, cooking, food
tags: [datapack, resourcepacks, standalone, crafting, food]
sidebar: home_sidebar
toc: true
last_updated: 07/Nov/2022
permalink: baked_goods.html
published: true
pmc: https://www.planetminecraft.com/data-pack/daenvil-s-baked-goods/
first_release: ["10","Nov","2022"]
last_release: ["10","Nov","2022"]
logo: baked_goods/pack.png
thumbnail: baked_goods/thumbnail.png
intro: A datapack which adds new pies, cakes, cookies, and other baked goods to Minecraft. Bake apple pies, chocolate cakes, glow berry cookies, and many more! See <a href="#new-recipes">below</a> for the full list of recipes. Foods with golden apples/carrots/melon, chorus fruit, and glow berries provide <a href="#special-effects">special effects</a> when eating them.
abstract: "Adds 25 new baked goods to Minecraft, including apple pies, chocolate cakes, berry cookies, and many more."
priority: 0
index: 13
gallery: [images/baked_goods/thumbnail.png,images/baked_goods/screenshots/carrot_cakes.png,images/baked_goods/screenshots/golden_carrot_cakes.png,images/baked_goods/screenshots/chocolate_cakes.png]
TBR: true
---

## Downloads
![Minecraft supported versions](https://img.shields.io/badge/supported%20MC%20versions-1.19%2B-green?style=flat-square)
![Tested versions](https://img.shields.io/badge/tested%20in-1.19.2-informational?style=flat-square)

{% include dp_download.html version="TBR" mirror-url="TBR" mirror-platform="TBR" rp-version="TBR" rp-mirror-url="TBR" rp-mirror-platform="TBR" %}

{% include installation.html resourcepack=true %}

## Features

{% capture var_pmc_url %}{{page.pmc}}{% endcapture %}
{% include comments/important.html content='Remember you need to install and load the resourcepack (download above) in order to see the custom textures.' align='center' %}

{% include image/basic.html src='baked_goods/screenshots/all_items.png' align='center' caption='All the new foods added by this datapack' %}

### New recipes

{% include comments/important.html content="These recipes will output a knowledge book, the knowledge book will convert automatically into the desired item once you click on it. ***Not compatible with recipe unlockers***." %}
{% include comments/tip.html content="All these recipes are unshaped, you don't need to put the ingredients in the same order as shown here." %}

#### <ins>Egg-based pies</ins>
_<ins>Base ingredients: wheat + sugar + egg</ins>_

All egg-based pies are crafted with the **base ingredients plus 2 of their main ingredient**, and provide the same hunger/saturation as a pumpkin pie, unless stated otherwise in the recipe list below.

- **Carrot pie**: _base ingredients + **2 carrots**_.
- **Golden carrot pie**: _base ingredients + **2 golden carrots**_. Provides a total of 6.5 {% include image/drumstick.html %} drumsticks and 14.8 saturation, and [special effects\*](#golden-carrot-foods).
- **Sweet berry pie**: _base ingredients + **2 sweet berries**_.
- **Glow berry pie**: _base ingredients + **2 glow berries**_. Provides [special effects\*](#glow-berry-foods).
- **Melon pie**: _base ingredients + **2 melon slices**_.
- **Glistering melon pie**: _base ingredients + **2 glistering melon slices**_. Provides [special effects\*](#glistering-melon-pie).
- **Cream pie**: _base ingredients + **2 milk buckets**_. Provides a total of 5 {% include image/drumstick.html %} drumsticks and 8.8 saturation.


<p align=center>
{% include image/basic.html src='baked_goods/textures/carrot_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/golden_carrot_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/sweet_berry_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/glow_berry_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/melon_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/glistering_melon_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/cream_pie.png' width='32' nn=true %}
</p>
{% include image/basic.html src='baked_goods/screenshots/egg-based_pies.gif' alt='Egg-based pies recipes' align='center' width='300' nn=true %}
<p align=center style="color:gray;"><i>Textures and recipes for the new "egg-based" pies</i></p>

#### <ins>Simple pies</ins>
_<ins>Base ingredients: wheat + sugar</ins>_

All simple pies, with the exception of the mushroom pie, are crafted with the **base ingredients plus 1 of their main ingredient**, and provide the same hunger/saturation as a pumpkin pie, unless stated otherwise in the recipe list below.


- **Apple pie**: _base ingredients + **1 apple**_. 
- **Golden apple pie**: _base ingredients + **1 golden apple**_. Provides a total of 5 {% include image/drumstick.html %} drumsticks and 8.8 saturation, and [special effects\*](#golden-apple-pies).
- **Enchanted golden apple pie**: _base ingredients + **1 enchanted golden apple**_. Provides a total of 5 {% include image/drumstick.html %} drumsticks and 8.8 saturation, and [special effects\*](#golden-apple-pies).
- **Chorus fruit pie**: _base ingredients + **1 <ins>popped</ins> chorus fruit**_. Provides [special effects\*](#chorus-fruit-pie).
- **Mushroom pie**: _**wheat** + **2 red or brown mushrooms**_. Provides a total of 5 {% include image/drumstick.html %} drumsticks and 8.8 saturation.

<p align=center>
{% include image/basic.html src='baked_goods/textures/apple_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/golden_apple_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/chorus_fruit_pie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/mushroom_pie.png' width='32' nn=true %}
</p>
{% include image/basic.html src='baked_goods/screenshots/simple_pies.gif' alt='Simple pies recipes' align='center' width='300' nn=true %}
<p align=center style="color:gray;"><i>Textures and recipes for the new "simple" pies</i></p>

#### <ins>Cakes</ins>
_<ins>Base ingredients: 3 wheat + 1 sugar + 1 milk + 1 egg</ins>_

All cakes are crafted with the **base ingredients plus 3 of their main ingredient**. These cakes have custom 3D models and can be placed and eaten as regular cakes! They provide the same hunger/saturation as regular cake, unless stated otherwise in the recipe list below.

- **Carrot cake**: _base ingredients + **3 carrots**_.
- **Golden carrot cake**: _base ingredients + **3 golden carrots**_. Each slice provides a total of 2.5 {% include image/drumstick.html %} drumsticks and 6.4 saturation, and [special effects\*](#golden-carrot-foods).
- **Chocolate cake**: _base ingredients + **3 cocoa beans**_.

<p align=center>
{% include image/basic.html src='baked_goods/textures/carrot_cake.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/golden_carrot_cake.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/chocolate_cake.png' width='32' nn=true %}
</p>
<p align=center>
{% include image/basic.html src='baked_goods/screenshots/all_cakes.png' alt='Screenshot of the three new cakes' width='300' %}
{% include image/basic.html src='baked_goods/screenshots/cakes.gif' alt='Cake recipes' width='300' nn=true %}
</p>
<p align=center style="color:gray;"><i>Textures, models, and recipes for the new cakes</i></p>

#### <ins>Cookies and breads</ins>

All cookies and breads are crafted with **2 wheat plus 1 of their main ingredient**, and provide the same hunger/saturation as regular cookies and bread, except stated otherwise in the recipe list below.

- **Sugar cookies**: _2 wheat + **1 sugar**_.
- **Sweet berry cookies**: _2 wheat + **1 sweet berries**_.
- **Glow berry cookies**: _2 wheat + **1 glow berries**_. Provides [special effects\*](#glow-berry-foods).
- **Carrot bread**: _2 wheat + **1 carrot**_.
- **Golden carrot bread**: _2 wheat + **1 golden carrot**_. Provides a total of 4.5 {% include image/drumstick.html %} drumsticks and 14 saturation, and [special effects\*](#golden-carrot-foods).
- **Pumpkin bread**: _2 wheat + **1 pumpkin**_.

<p align=center>
{% include image/basic.html src='baked_goods/textures/sugar_cookie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/sweet_berry_cookie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/glow_berry_cookie.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/carrot_bread.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/golden_carrot_bread.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/pumpkin_bread.png' width='32' nn=true %}
</p>
{% include image/basic.html src='baked_goods/screenshots/cookies_and_breads.gif' alt='Cookies and bread recipes' align='center' width='300' nn=true %}
<p align=center style="color:gray;"><i>Textures and recipes for the new cookies and breads</i></p>

#### <ins>Others</ins>

These other recipes all provide the same hunger/saturation as pumpkin pie, unless stated otherwise in the recipe list below.

- **Sponge cake**: _wheat + sugar + 2 eggs_.
- **Cocoa sponge cake**: _wheat + sugar + egg + cocoa beans_.
- **Custard tart**: _wheat + sugar + egg + milk bucket_. Provides a total of 4.5 {% include image/drumstick.html %} drumsticks and 6.8 saturation.
- **Mushroom quiche**: _wheat + egg + milk bucket + 2 red or brown mushrooms_. Provides a total of 5.5 {% include image/drumstick.html %} drumsticks and 10.8 saturation.

<p align=center>
{% include image/basic.html src='baked_goods/textures/sponge_cake.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/cocoa_sponge_cake.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/custard_tart.png' width='32' nn=true %}
{% include image/basic.html src='baked_goods/textures/mushroom_quiche.png' width='32' nn=true %}
</p>
{% include image/basic.html src='baked_goods/screenshots/others.gif' alt='Other recipes' align='center' width='300' nn=true %}
<p align=center style="color:gray;"><i>Textures and recipes for the other new foods</i></p>

### Special effects

Some foods containing special ingredients provide unique effects related to these ingredients.

#### <ins>Golden carrot foods</ins>

Golden carrot foods provide **night vision** for a certain amount of time:

- Golden carrot bread: 1 minute
- Golden carrot pie: 2 minutes
- Golden carrot cake: 3 minutes (same as a Potion of Night Vision)

#### <ins>Golden apple pies</ins>

Eating a golden apple pie provides a **slightly improved version of the effects of eating a golden apple**: Absorption II for 2 minutes and Regeneration II for 10 seconds.

In the same vein, eating an enchanted golden apple pie provides a **slightly improved version of eating an enchanted golden apple**: Absorption V for 2 minutes, Regeneration II for 1 minute, Fire Resistance I for 5 minutes, and Resistance I for 5 minutes.

#### <ins>Glistering melon pie</ins>

Eating a glistering melon pie provides **2 hearts of instant health** (same as a Potion of Healing).

#### <ins>Glow berry foods</ins>

Glow berry foods **end the Darkness effect** and provide **night vision** for a short time (5 seconds for cookies and 20 seconds for pies).

#### <ins>Chorus fruit pie</ins>

When eating a chorus fruit pie, you will be **teleported randomly within 32 blocks**, as if you just ate a chorus fruit (with four times more range). In addition, it has some interactions with endermen:

- When holding a chorus fruit pie on any hand, nearby endermen are attracted to it, having a chance of teleporting near you.
- When eating a chorus fruit pie near endermen (<64 blocks), they may become angry towards you.

### Vegancraft compatibility

This datapack was made to be compatible with my _[Plant-based Foods](plant-based_foods.html)_ datapack. As such, **you will be able to replace eggs with wheat or potato in any of the recipes**. **If _Plant-based Foods_ is also installed**, the custom naming and advancements of that datapack are also supported by the foods in this datapack.