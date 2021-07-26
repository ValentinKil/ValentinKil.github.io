---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h1> Rapports et mémoires </h1>

{% for post in site.publications.RapportMemoire reversed %}
  {% include archive-single.html %}
{% endfor %}

