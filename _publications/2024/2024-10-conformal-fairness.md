---
title: "Conformal Prediction Sets Can Cause Disparate Impact"
collection: publications
permalink: /publication/2024-10-conformal-fairness
excerpt: 
date: 2024-10-02
authors: '<b>Jesse C. Cresswell</b>, Bhargava Kumar, Yi Sui, Mouloud Belbahri'
note:
venueshort: 'arXiv'
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2410.01888'
pdf: 'https://arxiv.org/pdf/2410.01888.pdf'
codeurl: 'https://github.com/layer6ai-labs/conformal-prediction-fairness'
videourl:
slidesurl:
citation: 'Jesse C. Cresswell, Bhargava Kumar, Yi Sui, and Mouloud Belbahri. Conformal Prediction Sets Can Cause Disparate Impact. arXiv preprint 2410.01888'
---
Although conformal prediction is a promising method for quantifying the uncertainty of machine learning models, the prediction sets it outputs are not inherently actionable. Many applications require a single output to act on, not several. To overcome this, prediction sets can be provided to a human who then makes an informed decision. In any such system it is crucial to ensure the fairness of outcomes across protected groups, and researchers have proposed that Equalized Coverage be used as the standard for fairness. By conducting experiments with human participants, we demonstrate that providing prediction sets can increase the unfairness of their decisions. Disquietingly, we find that providing sets that satisfy Equalized Coverage actually increases unfairness compared to marginal coverage. Instead of equalizing coverage, we propose to equalize set sizes across groups which empirically leads to more fair outcomes.