---
title: Blog
permalink: /blog/
layout: page
---

Tous les messages postés sur ce site sont consultables ici.
<i>All posts on this site are displayed here.</i>
<br>
<div class="home">
{%- if site.posts.size > 0 -%}
    <table style="width:100%;border:none;">
      {%- for post in site.posts -%}
      <tr>
        <td style="width:15%;border:none;">
        {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        <span>{{ post.date | date: date_format }}</span>
        </td>
        <td style="border:none;">
          <a href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
          </a>
          {%- if post.tags.size > 0 -%}
           | [{{ post.tags }}]
          {%- endif -%}
        </td>
        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </tr>
      {%- endfor -%}
    </table>
<br><br>
    <div style="text-align:center"><p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p></div>
  {%- endif -%}
</div>
