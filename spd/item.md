---
layout: spd
title: Items
---

# Items

Activatable items can be unlocked by exploring various parts of the map. Once unlocked, they can be used at no cost to deal a percentage of the enemy's max health.

Each of the 4 maps have 7 of a single type of item. It is technically possible to grab every item in any of the map variations, but some can be very difficult to find.

# Item List

<ul>
  {% assign items = site.item %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
