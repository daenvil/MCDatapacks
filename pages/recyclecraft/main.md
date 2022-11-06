---
title: Daenvil's Recyclecraft
keywords: minecraft, datapack
tags: [collection, info, recyclecraft]
sidebar: home_sidebar
toc: true
last_updated: 04/Nov/2022
permalink: recyclecraft.html
published: true
pmc-collection: https://www.planetminecraft.com/collection/133777/daenvil-s-recyclecraft-datapacks/
logo: recyclecraft/pack.png
intro: "Recyclecraft is a collection of datapacks designed to improve the survival experience by repurposing unused items instead of wasting them."
---
{% include comments/note.html content="Under construction" %}

***

Unlike [Vegancraft](vegancraft.html), Recyclecraft is not released as a singular datapack, nor its contents are meant to complement each other (although they accidentally might). It is just a name under which I release separate datapacks which fulfill a similar purpose in the game.

The Recyclecraft collection is consided completed, only updating the current datapacks to fix issues or to provide support for new Minecraft updates.

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Recyclecraft datapacks</h2>
    </div>
    {% assign sorted_pages = site.pages | sort: 'priority' %}
    {% for page in sorted_pages %}
    {% if page.tags contains "recyclecraft" %}
    {% if page.tags contains "datapack" %}
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
    {% endfor %}
</div>

## Complementary datapacks

The following is a list of datapacks made by other people that I think complement the datapacks of this collection:

- **_Back to Blocks_**, from [Vanilla Tweak's crafting tweaks](https://vanillatweaks.net/picker/crafting-tweaks/){:target="_blank"}. Will allow you to make better use of the [_Better Stonecutter_](better_stonecutter.html) and [_Cuttable Wood_](cuttable_wood.html) datapacks by allowing you to completely recycle partial blocks.