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


<table style="width:100%;border:none;">
  {% for page in site.pages %}
  {% if page.categories contains 'projets' %}
    <tr>
      <td style="width:15%;border:none;">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      <span>{{ post.date | date: date_format }}</span>
      </td>
      <td style="border:none;">
        <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
        </a>
      </td>
    </tr>
    <tr>
      <td style="width:15%;border:none;">
      </td>
      <td style="border:none;">
      {%- if site.show_excerpts -%}
        <i>{{ page.excerpt | strip_html | truncatewords:75}}</i>
      {%- endif -%}
      </td>
    </tr>
    {% endfor %}
  </table>
<br>
