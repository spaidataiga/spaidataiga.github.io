---
layout: post
title: DeepSeek-R1 Thoughtology Let’s think about LLM reasoning
subtitle: SV Marjanović, A Patel, V Adlakha, M Aghajohari, P BehnamGhader, M Bhatia, A Khandelwal, A Kraft, B Krojer, XH Lù, N Meade, D Shin, A Kazemnejad, G Kamath, M Mosbach, K Stańczak, S Reddy
# cover-img: /assets/img/path.jpg
# thumbnail-img: /assets/img/thumb.png
# share-img: /assets/img/path.jpg
tags: [reasoning, safety, cultural, inference time,]
author: Preprint
out_url: https://mcgill-nlp.github.io/thoughtology/
---

Large Reasoning Models like DeepSeek-R1 mark a fundamental shift in how LLMs approach complex problems. Instead of directly producing an answer for a given input, DeepSeek-R1 creates detailed multi-step reasoning chains, seemingly "thinking" about a problem before providing an answer. This reasoning process is publicly available to the user, creating endless opportunities for studying the reasoning behaviour of the model and opening up the field of Thoughtology. Starting from a taxonomy of DeepSeek-R1's basic building blocks of reasoning, our [analyses](https://mcgill-nlp.github.io/thoughtology/) on DeepSeek-R1 investigate the impact and controllability of thought length, management of long or confusing contexts, cultural and safety concerns, and the status of DeepSeek-R1 vis-à-vis cognitive phenomena, such as human-like language processing and world modelling. Our findings paint a nuanced picture. Notably, we show DeepSeek-R1 has a 'sweet spot' of reasoning, where extra inference time can impair model performance. Furthermore, we find a tendency for DeepSeek-R1 to persistently ruminate on previously explored problem formulations, obstructing further exploration. We also note strong safety vulnerabilities of DeepSeek-R1 compared to its non-reasoning counterpart, which can also compromise safety-aligned LLMs.