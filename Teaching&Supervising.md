---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---

<h3>Enseignements | Teaching</h3>

Vous trouverez à la rentrée académique des informations sur les cours que je donne et leur validation.

<h3>Supervision | Supervising</h3>

Si vous souhaitez que je sois le tuteur académique d'un stage, merci de prendre contact par e-mail. Je vous fournirai le cas échéant les informations nécessaires pour l'écriture d'un rapport de stage.

Supervision d'étudiants en thèse : Antoine Machut (Structure des mondes de l'information financière en France) ; Monia Haddad (Impact des humanités numériques sur le focntionnement des mondes académiques).


{% for post in site.categories[category] %}
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
