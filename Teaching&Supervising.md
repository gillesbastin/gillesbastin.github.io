---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---

Vous trouverez sur cette page des informations utiles relatives aux cours principaux que je donne à Sciences Po Grenoble.
Certains documents sont réservés aux étudiant•es qui suivent ces cours (accès par vos identifiants étudiants sur le drive de Sciences Po).
Vous trouverez aussi des renseignements sur les étudiant•es que j'encadre. N'hésitez pas à me contacter si vous souhaitez discuter d'un sujet de recherche, en vue d'une thèse ou d'un mémoire de Master.

<h4>Enseignements | Teaching</h4>

Sociologie contemporaine (Cours fondamental de 3ème année) :
- [Syllabus](/pdf/Sociologie contemporaine (Syllabus 2019-2020).pdf)
- Bibliographie
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/0B5jxP8422LB8WkRJWGNiX1VQYTg?usp=sharing)

Histoire des pratiques journalistiques :
- [Syllabus](/pdf/Histoire des Pratiques Journalistiques.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/1jhvx69UzuCIqNWo570SBm4hXYty_pnU4)

<h4>Supervision de thèses | PhD Supervising</h4>

[Antoine Machut](https://www.pacte-grenoble.fr/membres/antoine-machut) (Structure des mondes de l'information financière en France)

[Monia Haddad](https://www.pacte-grenoble.fr/membres/monia-haddad) (Impact des humanités numériques sur le fonctionnement des mondes académiques)

[Flavie Genatio](https://www.pacte-grenoble.fr/actualites/flavie-genatio-debute-une-these-a-pacte) (Réseaux et carrières dans le monde social des <i>makers</i>)
<br><br>

---

<h4>Lectures utiles si vous participez à un de mes cours…</h4>
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
      <i>{{ post.excerpt | strip_html | truncatewords:75 }}</i>
    {%- endif -%}
    </td>
  </tr>
  {% endfor %}
</table>
