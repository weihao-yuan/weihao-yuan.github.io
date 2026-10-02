---
title: "Glob3R: Global Structure-from-Motion with 3D Foundation Models"
collection: publications
category: conferences
permalink: /publication/2026-nips-global3r
excerpt: '' 
date: 2026-11-01
venue: 'NeurIPS'
authors: 'Junyuan Deng, Heng Li, Kejie Qiu, Lingteng Qiu, Rui Peng, Weichao Shen, <b>Weihao Yuan</b>, Siyu Zhu, Zilong Dong, Ping Tan'
projecturl: 'https://laiyingxin2.github.io/Projects/'
paperurl: 'https://arxiv.org/abs/2605.27154'
# codeurl: ''

citation: 'Junyuan Deng, Heng Li, Kejie Qiu, Lingteng Qiu, Rui Peng, Weichao Shen, <b>Weihao Yuan</b>, Siyu Zhu, Zilong Dong, Ping Tan. “Glob3R: Global Structure-from-Motion with 3D Foundation Models”. Conference on Neural Information Processing Systems (NeurIPS). 2026'
---
Recent 3D geometric foundation models, such as VGGT, provide robust feed-forward 3D reconstruction by directly predicting camera poses and 3D scene points from input images. However, their results remain inaccurate, and scaling them to long sequences or large unordered image sets typically requires chunk-wise processing, which can introduce drift and inconsistency. We present Glob3R, a global SfM-style reconstruction built on 3D foundation models. Our key idea is to explicitly optimize feed-forward geometric predictions. To this end, we augment a frozen Pi3X backbone with a lightweight dense matching head that predicts image warps between selected reference frames and neighboring views. These dense warps are converted into sparse but reliable multi-view feature tracks, which provide correspondence constraints for global optimization. We further introduce a keyframe-based sliding-window association strategy that propagates tracks and relative poses across overlapping windows, enabling scalable reconstruction. Finally, we perform global motion averaging and bundle adjustment to refine camera poses, reduce scale inconsistencies, and recover dense scene geometry. Extensive experiments on indoor, outdoor, large-scale driving, and unordered SfM benchmarks demonstrate that Glob3R achieves robust and accurate reconstruction. It consistently improves over feed-forward foundation-model baselines and recent scalable reconstruction methods, while being more robust than classical SfM pipelines. The refined poses also lead to higher-quality neural rendering, validating the benefit of combining foundation-model priors with global geometric optimization.