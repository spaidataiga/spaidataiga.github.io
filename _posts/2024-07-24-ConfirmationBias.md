---
layout: post
title: DYNAMICQA Tracing Internal Knowledge Conflicts in Language Models
subtitle: SV Marjanović, H Yu, P Atanasova, M Maistro, C Lioma, I Augenstein
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
# share-img: /assets/img/path.jpg
tags: [knowledge conflict, intra-memory conflict, dataset, uncertainty]
author: EMNLP Findings 2024
url: https://aclanthology.org/2024.findings-emnlp.838/
---

Knowledge-intensive language understanding tasks require Language Models (LMs) to integrate relevant context, mitigating their inherent weaknesses, such as incomplete or outdated knowledge. However, conflicting knowledge can be present in the LM's parameters, termed intra-memory conflict, which can affect a model's propensity to accept contextual knowledge. To study the effect of intra-memory conflict on an LM's ability to accept relevant context, we utilize two knowledge conflict measures and a novel dataset containing inherently conflicting data, DynamicQA. This dataset includes facts with a temporal dynamic nature where facts can change over time and disputable dynamic facts, which can change depending on the viewpoint. DynamicQA is the first to include real-world knowledge conflicts and provide context to study the link between the different types of knowledge conflicts. We also evaluate several measures on their ability to reflect the presence of intra-memory conflict: semantic entropy and a novel coherent persuasion score. With our extensive experiments, in this [EMNLP 2024 paper](https://arxiv.org/abs/2407.17023), we verify that LMs exhibit a greater degree of intra-memory conflict with dynamic facts compared to facts that have a single truth value. Furthermore, we reveal that facts with intra-memory conflict are harder to update with context, suggesting that retrieval-augmented generation will struggle with the most commonly adapted facts. 