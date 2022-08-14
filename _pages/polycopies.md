---
layout: archive
title: "Polycopiés"
permalink: /polycopies/
author_profile: true
---

## Développement pour l'Agrégation 

Lors de ma préparation à l'agrégation j'ai écrit quelques dévelopements que vous ne trouverez dans aucun livre, les voici : 


- <a href="files/pdf/TFgauss.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Une autre méthode pour calculer la TF de la gaussienne
- [Une autre méthode pour calculer la TF de la gaussienne](/files/pdf/TFgauss.pdf)
- [Marche aléatoire sur $\mathbb{Z}^d$](/files/pdf/MarcheAleatoire.pdf)
- [Solutions Prolongeables de l'équation de Legendre](/files/pdf/Legendre.pdf)
- [Critère de Weyl](/files/pdf/Weyl.pdf)


Voici égallement la liste de mes [couplages](/files/pdf/Couplage.pdf) et  mon mémoire de master sur la leçon [Nombres Premiers, Applications](/files/pdf/Memoire_nb_premier.pdf)

## Stages

{% for post in site.publications %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}