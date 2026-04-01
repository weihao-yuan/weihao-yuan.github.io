---
title: "DicFace: Dirichlet-Constrained Variational Codebook Learning for Temporally Coherent Video Face Restoration"
collection: publications
category: conferences
permalink: /publication/2025-iccv-lhm
excerpt: '<span class="text-why-red">Highlight Presentation</span>' 
date: 2025-10-01
venue: 'ICCV'
authors: 'Yan Chen, Hanlin Shang, Ce Liu, Yuxuan Chen, Hui Li, <b>Weihao Yuan</b>, Hao Zhu, Zilong Dong, Siyu Zhu'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2506.13355'
codeurl: 'https://github.com/fudan-generative-vision/DicFace'
citation: 'Yan Chen, Hanlin Shang, Ce Liu, Yuxuan Chen, Hui Li, <b>Weihao Yuan</b>, Hao Zhu, Zilong Dong, Siyu Zhu. “DicFace: Dirichlet-Constrained Variational Codebook Learning for Temporally Coherent Video Face Restoration”, International Conference on Computer Vision (ICCV). 2025.'
---
Video face restoration faces a critical challenge in maintaining temporal consistency while recovering fine facial details from degraded inputs. This paper presents a novel approach that extends Vector-Quantized Variational Autoencoders (VQ-VAEs), pretrained on static high-quality portraits, into a video restoration framework through variational latent space modeling. Our key innovation lies in reformulating discrete codebook representations as Dirichlet-distributed continuous variables, enabling probabilistic transitions between facial features across frames. A spatio-temporal Transformer architecture jointly models inter-frame dependencies and predicts latent distributions, while a Laplacian-constrained reconstruction loss combined with perceptual (LPIPS) regularization enhances both pixel accuracy and visual quality. Comprehensive evaluations on blind face restoration, video inpainting, and facial colorization tasks demonstrate state-of-the-art performance. This work establishes an effective paradigm for adapting intensive image priors, pretrained on high-quality images, to video restoration while addressing the critical challenge of flicker artifacts.