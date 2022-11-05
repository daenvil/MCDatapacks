---
layout: home
title: "Home"
keywords: homepage
sidebar: home_sidebar
toc: true
intro: "Welcome to my website, where I document all the info of my Minecraft creations. In this page you have a summary of my content. Use the sidebar and the top bar to navigate through all the site's pages."
---

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Latest releases</h2>
    </div>
    {% assign sorted_pages = site.pages | sort: 'index' | reverse %}
    {% for page in sorted_pages | limit: 3 %}
    {% if page.index %}
    {% if page.tags contains "datapack" %}
    <div class="col-md-4 col-sm-6">
        <div class="panel panel-default text-center">
            <div class="panel-heading">
                {% capture var_logo %}
                images/{{page.logo}}
                {% endcapture %}
                {% include image/basic.html full-src=var_logo width="128" nn=true %}
                <img src="https://img.shields.io/badge/released%20on-{{page.first_release[0]}}%2F{{page.first_release[1]}}%2F{{page.first_release[2]}}-72ac4a?style=flat-square">
            </div>
            <div class="panel-body">
                <p style="font-size:18px;color:#587545;"><b><i>{{page.title}}</i></b></p>
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

<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Most downloaded datapacks</h2>
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
                {% capture var_logo %}
                images/{{page.logo}}
                {% endcapture %}
                {% include image/basic.html full-src=var_logo width="128" nn=true %}
                <img src="https://img.shields.io/badge/downloads-{{page.downloads_str}}-72ac4a?style=flat-square">
            </div>
            <div class="panel-body">
                <p style="font-size:18px;color:#587545;"><b><i>{{pos}}. {{page.title}}</i></b></p>
                <p>{{page.abstract}}</p>
                <a href="{{page.permalink}}" class="btn btn-primary">Learn More</a>
            </div>
        </div>
    </div>
    {% endif %}
    {% endif %}
    {% endfor %}
</div>