---
title: "MaskSQL: Safeguarding Privacy for LLM-Based Text-to-SQL via Abstraction"
collection: publications
permalink: /publication/2025-09-masksql
excerpt: 
date: 2025-09-27
authors: 'Sepideh Abedini, Shubhankar Mohapatra, D. B. Emerson, Masoumeh Shafieinejad, <b>Jesse C. Cresswell</b>, Xi He'
note:
venueshort: 'NeurIPS 2025 Workshop RegML'
venue: 'NeurIPS 2025 Workshop on Regulatable ML'
paperurl: 'https://arxiv.org/abs/2509.23459'
pdf: 'https://arxiv.org/pdf/2509.23459'
codeurl: 'https://github.com/sepideh-abedini/MaskSQL'
videourl:
slidesurl:
citation: 'Sepideh Abedini, Shubhankar Mohapatra, D. B. Emerson, Masoumeh Shafieinejad, Jesse C. Cresswell, Xi He. MaskSQL: Safeguarding Privacy for LLM-Based Text-to-SQL via Abstraction. arXiv preprint: 2509.23459'
---
Large language models (LLMs) have shown promising performance on tasks that require reasoning, such as text-to-SQL, code generation, and debugging. However, regulatory frameworks with strict privacy requirements constrain their integration into sensitive systems. State-of-the-art LLMs are also proprietary, costly, and resource-intensive, making local deployment impractical. Consequently, utilizing such LLMs often requires sharing data with third-party providers, raising privacy concerns and risking noncompliance with regulations. Although fine-tuned small language models (SLMs) can outperform LLMs on certain tasks and be deployed locally to mitigate privacy concerns, they underperform on more complex tasks such as text-to-SQL translation. In this work, we introduce MaskSQL, a text-to-SQL framework that utilizes abstraction as a privacy protection mechanism to mask sensitive information in LLM prompts. Unlike redaction, which removes content entirely, or generalization, which broadens tokens, abstraction retains essential information while discarding unnecessary details, striking an effective privacy-utility balance for the text-to-SQL task. Moreover, by providing mechanisms to control the privacy-utility tradeoff, MaskSQL facilitates adoption across a broader range of use cases. Our experimental results show that MaskSQL outperforms leading SLM-based text-to-SQL models and achieves performance approaching state-of-the-art LLM-based models, while preserving privacy.