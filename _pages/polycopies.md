---
layout: archive
title: "Polycopiés"
permalink: /polycopies/
author_profile: true
---

## Développement pour l'Agrégation 

Lors de ma préparation à l'agrégation j'ai écrit quelques dévelopements que vous ne trouverez dans aucun livre, les voici : 


- <a href="https://valentinkil.github.io/files/pdf/TFgauss.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Une autre méthode pour calculer la TF de la gaussienne
- <a href="https://valentinkil.github.io/files/pdf/MarcheAleatoire.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Marche aléatoire sur $\mathbb{Z}^d$
- <a href="https://valentinkil.github.io/files/pdf/Legendre.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Solutions Prolongeables de l'équation de Legendre
- <a href="https://valentinkil.github.io/files/pdf/Weyl.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Critère de Weyl
- <a href="https://valentinkil.github.io/files/pdf/LGN.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a> Loi forte des grands nombres


Voici égallement la liste de mes [couplages](/files/pdf/Couplage.pdf) et  mon mémoire de master sur la leçon [Nombres Premiers, Applications](/files/pdf/Memoire_nb_premier.pdf)

## 4A Seminar 
This year, Pauline Hellio and I organised the traditional seminar for fourth-year students at ENS Rennes. Here are the summaries of the presentations [Day 1](/files/pdf/Journee4A.pdf), [Day 2](/files/pdf/Journee4A2.pdf) as well as my personal contribution to this day [here](/files/pdf/LGN.pdf).

## Stages

{% for post in site.polycopies %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}