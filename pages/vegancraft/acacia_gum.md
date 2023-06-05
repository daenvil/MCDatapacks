---
title: Acacia Gum
keywords: minecraft, datapack, vegan, veganism, plant-based, pacifist, slime
tags: [datapack, vegancraft, standalone, simple]
sidebar: home_sidebar
toc: true
last_updated: 05/Jun/2023
permalink: acacia_gum.html
published: true
github: https://github.com/daenvil/vegancraft
pmc: https://www.planetminecraft.com/data-pack/acacia-gum-slime-from-stripping-acacias/
first_release: ["25","Aug","2022"]
last_release: ["05","Jun","2023"]
logo: vegancraft/acacia_gum/pack.png
thumbnail: vegancraft/acacia_gum/thumbnail.png
intro: "This datapack adds the item \"Acacia Gumball\" (a retextured Slimeball), which is obtained by stripping acacia logs."
abstract: "Get gum from stripping acacia trees. A vegan alternative for slime."
priority: 3
index: 11
gallery: [images/vegancraft/acacia_gum/thumbnail.png]
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
            {% include dp_download.html version="v1.1" pmc-url="https://www.planetminecraft.com/data-pack/acacia-gum-slime-from-stripping-acacias/" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/acacia_gum_v1.1.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.17–1.19.4" tested="1.17.1, 1.18.2, 1.19.2" %}
            <br/>
            {% include dp_download.html version="v1" github-url="https://github.com/daenvil/vegancraft/releases/download/v1c/acacia_gum_v1.zip" rp-version="v1d" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1d/vegancraft-RP_v1d.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include comments/note.html content="This resourcepack is the same for all Vegancraft datapacks, meaning you don't need to download it if you are already using another Vegancraft datapack. Just make sure you are using the latest version." %}

{% include installation.html resourcepack=true %}

## Features

- When stripping an acacia log (or wood), there is a 1/4 chance that an "acacia gumball" drops from it.
- Your axe's Fortune enchantment level gives you an extra chance of obtaining a second gumball drop, topping at a total average of 1 gumball per log with Fortune III.
- Acacia gumball behaves just as a regular slimeball but has a different texture and name. Use it to craft slime blocks, sticky pistons, etc. without the need of finding and killing slimes.

{% include image/basic.html src="vegancraft/acacia_gum/screenshots/example.gif" alt="Example of stripping an acacia tree and how the gumballs drop from it" align="center" width="360" %}

### Vegancraft

This is a standalone datapack, but it is designed as a part of [Vegancraft](vegancraft.html), a collection of datapacks with the goal of making a vegan gamestyle possible in a vanilla-like way without missing any game features.

As part of its integration in Vegancraft, this datapack includes the following additional features:
- Two custom advancements.
- Some xp will be awarded each time you get an acacia gumball. If using a Fortune III axe, the amount of xp per gumball is equivalent to that you would get by getting slimeballs by killing slimes.
- In conjunction with my *[Ethical Textiles](ethical_textiles.html)* datapack, this datapack allows you to craft vegan leather.

If, for any reason, you want to remove these features, you can use the command **<code>/function dnv.vegancraft:toggle</code>** to disable them. You can also use that command to turn them on again.

## Reasoning

On the search of a plant-based alternative for slime, I thought gum was the most similar thing in real life. Both the texture and way of obtaining "Acacia Gumball" are based on real-life acacia gum (also known as *gum arabica*), which is obtained from the bark of acacias.

I decided to restrict this to only acacia (despite other real-life trees producing gum as well) in order to not make the mechanic too easy and exploitable. Acacia has the advantage of being available only on savannas (encouraging players to explore, just as they need to explore to find slimes), and having small trunks, which means that it isn't as easily farmed as, for example, spruce or jungle trees.
