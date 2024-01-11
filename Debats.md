---
title: Débat Public
permalink: /debat/
layout: page
categories: debat
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
    {% endfor %}
  </table>
<br>
