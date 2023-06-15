---
title: More Compostable Items
keywords: minecraft, datapack
tags: [datapack, recyclecraft, standalone, QoL]
sidebar: home_sidebar
toc: true
last_updated: 06/Jun/2023
permalink: more_compostable_items.html
published: true
github: https://github.com/daenvil/more_compostable_items/
pmc: https://www.planetminecraft.com/data-pack/more-compostable-items/
first_release: ["18","Jan","2022"]
last_release: ["06","Jun","2023"]
logo: recyclecraft/more_compostable_items/pack.png
intro: "This datapack aims to add composting mechanics to all vanilla items which <i>should</i> be compostable, while being as close as possible to vanilla mechanics."
abstract: "Adds composting mechanics to all vanilla items which should be compostable."
priority: 1
index: 6
downloads: 2781
downloads_str: "&gt;2.7k"
thumbnail: recyclecraft/more_compostable_items/thumbnail.png
gallery: [images/recyclecraft/more_compostable_items/thumbnail.png]
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
            {% include dp_badges.html supports="1.20+" tested="snapshot 23w16a" %}
            <br/>
            {% include dp_download.html version="v1.2" pmc-url="https://www.planetminecraft.com/data-pack/more-compostable-items/" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v1.2/more_compostable_items_v1.2.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.16.2–1.19.4" tested="1.16.5, 1.17.1, 1.18.2, 1.19.3" %}
            <br/>
            {% include dp_download.html version="v1.1" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v1.1/more_compostable_items_v1.1.zip" discontinued=true %}
        </p>
    </div>
</div>

{% include installation.html %}

## Features

New compostable items, including rotten flesh, poisonous potatoes, foods, and many more (see the list below). These new items are compostable in the following ways:

- By putting them in a hopper on top of a composter, the same way you would do with vanilla-compostable items.

{% include image/basic.html src="recyclecraft/more_compostable_items/screenshots/hopper.gif" alt="Composting a poisonous potato via hopper" width="480" align="center" %}

<br/>
- By dropping them ***inside*** a composter (vanilla items are also given this feature).

{% include image/basic.html src="recyclecraft/more_compostable_items/screenshots/dropping.gif" alt="Composting a poisonous potato by dropping it" width="480" align="center" %}

{% include comments/tip.html content='Composting items by dropping them inside composters can be disabled (see the <a href="#available-commands">Available commands</a> section)' %}

- _[Youtube video showcasing all the features of this datapack:](https://youtu.be/S8mXr1R7Kl0){:target="_blank"}_

<iframe width="560" height="315" src="https://www.youtube.com/embed/S8mXr1R7Kl0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

{% include comments/note.html content='This datapack was tested in a multiplayer server with ~10 players and performed well without any noticeable performance issue.' %}

### List of new compostable items
*(Click to expand)*

{% include collapsible.html title='10% chance:' content='<ul><li>Sugar
</li><li>Honeycomb
</li><li>Spider eye
</li><li>Fermented spider eye
</li><li>Phantom membrane
</li><li>Scute
</li><li>Rabbit hide
</li><li>Bamboo
</li><li>String
</li><li>Feather
</li><li>Slimeball
</li><li>Magma cream
</li><li>Ink Sac (both glow and regular)
</li><li>Any dye
</li><li>Stick
</li><li>Carpets</li></ul>' id='10-chance' %}

 {% include collapsible.html title='30% chance:' content='<ul><li>Chorus fruit
</li><li>Popped chorus fruit
</li><li>Chorus flower
</li><li>Honey block
</li><li>Honeycomb block
</li><li>Rotten flesh
</li><li>Egg
</li><li>Turtle egg
</li><li>Leather
</li><li>Dead bush
</li><li>Charcoal
</li><li>Wool
</li><li>Slime block
</li><li>Nautilus shell
</li><li>Paper
</li><li>Cobweb
</li><li>Goat horn
</li><li>Muddy mangrove roots</li></ul>' id='30-chance' %}
 
{% include collapsible.html title='50% chance:' content='<ul><li>Raw/cooked chicken, cod, mutton, porkchop, rabbit, beef, and salmon
</li><li>Rabbit\'s foot
</li><li>Pufferfish
</li><li>Tropical fish
</li><li>Crimson/warped nylium</li></ul>' id='50-chance' %}

{% include collapsible.html title='65% chance:' content='<ul><li>Poisonous potato
</li><li>Corals (dead or alive)
</li><li>Bee nest</li></ul>' id='65-chance' %}

{% include collapsible.html title='85% chance:' content='<ul><li>Beetroot soup
</li><li>Mushroom/rabbit/suspicious stew
</li><li>Coral blocks (dead or alive)
</li><li>Sculk vein</li></ul>' id='85-chance' %}

{% include collapsible.html title='100% chance' content='<ul><li>Mycelium
</li><li>Sculk
</li><li>Sculk catalyst/shrieker/sensor/calibrated sensor</li></ul>' id='100-chance' %}

{% include comments/note.html content='This datapack aims to contain all vanilla items which should be compostable in a realistic way, so if you find any item that is missing or should be changed, please <a href="contact.html" target="_blank">contact me</a>.' %}

### Known issues (and solutions)

- **Custom-composting only works with composters that are placed by players**. This means that it wont work with world-generated composters, with composters summoned via commands, or with composters placed *before* the datapack was installed. Simply **break a composter and place it again manually to make the datapack register it**.
- The datapack might have trouble detecting a placed composter if you are moving very fast while placing it. This shouldn't be a problem as long as you are not MLG-360-no-scoping composters. If a composter is not working, just break it and place it again while not moving.
- Some things are hardcoded in this datapack, which means that it can interact in unexpected ways with mods that alter vanilla mechanics:
  - Hopper-custom-composting uses the hopper built-in <code>TransferCooldown</code> variable, so it might conflict with any mod or datapack that changes the vanilla behaviour of hopper cooldowns.
  - Since vanilla-compostable items are hardcoded in Minecraft, I had to hardcode them also in this datapack, so it detects when one of them is present in a hopper and avoids composting other items at the same time. This means that any mod that changes which items are compostable with vanilla mechanics might cause unintended behaviours (but nothing game-breaking).

### Adding new compostable items

This datapack provides item tags for 10%, 30%, 50%, 65%, 85%, and 100% composting chances. You can find their .json files in <code>&lt;this datapack&gt;/data/dnv.recyclecraft/tags/items/</code>. If you want to customize the datapack for your own use, edit those files however you want.

{% include comments/important.html content='There is another item tag for vanilla-compostable items, do not edit that one unless you know what you are doing. It is used to detect when a hopper is containing them as to not overlap vanilla-composting with custom-composting, otherwise, both mechanics would function at the same time, breaking the intended effect of this datapack.' %}

### Available commands

There are some commands that you can optionally use with this datapack:

- **<code>/function dnv.compost:dropping_toggle</code>**: enables or disables compost-by-dropping (***on*** by default). Disable it if you don't want compostable items that drop inside a composter to be composted.
- **<code>/function dnv.compost:uninstall</code>**: removes all the entities and scoreboard objectives created by this datapack. Run this function if you want to stop using the datapack to ensure it leaves no trace. All composter markers will be removed, meaning that if you want to use the datapack again after uninstalling it, you will have to manually replace already existing composters in order for the datapack to register them again.
- **<code>/function dnv.compost:debug_mode</code>**: enables or disables debug mode (***off*** by default). While debug mode is enabled, you will be able to see small armor stands inside the composters which are registered by the datapack, and some messages will display in chat, like warnings whenever a composter is not registered correctly. *This was implemented for myself to test the datapack, you shouldn't need it except if you are messing with the files and testing things by yourself.*

***

{% include comments/tip.html content='If you are just casually using this datapack you don\'t need to read any more from here. The following info is just for interested developers.' %}

## Explanation for datapackers/modders

Composting is hardcoded in vanilla minecraft, meaning that in order to add new compostable items, the datapack needs to mimic vanilla mechanics via other means.

### Interacting with composters by hand

In vanilla, you right-click a composter with a compostable item to compost it. AFAIK this is impossible to emulate with custom-compostable items, since we don't have a way of detecting a right-click in a composter with them.

So to mimic this, we have multiple options:
- Right-click can be detected with food items, since it's the way you eat them. Theoretically, this could be used to detect when you press right-click with a food item in your hand while facing a composter, and use that to compost the item. However this has two short-comings: it's not an universal solution (we would have to find an alternative for non-food items), and would only work when the player is hungry.
- Right-click *can* be detected by using more complex methods like invisible villagers, item frames, etc. However, these methods have their shortcomings and I do not wish to have to use something as complex as that for something so simple and common as composting items.
- Instead of right-clicking, dropping the items *inside* the composter. This can be easily detected and is the method already used by the other custom composting datapacks I found. It's not the same as the vanilla mechanic, but it's probably the best method we have. This was the chosen approach for this datapack, and I decided to also make vanilla-compostable items compostable this way, for consistency.

### Interacting with composters via hoppers

In vanilla, composting can be automated by placing hoppers on top and below the composter. This was the main goal of this datapack and why I didn't want to expend much effort in composting by hand, since using hoppers along composters is probably the most common method of composting items by far. I couldn't find any datapack that emulates this with custom-compostable items, but it is fairly easy to do:

1. Summon an invisible armor stand in all composters, which stores the composter information. I refer to these as "composter markers".
2. Each tick, check which composter markers have an enabled hopper on top pointing to them.
3. Search all slots of the hopper inventory:
 - If vanilla-compostable items are present, ignore the rest of the algorithm, since they will already be composted with vanilla mechanics.
 - If not, search for the first slot with a custom-compostable item, reduce its count by one and call the appropiate composting function *(in order to check the item tag of the items in the hopper, they are copied to the composter marker's main hand slot, and checked on there)*.
4. A custom composting function emulates the composter behaviour, increasing its level if the appropiate random check was succesful, and producing the corresponding aesthetic effects.
5. The bottom hopper will work as usual, extracting bonemeal when the composter is full.

Some extra details need to be taken into account, like hopper cooldown, stopping custom composting when the composter is full, different composting chances for each item, etc.

In principle, this method should emulate perfectly the behaviour of vanilla composters with any item you want to add, the only short-coming it has right now is that vanilla items are still hardcoded, so it is impossible to change their random composting chances or make them non-compostable. They also have to be manually added to an item tag (<code>dnv.recyclecraft:vanilla-compostable</code>) in order to take them into account in the algorithm, so this could create conflicts with any mod which adds new items which are vanilla-compostable and are not added to that item tag (also, I have to manually add any new compostable item with each Minecraft major update). The effect of such conflict is making hoppered composters be able to process vanilla and custom-compostable items at the same time, though, so it doesn't break anything important, it just doubles the composting speed in the specific case where the hopper contains a custom-compostable item and a vanilla-compostable item which is not in the vanilla-compostable tag at the same time.
