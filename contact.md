---
title: Contact
ref: contact
permalink: /contact/
description: "Contact Sandra León, Institute of Public Goods and Policies (IPP), Spanish National Research Council (CSIC), Madrid."
---
**Email:** [sandra.leon@csic.es](mailto:sandra.leon@csic.es)

Institute of Public Goods and Policies (IPP)<br>
Spanish National Research Council (CSIC)

## Profiles

{% for p in site.author.profiles -%}
- [{{ p.name }}]({{ p.url }}){: rel="me"}
{% endfor %}
