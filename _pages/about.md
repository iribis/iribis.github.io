---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am a PhD student at the Saarland University (Max-Planck-Institut für Informatik) under the supervision of Gurprit Singh. I am working on stochastic Monte Carlo integration methods and their application to light transport simulations.

My main interests are :
* Blue noise error distribution
* Multiple importance sampling
* Multi-class sampling
* General variance reduction tools for Monte Carlo

# Latest publications
{% assign last_three_posts = site.publications | sort: 'date' | reverse | slice: 0, 3 %}
{% for post in last_three_posts %}
  {% include archive-single.html %}
{% endfor %}

