---
title: "Agentic Monte Carlo: Reinforcement Learning for Black-Box LLM Agents"
collection: publications
permalink: /publication/2026-07-agent-mc
excerpt: 
date: 2026-07-06
authors: 'Dae Yon Hwang, Raunaq Suri, Valentin Villecroze, Anthony L. Caterini, <b>Jesse C. Cresswell</b>, Noël Vouitsis, Brendan Leigh Ross'
note:
venueshort: 'ICML 2026'
venue: 'International Conference on Machine Learning 2026'
paperurl:
pdf:
codeurl:
videourl:
slidesurl:
citation: 'Dae Yon Hwang, Raunaq Suri, Valentin Villecroze, Anthony L. Caterini, Jesse C. Cresswell, Noël Vouitsis, Brendan Leigh Ross. Agentic Monte Carlo: Reinforcement Learning for Black-Box LLM Agents. International Conference on Machine Learning 2026'
---
LLM agents operate in two distinct regimes: open-weight agents amenable to reinforcement learning (RL) and black-box agents whose behaviour must be controlled purely at test time. Although black-box agents are often backed by state-of-the-art proprietary LLMs, API-only access precludes parameter-level optimization, rendering most RL methods inapplicable. To address this limitation, we turn to a known equivalence between RL and Bayesian inference. We propose Agentic Monte Carlo (AMC) to directly sample from the optimal policy of a black-box agent rather than training it through RL. The optimal policy is a posterior over trajectories whose prior we define as the fixed black-box LLM agent. We employ Sequential Monte Carlo to sample from this posterior by learning a value function to steer the agent while leaving the underlying black-box model unchanged. We validate AMC on three diverse environments from the AgentGym benchmark, demonstrating significant improvements over prompting baselines and even outperforming Group Relative Policy Optimization (GRPO) as we scale the test-time compute of our method. AMC demonstrates the feasibility of performing principled RL-style optimization of black-box LLM agents.