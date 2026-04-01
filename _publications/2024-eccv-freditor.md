---
title: "Freditor: High-Fidelity and Transferable NeRF Editing by Frequency Decomposition"
collection: publications
category: conferences
permalink: /publication/2024-eccv-freditor
excerpt: '' 
date: 2024-09-01
venue: 'ECCV'
authors: 'Yisheng He, <b>Weihao Yuan</b>†, Siyu Zhu, Zilong Dong, Liefeng Bo, Qixing Huang'
projecturl: 'https://aigc3d.github.io/freditor/'
paperurl: 'https://arxiv.org/abs/2404.02514'
# codeurl: 'https://github.com/ethnhe/freditor'
citation: 'Yisheng He, <b>Weihao Yuan</b>†, Siyu Zhu, Zilong Dong, Liefeng Bo, Qixing Huang. “Freditor: High-Fidelity and Transferable NeRF Editing by Frequency Decomposition”, European Conference on Computer Vision (ECCV). 2024.'
---
This paper enables high-fidelity, transferable NeRF editing by frequency decomposition. Recent NeRF editing pipelines lift 2D stylization results to 3D scenes while suffering from blurry results, and fail to capture detailed structures caused by the inconsistency between 2D editings. Our critical insight is that low-frequency components of images are more multiview-consistent after editing compared with their high-frequency parts. Moreover, the appearance style is mainly exhibited on the low-frequency components, and the content details especially reside in high-frequency parts. This motivates us to perform editing on low-frequency components, which results in high-fidelity edited scenes. In addition, the editing is performed in the low-frequency feature space, enabling stable intensity control and novel scene transfer. Comprehensive experiments conducted on photorealistic datasets demonstrate the superior performance of high-fidelity and transferable NeRF editing. 
