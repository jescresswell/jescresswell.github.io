---
title: "Diagnosing and Fixing Manifold Overfitting in Deep Generative Models"
collection: publications
permalink: /publication/2022-07-manifold-overfitting
excerpt: 
date: 2022-07-11
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/forum?id=0nEZCVshxS'
citation: 'Gabriel Loaiza-Ganem, Brendan Leigh Ross, Jesse C. Cresswell, and Anthony L. Caterini. Diagnosing and Fixing Manifold Overfitting in Deep Generative Models. TMLR 2022'
---
The manifold hypothesis states that observed data lies on a low-dimensional manifold embedded in high-dimensional ambient space. In this paper we investigate the pathologies of maximum-likelihood training in the presence of this dimensionality mismatch. We formally prove that degenerate optima are achieved wherein the manifold itself is learned but not the distribution on it, a phenomenon we call manifold overfitting. We propose a class of two-step procedures consisting of a dimensionality reduction step followed by maximum-likelihood density estimation, and prove that they recover the data-generating distribution in the nonparametric regime, thus avoiding manifold overfitting. We also show that these procedures enable density estimation on the manifolds learned by implicit models.

[Download paper here](http://jescresswell.github.io/files/2204.07172.pdf)