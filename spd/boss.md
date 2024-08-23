---
layout: spd
title: Bosses
---

# Bosses

Bosses are much more challenging than regular enemies and typically come in the later waves. They cannot be stunned to prevent chain locking bosses in place. Instead, the stun tower will deal [greater bonus damage](/spd/tower/stun) compared to against regular enemies.

Second, bosses are roughly 50% stronger than regular enemies and only provides a small amount of extra money when defeated. Only one boss can be spawned per wave.

During mazing levels, abilities that move towers are replaced with dealing 10 area of effect damage instead.

[//]: # (Stats can be found within HUDLevel.cpp)

# Boss List

<ul>
  {% assign items = site.boss %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
