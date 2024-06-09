---
layout: archive
title: "India's Multilingual GenAI Language Models 💬 🇮🇳"
permalink: /paramanu/
author_profile: true
---

{% include responsive_navbar.html %}
<img src="../images/output-indo-aryan.jpg"/>

Gyan AI's Paramanu: A Family of Novel Efficient Indic Generative Foundation Language Models  
========

We present **Gyan AI Paramanu** ("atom"), a family of **novel language models for Indian languages.**

**It is a collection of auto-regressive monolingual, bilingual, and multilingual Indic language models pretrained from scratch on a single GPU for 10 Indian languages (Assamese, Bangla, Hindi, Konkani, Maithili, Marathi, Odia, Sanskrit, Tamil, Telugu) across 5 scripts (Bangla, Devanagari, Odia, Tamil, Telugu) of varying sizes ranging from 13.29M to 367.5M.**

**The models are pretrained with a context size of 1024 on a single GPU.** The models are very efficient, small, fast, and powerful. We have also developed an efficient most advanced Indic tokenizer that can even tokenize unseen languages. 

In order to avoid the "curse of multi-linguality" in our multilingual mParamanu model, we pretrained on comparable corpora by typological grouping using the same script. 
We performed human evaluation of our pretrained models for open end text generation on grammar, coherence, creativity, and factuality metrics for Bangla, Hindi, and Sanskrit.

**Our Bangla, Hindi, and Sanskrit models outperformed GPT-3.5-Turbo (ChatGPT), Bloom 7B, LLaMa-2 7B, OPT 6.7B, GPT-J 6B, GPTNeo 1.3B, GPT2-XL large language models (LLMs) by a large margin despite being smaller in size by 66 to 20 times compared to standard 7B LLMs.**

**To run inference on our pretrained models, CPU is enough, and GPU is not needed.**

**We also instruction-tuned our pretrained Bangla, Hindi, Marathi, Tamil, and Telugu models on 23k instructions in respective languages.**

Our pretrained and instruction-tuned models which are first of its kind, most powerful efficient small generative language models ever developed for Indic languages.

The various results in our research lead to the conclusion that high quality generative language models are possible without high amount of compute power and humongous number of parameters.

Our models: **Paramanu-Assamese, Paramanu-Bangla, Paramanu-Hindi, Paramanu-Tamil, Paramanu-Telugu, Paramanu-Konkani-Maithili,
Paramanu-Odia, Paramanu-Sanskrit, and multilingual mParamanu.**

Bangla Evaluation
---

| Model                  | MMLU  | HellaSwag | ARC  |
|------------------------|-------|-----------|------|
| Bloom 7B               | 28.2  | 32.8      | 29.2 |
| Bloomz 7B              | 25.9  | 31.5      | 28.2 |
| Paramanu-Bangla 108.5M | 31.7  | 33.45     | 32.5 |

Hindi Evaluation
---

| Model                 | MMLU  | HellaSwag | ARC   |
|-----------------------|-------|-----------|-------|
| Bloom 7B              | 27.5  | 36.4      | 29.2  |
| Bloomz 7B             | 25.9  | 34.0      | 28.2  |
| Open Hathi 7B         | 32.27 | 25.59     | 38.48 |
| Airavata 7B           | 34.96 | 25.37     | 44.96 |
| Paramanu-Hindi 367.5M | 38.47 | 37.65     | 41.7  |


Zero-shot XNLI and XStoryCloze for Hindi
---

| XNLI  | XStoryCloze |
|-------|-------------|
| 33.49 | 52.42       |

Tamil Evaluation
---

| Model                  | MMLU  | HellaSwag | ARC  |
|------------------------|-------|-----------|------|
| Bloom 7B               | 26.6  | 29.4      | 24.2 |
| Bloomz 7B              | 26.7  | 29.5      | 25.6 |
| Paramanu-Tamil 207M    | 30.70 | 32.42     | 33.8 |


Telugu Evaluation
---

| Model                 | MMLU  | HellaSwag | ARC  |
|-----------------------|-------|-----------|------|
| Bloom 7B              | 26.2  | 29.2      | 24.3 |
| Bloomz 7B             | 25.7  | 30.7      | 25.8 |
| Paramanu-Telugu 208M  | 30.23 | 32.2      | 32.9 |


Generative AI technology for multilingual India and World.
=====


* We are **seeking for grants/funds** to keep pursuing world-class AI research for India and the world.
  

German Engineering in India
===

* Interested in learning more about how we can grow your business using our Generative State-of-the-art domain-adaptive
sector-agnostic AI models? 

* Contact us today to schedule a consultation.

* **Email: [info@bharatgpts.com]()**

![](../images/gyanai-logo.jpeg)
