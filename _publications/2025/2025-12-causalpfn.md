---
title: "CausalPFN: Amortized Causal Effect Estimation via In-Context Learning"
collection: publications
permalink: /publication/2025-12-causalpfn
excerpt: 
date: 2025-12-02
authors: 'Vahid Balazadeh Meresht, Hamidreza Kamkari, Valentin Thomas, Junwei Ma, Bingru Li, <b>Jesse C. Cresswell</b>, Rahul G. Krishnan'
note: 'Spotlight. Top 15% of accepted papers'
venueshort: 'NeurIPS 2025'
venue: 'Advances in Neural Information Processing Systems 2025'
paperurl: 'https://papers.nips.cc/paper_files/paper/2025/hash/e3d3db07c1bfb63e1d0b998996de1d12-Abstract-Conference.html'
pdf: 'https://papers.nips.cc/paper_files/paper/2025/file/e3d3db07c1bfb63e1d0b998996de1d12-Paper-Conference.pdf'
codeurl: 'https://github.com/vdblm/CausalPFN'
videourl:
slidesurl:
citation: 'Vahid Balazadeh Meresht, Hamidreza Kamkari, Valentin Thomas, Junwei Ma, Bingru Li, Jesse C. Cresswell, Rahul G. Krishnan. CausalPFN: Amortized Causal Effect Estimation via In-Context Learning. In Advances in Neural Information Processing Systems, volume 38, 2025'
---
Causal effect estimation from observational data is fundamental across various applications. However, selecting an appropriate estimator from dozens of specialized methods demands substantial manual effort and domain expertise. We present CausalPFN, a single transformer that amortizes this workflow: trained once on a large library of simulated data-generating processes that satisfy ignorability, it infers causal effects for new observational datasets out-of-the-box. CausalPFN combines ideas from Bayesian causal inference with the large-scale training protocol of prior-fitted networks (PFNs), learning to map raw observations directly to causal effects without any task-specific adjustment. Our approach achieves superior average performance on heterogeneous and average treatment effect estimation benchmarks (IHDP, Lalonde, ACIC). Moreover, it shows competitive performance for real-world policy making on uplift modeling tasks. CausalPFN provides calibrated uncertainty estimates to support reliable decision-making based on Bayesian principles. This ready-to-use model does not require any further training or tuning and takes a step toward automated causal inference.