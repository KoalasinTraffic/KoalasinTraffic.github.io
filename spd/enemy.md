---
layout: spd
title: Enemies
---

# Enemies

There are many types of enemies to defend against in Small People Defense. Enemies are spawned with a new wave every 30 seconds or less if rushed by the player. Their stats are dependent on the number of enemies spawned and based on how much money the player could have earned over the course of the level.

Serfs are spawned every 3 seconds and serve as a source of passive income. They are intended to be weak until the late game. Rushing does not influence the spawn rate of serfs, so faster waves will both starve player income and increase relative difficulty.

In endless mode, serfs are promoted to super serfs after wave 45. This is mainly a visual aspect to the game, but represents the point where your passive source of income becomes as threatening as the main waves.

[//]: # (Stats can be found within HUDLevel.cpp)

# Enemy List

<ul>
  {% assign items = site.enemy %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
