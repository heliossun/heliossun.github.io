---
title: "STLLaVA-Med: Self-Training Large Language and Vision Assistant for Medical"
collection: publications
permalink: /publication/2024-STLLaVA
excerpt: 'This work have introduced a novel self-training approach to enhance the data efficiency of training LVLMs for medical tasks'
date: 2024-03-17
venue: 'Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'https://arxiv.org/pdf/2406.19973'
citation: 'Sun, G., Qin, C., Fu, H., Wang, L., & Tao, Z. (2024). STLLaVA-Med: Self-Training Large Language and Vision Assistant for Medical.'
---

Large Vision-Language Models (LVLMs) have shown significant potential in assisting medical diagnosis by leveraging extensive biomedical datasets. However, the advancement of medical image understanding and reasoning critically depends on building high-quality visual instruction data, which is costly and labor-intensive to obtain, particularly in the medical domain. To mitigate this data-starving issue, we introduce Self-Training Large Language and Vision Assistant for Medical (STLLaVA-Med). The proposed method is designed to train a policy model (an LVLM) capable of auto-generating medical visual instruction data to improve data efficiency, guided through Direct Preference Optimization (DPO). Specifically, a more powerful and larger LVLM (e.g., GPT-4o) is involved as a biomedical expert to oversee the DPO fine-tuning process on the auto-generated data, encouraging the policy model to align efficiently with human preferences.