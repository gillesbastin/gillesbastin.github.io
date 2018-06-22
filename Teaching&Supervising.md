---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---



{% for post in site.categories[page.categories] %}
<h2>Actualités | Updates</h2>
  <table style="width:100%;border:none;">
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
      {%- if site.show_excerpts -%}
        {{ post.excerpt }}
      {%- endif -%}
    </tr>
  </table>
{% endfor %}
