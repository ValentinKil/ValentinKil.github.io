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

## Internships
{% assign reversed_posts = site.polycopies | reverse %}
{% for post in reversed_posts %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}


## Development for the <i>Agrégation</i>

In 2022, during my preparation for the <i>[agrégation](https://en.wikipedia.org/wiki/Agrégation)</i> I wrote a few essays (in French) that you won't find in any common book: 


- <a href="https://valentinkil.github.io/files/pdf/TFgauss.pdf" class="special-link"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Another method for calculating the FT of the Gaussian
- <a href="https://valentinkil.github.io/files/pdf/MarcheAleatoire.pdf" class="special-link"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Random walk on $\mathbb{Z}^d$
- <a href="https://valentinkil.github.io/files/pdf/Legendre.pdf" class="special-link"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Extendable solutions to the Legendre's PDE
- <a href="https://valentinkil.github.io/files/pdf/Weyl.pdf" class="special-link"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Weyl's criterion
- <a href="https://valentinkil.github.io/files/pdf/LGN.pdf" class="special-link"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Strong law of large numbers (not really a development but could be)


Here is also the list of my [pairings](/files/pdf/Couplage.pdf) and my master's thesis on the lesson [Prime Numbers, Applications](/files/pdf/Memoire_nb_premier.pdf)

## 4A Seminar 
In 2023, Pauline Hellio and I organised the traditional seminar for fourth-year students at ENS Rennes. Here are the summaries of the presentations [Day 1](/files/pdf/Journee4A.pdf), [Day 2](/files/pdf/Journee4A2.pdf) as well as my personal contribution to this day (in French) [here](/files/pdf/LGN.pdf).


