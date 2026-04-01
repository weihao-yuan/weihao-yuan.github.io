---
title: "RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D"
collection: publications
category: conferences
permalink: /publication/2024-cvpr-richdreamer
excerpt: '<span class="text-why-red">Highlight Presentation</span>' 
date: 2024-06-01
venue: 'CVPR'
authors: 'Lingteng Qiu, Guanying Chen, Xiaodong Gu, Qi Zuo, Mutian Xu, Yushuang Wu, <b>Weihao Yuan</b>, Zilong Dong, Liefeng Bo, Xiaoguang Han'
projecturl: 'https://aigc3d.github.io/richdreamer/'
paperurl: 'https://arxiv.org/abs/2311.16918'
codeurl: 'https://github.com/modelscope/RichDreamer'
citation: 'Lingteng Qiu, Guanying Chen, Xiaodong Gu, Qi Zuo, Mutian Xu, Yushuang Wu, <b>Weihao Yuan</b>, Zilong Dong, Liefeng Bo, Xiaoguang Han. “RichDreamer: A Generalizable Normal-Depth Diffusion Model for Detail Richness in Text-to-3D”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2024.'
---
Lifting 2D diffusion for 3D generation is a challenging problem due to the lack of geometric prior and the complex entanglement of materials and lighting in natural images. Existing methods have shown promise by first creating the geometry through score-distillation sampling (SDS) applied to rendered surface normals, followed by appearance modeling. However, relying on a 2D RGB diffusion model to optimize surface normals is suboptimal due to the distribution discrepancy between natural images and normals maps, leading to instability in optimization. In this paper, recognizing that the normal and depth information effectively describe scene geometry and be automatically estimated from images, we propose to learn a generalizable Normal-Depth diffusion model for 3D generation. We achieve this by training on the large-scale LAION dataset together with the generalizable image-to-depth and normal prior models. In an attempt to alleviate the mixed illumination effects in the generated materials, we introduce an albedo diffusion model to impose data-driven constraints on the albedo component. Our experiments show that when integrated into existing text-to-3D pipelines, our models significantly enhance the detail richness, achieving state-of-the-art results.
