---
title: "Find Your Friends: Personalized Federated Learning with the Right Collaborators"
collection: publications
permalink: /publication/2022-10-find-your-friends
excerpt: 
date: 2022-10-12
venue: 'Arxiv preprint'
paperurl: 'https://arxiv.org/abs/2210.06507'
citation: 'Yi Sui, Junfeng Wen, Yenson Lau, Brendan Leigh Ross, and Jesse C. Cresswell. Find Your Friends: Personalized Federated Learning with the Right Collaborators. arXiv:2210.06597, 2022.'
---
In the traditional federated learning setting, a central server coordinates a network of clients to train one global model. However, the global model may serve many clients poorly due to data heterogeneity. Moreover, there may not exist a trusted central party that can coordinate the clients to ensure that each of them can benefit from others. To address these concerns, we present a novel decentralized framework, FedeRiCo, where each client can learn as much or as little from other clients as is optimal for its local data distribution. Based on expectation-maximization, FedeRiCo estimates the utilities of other participants' models on each client's data so that everyone can select the right collaborators for learning. As a result, our algorithm outperforms other federated, personalized, and/or decentralized approaches on several benchmark datasets, being the only approach that consistently performs better than training with local data only.

[Download paper here](http://jescresswell.github.io/files/2210.06597.pdf)