---
title: Projets
layout: page
permalink: /projects/
---

{% for page in site.pages %}
  {% if page.categories contains 'projets' %}
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
  <br>{{ page.excerpt}}
  {% endif %}
{% endfor %}


<table style="width:100%;border:none;">
    <tr>
      <td style="border:none;">
        {% for page in site.pages %}
        {% if page.categories contains 'projets' %}
        <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
        </a>
      </td>
    </tr>
    <tr>
      <td style="border:none;">
      {%- if site.show_excerpts -%}
        <i>{{ page.excerpt | strip_html | truncatewords:75}}</i>
      {%- endif -%}
      </td>
    </tr>
    {% endfor %}
  </table>
<br>
