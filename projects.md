---
title: projects
layout: page
permalink: /projects/
---

{% for page in site.pages %}
  {% if page.categories contains 'projets' %}
  <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
