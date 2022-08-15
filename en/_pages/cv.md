---
layout: archive
title: "Curriculum Vitae"
permalink: /en/cv/
author_profile: true
redirect_from:
  - /en/resume
ref: cv
---

<iframe src="/files/pdf/CV classique ENG.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>

You can dowload my resume <I> (Last update : August 2022) </I> [english](/files/pdf/CV classique ENG.pdf), [français](/files/pdf/CV classique FR.pdf) 
My[Linkedin](http://www.linkedin.com/in/valentin-kilian-277777209/) is updated more regularly. 


<ul>
{% assign pages=site.pages | where:"ref", page.ref | sort: 'lang' %}
{% for page in pages %}
  <li>
    <a href="{{ page.url }}" class="{{ page.lang }}">{{ page.lang }}</a>
  </li>
{% endfor %}
</ul>