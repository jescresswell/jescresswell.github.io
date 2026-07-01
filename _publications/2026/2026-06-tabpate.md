---
title: "TabPATE: Differentially Private Tabular In-Context Learning Without Public Data"
collection: publications
permalink: /publication/2026-06-tabpate
excerpt: 
date: 2026-06-30
authors: 'Dariush Wahdany, Matthew Jagielski, <b>Jesse C. Cresswell</b>, Adam Dziedzic, Franzsika Boenisch'
note:
venueshort: 'ICML 2026 Workshop FMSD'
venue: 'ICML 2026 Workshop on Foundation Models for Structured Data'
paperurl: 'https://arxiv.org/abs/2606.31474'
pdf: 'https://arxiv.org/pdf/2606.31474.pdf'
codeurl:
videourl:
slidesurl:
citation: 'Dariush Wahdany, Matthew Jagielski, Jesse C. Cresswell, Adam Dziedic, Franzsika Boenisch. TabPATE: Differentially Private Tabular In-Context Learning Without Public Data. ICML 2026 Workshop on Foundation Models for Structured Data'
---
Tabular foundation models enable accurate in-context learning (ICL) from small labeled datasets, but the private records placed in context can leak through model predictions. We first show that even basic membership inference attacks succeed against tabular ICL, motivating formal privacy protection. We then introduce TabPATE, a differentially private PATE-style defense for tabular ICL that does not require public in-distribution data. TabPATE partitions the private context across teacher models, privately aggregates their labels on synthetic tabular queries, and releases the resulting labeled queries as a student context. Because tabular features are bounded and relatively low-dimensional, useful queries can be generated from feature ranges alone or from lightly privatized marginals. Across tabular benchmarks, TabPATE preserves competitive utility while reducing membership inference to near-random success, providing a practical path to private tabular ICL without public data.