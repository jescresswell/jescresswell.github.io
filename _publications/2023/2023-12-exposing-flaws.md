---
title: "Exposing flaws of generative model evaluation metrics and their unfair treatment of diffusion models"
collection: publications
permalink: /publication/2023-06-exposing-flaws
excerpt: 
date: 2023-12-10
authors: 'George Stein, <b>Jesse C. Cresswell</b>, Rasa Hosseinzadeh, Yi Sui, Brendan Leigh Ross, Valentin Villecroze, Anthony L. Caterini, J. Eric T. Taylor, Gabriel Loaiza-Ganem'
note:
venueshort: 'NeurIPS 2023'
venue: 'Advances in Neural Information Processing Systems'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/hash/0bc795afae289ed465a65a3b4b1f4eb7-Abstract-Conference.html'
pdf: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/0bc795afae289ed465a65a3b4b1f4eb7-Paper-Conference.pdf'
codeurl: 'https://github.com/layer6ai-labs/dgm-eval'
videourl:
slidesurl:
citation: 'George Stein, Jesse C. Cresswell, Rasa Hosseingzadeh, Yi Sui, Brendan Leigh Ross, Valentin Villecroze, Anthony L. Caterini, J. Eric T. Taylor, Gabriel Loaiza-Ganem. Exposing flaws of generative model evaluation metrics and their unfair treatment of diffusion models. In Advances in Neural Information Processing Systems, volume 36, 2023'
---
We study image-based generative models spanning semantically-diverse datasets to understand and improve the feature extractors and metrics used to evaluate them. We conduct the largest human experiment evaluating generative models to date, and find that no existing metric strongly correlates with human evaluations, and that diffusion models are unfairly punished by common metrics based on Inception. We show that DINOv2-ViT-L/14 is the best alternative to Inception.