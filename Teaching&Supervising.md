---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---

À noter : je serai en congé pour recherches au second semestre de l'année 2018-2019 | <i>I will be on sabbatical leave during the spring semester in 2018-2019.</i>

<h3>Enseignements | Teaching</h3>

Sociologie contemporaine (Cours fondamental de 3ème année) :
- [Syllabus](/pdf/Sociologie contemporaine — CF 3A — Bastin — 2018-19.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/0B5jxP8422LB8WkRJWGNiX1VQYTg?usp=sharing)

Histoire des pratiques journalistiques :
- Syllabus
- Accès au cours en ligne sur Chamilo

<h3>Supervision de thèses | PhD Supervising</h3>

[Antoine Machut](https://www.pacte-grenoble.fr/membres/antoine-machut) (Structure des mondes de l'information financière en France)

[Monia Haddad](https://www.pacte-grenoble.fr/membres/monia-haddad) (Impact des humanités numériques sur le fonctionnement des mondes académiques)

[Flavie Genatio](https://www.pacte-grenoble.fr/actualites/flavie-genatio-debute-une-these-a-pacte) (Réseaux et carrières dans le monde social des <i>makers</i>)

Si vous souhaitez que je sois le tuteur académique d'un stage, merci de prendre contact par e-mail. Je vous fournirai le cas échéant les informations nécessaires pour l'écriture d'un rapport de stage.


{% for post in site.categories[page.categories] %}
<h3>Related posts</h3>
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
  
