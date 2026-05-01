---
title: "Beyond Procedure: Substantive Fairness in Conformal Prediction"
collection: publications
permalink: /publication/2026-07-beyond-procedure
excerpt: 
date: 2026-07-06
authors: 'Pengqi Liu, Zijun Yu, Mouloud Belbahri, Arthur Charpentier, Masoud Asgharian, <b>Jesse C. Cresswell</b>'
note:
venueshort: 'ICML 2026'
venue: 'International Conference on Machine Learning 2026'
paperurl: 'https://arxiv.org/abs/2602.16794'
pdf: 'https://arxiv.org/pdf/2602.16794'
codeurl: 'https://github.com/layer6ai-labs/llm-in-the-loop-conformal-fairness'
videourl:
slidesurl:
citation: 'Pengqi Liu, Zijun Yu, Mouloud Belbahri, Arthur Charpentier, Masoud Asgharian, Jesse C. Cresswell. Beyond Procedure: Substantive Fairness in Conformal Prediction. International Conference on Machine Learning 2026'
---
Conformal prediction (CP) offers distribution-free uncertainty quantification for machine learning models, yet its interplay with fairness in downstream decision-making remains underexplored. Moving beyond CP as a standalone operation (procedural fairness), we analyze the holistic decision-making pipeline to evaluate substantive fairness-the equity of downstream outcomes. Theoretically, we derive an upper bound that decomposes prediction-set size disparity into interpretable components, clarifying how label-clustered CP helps control method-driven contributions to unfairness. To facilitate scalable empirical analysis, we introduce an LLM-in-the-loop evaluator that approximates human assessment of substantive fairness across diverse modalities. Our experiments reveal that label-clustered CP variants consistently deliver superior substantive fairness. Finally, we empirically show that equalized set sizes, rather than coverage, strongly correlate with improved substantive fairness, enabling practitioners to design more fair CP systems.