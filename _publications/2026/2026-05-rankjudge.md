---
title: "RankJudge: A Multi-Turn LLM-as-a-Judge Synthetic Benchmark Generator"
collection: publications
permalink: /publication/2026-05-rankjudge
excerpt: 
date: 2026-05-20
authors: 'Zhenwei Tang, Zhaoyan Liu, Rasa Hosseinzadeh, Tongzi Wu, Keyvan Golestan, <b>Jesse C. Cresswell</b>'
note:
venueshort: 'arXiv'
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2605.21748'
pdf: 'https://arxiv.org/pdf/2605.21748'
codeurl: 'https://github.com/layer6ai-labs/RankJudge'
videourl:
slidesurl:
citation: 'Zhenwei Tang, Zhaoyan Liu, Rasa Hosseinzadeh, Tongzi Wu, Keyvan Golestan, Jesse C. Cresswell. RankJudge: A Multi-Turn LLM-as-a-Judge Synthetic Benchmark Generator. arXiv preprint: 2605.21748'
---
As interactive LLM-based applications are created and refined, model developers need to evaluate the quality of generated text along many possible axes. For simpler systems, human evaluation may be practical, but in complicated systems like conversational chatbots, the amount of generated text can overwhelm human annotation resources. Model developers have begun to rely heavily on auto-evaluation, where LLMs are also used to judge generation quality. However, existing LLM-as-a-judge benchmarks largely focus on simple Q\&A tasks that do not match the complexity of multi-turn conversations. We introduce RankJudge, a benchmark generator for evaluating LLM-as-a-judge on multi-turn conversations grounded in reference documents. RankJudge creates pairs of conversations where one conversation has a single flaw injected into one turn. This construction allows paired conversations to be labeled unambiguously as better or worse, and precisely isolates failure categories to individual turns, enabling a strict joint correctness criterion for judging. We implement RankJudge across the domains of machine learning, biomedicine, and finance, evaluate 21 frontier LLM judges, and rank those judges via the Bradley-Terry model. Our formulation also allows ranking each conversation pair with difficulty ratings, which we use to dynamically curate the evaluation slice to reduce label noise, as confirmed via human annotation. We find that judge rankings are stable under partial observability, coarser correctness criteria, and an alternative random-walk rating algorithm.