---
title: "SQ-LLaVA: Self-Questioning for Large Vision-Language Assistant"
collection: publications
permalink: /publication/2024-SQLLaVA-ECCV
excerpt: 'This work has introduced a new training method that enhances general-purpose vision-language understanding and image-oriented question answering through visual self-questioning.'
date: 2024-03-17
venue: 'Proceedings of the 18th European Conference on Computer Vision'
paperurl: 'https://arxiv.org/pdf/2403.11299'
citation: 'Sun, G., Qin, C., Wang, J., Chen, Z., Xu, R., & Tao, Z. (2024). SQ-LLaVA: Self-Questioning for Large Vision-Language Assistant. ArXiv, abs/2403.11299.'
---

Recent advances in vision-language models have shown notable generalization in broad tasks through visual instruction tuning. However, bridging the gap between the pre-trained vision encoder and the large language models (LLMs) becomes the whole network's bottleneck. To improve cross-modality alignment, existing works usually consider more visual instruction data covering a broader range of vision tasks to fine-tune the model for question-answering, which, however, is costly to obtain and has not thoroughly explored the rich contextual information contained in images. This paper first attempts to harness the overlooked context within visual instruction data, training the model to self-supervised "learning" how to ask high-quality questions. In this way, we introduce a novel framework named SQ-LLaVA: Self-Questioning for Large Vision-Language Assistant. SQ-LLaVA exhibits proficiency in generating flexible and meaningful image-related questions while analyzing the visual clue and prior language knowledge, signifying an advanced level of generalized visual understanding. Moreover, fine-tuning SQ-LLaVA on higher-quality instruction data shows a performance improvement compared with traditional visual-instruction tuning methods. This improvement highlights the efficacy of self-questioning techniques in achieving a deeper and more nuanced comprehension of visual content across various contexts.
