---
title: "MVImgNet2.0: A Larger-scale Dataset of Multi-view Images"
collection: publications
category: journals
permalink: /publication/2024-tog-mvimagenet2
excerpt: '' 
date: 2024-12-01
venue: 'Transactions on Graphics (TOG)'
authors: 'Xiaoguang Han*, Yushuang Wu*, Luyue Shi*, Haolin Liu*, Hongjie Liao, Lingteng Qiu, <b>Weihao Yuan</b>‡, Xiaodong Gu, Zilong Dong, Shuguang Cui'
projecturl: 'https://luyues.github.io/mvimgnet2/'
paperurl: 'https://arxiv.org/abs/2412.01430'
codeurl: 'https://github.com/GAP-LAB-CUHK-SZ/MVImgNet2.0'
citation: 'Xiaoguang Han*, Yushuang Wu*, Luyue Shi*, Haolin Liu*, Hongjie Liao, Lingteng Qiu, <b>Weihao Yuan</b>‡, Xiaodong Gu, Zilong Dong, Shuguang Cui. “MVImgNet2.0: A Larger-scale Dataset of Multi-view Images”, ACM Transactions on Graphics (TOG). 2024.'
---
MVImgNet is a large-scale dataset that contains multi-view images of ~220k real-world objects in 238 classes. As a counterpart of ImageNet, it introduces 3D visual signals via multi-view shooting, making a soft bridge between 2D and 3D vision. This paper constructs the MVImgNet2.0 dataset that expands MVImgNet into a total of ~520k objects and 515 categories, which derives a 3D dataset with a larger scale that is more comparable to ones in the 2D domain. In addition to the expanded dataset scale and category range, MVImgNet2.0 is of a higher quality than MVImgNet owing to four new features: (i) most shoots capture 360-degree views of the objects, which can support the learning of object reconstruction with completeness; (ii) the segmentation manner is advanced to produce foreground object masks of higher accuracy; (iii) a more powerful structure-from-motion method is adopted to derive the camera pose for each frame of a lower estimation error; (iv) higher-quality dense point clouds are reconstructed via advanced methods for objects captured in 360-degree views, which can serve for downstream applications. Extensive experiments confirm the value of the proposed MVImgNet2.0 in boosting the performance of large 3D reconstruction models.