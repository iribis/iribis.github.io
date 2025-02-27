---
title: "Online Importance Sampling for Stochastic Gradient Optimization"
authors: <p><a href="https://iribis.github.io/">Corentin Salaün</a>, <a href="https://xchhuang.github.io/">Xingchang Huang</a>, <a href="http://iliyan.com/">Iliyan Georgiev</a>, <a href="http://www0.cs.ucl.ac.uk/staff/n.mitra/">Niloy J. Mitra</a>, <a href="https://people.mpi-inf.mpg.de/~gsingh/">Gurprit Singh</a></p>
collection: publications
permalink: /publication/Online_Importance_Sampling_for_Stochastic_Gradient_Optimization
excerpt: ''
date: 2025-02-28
venue: '14th International Conference on Pattern Recognition Applications and Methods'
conference: 'ICPRAM 2025 (Full Paper) <span style="color:red"> <b>Best Student Paper Award</b></span>'
citation: 'Salaun, Corentin. (2025). "Online Importance Sampling for Stochastic Gradient Optimization" <i>ICPRAM 2025</i>.'

header:
  teaser: "http://iribis.github.io/files/Online_Importance_Sampling_for_Stochastic_Gradient_Optimization/teaser.png"
  thumbnail: "http://iribis.github.io/files/Online_Importance_Sampling_for_Stochastic_Gradient_Optimization/thumbnail.svg"
---

![Teaser](http://iribis.github.io/files/Online_Importance_Sampling_for_Stochastic_Gradient_Optimization/teaser.png)

### Abstract

Machine learning optimization often depends on stochastic gradient descent, where the precision of gradient estimation is vital for model performance. Gradients are calculated from mini-batches formed by uniformly selecting data samples from the training dataset. However, not all data samples contribute equally to gradient estimation. To address this, various importance sampling strategies have been developed to prioritize more significant samples. Despite these advancements, all current importance sampling methods encounter challenges related to computational efficiency and seamless integration into practical machine learning pipelines. In this work, we propose a practical algorithm that efficiently computes data importance on-the-fly during training, eliminating the need for dataset preprocessing. We also introduce a novel metric based on the derivative of the loss w.r.t. the network output, designed for mini-batch importance sampling. Our metric prioritizes influential data points, thereby enhancing gradient estimation accuracy. We demonstrate the effectiveness of our approach across various applications. We first perform classification and regression tasks to demonstrate improvements in accuracy. Then, we show how our approach can also be used for online data pruning by identifying and discarding data samples that contribute minimally towards the training loss. This significantly reduce training time with negligible loss in the accuracy of the model.

### Downloads and links
- <img width="20px" src="http://iribis.github.io/assets/fonts/file-pdf-solid.svg"> [Paper](http://iribis.github.io/files/Online_Importance_Sampling_for_Stochastic_Gradient_Optimization/paper.pdf)<br />
