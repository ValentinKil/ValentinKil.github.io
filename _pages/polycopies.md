---
layout: archive
title: "Polycopiés"
permalink: /polycopies/
author_profile: true
---

## Développement pour l'Agrégation 

Lors de ma préparation à l'agrégation j'ai écrit quelques dévelopement que vous ne trouverez dans aucun livre, les voici : 

- Calcul d’intégrale par une DSE
- Marche aléatoire sur Z^d 
<!-- - Théorème d’échantillonnage de Shannon -->- 
- [Equation de Legendre](/files/pdf/Legendre.pdf)
<!-- - Critère de Weyl -->
Voici égallement mon mémoire de master sur la leçon [Nombres Premiers et Applications](/files/pdf/Memoire_nb_premier.pdf)

## Stages

{% for post in site.publications %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}