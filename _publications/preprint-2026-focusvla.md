---
title: "FocusVLA: Focused Visual Utilization for Vision-Language-Action Models"
collection: publications
category: preprint
permalink: /publication/preprint-2026-focusvla
excerpt: '' 
date: 2026-03-01
venue: 'Arxiv'
authors: 'Yichi Zhang*, <b>Weihao Yuan</b>*‡, Yizhuo Zhang, Xidong Zhang, Jia Wan'
# projecturl: ''
paperurl: 'https://arxiv.org/abs/2603.28740'
# codeurl: ''

citation: 'Yichi Zhang*, <b>Weihao Yuan</b>*‡, Yizhuo Zhang, Xidong Zhang, Jia Wan. “FocusVLA: Focused Visual Utilization for Vision-Language-Action Models”.'
---
Vision-Language-Action (VLA) models improve action generation by conditioning policies on rich vision-language information. However, current auto-regressive policies are constrained by three bottlenecks: (1) architectural bias drives models to overlook visual details, (2) an excessive number of visual tokens makes attention difficult to focus on the correct regions, and (3) task-irrelevant visual information introduces substantial noise - together severely impairing the quality of action. In this paper, we investigate how to effectively utilize different visual representations for action generation. To this end, we first empirically validate the above issues and show that VLA performance is primarily limited by how visual information is utilized, rather than by the quality of visual representations. Based on these insights, we introduce FocusVLA, a novel paradigm that directs the model's attention to task-relevant visual regions to effectively bridge vision to action. Specifically, we first propose Modality Cascaded Attention to eliminate shortcut pathways, thereby compelling VLA models to rely on task-relevant visual details for action generation. Furthermore, we propose Focus Attention, which dynamically selects task-relevant visual patches to control information quantity while explicitly modulating their influence to suppress task-irrelevant noise. Extensive experiments on both simulated and real-world robotic benchmarks demonstrate that FocusVLA not only effectively leverages visual details to perform dexterous manipulations, but also substantially improves performance and accelerates convergence across a variety of tasks.