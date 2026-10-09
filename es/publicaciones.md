---
title: Publicaciones
ref: publications
lang: es
permalink: /es/publicaciones/
description: "Publicaciones de Sandra León: artículos en revistas, libros, capítulos de libro e informes sobre descentralización, federalismo, polarización y relaciones intergubernamentales."
---
<nav class="toc" aria-label="En esta página" markdown="1">
[Artículos](#articulos) · [Libros](#libros) · [Capítulos de libro](#capitulos) · [Informes y policy papers](#informes) · [Trabajos en curso](#en-curso)
</nav>

## Artículos en revistas (selección)
{: #articulos}

{% assign articles = site.papers | sort: "order" %}
{% assign years = articles | group_by: "year" %}
<div class="by-year">
{%- for y in years %}
<h3 class="year">{{ y.name }}</h3>
<ul class="pub-list plain">
{%- for p in y.items %}
  <li>{% include pub-item.html paper=p %}</li>
{%- endfor %}
</ul>
{%- endfor %}
</div>

## Libros
{: #libros}

{% include other-pubs.html items=site.data.other_publications.books %}

## Capítulos de libro
{: #capitulos}

{% include other-pubs.html items=site.data.other_publications.chapters %}

## Informes y policy papers
{: #informes}

{% include other-pubs.html items=site.data.other_publications.policy %}

## Trabajos en curso
{: #en-curso}

{% include other-pubs.html items=site.data.other_publications.wip grouped=false %}
