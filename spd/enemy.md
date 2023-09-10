---
layout: spd
title: Enemies
---

# Enemies

There are many different enemies to defend against in Small People Defense. Enemies are spawned with a new wave every 30 seconds, or 6 seconds if rushed by the player. Their stats are dependent on the number of enemies spawned and based on how much money the player could have earned over the course of the level.

# Serfs

Serfs are spawned every 3 seconds and serve as a source of passive income. They are intended to be weak until the late game. Rushing does not influence the spawn rate of serfs, so faster waves will both starve player income and increase relative difficulty.

In endless mode, serfs are promoted to super serfs after wave 100. This is only a visual aspect to the game.

# Score

Enemies will increase score (along with persistent points) after being defeated. Score per enemy/boss is calculated using Difficulty multiplied by the sum of Base Score and Base Rush Bonus. Difficulty increases by a small percentage each wave.

* Score per serf: 1 point

* Base Score per enemy/boss: 10 points

* Base Rush Bonus per enemy/boss: 2 points per second rushed (to a maximum of 48 points)

[//]: # (Stats can be found within HUDLevel.cpp)

# Enemy List

<ul>
  {% assign items = site.enemy %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
