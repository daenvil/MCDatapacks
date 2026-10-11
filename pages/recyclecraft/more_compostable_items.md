---
title: More Compostable Items
keywords: minecraft, datapack
tags: [datapack, recyclecraft, standalone, QoL]
sidebar: home_sidebar
toc: true
last_updated: 11/Oct/2026
permalink: more_compostable_items.html
published: true
github: https://github.com/daenvil/more_compostable_items/
modrinth: https://modrinth.com/datapack/more-compostable-items
first_release: ["18","Jan","2022"]
last_release: ["11","Oct","2026"]
logo: recyclecraft/more_compostable_items/pack.png
intro: "This datapack aims to add composting mechanics to all vanilla items which <i>should</i> be compostable."
abstract: "Adds composting mechanics to all vanilla items which should be compostable."
priority: 1
index: 6
downloads: 13900 # 7000 on pmc before redirecting to modrinth
downloads_str: "&gt;13k"
thumbnail: recyclecraft/more_compostable_items/thumbnail.png
gallery: [images/recyclecraft/more_compostable_items/thumbnail.png]
---

## Downloads

Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#26-3" data-toggle="tab">26.3+</a></li>
    <li><a href="#1-21-9" data-toggle="tab">1.21.9–26.2</a></li>
    <li><a href="#1-21-5" data-toggle="tab">1.21.5–1.21.8</a></li>
    <li><a href="#1-21" data-toggle="tab">1.21–1.21.4</a></li>
    <li><a href="#legacy" data-toggle="tab">1.16.2–1.20.6</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="26-3">
        <p>
            {% include dp_badges.html supports="26.3+" tested="26.3" %}
            <br/>
            {% include dp_download.html version="v2.0" modrinth-url="https://cdn.modrinth.com/data/fli89JFe/versions/yAmy1tRb/more_compostable_items_v2.0.zip?mr_download_reason=standalone" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v2.0/more_compostable_items_v2.0.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-21-9">
        <p>
            {% include dp_badges.html supports="1.21.9–26.2" tested="1.21.9, 1.21.11, 26.1.1, 26.2" %}
            <br/>
            {% include dp_download.html version="v1.4.1" modrinth-url="https://cdn.modrinth.com/data/fli89JFe/versions/t7Cjjf4l/more_compostable_items_v1.4.1.zip" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v1.4.1/more_compostable_items_v1.4.1.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-21-5">
        <p>
            {% include dp_badges.html supports="1.21.5–1.21.8" tested="1.21.5, 1.21.7" %}
            <br/>
            {% include dp_download.html version="v1.4" modrinth-url="https://cdn.modrinth.com/data/fli89JFe/versions/VmYTTPlq/more_compostable_items_v1.4.zip" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v1.4/more_compostable_items_v1.4.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="1-21">
        <p>
            {% include dp_badges.html supports="1.21–1.21.4" tested="1.21.4" %}
            <br/>
            {% include dp_download.html version="v1.3.3" modrinth-url="https://cdn.modrinth.com/data/fli89JFe/versions/tkE72oj5/more_compostable_items_v1.3.3.zip" github-url="https://github.com/daenvil/more_compostable_items/releases/download/v1.3.3/more_compostable_items_v1.3.3.zip" discontinued=true %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        For older Minecraft versions (no longer maintained, features may be different than described in this page):
        <table><thead>
            <tr>
                <th>Supported Minecraft versions</th>
                <th>Datapack version</th>
                <th>Tested in</th>
                <th>Download links</th>
            </tr></thead>
            <tbody>
            <tr>
                <td>1.20.5–1.20.6</td>
                <td>1.3</td>
                <td>1.20.6</td>
                <td><a href='https://github.com/daenvil/more_compostable_items/releases/download/v1.3/more_compostable_items_v1.3.zip'>Github</a></td>
            </tr>
            <tr>
                <td>1.20–1.20.4</td>
                <td>1.2.1</td>
                <td>1.20, 1.20.4</td>
                <td><a href='https://github.com/daenvil/more_compostable_items/releases/download/v1.2.1/more_compostable_items_v1.2.1.zip'>Github</a></td>
            </tr>
            <tr>
                <td>1.16.2–1.19.4</td>
                <td>1.1</td>
                <td>1.16.5, 1.17.1, 1.18.2, 1.19.3</td>
                <td><a href='https://github.com/daenvil/more_compostable_items/releases/download/v1.1/more_compostable_items_v1.1.zip'>Github</a></td>
            </tr>
            </tbody>
        </table>
    </div>
</div>

{% include installation.html %}

## Features

New compostable items, including rotten flesh, poisonous potatoes, foods, and many more (see the list below).

{% include collapsible.html title='Important information for versions previous to Minecraft 26.3' content='Prior to Minecraft 26.3, items could not be made compostable in a fully vanilla way. These items were compostable in the following ways:

<ul>
<li>By putting them in a hopper on top of a composter, the same way you would do with vanilla-compostable items.</li>
<li>By dropping them *inside* a composter (vanilla items are also given this feature).</li>
</ul>
Composting items by dropping them inside composters can be disabled (see the <a href="#available-commands">Available commands</a> section)' %}

{% include comments/note.html content='This datapack was tested in a multiplayer server with ~10 players and performed well without any noticeable performance issue.' id='legacy-info' %}

### List of new compostable items
*(Click to expand)*

{% include collapsible.html title='10% chance:' content='<ul><li>Sugar
</li><li>Honeycomb
</li><li>Spider eye
</li><li>Fermented spider eye
</li><li>Phantom membrane
</li><li>Turtle and armadillo scutes
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
</li><li>Chicken eggs
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
</li><li>Muddy mangrove roots</li>
</li><li>Pale moss carpet</li>
</li><li>Pale hanging moss</li>
</li><li>Bush and firefly bush</li>
</li><li>Cactus flower</li>
</li><li>Dry grass</li>
</li><li>Leaf litter</li>
</li><li>Wildflowers</li></ul>' id='30-chance' %}
 
{% include collapsible.html title='50% chance:' content='<ul><li>Cooked chicken, cod, mutton, porkchop, rabbit, beef, and salmon
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

{% include comments/note.html content='All these issues should be solved in Minecraft 26.3+' %}

- **Custom-composting via hoppers only works with composters that are placed by players**. This means that it won't work with world-generated composters, with composters summoned via commands, or with composters placed *before* the datapack was installed. Simply **break a composter and place it again manually to make the datapack register it**.
- The datapack might have trouble detecting a placed composter if you are moving very fast while placing it. This shouldn't be a problem as long as you are not MLG-360-no-scoping composters. If a composter is not working, just break it and place it again while not moving.
- Some things are hardcoded in this datapack, which means that it can interact in unexpected ways with mods that alter vanilla mechanics:
  - Hopper-custom-composting uses the hopper built-in <code>TransferCooldown</code> variable, so it might conflict with any mod or datapack that changes the vanilla behaviour of hopper cooldowns.
  - Since vanilla-compostable items are hardcoded in Minecraft, I had to hardcode them also in this datapack, so it detects when one of them is present in a hopper and avoids composting other items at the same time. This means that any mod that changes which items are compostable with vanilla mechanics might cause unintended behaviours (but nothing game-breaking).

### Adding new compostable items

This datapack provides item tags for 10%, 30%, 50%, 65%, 85%, and 100% composting chances. You can find their .json files in <code>&lt;this datapack&gt;/data/dnv.compost/tags/items/</code>. If you want to customize the datapack for your own use, edit those files however you want.

### Available commands

- **<code>/function dnv.compost:uninstall</code>**: removes all the entities and scoreboard objectives created by this datapack. Run this function if you want to stop using the datapack to ensure it leaves no trace. All composter markers will be removed, meaning that if you want to use the datapack again after uninstalling it, you will have to manually replace already existing composters in order for the datapack to register them again.
