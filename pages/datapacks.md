---
title: Full list of datapacks
keywords: 
tags: [info]
sidebar: home_sidebar
toc: true
last_updated: 05/Nov/2022
permalink: datapacks.html
published: true
intro: All my datapacks are listed on this page, sorted by different criteria.
---

## Datapacks by collection

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#standalone-tab" data-toggle="tab">Standalone datapacks</a></li>
    <li><a href="#recyclecraft-tab" data-toggle="tab">Recyclecraft datapacks</a></li>
    <li><a href="#vegancraft-tab" data-toggle="tab">Vegancraft datapacks</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="standalone-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Standalone datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% unless page.tags contains "vegancraft" %}
            {% unless page.tags contains "recyclecraft" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
                    </div>
                    <div class="panel-body">
                        <p style="font-size:18px;color:#587545;"><b><i>{{page.title}}</i></b></p>
                        <p>{{page.abstract}}</p>
                        <a href="{{page.permalink}}" class="btn btn-primary">Learn More</a>
                    </div>
                </div>
            </div>
            {% endif %}
            {% endunless %}
            {% endunless %}
            {% endfor %}
        </div>
    </div>
    <div role="tabpanel" class="tab-pane" id="recyclecraft-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Recyclecraft datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <p align=center>
        {% include buttons/basic.html url="recyclecraft.html" content="View the Recyclecraft collection" %}
        </p>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "recyclecraft" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
    <div role="tabpanel" class="tab-pane" id="vegancraft-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Vegancraft datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <p align=center>
        {% include buttons/basic.html url="vegancraft.html" content="View the Vegancraft collection" %}
        </p>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "vegancraft" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
</div>

## Datapacks by category

<ul id="profileTabs" class="nav nav-tabs">
    <li class="active"><a href="#qol-tab" data-toggle="tab">Quality of Life datapacks</a></li>
    <li><a href="#food-tab" data-toggle="tab">Food datapacks</a></li>
    <li><a href="#simple-tab" data-toggle="tab">Simple datapacks</a></li>
    <li><a href="#crafting-tab" data-toggle="tab">Crafting datapacks</a></li>
</ul>

<div class="tab-content">
    <div role="tabpanel" class="tab-pane active" id="simple-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Simple datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "simple" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
    <div role="tabpanel" class="tab-pane" id="crafting-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Crafting datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "crafting" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
    <div role="tabpanel" class="tab-pane" id="food-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Food datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "food" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
    <div role="tabpanel" class="tab-pane" id="qol-tab">
        <div class="col-lg-12">
            <p style="font-size:20px;color:#406b23;">Quality of Life datapacks:</p>
            <hr style="text-align:left;margin-left:0;margin-top:0;width:100%;">
        </div>
        <div class="row">
            {% assign sorted_pages = site.pages | sort: 'priority' %}
            {% for page in sorted_pages %}
            {% if page.tags contains "QoL" %}
            {% if page.tags contains "datapack" %}
            <div class="col-md-4 col-sm-6">
                <div class="panel panel-default text-center">
                    <div class="panel-heading">
                        {% capture var_logo %}
                        images/{{page.logo}}
                        {% endcapture %}
                        {% include image/basic.html full-src=var_logo width="128" style="-ms-interpolation-mode: nearest neighbour; image-rendering: pixelated;" %}
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
    </div>
</div>