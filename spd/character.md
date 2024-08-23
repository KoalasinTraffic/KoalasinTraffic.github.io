---
layout: spd
title: Characters
---

# Characters

Character selection will provide small differences that can influence players trying to optimize their builds. The default character is the [Merchant](/spd/character/merchant).

# Character List

<ul>
  {% assign items = site.character %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
