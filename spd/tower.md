---
layout: spd
title: Towers
---

# Towers

Small People Defense has up to 6 available towers. When upgraded to level 8, towers will evolve and improve their unique abilities. Currently, there are no plans to increase the number of towers to maintain simplicity in building. However, status effect interactions and enemy mechanics are designed to add depth to this game's strategy.

If a tower is destroyed, it is automatically sold. However, selling will only return 80% of its original value including upgrades.

# Tower List

<ul>
  {% assign items = site.tower %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
