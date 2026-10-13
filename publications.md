---
title: Publications
ref: publications
permalink: /publications/
description: "Publications by Sandra León: journal articles, books, book chapters and policy papers on decentralization, federalism, economic voting and intergovernmental relations."
---
<nav class="toc" aria-label="On this page" markdown="1">
[Journal articles](#journal-articles) · [Books](#books) · [Book chapters](#book-chapters) · [Policy papers](#policy-papers) · [Other articles](#other-articles) · [Work in progress](#work-in-progress)
</nav>

## Journal articles (selected)
{: #journal-articles}

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

## Books

{% include other-pubs.html items=site.data.other_publications.books %}

<h3 class="pub-subhead">Edited books</h3>

{% include other-pubs.html items=site.data.other_publications.edited_books %}

## Book chapters

{% include other-pubs.html items=site.data.other_publications.chapters %}

## Policy papers

{% include other-pubs.html items=site.data.other_publications.policy %}

## Other articles and working papers
{: #other-articles}

{% include other-pubs.html items=site.data.other_publications.other %}

## Work in progress

{% include other-pubs.html items=site.data.other_publications.wip grouped=false %}
