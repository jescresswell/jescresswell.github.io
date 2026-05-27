---
title: "Chartographer: Counterfactual Chart Generation for Evaluating Vision-Language Models"
collection: publications
permalink: /publication/2026-05-chartographer
excerpt: 
date: 2026-05-26
authors: 'Yifan Jiang, Dae Yon Hwang, <b>Jesse C. Cresswell</b>, Freda Shi'
note:
venueshort: 'arXiv'
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2605.27311'
pdf: 'https://arxiv.org/pdf/2605.27311'
codeurl:
videourl:
slidesurl:
citation: 'Yifan Jiang, Dae Yon Hwang, Jesse C. Cresswell, Freda Shi. Chartographer: Counterfactual Chart Generation for Evaluating Vision-Language Models. arXiv preprint: 2605.27311'
---
Chart question-answering (QA) benchmarks aim to pose questions that require visual reasoning to correctly answer, but models can often reach solutions through shortcuts or prior familiarity with a chart based on their own background knowledge. To strictly evaluate visual reasoning, we propose counterfactual charts where the chart-question task remains fixed, but underlying chart and the corresponding answer are varied. We introduce Chartographer, a framework to reverse engineer charts into executable code, validate reconstruction fidelity, generate seed-controlled counterfactual variants, and derive new answers from executable QA logic. We apply this framework to existing chart QA datasets and evaluate proprietary and open-source vision-language models (VLMs), measuring variation sensitivity and generalizability. Counterfactual charts reveal failures hidden by single-chart performance: VLMs often fail to generalize after answering the original chart correctly. We find failures are most prevalent when updated charts require novel visual reasoning pathways.