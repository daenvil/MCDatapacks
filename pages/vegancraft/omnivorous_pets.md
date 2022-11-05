---
title: Omnivorous Pets
keywords: minecraft, datapack, taming, food, vegan, veganism, plant-based, pacifist
tags: [datapack, vegancraft, standalone, QoL]
sidebar: home_sidebar
toc: true
last_updated: 05/Nov/2022
permalink: omnivorous_pets.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/omnivorous-pets/
first_release: ["22","Jul","2022"]
last_release: ["22","Jul","2022"]
logo: vegancraft/omni_pets/pack.png
intro: "A datapack that allows you to tame wolves and cats using any food."
abstract: "Tame cats and wolves using any food. You don't need meat anymore to make animal friends!"
priority: 2
---

## Downloads

Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.19+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.16.2-1.18.2</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.19%2B" tested="1.19.2" %}
            <br/>
            {% include dp_download.html version="v1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1b/omnivorous_pets_v1.zip" pmc-url="https://www.planetminecraft.com/data-pack/omnivorous-pets/download/file/16024623/" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.16.2--1.18.2" tested="1.16.5%2C%201.17.1%2C%201.18.2" %}
            <br/>
            {% include dp_download.html version="v1-mc1.16.2-1.18.2" github-url="https://github.com/daenvil/vegancraft/releases/download/v1b-mc1.16.2-1.18.2/omnivorous_pets_v1-mc1.16.2-1.18.2.zip" dropbox-url="https://www.dropbox.com/s/9h769wy5ch7omjn/omnivorous_pets_v1-mc1.16.2-1.18.2.zip?dl=1" %}
        </p>
    </div>
</div>

{% include installation.html %}

## Features

- _[Youtube video showcasing all the features of this datapack:](https://youtu.be/V5IjyHmo3BI){:target="_blank"}_

<iframe width="560" height="315" src="https://www.youtube.com/embed/V5IjyHmo3BI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Taming

Throw food at stray cats or wolves to attempt to tame them. They will eat any food thrown by players if they are close enough to it.
- Wolves will react the same way as if you just gave them a bone (1/3 chance of being tamed).
- Cats are picky eaters, so food consumed this way will only have a 20% chance of taming them.

{% include image/basic.html src="vegancraft/omni_pets/screenshots/example.gif" alt="Example of taming a wolf by throwing food at them" align="center" width="300" %}

#### Accepted foods

Basically any food that can be eaten by you --except chocolate cookies-- and some others which make sense for animals to eat, like sugar cane and mushrooms. Here's the full list as it is in the code:

{% include collapsible.html id="food-list" title="List of accepted foods (item ids)" content="sugar,<br/>spider_eye,<br/>fermented_spider_eye,<br/>dried_kelp,<br/>glow_berries,<br/>sweet_berries,<br/>egg,<br/>turtle_egg,<br/>melon_slice,<br/>sugar_cane,<br/>cooked_chicken,<br/>cooked_cod,<br/>cooked_mutton,<br/>cooked_porkchop,<br/>cooked_rabbit,<br/>cooked_salmon,<br/>pufferfish,<br/>beef,<br/>chicken,<br/>cod,<br/>mutton,<br/>porkchop,<br/>rabbit,<br/>rabbit_foot,<br/>salmon,<br/>cooked_beef,<br/>tropical_fish,<br/>apple,<br/>beetroot,<br/>carrot,<br/>melon,<br/>red_mushroom,<br/>brown_mushroom,<br/>potato,<br/>pumpkin,<br/>wheat,<br/>baked_potato,<br/>bread,<br/>beetroot_soup,<br/>mushroom_stew,<br/>rabbit_stew,<br/>suspicious_stew,<br/>cake,<br/>pumpkin_pie,<br/>bone,<br/>rotten_flesh" %}

### Vegancraft
This is a standalone datapack, but was originally designed as a part of Vegancraft, a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features. Check out my *[Plant-based Foods](plant-based_foods.html)* datapack if you also want to be able to heal and breed your pets with plant-based food, and some additional features.

## Known issues and solutions

- Cats won't approach you as they do if you hold raw fish, so you will have to catch them somehow or run behind them and throw the food at them (they have an increased "eating range" compared to wolves so that this is not impossible). You can also just throw a lot of food in the ground around them and they will eat it when walking over it. Easiest way is to first leash them so they stop running, and then try to tame them.
- Stray cats and wolves will eat any valid food which was thrown by a player and which is within their "eating range" (1 block for wolves, 2.5 blocks for cats), so it can happen that you feed them by accident.
