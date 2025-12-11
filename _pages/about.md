---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I recently completed my PhD at Saarland University (Max Planck Institute for Informatics) under the supervision of Gurprit Singh. I am currently continuing as a postdoctoral researcher at the Max Planck Institute for Informatics with Karol Myszkowski.

My research focuses on Monte Carlo integration for rendering and machine learning, with a particular interest in variance reduction and sampling theory. More recently, I have been exploring how sampling correlations—both per-pixel and across the image domain—can be leveraged to improve real-time physically based rendering, and how perceptual modeling can further guide sampling to maximize visual quality.

My main research interests include:
* Blue-noise error distributions
* Multiple importance sampling
* Multi-class and structured sampling
* General variance-reduction techniques for Monte Carlo methods

# Latest publications
{% assign last_three_posts = site.publications | sort: 'date' | reverse | slice: 0, 3 %}
{% for post in last_three_posts %}
  {% include archive-single.html %}
{% endfor %}

