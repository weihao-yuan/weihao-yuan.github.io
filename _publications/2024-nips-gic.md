---
title: "Gaussian-Informed Continuum for Physical Property Identification and Simulation"
collection: publications
category: conferences
permalink: /publication/2024-nips-gic
excerpt: '<span class="text-why-red">Oral Presentation, Top 0.39%, 61/15671</span>' 
date: 2024-12-01
venue: 'NeurIPS'
authors: 'Junhao Cai*, Yuji Yang*, <b>Weihao Yuan</b>†, Yisheng He, Zilong Dong, Liefeng Bo, Hui Cheng, Qifeng Chen'
projecturl: 'https://jukgei.github.io/project/gic/'
paperurl: 'https://arxiv.org/abs/2406.14927'
codeurl: 'https://github.com/Jukgei/gic'
citation: 'Junhao Cai*, Yuji Yang*, <b>Weihao Yuan</b>†, Yisheng He, Zilong Dong, Liefeng Bo, Hui Cheng, Qifeng Chen. “Gaussian-Informed Continuum for Physical Property Identification and Simulation”, Conference on Neural Information Processing Systems (NeurIPS). 2024.'
---
This paper studies the problem of estimating physical properties (system identification) through visual observations. To facilitate geometry-aware guidance in physical property estimation, we introduce a novel hybrid framework that leverages 3D Gaussian representation to not only capture explicit shapes but also enable the simulated continuum to render object masks as 2D shape surrogates during training. We propose a new dynamic 3D Gaussian framework based on motion factorization to recover the object as 3D Gaussian point sets across different time states. Furthermore, we develop a coarse-to-fine filling strategy to generate the density fields of the object from the Gaussian reconstruction, allowing for the extraction of object continuums along with their surfaces and the integration of Gaussian attributes into these continuum. In addition to the extracted object surfaces, the Gaussian-informed continuum also enables the rendering of object masks during simulations, serving as 2D-shape guidance for physical property estimation. Extensive experimental evaluations demonstrate that our pipeline achieves state-of-the-art performance across multiple benchmarks and metrics. Additionally, we illustrate the effectiveness of the proposed method through real-world demonstrations, showcasing its practical utility.