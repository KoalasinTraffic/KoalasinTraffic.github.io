---
layout: spd
title: Weapons
---

# Weapons

Weapon charges can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health.

The first 4 biomes hold 8 permanent charges of a single weapon type. It is possible to get all 8 charges in any of the map variations, but some variations can be more difficult than others.

Also, charges of the weapons can be bought using points but their costs grow exponentially. A total of 22 charges can be bought, meaning a player can have a maximum of 30 charges per weapon at the start of any game.

The blaze weapon is the only weapon where the player can get charges as the level progresses, rather than permanently unlocked.

# Weapon List

<ul>
  {% assign items = site.weapon %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
