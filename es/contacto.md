---
title: Contacto
ref: contact
lang: es
permalink: /es/contacto/
description: "Contacto de Sandra León, Instituto de Políticas y Bienes Públicos (IPP), Consejo Superior de Investigaciones Científicas (CSIC), Madrid."
---
**Correo:** [sandra.leon@csic.es](mailto:sandra.leon@csic.es)

Instituto de Políticas y Bienes Públicos (IPP)<br>
Consejo Superior de Investigaciones Científicas (CSIC)

## Perfiles

{% for p in site.author.profiles -%}
- [{{ p.name }}]({{ p.url }}){: rel="me"}
{% endfor %}
