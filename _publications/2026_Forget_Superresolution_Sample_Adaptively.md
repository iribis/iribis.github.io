---
title: "Forget Superresolution, Sample Adaptively (when Path Tracing)"
authors: <p><a href="https://people.mpi-inf.mpg.de/~mbalint/">Martin Bálint</a>, <a href="https://iribis.github.io/">Corentin Salaün</a>, <a href="https://people.mpi-inf.mpg.de/~hpseidel/">Hans-Peter Seidel</a> and <a href="https://people.mpi-inf.mpg.de/~karol/">Karol Myszkowski</a></p>
collection: publications
permalink: /publication/2026_Forget_Superresolution_Sample_Adaptively
excerpt: ''
date: 2026-08-10
venue: 'ACM Transactions on Graphics, Volume 45'
conference: 'ACM Siggraph asia 2026 (Journal track)'
citation: 'Bálint, Martin. (2026). "Forget Superresolution, Sample Adaptively (when Path Tracing)" <i>ACM Transactions on Graphics, Volume 45</i>.'

header:
  teaser: "http://iribis.github.io/files/Forget_Superresolution_Sample_Adaptively/teaser.jpg"
  thumbnail: "http://iribis.github.io/files/Forget_Superresolution_Sample_Adaptively/thumbnail.jpg"
---

![Teaser](http://iribis.github.io/files/Forget_Superresolution_Sample_Adaptively/teaser.jpg)

### Abstract

Real-time path tracing increasingly operates under extremely low sampling budgets, often below one sample per pixel, as rendering complexity, resolution, and frame-rate requirements continue to rise. Superresolution is widely used in production because it reduces path-tracing cost by tracing rays on a coarser image grid and reconstructing missing details. This creates a uniform tradeoff between cost and spatial detail: every image region receives the same reduced ray budget, although path-tracing noise, reconstruction difficulty, and perceptual importance vary strongly across the image. Adaptive sampling offers a compelling alternative, but existing end-to-end approaches rely on approximations that break down in sparse regimes.
We introduce an end-to-end adaptive sampling and denoising pipeline explicitly designed for the sub-1-spp regime. Our method uses a stochastic formulation of sample placement that enables gradient estimation despite discrete sampling decisions, allowing stable training of a neural sampler at low sampling budgets. To better align optimization with human perception, we propose a tone-mapping-aware training pipeline that integrates differentiable filmic operators and a state-of-the-art perceptual loss, preventing oversampling of regions with low visual impact.
In addition, we introduce a gather-based pyramidal denoising filter and a learnable generalization of albedo demodulation tailored to sparse sampling. Our results show consistent improvements over uniform sparse sampling, with notably better reconstruction of perceptually critical details such as specular highlights and shadow boundaries, and demonstrate that adaptive sampling remains effective in the sub-1-spp regime.

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Forget_Superresolution_Sample_Adaptively/paper.pdf)<br />
- <i class="fas fa-fw fa-link" aria-hidden="true"></i> [Project Page](https://balint.io/fssa/)<br />
<br />
