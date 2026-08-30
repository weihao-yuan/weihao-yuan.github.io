---
title: "IPoD: Implicit Field Learning with Point Diffusion for Generalizable 3D Object Reconstruction from Single RGB-D Images"
collection: publications
category: conferences
permalink: /publication/2024-cvpr-ipod
excerpt: '<span class="text-why-red">Highlight Presentation</span>' 
date: 2024-06-01
venue: 'CVPR'
authors: 'Yushuang Wu, Luyue Shi, Junhao Cai, <b>Weihao Yuan</b>‡, Lingteng Qiu, Zilong Dong, Liefeng Bo, Shuguang Cui, Xiaoguang Han'
projecturl: 'https://yushuang-wu.github.io/IPoD/'
paperurl: 'https://arxiv.org/abs/2404.00269'
codeurl: 'https://github.com/yushuang-wu/IPoD'
citation: 'Yushuang Wu, Luyue Shi, Junhao Cai, <b>Weihao Yuan</b>‡, Lingteng Qiu, Zilong Dong, Liefeng Bo, Shuguang Cui, Xiaoguang Han. “IPoD: Implicit Field Learning with Point Diffusion for Generalizable 3D Object Reconstruction from Single RGB-D Images”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). IEEE, 2024. <b>Highlight</b>'
---
Generalizable 3D object reconstruction from single-view RGB-D images remains a challenging task, particularly with real-world data. Current state-of-the-art methods develop Transformer-based implicit field learning, necessitating an intensive learning paradigm that requires dense query-supervision uniformly sampled throughout the entire space. We propose a novel approach, IPoD, which harmonizes implicit field learning with point diffusion. This approach treats the query points for implicit field learning as a noisy point cloud for iterative denoising, allowing for their dynamic adaptation to the target object shape. Such adaptive query points harness diffusion learning's capability for coarse shape recovery and also enhances the implicit representation's ability to delineate finer details. Besides, an additional self-conditioning mechanism is designed to use implicit predictions as the guidance of diffusion learning, leading to a cooperative system. Experiments conducted on the CO3D-v2 dataset affirm the superiority of IPoD, achieving 7.8% improvement in F-score and 28.6% in Chamfer distance over existing methods. The generalizability of IPoD is also demonstrated on the MVImgNet dataset.
