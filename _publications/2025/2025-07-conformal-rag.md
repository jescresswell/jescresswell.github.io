---
title: "Response Quality Assessment for Retrieval-Augmented Generation via Conditional Conformal Factuality"
collection: publications
permalink: /publication/2025-05-conformal-rag
excerpt: 
date: 2025-07-13
authors: 'Naihe Feng, Yi Sui, Shiyi Hou, <b>Jesse C. Cresswell</b>, Ga Wu'
note: 'Short Paper'
venueshort: 'SIGIR 2025'
venue: 'SIGIR Conference on Research and Development in Information Retrieval 2025'
paperurl:
pdf:
codeurl:
videourl:
slidesurl:
citation: 'Naihe Feng, Yi Sui, Shiyi Hou, Jesse C. Cresswell, Ga Wu. Response Quality Assessment for Retrieval-Augmented Generation via Conditional Conformal Factuality. SIGIR 2025'
---
Existing research on Retrieval-Augmented Generation (RAG) primarily focuses on improving overall question-answering accuracy, often overlooking the quality of sub-claims within generated responses. Recent methods that attempt to improve RAG trustworthiness, such as auto-evaluation metrics, often lack probabilistic guarantees or requires ground truth answers, failing to provide reliable and scalable assessment. To address these limitations, we propose Conformal-RAG, a novel framework inspired by recent applications of conformal prediction in large language models (LLMs). Conformal-RAG leverages conformal prediction and internal information from the RAG mechanism to offer statistical guarantees on response quality. It ensures conditional coverage (potentially spanning multiple sub-domains) without requiring manual calibration of conformal sets, making it suitable for complex RAG applications. Compared to existing RAG auto-evaluation methods, Conformal-RAG offers statistical guarantees on the quality of refined sub-claims, ensuring response reliability without needing ground truth answers. Additionally, our experiments demonstrate that by leveraging RAG internal information, Conformal-RAG retains more high-quality sub-claims from the response while maintaining the same reliability guarantee as naïve adaptations of conformal prediction in LLMs. Specifically, Conformal-RAG retains 60% more high-quality sub-claims in biography generation tasks and 20% more in medication question-answering tasks.