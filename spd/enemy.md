---
layout: spd
title: Enemies
---

# Enemies

There are over 20 enemy types to defend against. Enemies are spawned with a new wave every 30 seconds, or as low as 6 seconds if rushed by the player. Their stats are dependent on the number of enemies spawned and based on how much money the player could have earned over the course of the level. When there are multiple enemies in a wave, health is distributed evenly among the enemies.

# Serfs

Serfs are spawned every 3 seconds. They have 10 times less health but provides 10 times less points than a single wave. Rushing does not influence the spawn rate of serfs. Starting from wave 100, serfs are promoted to super serfs and have 10% more health.

# Scoring and Cash

Defeating enemies grants cash and points (including persistent points). The higher the base difficulty, the more you get per wave. Rushing waves can grant up to 2 times more cash and points. This means that by rushing all waves, you will get roughly 60% more compared to players who didn't rush all waves.

[//]: # (Stats can be found within HUDLevel.cpp)

# Enemy List

<ul>
  {% assign items = site.enemy %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
