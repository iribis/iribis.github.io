---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Maître de conférences (Associate Professor) at Université Claude Bernard Lyon-1, where I conduct research at the intersection of computer graphics, rendering, and perception.

My research focuses on real-time physically based rendering, with a particular interest in sampling, perceptual modeling, and efficient image reconstruction. I am especially interested in understanding how human visual perception can be integrated into rendering algorithms to improve the quality and efficiency of real-time graphics. My work also explores real-time denoising and reconstruction techniques for noisy Monte Carlo rendered images, with the goal of producing high-quality imagery under tight computational constraints.

My main research interests include:
* Real-time physically based rendering
* Monte Carlo sampling and variance reduction
* Applied perception for computer graphics
* Perceptual sampling and rendering
* Real-time denoising and image reconstruction
* Blue-noise error distributions and sampling correlations
* Multiple importance sampling
* Spatiotemporal sampling and reconstruction

# Latest publications
{% assign last_three_posts = site.publications | sort: 'date' | reverse | slice: 0, 3 %}
{% for post in last_three_posts %}
  {% include archive-single.html %}
{% endfor %}

