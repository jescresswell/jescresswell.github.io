---
title: "Benchmarking Robust Self-Supervised Learning Across Diverse Downstream Tasks"
collection: publications
permalink: /publication/2024-07-ssl-robustness
excerpt: 
date: 2024-07-26
authors: 'Antoni Kowalczuk, Jan Dubiński, Atiyeh Ashari Ghomi, Yi Sui, George Stein, Jiapeng Wu, <b>Jesse C. Cresswell</b>, Franziska Boenisch, Adam Dziedzic'
note:
venueshort: 'ICML 2024 Workshop FMWild'
venue: 'ICML 2024 Workshop on Foundation Models in the Wild'
paperurl: 'https://openreview.net/forum?id=U2nyqFbnRF'
pdf: 'https://arxiv.org/pdf/2407.12588.pdf'
codeurl: 'https://github.com/layer6ai-labs/ssl-robustness'
videourl:
slidesurl:
citation: 'Antoni Kowalczuk, Jan Dubiński, Atiyeh Ashari Ghomi, Yi Sui, George Stein, Jiapeng Wu, Jesse C. Cresswell, Franziska Boenisch, Adam Dziedzic. Robust Self-Supervised Learning Across Diverse Downstream Tasks. ICML 2024 Workshop on Foundation Models in the Wild'
---
Large-scale vision models have become integral in many applications due to their unprecedented performance and versatility across downstream tasks. However, the robustness of these foundation models has primarily been explored for a single task, namely image classification. The vulnerability of other common vision tasks, such as semantic segmentation and depth estimation, remains largely unknown. We present a comprehensive empirical evaluation of the adversarial robustness of self-supervised vision encoders across multiple downstream tasks. Our attacks operate in the encoder embedding space and at the downstream task output level. In both cases, current state-of-the-art adversarial fine-tuning techniques tested only for  lassification significantly degrade clean and robust performance on other tasks. Since the purpose of a foundation model is to cater to multiple applications at once, our findings reveal the need to enhance encoder robustness more broadly. We discuss potential strategies for more robust foundation vision models across diverse downstream tasks.