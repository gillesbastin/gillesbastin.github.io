---
title: Le Monde des Livres
permalink: /livres/
layout: page
categories: bookreview
---


  <table style="width:100%;border:none;">
  {% for post in site.categories[page.categories] limit:none %}
    <tr>
      <td style="width:15%;border:none;">
      {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
      <span>{{ post.date | date: date_format }}</span>
      </td>
      <td style="border:none;">
        <a href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </td>
    </tr>
    <tr>
      <td style="width:15%;border:none;">
      </td>
      <td style="border:none;">
      {%- if site.show_excerpts -%}
        <i>{{ post.excerpt | strip_html | truncatewords:300 }}</i>
      {%- endif -%}
      </td>
    </tr>
    {% endfor %}
  </table>
<br>
