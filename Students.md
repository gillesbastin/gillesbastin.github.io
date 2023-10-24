---
title: Etudiants
permalink: /students/
layout: page
categories: teaching&supervising
---

Vous trouverez ici des renseignements sur les étudiant•es que j'encadre. N'hésitez pas à me contacter si vous souhaitez discuter d'un sujet de recherche, en vue d'une thèse ou d'un mémoire de Master.

<h4>Supervision de thèses | PhD Supervising</h4>

<h5>En cours | Ongoing</h5>

- [Anastasia Magat](https://www.pacte-grenoble.fr/membres/anastasia-magat) : La participation des habitants des quartiers sensibles dans la production et la réception de l’image de leur quartier sur les réseaux sociaux
- [Ange Richard](https://www.pacte-grenoble.fr/membres/ange-richard) : Mesure et analyse des biais de genre dans les médias (avec [François Portet](https://lig-membres.imag.fr/portet/home.php))
- [Guillaume Le Lay]() : Apprendre l'IA : la production sociale du savoir algorithmique (avec [Séverine Louvel](https://www.pacte-grenoble.fr/membres/severine-louvel))

<h5>Soutenues | Defended</h5>

- [Antoine Machut](https://www.pacte-grenoble.fr/membres/antoine-machut) : Structure des mondes de l'information financière en France (Antoine Machut est actuellement post-doctorant au Medialab de Sciences Po. Avant cela, il a été post-doctorant au Data Institute de l’Université Grenoble Alpes puis post-doctorant sur l’ANR VICO (Pacte, dir. P. Mercklé) et sur l’ANR ProVirCap (IRISSO, dir. L. Bereni)).

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
