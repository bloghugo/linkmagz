---
layout: default
title: "Categories"
permalink: /categories/
---
<h1>Categories</h1>
<ul>
  {% for tag in site.tags %}
    <li><a href="{{ '/tag/' | append: tag[0] | relative_url }}">{{ tag[0] }} ({{ tag[1].size }})</a></li>
  {% endfor %}
</ul>
