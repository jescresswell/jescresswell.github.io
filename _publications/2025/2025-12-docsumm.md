---
title: "Document Summarization with Conformal Importance Guarantees"
collection: publications
permalink: /publication/2025-12-docsumm
excerpt: 
date: 2025-12-02
authors: 'Bruce Kuwahara, Chen-Yuan Lin, Xiao Shi Huang, Kin Kwan Leung, Jullian Arta Yapeter, Ilya Stanevich, Felipe Perez, <b>Jesse C. Cresswell</b>'
note:
venueshort: 'NeurIPS 2025'
venue: 'Advances in Neural Information Processing Systems 2025'
paperurl: 'https://arxiv.org/abs/2509.20461'
pdf: 'https://arxiv.org/pdf/2509.20461'
codeurl: 'https://github.com/layer6ai-labs/conformal-importance-summarization'
videourl:
slidesurl:
citation: 'Bruce Kuwahara, Chen-Yuan Lin, Xiao Shi Huang, Kin Kwan Leung, Jullian Arta Yapeter, Ilya Stanevich, Felipe Perez, Jesse C. Cresswell. Document Summarization with Conformal Importance Guarantees. In Advances in Neural Information Processing Systems, volume 38, 2025'
---
Automatic summarization systems have advanced rapidly with large language models (LLMs), yet they still lack reliable guarantees on inclusion of critical content in high-stakes domains like healthcare, law, and finance. In this work, we introduce Conformal Importance Summarization, the first framework for importance-preserving summary generation which uses conformal prediction to provide rigorous, distribution-free coverage guarantees. By calibrating thresholds on sentence-level importance scores, we enable extractive document summarization with user-specified coverage and recall rates over critical content. Our method is model-agnostic, requires only a small calibration set, and seamlessly integrates with existing black-box LLMs. Experiments on established summarization benchmarks demonstrate that Conformal Importance Summarization achieves the theoretically assured information coverage rate. Our work suggests that Conformal Importance Summarization can be combined with existing techniques to achieve reliable, controllable automatic summarization, paving the way for safer deployment of AI summarization tools in critical applications. Code is provided as supplementary material and will be released upon publication.