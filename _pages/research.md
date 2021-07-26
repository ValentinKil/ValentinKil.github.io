---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

#{% for post in ordered_pages %}
#  {% include archive-single.html type="grid" %}
#{% endfor %}


<h1> Rapports de stage et mémoires <\h1> 
 
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
