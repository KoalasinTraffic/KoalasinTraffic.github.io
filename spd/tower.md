---
layout: spd
title: Towers
---

# Towers

Small People Defense maintains simplicity in building by having 6 towers, each with unique abilities when upgraded. Tower interactions and different enemy mechanics are designed to add a lot of depth to this game's strategy.

Each upgrade costs twice the previous upgrade. Level increases grant damage relative to its cost and 20% more maximum health. Additionally, the tower's attack speed and rotation rate (excluding [beam](/spd/tower/beam)) are increased with each level to incentivize upgrading.

Selling a tower only returns 80% of its original value including its upgrades. If a tower is destroyed by the [Kraken](/spd/boss/kraken) or [Zombie](/spd/enemy/zombie), it is automatically sold.

# Tower List

<ul>
  {% assign items = site.tower %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
