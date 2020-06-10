---
title: Teaching & Supervising
permalink: /teaching&supervising/
layout: page
categories: teaching&supervising
---

Vous trouverez sur cette page des liens vers les pages des cours principaux que je donne à Sciences Po Grenoble. Certains documents sur ces pages sont réservés aux étudiant•es qui suivent ces cours. Vous trouverez aussi des renseignements sur les étudiant•es que j'encadre. N'hésitez pas à me contacter si vous souhaitez discuter d'un sujet de recherche, en vue d'une thèse ou d'un mémoire de Master.

<h4>Sociologie contemporaine (Cours fondamental de 3ème année) :</h4>

L’objectif de ce cours est d’aborder l’étude de la sociologie contemporaine par le biais de questionnements théoriques sur des traditions de recherche, des concepts, des méthodes qui sont l’objet de discussion dans la discipline telle qu’elle se pratique aujourd’hui. Ce cours se donne à la fois pour objectif de décrire le changement des sociétés contemporaines et d’interroger les tensions que ces changements provoquent dans une discipline, la sociologie. En interrogeant, au fil du cours, ces tensions on se livrera donc à un exercice d’« imagination sociologique » : une réflexion sur les outils par lesquels nous pouvons tous essayer de comprendre le monde social dans lequel nous vivons et — par là — agir sur lui.
Le cours est aussi motivé par les questionnements qui se sont récemment emparés des sciences sociales dans un monde marqué par la résurgence de formes radicales de critiques de la société, notamment par le terrorisme. La sociologie, qui est née au moment de la grande vague des attentats anarchistes en Europe à la fin du XIXème siècle, a-t-elle quelque chose à dire sur la crise traversée aujourd’hui par la société ? Si oui, pourquoi est-elle si peu audible ? Ces questions serviront de fil conducteur au cours et permettront d’avancer petit à petit vers la formulation du grand secret des sociétés contemporaines : l’existence, le maintien et la reproduction des inégalités.

- [Syllabus](/pdf/Sociologie contemporaine (Syllabus 2019-2020).pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/0B5jxP8422LB8WkRJWGNiX1VQYTg?usp=sharing)

<h4>Société algorithmique (Cours spécialisé) :</h4>

Ce cours aborde la question de la régulation algorithmique de la société. Sur le marché du travail, sur celui des relations amoureuses, dans les tribunaux ou dans l’espace public animé par les plateformes de réseaux sociaux, des algorithmes prennent petit à petit la place des règles institutionnelles, des routines organisationnelles ou des principes professionnels pour arbitrer des situations, décider du devenir des individus ou des connaissances auxquelles ils ou elles sont exposé•es. À partir d’une démarche mêlant discussion théorique et étude de cas le cours essaiera de définir ce « tournant algorithmique » de la société et d’en étudier l’origine et les effets.
Les étudiant•es sont invité•es à participer au cours de façon active par le biais de lectures régulières, de participation à des discussions en cours et en produisant deux « papiers » dans le cadre du cours.

- [Syllabus](/pdf/Societe-Algorithmique-Syllabus.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/16P7jJnqoW85xtka--PfebQiOwAvZx5UQ?usp=sharing)

<h4>Histoire des pratiques journalistiques (Master de Journalisme) :</h4>

L’histoire du journalisme est souvent mal connue. L’objectif de ce cours est de contribuer à une meilleure connaissance de cette histoire à partir de l’étude de grands moments fondateurs et de figures typiques des différentes configurations de pratiques que l’on a appelées, à diverses périodes, « journalisme ». Ce cours permet aux étudiants de se familiariser, entre autres, avec l’histoire du reportage, de l’enquête, de l’objectivité ou du style littéraire en journalisme. Il se conclut par une réflexion sur les mutations contemporaines des pratiques journalistiques.

- [Syllabus](/pdf/Histoire des Pratiques Journalistiques.pdf)
- [Accès (réservé) aux documents du cours](https://drive.google.com/drive/folders/1jhvx69UzuCIqNWo570SBm4hXYty_pnU4)

<h4>Supervision de thèses | PhD Supervising</h4>

- [Antoine Machut](https://www.pacte-grenoble.fr/membres/antoine-machut) (Structure des mondes de l'information financière en France)
- [Monia Haddad](https://www.pacte-grenoble.fr/membres/monia-haddad) (Impact des humanités numériques sur le fonctionnement des mondes académiques)
- [Flavie Genatio](https://www.pacte-grenoble.fr/actualites/flavie-genatio-debute-une-these-a-pacte) (Réseaux et carrières dans le monde social des <i>makers</i>)
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
