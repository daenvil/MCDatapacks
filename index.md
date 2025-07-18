---
layout: home
title: "Home"
keywords: homepage
sidebar: home_sidebar
last_updated: 16/Jul/2025
toc: true
intro: "Welcome to my website, where I document all the info of my Minecraft creations. In this page you have a summary of my content. Use the sidebar and the top bar to navigate through all the site's pages."
---

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Most popular datapacks</h2>
    </div>
    {% assign sorted_pages = site.pages | sort: 'downloads' | reverse %}
    {% for i in (0..2) %}
    {% assign pos = i | plus: 1 %}
    {% assign page = sorted_pages[i] %}
    {% if page.downloads %}
    {% if page.tags contains "datapack" %}
    <div class="col-md-4 col-sm-6">
        <div class="panel panel-default text-center">
            <div class="panel-heading">
                {% if page.thumbnail %}
                {% capture var_thumbnail %}
                images/{{page.thumbnail}}
                {% endcapture %}
                {% capture var_url %}
                {{page.permalink}}
                {% endcapture %}
                {% include image/basic.html full-src=var_thumbnail align='center' style='max-width:100%;' url=var_url %}
                {% elsif page.logo %}
                {% capture var_logo %}
                images/{{page.logo}}
                {% endcapture %}
                {% include image/basic.html full-src=var_logo align='center' style='max-width:100%;' nn=true url=var_url %}
                {% endif %}
                <img src="https://img.shields.io/badge/downloads-{{page.downloads_str}}-72ac4a?style=flat-square">
            </div>
            <div class="panel-body">
                <p style="font-size:18px;color:#587545;"><a href="{{page.permalink}}"><b><i>{{pos}}. {{page.title}}</i></b></a></p>
                <p>{{page.abstract}}</p>
                <a href="{{page.permalink}}" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>
    {% endif %}
    {% endif %}
    {% endfor %}
</div>

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Latest releases</h2>
    </div>
    {% assign sorted_pages = site.pages | sort: 'index' | reverse %}
    {% for page in sorted_pages limit: 3 %}
    {% if page.index %}
    {% if page.tags contains "datapack" %}
    <div class="col-md-4 col-sm-6">
        <div class="panel panel-default text-center">
            <div class="panel-heading">
                {% if page.thumbnail %}
                {% capture var_thumbnail %}
                images/{{page.thumbnail}}
                {% endcapture %}
                {% capture var_url %}
                {{page.permalink}}
                {% endcapture %}
                {% include image/basic.html full-src=var_thumbnail align='center' style='max-width:100%;' url=var_url %}
                {% elsif page.logo %}
                {% capture var_logo %}
                images/{{page.logo}}
                {% endcapture %}
                {% include image/basic.html full-src=var_logo align='center' style='max-width:100%;' nn=true url=var_url %}
                {% endif %}
                <p style="text-align:center;"><img src="https://img.shields.io/badge/released%20on-{{page.first_release[0]}}%2F{{page.first_release[1]}}%2F{{page.first_release[2]}}-72ac4a?style=flat-square"></p>
            </div>
            <div class="panel-body">
                <p style="font-size:18px;color:#587545;"><a href="{{page.permalink}}"><b><i>{{page.title}}</i></b></a></p>
                <p>
                    {{page.abstract}}
                </p>
                <a href="{{page.permalink}}" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>
    {% endif %}
    {% endif %}
    {% endfor %}
</div>

<hr>
<p align=center>
{% include buttons/basic.html url="datapacks.html" content="Full list of datapacks" %}
</p>