---
layout: default
title: "Categories"
permalink: /categories/
---

<h1>Categories</h1>
<ul class="categories-list">
  {% for tag in site.tags %}
    {% assign tag_name = tag[0] %}
    <li><a href="{{ '/tag/' | append:tag_name | relative_url }}">{{ tag_name }} ({{ tag[1].size }})</a></li>
  {% endfor %}
</ul>
