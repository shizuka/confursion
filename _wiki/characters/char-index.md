---
title: Characters
notoc: true
permalink: "/characters/"
---

# Characters

### The inhabitants and groups in the land of Confursion

<ul class="wiki-page-list">
<p>This list is automatically built</p>
{% for item in site.wiki %}
  {% if item.url contains "/characters/" and item.url != "/characters/" %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>