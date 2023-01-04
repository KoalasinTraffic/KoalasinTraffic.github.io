---
layout: spd
title: Items
---

# Items

Activatable items can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health. There are 4 unlockable items.

<ul>
  {% assign items = site.item %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
