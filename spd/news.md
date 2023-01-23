---
layout: spd
title: News
---

# News and Updates

Source of all major updates and news related to Small People Defense, an indie 3rd person tower defense game.

<ul>
  {% assign counter = 0 %}
  {% for post in site.news reversed %}
    <li>
      <a href="{{ post.url }}">
        {{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}
      </a>
      {% if counter == 0 %}
        {% assign counter = counter | plus:1 %}
        <br/><br/>
{% assign page_excerpt = post.content | newline_to_br | split:'<br />' | slice:2 %}
{% assign page_excerpt = page_excerpt | strip_html | remove:'["\n' | remove:'"]' %}
        <pre style="white-space:pre-wrap">{{ page_excerpt }}</pre>
        <br/>
      {% endif %}
    </li>
  {% endfor %}
<ul>
