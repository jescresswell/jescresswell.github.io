---
title: "Scaling Up Diffusion and Flow-based XGBoost Models"
collection: publications
permalink: /publication/2024-07-scaling-xgb
excerpt: 
date: 2024-07-26
authors: '<b>Jesse C. Cresswell</b>, Taewoo Kim'
note:
venueshort: 'ICML 2024 Workshop AI4Science'
venue: 'ICML 2024 Workshop on AI for Science'
paperurl: 'https://arxiv.org/abs/2408.16046'
pdf: 'https://arxiv.org/pdf/2408.16046.pdf'
codeurl: 'https://github.com/layer6ai-labs/calo-forest'
videourl:
slidesurl:
citation: 'Jesse C. Cresswell, Taewoo Kim. Scaling Up Diffusion and Flow-based XGBoost Models. ICML 2024 Workshop on AI for Science'
---
Novel machine learning methods for tabular data generation are often developed on small datasets which do not match the scale required for scientific applications. We investigate a recent proposal to use XGBoost as the function approximator in diffusion and flow-matching models on tabular data, which proved to be extremely memory intensive, even on tiny datasets. In this work, we conduct a critical analysis of the existing implementation from an engineering perspective, and show that these limitations are not fundamental to the method; with better implementation it can be scaled to datasets 370x larger than previously used. We also propose algorithmic improvements that can further benefit resource usage and model performance, including multi-output trees which are well-suited to generative modeling. Finally, we present results on large-scale scientific datasets derived from experimental particle physics as part of the Fast Calorimeter Simulation Challenge.