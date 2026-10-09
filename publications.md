---
title: Publications
ref: publications
permalink: /publications/
description: "Publications by Sandra León: journal articles, books, book chapters and policy papers on decentralisation, federalism, economic voting and intergovernmental relations."
---
<nav class="toc" aria-label="On this page" markdown="1">
[Journal articles](#journal-articles) · [Books](#books) · [Book chapters](#book-chapters) · [Policy papers](#policy-papers) · [Work in progress](#work-in-progress)
</nav>

## Journal articles

{% assign articles = site.papers | where: "lang", page.lang | sort: "order" %}
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

1. *La financiación autonómica: Claves para comprender un (interminable) debate* (ed.). Alianza Editorial, 2015. Review: Alain Cuenca, *Revista de Libros*, 29/06/2015 (in Spanish).
2. *Aragón es nuestro Ohio: Así votan los españoles* (Piedras de Papel, eds.). Malpaso, 2015.
3. *The Political Economy of Fiscal Decentralization. Bringing Politics to the Study of Intergovernmental Transfers*. Institut d'Estudis Autonòmics, Barcelona, 2007. Review: Santiago Lago (2007), *Administración y Ciudadanía*, 2(1), 151–154 (in Spanish).
{: .pub-list}

## Book chapters

1. <span class="pub-year">2025</span> Cataluña y la financiación singular: del acuerdo político al (todavía incierto) encaje institucional. *Informe de la Democracia en España 2024*. Fundación Alternativas.
2. <span class="pub-year">2024</span> La articulación de la gobernanza autonómica: financiación y relaciones intergubernamentales. In *Una nueva gobernanza para el siglo XXI*, eds. Pajares, Salvador and Herrera. CEPC.
3. <span class="pub-year">2023</span> Cómo ampliar el espacio político para las reformas navegando la polarización (with L. Miller). In *Un país posible. Manual de reformas políticamente viables*, ed. Teresa Raigada et al. Deusto.
4. <span class="pub-year">2022</span> Alternativas institucionales al encaje de Cataluña en España (with I. Jurado). *Informe de la Democracia en España 2022*. Fundación Alternativas.
5. <span class="pub-year">2021</span> Attributions of responsibility in multilevel states (with I. Jurado). In *The Edward Elgar Handbook on Decentralization*, ed. Ignacio Lago-Peñas. Edward Elgar.
6. <span class="pub-year">2020</span> ¿El fin del consenso territorial? (with A. Garmendia). *Informe de la Democracia en España 2019*. Fundación Alternativas.
7. <span class="pub-year">2019</span> Multi-level governance in Spain (with I. Jurado). In *The Oxford Handbook of Spanish Politics*, eds. Diego Muro and Ignacio Lago-Peñas. Oxford University Press.
8. <span class="pub-year">2019</span> Descentralización y control electoral: la atribución de responsabilidades en el Estado autonómico (with I. Jurado). In *El sector público español: reformas pendientes*, eds. Alain Cuenca and Santiago Lago Peñas. FUNCAS.
9. <span class="pub-year">2018</span> ¿Por qué culpamos a Europa? (with Ll. Orriols). In *Los españoles ante Europa: Crisis económica y social, crisis institucional y ciudadanía en España en 2014-15*, ed. Mariano Torcal.
10. <span class="pub-year">2016</span> ¿España vertebrada? Ideología, representación y territorio en el Estado Autonómico (with F. Mota and M. Salvador). In *El poder político en España: Parlamentarios y ciudadanía*. CIS.
11. <span class="pub-year">2015</span> Federalism (with P. Beramendi). In *Routledge Handbook of Comparative Political Institutions*, eds. Jennifer Gandhi and Rubén Ruiz-Rufino. Routledge.
12. <span class="pub-year">2013</span> Economic crisis and the State of Autonomies. In *Report on Fiscal Federalism 2012*. Barcelona Economic Institute.
13. <span class="pub-year">2012</span> Democracia, atribución de responsabilidades y voto económico. In *Democracia y Socialdemocracia*, eds. A. Przeworski and I. Sánchez-Cuenca. CEPC, Madrid.
14. <span class="pub-year">2012</span> Algunos déficits de la democracia en España. *Informe sobre la Democracia en España 2012*. Fundación Alternativas.
15. <span class="pub-year">2012</span> Las relaciones intergubernamentales en el Estado Autonómico. In *Foro de Estructura Territorial*. CEPC, Madrid.
16. <span class="pub-year">2010</span> Spanish Fiscal Federalism. In *The Political Economy of Regional Fiscal Flows*, eds. N. Bosch, M. Espasa and A. Solé. Edward Elgar.
17. <span class="pub-year">2005</span> El Gobierno de la Sanidad. Descentralización Sanitaria y Estructura Organizativa (co-authored). In *Informe Anual del Sistema Nacional de Salud 2003*. Observatory of the National Health System, Ministry of Health.
18. <span class="pub-year">2002</span> Sweden (with A. Rico). In *Health Care Systems in Eight Countries: Trends and Challenges*, eds. A. Dixon and E. Mossialos, 93–102. European Observatory on Health Care Systems.
{: .pub-list}

## Policy papers

- <span class="pub-year">2023</span> Claves sobre la estructura y la negociación de la financiación autonómica. Policy Papers 178, Fundació Rafael Campalans.
- <span class="pub-year">2022</span> Comparative practices in fiscal management between governments: Experiences for Philippines. Forum of Federations.
- <span class="pub-year">2022</span> Polarización y convivencia en España 2021. El papel de lo territorial (with A. Garmendia). Policy Insight, EsadeEcPol and ICIP.
- <span class="pub-year">2022</span> Study on Spanish society's divisions and consensus on climate change (with others). EsadeEcPol.
- <span class="pub-year">2020</span> De gestión centralizada a gestión autonómica de la pandemia: desafíos y oportunidades. EsadeEcPol Insight 14.
- <span class="pub-year">2020</span> Intergovernmental Relations in Spain. Lessons to be drawn for Nepal. Forum of Federations.
- <span class="pub-year">2020</span> Fiscal Federalism in Spain. Lessons to be drawn for Nepal. Forum of Federations.
- <span class="pub-year">2013</span> La descentralización y el control de los gobiernos. Colección Política Comparada, Fundación Alternativas.
- <span class="pub-year">2012</span> Algunos déficits de la democracia en España. Informe sobre la Democracia en España 2012, Fundación Alternativas.
- <span class="pub-year">2011</span> ¿Nos cambia la crisis? (with L. Orriols). Zoom Político 2011(1), Fundación Alternativas.
- <span class="pub-year">2011</span> El año más difícil (with R. Ruiz-Rufino and L. Orriols). Informe sobre la Democracia en España 2011, Fundación Alternativas.
- <span class="pub-year">2010</span> Las estrategias políticas del gobierno y la oposición (with R. Ruiz-Rufino and I. Urquizu). Informe sobre la Democracia en España 2009, Fundación Alternativas.
- <span class="pub-year">2009</span> El sistema de financiación autonómica. Informe sobre la Democracia en España 2009, Fundación Alternativas.
- <span class="pub-year">2008</span> Cuatro Años de Gobierno Socialista (with R. Ruiz-Rufino and I. Urquizu). Informe sobre la Democracia en España 2008, Fundación Alternativas.
- <span class="pub-year">2007</span> Relaciones intergubernamentales en el Estado Autonómico. Informe sobre la Democracia en España 2007, Fundación Alternativas.
{: .pub-list}

## Work in progress

- Preferences for territorial reforms in Spain and Catalonia. Evidence of a conjoint analysis (with I. Jurado)
- Partisan animosity and cooperation: A Behavioral Experiment (with I. Jurado and A. Falcó)
- Disaster in a Distrustful Democracy: Public Reactions to the DANA Crisis in Spain (with A. Garmendia)
- How Disaster Divides and Unites along Territorial Lines (with A. Garmendia)
- Territorial Affective Polarization (with A. Garmendia)
- Testing the limits of partisan bias (with Ll. Orriols)
- Losers' Consent: Foundations, Causes, and Consequences of an Elusive Concept (with I. Jurado). *Annual Review of Political Science*
{: .pub-list}
