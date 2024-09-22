---
layout: spd
title: Towers
---

# Towers

Small People Defense only has 6 towers but each has their own unique abilities when upgraded. Tower interactions and enemy mechanics add depth to the game's strategy.

Each upgrade costs twice the previous upgrade. Level increases grant damage relative to its cost and grant 50% more health (capped at 40 per level). Additionally, the tower's attack speed and rotation rate (excluding [Beam](/spd/tower/beam)) are increased with each level to incentivize upgrading.

Selling a tower only returns 80% of its original value including its upgrades (90% if playing the [Merchant](/spd/character/merchant). This amount is rounded down to discourage buying and selling infinitely. If a tower is destroyed by the [Kraken](/spd/boss/kraken) or [Zombie](/spd/enemy/zombie), it is automatically sold.

# Tower List

<ul>
  {% assign items = site.tower %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
