---
title: "Latent Chain-of-Thought for Visual Reasoning"
collection: publications
permalink: /publication/2025-LaCoT
excerpt: 'This work has introduced a new deep-RL method that enhances VLM reasoning ability.'
date: 2025-10-27
venue: 'NeurIPS'
paperurl: 'https://arxiv.org/abs/2510.23925'
citation: 'Sun, G., Hua, H., Wang, J., Luo, J., Dianat, S., Rabbani, M., & Tao, Z. (2025). Latent chain-of-thought for visual reasoning. NeurIPS'
---

Chain-of-thought (CoT) reasoning is critical for improving the interpretability and reliability of Large Vision-Language Models (LVLMs). However, existing training algorithms such as SFT, PPO, and GRPO may not generalize well across unseen reasoning tasks and heavily rely on a biased reward model. To address this challenge, we reformulate reasoning in LVLMs as posterior inference and propose a scalable training algorithm based on amortized variational inference. By leveraging diversity-seeking reinforcement learning algorithms, we introduce a novel sparse reward function for token-level learning signals that encourage diverse, high-likelihood latent CoT, overcoming deterministic sampling limitations and avoiding reward hacking. Additionally, we implement a Bayesian inference-scaling strategy that replaces costly Best-of-N and Beam Search with a marginal likelihood to efficiently rank optimal rationales and answers. We empirically demonstrate that the proposed method enhances the state-of-the-art LVLMs on seven reasoning benchmarks, in terms of effectiveness, generalization, and interpretability.
