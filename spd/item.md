---
layout: spd
title: Items
---

# Items

Activatable items can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health.

Map 1 has 7 muffins.

Map 2 has 7 donuts.

Map 3 has 7 cabbages.

Map 4 has 7 pineapples.

# Item List

<ul>
  {% assign items = site.item %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
