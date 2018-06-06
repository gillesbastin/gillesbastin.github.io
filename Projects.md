---
title: Projects
layout: page
permalink: /projects/
---

{% for pages in site.pages %}
  {% if page.categories contains 'projets' %}
  <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
