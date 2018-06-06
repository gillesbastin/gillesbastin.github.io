---
title: projects
layout: page
permalink: /projects/
---

{% for post in site.posts %}
  {% if post.categories contains 'projets' %}
  <li>{{ post.title }}</li>
  {% endif %}
{% endfor %}
