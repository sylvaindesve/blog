---
layout: page
title: Liens utiles
permalink: /liens/
---

Voici quelques liens utiles !

{%- if site.data.liens_utiles.size > 0 -%}
  {% for lien_utile in site.data.liens_utiles %}
* [{{ lien_utile.titre | escape }}]({{ lien_utile.url}})
  {% endfor %}
{%- endif -%}
