---
title: Locations
notoc: true
noedit: true
permalink: "/locations/"
---

# Locations

### Places to visit in the land of Confursion

<ul class="wiki-page-list">
<p>This list is automatically built</p>
{% for item in site.wiki %}
  {% if item.url contains "/locations/" and item.url != "/locations/" %}
  <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>