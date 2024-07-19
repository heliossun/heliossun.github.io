---
title: "Text Is MASS: Modeling as Stochastic Embedding for Text-Video Retrieval"
collection: publications
permalink: /publication/2024-TMASS-CVPR
excerpt: 'We introduced T-MASS, where text is modeled as a stochastic embedding, facilitating joint learning of the text mass and video points.'
date: 2024-06-17
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Text_Is_MASS_Modeling_as_Stochastic_Embedding_for_Text-Video_Retrieval_CVPR_2024_paper.html'
citation: 'Wang, J., Sun, G., Wang, P., Liu, D., Dianat, S.A., Rabbani, M., Rao, R.M., & Tao, Z. (2024). Text Is MASS: Modeling as Stochastic Embedding for Text-Video Retrieval. CVPR'
---

The increasing prevalence of video clips has sparked growing interest in text-video retrieval. 
Recent advances focus on establishing a joint embedding space for text and video, relying on consistent embedding representations to compute similarity. 
However, the text content in existing datasets is generally short and concise, making it hard to fully describe the redundant semantics of a video. Correspondingly, a single text embedding may be less expressive to capture the video embedding and empower the retrieval.
In this study, we propose a new stochastic text modeling method T-MASS, i.e., text is modeled as a stochastic embedding, to enrich text embedding with a flexible and resilient semantic range, yielding a text mass. To be specific, we introduce a similarity-aware radius module to adapt the scale of the text mass upon the given text-video pairs. Plus, we design and develop a support text regularization to further control the text mass during the training. 
The inference pipeline is also tailored to fully exploit the text mass for accurate retrieval. 