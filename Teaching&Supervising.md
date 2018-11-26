---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---

À noter : je serai en congé pour recherches au second semestre de l'année 2018-2019 | <i>I will be on sabbatical leave during the spring semester in 2018-2019.</i>

<h4>Enseignements | Teaching</h4>

<h5>Sociologie contemporaine (Cours fondamental de 3ème année) :</h5>
- [Syllabus](/pdf/Sociologie contemporaine — CF 3A — Bastin — 2018-19.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/0B5jxP8422LB8WkRJWGNiX1VQYTg?usp=sharing)

<h5>Histoire des pratiques journalistiques :</h5>
- [Syllabus](/pdf/Histoire des Pratiques Journalistiques.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/1jhvx69UzuCIqNWo570SBm4hXYty_pnU4)

<h4>Supervision de thèses | PhD Supervising</h4>

[Antoine Machut](https://www.pacte-grenoble.fr/membres/antoine-machut) (Structure des mondes de l'information financière en France)

[Monia Haddad](https://www.pacte-grenoble.fr/membres/monia-haddad) (Impact des humanités numériques sur le fonctionnement des mondes académiques)

[Flavie Genatio](https://www.pacte-grenoble.fr/actualites/flavie-genatio-debute-une-these-a-pacte) (Réseaux et carrières dans le monde social des <i>makers</i>)

Si vous souhaitez que je sois le tuteur académique d'un stage, merci de prendre contact par e-mail. Je vous fournirai le cas échéant les informations nécessaires pour l'écriture d'un rapport de stage.

---

<h3>Lectures utiles…</h3>
<table style="width:100%;border:none;">
{% for post in site.categories[page.categories] %}
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
      {{ post.excerpt | strip_html | truncatewords:75 }}
    {%- endif -%}
    </td>
  </tr>
  {% endfor %}
</table>
