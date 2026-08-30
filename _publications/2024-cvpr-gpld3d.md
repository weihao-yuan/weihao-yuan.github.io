---
title: "GPLD3D: Latent Diffusion of 3D Shape Generative Models by Enforcing Geometric and Physical Priors"
collection: publications
category: conferences
permalink: /publication/2024-cvpr-gpld3d
excerpt: '<span class="text-why-red">Oral Presentation</span>' 
date: 2024-06-01
venue: 'CVPR'
authors: 'Yuan Dong, Qi Zuo, Xiaodong Gu, <b>Weihao Yuan</b>, Zhengyi Zhao, Zilong Dong, Liefeng Bo, Qixing Huang'
projecturl: 'https://aigc3d.github.io/GPLD3D/'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/papers/Dong_GPLD3D_Latent_Diffusion_of_3D_Shape_Generative_Models_by_Enforcing_CVPR_2024_paper.pdf'
# codeurl: ''
citation: 'Yuan Dong, Qi Zuo, Xiaodong Gu, <b>Weihao Yuan</b>, Zhengyi Zhao, Zilong Dong, Liefeng Bo, Qixing Huang. “GPLD3D: Latent Diffusion of 3D Shape Generative Models by Enforcing Geometric and Physical Priors”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2024. <b>Oral Presentation</b>'
---
State-of-the-art man-made shape generative models usually adopt established generative models under a suitable implicit shape representation. A common theme is to perform distribution alignment, which does not explicitly model important shape priors. As a result, many synthetic shapes are not connected. Other synthetic shapes present problems of physical stability and geometric feasibility. This paper introduces a novel latent diffusion shape-generative model regularized by a quality checker that outputs a score of a latent code. The scoring function employs a learned function that provides a geometric feasibility score and a deterministic procedure to quantify a physical stability score. The key to our approach is a new diffusion procedure that combines the discrete empirical data distribution and a continuous distribution induced by the quality checker. We introduce a principled approach to determine the tradeoff parameters for learning the denoising network at different noise levels. Experimental results show that our approach outperforms state-of-the-art shape generations quantitatively and qualitatively on ShapeNet-v2.
