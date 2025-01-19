---
title: Lead Tweaks
keywords: minecraft, datapack
tags: [datapack, standalone, QoL]
sidebar: home_sidebar
toc: true
last_updated: 05/Nov/2022
permalink: lead_tweaks.html
published: false
pmc: TBR
first_release: ["TBR","Nov","2020"]
last_release: ["TBR","Nov","2022"]
logo: lead_tweaks/pack.png
intro: "A datapack that adds some new optional features/fixes to leads, with the purpose of making them easier to use. Summarized, this functionalities will:<br/><ul><li>Warn you when a lead is broken.</li><li>Make leads drop by your side when they break, instead of at the mob's position.</li>"
abstract: "Small tweaks that make leads easier to use. Get notified when a lead breaks and make broken leads drop besides you! Entirely customizable settings."
priority: 0
index: 15
---

{% include comments/note.html content="Under construction" %}

## Download
![Minecraft supported versions](https://img.shields.io/badge/supported%20MC%20versions-1.17%2B-green?style=flat-square)
![Tested versions](https://img.shields.io/badge/tested%20in-1.19.2-informational?style=flat-square)

{% include dp_download.html version="TBR" mirror-url="TBR" mirror-platform="TBR" %}

{% include installation.html %}

## Features

All the following features are optional. They come enabled by default, but you can customize and disable each one of them by using the command **<code>/trigger dnv.leads.config</code>**.

### Lead indicators

The purpose of lead indicators is to **solve the problem where you don't realize that a lead broke** when you are running while looking away from a mob that you leashed.

#### Acoustic indicator

The acoustic indicator will **play a sound whenever you leash a mob or whenever a mob is unleashed**, either by you or accidentally. The sounds are the same as the ones that are played when you attach/deattach a lead to a fence.

#### Visual indicator

The visual indicator will **display on your screen the number of mobs that you have currently leashed, turning red when you lose a mob**. There are two display options for the visual indicator:

- Action bar (default): will display it on the bottom of the screen, right on top of the action/tools bar.
- Chatbox: will display it as a message on your chat whenever the number of mobs changes.

The action bar visual indicator is only displayed when you have mobs leashed or when less than two seconds have passed since you leashed any mob. So you won't see it at all when you are not using leads.

### Lead drop tweak

The purpose of the drop tweak is to solve the problem where a lead is broken and you have to search for it returning to the mob's previous position while the mob is moving freely around. **With this tweak, when a lead is broken, it will teleport to *your* position, making it easier and faster to recover it**.

If you are moving slowly, the lead might directly be picked up to your inventory. If you are moving fast, it will probably be left in the ground where you were a moment ago. Nevertheless, it will be easier to recover than when it is dropped at the mob's position, specially if you have a lead indicator enabled, since you will instantly know that the lead broke.

### Configuration

You can use the command **<code>/trigger dnv.leads.config</code>** to customize your personal settings. These will let you disable or customize each one of this datapack's features.

{% include image/figure.html src="lead_tweaks/screenshots/config.png" caption="Screenshot of the configuration menu." %}
