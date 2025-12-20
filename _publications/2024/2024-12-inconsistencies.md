---
title: "Inconsistencies In Consistency Models: Better ODE Solving Does Not Imply Better Samples"
collection: publications
permalink: /publication/2024-12-inconsistencies
excerpt: 
date: 2024-12-14
authors: 'Noël Vouitsis, Rasa Hosseinzadeh, Brendan Leigh Ross, Valentin Villecroze, Satya Krishna Gorti, <b>Jesse C. Cresswell</b>, Gabriel Loaiza-Ganem'
note:
venueshort: 'NeurIPS 2024 Workshop FITML'
venue: 'NeurIPS 2024 Workshop on Fine-Tuning in Modern Machine Learning'
paperurl: 'https://openreview.net/forum?id=2p4ES8QPUi'
pdf: 'https://arxiv.org/pdf/2411.08954'
codeurl: 'https://github.com/layer6ai-labs/direct-cms'
videourl:
slidesurl:
citation: 'Noël Vouitsis, Rasa Hosseinzadeh, Brendan Leigh Ross, Valentin Villecroze, Satya Krishna Gorti, Jesse C. Cresswell, Gabriel Loaiza-Ganem. Inconsistencies In Consistency Models: Better ODE Solving Does Not Imply Better Samples. NeurIPS 2024 Workshop on Fine-Tuning in Modern Machine Learning'
---
Although diffusion models can generate remarkably high-quality samples, they are intrinsically bottlenecked by their expensive iterative sampling procedure. Consistency models (CMs) have recently emerged as a promising diffusion model distillation method, reducing the cost of sampling by generating high fidelity samples in just a few iterations. Consistency model distillation aims to solve the probability flow ordinary differential equation (ODE) defined by an existing diffusion model. CMs are not directly trained to minimize error against an ODE solver, rather they use a more computationally tractable objective. As a way to study how effectively CMs solve the probability flow ODE, and the effect that any induced error has on the quality of generated samples, we introduce Direct CMs, which \textit{directly} minimize this error. Intriguingly, we find that Direct CMs reduce the ODE solving error compared to CMs but also result in significantly worse sample quality, calling into question why exactly CMs work well in the first place. Full training and evaluation code will be made publicly available.