---
title: Projets
layout: page
permalink: /projects/
---

Projets de recherche en cours.
<br><i>Ongoing research projects</i>
<br><br>
{% for page in site.pages %}
  {% if page.categories contains 'projets' %}
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
  <br>{{ page.excerpt | strip_html | truncatewords:75}}
  {% endif %}
{% endfor %}
