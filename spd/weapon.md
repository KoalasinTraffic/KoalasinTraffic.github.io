---
layout: spd
title: Weapons
---

# Weapons

Weapon charges can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health.

Each of the 4 biomes have 7 permanent charges of a single weapon type. It is possible to get all charges in any of the map variations, but some variations can be more difficult than others.

The blaze weapon is the only weapon where the player can get charges as the level progresses, rather than permanently unlocked.

# Weapon List

<ul>
  {% assign items = site.weapon %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
