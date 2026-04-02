---
title: "ViSA: 3D-Aware Video Shading for Real-Time Upper-Body Avatar Creation"
collection: publications
category: preprint
permalink: /publication/preprint-2025-visa
excerpt: '' 
date: 2025-12-01
venue: 'Arxiv'
authors: 'Fan Yang, Heyuan Li, Peihao Li, <b>Weihao Yuan</b>, Lingteng Qiu, Chaoyue Song, Cheng Chen, Yisheng He, Shifeng Zhang, Xiaoguang Han, Steven Hoi, Guosheng Lin'
projecturl: 'https://lhyfst.github.io/visa/'
paperurl: 'https://arxiv.org/abs/2603.28740'
# codeurl: ''

citation: 'Fan Yang, Heyuan Li, Peihao Li, <b>Weihao Yuan</b>, Lingteng Qiu, Chaoyue Song, Cheng Chen, Yisheng He, Shifeng Zhang, Xiaoguang Han, Steven Hoi, Guosheng Lin. “ViSA: 3D-Aware Video Shading for Real-Time Upper-Body Avatar Creation”.'
---
Generating high-fidelity upper-body 3D avatars from one-shot input image remains a significant challenge. Current 3D avatar generation methods, which rely on large reconstruction models, are fast and capable of producing stable body structures, but they often suffer from artifacts such as blurry textures and stiff, unnatural motion. In contrast, generative video models show promising performance by synthesizing photorealistic and dynamic results, but they frequently struggle with unstable behavior, including body structural errors and identity drift. To address these limitations, we propose a novel approach that combines the strengths of both paradigms. Our framework employs a 3D reconstruction model to provide robust structural and appearance priors, which in turn guides a real-time autoregressive video diffusion model for rendering. This process enables the model to synthesize high-frequency, photorealistic details and fluid dynamics in real time, effectively reducing texture blur and motion stiffness while preventing the structural inconsistencies common in video generation methods. By uniting the geometric stability of 3D reconstruction with the generative capabilities of video models, our method produces high-fidelity digital avatars with realistic appearance and dynamic, temporally coherent motion. Experiments demonstrate that our approach significantly reduces artifacts and achieves substantial improvements in visual quality over leading methods, providing a robust and efficient solution for real-time applications such as gaming and virtual reality.