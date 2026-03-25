---
title: "IF-Prune: Information-Flow Guided Token Pruning for Efficient Vision-Language Models"
collection: publications
permalink: /publication/2026-IF-Prune
excerpt: 'This work has introduced a statistic way to provide an importance map for token pruning in VLM.'
date: 2026-02-20
venue: 'CVPR'
paperurl: 'https://openreview.net/forum?id=X9cwzjd2g4&referrer=%5Bthe%20profile%20of%20Guohao%20Sun%5D(%2Fprofile%3Fid%3D~Guohao_Sun1)'
citation: ''
---

Vision-language models (VLMs) with dynamic-resolution vision encoders achieve strong performance but face significant efficiency challenges due to long input sequences. A common approach is to assess the importance of tokens and prune those that are less informative. Recent methods that use a small VLM to generate importance maps for visual tokens have outperformed existing rule-based and similarity-driven pruning approaches, particularly at high pruning ratios. However, directly using the small VLM remains unreliable, as it relies on aggregated visual attention weights as an importance score, which can lead to noisy guidance when the generated tokens are incorrect.
To address this, we invert the approach by having it detect non-informative visual tokens based on the user's query. By adding a variational information bottleneck to the small VLM, we can approximate the entropy of each visual token to provide pruning guidance. Such a posterior-guided pruning method enables the large VLM to retain its reasoning capacity while improving efficiency.
Extensive experiments on eight benchmarks demonstrate the effectiveness of our approach. With only 5% of visual tokens retained, the large VLM preserves 95% of its original performance, outperforming the state of the art by 8%. 
