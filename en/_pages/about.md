---
permalink: /en/
title: "A propos"
excerpt: "A propos"
author_profile: true
redirect_from: 
  - /en/about/
  - /en/about.html
ref:  about
---

Website in progress 

I'm Normalien-Agrégé of Mathematics at the École Normale Supérieure de Rennes, 

Actually I'm a student in the M2 Mathematics of Randomness at Paris-Saclay University

<ul>
{% assign pages=site.pages | where:"ref", page.ref | sort: 'lang' %}
{% for page in pages %}
  <li>
    <a href="{{ page.url }}" class="{{ page.lang }}">{{ page.lang }}</a>
  </li>
{% endfor %}
</ul>