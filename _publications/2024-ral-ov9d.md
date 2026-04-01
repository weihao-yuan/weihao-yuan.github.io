---
title: "OV9D: Open-Vocabulary Category-Level 9D Object Pose and Size Estimation"
collection: publications
category: journals
permalink: /publication/2024-ral-ov9d
excerpt: '' 
date: 2024-07-01
venue: 'Robotics and Automation Letters (RA-L)'
authors: 'Junhao Cai*, Yisheng He*, <b>Weihao Yuan</b>†, Siyu Zhu, Zilong Dong, Liefeng Bo, Qifeng Chen'
projecturl: 'https://ov9d.github.io/'
paperurl: 'https://arxiv.org/abs/2403.12396'
codeurl: 'https://github.com/caijunhao/ov9d'
citation: 'Junhao Cai*, Yisheng He*, <b>Weihao Yuan</b>†, Siyu Zhu, Zilong Dong, Liefeng Bo, Qifeng Chen. “OV9D: Open-Vocabulary Category-Level 9D Object Pose and Size Estimation”, IEEE Robotics and Automation Letters (RAL). 2024.'
---
This paper studies a new open-set problem, the open-vocabulary category-level object pose and size estimation. Given human text descriptions of arbitrary novel object categories, the robot agent seeks to predict the position, orientation, and size of the target object in the observed scene image. To enable such generalizability, we first introduce OO3D-9D, a large-scale photorealistic dataset for this task. Derived from OmniObject3D, OO3D-9D is the largest and most diverse dataset in the field of category-level object pose and size estimation. It includes additional annotations for the symmetry axis of each category, which help resolve symmetric ambiguity. Apart from the large-scale dataset, we find another key to enabling such generalizability is leveraging the strong prior knowledge in pre-trained visual-language foundation models. We then propose a framework built on pre-trained DinoV2 and text-to-image stable diffusion models to infer the normalized object coordinate space (NOCS) maps of the target instances. This framework fully leverages the visual semantic prior from DinoV2 and the aligned visual and language knowledge within the text-to-image diffusion model, which enables generalization to various text descriptions of novel categories. Comprehensive quantitative and qualitative experiments demonstrate that the proposed open-vocabulary method, trained on our large-scale synthesized data, significantly outperforms the baseline and can effectively generalize to real-world images of unseen categories.