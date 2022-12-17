---
layout: spd
title: News
---

# News and Updates

<ul>
  {% assign counter = 0 %}
  {% for post in site.news reversed %}
    <li>
      <a href="{{ post.url }}">
        {{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}
      </a>
      {% if counter == 0 %}
        <pre style="white-space: pre-wrap">{{ post.excerpt | strip_newlines }}</pre>
        {% assign counter = counter | plus:1 %}
      {% endif %}
    </li>
  {% endfor %}
<ul>
