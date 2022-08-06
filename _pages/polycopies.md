---
layout: archive
title: "Polycopiés"
permalink: /polycopies/
author_profile: true
---

## Développement pour l'Agrégation 

Lors de ma préparation à l'agrégation j'ai écrit quelques dévelopement que vous nous trouverez dans aucun livre, les voici : 

Calcul d’intégrale par une DSE
Marche aléatoire sur Z^d 
Méthode de Newton
Théorème d’échantillonnage de Shannon 
Equation de Legendre
Critère de Weyl

## Stages

{% for post in site.polycopies reversed %}
  {% include archive-single.html %}
{% endfor %}
