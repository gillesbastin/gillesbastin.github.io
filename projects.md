---
title: projects
layout: page
permalink: /projects/
---

{% for post in site.posts %}
  {% if post.categories contains 'projets' %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
