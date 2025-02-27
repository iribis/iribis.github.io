---
title: "Multiple Importance Sampling for Stochastic Gradient Estimation"
authors: <p><a href="https://iribis.github.io/">Corentin Salaün</a>, <a href="https://xchhuang.github.io/">Xingchang Huang</a>, <a href="http://iliyan.com/">Iliyan Georgiev</a>, <a href="http://www0.cs.ucl.ac.uk/staff/n.mitra/">Niloy J. Mitra</a>, <a href="https://people.mpi-inf.mpg.de/~gsingh/">Gurprit Singh</a></p>
collection: publications
permalink: /publication/Multiple_Importance_Sampling_for_Stochastic_Gradient_Estimation
excerpt: ''
date: 2025-02-28
venue: '14th International Conference on Pattern Recognition Applications and Methods'
conference: 'ICPRAM 2025 (Short Paper)'
citation: 'Salaun, Corentin. (2025). "Multiple Importance Sampling for Stochastic Gradient Estimation" <i>ICPRAM 2025</i>.'

header:
  teaser: "http://iribis.github.io/files/Multiple_Importance_Sampling_for_Stochastic_Gradient_Estimation/teaser.png"
  thumbnail: "http://iribis.github.io/files/Multiple_Importance_Sampling_for_Stochastic_Gradient_Estimation/thumbnail.png"
---

![Teaser](http://iribis.github.io/files/Multiple_Importance_Sampling_for_Stochastic_Gradient_Estimation/teaser.png)

### Abstract

We introduce a theoretical and practical framework for efficient importance sampling of mini-batch samples for gradient estimation from single and multiple probability distributions. To handle noisy gradients, our framework dynamically evolves the importance distribution during training by utilizing a self-adaptive metric. Our framework combines multiple, diverse sampling distributions, each tailored to specific parameter gradients. This approach facilitates the importance sampling of vector-valued gradient estimation. Rather than naively combining multiple distributions, our framework involves optimally weighting data contribution across multiple distributions. This adapted combination of multiple importance yields superior gradient estimates, leading to faster training convergence. We demonstrate the effectiveness of our approach through empirical evaluations across a range of optimization tasks like classification and regression on both image and point cloud datasets.

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Multiple_Importance_Sampling_for_Stochastic_Gradient_Estimation/paper.pdf)<br />