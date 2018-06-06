---
title: Projects
layout: page
permalink: /projects/
---

{% for page in site.pages %}
  {% if page.categories contains 'projets' %}
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
  {{ page.excerpt }}
  {% endif %}
{% endfor %}
