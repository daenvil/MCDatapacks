---
title: Better Hoe Enchantments
keywords: minecraft, datapack, hoe, farming, enchantments
tags: [datapack, standalone, simple, QoL]
sidebar: home_sidebar
toc: true
last_updated: 01/Oct/2025
permalink: better_hoe.html
published: true
# github:
pmc: https://www.planetminecraft.com/data-pack/better-hoe-enchantments/
first_release: ["16","Jul","2025"]
last_release: ["01","Oct","2025"]
logo: better_hoe/pack.png
thumbnail: better_hoe/thumbnail.png
intro: "This datapack adds new effects to some vanilla hoe enchantments, including auto-seeding and harvesting multiple blocks simultaneously."
abstract: "Make farming more efficient with improved vanilla enchantments."
priority: 1
index: 19
downloads: 199
downloads_str: "&gt;100"
gallery: [images/better_hoe/thumbnail.png, images/better_hoe/cutting_grass.gif, images/better_hoe/tiling.gif, images/better_hoe/harvesting.gif, images/better_hoe/silk_touch.gif]
---

## Downloads
Choose the option compatible with your Minecraft version:

<ul id="profileTabs" class="nav nav-tabs">
	<li class="active"><a href="#1-21-9" data-toggle="tab">1.21.9+</a></li>
	<li><a href="#1-21-5" data-toggle="tab">1.21.5–1.21.8</a></li>
</ul>

<div class="tab-content">
	<div role="tabpanel" class="tab-pane active" id="1-21-9">
		<p>
			{% include dp_badges.html supports="1.21.9+" tested="1.21.9" %}
			<br/>
			{% include dp_download.html version="v1.0.1" pmc-url="https://www.planetminecraft.com/data-pack/better-hoe-enchantments/" dropbox-url="https://www.dropbox.com/scl/fi/e59okjzjbzsomywyj7fkf/better_hoe_enchantments_v1.0.1.zip?rlkey=iorztsd27yjir9qdsqna7kvam&st=qgnx0djh&dl=1" %}
		</p>
	</div>
	<div role="tabpanel" class="tab-pane" id="1-21-5">
		<p>
			{% include dp_badges.html supports="1.21.5–1.21.8" tested="1.21.5, 1.21.7, 1.21.8" %}
			<br/>
			{% include dp_download.html version="v1" dropbox-url="https://www.dropbox.com/scl/fi/jtuqj9iz4w9u31a3yaf82/better_hoe_enchantments_v1.zip?rlkey=0jtii3mnumayr8xqs70yzwaa3&st=t96lluwa&dl=1" discontinued=true %}
		</p>
	</div>
</div>

{% include installation.html resourcepack=false %}

## Features

The Efficiency, Silk Touch, and Fortune enchantments have extra features when using hoes:

{% include comments/warning.html content='These effects **only work if the enchanted hoe is held on the main hand**. Holding the hoe in the off hand won\'t work.' %}

### Efficiency

**Efficiency** increases the **area of effect when harvesting crops, cutting gras, and tiling soil**. Only crops with age > 0 will be auto-harvested. Only blocks that have air, grass, or small flowers on top of them will be auto-tiled. ***Sneak while using the hoe to avoid triggering this effect.***

- Efficiency 1: affects 2 blocks. Targeted block + next block in the direction the player is facing.
- Efficiency 2: affects 5 blocks. A plus shape (+) centered on the targeted block.
- Efficiency 3: affects 9 blocks. a 3x3 square centered on the targeted block.
- Efficiency 4: affects 13 blocks. a 3x3 diagonal square centered on the targeted block.
- Efficiency 5: affects 25 blocks. a 5x5 square centered on the targeted block.
- The hoe will suffer damage proportional to the number of affected blocks.

<div style="display: flex; flex-wrap: wrap; justify-content: center;">
	<img src="images/better_hoe/tiling_1.png" alt="Tiling with efficiency 1" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/tiling_2.png" alt="Tiling with efficiency 2" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/tiling_3.png" alt="Tiling with efficiency 3" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/tiling_4.png" alt="Tiling with efficiency 4" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/tiling_5.png" alt="Tiling with efficiency 5" style="width: 180px; height: 180px;">
</div>
<p style="text-align:center;color:gray;">
<i>Area affected by tiling with each efficiency level</i>
</p>

<div style="display: flex; flex-wrap: wrap; justify-content: center;">
	<img src="images/better_hoe/harvest_1.png" alt="Harvesting with efficiency 1" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/harvest_2.png" alt="Harvesting with efficiency 2" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/harvest_3.png" alt="Harvesting with efficiency 3" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/harvest_4.png" alt="Harvesting with efficiency 4" style="width: 180px; height: 180px;">
	<img src="images/better_hoe/harvest_5.png" alt="Harvesting with efficiency 5" style="width: 180px; height: 180px;">
</div>
<p style="text-align:center;color:gray;">
<i>Area affected by harvesting crops with each efficiency level</i>
</p>

<div style="display: flex; flex-wrap: wrap; justify-content: center;">
	<img src="images/better_hoe/tiling.gif" alt="Tiling with efficiency 5" style="width: 360px;">
	<img src="images/better_hoe/harvesting.gif" alt="Harvesting with efficiency 5" style="width: 360px;">
	<img src="images/better_hoe/cutting_grass.gif" alt="Cutting grass with efficiency 5" style="width: 360px;">
</div>
<p style="text-align:center;color:gray;">
<i>Using efficiency to tile soil, harvest crops, and cut grass</i>
</p>

{% include comments/tip.html content='Pumpkin and melon stems are not affected by the Efficiency effect. You can safely harvest crops around planted pumpkins/melons without accidentally cutting those.' %}


### Silk Touch

**Silk Touch** automatically **reseeds crops when harvested**. This affects any crop with age greater than 2. ***Sneak while using the hoe to avoid triggering this effect.***

{% include image/basic.html src="better_hoe/silk_touch.gif" alt="Example of using silk touch with this datapack" align="center" width="360" %}

{% include comments/tip.html content='A hoe enchanted with both Efficiency and Silk Touch will also reseed the extra blocks affected by Efficiency.' %}

### Fortune

**Fortune** gives a **chance of getting an extra drop from wheat and beetroot crops**. The extra chance is +15.5% per Fortune level. With Fortune III, you'll get an average of 1.465 wheat/beetroot per crop.

{% include comments/tip.html content='A hoe enchanted with both Efficiency and Fortune will also give more drops in the extra blocks affected by Efficiency.' %}

{% include comments/note.html content='Wheat and beetroot were the only vanilla crops unaffected by Fortune. The extra-drop chances given here were calculated in a way that it\'s proportional to the chances that the other vanilla crops get from Fortune.' %}

### Limitations

- The crops affected by Efficiency and Silk Touch effects are the four vanilla crops (wheat, potatoes, carrots, and beetroots) + nether wart. Other plants are not affected.
- This datapack modifies the Efficiency and Silk Touch vanilla enchantment files. It will be incompatible with any datapack that also modifies those.
