---
title: Daenvil's Vegancraft
keywords: minecraft, datapack, baking, cooking, food, vegan, veganism, plant-based, pacifist
tags: [datapack, vegancraft, collection, crafting, food, info]
sidebar: home_sidebar
toc: true
last_updated: 05/Jun/2023
permalink: vegancraft.html
published: true
github: https://github.com/daenvil/vegancraft
pmc-collection: https://www.planetminecraft.com/collection/162672/daenvil-s-vegancraft/
first_release: ["17","Jun","2022"]
last_release: ["05","Jun","2023"]
logo: vegancraft/pack.png
intro: "Vegancraft is a modular datapack which makes a vegan gamestyle possible in a vanilla-like way without missing any game features. Tired of killing cows to make books and item frames? Tired of using sheep to make beds? This datapack is for you.<br/><br/>You can either download the full collection in a single datapack or <a href=#features>download the individual datapacks as desired</a>."
abstract: "A merged version of every Vegancraft datapack. Makes a vegan gamestyle possible in a vanilla-like way without missing any game features."
index: 16
---

## Full datapack download

Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#current" data-toggle="tab">1.20+</a></li>
    <li><a href="#legacy" data-toggle="tab">1.19.x</a></li>
    <li><a href="#legacy2" data-toggle="tab">1.17–1.18.2</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="current">
        <p>
            {% include dp_badges.html supports="1.20+" tested="1.20--rc1" %}
            <br/>
            {% include dp_download.html version="v1.0" github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-DP_v1.0.zip" rp-version="v1.0" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1.0/vegancraft-RP_v1.0.zip" %}
        </p>
    </div>
    <div role="tabpanel" class="tab-pane" id="legacy">
        <p>
            {% include dp_badges.html supports="1.19.x" tested="1.19.3" %}
            <br/>
            {% include dp_download.html version="v1e" github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/vegancraft-DP_v1e.zip" rp-version="v1e" rp-github-url="https://github.com/daenvil/vegancraft/releases/download/v1e/vegancraft-RP_v1e.zip" %}
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

{% include comments/note.html content="The resourcepack will give you a warning if you are not using 1.20, but it will work. Both datapack and resourcepack were tested on the mentioned versions; and also on multiplayer." %}
{% include installation.html resourcepack=true %}

## Features
This datapack aims to make any vanilla feature available without hurting or using any mob. The currently implemented features, also available as individual datapacks, are listed below.

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Included datapacks</h2>
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

### Resourcepack

Most of these datapacks contain custom textures and item names. The Vegancraft resourcepack is needed in order to view them properly. For simplicity, this resourcepack is the same for all datapacks, and is available on the [Downloads](#full-datapack-download) section or in the page of any single datapack that uses it.

### Customization options

- **These individual datapacks are entirely modular**, meaning that if you don't like one (or more) of them, you can just download all the rest of them without worrying about compatibility issues. The "full" datapack (downloadable at the top of the page) is just an optimized merged version of all of these datapacks.

- As detailed on the individual datapacks, some features, such as custom advancements or XP rewards for crafting vegan items, can be disabled by using the command <code>/function dnv.vegancraft:toggle</code>. You can also use that command to turn them on again. This allows to play in an even more vanilla way, if desired.

## Future Features
Planned datapacks that are still in progress

### Vegan Brewing

Vegan alternatives for brewing ingredients.

### Copper horns

Craft horns using copper and wax.

## Contributing

If you wish to contribute in any way to the development of Vegancraft, you can [contact me](#contact) on any platform, I will gladly welcome feature suggestions or even collaborators.

You can also [create an issue](https://github.com/daenvil/vegancraft/issues/new/choose){:target="_blank"} on this project's GitHub repository for bug reports, feature requests, contributions, or any question you may have.

### Translations

If you wish to translate this datapack to your language(s) (or fix any already existing one), just use the "lang" files you can find inside the resorcepack as template, and send your version to me either via a pull request or an issue. I will credit you as translator on here, on the corresponding datapacks' PlanetMinecraft pages, and on the README file of the resourcepack.