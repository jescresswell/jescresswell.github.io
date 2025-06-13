---
title: "CausalPFN: Amortized Causal Effect Estimation via In-Context Learning"
collection: publications
permalink: /publication/2025-06-causalpfn
excerpt: 
date: 2025-06-09
authors: 'Vahid Balazadeh, Hamidreza Kamkari, Valentin Thomas, Benson Li, Junwei Ma, <b>Jesse C. Cresswell</b>, Rahul G. Krishnan'
note: 'Oral'
venueshort: 'ICML 2025 Workshop SIM'
venue: 'ICML 2025 Workshop on Scaling up Intervention Models'
paperurl: 'https://arxiv.org/abs/2506.07918'
pdf: 'https://arxiv.org/pdf/2506.07918'
codeurl: 'https://github.com/vdblm/CausalPFN'
videourl:
slidesurl:
citation: 'Vahid Balazadeh, Hamidreza Kamkari, Valentin Thomas, Benson Li, Junwei Ma, Jesse C. Cresswell, Rahul G. Krishnan. CausalPFN: Amortized Causal Effect Estimation via In-Context Learning. arXiv preprint: 2506.07918'
---
Causal effect estimation from observational data is fundamental across various applications. However, selecting an appropriate estimator from dozens of specialized methods demands substantial manual effort and domain expertise. We present CausalPFN, a single transformer that amortizes this workflow: trained once on a large library of simulated data-generating processes that satisfy ignorability, it infers causal effects for new observational datasets out-of-the-box. CausalPFN combines ideas from Bayesian causal inference with the large-scale training protocol of prior-fitted networks (PFNs), learning to map raw observations directly to causal effects without any task-specific adjustment. Our approach achieves superior average performance on heterogeneous and average treatment effect estimation benchmarks (IHDP, Lalonde, ACIC). Moreover, it shows competitive performance for real-world policy making on uplift modeling tasks. CausalPFN provides calibrated uncertainty estimates to support reliable decision-making based on Bayesian principles. This ready-to-use model does not require any further training or tuning and takes a step toward automated causal inference.