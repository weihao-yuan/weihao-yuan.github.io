---
title: "Motions as Queries: One-Stage Multi-Person Holistic Human Motion Capture"
collection: publications
category: conferences
permalink: /publication/2025-cvpr-anigs
excerpt: '' 
date: 2025-06-01
venue: 'CVPR'
authors: 'Kenkun Liu*, Yurong Fu*, <b>Weihao Yuan</b>*, Jing Lin, Peihao Li, Xiaodong Gu, Lingteng Qiu, Haoqian Wang, Zilong Dong, Xiaoguang Han'
# projecturl: ''
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Motions_as_Queries_One-Stage_Multi-Person_Holistic_Human_Motion_Capture_CVPR_2025_paper.html'
codeurl: 'https://github.com/KenkunLiu/MaQ'
citation: 'Kenkun Liu*, Yurong Fu*, <b>Weihao Yuan</b>*, Jing Lin, Peihao Li, Xiaodong Gu, Lingteng Qiu, Haoqian Wang, Zilong Dong, Xiaoguang Han. “Motions as Queries: One-Stage Multi-Person Holistic Human Motion Capture”, IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2025.'
---
Existing methods for capturing multi-person holistic human motions from a monocular video usually involve integrating the detector, the tracker, and the human pose & shape estimator into a cascaded system. Differently, we develop a one-stage multi-person holistic human motion capture system, which 1) employs only one network, enabling significant benefits from the end-to-end training on a large-scale dataset; 2) enables performance improving of the tracking module during training, avoiding being limited by a pre-trained tracker; 3) captures the motions of all individuals within a single shot, rather than tracking and estimating each person sequentially. In this system, each query within a temporal cross-attention module is responsible for the long motion of a specific individual, implicitly aggregating individual-specific information throughout the entire video. To further boost the proposed system from end-to-end training, we also construct a synthetic human video dataset, with multi-person and whole-body annotations. Extensive experiments across different datasets demonstrate both the efficacy and the efficiency of both the proposed method and the dataset.