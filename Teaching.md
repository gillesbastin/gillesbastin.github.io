---
title: Enseignement
permalink: /teaching/
layout: page
categories: teaching&supervising
---

Vous trouverez sur cette page des liens vers les pages des cours principaux que je donne. Certains documents sur ces pages sont réservés aux étudiant•es qui suivent ces cours.

<table>
  <tr>
    <td width="48%" valign="top">
      <h3>Sociologie contemporaine</h3>
      L’objectif de ce cours fondamental de 3ème année est d’aborder l’étude de la sociologie contemporaine par le biais de questionnements théoriques sur des traditions de recherche, des concepts, des méthodes qui sont l’objet de discussion 
      dans la discipline telle qu’elle se pratique aujourd’hui. Ce cours se donne à la fois pour objectif de décrire le changement des sociétés contemporaines et d’interroger les tensions que ces changements provoquent dans une discipline, 
      la sociologie. En interrogeant, au fil du cours, ces tensions on se livrera donc à un exercice d’« imagination sociologique » : une réflexion sur les outils par lesquels nous pouvons essayer de comprendre le monde social dans lequel nous vivons 
      et — par là — envisager d'agir sur lui.
      Le cours est aussi motivé par les questionnements qui se sont récemment emparés des sciences sociales dans un monde marqué par les crises sanitaires et environnementales ainsi que par la résurgence de formes radicales de critiques de la société 
      comme le terrorisme. La sociologie, qui est née au moment de la grande vague des attentats anarchistes en Europe à la fin du XIXème siècle, a-t-elle quelque chose à dire sur la crise traversée aujourd’hui par la société ? Si oui, à quel prix 
      en termes de concepts et de méthodes ? Ces questions serviront de fil conducteur au cours et permettront d’avancer petit à petit vers la formulation du grand secret des sociétés contemporaines : l’existence, le maintien et la reproduction des inégalités.
      <br>
      <a href="https://gillesbastin.github.io/pdf/Sociologie_contemporaine_2022-2023_Syllabus.pdf">Syllabus</a>
      <br>
      <a href="https://cours.univ-grenoble-alpes.fr/course/view.php?id=16967">Moodle du cours</a>
      <br><br>
      <hr size = 1>
      <br>
      <h3>Design de la recherche</h3>
      Le séminaire de design de recherche vise à aider les étudiant•es du Label Recherche (niveau Master) à entreprendre ce qui constitue souvent leur premier travail de recherche. Il s’agit donc de proposer une réflexion autour de la démarche de recherche 
      et d’offrir les outils épistémologiques et méthodologiques pour leur permettre de développer cette démarche avec succès. L’enseignement est dispensé via l’invitation à des lectures portant sur la démarche de recherche et un suivi régulier et personnalisé 
      des étudiant•es. Ce suivi permet aux étudiant•es de construire l’objet de leur future recherche dans toutes ses composantes (recherche dans la littérature pertinente, rédaction d’hypothèses, choix des données utilisées et d’une approche méthodologique, 
      rédaction d’un projet de thèse, évaluation des enjeux éthiques et déontologiques du projet…).
      <br>
      <a href="https://gillesbastin.github.io/pdf/Sociologie_contemporaine_2022-2023_Syllabus.pdf">Syllabus</a>
      <br>
      <a href="https://cours.univ-grenoble-alpes.fr/course/view.php?id=18277">Moodle du cours</a>
    </td>  
    <td width="4%">
    </td>
    <td width="48%" valign="top">
      <h3>Histoire des pratiques journalistiques</h3>
      L’histoire du journalisme est souvent mal connue. L’objectif de ce cours du Master de Journalisme est de contribuer à une meilleure connaissance de cette histoire à partir de l’étude de grands moments fondateurs et de figures typiques des différentes 
      configurations de pratiques que l’on a appelées, à diverses périodes, « journalisme ». Ce cours permet aux étudiants de se familiariser, entre autres, avec l’histoire du reportage, de l’enquête, de l’objectivité ou du style littéraire en journalisme. 
      Il se conclut par une réflexion sur les mutations contemporaines des pratiques journalistiques.
      <br>
      <a href="https://gillesbastin.github.io/pdf/Histoire des Pratiques Journalistiques 2021-2022.pdf">Syllabus</a>
      <br>
      <a href="https://cours.univ-grenoble-alpes.fr/course/view.php?id=18108">Moodle du cours</a>
      <br><br>
      <hr size = 1>
      <br>
      <h3>Société algorithmique</h3>
      Ce cours aborde la question de la régulation algorithmique de la société. Sur le marché du travail, sur celui des relations amoureuses, dans les tribunaux ou dans l’espace public animé par les plateformes de réseaux sociaux, des algorithmes 
      prennent petit à petit la place des règles institutionnelles, des routines organisationnelles ou des principes professionnels pour arbitrer des situations, décider du devenir des individus ou des connaissances auxquelles ils ou elles sont exposé•es. 
      À partir d’une démarche mêlant discussion théorique et étude de cas le cours essaiera de définir ce « tournant algorithmique » de la société et d’en étudier l’origine et les effets.
      Les étudiant•es sont invité•es à participer au cours de façon active par le biais de lectures régulières, de participation à des discussions en cours et en produisant deux « papiers » dans le cadre du cours.
      <br>
      <a href="https://gillesbastin.github.io/pdf/Societe-Algorithmique-Syllabus.pdf">Syllabus</a>
      <br>
      <a href="https://cours.univ-grenoble-alpes.fr/course/view.php?id=18108">Moodle du cours</a>
    </td>
  </tr>
</table>

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
