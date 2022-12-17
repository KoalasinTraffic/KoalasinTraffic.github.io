---
layout: spd
title: Towers
---

# Towers

Small People Defense has up to 6 available towers. When leveled up to their max level, towers will evolve and improve their unique abilities. There are no plans to increase the number of towers to maintain simplicity in building. However, status effect interactions and enemy mechanics are designed to add depth in this game's strategy.

<ul>
  {% for item in site.tower %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
