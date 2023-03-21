---
layout: spd
title: Bosses
---

# Bosses

Bosses are much more challenging than regular enemies and typically come in the later waves. Their first attribute is that they cannot be stunned. Instead, the stun tower will deal greater bonus damage compared to against regular enemies.

Second, bosses are roughly 50% stronger than regular enemies but only provides the normal amount of money when defeated. Only one boss can be spawned per wave.

[//]: # (Stats can be found within HUDLevel.cpp)

# Boss List

<ul>
  {% assign items = site.boss %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
