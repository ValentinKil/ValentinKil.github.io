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

## Development for the <i>Agrégation</i>

During my preparation for the <i>[agrégation](https://en.wikipedia.org/wiki/Agrégation)</i> I wrote a few essays (in french) that you won't find in any common book: 


- <a href="https://valentinkil.github.io/files/pdf/TFgauss.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Another method for calculating the FT of the Gaussian
- <a href="https://valentinkil.github.io/files/pdf/MarcheAleatoire.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Random walk on $\mathbb{Z}^d$
- <a href="https://valentinkil.github.io/files/pdf/Legendre.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Extendable solutions to the Legendre's PDE
- <a href="https://valentinkil.github.io/files/pdf/Weyl.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Weyl's criterion
- <a href="https://valentinkil.github.io/files/pdf/LGN.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Strong law of large numbers (not really a development but could be)


Here is also the list of my [pairings](/files/pdf/Couplage.pdf) and my master's thesis on the lesson [Prime Numbers, Applications](/files/pdf/Memoire_nb_premier.pdf)

## 4A Seminar 
This year, Pauline Hellio and I organised the traditional seminar for fourth-year students at ENS Rennes. Here are the summaries of the presentations [Day 1](/files/pdf/Journee4A.pdf), [Day 2](/files/pdf/Journee4A2.pdf) as well as my personal contribution to this day (in French) [here](/files/pdf/LGN.pdf).

## Stages

{% for post in site.polycopies %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}
