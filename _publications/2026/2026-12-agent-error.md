---
title: "Conformal Agent Error Attribution"
collection: publications
permalink: /publication/2026-12-agent-error
excerpt: 
date: 2026-12-07
authors: 'Naihe Feng, Yi Sui, Shiyi Hou, Ga Wu, <b>Jesse C. Cresswell</b>'
note:
venueshort: 'NeurIPS 2026'
venue: 'Advances in Neural Information Processing Systems 2026'
paperurl: 'https://arxiv.org/abs/2605.06788'
pdf: 'https://arxiv.org/pdf/2605.06788'
codeurl: 'https://github.com/layer6ai-labs/conformal-agent-error-attribution'
videourl:
slidesurl:
citation: 'Naihe Feng, Yi Sui, Shiyi Hou, Ga Wu, Jesse C. Cresswell. Conformal Agent Error Attribution. In Advances in Neural Information Processing Systems, volume 39, 2026'
---
When multi-agent systems (MAS) fail, identifying where the decisive error occurred is the first step for automated recovery to an earlier state. Error attribution remains a fundamental challenge due to the long interaction traces that large language model-based MAS generate. This paper presents a framework for error attribution based on conformal prediction (CP) which provides finite-sample, distribution-free coverage guarantees. We introduce new algorithms for filtration-based CP designed for sequential data such as agent trajectories. Unlike existing CP algorithms, our approach predicts sets that are contiguous sequences to enable efficient recovery and debugging. We verify our theoretical guarantees on a variety of agents and datasets, show that errors can be precisely isolated, then use prediction sets to rollback MAS to correct their own errors. Our overall approach is model-agnostic, and offers a principled uncertainty layer for MAS error attribution.