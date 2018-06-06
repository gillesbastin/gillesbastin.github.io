---
layout: page
---

{% for post in site.posts %}
  {% if post.categories contains 'chronique' %}
  <li>{{ post.title }}</li>
  {% endif %}
{% endfor %}
