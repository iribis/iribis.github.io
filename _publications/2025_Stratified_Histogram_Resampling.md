---
title: "Histogram Stratification for Spatio-Temporal Reservoir Sampling"
authors: <p><a href="https://iribis.github.io/">Corentin Salaün</a>,<a href="https://people.mpi-inf.mpg.de/~mbalint/">Martin Bálint</a>,<a href="https://belcour.github.io/blog/">Laurent Belcour</a>,<a href="https://eheitzresearch.wordpress.com/">Eric Heitz</a>, <a href="https://people.mpi-inf.mpg.de/~gsingh/">Gurprit Singh</a><a href="https://people.mpi-inf.mpg.de/~karol/">Karol Myszkowski</a>,</p>
collection: publications
permalink: /publication/2025_Stratified_Histogram_Resampling
excerpt: ''
date: 2025-08-10
venue: 'SIGGRAPH 2025 Conference Papers'
conference: 'ACM Siggraph 2025 (Conference track)'
citation: 'Salaun, Corentin. (2025). "Histogram Stratification for Spatio-Temporal Reservoir Sampling" <i>SIGGRAPH 2025 Conference Papers</i>.'

header:
  teaser: "http://iribis.github.io/files/Stratified_Histogram_Resampling/teaser.png"
  thumbnail: "http://iribis.github.io/files/Stratified_Histogram_Resampling/thumbnail.png"
---

![Teaser](http://iribis.github.io/files/Stratified_Histogram_Resampling/teaser.png)

### Abstract

Monte Carlo (MC) rendering is a widely used approach for photorealistic image synthesis, yet real-time applications often limit sampling to one path per pixel, resulting in high noise levels. To mitigate this, resampled importance sampling (RIS) has shown promise by approximating ideal sample distributions through a discrete set of candidates, avoiding the complexity of neural models or data-intensive structures. However, current RIS techniques often rely on random sampling, which fails to maximize the potential of the candidate pool. 
We propose a two step approach that first organizes samples candidates into local histograms and then sample the histogram using Quasi Monte Carlo and antithetic patterns. This can be done with minimal overhead and allows to reduce error in rendering to increase visual quality.
Additionally, we show how it can be combined with blue noise error distribution to perceptually reduce noise artifacts. Our approach yields a higher-quality resampling estimator with enhanced noise reduction, demonstrating significant improvements in real-time rendering tasks.

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Stratified_Histogram_Resampling/paper.pdf)<br />
<br />
