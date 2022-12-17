---
layout: spd
title: Items
---

# Items

Activatable items can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health. There are 4 unlockable items.

<ul>
  {% for item in site.item %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
