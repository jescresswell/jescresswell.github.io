---
title: "Training Fair Tabular Foundation Models"
collection: publications
permalink: /publication/2026-06-fairtfm
excerpt: 
date: 2026-06-30
authors: 'Patrik Kenfack, <b>Jesse C. Cresswell</b>, Anthony L. Caterini, Samira Ebrahimi Kahou, Ulrich Aïvodji'
note: 'Spotlight Oral Award'
venueshort: 'ICML 2026 Workshop FMSD'
venue: 'ICML 2026 Workshop on Foundation Models for Structured Data'
paperurl: 'https://openreview.net/forum?id=ajIvCEbadL'
pdf: 'https://openreview.net/pdf?id=ajIvCEbadL'
codeurl:
videourl:
slidesurl:
citation: 'Patrik Kenfack, Jesse C. Cresswell, Anthony L. Caterini, Samira Ebrahimi Kahou, Ulrich Aïvodji. Training Fair Tabular Foundation Models. ICML 2026 Workshop on Foundation Models for Structured Data'
---
Tabular Foundation Models (TFMs) have emerged as leading methods for tabular predictive tasks, leveraging in-context learning to predict on new data without task-specific training. Despite the increased use of TFMs in high-stakes decision-making, their fairness properties remain largely unexplored. In this work, we incorporate fairness constraints directly into TFM training, enabling fair predictions in a single forward pass. Our approach addresses two key challenges: limited access to sensitive attributes in training data, and the incompatibility of existing fairness techniques with the in-context learning paradigm. We propose \ftfm{}, a scalable training strategy based on synthetic fairness tasks and a fairness-aware architecture using a gradient reversal layer, which encourages the model to learn representations invariant to sensitive attributes. Experiments on 120 fairness tasks show consistent improvements in fairness while maintaining competitive accuracy.