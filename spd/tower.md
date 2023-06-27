---
layout: spd
title: Towers
---

# Towers

Small People Defense has 6 available towers. Towers will evolve and improve their unique abilities when upgraded to level 8. Although there are no plans to increase the number of towers to maintain simplicity in building, status effect interactions and enemy mechanics are designed to add depth to this game's strategy.

Each upgrade will cost twice the previous upgrade. Level increases will grant damage relative to its cost and 20% more maximum health. Additionally, the tower's attack speed and rotation rate (excluding [beam](/spd/tower/beam)) are increased with each level to incentivize upgrading.

Selling a tower will only return 80% of its original value including its upgrades. If a tower is destroyed by the [Kraken](/spd/boss/kraken) or [Zombie](/spd/enemy/zombie), it is automatically sold.

# Tower List

<ul>
  {% assign items = site.tower %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
