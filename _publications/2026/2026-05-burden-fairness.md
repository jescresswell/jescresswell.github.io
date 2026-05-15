---
title: "On the Burden of Achieving Fairness in Conformal Prediction"
collection: publications
permalink: /publication/2026-05-burden-fairness
excerpt: 
date: 2026-05-14
authors: 'Ziang Gao, Pengqi Liu, Archer Yi Yang, Mouloud Belbahri, <b>Jesse C. Cresswell</b>, Masoud Asgharian'
note:
venueshort: 'arXiv'
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2605.14260'
pdf: 'https://arxiv.org/pdf/2605.14260'
codeurl:
videourl:
slidesurl:
citation: 'Ziang Gao, Pengqi Liu, Archer Yi Yang, Mouloud Belbahri, Jesse C. Cresswell, Masoud Asgharian. On the Burden of Achieving Fairness in Conformal Prediction. arXiv preprint: 2605.14260'
---
Conformal prediction is often calibrated with a single pooled threshold, but this can hide cross-group heterogeneity in score distributions and distort group-wise coverage. We study this phenomenon through the population score distributions underlying split conformal calibration. First, we derive a conservation law and lower bound showing that pooled calibration incurs irreducible group-wise coverage distortion at a scale set by cross-group quantile heterogeneity. Second, we demonstrate that the two leading fairness definitions for conformal prediction, Equalized Coverage and Equalized Set Size, are fundamentally in tension. Third, we quantify the cost of moving between policies which treat groups separately or pool them. Experiments on synthetic and real data confirm the same bidirectional trade-off after finite-sample calibration. Our results show that, for the policy families studied here, calibration choice does not remove cross-group heterogeneity; it determines whether the resulting distortion appears in the coverage or size dimension, providing a principled lens for analyzing fairness-oriented calibration choices in practice.