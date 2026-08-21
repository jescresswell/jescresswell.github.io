---
title: "Unifying Conformal Language Tasks with In-Context Ensembles"
collection: publications
permalink: /publication/2026-08-conformal-relevance
excerpt: 
date: 2026-08-24
authors: 'Xiao Shi Huang, Bruce Kuwahara, Chen-Yuan Lin, Kin Kwan Leung, <b>Jesse C. Cresswell</b>'
note:
venueshort: 'Findings of EMNLP 2026'
venue: 'Findings of Empirical Methods in Natural Language Processing 2026'
paperurl:
pdf:
codeurl:
videourl:
slidesurl:
citation: 'Xiao Shi Huang, Bruce Kuwahara, Chen-Yuan Lin, Kin Kwan Leung, Jesse C. Cresswell. Unifying Conformal Language Tasks with In-Context Ensembles. Findings of EMNLP 2026'
---
Many NLP tasks, such as summarization and extractive question answering, reduce to retrieving relevant content from documents under two constraints: coverage, retaining enough pertinent information to achieve some goal, and conciseness, removing as much irrelevant information as possible. Conformal prediction methods have been used to guarantee coverage, and must be optimized for conciseness through design of a score function. State-of-the-art scoring functions use hand-engineered LLM prompts asking the model to rate the importance of content, but manual prompt engineering is labor-intensive and task-specific. We introduce the Conformal Relevance framework which uses in-context learning example curation and ensembling to create a score function which maintains coverage while improving conciseness with minimal manual input, and demonstrate its application on seven NLP tasks. We also theoretically study the impact of diversity for ensembled conformal scores, giving a complementarity condition that characterizes when ensembling improves worst-case sentence scores, and a saturation bound on ensemble improvement.