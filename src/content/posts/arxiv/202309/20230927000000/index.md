---
draft: false
title: "arXiv @ 2023.09.27"
date: 2023-09-27
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.09.27"
    identifier: arxiv_20230927
    parent: 202309_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.CL (17)](#cscl-17)
- [cs.CV (31)](#cscv-31)
- [cs.AI (4)](#csai-4)
- [cs.HC (12)](#cshc-12)
- [cs.CY (3)](#cscy-3)
- [cs.LG (22)](#cslg-22)
- [eess.IV (4)](#eessiv-4)
- [eess.AS (5)](#eessas-5)
- [cond-mat.mtrl-sci (1)](#cond-matmtrl-sci-1)
- [cs.SD (5)](#cssd-5)
- [q-bio.QM (1)](#q-bioqm-1)
- [cs.IR (1)](#csir-1)
- [cs.RO (8)](#csro-8)
- [cs.GT (1)](#csgt-1)
- [cs.CR (2)](#cscr-2)
- [cs.NI (1)](#csni-1)
- [cs.SE (2)](#csse-2)
- [cs.CE (1)](#csce-1)
- [cs.DC (1)](#csdc-1)
- [hep-ph (1)](#hep-ph-1)
- [math.NA (1)](#mathna-1)
- [cs.SI (1)](#cssi-1)

## cs.CL (17)



### (1/125) Introducing DictaLM -- A Large Generative Language Model for Modern Hebrew (Shaltiel Shmidman et al., 2023)

{{<citation>}}

Shaltiel Shmidman, Avi Shmidman, Amir David Nissan Cohen, Moshe Koppel. (2023)  
**Introducing DictaLM -- A Large Generative Language Model for Modern Hebrew**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2309.14568v1)  

---


**ABSTRACT**  
We present DictaLM, a large-scale language model tailored for Modern Hebrew. Boasting 7B parameters, this model is predominantly trained on Hebrew-centric data. As a commitment to promoting research and development in the Hebrew language, we release both the foundation model and the instruct-tuned model under a Creative Commons license. Concurrently, we introduce DictaLM-Rab, another foundation model geared towards Rabbinic/Historical Hebrew. These foundation models serve as ideal starting points for fine-tuning various Hebrew-specific tasks, such as instruction, Q&A, sentiment analysis, and more. This release represents a preliminary step, offering an initial Hebrew LLM model for the Hebrew NLP community to experiment with.

{{</citation>}}


### (2/125) Disinformation Detection: An Evolving Challenge in the Age of LLMs (Bohan Jiang et al., 2023)

{{<citation>}}

Bohan Jiang, Zhen Tan, Ayushi Nirmal, Huan Liu. (2023)  
**Disinformation Detection: An Evolving Challenge in the Age of LLMs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CY, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.15847v1)  

---


**ABSTRACT**  
The advent of generative Large Language Models (LLMs) such as ChatGPT has catalyzed transformative advancements across multiple domains. However, alongside these advancements, they have also introduced potential threats. One critical concern is the misuse of LLMs by disinformation spreaders, leveraging these models to generate highly persuasive yet misleading content that challenges the disinformation detection system. This work aims to address this issue by answering three research questions: (1) To what extent can the current disinformation detection technique reliably detect LLM-generated disinformation? (2) If traditional techniques prove less effective, can LLMs themself be exploited to serve as a robust defense against advanced disinformation? and, (3) Should both these strategies falter, what novel approaches can be proposed to counter this burgeoning threat effectively? A holistic exploration for the formation and detection of disinformation is conducted to foster this line of research.

{{</citation>}}


### (3/125) Art or Artifice? Large Language Models and the False Promise of Creativity (Tuhin Chakrabarty et al., 2023)

{{<citation>}}

Tuhin Chakrabarty, Philippe Laban, Divyansh Agarwal, Smaranda Muresan, Chien-Sheng Wu. (2023)  
**Art or Artifice? Large Language Models and the False Promise of Creativity**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-HC, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14556v1)  

---


**ABSTRACT**  
Researchers have argued that large language models (LLMs) exhibit high-quality writing capabilities from blogs to stories. However, evaluating objectively the creativity of a piece of writing is challenging. Inspired by the Torrance Test of Creative Thinking (TTCT), which measures creativity as a process, we use the Consensual Assessment Technique [3] and propose the Torrance Test of Creative Writing (TTCW) to evaluate creativity as a product. TTCW consists of 14 binary tests organized into the original dimensions of Fluency, Flexibility, Originality, and Elaboration. We recruit 10 creative writers and implement a human assessment of 48 stories written either by professional authors or LLMs using TTCW. Our analysis shows that LLM-generated stories pass 3-10X less TTCW tests than stories written by professionals. In addition, we explore the use of LLMs as assessors to automate the TTCW evaluation, revealing that none of the LLMs positively correlate with the expert assessments.

{{</citation>}}


### (4/125) When Automated Assessment Meets Automated Content Generation: Examining Text Quality in the Era of GPTs (Marialena Bevilacqua et al., 2023)

{{<citation>}}

Marialena Bevilacqua, Kezia Oketch, Ruiyang Qin, Will Stamey, Xinyuan Zhang, Yi Gan, Kai Yang, Ahmed Abbasi. (2023)  
**When Automated Assessment Meets Automated Content Generation: Examining Text Quality in the Era of GPTs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, GPT  
[Paper Link](http://arxiv.org/abs/2309.14488v1)  

---


**ABSTRACT**  
The use of machine learning (ML) models to assess and score textual data has become increasingly pervasive in an array of contexts including natural language processing, information retrieval, search and recommendation, and credibility assessment of online content. A significant disruption at the intersection of ML and text are text-generating large-language models such as generative pre-trained transformers (GPTs). We empirically assess the differences in how ML-based scoring models trained on human content assess the quality of content generated by humans versus GPTs. To do so, we propose an analysis framework that encompasses essay scoring ML-models, human and ML-generated essays, and a statistical model that parsimoniously considers the impact of type of respondent, prompt genre, and the ML model used for assessment model. A rich testbed is utilized that encompasses 18,460 human-generated and GPT-based essays. Results of our benchmark analysis reveal that transformer pretrained language models (PLMs) more accurately score human essay quality as compared to CNN/RNN and feature-based ML methods. Interestingly, we find that the transformer PLMs tend to score GPT-generated text 10-15\% higher on average, relative to human-authored documents. Conversely, traditional deep learning and feature-based ML models score human text considerably higher. Further analysis reveals that although the transformer PLMs are exclusively fine-tuned on human text, they more prominently attend to certain tokens appearing only in GPT-generated text, possibly due to familiarity/overlap in pre-training. Our framework and results have implications for text classification settings where automated scoring of text is likely to be disrupted by generative AI.

{{</citation>}}


### (5/125) Physics of Language Models: Part 3.2, Knowledge Manipulation (Zeyuan Allen-Zhu et al., 2023)

{{<citation>}}

Zeyuan Allen-Zhu, Yuanzhi Li. (2023)  
**Physics of Language Models: Part 3.2, Knowledge Manipulation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14402v1)  

---


**ABSTRACT**  
Language models can store vast amounts of factual knowledge, but their ability to use this knowledge for logical reasoning remains questionable. This paper explores a language model's ability to manipulate its stored knowledge during inference. We focus on four manipulation types: retrieval (e.g., "What is person A's attribute X"), classification (e.g., "Is A's attribute X even or odd?"), comparison (e.g., "Is A greater than B in attribute X?") and inverse search (e.g., "Which person's attribute X equals T?")   We observe that pre-trained language models like GPT2/3/4 excel in knowledge retrieval but struggle with simple classification or comparison tasks unless Chain of Thoughts (CoTs) are employed during both training and inference. They also perform poorly in inverse knowledge search, irrespective of the prompts. Our primary contribution is a synthetic dataset for a controlled experiment that confirms these inherent weaknesses: a language model cannot efficiently manipulate knowledge from pre-training data, even when such knowledge is perfectly stored and fully extractable in the models, and despite adequate instruct fine-tuning.

{{</citation>}}


### (6/125) Physics of Language Models: Part 3.1, Knowledge Storage and Extraction (Zeyuan Allen Zhu et al., 2023)

{{<citation>}}

Zeyuan Allen Zhu, Yuanzhi Li. (2023)  
**Physics of Language Models: Part 3.1, Knowledge Storage and Extraction**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14316v1)  

---


**ABSTRACT**  
Large language models can store extensive world knowledge, often extractable through question-answering (e.g., "What is Abraham Lincoln's birthday?"). However, it's unclear whether the model answers questions based on exposure to exact/similar questions during training, or if it genuinely extracts knowledge from the source (e.g., Wikipedia biographies).   In this paper, we conduct an in-depth study of this problem using a controlled set of semi-synthetic biography data. We uncover a relationship between the model's knowledge extraction ability and different diversity measures of the training data. We conduct (nearly) linear probing, revealing a strong correlation between this relationship and whether the model (nearly) linearly encodes the knowledge attributes at the hidden embedding of the entity names, or across the embeddings of other tokens in the training text.

{{</citation>}}


### (7/125) Urdu Poetry Generated by Using Deep Learning Techniques (Muhammad Shoaib Farooq et al., 2023)

{{<citation>}}

Muhammad Shoaib Farooq, Ali Abbas. (2023)  
**Urdu Poetry Generated by Using Deep Learning Techniques**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: LSTM, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2309.14233v1)  

---


**ABSTRACT**  
This study provides Urdu poetry generated using different deep-learning techniques and algorithms. The data was collected through the Rekhta website, containing 1341 text files with several couplets. The data on poetry was not from any specific genre or poet. Instead, it was a collection of mixed Urdu poems and Ghazals. Different deep learning techniques, such as the model applied Long Short-term Memory Networks (LSTM) and Gated Recurrent Unit (GRU), have been used. Natural Language Processing (NLP) may be used in machine learning to understand, analyze, and generate a language humans may use and understand. Much work has been done on generating poetry for different languages using different techniques. The collection and use of data were also different for different researchers. The primary purpose of this project is to provide a model that generates Urdu poems by using data completely, not by sampling data. Also, this may generate poems in pure Urdu, not Roman Urdu, as in the base paper. The results have shown good accuracy in the poems generated by the model.

{{</citation>}}


### (8/125) Multiple Noises in Diffusion Model for Semi-Supervised Multi-Domain Translation (Tsiry Mayet et al., 2023)

{{<citation>}}

Tsiry Mayet, Simon Bernard, Clement Chatelain, Romain Herault. (2023)  
**Multiple Noises in Diffusion Model for Semi-Supervised Multi-Domain Translation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2309.14394v1)  

---


**ABSTRACT**  
Domain-to-domain translation involves generating a target domain sample given a condition in the source domain. Most existing methods focus on fixed input and output domains, i.e. they only work for specific configurations (i.e. for two domains, either $D_1\rightarrow{}D_2$ or $D_2\rightarrow{}D_1$). This paper proposes Multi-Domain Diffusion (MDD), a conditional diffusion framework for multi-domain translation in a semi-supervised context. Unlike previous methods, MDD does not require defining input and output domains, allowing translation between any partition of domains within a set (such as $(D_1, D_2)\rightarrow{}D_3$, $D_2\rightarrow{}(D_1, D_3)$, $D_3\rightarrow{}D_1$, etc. for 3 domains), without the need to train separate models for each domain configuration. The key idea behind MDD is to leverage the noise formulation of diffusion models by incorporating one noise level per domain, which allows missing domains to be modeled with noise in a natural way. This transforms the training task from a simple reconstruction task to a domain translation task, where the model relies on less noisy domains to reconstruct more noisy domains. We present results on a multi-domain (with more than two domains) synthetic image translation dataset with challenging semantic domain inversion.

{{</citation>}}


### (9/125) LLMCarbon: Modeling the end-to-end Carbon Footprint of Large Language Models (Ahmad Faiz et al., 2023)

{{<citation>}}

Ahmad Faiz, Sotaro Kaneda, Ruhan Wang, Rita Osi, Parteek Sharma, Fan Chen, Lei Jiang. (2023)  
**LLMCarbon: Modeling the end-to-end Carbon Footprint of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CY, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14393v1)  

---


**ABSTRACT**  
The carbon footprint associated with large language models (LLMs) is a significant concern, encompassing emissions from their training, inference, experimentation, and storage processes, including operational and embodied carbon emissions. An essential aspect is accurately estimating the carbon impact of emerging LLMs even before their training, which heavily relies on GPU usage. Existing studies have reported the carbon footprint of LLM training, but only one tool, mlco2, can predict the carbon footprint of new neural networks prior to physical training. However, mlco2 has several serious limitations. It cannot extend its estimation to dense or mixture-of-experts (MoE) LLMs, disregards critical architectural parameters, focuses solely on GPUs, and cannot model embodied carbon footprints. Addressing these gaps, we introduce \textit{LLMCarbon}, an end-to-end carbon footprint projection model designed for both dense and MoE LLMs. Compared to mlco2, LLMCarbon significantly enhances the accuracy of carbon footprint estimations for various LLMs.

{{</citation>}}


### (10/125) Only 5\% Attention Is All You Need: Efficient Long-range Document-level Neural Machine Translation (Zihan Liu et al., 2023)

{{<citation>}}

Zihan Liu, Zewei Sun, Shanbo Cheng, Shujian Huang, Mingxuan Wang. (2023)  
**Only 5\% Attention Is All You Need: Efficient Long-range Document-level Neural Machine Translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Attention, Machine Translation, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14174v1)  

---


**ABSTRACT**  
Document-level Neural Machine Translation (DocNMT) has been proven crucial for handling discourse phenomena by introducing document-level context information. One of the most important directions is to input the whole document directly to the standard Transformer model. In this case, efficiency becomes a critical concern due to the quadratic complexity of the attention module. Existing studies either focus on the encoder part, which cannot be deployed on sequence-to-sequence generation tasks, e.g., Machine Translation (MT), or suffer from a significant performance drop. In this work, we keep the translation performance while gaining 20\% speed up by introducing extra selection layer based on lightweight attention that selects a small portion of tokens to be attended. It takes advantage of the original attention to ensure performance and dimension reduction to accelerate inference. Experimental results show that our method could achieve up to 95\% sparsity (only 5\% tokens attended) approximately, and save 93\% computation cost on the attention module compared with the original Transformer, while maintaining the performance.

{{</citation>}}


### (11/125) Examining Temporal Bias in Abusive Language Detection (Mali Jin et al., 2023)

{{<citation>}}

Mali Jin, Yida Mu, Diana Maynard, Kalina Bontcheva. (2023)  
**Examining Temporal Bias in Abusive Language Detection**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.14146v1)  

---


**ABSTRACT**  
The use of abusive language online has become an increasingly pervasive problem that damages both individuals and society, with effects ranging from psychological harm right through to escalation to real-life violence and even death. Machine learning models have been developed to automatically detect abusive language, but these models can suffer from temporal bias, the phenomenon in which topics, language use or social norms change over time. This study aims to investigate the nature and impact of temporal bias in abusive language detection across various languages and explore mitigation methods. We evaluate the performance of models on abusive data sets from different time periods. Our results demonstrate that temporal bias is a significant challenge for abusive language detection, with models trained on historical data showing a significant drop in performance over time. We also present an extensive linguistic analysis of these abusive data sets from a diachronic perspective, aiming to explore the reasons for language evolution and performance decline. This study sheds light on the pervasive issue of temporal bias in abusive language detection across languages, offering crucial insights into language evolution and temporal bias mitigation.

{{</citation>}}


### (12/125) Comprehensive Overview of Named Entity Recognition: Models, Domain-Specific Applications and Challenges (Kalyani Pakhale, 2023)

{{<citation>}}

Kalyani Pakhale. (2023)  
**Comprehensive Overview of Named Entity Recognition: Models, Domain-Specific Applications and Challenges**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs.CL  
Keywords: AI, BERT, LSTM, NER, NLP, Named Entity Recognition, Natural Language Processing, OCR  
[Paper Link](http://arxiv.org/abs/2309.14084v1)  

---


**ABSTRACT**  
In the domain of Natural Language Processing (NLP), Named Entity Recognition (NER) stands out as a pivotal mechanism for extracting structured insights from unstructured text. This manuscript offers an exhaustive exploration into the evolving landscape of NER methodologies, blending foundational principles with contemporary AI advancements. Beginning with the rudimentary concepts of NER, the study spans a spectrum of techniques from traditional rule-based strategies to the contemporary marvels of transformer architectures, particularly highlighting integrations such as BERT with LSTM and CNN. The narrative accentuates domain-specific NER models, tailored for intricate areas like finance, legal, and healthcare, emphasizing their specialized adaptability. Additionally, the research delves into cutting-edge paradigms including reinforcement learning, innovative constructs like E-NER, and the interplay of Optical Character Recognition (OCR) in augmenting NER capabilities. Grounding its insights in practical realms, the paper sheds light on the indispensable role of NER in sectors like finance and biomedicine, addressing the unique challenges they present. The conclusion outlines open challenges and avenues, marking this work as a comprehensive guide for those delving into NER research and applications.

{{</citation>}}


### (13/125) LORD: Low Rank Decomposition Of Monolingual Code LLMs For One-Shot Compression (Ayush Kaushal et al., 2023)

{{<citation>}}

Ayush Kaushal, Tejas Vaidhya, Irina Rish. (2023)  
**LORD: Low Rank Decomposition Of Monolingual Code LLMs For One-Shot Compression**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14021v1)  

---


**ABSTRACT**  
Low Rank Decomposition of matrix - splitting a large matrix into a product of two smaller matrix offers a means for compression that reduces the parameters of a model without sparsification, and hence delivering more speedup on modern hardware. Moreover, unlike quantization, the compressed linear layers remain fully differentiable and all the parameters trainable, while being able to leverage the existing highly efficient kernels over floating point matrices. We study the potential to compress Large Language Models (LLMs) for monolingual Code generation via Low Rank Decomposition (LoRD) and observe that ranks for the linear layers in these models can be reduced by upto 39.58% with less than 1% increase in perplexity. We then use Low Rank Decomposition (LoRD) to compress StarCoder 16B to 13.2B parameter with no drop and to 12.3B with minimal drop in HumanEval Pass@1 score, in less than 10 minutes on a single A100. The compressed models speeds up inference by up to 22.35% with just a single line of change in code over huggingface's implementation with pytorch backend. Low Rank Decomposition (LoRD) models remain compatible with state of the art near-lossless quantization method such as SpQR, which allows leveraging further compression gains of quantization. Lastly, QLoRA over Low Rank Decomposition (LoRD) model further reduces memory requirements by as much as 21.2% over vanilla QLoRA while offering similar gains from parameter efficient fine tuning. Our work shows Low Rank Decomposition (LoRD) as a promising new paradigm for LLM compression.

{{</citation>}}


### (14/125) Reproducing Whisper-Style Training Using an Open-Source Toolkit and Publicly Available Data (Yifan Peng et al., 2023)

{{<citation>}}

Yifan Peng, Jinchuan Tian, Brian Yan, Dan Berrebbi, Xuankai Chang, Xinjian Li, Jiatong Shi, Siddhant Arora, William Chen, Roshan Sharma, Wangyou Zhang, Yui Sudo, Muhammad Shakeel, Jee-weon Jung, Soumi Maiti, Shinji Watanabe. (2023)  
**Reproducing Whisper-Style Training Using an Open-Source Toolkit and Publicly Available Data**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.13876v1)  

---


**ABSTRACT**  
Pre-training speech models on large volumes of data has achieved remarkable success. OpenAI Whisper is a multilingual multitask model trained on 680k hours of supervised speech data. It generalizes well to various speech recognition and translation benchmarks even in a zero-shot setup. However, the full pipeline for developing such models (from data collection to training) is not publicly accessible, which makes it difficult for researchers to further improve its performance and address training-related issues such as efficiency, robustness, fairness, and bias. This work presents an Open Whisper-style Speech Model (OWSM), which reproduces Whisper-style training using an open-source toolkit and publicly available data. OWSM even supports more translation directions and can be more efficient to train. We will publicly release all scripts used for data preparation, training, inference, and scoring as well as pre-trained models and training logs to promote open science.

{{</citation>}}


### (15/125) PRiSM: Enhancing Low-Resource Document-Level Relation Extraction with Relation-Aware Score Calibration (Minseok Choi et al., 2023)

{{<citation>}}

Minseok Choi, Hyesu Lim, Jaegul Choo. (2023)  
**PRiSM: Enhancing Low-Resource Document-Level Relation Extraction with Relation-Aware Score Calibration**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Low-Resource, Relation Extraction  
[Paper Link](http://arxiv.org/abs/2309.13869v1)  

---


**ABSTRACT**  
Document-level relation extraction (DocRE) aims to extract relations of all entity pairs in a document. A key challenge in DocRE is the cost of annotating such data which requires intensive human effort. Thus, we investigate the case of DocRE in a low-resource setting, and we find that existing models trained on low data overestimate the NA ("no relation") label, causing limited performance. In this work, we approach the problem from a calibration perspective and propose PRiSM, which learns to adapt logits based on relation semantic information. We evaluate our method on three DocRE datasets and demonstrate that integrating existing models with PRiSM improves performance by as much as 26.38 F1 score, while the calibration error drops as much as 36 times when trained with about 3% of data. The code is publicly available at https://github.com/brightjade/PRiSM.

{{</citation>}}


### (16/125) Fast-HuBERT: An Efficient Training Framework for Self-Supervised Speech Representation Learning (Guanrou Yang et al., 2023)

{{<citation>}}

Guanrou Yang, Ziyang Ma, Zhisheng Zheng, Yakun Song, Zhikang Niu, Xie Chen. (2023)  
**Fast-HuBERT: An Efficient Training Framework for Self-Supervised Speech Representation Learning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs-SD, cs.CL, eess-AS  
Keywords: BERT, Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.13860v1)  

---


**ABSTRACT**  
Recent years have witnessed significant advancements in self-supervised learning (SSL) methods for speech-processing tasks. Various speech-based SSL models have been developed and present promising performance on a range of downstream tasks including speech recognition. However, existing speech-based SSL models face a common dilemma in terms of computational cost, which might hinder their potential application and in-depth academic research. To address this issue, we first analyze the computational cost of different modules during HuBERT pre-training and then introduce a stack of efficiency optimizations, which is named Fast-HuBERT in this paper. The proposed Fast-HuBERT can be trained in 1.1 days with 8 V100 GPUs on the Librispeech 960h benchmark, without performance degradation, resulting in a 5.2x speedup, compared to the original implementation. Moreover, we explore two well-studied techniques in the Fast-HuBERT and demonstrate consistent improvements as reported in previous work.

{{</citation>}}


### (17/125) Can LLM-Generated Misinformation Be Detected? (Canyu Chen et al., 2023)

{{<citation>}}

Canyu Chen, Kai Shu. (2023)  
**Can LLM-Generated Misinformation Be Detected?**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CR, cs-HC, cs-LG, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.13788v1)  

---


**ABSTRACT**  
The advent of Large Language Models (LLMs) has made a transformative impact. However, the potential that LLMs such as ChatGPT can be exploited to generate misinformation has posed a serious concern to online safety and public trust. A fundamental research question is: will LLM-generated misinformation cause more harm than human-written misinformation? We propose to tackle this question from the perspective of detection difficulty. We first build a taxonomy of LLM-generated misinformation. Then we categorize and validate the potential real-world methods for generating misinformation with LLMs. Then, through extensive empirical investigation, we discover that LLM-generated misinformation can be harder to detect for humans and detectors compared to human-written misinformation with the same semantics, which suggests it can have more deceptive styles and potentially cause more harm. We also discuss the implications of our discovery on combating misinformation in the age of LLMs and the countermeasures.

{{</citation>}}


## cs.CV (31)



### (18/125) Generative Escher Meshes (Noam Aigerman et al., 2023)

{{<citation>}}

Noam Aigerman, Thibault Groueix. (2023)  
**Generative Escher Meshes**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CG, cs-CV, cs-GR, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2309.14564v2)  

---


**ABSTRACT**  
This paper proposes a fully-automatic, text-guided generative method for producing periodic, repeating, tile-able 2D art, such as the one seen on floors, mosaics, ceramics, and the work of M.C. Escher. In contrast to the standard concept of a seamless texture, i.e., square images that are seamless when tiled, our method generates non-square tilings which comprise solely of repeating copies of the same object. It achieves this by optimizing both geometry and color of a 2D mesh, in order to generate a non-square tile in the shape and appearance of the desired object, with close to no additional background details. We enable geometric optimization of tilings by our key technical contribution: an unconstrained, differentiable parameterization of the space of all possible tileable shapes for a given symmetry group. Namely, we prove that modifying the laplacian used in a 2D mesh-mapping technique - Orbifold Tutte Embedding - can achieve all possible tiling configurations for a chosen planar symmetry group. We thus consider both the mesh's tile-shape and its texture as optimizable parameters, rendering the textured mesh via a differentiable renderer. We leverage a trained image diffusion model to define a loss on the resulting image, thereby updating the mesh's parameters based on its appearance matching the text prompt. We show our method is able to produce plausible, appealing results, with non-trivial tiles, for a variety of different periodic tiling patterns.

{{</citation>}}


### (19/125) Aligning Large Multimodal Models with Factually Augmented RLHF (Zhiqing Sun et al., 2023)

{{<citation>}}

Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen, Chuang Gan, Liang-Yan Gui, Yu-Xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell. (2023)  
**Aligning Large Multimodal Models with Factually Augmented RLHF**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: GPT, GPT-4, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14525v1)  

---


**ABSTRACT**  
Large Multimodal Models (LMM) are built across modalities and the misalignment between two modalities can result in "hallucination", generating textual outputs that are not grounded by the multimodal information in context. To address the multimodal misalignment issue, we adapt the Reinforcement Learning from Human Feedback (RLHF) from the text domain to the task of vision-language alignment, where human annotators are asked to compare two responses and pinpoint the more hallucinated one, and the vision-language model is trained to maximize the simulated human rewards. We propose a new alignment algorithm called Factually Augmented RLHF that augments the reward model with additional factual information such as image captions and ground-truth multi-choice options, which alleviates the reward hacking phenomenon in RLHF and further improves the performance. We also enhance the GPT-4-generated training data (for vision instruction tuning) with previously available human-written image-text pairs to improve the general capabilities of our model. To evaluate the proposed approach in real-world scenarios, we develop a new evaluation benchmark MMHAL-BENCH with a special focus on penalizing hallucinations. As the first LMM trained with RLHF, our approach achieves remarkable improvement on the LLaVA-Bench dataset with the 94% performance level of the text-only GPT-4 (while previous best methods can only achieve the 87% level), and an improvement by 60% on MMHAL-BENCH over other baselines. We opensource our code, model, data at https://llava-rlhf.github.io.

{{</citation>}}


### (20/125) UniBEV: Multi-modal 3D Object Detection with Uniform BEV Encoders for Robustness against Missing Sensor Modalities (Shiming Wang et al., 2023)

{{<citation>}}

Shiming Wang, Holger Caesar, Liangliang Nan, Julian F. P. Kooij. (2023)  
**UniBEV: Multi-modal 3D Object Detection with Uniform BEV Encoders for Robustness against Missing Sensor Modalities**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2309.14516v1)  

---


**ABSTRACT**  
Multi-sensor object detection is an active research topic in automated driving, but the robustness of such detection models against missing sensor input (modality missing), e.g., due to a sudden sensor failure, is a critical problem which remains under-studied. In this work, we propose UniBEV, an end-to-end multi-modal 3D object detection framework designed for robustness against missing modalities: UniBEV can operate on LiDAR plus camera input, but also on LiDAR-only or camera-only input without retraining. To facilitate its detector head to handle different input combinations, UniBEV aims to create well-aligned Bird's Eye View (BEV) feature maps from each available modality. Unlike prior BEV-based multi-modal detection methods, all sensor modalities follow a uniform approach to resample features from the native sensor coordinate systems to the BEV features. We furthermore investigate the robustness of various fusion strategies w.r.t. missing modalities: the commonly used feature concatenation, but also channel-wise averaging, and a generalization to weighted averaging termed Channel Normalized Weights. To validate its effectiveness, we compare UniBEV to state-of-the-art BEVFusion and MetaBEV on nuScenes over all sensor input combinations. In this setting, UniBEV achieves $52.5 \%$ mAP on average over all input combinations, significantly improving over the baselines ($43.5 \%$ mAP on average for BEVFusion, $48.7 \%$ mAP on average for MetaBEV). An ablation study shows the robustness benefits of fusing by weighted averaging over regular concatenation, and of sharing queries between the BEV encoders of each modality. Our code will be released upon paper acceptance.

{{</citation>}}


### (21/125) Assessment of IBM and NASA's geospatial foundation model in flood inundation mapping (Wenwen Li et al., 2023)

{{<citation>}}

Wenwen Li, Hyunho Lee, Sizhe Wang, Chia-Yu Hsu, Samantha T. Arundel. (2023)  
**Assessment of IBM and NASA's geospatial foundation model in flood inundation mapping**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14500v1)  

---


**ABSTRACT**  
Vision foundation models are a new frontier in GeoAI research because of their potential to enable powerful image analysis by learning and extracting important image features from vast amounts of geospatial data. This paper evaluates the performance of the first-of-its-kind geospatial foundation model, IBM-NASA's Prithvi, to support a crucial geospatial analysis task: flood inundation mapping. This model is compared with popular convolutional neural network and vision transformer-based architectures in terms of mapping accuracy for flooded areas. A benchmark dataset, Sen1Floods11, is used in the experiments, and the models' predictability, generalizability, and transferability are evaluated based on both a test dataset and a dataset that is completely unseen by the model. Results show the impressive transferability of the Prithvi model, highlighting its performance advantages in segmenting flooded areas in previously unseen regions. The findings also suggest areas for improvement for the Prithvi model in terms of adopting multi-scale representation learning, developing more end-to-end pipelines for high-level image analysis tasks, and offering more flexibility in terms of input data bands.

{{</citation>}}


### (22/125) Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator (Hanzhuo Huang et al., 2023)

{{<citation>}}

Hanzhuo Huang, Yufan Feng, Cheng Shi, Lan Xu, Jingyi Yu, Sibei Yang. (2023)  
**Free-Bloom: Zero-Shot Text-to-Video Generator with LLM Director and LDM Animator**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2309.14494v1)  

---


**ABSTRACT**  
Text-to-video is a rapidly growing research area that aims to generate a semantic, identical, and temporal coherence sequence of frames that accurately align with the input text prompt. This study focuses on zero-shot text-to-video generation considering the data- and cost-efficient. To generate a semantic-coherent video, exhibiting a rich portrayal of temporal semantics such as the whole process of flower blooming rather than a set of "moving images", we propose a novel Free-Bloom pipeline that harnesses large language models (LLMs) as the director to generate a semantic-coherence prompt sequence, while pre-trained latent diffusion models (LDMs) as the animator to generate the high fidelity frames. Furthermore, to ensure temporal and identical coherence while maintaining semantic coherence, we propose a series of annotative modifications to adapting LDMs in the reverse process, including joint noise sampling, step-aware attention shift, and dual-path interpolation. Without any video data and training requirements, Free-Bloom generates vivid and high-quality videos, awe-inspiring in generating complex scenes with semantic meaningful frame sequences. In addition, Free-Bloom is naturally compatible with LDMs-based extensions.

{{</citation>}}


### (23/125) UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation (Jianglin Fu et al., 2023)

{{<citation>}}

Jianglin Fu, Shikai Li, Yuming Jiang, Kwan-Yee Lin, Wayne Wu, Ziwei Liu. (2023)  
**UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14335v1)  

---


**ABSTRACT**  
Human generation has achieved significant progress. Nonetheless, existing methods still struggle to synthesize specific regions such as faces and hands. We argue that the main reason is rooted in the training data. A holistic human dataset inevitably has insufficient and low-resolution information on local parts. Therefore, we propose to use multi-source datasets with various resolution images to jointly learn a high-resolution human generative model. However, multi-source data inherently a) contains different parts that do not spatially align into a coherent human, and b) comes with different scales. To tackle these challenges, we propose an end-to-end framework, UnitedHuman, that empowers continuous GAN with the ability to effectively utilize multi-source data for high-resolution human generation. Specifically, 1) we design a Multi-Source Spatial Transformer that spatially aligns multi-source images to full-body space with a human parametric model. 2) Next, a continuous GAN is proposed with global-structural guidance and CutMix consistency. Patches from different datasets are then sampled and transformed to supervise the training of this scale-invariant generative model. Extensive experiments demonstrate that our model jointly learned from multi-source data achieves superior quality than those learned from a holistic dataset.

{{</citation>}}


### (24/125) Noise-in, Bias-out: Balanced and Real-time MoCap Solving (Georgios Albanis et al., 2023)

{{<citation>}}

Georgios Albanis, Nikolaos Zioulis, Spyridon Thermos, Anargyros Chatzitofis, Kostas Kolomvatsos. (2023)  
**Noise-in, Bias-out: Balanced and Real-time MoCap Solving**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-GR, cs-LG, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.14330v1)  

---


**ABSTRACT**  
Real-time optical Motion Capture (MoCap) systems have not benefited from the advances in modern data-driven modeling. In this work we apply machine learning to solve noisy unstructured marker estimates in real-time and deliver robust marker-based MoCap even when using sparse affordable sensors. To achieve this we focus on a number of challenges related to model training, namely the sourcing of training data and their long-tailed distribution. Leveraging representation learning we design a technique for imbalanced regression that requires no additional data or labels and improves the performance of our model in rare and challenging poses. By relying on a unified representation, we show that training such a model is not bound to high-end MoCap training data acquisition, and exploit the advances in marker-less MoCap to acquire the necessary data. Finally, we take a step towards richer and affordable MoCap by adapting a body model-based inverse kinematics solution to account for measurement and inference uncertainty, further improving performance and robustness. Project page: https://moverseai.github.io/noise-tail

{{</citation>}}


### (25/125) DeepSpeed-VisualChat: Multi-Round Multi-Image Interleave Chat via Multi-Modal Causal Attention (Zhewei Yao et al., 2023)

{{<citation>}}

Zhewei Yao, Xiaoxia Wu, Conglong Li, Minjia Zhang, Heyang Qi, Olatunji Ruwase, Ammar Ahmad Awan, Samyam Rajbhandari, Yuxiong He. (2023)  
**DeepSpeed-VisualChat: Multi-Round Multi-Image Interleave Chat via Multi-Modal Causal Attention**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: Attention, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14327v1)  

---


**ABSTRACT**  
Most of the existing multi-modal models, hindered by their incapacity to adeptly manage interleaved image-and-text inputs in multi-image, multi-round dialogues, face substantial constraints in resource allocation for training and data accessibility, impacting their adaptability and scalability across varied interaction realms. To address this, we present the DeepSpeed-VisualChat framework, designed to optimize Large Language Models (LLMs) by incorporating multi-modal capabilities, with a focus on enhancing the proficiency of Large Vision and Language Models in handling interleaved inputs. Our framework is notable for (1) its open-source support for multi-round and multi-image dialogues, (2) introducing an innovative multi-modal causal attention mechanism, and (3) utilizing data blending techniques on existing datasets to assure seamless interactions in multi-round, multi-image conversations. Compared to existing frameworks, DeepSpeed-VisualChat shows superior scalability up to 70B parameter language model size, representing a significant advancement in multi-modal language models and setting a solid foundation for future explorations.

{{</citation>}}


### (26/125) Multiple Different Explanations for Image Classifiers (Hana Chockler et al., 2023)

{{<citation>}}

Hana Chockler, David A. Kelly, Daniel Kroening. (2023)  
**Multiple Different Explanations for Image Classifiers**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.14309v1)  

---


**ABSTRACT**  
Existing explanation tools for image classifiers usually give only one single explanation for an image. For many images, however, both humans and image classifiers accept more than one explanation for the image label. Thus, restricting the number of explanations to just one severely limits the insight into the behavior of the classifier. In this paper, we describe an algorithm and a tool, REX, for computing multiple explanations of the output of a black-box image classifier for a given image. Our algorithm uses a principled approach based on causal theory. We analyse its theoretical complexity and provide experimental results showing that REX finds multiple explanations on 7 times more images than the previous work on the ImageNet-mini benchmark.

{{</citation>}}


### (27/125) Dataset Diffusion: Diffusion-based Synthetic Dataset Generation for Pixel-Level Semantic Segmentation (Quang Nguyen et al., 2023)

{{<citation>}}

Quang Nguyen, Truong Vu, Anh Tran, Khoi Nguyen. (2023)  
**Dataset Diffusion: Diffusion-based Synthetic Dataset Generation for Pixel-Level Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14303v2)  

---


**ABSTRACT**  
Preparing training data for deep vision models is a labor-intensive task. To address this, generative models have emerged as an effective solution for generating synthetic data. While current generative models produce image-level category labels, we propose a novel method for generating pixel-level semantic segmentation labels using the text-to-image generative model Stable Diffusion (SD). By utilizing the text prompts, cross-attention, and self-attention of SD, we introduce three new techniques: class-prompt appending, class-prompt cross-attention, and self-attention exponentiation. These techniques enable us to generate segmentation maps corresponding to synthetic images. These maps serve as pseudo-labels for training semantic segmenters, eliminating the need for labor-intensive pixel-wise annotation. To account for the imperfections in our pseudo-labels, we incorporate uncertainty regions into the segmentation, allowing us to disregard loss from those regions. We conduct evaluations on two datasets, PASCAL VOC and MSCOCO, and our approach significantly outperforms concurrent work. Our benchmarks and code will be released at https://github.com/VinAIResearch/Dataset-Diffusion

{{</citation>}}


### (28/125) CLIP-DIY: CLIP Dense Inference Yields Open-Vocabulary Semantic Segmentation For-Free (Monika Wysoczańska et al., 2023)

{{<citation>}}

Monika Wysoczańska, Michaël Ramamonjisoa, Tomasz Trzciński, Oriane Siméoni. (2023)  
**CLIP-DIY: CLIP Dense Inference Yields Open-Vocabulary Semantic Segmentation For-Free**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14289v1)  

---


**ABSTRACT**  
The emergence of CLIP has opened the way for open-world image perception. The zero-shot classification capabilities of the model are impressive but are harder to use for dense tasks such as image segmentation. Several methods have proposed different modifications and learning schemes to produce dense output. Instead, we propose in this work an open-vocabulary semantic segmentation method, dubbed CLIP-DIY, which does not require any additional training or annotations, but instead leverages existing unsupervised object localization approaches. In particular, CLIP-DIY is a multi-scale approach that directly exploits CLIP classification abilities on patches of different sizes and aggregates the decision in a single map. We further guide the segmentation using foreground/background scores obtained using unsupervised object localization methods. With our method, we obtain state-of-the-art zero-shot semantic segmentation results on PASCAL VOC and perform on par with the best methods on COCO.

{{</citation>}}


### (29/125) Calibration-based Dual Prototypical Contrastive Learning Approach for Domain Generalization Semantic Segmentation (Muxin Liao et al., 2023)

{{<citation>}}

Muxin Liao, Shishun Tian, Yuhang Zhang, Guoguang Hua, Wenbin Zou, Xia Li. (2023)  
**Calibration-based Dual Prototypical Contrastive Learning Approach for Domain Generalization Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14282v1)  

---


**ABSTRACT**  
Prototypical contrastive learning (PCL) has been widely used to learn class-wise domain-invariant features recently. These methods are based on the assumption that the prototypes, which are represented as the central value of the same class in a certain domain, are domain-invariant. Since the prototypes of different domains have discrepancies as well, the class-wise domain-invariant features learned from the source domain by PCL need to be aligned with the prototypes of other domains simultaneously. However, the prototypes of the same class in different domains may be different while the prototypes of different classes may be similar, which may affect the learning of class-wise domain-invariant features. Based on these observations, a calibration-based dual prototypical contrastive learning (CDPCL) approach is proposed to reduce the domain discrepancy between the learned class-wise features and the prototypes of different domains for domain generalization semantic segmentation. It contains an uncertainty-guided PCL (UPCL) and a hard-weighted PCL (HPCL). Since the domain discrepancies of the prototypes of different classes may be different, we propose an uncertainty probability matrix to represent the domain discrepancies of the prototypes of all the classes. The UPCL estimates the uncertainty probability matrix to calibrate the weights of the prototypes during the PCL. Moreover, considering that the prototypes of different classes may be similar in some circumstances, which means these prototypes are hard-aligned, the HPCL is proposed to generate a hard-weighted matrix to calibrate the weights of the hard-aligned prototypes during the PCL. Extensive experiments demonstrate that our approach achieves superior performance over current approaches on domain generalization semantic segmentation tasks.

{{</citation>}}


### (30/125) Identity-preserving Editing of Multiple Facial Attributes by Learning Global Edit Directions and Local Adjustments (Najmeh Mohammadbagheri et al., 2023)

{{<citation>}}

Najmeh Mohammadbagheri, Fardin Ayar, Ahmad Nickabadi, Reza Safabakhsh. (2023)  
**Identity-preserving Editing of Multiple Facial Attributes by Learning Global Edit Directions and Local Adjustments**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14267v1)  

---


**ABSTRACT**  
Semantic facial attribute editing using pre-trained Generative Adversarial Networks (GANs) has attracted a great deal of attention and effort from researchers in recent years. Due to the high quality of face images generated by StyleGANs, much work has focused on the StyleGANs' latent space and the proposed methods for facial image editing. Although these methods have achieved satisfying results for manipulating user-intended attributes, they have not fulfilled the goal of preserving the identity, which is an important challenge. We present ID-Style, a new architecture capable of addressing the problem of identity loss during attribute manipulation. The key components of ID-Style include Learnable Global Direction (LGD), which finds a shared and semi-sparse direction for each attribute, and an Instance-Aware Intensity Predictor (IAIP) network, which finetunes the global direction according to the input instance. Furthermore, we introduce two losses during training to enforce the LGD to find semi-sparse semantic directions, which along with the IAIP, preserve the identity of the input instance. Despite reducing the size of the network by roughly 95% as compared to similar state-of-the-art works, it outperforms baselines by 10% and 7% in Identity preserving metric (FRS) and average accuracy of manipulation (mACC), respectively.

{{</citation>}}


### (31/125) Informative Data Mining for One-Shot Cross-Domain Semantic Segmentation (Yuxi Wang et al., 2023)

{{<citation>}}

Yuxi Wang, Jian Liang, Jun Xiao, Shuqi Mei, Yuran Yang, Zhaoxiang Zhang. (2023)  
**Informative Data Mining for One-Shot Cross-Domain Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14241v1)  

---


**ABSTRACT**  
Contemporary domain adaptation offers a practical solution for achieving cross-domain transfer of semantic segmentation between labeled source data and unlabeled target data. These solutions have gained significant popularity; however, they require the model to be retrained when the test environment changes. This can result in unbearable costs in certain applications due to the time-consuming training process and concerns regarding data privacy. One-shot domain adaptation methods attempt to overcome these challenges by transferring the pre-trained source model to the target domain using only one target data. Despite this, the referring style transfer module still faces issues with computation cost and over-fitting problems. To address this problem, we propose a novel framework called Informative Data Mining (IDM) that enables efficient one-shot domain adaptation for semantic segmentation. Specifically, IDM provides an uncertainty-based selection criterion to identify the most informative samples, which facilitates quick adaptation and reduces redundant training. We then perform a model adaptation method using these selected samples, which includes patch-wise mixing and prototype-based information maximization to update the model. This approach effectively enhances adaptation and mitigates the overfitting problem. In general, we provide empirical evidence of the effectiveness and efficiency of IDM. Our approach outperforms existing methods and achieves a new state-of-the-art one-shot performance of 56.7\%/55.4\% on the GTA5/SYNTHIA to Cityscapes adaptation tasks, respectively. The code will be released at \url{https://github.com/yxiwang/IDM}.

{{</citation>}}


### (32/125) Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-level Vision (Haoning Wu et al., 2023)

{{<citation>}}

Haoning Wu, Zicheng Zhang, Erli Zhang, Chaofeng Chen, Liang Liao, Annan Wang, Chunyi Li, Wenxiu Sun, Qiong Yan, Guangtao Zhai, Weisi Lin. (2023)  
**Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-level Vision**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-MM, cs.CV  
Keywords: GPT, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2309.14181v2)  

---


**ABSTRACT**  
The rapid evolution of Multi-modality Large Language Models (MLLMs) has catalyzed a shift in computer vision from specialized models to general-purpose foundation models. Nevertheless, there is still an inadequacy in assessing the abilities of MLLMs on low-level visual perception and understanding. To address this gap, we present Q-Bench, a holistic benchmark crafted to systematically evaluate potential abilities of MLLMs on three realms: low-level visual perception, low-level visual description, and overall visual quality assessment. a) To evaluate the low-level perception ability, we construct the LLVisionQA dataset, consisting of 2,990 diverse-sourced images, each equipped with a human-asked question focusing on its low-level attributes. We then measure the correctness of MLLMs on answering these questions. b) To examine the description ability of MLLMs on low-level information, we propose the LLDescribe dataset consisting of long expert-labelled golden low-level text descriptions on 499 images, and a GPT-involved comparison pipeline between outputs of MLLMs and the golden descriptions. c) Besides these two tasks, we further measure their visual quality assessment ability to align with human opinion scores. Specifically, we design a softmax-based strategy that enables MLLMs to predict quantifiable quality scores, and evaluate them on various existing image quality assessment (IQA) datasets. Our evaluation across the three abilities confirms that MLLMs possess preliminary low-level visual skills. However, these skills are still unstable and relatively imprecise, indicating the need for specific enhancements on MLLMs towards these abilities. We hope that our benchmark can encourage the research community to delve deeper to discover and enhance these untapped potentials of MLLMs. Project Page: https://vqassessment.github.io/Q-Bench.

{{</citation>}}


### (33/125) Data Upcycling Knowledge Distillation for Image Super-Resolution (Yun Zhang et al., 2023)

{{<citation>}}

Yun Zhang, Wei Li, Simiao Li, Jie Hu, Hanting Chen, Hailing Wang, Zhijun Tu, Wenjia Wang, Bingyi Jing, Yunhe Wang. (2023)  
**Data Upcycling Knowledge Distillation for Image Super-Resolution**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2309.14162v1)  

---


**ABSTRACT**  
Knowledge distillation (KD) emerges as a challenging yet promising technique for compressing deep learning models, characterized by the transmission of extensive learning representations from proficient and computationally intensive teacher models to compact student models. However, only a handful of studies have endeavored to compress the models for single image super-resolution (SISR) through KD, with their effects on student model enhancement remaining marginal. In this paper, we put forth an approach from the perspective of efficient data utilization, namely, the Data Upcycling Knowledge Distillation (DUKD) which facilitates the student model by the prior knowledge teacher provided via upcycled in-domain data derived from their inputs. This upcycling process is realized through two efficient image zooming operations and invertible data augmentations which introduce the label consistency regularization to the field of KD for SISR and substantially boosts student model's generalization. The DUKD, due to its versatility, can be applied across a broad spectrum of teacher-student architectures. Comprehensive experiments across diverse benchmarks demonstrate that our proposed DUKD method significantly outperforms previous art, exemplified by an increase of up to 0.5dB in PSNR over baselines methods, and a 67% parameters reduced RCAN model's performance remaining on par with that of the RCAN teacher model.

{{</citation>}}


### (34/125) LAPP: Layer Adaptive Progressive Pruning for Compressing CNNs from Scratch (Pucheng Zhai et al., 2023)

{{<citation>}}

Pucheng Zhai, Kailing Guo, Fang Liu, Xiaofen Xing, Xiangmin Xu. (2023)  
**LAPP: Layer Adaptive Progressive Pruning for Compressing CNNs from Scratch**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Pruning  
[Paper Link](http://arxiv.org/abs/2309.14157v1)  

---


**ABSTRACT**  
Structured pruning is a commonly used convolutional neural network (CNN) compression approach. Pruning rate setting is a fundamental problem in structured pruning. Most existing works introduce too many additional learnable parameters to assign different pruning rates across different layers in CNN or cannot control the compression rate explicitly. Since too narrow network blocks information flow for training, automatic pruning rate setting cannot explore a high pruning rate for a specific layer. To overcome these limitations, we propose a novel framework named Layer Adaptive Progressive Pruning (LAPP), which gradually compresses the network during initial training of a few epochs from scratch. In particular, LAPP designs an effective and efficient pruning strategy that introduces a learnable threshold for each layer and FLOPs constraints for network. Guided by both task loss and FLOPs constraints, the learnable thresholds are dynamically and gradually updated to accommodate changes of importance scores during training. Therefore the pruning strategy can gradually prune the network and automatically determine the appropriate pruning rates for each layer. What's more, in order to maintain the expressive power of the pruned layer, before training starts, we introduce an additional lightweight bypass for each convolutional layer to be pruned, which only adds relatively few additional burdens. Our method demonstrates superior performance gains over previous compression methods on various datasets and backbone architectures. For example, on CIFAR-10, our method compresses ResNet-20 to 40.3% without accuracy drop. 55.6% of FLOPs of ResNet-18 are reduced with 0.21% top-1 accuracy increase and 0.40% top-5 accuracy increase on ImageNet.

{{</citation>}}


### (35/125) Masked Image Residual Learning for Scaling Deeper Vision Transformers (Guoxi Huang et al., 2023)

{{<citation>}}

Guoxi Huang, Hongtao Fu, Adrian G. Bors. (2023)  
**Masked Image Residual Learning for Scaling Deeper Vision Transformers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.14136v1)  

---


**ABSTRACT**  
Deeper Vision Transformers (ViTs) are more challenging to train. We expose a degradation problem in deeper layers of ViT when using masked image modeling (MIM) for pre-training. To ease the training of deeper ViTs, we introduce a self-supervised learning framework called \textbf{M}asked \textbf{I}mage \textbf{R}esidual \textbf{L}earning (\textbf{MIRL}), which significantly alleviates the degradation problem, making scaling ViT along depth a promising direction for performance upgrade. We reformulate the pre-training objective for deeper layers of ViT as learning to recover the residual of the masked image. We provide extensive empirical evidence showing that deeper ViTs can be effectively optimized using MIRL and easily gain accuracy from increased depth. With the same level of computational complexity as ViT-Base and ViT-Large, we instantiate 4.5{$\times$} and 2{$\times$} deeper ViTs, dubbed ViT-S-54 and ViT-B-48. The deeper ViT-S-54, costing 3{$\times$} less than ViT-Large, achieves performance on par with ViT-Large. ViT-B-48 achieves 86.2\% top-1 accuracy on ImageNet. On one hand, deeper ViTs pre-trained with MIRL exhibit excellent generalization capabilities on downstream tasks, such as object detection and semantic segmentation. On the other hand, MIRL demonstrates high pre-training efficiency. With less pre-training time, MIRL yields competitive performance compared to other approaches.

{{</citation>}}


### (36/125) Small Objects Matters in Weakly-supervised Semantic Segmentation (Cheolhyun Mun et al., 2023)

{{<citation>}}

Cheolhyun Mun, Sanghuk Lee, Youngjung Uh, Junsuk Choe, Hyeran Byun. (2023)  
**Small Objects Matters in Weakly-supervised Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14117v1)  

---


**ABSTRACT**  
Weakly-supervised semantic segmentation (WSSS) performs pixel-wise classification given only image-level labels for training. Despite the difficulty of this task, the research community has achieved promising results over the last five years. Still, current WSSS literature misses the detailed sense of how well the methods perform on different sizes of objects. Thus we propose a novel evaluation metric to provide a comprehensive assessment across different object sizes and collect a size-balanced evaluation set to complement PASCAL VOC. With these two gadgets, we reveal that the existing WSSS methods struggle in capturing small objects. Furthermore, we propose a size-balanced cross-entropy loss coupled with a proper training strategy. It generally improves existing WSSS methods as validated upon ten baselines on three different datasets.

{{</citation>}}


### (37/125) AsymFormer: Asymmetrical Cross-Modal Representation Learning for Mobile Platform Real-Time RGB-D Semantic Segmentation (Siqi Du et al., 2023)

{{<citation>}}

Siqi Du, Weixi Wang, Renzhong Guo, Shengjun Tang. (2023)  
**AsymFormer: Asymmetrical Cross-Modal Representation Learning for Mobile Platform Real-Time RGB-D Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Embedding, Representation Learning, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14065v2)  

---


**ABSTRACT**  
In the realm of robotic intelligence, achieving efficient and precise RGB-D semantic segmentation is a key cornerstone. State-of-the-art multimodal semantic segmentation methods, primarily rooted in symmetrical skeleton networks, find it challenging to harmonize computational efficiency and precision. In this work, we propose AsymFormer, a novel network for real-time RGB-D semantic segmentation, which targets the minimization of superfluous parameters by optimizing the distribution of computational resources and introduces an asymmetrical backbone to allow for the effective fusion of multimodal features. Furthermore, we explore techniques to bolster network accuracy by redefining feature selection and extracting multi-modal self-similarity features without a substantial increase in the parameter count, thereby ensuring real-time execution on robotic platforms. Additionally, a Local Attention-Guided Feature Selection (LAFS) module is used to selectively fuse features from different modalities by leveraging their dependencies. Subsequently, a Cross-Modal Attention-Guided Feature Correlation Embedding (CMA) module is introduced to further extract cross-modal representations. This method is evaluated on NYUv2 and SUNRGBD datasets, with AsymFormer demonstrating competitive results with 52.0% mIoU on NYUv2 and 49.1% mIoU on SUNRGBD. Notably, AsymFormer achieves an inference speed of 65 FPS and after implementing mixed precision quantization, it attains an impressive inference speed of 79 FPS on RTX3090. This significantly outperforms existing multi-modal methods, thereby demonstrating that AsymFormer can strike a balance between high accuracy and efficiency for RGB-D semantic segmentation.

{{</citation>}}


### (38/125) Weakly Supervised Semantic Segmentation by Knowledge Graph Inference (Jia Zhang et al., 2023)

{{<citation>}}

Jia Zhang, Bo Peng, Xi Wu. (2023)  
**Weakly Supervised Semantic Segmentation by Knowledge Graph Inference**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Knowledge Graph, Reasoning, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.14057v1)  

---


**ABSTRACT**  
Currently, existing efforts in Weakly Supervised Semantic Segmentation (WSSS) based on Convolutional Neural Networks (CNNs) have predominantly focused on enhancing the multi-label classification network stage, with limited attention given to the equally important downstream segmentation network. Furthermore, CNN-based local convolutions lack the ability to model the extensive inter-category dependencies. Therefore, this paper introduces a graph reasoning-based approach to enhance WSSS. The aim is to improve WSSS holistically by simultaneously enhancing both the multi-label classification and segmentation network stages. In the multi-label classification network segment, external knowledge is integrated, coupled with GCNs, to globally reason about inter-class dependencies. This encourages the network to uncover features in non-salient regions of images, thereby refining the completeness of generated pseudo-labels. In the segmentation network segment, the proposed Graph Reasoning Mapping (GRM) module is employed to leverage knowledge obtained from textual databases, facilitating contextual reasoning for class representation within image regions. This GRM module enhances feature representation in high-level semantics of the segmentation network's local convolutions, while dynamically learning semantic coherence for individual samples. Using solely image-level supervision, we have achieved state-of-the-art performance in WSSS on the PASCAL VOC 2012 and MS-COCO datasets. Extensive experimentation on both the multi-label classification and segmentation network stages underscores the effectiveness of the proposed graph reasoning approach for advancing WSSS.

{{</citation>}}


### (39/125) Egocentric RGB+Depth Action Recognition in Industry-Like Settings (Jyoti Kini et al., 2023)

{{<citation>}}

Jyoti Kini, Sarah Fleischer, Ishan Dave, Mubarak Shah. (2023)  
**Egocentric RGB+Depth Action Recognition in Industry-Like Settings**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.13962v1)  

---


**ABSTRACT**  
Action recognition from an egocentric viewpoint is a crucial perception task in robotics and enables a wide range of human-robot interactions. While most computer vision approaches prioritize the RGB camera, the Depth modality - which can further amplify the subtleties of actions from an egocentric perspective - remains underexplored. Our work focuses on recognizing actions from egocentric RGB and Depth modalities in an industry-like environment. To study this problem, we consider the recent MECCANO dataset, which provides a wide range of assembling actions. Our framework is based on the 3D Video SWIN Transformer to encode both RGB and Depth modalities effectively. To address the inherent skewness in real-world multimodal action occurrences, we propose a training strategy using an exponentially decaying variant of the focal loss modulating factor. Additionally, to leverage the information in both RGB and Depth modalities, we opt for late fusion to combine the predictions from each modality. We thoroughly evaluate our method on the action recognition task of the MECCANO dataset, and it significantly outperforms the prior work. Notably, our method also secured first place at the multimodal action recognition challenge at ICIAP 2023.

{{</citation>}}


### (40/125) Speed Co-Augmentation for Unsupervised Audio-Visual Pre-training (Jiangliu Wang et al., 2023)

{{<citation>}}

Jiangliu Wang, Jianbo Jiao, Yibing Song, Stephen James, Zhan Tong, Chongjian Ge, Pieter Abbeel, Yun-hui Liu. (2023)  
**Speed Co-Augmentation for Unsupervised Audio-Visual Pre-training**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs-SD, cs.CV, eess-AS  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2309.13942v1)  

---


**ABSTRACT**  
This work aims to improve unsupervised audio-visual pre-training. Inspired by the efficacy of data augmentation in visual contrastive learning, we propose a novel speed co-augmentation method that randomly changes the playback speeds of both audio and video data. Despite its simplicity, the speed co-augmentation method possesses two compelling attributes: (1) it increases the diversity of audio-visual pairs and doubles the size of negative pairs, resulting in a significant enhancement in the learned representations, and (2) it changes the strict correlation between audio-visual pairs but introduces a partial relationship between the augmented pairs, which is modeled by our proposed SoftInfoNCE loss to further boost the performance. Experimental results show that the proposed method significantly improves the learned representations when compared to vanilla audio-visual contrastive learning.

{{</citation>}}


### (41/125) A Lightweight Recurrent Grouping Attention Network for Video Super-Resolution (Yonggui Zhu et al., 2023)

{{<citation>}}

Yonggui Zhu, Guofang Li. (2023)  
**A Lightweight Recurrent Grouping Attention Network for Video Super-Resolution**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.13940v1)  

---


**ABSTRACT**  
Effective aggregation of temporal information of consecutive frames is the core of achieving video super-resolution. Many scholars have utilized structures such as sliding windows and recurrent to gather spatio-temporal information of frames. However, although the performance of the constructed VSR models is improving, the size of the models is also increasing, exacerbating the demand on the equipment. Thus, to reduce the stress on the device, we propose a novel lightweight recurrent grouping attention network. The parameters of this model are only 0.878M, which is much lower than the current mainstream model for studying video super-resolution. We design forward feature extraction module and backward feature extraction module to collect temporal information between consecutive frames from two directions. Moreover, a new grouping mechanism is proposed to efficiently collect spatio-temporal information of the reference frame and its neighboring frames. The attention supplementation module is presented to further enhance the information gathering range of the model. The feature reconstruction module aims to aggregate information from different directions to reconstruct high-resolution features. Experiments demonstrate that our model achieves state-of-the-art performance on multiple datasets.

{{</citation>}}


### (42/125) Analyzing the Efficacy of an LLM-Only Approach for Image-based Document Question Answering (Nidhi Hegde et al., 2023)

{{<citation>}}

Nidhi Hegde, Sujoy Paul, Gagan Madan, Gaurav Aggarwal. (2023)  
**Analyzing the Efficacy of an LLM-Only Approach for Image-based Document Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Language Model, Question Answering  
[Paper Link](http://arxiv.org/abs/2309.14389v1)  

---


**ABSTRACT**  
Recent document question answering models consist of two key components: the vision encoder, which captures layout and visual elements in images, and a Large Language Model (LLM) that helps contextualize questions to the image and supplements them with external world knowledge to generate accurate answers. However, the relative contributions of the vision encoder and the language model in these tasks remain unclear. This is especially interesting given the effectiveness of instruction-tuned LLMs, which exhibit remarkable adaptability to new tasks. To this end, we explore the following aspects in this work: (1) The efficacy of an LLM-only approach on document question answering tasks (2) strategies for serializing textual information within document images and feeding it directly to an instruction-tuned LLM, thus bypassing the need for an explicit vision encoder (3) thorough quantitative analysis on the feasibility of such an approach. Our comprehensive analysis encompasses six diverse benchmark datasets, utilizing LLMs of varying scales. Our findings reveal that a strategy exclusively reliant on the LLM yields results that are on par with or closely approach state-of-the-art performance across a range of datasets. We posit that this evaluation framework will serve as a guiding resource for selecting appropriate datasets for future research endeavors that emphasize the fundamental importance of layout and image content information.

{{</citation>}}


### (43/125) Subspace-Aware Feature Reconstruction for Unsupervised Anomaly Localization (Katsuya Hotta et al., 2023)

{{<citation>}}

Katsuya Hotta, Chao Zhang, Yoshihiro Hagihara, Takuya Akashi. (2023)  
**Subspace-Aware Feature Reconstruction for Unsupervised Anomaly Localization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.13904v1)  

---


**ABSTRACT**  
Unsupervised anomaly localization, which plays a critical role in industrial manufacturing, is to identify anomalous regions that deviate from patterns established exclusively from nominal samples. Recent mainstream methods focus on approximating the target feature distribution by leveraging embeddings from ImageNet models. However, a common issue in many anomaly localization methods is the lack of adaptability of the feature approximations to specific targets. Consequently, their ability to effectively identify anomalous regions relies significantly on the data coverage provided by the finite resources in a memory bank. In this paper, we propose a novel subspace-aware feature reconstruction framework for anomaly localization. To achieve adaptive feature approximation, our proposed method involves the reconstruction of the feature representation through the self-expressive model designed to learn low-dimensional subspaces. Importantly, the sparsity of the subspace representation contributes to covering feature patterns from the same subspace with fewer resources, leading to a reduction in the memory bank. Extensive experiments across three industrial benchmark datasets demonstrate that our approach achieves competitive anomaly localization performance compared to state-of-the-art methods by adaptively reconstructing target features with a small number of samples.

{{</citation>}}


### (44/125) Skip-Connected Neural Networks with Layout Graphs for Floor Plan Auto-Generation (Yuntae Jeon et al., 2023)

{{<citation>}}

Yuntae Jeon, Dai Quoc Tran, Seunghee Park. (2023)  
**Skip-Connected Neural Networks with Layout Graphs for Floor Plan Auto-Generation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, GNN  
[Paper Link](http://arxiv.org/abs/2309.13881v2)  

---


**ABSTRACT**  
With the advent of AI and computer vision techniques, the quest for automated and efficient floor plan designs has gained momentum. This paper presents a novel approach using skip-connected neural networks integrated with layout graphs. The skip-connected layers capture multi-scale floor plan information, and the encoder-decoder networks with GNN facilitate pixel-level probability-based generation. Validated on the MSD dataset, our approach achieved a 93.9 mIoU score in the 1st CVAAD workshop challenge. Code and pre-trained models are publicly available at https://github.com/yuntaeJ/SkipNet-FloorPlanGe.

{{</citation>}}


### (45/125) Adversarial Attacks on Video Object Segmentation with Hard Region Discovery (Ping Li et al., 2023)

{{<citation>}}

Ping Li, Yu Zhang, Li Yuan, Jian Zhao, Xianghua Xu, Xiaoqin Zhang. (2023)  
**Adversarial Attacks on Video Object Segmentation with Hard Region Discovery**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2309.13857v1)  

---


**ABSTRACT**  
Video object segmentation has been applied to various computer vision tasks, such as video editing, autonomous driving, and human-robot interaction. However, the methods based on deep neural networks are vulnerable to adversarial examples, which are the inputs attacked by almost human-imperceptible perturbations, and the adversary (i.e., attacker) will fool the segmentation model to make incorrect pixel-level predictions. This will rise the security issues in highly-demanding tasks because small perturbations to the input video will result in potential attack risks. Though adversarial examples have been extensively used for classification, it is rarely studied in video object segmentation. Existing related methods in computer vision either require prior knowledge of categories or cannot be directly applied due to the special design for certain tasks, failing to consider the pixel-wise region attack. Hence, this work develops an object-agnostic adversary that has adversarial impacts on VOS by first-frame attacking via hard region discovery. Particularly, the gradients from the segmentation model are exploited to discover the easily confused region, in which it is difficult to identify the pixel-wise objects from the background in a frame. This provides a hardness map that helps to generate perturbations with a stronger adversarial power for attacking the first frame. Empirical studies on three benchmarks indicate that our attacker significantly degrades the performance of several state-of-the-art video object segmentation models.

{{</citation>}}


### (46/125) DISeR: Designing Imaging Systems with Reinforcement Learning (Tzofi Klinghoffer et al., 2023)

{{<citation>}}

Tzofi Klinghoffer, Kushagra Tiwary, Nikhil Behari, Bhavya Agrawalla, Ramesh Raskar. (2023)  
**DISeR: Designing Imaging Systems with Reinforcement Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.13851v1)  

---


**ABSTRACT**  
Imaging systems consist of cameras to encode visual information about the world and perception models to interpret this encoding. Cameras contain (1) illumination sources, (2) optical elements, and (3) sensors, while perception models use (4) algorithms. Directly searching over all combinations of these four building blocks to design an imaging system is challenging due to the size of the search space. Moreover, cameras and perception models are often designed independently, leading to sub-optimal task performance. In this paper, we formulate these four building blocks of imaging systems as a context-free grammar (CFG), which can be automatically searched over with a learned camera designer to jointly optimize the imaging system with task-specific perception models. By transforming the CFG to a state-action space, we then show how the camera designer can be implemented with reinforcement learning to intelligently search over the combinatorial space of possible imaging system configurations. We demonstrate our approach on two tasks, depth estimation and camera rig design for autonomous vehicles, showing that our method yields rigs that outperform industry-wide standards. We believe that our proposed approach is an important step towards automating imaging system design.

{{</citation>}}


### (47/125) Dual Feature Augmentation Network for Generalized Zero-shot Learning (Lei Xiang et al., 2023)

{{<citation>}}

Lei Xiang, Yuan Zhou, Haoran Duan, Yang Long. (2023)  
**Dual Feature Augmentation Network for Generalized Zero-shot Learning**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2309.13833v1)  

---


**ABSTRACT**  
Zero-shot learning (ZSL) aims to infer novel classes without training samples by transferring knowledge from seen classes. Existing embedding-based approaches for ZSL typically employ attention mechanisms to locate attributes on an image. However, these methods often ignore the complex entanglement among different attributes' visual features in the embedding space. Additionally, these methods employ a direct attribute prediction scheme for classification, which does not account for the diversity of attributes in images of the same category. To address these issues, we propose a novel Dual Feature Augmentation Network (DFAN), which comprises two feature augmentation modules, one for visual features and the other for semantic features. The visual feature augmentation module explicitly learns attribute features and employs cosine distance to separate them, thus enhancing attribute representation. In the semantic feature augmentation module, we propose a bias learner to capture the offset that bridges the gap between actual and predicted attribute values from a dataset's perspective. Furthermore, we introduce two predictors to reconcile the conflicts between local and global features. Experimental results on three benchmarks demonstrate the marked advancement of our method compared to state-of-the-art approaches. Our code is available at https://github.com/Sion1/DFAN.

{{</citation>}}


### (48/125) PARTICLE: Part Discovery and Contrastive Learning for Fine-grained Recognition (Oindrila Saha et al., 2023)

{{<citation>}}

Oindrila Saha, Subhransu Maji. (2023)  
**PARTICLE: Part Discovery and Contrastive Learning for Fine-grained Recognition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning, ImageNet  
[Paper Link](http://arxiv.org/abs/2309.13822v1)  

---


**ABSTRACT**  
We develop techniques for refining representations for fine-grained classification and segmentation tasks in a self-supervised manner. We find that fine-tuning methods based on instance-discriminative contrastive learning are not as effective, and posit that recognizing part-specific variations is crucial for fine-grained categorization. We present an iterative learning approach that incorporates part-centric equivariance and invariance objectives. First, pixel representations are clustered to discover parts. We analyze the representations from convolutional and vision transformer networks that are best suited for this task. Then, a part-centric learning step aggregates and contrasts representations of parts within an image. We show that this improves the performance on image classification and part segmentation tasks across datasets. For example, under a linear-evaluation scheme, the classification accuracy of a ResNet50 trained on ImageNet using DetCon, a self-supervised learning approach, improves from 35.4% to 42.0% on the Caltech-UCSD Birds, from 35.5% to 44.1% on the FGVC Aircraft, and from 29.7% to 37.4% on the Stanford Cars. We also observe significant gains in few-shot part segmentation tasks using the proposed technique, while instance-discriminative learning was not as effective. Smaller, yet consistent, improvements are also observed for stronger networks based on transformers.

{{</citation>}}


## cs.AI (4)



### (49/125) Algorithmic Collusion or Competition: the Role of Platforms' Recommender Systems (Xingchen Xu et al., 2023)

{{<citation>}}

Xingchen Xu, Stephanie Lee, Yong Tan. (2023)  
**Algorithmic Collusion or Competition: the Role of Platforms' Recommender Systems**  

---
Primary Category: cs.AI  
Categories: J-4, cs-AI, cs-IR, cs.AI, econ-GN, q-fin-EC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14548v1)  

---


**ABSTRACT**  
Recent academic research has extensively examined algorithmic collusion resulting from the utilization of artificial intelligence (AI)-based dynamic pricing algorithms. Nevertheless, e-commerce platforms employ recommendation algorithms to allocate exposure to various products, and this important aspect has been largely overlooked in previous studies on algorithmic collusion. Our study bridges this important gap in the literature and examines how recommendation algorithms can determine the competitive or collusive dynamics of AI-based pricing algorithms. Specifically, two commonly deployed recommendation algorithms are examined: (i) a recommender system that aims to maximize the sellers' total profit (profit-based recommender system) and (ii) a recommender system that aims to maximize the demand for products sold on the platform (demand-based recommender system). We construct a repeated game framework that incorporates both pricing algorithms adopted by sellers and the platform's recommender system. Subsequently, we conduct experiments to observe price dynamics and ascertain the final equilibrium. Experimental results reveal that a profit-based recommender system intensifies algorithmic collusion among sellers due to its congruence with sellers' profit-maximizing objectives. Conversely, a demand-based recommender system fosters price competition among sellers and results in a lower price, owing to its misalignment with sellers' goals. Extended analyses suggest the robustness of our findings in various market scenarios. Overall, we highlight the importance of platforms' recommender systems in delineating the competitive structure of the digital marketplace, providing important insights for market participants and corresponding policymakers.

{{</citation>}}


### (50/125) Identifying the Risks of LM Agents with an LM-Emulated Sandbox (Yangjun Ruan et al., 2023)

{{<citation>}}

Yangjun Ruan, Honghua Dong, Andrew Wang, Silviu Pitis, Yongchao Zhou, Jimmy Ba, Yann Dubois, Chris J. Maddison, Tatsunori Hashimoto. (2023)  
**Identifying the Risks of LM Agents with an LM-Emulated Sandbox**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.15817v1)  

---


**ABSTRACT**  
Recent advances in Language Model (LM) agents and tool use, exemplified by applications like ChatGPT Plugins, enable a rich set of capabilities but also amplify potential risks - such as leaking private data or causing financial losses. Identifying these risks is labor-intensive, necessitating implementing the tools, manually setting up the environment for each test scenario, and finding risky cases. As tools and agents become more complex, the high cost of testing these agents will make it increasingly difficult to find high-stakes, long-tailed risks. To address these challenges, we introduce ToolEmu: a framework that uses an LM to emulate tool execution and enables the testing of LM agents against a diverse range of tools and scenarios, without manual instantiation. Alongside the emulator, we develop an LM-based automatic safety evaluator that examines agent failures and quantifies associated risks. We test both the tool emulator and evaluator through human evaluation and find that 68.8% of failures identified with ToolEmu would be valid real-world agent failures. Using our curated initial benchmark consisting of 36 high-stakes tools and 144 test cases, we provide a quantitative risk analysis of current LM agents and identify numerous failures with potentially severe outcomes. Notably, even the safest LM agent exhibits such failures 23.9% of the time according to our evaluator, underscoring the need to develop safer LM agents for real-world deployment.

{{</citation>}}


### (51/125) Prior Bilinear Based Models for Knowledge Graph Completion (Jiayi Li et al., 2023)

{{<citation>}}

Jiayi Li, Ruilin Luo, Jiaqi Sun, Jing Xiao, Yujiu Yang. (2023)  
**Prior Bilinear Based Models for Knowledge Graph Completion**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2309.13834v1)  

---


**ABSTRACT**  
Bilinear based models are powerful and widely used approaches for Knowledge Graphs Completion (KGC). Although bilinear based models have achieved significant advances, these studies mainly concentrate on posterior properties (based on evidence, e.g. symmetry pattern) while neglecting the prior properties. In this paper, we find a prior property named "the law of identity" that cannot be captured by bilinear based models, which hinders them from comprehensively modeling the characteristics of KGs. To address this issue, we introduce a solution called Unit Ball Bilinear Model (UniBi). This model not only achieves theoretical superiority but also offers enhanced interpretability and performance by minimizing ineffective learning through minimal constraints. Experiments demonstrate that UniBi models the prior property and verify its interpretability and performance.

{{</citation>}}


### (52/125) Evaluating Cognitive Maps and Planning in Large Language Models with CogEval (Ida Momennejad et al., 2023)

{{<citation>}}

Ida Momennejad, Hosein Hasanbeig, Felipe Vieira, Hiteshi Sharma, Robert Osazuwa Ness, Nebojsa Jojic, Hamid Palangi, Jonathan Larson. (2023)  
**Evaluating Cognitive Maps and Planning in Large Language Models with CogEval**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI  
Keywords: AI, GPT, GPT-3.5, GPT-4, Google, LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2309.15129v1)  

---


**ABSTRACT**  
Recently an influx of studies claim emergent cognitive abilities in large language models (LLMs). Yet, most rely on anecdotes, overlook contamination of training sets, or lack systematic Evaluation involving multiple tasks, control conditions, multiple iterations, and statistical robustness tests. Here we make two major contributions. First, we propose CogEval, a cognitive science-inspired protocol for the systematic evaluation of cognitive capacities in Large Language Models. The CogEval protocol can be followed for the evaluation of various abilities. Second, here we follow CogEval to systematically evaluate cognitive maps and planning ability across eight LLMs (OpenAI GPT-4, GPT-3.5-turbo-175B, davinci-003-175B, Google Bard, Cohere-xlarge-52.4B, Anthropic Claude-1-52B, LLaMA-13B, and Alpaca-7B). We base our task prompts on human experiments, which offer both established construct validity for evaluating planning, and are absent from LLM training sets. We find that, while LLMs show apparent competence in a few planning tasks with simpler structures, systematic evaluation reveals striking failure modes in planning tasks, including hallucinations of invalid trajectories and getting trapped in loops. These findings do not support the idea of emergent out-of-the-box planning ability in LLMs. This could be because LLMs do not understand the latent relational structures underlying planning problems, known as cognitive maps, and fail at unrolling goal-directed trajectories based on the underlying structure. Implications for application and future directions are discussed.

{{</citation>}}


## cs.HC (12)



### (53/125) 'Teach AI How to Code': Using Large Language Models as Teachable Agents for Programming Education (Hyoungwook Jin et al., 2023)

{{<citation>}}

Hyoungwook Jin, Seonghee Lee, Hyungyu Shin, Juho Kim. (2023)  
**'Teach AI How to Code': Using Large Language Models as Teachable Agents for Programming Education**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14534v1)  

---


**ABSTRACT**  
This work investigates large language models (LLMs) as teachable agents for learning by teaching (LBT). LBT with teachable agents helps learners identify their knowledge gaps and discover new knowledge. However, teachable agents require expensive programming of subject-specific knowledge. While LLMs as teachable agents can reduce the cost, LLMs' over-competence as tutees discourages learners from teaching. We propose a prompting pipeline that restrains LLMs' competence and makes them initiate "why" and "how" questions for effective knowledge-building. We combined these techniques into TeachYou, an LBT environment for algorithm learning, and AlgoBo, an LLM-based tutee chatbot that can simulate misconceptions and unawareness prescribed in its knowledge state. Our technical evaluation confirmed that our prompting pipeline can effectively configure AlgoBo's problem-solving performance. Through a between-subject study with 40 algorithm novices, we also observed that AlgoBo's questions led to knowledge-dense conversations (effect size=0.73). Lastly, we discuss design implications, cost-efficiency, and personalization of LLM-based teachable agents.

{{</citation>}}


### (54/125) Watch Your Language: Large Language Models and Content Moderation (Deepak Kumar et al., 2023)

{{<citation>}}

Deepak Kumar, Yousef AbuHashem, Zakir Durumeric. (2023)  
**Watch Your Language: Large Language Models and Content Moderation**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-CL, cs-CR, cs-HC, cs-SI, cs.HC  
Keywords: GPT, GPT-3.5, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14517v1)  

---


**ABSTRACT**  
Large language models (LLMs) have exploded in popularity due to their ability to perform a wide array of natural language tasks. Text-based content moderation is one LLM use case that has received recent enthusiasm, however, there is little research investigating how LLMs perform in content moderation settings. In this work, we evaluate a suite of modern, commercial LLMs (GPT-3, GPT-3.5, GPT-4) on two common content moderation tasks: rule-based community moderation and toxic content detection. For rule-based community moderation, we construct 95 LLM moderation-engines prompted with rules from 95 Reddit subcommunities and find that LLMs can be effective at rule-based moderation for many communities, achieving a median accuracy of 64% and a median precision of 83%. For toxicity detection, we find that LLMs significantly outperform existing commercially available toxicity classifiers. However, we also find that recent increases in model size add only marginal benefit to toxicity detection, suggesting a potential performance plateau for LLMs on toxicity detection tasks. We conclude by outlining avenues for future work in studying LLMs and content moderation.

{{</citation>}}


### (55/125) People's Perceptions Toward Bias and Related Concepts in Large Language Models: A Systematic Review (Lu Wang et al., 2023)

{{<citation>}}

Lu Wang, Max Song, Rezvaneh Rezapour, Bum Chul Kwon, Jina Huh-Yoo. (2023)  
**People's Perceptions Toward Bias and Related Concepts in Large Language Models: A Systematic Review**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: Bias, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14504v1)  

---


**ABSTRACT**  
Large language models (LLMs) have brought breakthroughs in tasks including translation, summarization, information retrieval, and language generation, gaining growing interest in the CHI community. Meanwhile, the literature shows researchers' controversial perceptions about the efficacy, ethics, and intellectual abilities of LLMs. However, we do not know how lay people perceive LLMs that are pervasive in everyday tools, specifically regarding their experience with LLMs around bias, stereotypes, social norms, or safety. In this study, we conducted a systematic review to understand what empirical insights papers have gathered about people's perceptions toward LLMs. From a total of 231 retrieved papers, we full-text reviewed 15 papers that recruited human evaluators to assess their experiences with LLMs. We report different biases and related concepts investigated by these studies, four broader LLM application areas, the evaluators' perceptions toward LLMs' performances including advantages, biases, and conflicting perceptions, factors influencing these perceptions, and concerns about LLM applications.

{{</citation>}}


### (56/125) More than Model Documentation: Uncovering Teachers' Bespoke Information Needs for Informed Classroom Integration of ChatGPT (Mei Tan et al., 2023)

{{<citation>}}

Mei Tan, Hariharan Subramonyam. (2023)  
**More than Model Documentation: Uncovering Teachers' Bespoke Information Needs for Informed Classroom Integration of ChatGPT**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2309.14458v1)  

---


**ABSTRACT**  
ChatGPT has entered classrooms, but not via the typical route of other educational technology, which includes comprehensive training, documentation, and vetting. Consequently, teachers are urgently tasked to assess its capabilities to determine potential effects on student learning and instruct their use of ChatGPT. However, it is unclear what support teachers have and need and whether existing documentation, such as model cards, provides adequate direction for educators in this new paradigm. By interviewing 22 middle- and high-school teachers, we connect the discourse on AI transparency and documentation with educational technology integration, highlighting the critical information needs of teachers. Our findings reveal that teachers confront significant information gaps, lacking clarity on exploring ChatGPT's capabilities for bespoke learning tasks and ensuring its fit with the needs of diverse learners. As a solution, we propose a framework for interactive model documentation that empowers teachers to navigate the interplay between pedagogical and technical knowledge.

{{</citation>}}


### (57/125) Innovative Digital Storytelling with AIGC: Exploration and Discussion of Recent Advances (Rongzhang Gu et al., 2023)

{{<citation>}}

Rongzhang Gu, Hui Li, Changyue Su, Wayne Wu. (2023)  
**Innovative Digital Storytelling with AIGC: Exploration and Discussion of Recent Advances**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-CV, cs-GR, cs-HC, cs-MM, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14329v2)  

---


**ABSTRACT**  
Digital storytelling, as an art form, has struggled with cost-quality balance. The emergence of AI-generated Content (AIGC) is considered as a potential solution for efficient digital storytelling production. However, the specific form, effects, and impacts of this fusion remain unclear, leaving the boundaries of AIGC combined with storytelling undefined. This work explores the current integration state of AIGC and digital storytelling, investigates the artistic value of their fusion in a sample project, and addresses common issues through interviews. Through our study, we conclude that AIGC, while proficient in image creation, voiceover production, and music composition, falls short of replacing humans due to the irreplaceable elements of human creativity and aesthetic sensibilities at present, especially in complex character animations, facial expressions, and sound effects. The research objective is to increase public awareness of the current state, limitations, and challenges arising from combining AIGC and digital storytelling.

{{</citation>}}


### (58/125) ID.8: Co-Creating Visual Stories with Generative AI (Victor Nikhil Antony et al., 2023)

{{<citation>}}

Victor Nikhil Antony, Chien-Ming Huang. (2023)  
**ID.8: Co-Creating Visual Stories with Generative AI**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2309.14228v1)  

---


**ABSTRACT**  
Storytelling is an integral part of human culture and significantly impacts cognitive and socio-emotional development and connection. Despite the importance of interactive visual storytelling, the process of creating such content requires specialized skills and is labor-intensive. This paper introduces ID.8, an open-source system designed for the co-creation of visual stories with generative AI. We focus on enabling an inclusive storytelling experience by simplifying the content creation process and allowing for customization. Our user evaluation confirms a generally positive user experience in domains such as enjoyment and exploration, while highlighting areas for improvement, particularly in immersiveness, alignment, and partnership between the user and the AI system. Overall, our findings indicate promising possibilities for empowering people to create visual stories with generative AI. This work contributes a novel content authoring system, ID.8, and insights into the challenges and potential of using generative AI for multimedia content creation.

{{</citation>}}


### (59/125) How Novices Use LLM-Based Code Generators to Solve CS1 Coding Tasks in a Self-Paced Learning Environment (Majeed Kazemitabaar et al., 2023)

{{<citation>}}

Majeed Kazemitabaar, Xinying Hou, Austin Henley, Barbara J. Ericson, David Weintrop, Tovi Grossman. (2023)  
**How Novices Use LLM-Based Code Generators to Solve CS1 Coding Tasks in a Self-Paced Learning Environment**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14049v1)  

---


**ABSTRACT**  
As Large Language Models (LLMs) gain in popularity, it is important to understand how novice programmers use them. We present a thematic analysis of 33 learners, aged 10-17, independently learning Python through 45 code-authoring tasks using Codex, an LLM-based code generator. We explore several questions related to how learners used these code generators and provide an analysis of the properties of the written prompts and the generated code. Specifically, we explore (A) the context in which learners use Codex, (B) what learners are asking from Codex, (C) properties of their prompts in terms of relation to task description, language, and clarity, and prompt crafting patterns, (D) the correctness, complexity, and accuracy of the AI-generated code, and (E) how learners utilize AI-generated code in terms of placement, verification, and manual modifications. Furthermore, our analysis reveals four distinct coding approaches when writing code with an AI code generator: AI Single Prompt, where learners prompted Codex once to generate the entire solution to a task; AI Step-by-Step, where learners divided the problem into parts and used Codex to generate each part; Hybrid, where learners wrote some of the code themselves and used Codex to generate others; and Manual coding, where learners wrote the code themselves. The AI Single Prompt approach resulted in the highest correctness scores on code-authoring tasks, but the lowest correctness scores on subsequent code-modification tasks during training. Our results provide initial insight into how novice learners use AI code generators and the challenges and opportunities associated with integrating them into self-paced learning environments. We conclude with various signs of over-reliance and self-regulation, as well as opportunities for curriculum and tool development.

{{</citation>}}


### (60/125) DeWave: Discrete EEG Waves Encoding for Brain Dynamics to Text Translation (Yiqun Duan et al., 2023)

{{<citation>}}

Yiqun Duan, Jinzhao Zhou, Zhen Wang, Yu-Kai Wang, Chin-Teng Lin. (2023)  
**DeWave: Discrete EEG Waves Encoding for Brain Dynamics to Text Translation**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: BLEU, ChatGPT, GPT, Rouge  
[Paper Link](http://arxiv.org/abs/2309.14030v1)  

---


**ABSTRACT**  
The translation of brain dynamics into natural language is pivotal for brain-computer interfaces (BCIs), a field that has seen substantial growth in recent years. With the swift advancement of large language models, such as ChatGPT, the need to bridge the gap between the brain and languages becomes increasingly pressing. Current methods, however, require eye-tracking fixations or event markers to segment brain dynamics into word-level features, which can restrict the practical application of these systems. These event markers may not be readily available or could be challenging to acquire during real-time inference, and the sequence of eye fixations may not align with the order of spoken words. To tackle these issues, we introduce a novel framework, DeWave, that integrates discrete encoding sequences into open-vocabulary EEG-to-text translation tasks. DeWave uses a quantized variational encoder to derive discrete codex encoding and align it with pre-trained language models. This discrete codex representation brings forth two advantages: 1) it alleviates the order mismatch between eye fixations and spoken words by introducing text-EEG contrastive alignment training, and 2) it minimizes the interference caused by individual differences in EEG waves through an invariant discrete codex. Our model surpasses the previous baseline (40.1 and 31.7) by 3.06% and 6.34%, respectively, achieving 41.35 BLEU-1 and 33.71 Rouge-F on the ZuCo Dataset. Furthermore, this work is the first to facilitate the translation of entire EEG signal periods without needing word-level order markers (e.g., eye fixations), scoring 20.5 BLEU-1 and 29.5 Rouge-1 on the ZuCo Dataset, respectively. Codes and the final paper will be public soon.

{{</citation>}}


### (61/125) A Cyberpunk 2077 perspective on the prediction and understanding of future technology (Miguel Bordallo López et al., 2023)

{{<citation>}}

Miguel Bordallo López, Constantino Álvarez Casado. (2023)  
**A Cyberpunk 2077 perspective on the prediction and understanding of future technology**  

---
Primary Category: cs.HC  
Categories: cs-ET, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.13970v1)  

---


**ABSTRACT**  
Science fiction and video games have long served as valuable tools for envisioning and inspiring future technological advancements. This position paper investigates the potential of Cyberpunk 2077, a popular science fiction video game, to shed light on the future of technology, particularly in the areas of artificial intelligence, edge computing, augmented humans, and biotechnology. By analyzing the game's portrayal of these technologies and their implications, we aim to understand the possibilities and challenges that lie ahead. We discuss key themes such as neurolink and brain-computer interfaces, multimodal recording systems, virtual and simulated reality, digital representation of the physical world, augmented and AI-based home appliances, smart clothing, and autonomous vehicles. The paper highlights the importance of designing technologies that can coexist with existing preferences and systems, considering the uneven adoption of new technologies. Through this exploration, we emphasize the potential of science fiction and video games like Cyberpunk 2077 as tools for guiding future technological advancements and shaping public perception of emerging innovations.

{{</citation>}}


### (62/125) May I Ask a Follow-up Question? Understanding the Benefits of Conversations in Neural Network Explainability (Tong Zhang et al., 2023)

{{<citation>}}

Tong Zhang, X. Jessie Yang, Boyang Li. (2023)  
**May I Ask a Follow-up Question? Understanding the Benefits of Conversations in Neural Network Explainability**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.13965v1)  

---


**ABSTRACT**  
Research in explainable AI (XAI) aims to provide insights into the decision-making process of opaque AI models. To date, most XAI methods offer one-off and static explanations, which cannot cater to the diverse backgrounds and understanding levels of users. With this paper, we investigate if free-form conversations can enhance users' comprehension of static explanations, improve acceptance and trust in the explanation methods, and facilitate human-AI collaboration. Participants are presented with static explanations, followed by a conversation with a human expert regarding the explanations. We measure the effect of the conversation on participants' ability to choose, from three machine learning models, the most accurate one based on explanations and their self-reported comprehension, acceptance, and trust. Empirical results show that conversations significantly improve comprehension, acceptance, trust, and collaboration. Our findings highlight the importance of customized model explanations in the format of free-form conversations and provide insights for the future design of conversational explanations.

{{</citation>}}


### (63/125) LLM-Powered Conversational Voice Assistants: Interaction Patterns, Opportunities, Challenges, and Design Guidelines (Amama Mahmood et al., 2023)

{{<citation>}}

Amama Mahmood, Junxiang Wang, Bingsheng Yao, Dakuo Wang, Chien-Ming Huang. (2023)  
**LLM-Powered Conversational Voice Assistants: Interaction Patterns, Opportunities, Challenges, and Design Guidelines**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.13879v1)  

---


**ABSTRACT**  
Conventional Voice Assistants (VAs) rely on traditional language models to discern user intent and respond to their queries, leading to interactions that often lack a broader contextual understanding, an area in which Large Language Models (LLMs) excel. However, current LLMs are largely designed for text-based interactions, thus making it unclear how user interactions will evolve if their modality is changed to voice. In this work, we investigate whether LLMs can enrich VA interactions via an exploratory study with participants (N=20) using a ChatGPT-powered VA for three scenarios (medical self-diagnosis, creative planning, and debate) with varied constraints, stakes, and objectivity. We observe that LLM-powered VA elicits richer interaction patterns that vary across tasks, showing its versatility. Notably, LLMs absorb the majority of VA intent recognition failures. We additionally discuss the potential of harnessing LLMs for more resilient and fluid user-VA interactions and provide design guidelines for tailoring LLMs for voice assistance.

{{</citation>}}


### (64/125) Impact of Human-AI Interaction on User Trust and Reliance in AI-Assisted Qualitative Coding (Jie Gao et al., 2023)

{{<citation>}}

Jie Gao, Junming Cao, ShunYi Yeo, Kenny Tsu Wei Choo, Zheng Zhang, Toby Jia-Jun Li, Shengdong Zhao, Simon Tangi Perrault. (2023)  
**Impact of Human-AI Interaction on User Trust and Reliance in AI-Assisted Qualitative Coding**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.13858v1)  

---


**ABSTRACT**  
While AI shows promise for enhancing the efficiency of qualitative analysis, the unique human-AI interaction resulting from varied coding strategies makes it challenging to develop a trustworthy AI-assisted qualitative coding system (AIQCs) that supports coding tasks effectively. We bridge this gap by exploring the impact of varying coding strategies on user trust and reliance on AI. We conducted a mixed-methods split-plot 3x3 study, involving 30 participants, and a follow-up study with 6 participants, exploring varying text selection and code length in the use of our AIQCs system for qualitative analysis. Our results indicate that qualitative open coding should be conceptualized as a series of distinct subtasks, each with differing levels of complexity, and therefore, should be given tailored design considerations. We further observed a discrepancy between perceived and behavioral measures, and emphasized the potential challenges of under- and over-reliance on AIQCs systems. Additional design implications were also proposed for consideration.

{{</citation>}}


## cs.CY (3)



### (65/125) Risk of AI in Healthcare: A Comprehensive Literature Review and Study Framework (Apoorva Muley et al., 2023)

{{<citation>}}

Apoorva Muley, Prathamesh Muzumdar, George Kurian, Ganga Prasad Basyal. (2023)  
**Risk of AI in Healthcare: A Comprehensive Literature Review and Study Framework**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs.CY, stat-AP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14530v1)  

---


**ABSTRACT**  
This study conducts a thorough examination of the research stream focusing on AI risks in healthcare, aiming to explore the distinct genres within this domain. A selection criterion was employed to carefully analyze 39 articles to identify three primary genres of AI risks prevalent in healthcare: clinical data risks, technical risks, and socio-ethical risks. Selection criteria was based on journal ranking and impact factor. The research seeks to provide a valuable resource for future healthcare researchers, furnishing them with a comprehensive understanding of the complex challenges posed by AI implementation in healthcare settings. By categorizing and elucidating these genres, the study aims to facilitate the development of empirical qualitative and quantitative research, fostering evidence-based approaches to address AI-related risks in healthcare effectively. This endeavor contributes to building a robust knowledge base that can inform the formulation of risk mitigation strategies, ensuring safe and efficient integration of AI technologies in healthcare practices. Thus, it is important to study AI risks in healthcare to build better and efficient AI systems and mitigate risks.

{{</citation>}}


### (66/125) ChatGPT Performance on Standardized Testing Exam -- A Proposed Strategy for Learners (Umer Farooq et al., 2023)

{{<citation>}}

Umer Farooq, Saira Anwar. (2023)  
**ChatGPT Performance on Standardized Testing Exam -- A Proposed Strategy for Learners**  

---
Primary Category: cs.CY  
Categories: cs-CL, cs-CY, cs.CY  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2309.14519v1)  

---


**ABSTRACT**  
This study explores the problem solving capabilities of ChatGPT and its prospective applications in standardized test preparation, focusing on the GRE quantitative exam. Prior research has shown great potential for the utilization of ChatGPT for academic purposes in revolutionizing the approach to studying across various disciplines. We investigate how ChatGPT performs across various question types in the GRE quantitative domain, and how modifying question prompts impacts its accuracy. More specifically this study addressed two research questions: 1. How does ChatGPT perform in answering GRE-based quantitative questions across various content areas? 2. How does the accuracy of ChatGPT vary with modifying the question prompts? The dataset consisting of 100 randomly selected GRE quantitative questions was collected from the ETS official guide to GRE test preparation. We used quantitative evaluation to answer our first research question, and t-test to examine the statistical association between prompt modification and ChatGPT's accuracy. Results show a statistical improvement in the ChatGPT's accuracy after applying instruction priming and contextual prompts to the original questions. ChatGPT showed 84% accuracy with the modified prompts compared to 69% with the original data. The study discusses the areas where ChatGPT struggled with certain questions and how modifications can be helpful for preparing for standardized tests like GRE and provides future directions for prompt modifications.

{{</citation>}}


### (67/125) Fairness and Bias in Algorithmic Hiring (Alessandro Fabris et al., 2023)

{{<citation>}}

Alessandro Fabris, Nina Baranowska, Matthew J. Dennis, Philipp Hacker, Jorge Saldivar, Frederik Zuiderveen Borgesius, Asia J. Biega. (2023)  
**Fairness and Bias in Algorithmic Hiring**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.13933v1)  

---


**ABSTRACT**  
Employers are adopting algorithmic hiring technology throughout the recruitment pipeline. Algorithmic fairness is especially applicable in this domain due to its high stakes and structural inequalities. Unfortunately, most work in this space provides partial treatment, often constrained by two competing narratives, optimistically focused on replacing biased recruiter decisions or pessimistically pointing to the automation of discrimination. Whether, and more importantly what types of, algorithmic hiring can be less biased and more beneficial to society than low-tech alternatives currently remains unanswered, to the detriment of trustworthiness. This multidisciplinary survey caters to practitioners and researchers with a balanced and integrated coverage of systems, biases, measures, mitigation strategies, datasets, and legal aspects of algorithmic hiring and fairness. Our work supports a contextualized understanding and governance of this technology by highlighting current opportunities and limitations, providing recommendations for future work to ensure shared benefits for all stakeholders.

{{</citation>}}


## cs.LG (22)



### (68/125) DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models (Sam Ade Jacobs et al., 2023)

{{<citation>}}

Sam Ade Jacobs, Masahiro Tanaka, Chengming Zhang, Minjia Zhang, Leon Song, Samyam Rajbhandari, Yuxiong He. (2023)  
**DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-DC, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14509v1)  

---


**ABSTRACT**  
Computation in a typical Transformer-based large language model (LLM) can be characterized by batch size, hidden dimension, number of layers, and sequence length. Until now, system works for accelerating LLM training have focused on the first three dimensions: data parallelism for batch size, tensor parallelism for hidden size and pipeline parallelism for model depth or layers. These widely studied forms of parallelism are not targeted or optimized for long sequence Transformer models. Given practical application needs for long sequence LLM, renewed attentions are being drawn to sequence parallelism. However, existing works in sequence parallelism are constrained by memory-communication inefficiency, limiting their scalability to long sequence large models. In this work, we introduce DeepSpeed-Ulysses, a novel, portable and effective methodology for enabling highly efficient and scalable LLM training with extremely long sequence length. DeepSpeed-Ulysses at its core partitions input data along the sequence dimension and employs an efficient all-to-all collective communication for attention computation. Theoretical communication analysis shows that whereas other methods incur communication overhead as sequence length increases, DeepSpeed-Ulysses maintains constant communication volume when sequence length and compute devices are increased proportionally. Furthermore, experimental evaluations show that DeepSpeed-Ulysses trains 2.5X faster with 4X longer sequence length than the existing method SOTA baseline.

{{</citation>}}


### (69/125) Explainable and Accurate Natural Language Understanding for Voice Assistants and Beyond (Kalpa Gunaratna et al., 2023)

{{<citation>}}

Kalpa Gunaratna, Vijay Srinivasan, Hongxia Jin. (2023)  
**Explainable and Accurate Natural Language Understanding for Voice Assistants and Beyond**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: NLU, Natural Language Understanding  
[Paper Link](http://arxiv.org/abs/2309.14485v1)  

---


**ABSTRACT**  
Joint intent detection and slot filling, which is also termed as joint NLU (Natural Language Understanding) is invaluable for smart voice assistants. Recent advancements in this area have been heavily focusing on improving accuracy using various techniques. Explainability is undoubtedly an important aspect for deep learning-based models including joint NLU models. Without explainability, their decisions are opaque to the outside world and hence, have tendency to lack user trust. Therefore to bridge this gap, we transform the full joint NLU model to be `inherently' explainable at granular levels without compromising on accuracy. Further, as we enable the full joint NLU model explainable, we show that our extension can be successfully used in other general classification tasks. We demonstrate this using sentiment analysis and named entity recognition.

{{</citation>}}


### (70/125) LogGPT: Log Anomaly Detection via GPT (Xiao Han et al., 2023)

{{<citation>}}

Xiao Han, Shuhan Yuan, Mohamed Trabelsi. (2023)  
**LogGPT: Log Anomaly Detection via GPT**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Anomaly Detection, GPT, LSTM, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14482v1)  

---


**ABSTRACT**  
Detecting system anomalies based on log data is important for ensuring the security and reliability of computer systems. Recently, deep learning models have been widely used for log anomaly detection. The core idea is to model the log sequences as natural language and adopt deep sequential models, such as LSTM or Transformer, to encode the normal patterns in log sequences via language modeling. However, there is a gap between language modeling and anomaly detection as the objective of training a sequential model via a language modeling loss is not directly related to anomaly detection. To fill up the gap, we propose LogGPT, a novel framework that employs GPT for log anomaly detection. LogGPT is first trained to predict the next log entry based on the preceding sequence. To further enhance the performance of LogGPT, we propose a novel reinforcement learning strategy to finetune the model specifically for the log anomaly detection task. The experimental results on three datasets show that LogGPT significantly outperforms existing state-of-the-art approaches.

{{</citation>}}


### (71/125) Adapting Double Q-Learning for Continuous Reinforcement Learning (Arsenii Kuznetsov, 2023)

{{<citation>}}

Arsenii Kuznetsov. (2023)  
**Adapting Double Q-Learning for Continuous Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14471v1)  

---


**ABSTRACT**  
Majority of off-policy reinforcement learning algorithms use overestimation bias control techniques. Most of these techniques rooted in heuristics, primarily addressing the consequences of overestimation rather than its fundamental origins. In this work we present a novel approach to the bias correction, similar in spirit to Double Q-Learning. We propose using a policy in form of a mixture with two components. Each policy component is maximized and assessed by separate networks, which removes any basis for the overestimation bias. Our approach shows promising near-SOTA results on a small set of MuJoCo environments.

{{</citation>}}


### (72/125) LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference (Hongwu Peng et al., 2023)

{{<citation>}}

Hongwu Peng, Ran Ran, Yukui Luo, Jiahui Zhao, Shaoyi Huang, Kiran Thorat, Tong Geng, Chenghong Wang, Xiaolin Xu, Wujie Wen, Caiwen Ding. (2023)  
**LinGCN: Structural Linearized Graph Convolutional Network for Homomorphically Encrypted Inference**  

---
Primary Category: cs.LG  
Categories: E-3; I-2; B-0, cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2309.14331v1)  

---


**ABSTRACT**  
The growth of Graph Convolution Network (GCN) model sizes has revolutionized numerous applications, surpassing human performance in areas such as personal healthcare and financial systems. The deployment of GCNs in the cloud raises privacy concerns due to potential adversarial attacks on client data. To address security concerns, Privacy-Preserving Machine Learning (PPML) using Homomorphic Encryption (HE) secures sensitive client data. However, it introduces substantial computational overhead in practical applications. To tackle those challenges, we present LinGCN, a framework designed to reduce multiplication depth and optimize the performance of HE based GCN inference. LinGCN is structured around three key elements: (1) A differentiable structural linearization algorithm, complemented by a parameterized discrete indicator function, co-trained with model weights to meet the optimization goal. This strategy promotes fine-grained node-level non-linear location selection, resulting in a model with minimized multiplication depth. (2) A compact node-wise polynomial replacement policy with a second-order trainable activation function, steered towards superior convergence by a two-level distillation approach from an all-ReLU based teacher model. (3) an enhanced HE solution that enables finer-grained operator fusion for node-wise activation functions, further reducing multiplication level consumption in HE-based inference. Our experiments on the NTU-XVIEW skeleton joint dataset reveal that LinGCN excels in latency, accuracy, and scalability for homomorphically encrypted inference, outperforming solutions such as CryptoGCN. Remarkably, LinGCN achieves a 14.2x latency speedup relative to CryptoGCN, while preserving an inference accuracy of 75% and notably reducing multiplication depth.

{{</citation>}}


### (73/125) Small-scale proxies for large-scale Transformer training instabilities (Mitchell Wortsman et al., 2023)

{{<citation>}}

Mitchell Wortsman, Peter J. Liu, Lechao Xiao, Katie Everett, Alex Alemi, Ben Adlam, John D. Co-Reyes, Izzeddin Gur, Abhishek Kumar, Roman Novak, Jeffrey Pennington, Jascha Sohl-dickstein, Kelvin Xu, Jaehoon Lee, Justin Gilmer, Simon Kornblith. (2023)  
**Small-scale proxies for large-scale Transformer training instabilities**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14322v1)  

---


**ABSTRACT**  
Teams that have trained large Transformer-based models have reported training instabilities at large scale that did not appear when training with the same hyperparameters at smaller scales. Although the causes of such instabilities are of scientific interest, the amount of resources required to reproduce them has made investigation difficult. In this work, we seek ways to reproduce and study training stability and instability at smaller scales. First, we focus on two sources of training instability described in previous work: the growth of logits in attention layers (Dehghani et al., 2023) and divergence of the output logits from the log probabilities (Chowdhery et al., 2022). By measuring the relationship between learning rate and loss across scales, we show that these instabilities also appear in small models when training at high learning rates, and that mitigations previously employed at large scales are equally effective in this regime. This prompts us to investigate the extent to which other known optimizer and model interventions influence the sensitivity of the final loss to changes in the learning rate. To this end, we study methods such as warm-up, weight decay, and the $\mu$Param (Yang et al., 2022), and combine techniques to train small models that achieve similar losses across orders of magnitude of learning rate variation. Finally, to conclude our exploration we study two cases where instabilities can be predicted before they emerge by examining the scaling behavior of model activation and gradient norms.

{{</citation>}}


### (74/125) Implicit Sensing in Traffic Optimization: Advanced Deep Reinforcement Learning Techniques (Emanuel Figetakis et al., 2023)

{{<citation>}}

Emanuel Figetakis, Yahuza Bello, Ahmed Refaey, Lei Lei, Medhat Moussa. (2023)  
**Implicit Sensing in Traffic Optimization: Advanced Deep Reinforcement Learning Techniques**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14395v1)  

---


**ABSTRACT**  
A sudden roadblock on highways due to many reasons such as road maintenance, accidents, and car repair is a common situation we encounter almost daily. Autonomous Vehicles (AVs) equipped with sensors that can acquire vehicle dynamics such as speed, acceleration, and location can make intelligent decisions to change lanes before reaching a roadblock. A number of literature studies have examined car-following models and lane-changing models. However, only a few studies proposed an integrated car-following and lane-changing model, which has the potential to model practical driving maneuvers. Hence, in this paper, we present an integrated car-following and lane-changing decision-control system based on Deep Reinforcement Learning (DRL) to address this issue. Specifically, we consider a scenario where sudden construction work will be carried out along a highway. We model the scenario as a Markov Decision Process (MDP) and employ the well-known DQN algorithm to train the RL agent to make the appropriate decision accordingly (i.e., either stay in the same lane or change lanes). To overcome the delay and computational requirement of DRL algorithms, we adopt an MEC-assisted architecture where the RL agents are trained on MEC servers. We utilize the highly reputable SUMO simulator and OPENAI GYM to evaluate the performance of the proposed model under two policies; {\epsilon}-greedy policy and Boltzmann policy. The results unequivocally demonstrate that the DQN agent trained using the {\epsilon}-greedy policy significantly outperforms the one trained with the Boltzmann policy.

{{</citation>}}


### (75/125) MemDA: Forecasting Urban Time Series with Memory-based Drift Adaptation (Zekun Cai et al., 2023)

{{<citation>}}

Zekun Cai, Renhe Jiang, Xinyu Yang, Zhaonan Wang, Diansheng Guo, Hiroki Kobayashi, Xuan Song, Ryosuke Shibasaki. (2023)  
**MemDA: Forecasting Urban Time Series with Memory-based Drift Adaptation**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2309.14216v1)  

---


**ABSTRACT**  
Urban time series data forecasting featuring significant contributions to sustainable development is widely studied as an essential task of the smart city. However, with the dramatic and rapid changes in the world environment, the assumption that data obey Independent Identically Distribution is undermined by the subsequent changes in data distribution, known as concept drift, leading to weak replicability and transferability of the model over unseen data. To address the issue, previous approaches typically retrain the model, forcing it to fit the most recent observed data. However, retraining is problematic in that it leads to model lag, consumption of resources, and model re-invalidation, causing the drift problem to be not well solved in realistic scenarios. In this study, we propose a new urban time series prediction model for the concept drift problem, which encodes the drift by considering the periodicity in the data and makes on-the-fly adjustments to the model based on the drift using a meta-dynamic network. Experiments on real-world datasets show that our design significantly outperforms state-of-the-art methods and can be well generalized to existing prediction backbones by reducing their sensitivity to distribution changes.

{{</citation>}}


### (76/125) (Predictable) Performance Bias in Unsupervised Anomaly Detection (Felix Meissen et al., 2023)

{{<citation>}}

Felix Meissen, Svenja Breuer, Moritz Knolle, Alena Buyx, Ruth Müller, Georgios Kaissis, Benedikt Wiestler, Daniel Rückert. (2023)  
**(Predictable) Performance Bias in Unsupervised Anomaly Detection**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-CY, cs-LG, cs.LG, eess-IV  
Keywords: Anomaly Detection, Bias, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.14198v1)  

---


**ABSTRACT**  
Background: With the ever-increasing amount of medical imaging data, the demand for algorithms to assist clinicians has amplified. Unsupervised anomaly detection (UAD) models promise to aid in the crucial first step of disease detection. While previous studies have thoroughly explored fairness in supervised models in healthcare, for UAD, this has so far been unexplored.   Methods: In this study, we evaluated how dataset composition regarding subgroups manifests in disparate performance of UAD models along multiple protected variables on three large-scale publicly available chest X-ray datasets. Our experiments were validated using two state-of-the-art UAD models for medical images. Finally, we introduced a novel subgroup-AUROC (sAUROC) metric, which aids in quantifying fairness in machine learning.   Findings: Our experiments revealed empirical "fairness laws" (similar to "scaling laws" for Transformers) for training-dataset composition: Linear relationships between anomaly detection performance within a subpopulation and its representation in the training data. Our study further revealed performance disparities, even in the case of balanced training data, and compound effects that exacerbate the drop in performance for subjects associated with multiple adversely affected groups.   Interpretation: Our study quantified the disparate performance of UAD models against certain demographic subgroups. Importantly, we showed that this unfairness cannot be mitigated by balanced representation alone. Instead, the representation of some subgroups seems harder to learn by UAD models than that of others. The empirical fairness laws discovered in our study make disparate performance in UAD models easier to estimate and aid in determining the most desirable dataset composition.

{{</citation>}}


### (77/125) One-Class Classification for Intrusion Detection on Vehicular Networks (Jake Guidry et al., 2023)

{{<citation>}}

Jake Guidry, Fahad Sohrab, Raju Gottumukkala, Satya Katragadda, Moncef Gabbouj. (2023)  
**One-Class Classification for Intrusion Detection on Vehicular Networks**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: Intrusion Detection  
[Paper Link](http://arxiv.org/abs/2309.14134v1)  

---


**ABSTRACT**  
Controller Area Network bus systems within vehicular networks are not equipped with the tools necessary to ward off and protect themselves from modern cyber-security threats. Work has been done on using machine learning methods to detect and report these attacks, but common methods are not robust towards unknown attacks. These methods usually rely on there being a sufficient representation of attack data, which may not be available due to there either not being enough data present to adequately represent its distribution or the distribution itself is too diverse in nature for there to be a sufficient representation of it. With the use of one-class classification methods, this issue can be mitigated as only normal data is required to train a model for the detection of anomalous instances. Research has been done on the efficacy of these methods, most notably One-Class Support Vector Machine and Support Vector Data Description, but many new extensions of these works have been proposed and have yet to be tested for injection attacks in vehicular networks. In this paper, we investigate the performance of various state-of-the-art one-class classification methods for detecting injection attacks on Controller Area Network bus traffic. We investigate the effectiveness of these techniques on attacks launched on Controller Area Network buses from two different vehicles during normal operation and while being attacked. We observe that the Subspace Support Vector Data Description method outperformed all other tested methods with a Gmean of about 85%.

{{</citation>}}


### (78/125) Tracking Control for a Spherical Pendulum via Curriculum Reinforcement Learning (Pascal Klink et al., 2023)

{{<citation>}}

Pascal Klink, Florian Wolf, Kai Ploeger, Jan Peters, Joni Pajarinen. (2023)  
**Tracking Control for a Spherical Pendulum via Curriculum Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-RO, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14096v1)  

---


**ABSTRACT**  
Reinforcement Learning (RL) allows learning non-trivial robot control laws purely from data. However, many successful applications of RL have relied on ad-hoc regularizations, such as hand-crafted curricula, to regularize the learning performance. In this paper, we pair a recent algorithm for automatically building curricula with RL on massively parallelized simulations to learn a tracking controller for a spherical pendulum on a robotic arm via RL. Through an improved optimization scheme that better respects the non-Euclidean task structure, we allow the method to reliably generate curricula of trajectories to be tracked, resulting in faster and more robust learning compared to an RL baseline that does not exploit this form of structured learning. The learned policy matches the performance of an optimal control baseline on the real system, demonstrating the potential of curriculum RL to jointly learn state estimation and control for non-linear tracking tasks.

{{</citation>}}


### (79/125) On the Benefit of Optimal Transport for Curriculum Reinforcement Learning (Pascal Klink et al., 2023)

{{<citation>}}

Pascal Klink, Carlo D'Eramo, Jan Peters, Joni Pajarinen. (2023)  
**On the Benefit of Optimal Transport for Curriculum Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14091v1)  

---


**ABSTRACT**  
Curriculum reinforcement learning (CRL) allows solving complex tasks by generating a tailored sequence of learning tasks, starting from easy ones and subsequently increasing their difficulty. Although the potential of curricula in RL has been clearly shown in various works, it is less clear how to generate them for a given learning environment, resulting in various methods aiming to automate this task. In this work, we focus on framing curricula as interpolations between task distributions, which has previously been shown to be a viable approach to CRL. Identifying key issues of existing methods, we frame the generation of a curriculum as a constrained optimal transport problem between task distributions. Benchmarks show that this way of curriculum generation can improve upon existing CRL methods, yielding high performance in various tasks with different characteristics.

{{</citation>}}


### (80/125) ODE-based Recurrent Model-free Reinforcement Learning for POMDPs (Xuanle Zhao et al., 2023)

{{<citation>}}

Xuanle Zhao, Duzhen Zhang, Liyuan Han, Tielin Zhang, Bo Xu. (2023)  
**ODE-based Recurrent Model-free Reinforcement Learning for POMDPs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14078v1)  

---


**ABSTRACT**  
Neural ordinary differential equations (ODEs) are widely recognized as the standard for modeling physical mechanisms, which help to perform approximate inference in unknown physical or biological environments. In partially observable (PO) environments, how to infer unseen information from raw observations puzzled the agents. By using a recurrent policy with a compact context, context-based reinforcement learning provides a flexible way to extract unobservable information from historical transitions. To help the agent extract more dynamics-related information, we present a novel ODE-based recurrent model combines with model-free reinforcement learning (RL) framework to solve partially observable Markov decision processes (POMDPs). We experimentally demonstrate the efficacy of our methods across various PO continuous control and meta-RL tasks. Furthermore, our experiments illustrate that our method is robust against irregular observations, owing to the ability of ODEs to model irregularly-sampled time series.

{{</citation>}}


### (81/125) Revisiting LARS for Large Batch Training Generalization of Neural Networks (Khoi Do et al., 2023)

{{<citation>}}

Khoi Do, Duong Nguyen, Hoa Nguyen, Long Tran-Thanh, Quoc-Viet Pham. (2023)  
**Revisiting LARS for Large Batch Training Generalization of Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14053v1)  

---


**ABSTRACT**  
LARS and LAMB have emerged as prominent techniques in Large Batch Learning (LBL), ensuring the stability of AI training. One of the primary challenges in LBL is convergence stability, where the AI agent usually gets trapped into the sharp minimizer. Addressing this challenge, a relatively recent technique, known as warm-up, has been employed. However, warm-up lacks a strong theoretical foundation, leaving the door open for further exploration of more efficacious algorithms. In light of this situation, we conduct empirical experiments to analyze the behaviors of the two most popular optimizers in the LARS family: LARS and LAMB, with and without a warm-up strategy. Our analyses give us a comprehension of the novel LARS, LAMB, and the necessity of a warm-up technique in LBL. Building upon these insights, we propose a novel algorithm called Time Varying LARS (TVLARS), which facilitates robust training in the initial phase without the need for warm-up. Experimental evaluation demonstrates that TVLARS achieves competitive results with LARS and LAMB when warm-up is utilized while surpassing their performance without the warm-up technique.

{{</citation>}}


### (82/125) Diffeomorphic Transformations for Time Series Analysis: An Efficient Approach to Nonlinear Warping (Iñigo Martinez, 2023)

{{<citation>}}

Iñigo Martinez. (2023)  
**Diffeomorphic Transformations for Time Series Analysis: An Efficient Approach to Nonlinear Warping**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2309.14029v1)  

---


**ABSTRACT**  
The proliferation and ubiquity of temporal data across many disciplines has sparked interest for similarity, classification and clustering methods specifically designed to handle time series data. A core issue when dealing with time series is determining their pairwise similarity, i.e., the degree to which a given time series resembles another. Traditional distance measures such as the Euclidean are not well-suited due to the time-dependent nature of the data. Elastic metrics such as dynamic time warping (DTW) offer a promising approach, but are limited by their computational complexity, non-differentiability and sensitivity to noise and outliers. This thesis proposes novel elastic alignment methods that use parametric \& diffeomorphic warping transformations as a means of overcoming the shortcomings of DTW-based metrics. The proposed method is differentiable \& invertible, well-suited for deep learning architectures, robust to noise and outliers, computationally efficient, and is expressive and flexible enough to capture complex patterns. Furthermore, a closed-form solution was developed for the gradient of these diffeomorphic transformations, which allows an efficient search in the parameter space, leading to better solutions at convergence. Leveraging the benefits of these closed-form diffeomorphic transformations, this thesis proposes a suite of advancements that include: (a) an enhanced temporal transformer network for time series alignment and averaging, (b) a deep-learning based time series classification model to simultaneously align and classify signals with high accuracy, (c) an incremental time series clustering algorithm that is warping-invariant, scalable and can operate under limited computational and time resources, and finally, (d) a normalizing flow model that enhances the flexibility of affine transformations in coupling and autoregressive layers.

{{</citation>}}


### (83/125) An AI Chatbot for Explaining Deep Reinforcement Learning Decisions of Service-oriented Systems (Andreas Metzger et al., 2023)

{{<citation>}}

Andreas Metzger, Jone Bartel, Jan Laufer. (2023)  
**An AI Chatbot for Explaining Deep Reinforcement Learning Decisions of Service-oriented Systems**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: AI, ChatGPT, GPT, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14391v1)  

---


**ABSTRACT**  
Deep Reinforcement Learning (Deep RL) is increasingly used to cope with the open-world assumption in service-oriented systems. Deep RL was successfully applied to problems such as dynamic service composition, job scheduling, and offloading, as well as service adaptation. While Deep RL offers many benefits, understanding the decision-making of Deep RL is challenging because its learned decision-making policy essentially appears as a black box. Yet, understanding the decision-making of Deep RL is key to help service developers perform debugging, support service providers to comply with relevant legal frameworks, and facilitate service users to build trust. We introduce Chat4XAI to facilitate the understanding of the decision-making of Deep RL by providing natural-language explanations. Compared with visual explanations, the reported benefits of natural-language explanations include better understandability for non-technical users, increased user acceptance and trust, as well as more efficient explanations. Chat4XAI leverages modern AI chatbot technology and dedicated prompt engineering. Compared to earlier work on natural-language explanations using classical software-based dialogue systems, using an AI chatbot eliminates the need for eliciting and defining potential questions and answers up-front. We prototypically realize Chat4XAI using OpenAI's ChatGPT API and evaluate the fidelity and stability of its explanations using an adaptive service exemplar.

{{</citation>}}


### (84/125) Early Churn Prediction from Large Scale User-Product Interaction Time Series (Shamik Bhattacharjee et al., 2023)

{{<citation>}}

Shamik Bhattacharjee, Utkarsh Thukral, Nilesh Patil. (2023)  
**Early Churn Prediction from Large Scale User-Product Interaction Time Series**  

---
Primary Category: cs.LG  
Categories: I-2-1, cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2309.14390v1)  

---


**ABSTRACT**  
User churn, characterized by customers ending their relationship with a business, has profound economic consequences across various Business-to-Customer scenarios. For numerous system-to-user actions, such as promotional discounts and retention campaigns, predicting potential churners stands as a primary objective. In volatile sectors like fantasy sports, unpredictable factors such as international sports events can influence even regular spending habits. Consequently, while transaction history and user-product interaction are valuable in predicting churn, they demand deep domain knowledge and intricate feature engineering. Additionally, feature development for churn prediction systems can be resource-intensive, particularly in production settings serving 200m+ users, where inference pipelines largely focus on feature engineering. This paper conducts an exhaustive study on predicting user churn using historical data. We aim to create a model forecasting customer churn likelihood, facilitating businesses in comprehending attrition trends and formulating effective retention plans. Our approach treats churn prediction as multivariate time series classification, demonstrating that combining user activity and deep neural networks yields remarkable results for churn prediction in complex business-to-customer contexts.

{{</citation>}}


### (85/125) Provable Training for Graph Contrastive Learning (Yue Yu et al., 2023)

{{<citation>}}

Yue Yu, Xiao Wang, Mengmei Zhang, Nian Liu, Chuan Shi. (2023)  
**Provable Training for Graph Contrastive Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2309.13944v1)  

---


**ABSTRACT**  
Graph Contrastive Learning (GCL) has emerged as a popular training approach for learning node embeddings from augmented graphs without labels. Despite the key principle that maximizing the similarity between positive node pairs while minimizing it between negative node pairs is well established, some fundamental problems are still unclear. Considering the complex graph structure, are some nodes consistently well-trained and following this principle even with different graph augmentations? Or are there some nodes more likely to be untrained across graph augmentations and violate the principle? How to distinguish these nodes and further guide the training of GCL? To answer these questions, we first present experimental evidence showing that the training of GCL is indeed imbalanced across all nodes. To address this problem, we propose the metric "node compactness", which is the lower bound of how a node follows the GCL principle related to the range of augmentations. We further derive the form of node compactness theoretically through bound propagation, which can be integrated into binary cross-entropy as a regularization. To this end, we propose the PrOvable Training (POT) for GCL, which regularizes the training of GCL to encode node embeddings that follows the GCL principle better. Through extensive experiments on various benchmarks, POT consistently improves the existing GCL approaches, serving as a friendly plugin.

{{</citation>}}


### (86/125) SAMN: A Sample Attention Memory Network Combining SVM and NN in One Architecture (Qiaoling Yang et al., 2023)

{{<citation>}}

Qiaoling Yang, Linkai Luo, Haoyu Zhang, Hong Peng, Ziyang Chen. (2023)  
**SAMN: A Sample Attention Memory Network Combining SVM and NN in One Architecture**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.13930v1)  

---


**ABSTRACT**  
Support vector machine (SVM) and neural networks (NN) have strong complementarity. SVM focuses on the inner operation among samples while NN focuses on the operation among the features within samples. Thus, it is promising and attractive to combine SVM and NN, as it may provide a more powerful function than SVM or NN alone. However, current work on combining them lacks true integration. To address this, we propose a sample attention memory network (SAMN) that effectively combines SVM and NN by incorporating sample attention module, class prototypes, and memory block to NN. SVM can be viewed as a sample attention machine. It allows us to add a sample attention module to NN to implement the main function of SVM. Class prototypes are representatives of all classes, which can be viewed as alternatives to support vectors. The memory block is used for the storage and update of class prototypes. Class prototypes and memory block effectively reduce the computational cost of sample attention and make SAMN suitable for multi-classification tasks. Extensive experiments show that SAMN achieves better classification performance than single SVM or single NN with similar parameter sizes, as well as the previous best model for combining SVM and NN. The sample attention mechanism is a flexible module that can be easily deepened and incorporated into neural networks that require it.

{{</citation>}}


### (87/125) TouchUp-G: Improving Feature Representation through Graph-Centric Finetuning (Jing Zhu et al., 2023)

{{<citation>}}

Jing Zhu, Xiang Song, Vassilis N. Ioannidis, Danai Koutra, Christos Faloutsos. (2023)  
**TouchUp-G: Improving Feature Representation through Graph-Centric Finetuning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs-SI, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.13885v1)  

---


**ABSTRACT**  
How can we enhance the node features acquired from Pretrained Models (PMs) to better suit downstream graph learning tasks? Graph Neural Networks (GNNs) have become the state-of-the-art approach for many high-impact, real-world graph applications. For feature-rich graphs, a prevalent practice involves utilizing a PM directly to generate features, without incorporating any domain adaptation techniques. Nevertheless, this practice is suboptimal because the node features extracted from PM are graph-agnostic and prevent GNNs from fully utilizing the potential correlations between the graph structure and node features, leading to a decline in GNNs performance. In this work, we seek to improve the node features obtained from a PM for downstream graph tasks and introduce TOUCHUP-G, which has several advantages. It is (a) General: applicable to any downstream graph task, including link prediction which is often employed in recommender systems; (b) Multi-modal: able to improve raw features of any modality (e.g. images, texts, audio); (c) Principled: it is closely related to a novel metric, feature homophily, which we propose to quantify the potential correlations between the graph structure and node features and we show that TOUCHUP-G can effectively shrink the discrepancy between the graph structure and node features; (d) Effective: achieving state-of-the-art results on four real-world datasets spanning different tasks and modalities.

{{</citation>}}


### (88/125) Backorder Prediction in Inventory Management: Classification Techniques and Cost Considerations (Sarit Maitra et al., 2023)

{{<citation>}}

Sarit Maitra, Sukanya Kundu. (2023)  
**Backorder Prediction in Inventory Management: Classification Techniques and Cost Considerations**  

---
Primary Category: cs.LG  
Categories: cs-IT, cs-LG, cs.LG, math-IT  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.13837v1)  

---


**ABSTRACT**  
This article introduces an advanced analytical approach for predicting backorders in inventory management. Backorder refers to an order that cannot be immediately fulfilled due to stock depletion. Multiple classification techniques, including Balanced Bagging Classifiers, Fuzzy Logic, Variational Autoencoder - Generative Adversarial Networks, and Multi-layer Perceptron classifiers, are assessed in this work using performance evaluation metrics such as ROC-AUC and PR-AUC. Moreover, this work incorporates a profit function and misclassification costs, considering the financial implications and costs associated with inventory management and backorder handling. The results demonstrate the effectiveness of the predictive model in enhancing inventory system service levels, which leads to customer satisfaction and overall organizational performance. Considering interpretability is a significant aspect of using AI in commercial applications, permutation importance is applied to the selected model to determine the importance of features. This research contributes to the advancement of predictive analytics and offers valuable insights for future investigations in backorder forecasting and inventory control optimization for decision-making.

{{</citation>}}


### (89/125) Sampling - Variational Auto Encoder - Ensemble: In the Quest of Explainable Artificial Intelligence (Sarit Maitra et al., 2023)

{{<citation>}}

Sarit Maitra, Vivek Mishra, Pratima Verma, Manav Chopra, Priyanka Nath. (2023)  
**Sampling - Variational Auto Encoder - Ensemble: In the Quest of Explainable Artificial Intelligence**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI, Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2309.14385v1)  

---


**ABSTRACT**  
Explainable Artificial Intelligence (XAI) models have recently attracted a great deal of interest from a variety of application sectors. Despite significant developments in this area, there are still no standardized methods or approaches for understanding AI model outputs. A systematic and cohesive framework is also increasingly necessary to incorporate new techniques like discriminative and generative models to close the gap. This paper contributes to the discourse on XAI by presenting an empirical evaluation based on a novel framework: Sampling - Variational Auto Encoder (VAE) - Ensemble Anomaly Detection (SVEAD). It is a hybrid architecture where VAE combined with ensemble stacking and SHapley Additive exPlanations are used for imbalanced classification. The finding reveals that combining ensemble stacking, VAE, and SHAP can. not only lead to better model performance but also provide an easily explainable framework. This work has used SHAP combined with Permutation Importance and Individual Conditional Expectations to create a powerful interpretability of the model. The finding has an important implication in the real world, where the need for XAI is paramount to boost confidence in AI applications.

{{</citation>}}


## eess.IV (4)



### (90/125) AiAReSeg: Catheter Detection and Segmentation in Interventional Ultrasound using Transformers (Alex Ranne et al., 2023)

{{<citation>}}

Alex Ranne, Yordanka Velikova, Nassir Navab, Ferdinando Rodriguez y Baena. (2023)  
**AiAReSeg: Catheter Detection and Segmentation in Interventional Ultrasound using Transformers**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-RO, eess-IV, eess.IV  
Keywords: Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.14492v1)  

---


**ABSTRACT**  
To date, endovascular surgeries are performed using the golden standard of Fluoroscopy, which uses ionising radiation to visualise catheters and vasculature. Prolonged Fluoroscopic exposure is harmful for the patient and the clinician, and may lead to severe post-operative sequlae such as the development of cancer. Meanwhile, the use of interventional Ultrasound has gained popularity, due to its well-known benefits of small spatial footprint, fast data acquisition, and higher tissue contrast images. However, ultrasound images are hard to interpret, and it is difficult to localise vessels, catheters, and guidewires within them. This work proposes a solution using an adaptation of a state-of-the-art machine learning transformer architecture to detect and segment catheters in axial interventional Ultrasound image sequences. The network architecture was inspired by the Attention in Attention mechanism, temporal tracking networks, and introduced a novel 3D segmentation head that performs 3D deconvolution across time. In order to facilitate training of such deep learning networks, we introduce a new data synthesis pipeline that used physics-based catheter insertion simulations, along with a convolutional ray-casting ultrasound simulator to produce synthetic ultrasound images of endovascular interventions. The proposed method is validated on a hold-out validation dataset, thus demonstrated robustness to ultrasound noise and a wide range of scanning angles. It was also tested on data collected from silicon-based aorta phantoms, thus demonstrated its potential for translation from sim-to-real. This work represents a significant step towards safer and more efficient endovascular surgery using interventional ultrasound.

{{</citation>}}


### (91/125) Gastro-Intestinal Tract Segmentation Using an Explainable 3D Unet (Kai Li et al., 2023)

{{<citation>}}

Kai Li, Jonathan Chan. (2023)  
**Gastro-Intestinal Tract Segmentation Using an Explainable 3D Unet**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14474v1)  

---


**ABSTRACT**  
In treating gastrointestinal cancer using radiotherapy, the role of the radiation oncologist is to administer high doses of radiation, through x-ray beams, toward the tumor while avoiding the stomach and intestines. With the advent of precise radiation treatment technology such as the MR-Linac, oncologists can visualize the daily positions of the tumors and intestines, which may vary day to day. Before delivering radiation, radio oncologists must manually outline the position of the gastrointestinal organs in order to determine position and direction of the x-ray beam. This is a time consuming and labor intensive process that may substantially prolong a patient's treatment. A deep learning (DL) method can automate and expedite the process. However, many deep neural networks approaches currently in use are black-boxes which lack interpretability which render them untrustworthy and impractical in a healthcare setting. To address this, an emergent field of AI known as Explainable AI (XAI) may be incorporated to improve the transparency and viability of a model. This paper proposes a deep learning pipeline that incorporates XAI to address the challenges of organ segmentation.

{{</citation>}}


### (92/125) Unveiling Fairness Biases in Deep Learning-Based Brain MRI Reconstruction (Yuning Du et al., 2023)

{{<citation>}}

Yuning Du, Yuyang Xue, Rohan Dharmakumar, Sotirios A. Tsaftaris. (2023)  
**Unveiling Fairness Biases in Deep Learning-Based Brain MRI Reconstruction**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: AI, Bias  
[Paper Link](http://arxiv.org/abs/2309.14392v1)  

---


**ABSTRACT**  
Deep learning (DL) reconstruction particularly of MRI has led to improvements in image fidelity and reduction of acquisition time. In neuroimaging, DL methods can reconstruct high-quality images from undersampled data. However, it is essential to consider fairness in DL algorithms, particularly in terms of demographic characteristics. This study presents the first fairness analysis in a DL-based brain MRI reconstruction model. The model utilises the U-Net architecture for image reconstruction and explores the presence and sources of unfairness by implementing baseline Empirical Risk Minimisation (ERM) and rebalancing strategies. Model performance is evaluated using image reconstruction metrics. Our findings reveal statistically significant performance biases between the gender and age subgroups. Surprisingly, data imbalance and training discrimination are not the main sources of bias. This analysis provides insights of fairness in DL-based image reconstruction and aims to improve equity in medical AI applications.

{{</citation>}}


### (93/125) Attention and Pooling based Sigmoid Colon Segmentation in 3D CT images (Md Akizur Rahman et al., 2023)

{{<citation>}}

Md Akizur Rahman, Sonit Singh, Kuruparan Shanmugalingam, Sankaran Iyer, Alan Blair, Praveen Ravindran, Arcot Sowmya. (2023)  
**Attention and Pooling based Sigmoid Colon Segmentation in 3D CT images**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.13872v1)  

---


**ABSTRACT**  
Segmentation of the sigmoid colon is a crucial aspect of treating diverticulitis. It enables accurate identification and localisation of inflammation, which in turn helps healthcare professionals make informed decisions about the most appropriate treatment options. This research presents a novel deep learning architecture for segmenting the sigmoid colon from Computed Tomography (CT) images using a modified 3D U-Net architecture. Several variations of the 3D U-Net model with modified hyper-parameters were examined in this study. Pyramid pooling (PyP) and channel-spatial Squeeze and Excitation (csSE) were also used to improve the model performance. The networks were trained using manually annotated sigmoid colon. A five-fold cross-validation procedure was used on a test dataset to evaluate the network's performance. As indicated by the maximum Dice similarity coefficient (DSC) of 56.92+/-1.42%, the application of PyP and csSE techniques improves segmentation precision. We explored ensemble methods including averaging, weighted averaging, majority voting, and max ensemble. The results show that average and majority voting approaches with a threshold value of 0.5 and consistent weight distribution among the top three models produced comparable and optimal results with DSC of 88.11+/-3.52%. The results indicate that the application of a modified 3D U-Net architecture is effective for segmenting the sigmoid colon in Computed Tomography (CT) images. In addition, the study highlights the potential benefits of integrating ensemble methods to improve segmentation precision.

{{</citation>}}


## eess.AS (5)



### (94/125) On the Impact of Quantization and Pruning of Self-Supervised Speech Models for Downstream Speech Recognition Tasks 'In-the-Wild'' (Arthur Pimentel et al., 2023)

{{<citation>}}

Arthur Pimentel, Heitor Guimarães, Anderson R. Avila, Mehdi Rezagholizadeh, Tiago H. Falk. (2023)  
**On the Impact of Quantization and Pruning of Self-Supervised Speech Models for Downstream Speech Recognition Tasks 'In-the-Wild''**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Pruning, Quantization, Self-Supervised, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.14462v1)  

---


**ABSTRACT**  
Recent advances with self-supervised learning have allowed speech recognition systems to achieve state-of-the-art (SOTA) word error rates (WER) while requiring only a fraction of the labeled training data needed by its predecessors. Notwithstanding, while such models achieve SOTA performance in matched train/test conditions, their performance degrades substantially when tested in unseen conditions. To overcome this problem, strategies such as data augmentation and/or domain shift training have been explored. Available models, however, are still too large to be considered for edge speech applications on resource-constrained devices, thus model compression tools are needed. In this paper, we explore the effects that train/test mismatch conditions have on speech recognition accuracy based on compressed self-supervised speech models. In particular, we report on the effects that parameter quantization and model pruning have on speech recognition accuracy based on the so-called robust wav2vec 2.0 model under noisy, reverberant, and noise-plus-reverberation conditions.

{{</citation>}}


### (95/125) Online Active Learning For Sound Event Detection (Mark Lindsey et al., 2023)

{{<citation>}}

Mark Lindsey, Ankit Shah, Francis Kubala, Richard M. Stern. (2023)  
**Online Active Learning For Sound Event Detection**  

---
Primary Category: eess.AS  
Categories: cs-AI, cs-CL, cs-SD, eess-AS, eess-SP, eess.AS  
Keywords: Active Learning, Event Detection  
[Paper Link](http://arxiv.org/abs/2309.14460v1)  

---


**ABSTRACT**  
Data collection and annotation is a laborious, time-consuming prerequisite for supervised machine learning tasks. Online Active Learning (OAL) is a paradigm that addresses this issue by simultaneously minimizing the amount of annotation required to train a classifier and adapting to changes in the data over the duration of the data collection process. Prior work has indicated that fluctuating class distributions and data drift are still common problems for OAL. This work presents new loss functions that address these challenges when OAL is applied to Sound Event Detection (SED). Experimental results from the SONYC dataset and two Voice-Type Discrimination (VTD) corpora indicate that OAL can reduce the time and effort required to train SED classifiers by a factor of 5 for SONYC, and that the new methods presented here successfully resolve issues present in existing OAL methods.

{{</citation>}}


### (96/125) Haha-Pod: An Attempt for Laughter-based Non-Verbal Speaker Verification (Yuke Lin et al., 2023)

{{<citation>}}

Yuke Lin, Xiaoyi Qin, Ning Jiang, Guoqing Zhao, Ming Li. (2023)  
**Haha-Pod: An Attempt for Laughter-based Non-Verbal Speaker Verification**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Speaker Verification  
[Paper Link](http://arxiv.org/abs/2309.14109v1)  

---


**ABSTRACT**  
It is widely acknowledged that discriminative representation for speaker verification can be extracted from verbal speech. However, how much speaker information that non-verbal vocalization carries is still a puzzle. This paper explores speaker verification based on the most ubiquitous form of non-verbal voice, laughter. First, we use a semi-automatic pipeline to collect a new Haha-Pod dataset from open-source podcast media. The dataset contains over 240 speakers' laughter clips with corresponding high-quality verbal speech. Second, we propose a Two-Stage Teacher-Student (2S-TS) framework to minimize the within-speaker embedding distance between verbal and non-verbal (laughter) signals. Considering Haha-Pod as a test set, two trials (S2L-Eval) are designed to verify the speaker's identity through laugh sounds. Experimental results demonstrate that our method can significantly improve the performance of the S2L-Eval test set with only a minor degradation on the VoxCeleb1 test set. The Haha-Pod dataset is open to access on https://drive.google.com/file/d/1J-HBRTsm_yWrcbkXupy-tiWRt5gE2LzG/view?usp=drive_link.

{{</citation>}}


### (97/125) Unsupervised Accent Adaptation Through Masked Language Model Correction Of Discrete Self-Supervised Speech Units (Jakob Poncelet et al., 2023)

{{<citation>}}

Jakob Poncelet, Hugo Van hamme. (2023)  
**Unsupervised Accent Adaptation Through Masked Language Model Correction Of Discrete Self-Supervised Speech Units**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: BERT, Language Model, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.13994v1)  

---


**ABSTRACT**  
Self-supervised pre-trained speech models have strongly improved speech recognition, yet they are still sensitive to domain shifts and accented or atypical speech. Many of these models rely on quantisation or clustering to learn discrete acoustic units. We propose to correct the discovered discrete units for accented speech back to a standard pronunciation in an unsupervised manner. A masked language model is trained on discrete units from a standard accent and iteratively corrects an accented token sequence by masking unexpected cluster sequences and predicting their common variant. Small accent adapter blocks are inserted in the pre-trained model and fine-tuned by predicting the corrected clusters, which leads to an increased robustness of the pre-trained model towards a target accent, and this without supervision. We are able to improve a state-of-the-art HuBERT Large model on a downstream accented speech recognition task by altering the training regime with the proposed method.

{{</citation>}}


### (98/125) Connecting Speech Encoder and Large Language Model for ASR (Wenyi Yu et al., 2023)

{{<citation>}}

Wenyi Yu, Changli Tang, Guangzhi Sun, Xianzhao Chen, Tian Tan, Wei Li, Lu Lu, Zejun Ma, Chao Zhang. (2023)  
**Connecting Speech Encoder and Large Language Model for ASR**  

---
Primary Category: eess.AS  
Categories: cs-CL, cs-SD, eess-AS, eess.AS  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.13963v2)  

---


**ABSTRACT**  
The impressive capability and versatility of large language models (LLMs) have aroused increasing attention in automatic speech recognition (ASR), with several pioneering studies attempting to build integrated ASR models by connecting a speech encoder with an LLM. This paper presents a comparative study of three commonly used structures as connectors, including fully connected layers, multi-head cross-attention, and Q-Former. Speech encoders from the Whisper model series as well as LLMs from the Vicuna model series with different model sizes were studied. Experiments were performed on the commonly used LibriSpeech, Common Voice, and GigaSpeech datasets, where the LLMs with Q-Formers demonstrated consistent and considerable word error rate (WER) reductions over LLMs with other connector structures. Q-Former-based LLMs can generalise well to out-of-domain datasets, where 12% relative WER reductions over the Whisper baseline ASR model were achieved on the Eval2000 test set without using any in-domain training data from Switchboard. Moreover, a novel segment-level Q-Former is proposed to enable LLMs to recognise speech segments with a duration exceeding the limitation of the encoders, which results in 17% relative WER reductions over other connector structures on 90-second-long speech data.

{{</citation>}}


## cond-mat.mtrl-sci (1)



### (99/125) Learning dislocation dynamics mobility laws from large-scale MD simulations (Nicolas Bertin et al., 2023)

{{<citation>}}

Nicolas Bertin, Vasily V. Bulatov, Fei Zhou. (2023)  
**Learning dislocation dynamics mobility laws from large-scale MD simulations**  

---
Primary Category: cond-mat.mtrl-sci  
Categories: cond-mat-mtrl-sci, cond-mat.mtrl-sci, cs-LG, physics-comp-ph  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2309.14450v1)  

---


**ABSTRACT**  
The computational method of discrete dislocation dynamics (DDD), used as a coarse-grained model of true atomistic dynamics of lattice dislocations, has become of powerful tool to study metal plasticity arising from the collective behavior of dislocations. As a mesoscale approach, motion of dislocations in the DDD model is prescribed via the mobility law; a function which specifies how dislocation lines should respond to the driving force. However, the development of traditional hand-crafted mobility laws can be a cumbersome task and may involve detrimental simplifications. Here we introduce a machine-learning (ML) framework to streamline the development of data-driven mobility laws which are modeled as graph neural networks (GNN) trained on large-scale Molecular Dynamics (MD) simulations of crystal plasticity. We illustrate our approach on BCC tungsten and demonstrate that our GNN mobility implemented in large-scale DDD simulations accurately reproduces the challenging tension/compression asymmetry observed in ground-truth MD simulations while correctly predicting the flow stress at lower straining rate conditions unseen during training, thereby demonstrating the ability of our method to learn relevant dislocation physics. Our DDD+ML approach opens new promising avenues to improve fidelity of the DDD model and to incorporate more complex dislocation motion behaviors in an automated way, providing a faithful proxy for dislocation dynamics several orders of magnitude faster than ground-truth MD simulations.

{{</citation>}}


## cs.SD (5)



### (100/125) Joint Audio and Speech Understanding (Yuan Gong et al., 2023)

{{<citation>}}

Yuan Gong, Alexander H. Liu, Hongyin Luo, Leonid Karlinsky, James Glass. (2023)  
**Joint Audio and Speech Understanding**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: LLaMA  
[Paper Link](http://arxiv.org/abs/2309.14405v1)  

---


**ABSTRACT**  
Humans are surrounded by audio signals that include both speech and non-speech sounds. The recognition and understanding of speech and non-speech audio events, along with a profound comprehension of the relationship between them, constitute fundamental cognitive capabilities. For the first time, we build a machine learning model, called LTU-AS, that has a conceptually similar universal audio perception and advanced reasoning ability. Specifically, by integrating Whisper as a perception module and LLaMA as a reasoning module, LTU-AS can simultaneously recognize and jointly understand spoken text, speech paralinguistics, and non-speech audio events - almost everything perceivable from audio signals.

{{</citation>}}


### (101/125) Multi-Domain Adaptation by Self-Supervised Learning for Speaker Verification (Wan Lin et al., 2023)

{{<citation>}}

Wan Lin, Lantian Li, Dong Wang. (2023)  
**Multi-Domain Adaptation by Self-Supervised Learning for Speaker Verification**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: Self-Supervised, Speaker Verification  
[Paper Link](http://arxiv.org/abs/2309.14149v1)  

---


**ABSTRACT**  
In real-world applications, speaker recognition models often face various domain-mismatch challenges, leading to a significant drop in performance. Although numerous domain adaptation techniques have been developed to address this issue, almost all present methods focus on a simple configuration where the model is trained in one domain and deployed in another. However, real-world environments are often complex and may contain multiple domains, making the methods designed for one-to-one adaptation suboptimal. In our paper, we propose a self-supervised learning method to tackle this multi-domain adaptation problem. Building upon the basic self-supervised adaptation algorithm, we designed three strategies to make it suitable for multi-domain adaptation: an in-domain negative sampling strategy, a MoCo-like memory bank scheme, and a CORAL-like distribution alignment. We conducted experiments using VoxCeleb2 as the source domain dataset and CN-Celeb1 as the target multi-domain dataset. Our results demonstrate that our method clearly outperforms the basic self-supervised adaptation method, which simply treats the data of CN-Celeb1 as a single domain. Importantly, the improvement is consistent in nearly all in-domain tests and cross-domain tests, demonstrating the effectiveness of our proposed method.

{{</citation>}}


### (102/125) On the Relation between Internal Language Model and Sequence Discriminative Training for Neural Transducers (Zijian Yang et al., 2023)

{{<citation>}}

Zijian Yang, Wei Zhou, Ralf Schlüter, Hermann Ney. (2023)  
**On the Relation between Internal Language Model and Sequence Discriminative Training for Neural Transducers**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14130v1)  

---


**ABSTRACT**  
Internal language model (ILM) subtraction has been widely applied to improve the performance of the RNN-Transducer with external language model (LM) fusion for speech recognition. In this work, we show that sequence discriminative training has a strong correlation with ILM subtraction from both theoretical and empirical points of view. Theoretically, we derive that the global optimum of maximum mutual information (MMI) training shares a similar formula as ILM subtraction. Empirically, we show that ILM subtraction and sequence discriminative training achieve similar performance across a wide range of experiments on Librispeech, including both MMI and minimum Bayes risk (MBR) criteria, as well as neural transducers and LMs of both full and limited context. The benefit of ILM subtraction also becomes much smaller after sequence discriminative training. We also provide an in-depth study to show that sequence discriminative training has a minimal effect on the commonly used zero-encoder ILM estimation, but a joint effect on both encoder and prediction + joint network for posterior probability reshaping including both ILM and blank suppression.

{{</citation>}}


### (103/125) Audio classification with Dilated Convolution with Learnable Spacings (Ismail Khalfaoui-Hassani et al., 2023)

{{<citation>}}

Ismail Khalfaoui-Hassani, Timothée Masquelier, Thomas Pellegrini. (2023)  
**Audio classification with Dilated Convolution with Learnable Spacings**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.13972v1)  

---


**ABSTRACT**  
Dilated convolution with learnable spacings (DCLS) is a recent convolution method in which the positions of the kernel elements are learned throughout training by backpropagation. Its interest has recently been demonstrated in computer vision (ImageNet classification and downstream tasks). Here we show that DCLS is also useful for audio tagging using the AudioSet classification benchmark. We took two state-of-the-art convolutional architectures using depthwise separable convolutions (DSC), ConvNeXt and ConvFormer, and a hybrid one using attention in addition, FastViT, and drop-in replaced all the DSC layers by DCLS ones. This significantly improved the mean average precision (mAP) with the three architectures without increasing the number of parameters and with only a low cost on the throughput. The method code is based on PyTorch and is available at https://github.com/K-H-Ismail/DCLS-Audio

{{</citation>}}


### (104/125) HiGNN-TTS: Hierarchical Prosody Modeling with Graph Neural Networks for Expressive Long-form TTS (Dake Guo et al., 2023)

{{<citation>}}

Dake Guo, Xinfa Zhu, Liumeng Xue, Tao Li, Yuanjun Lv, Yuepeng Jiang, Lei Xie. (2023)  
**HiGNN-TTS: Hierarchical Prosody Modeling with Graph Neural Networks for Expressive Long-form TTS**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.13907v1)  

---


**ABSTRACT**  
Recent advances in text-to-speech, particularly those based on Graph Neural Networks (GNNs), have significantly improved the expressiveness of short-form synthetic speech. However, generating human-parity long-form speech with high dynamic prosodic variations is still challenging. To address this problem, we expand the capabilities of GNNs with a hierarchical prosody modeling approach, named HiGNN-TTS. Specifically, we add a virtual global node in the graph to strengthen the interconnection of word nodes and introduce a contextual attention mechanism to broaden the prosody modeling scope of GNNs from intra-sentence to inter-sentence. Additionally, we perform hierarchical supervision from acoustic prosody on each node of the graph to capture the prosodic variations with a high dynamic range. Ablation studies show the effectiveness of HiGNN-TTS in learning hierarchical prosody. Both objective and subjective evaluations demonstrate that HiGNN-TTS significantly improves the naturalness and expressiveness of long-form synthetic speech

{{</citation>}}


## q-bio.QM (1)



### (105/125) pLMFPPred: a novel approach for accurate prediction of functional peptides integrating embedding from pre-trained protein language model and imbalanced learning (Zebin Ma et al., 2023)

{{<citation>}}

Zebin Ma, Yonglin Zou, Xiaobin Huang, Wenjin Yan, Hao Xu, Jiexin Yang, Ying Zhang, Jinqi Huang. (2023)  
**pLMFPPred: a novel approach for accurate prediction of functional peptides integrating embedding from pre-trained protein language model and imbalanced learning**  

---
Primary Category: q-bio.QM  
Categories: cs-LG, q-bio-QM, q-bio.QM  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14404v1)  

---


**ABSTRACT**  
Functional peptides have the potential to treat a variety of diseases. Their good therapeutic efficacy and low toxicity make them ideal therapeutic agents. Artificial intelligence-based computational strategies can help quickly identify new functional peptides from collections of protein sequences and discover their different functions.Using protein language model-based embeddings (ESM-2), we developed a tool called pLMFPPred (Protein Language Model-based Functional Peptide Predictor) for predicting functional peptides and identifying toxic peptides. We also introduced SMOTE-TOMEK data synthesis sampling and Shapley value-based feature selection techniques to relieve data imbalance issues and reduce computational costs. On a validated independent test set, pLMFPPred achieved accuracy, Area under the curve - Receiver Operating Characteristics, and F1-Score values of 0.974, 0.99, and 0.974, respectively. Comparative experiments show that pLMFPPred outperforms current methods for predicting functional peptides.The experimental results suggest that the proposed method (pLMFPPred) can provide better performance in terms of Accuracy, Area under the curve - Receiver Operating Characteristics, and F1-Score than existing methods. pLMFPPred has achieved good performance in predicting functional peptides and represents a new computational method for predicting functional peptides.

{{</citation>}}


## cs.IR (1)



### (106/125) Cluster Language Model for Improved E-Commerce Retrieval and Ranking: Leveraging Query Similarity and Fine-Tuning for Personalized Results (Duleep Rathgamage Don et al., 2023)

{{<citation>}}

Duleep Rathgamage Don, Ying Xie, Le Yu, Simon Hughes, Yun Zhu. (2023)  
**Cluster Language Model for Improved E-Commerce Retrieval and Ranking: Leveraging Query Similarity and Fine-Tuning for Personalized Results**  

---
Primary Category: cs.IR  
Categories: I-2-7, cs-IR, cs.IR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14323v1)  

---


**ABSTRACT**  
This paper proposes a novel method to improve the accuracy of product search in e-commerce by utilizing a cluster language model. The method aims to address the limitations of the bi-encoder architecture while maintaining a minimal additional training burden. The approach involves labeling top products for each query, generating semantically similar query clusters using the K-Means clustering algorithm, and fine-tuning a global language model into cluster language models on individual clusters. The parameters of each cluster language model are fine-tuned to learn local manifolds in the feature space efficiently, capturing the nuances of various query types within each cluster. The inference is performed by assigning a new query to its respective cluster and utilizing the corresponding cluster language model for retrieval. The proposed method results in more accurate and personalized retrieval results, offering a superior alternative to the popular bi-encoder based retrieval models in semantic search.

{{</citation>}}


## cs.RO (8)



### (107/125) Human-Assisted Continual Robot Learning with Foundation Models (Meenal Parakh et al., 2023)

{{<citation>}}

Meenal Parakh, Alisha Fong, Anthony Simeonov, Abhishek Gupta, Tao Chen, Pulkit Agrawal. (2023)  
**Human-Assisted Continual Robot Learning with Foundation Models**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14321v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have been shown to act like planners that can decompose high-level instructions into a sequence of executable instructions. However, current LLM-based planners are only able to operate with a fixed set of skills. We overcome this critical limitation and present a method for using LLM-based planners to query new skills and teach robots these skills in a data and time-efficient manner for rigid object manipulation. Our system can re-use newly acquired skills for future tasks, demonstrating the potential of open world and lifelong learning. We evaluate the proposed framework on multiple tasks in simulation and the real world. Videos are available at: https://sites.google.com/mit.edu/halp-robot-learning.

{{</citation>}}


### (108/125) Learning Risk-Aware Quadrupedal Locomotion using Distributional Reinforcement Learning (Lukas Schneider et al., 2023)

{{<citation>}}

Lukas Schneider, Jonas Frey, Takahiro Miki, Marco Hutter. (2023)  
**Learning Risk-Aware Quadrupedal Locomotion using Distributional Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14246v1)  

---


**ABSTRACT**  
Deployment in hazardous environments requires robots to understand the risks associated with their actions and movements to prevent accidents. Despite its importance, these risks are not explicitly modeled by currently deployed locomotion controllers for legged robots. In this work, we propose a risk sensitive locomotion training method employing distributional reinforcement learning to consider safety explicitly. Instead of relying on a value expectation, we estimate the complete value distribution to account for uncertainty in the robot's interaction with the environment. The value distribution is consumed by a risk metric to extract risk sensitive value estimates. These are integrated into Proximal Policy Optimization (PPO) to derive our method, Distributional Proximal Policy Optimization (DPPO). The risk preference, ranging from risk-averse to risk-seeking, can be controlled by a single parameter, which enables to adjust the robot's behavior dynamically. Importantly, our approach removes the need for additional reward function tuning to achieve risk sensitivity. We show emergent risk sensitive locomotion behavior in simulation and on the quadrupedal robot ANYmal.

{{</citation>}}


### (109/125) Hierarchical Reinforcement Learning based on Planning Operators (Jing Zhang et al., 2023)

{{<citation>}}

Jing Zhang, Karinne Ramirez-Amaro. (2023)  
**Hierarchical Reinforcement Learning based on Planning Operators**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14237v1)  

---


**ABSTRACT**  
Long-horizon manipulation tasks such as stacking represent a longstanding challenge in the field of robotic manipulation, particularly when using reinforcement learning (RL) methods which often struggle to learn the correct sequence of actions for achieving these complex goals. To learn this sequence, symbolic planning methods offer a good solution based on high-level reasoning, however, planners often fall short in addressing the low-level control specificity needed for precise execution. This paper introduces a novel framework that integrates symbolic planning with hierarchical RL through the cooperation of high-level operators and low-level policies. Our contribution integrates planning operators (e.g. preconditions and effects) as part of the hierarchical RL algorithm based on the Scheduled Auxiliary Control (SAC-X) method. We developed a dual-purpose high-level operator, which can be used both in holistic planning and as independent, reusable policies. Our approach offers a flexible solution for long-horizon tasks, e.g., stacking a cube. The experimental results show that our proposed method obtained an average of 97.2% success rate for learning and executing the whole stack sequence, and the success rate for learning independent policies, e.g. reach (98.9%), lift (99.7%), stack (85%), etc. The training time is also reduced by 68% when using our proposed approach.

{{</citation>}}


### (110/125) HumanMimic: Learning Natural Locomotion and Transitions for Humanoid Robot via Wasserstein Adversarial Imitation (Annan Tang et al., 2023)

{{<citation>}}

Annan Tang, Takuma Hiraoka, Naoki Hiraoka, Fan Shi, Kento Kawaharazuka, Kunio Kojima, Kei Okada, Masayuki Inaba. (2023)  
**HumanMimic: Learning Natural Locomotion and Transitions for Humanoid Robot via Wasserstein Adversarial Imitation**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14225v2)  

---


**ABSTRACT**  
Transferring human motion skills to humanoid robots remains a significant challenge. In this study, we introduce a Wasserstein adversarial imitation learning system, allowing humanoid robots to replicate natural whole-body locomotion patterns and execute seamless transitions by mimicking human motions. First, we present a unified primitive-skeleton motion retargeting to mitigate morphological differences between arbitrary human demonstrators and humanoid robots. An adversarial critic component is integrated with Reinforcement Learning (RL) to guide the control policy to produce behaviors aligned with the data distribution of mixed reference motions. Additionally, we employ a specific Integral Probabilistic Metric (IPM), namely the Wasserstein-1 distance with a novel soft boundary constraint to stabilize the training process and prevent model collapse. Our system is evaluated on a full-sized humanoid JAXON in the simulator. The resulting control policy demonstrates a wide range of locomotion patterns, including standing, push-recovery, squat walking, human-like straight-leg walking, and dynamic running. Notably, even in the absence of transition motions in the demonstration dataset, robots showcase an emerging ability to transit naturally between distinct locomotion patterns as desired speed changes.

{{</citation>}}


### (111/125) Co-Design Optimisation of Morphing Topology and Control of Winged Drones (Fabio Bergonti et al., 2023)

{{<citation>}}

Fabio Bergonti, Gabriele Nava, Valentin Wüest, Antonello Paolino, Giuseppe L'Erario, Daniele Pucci, Dario Floreano. (2023)  
**Co-Design Optimisation of Morphing Topology and Control of Winged Drones**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Drone  
[Paper Link](http://arxiv.org/abs/2309.13948v1)  

---


**ABSTRACT**  
The design and control of winged aircraft and drones is an iterative process aimed at identifying a compromise of mission-specific costs and constraints. When agility is required, shape-shifting (morphing) drones represent an efficient solution. However, morphing drones require the addition of actuated joints that increase the topology and control coupling, making the design process more complex. We propose a co-design optimisation method that assists the engineers by proposing a morphing drone's conceptual design that includes topology, actuation, morphing strategy, and controller parameters. The method consists of applying multi-objective constraint-based optimisation to a multi-body winged drone with trajectory optimisation to solve the motion intelligence problem under diverse flight mission requirements. We show that co-designed morphing drones outperform fixed-winged drones in terms of energy efficiency and agility, suggesting that the proposed co-design method could be a useful addition to the aircraft engineering toolbox.

{{</citation>}}


### (112/125) SPOTS: Stable Placement of Objects with Reasoning in Semi-Autonomous Teleoperation Systems (Joonhyung Lee et al., 2023)

{{<citation>}}

Joonhyung Lee, Sangbeom Park, Jeongeun Park, Kyungjae Lee, Sungjoon Choi. (2023)  
**SPOTS: Stable Placement of Objects with Reasoning in Semi-Autonomous Teleoperation Systems**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2309.13937v1)  

---


**ABSTRACT**  
Pick-and-place is one of the fundamental tasks in robotics research. However, the attention has been mostly focused on the ``pick'' task, leaving the ``place'' task relatively unexplored. In this paper, we address the problem of placing objects in the context of a teleoperation framework. Particularly, we focus on two aspects of the place task: stability robustness and contextual reasonableness of object placements. Our proposed method combines simulation-driven physical stability verification via real-to-sim and the semantic reasoning capability of large language models. In other words, given place context information (e.g., user preferences, object to place, and current scene information), our proposed method outputs a probability distribution over the possible placement candidates, considering the robustness and reasonableness of the place task. Our proposed method is extensively evaluated in two simulation and one real world environments and we show that our method can greatly increase the physical plausibility of the placement as well as contextual soundness while considering user preferences.

{{</citation>}}


### (113/125) A comparison of controller architectures and learning mechanisms for arbitrary robot morphologies (Jie Luo et al., 2023)

{{<citation>}}

Jie Luo, Jakub Tomczak, Karine Miras, Agoston E. Eiben. (2023)  
**A comparison of controller architectures and learning mechanisms for arbitrary robot morphologies**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-LG, cs-NE, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.13908v1)  

---


**ABSTRACT**  
The main question this paper addresses is: What combination of a robot controller and a learning method should be used, if the morphology of the learning robot is not known in advance? Our interest is rooted in the context of morphologically evolving modular robots, but the question is also relevant in general, for system designers interested in widely applicable solutions. We perform an experimental comparison of three controller-and-learner combinations: one approach where controllers are based on modelling animal locomotion (Central Pattern Generators, CPG) and the learner is an evolutionary algorithm, a completely different method using Reinforcement Learning (RL) with a neural network controller architecture, and a combination `in-between' where controllers are neural networks and the learner is an evolutionary algorithm. We apply these three combinations to a test suite of modular robots and compare their efficacy, efficiency, and robustness. Surprisingly, the usual CPG-based and RL-based options are outperformed by the in-between combination that is more robust and efficient than the other two setups.

{{</citation>}}


### (114/125) Invariant Smoothing for Localization: Including the IMU Biases (Paul Chauchat et al., 2023)

{{<citation>}}

Paul Chauchat, Silvère Bonnabel, Axel Barrau. (2023)  
**Invariant Smoothing for Localization: Including the IMU Biases**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.13903v1)  

---


**ABSTRACT**  
In this article we investigate smoothing (i.e., optimisation-based) estimation techniques for robot localization using an IMU aided by other localization sensors. We more particularly focus on Invariant Smoothing (IS), a variant based on the use of nontrivial Lie groups from robotics. We study the recently introduced Two Frames Group (TFG), and prove it can fit into the framework of Invariant Smoothing in order to better take into account the IMU biases, as compared to the state-of-the-art in robotics. Experiments based on the KITTI dataset show the proposed framework compares favorably to the state-of-the-art smoothing methods in terms of robustness in some challenging situations.

{{</citation>}}


## cs.GT (1)



### (115/125) Online and Offline Dynamic Influence Maximization Games Over Social Networks (Melih Bastopcu et al., 2023)

{{<citation>}}

Melih Bastopcu, S. Rasoul Etesami, Tamer Başar. (2023)  
**Online and Offline Dynamic Influence Maximization Games Over Social Networks**  

---
Primary Category: cs.GT  
Categories: cs-GT, cs-MA, cs-SY, cs.GT, eess-SY, math-OC  
Keywords: Social Network  
[Paper Link](http://arxiv.org/abs/2309.14317v1)  

---


**ABSTRACT**  
In this work, we consider dynamic influence maximization games over social networks with multiple players (influencers). The goal of each influencer is to maximize their own reward subject to their limited total budget rate constraints. Thus, influencers need to carefully design their investment policies considering individuals' opinion dynamics and other influencers' investment strategies, leading to a dynamic game problem. We first consider the case of a single influencer who wants to maximize its utility subject to a total budget rate constraint. We study both offline and online versions of the problem where the opinion dynamics are either known or not known a priori. In the singe-influencer case, we propose an online no-regret algorithm, meaning that as the number of campaign opportunities grows, the average utilities obtained by the offline and online solutions converge. Then, we consider the game formulation with multiple influencers in offline and online settings. For the offline setting, we show that the dynamic game admits a unique Nash equilibrium policy and provide a method to compute it. For the online setting and with two influencers, we show that if each influencer applies the same no-regret online algorithm proposed for the single-influencer maximization problem, they will converge to the set of $\epsilon$-Nash equilibrium policies where $\epsilon=O(\frac{1}{\sqrt{K}})$ scales in average inversely with the number of campaign times $K$ considering the average utilities of the influencers. Moreover, we extend this result to any finite number of influencers under more strict requirements on the information structure. Finally, we provide numerical analysis to validate our results under various settings.

{{</citation>}}


## cs.CR (2)



### (116/125) DECORAIT -- DECentralized Opt-in/out Registry for AI Training (Kar Balan et al., 2023)

{{<citation>}}

Kar Balan, Alex Black, Simon Jenni, Andrew Gilbert, Andy Parsons, John Collomosse. (2023)  
**DECORAIT -- DECentralized Opt-in/out Registry for AI Training**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR, eess-IV  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2309.14400v1)  

---


**ABSTRACT**  
We present DECORAIT; a decentralized registry through which content creators may assert their right to opt in or out of AI training as well as receive reward for their contributions. Generative AI (GenAI) enables images to be synthesized using AI models trained on vast amounts of data scraped from public sources. Model and content creators who may wish to share their work openly without sanctioning its use for training are thus presented with a data governance challenge. Further, establishing the provenance of GenAI training data is important to creatives to ensure fair recognition and reward for their such use. We report a prototype of DECORAIT, which explores hierarchical clustering and a combination of on/off-chain storage to create a scalable decentralized registry to trace the provenance of GenAI training data in order to determine training consent and reward creatives who contribute that data. DECORAIT combines distributed ledger technology (DLT) with visual fingerprinting, leveraging the emerging C2PA (Coalition for Content Provenance and Authenticity) standard to create a secure, open registry through which creatives may express consent and data ownership for GenAI.

{{</citation>}}


### (117/125) On the Effectiveness of Adversarial Samples against Ensemble Learning-based Windows PE Malware Detectors (Trong-Nghia To et al., 2023)

{{<citation>}}

Trong-Nghia To, Danh Le Kim, Do Thi Thu Hien, Nghi Hoang Khoa, Hien Do Hoang, Phan The Duy, Van-Hau Pham. (2023)  
**On the Effectiveness of Adversarial Samples against Ensemble Learning-based Windows PE Malware Detectors**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.13841v1)  

---


**ABSTRACT**  
Recently, there has been a growing focus and interest in applying machine learning (ML) to the field of cybersecurity, particularly in malware detection and prevention. Several research works on malware analysis have been proposed, offering promising results for both academic and practical applications. In these works, the use of Generative Adversarial Networks (GANs) or Reinforcement Learning (RL) can aid malware creators in crafting metamorphic malware that evades antivirus software. In this study, we propose a mutation system to counteract ensemble learning-based detectors by combining GANs and an RL model, overcoming the limitations of the MalGAN model. Our proposed FeaGAN model is built based on MalGAN by incorporating an RL model called the Deep Q-network anti-malware Engines Attacking Framework (DQEAF). The RL model addresses three key challenges in performing adversarial attacks on Windows Portable Executable malware, including format preservation, executability preservation, and maliciousness preservation. In the FeaGAN model, ensemble learning is utilized to enhance the malware detector's evasion ability, with the generated adversarial patterns. The experimental results demonstrate that 100\% of the selected mutant samples preserve the format of executable files, while certain successes in both executability preservation and maliciousness preservation are achieved, reaching a stable success rate.

{{</citation>}}


## cs.NI (1)



### (118/125) Rethinking Internet Communication Through LLMs: How Close Are We? (Sifat Ut Taki et al., 2023)

{{<citation>}}

Sifat Ut Taki, Spyridon Mastorakis. (2023)  
**Rethinking Internet Communication Through LLMs: How Close Are We?**  

---
Primary Category: cs.NI  
Categories: cs-AI, cs-LG, cs-NI, cs.NI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14247v1)  

---


**ABSTRACT**  
In this paper, we rethink the way that communication among users over the Internet, one of the fundamental outcomes of the Internet evolution, takes place. Instead of users communicating directly over the Internet, we explore an architecture that enables users to communicate with (query) Large Language Models (LLMs) that capture the cognition of users on the other end of the communication channel. We present an architecture to achieve such LLM-based communication and we perform a reality check to assess how close we are today to realizing such a communication architecture from a technical point of view. Finally, we discuss several research challenges and identify interesting directions for future research.

{{</citation>}}


## cs.SE (2)



### (119/125) Guess & Sketch: Language Model Guided Transpilation (Celine Lee et al., 2023)

{{<citation>}}

Celine Lee, Abdulrahman Mahmoud, Michal Kurek, Simone Campanoni, David Brooks, Stephen Chong, Gu-Yeon Wei, Alexander M. Rush. (2023)  
**Guess & Sketch: Language Model Guided Transpilation**  

---
Primary Category: cs.SE  
Categories: cs-LG, cs-PL, cs-SE, cs.SE  
Keywords: GPT, GPT-4, Language Model, Sketch  
[Paper Link](http://arxiv.org/abs/2309.14396v1)  

---


**ABSTRACT**  
Maintaining legacy software requires many software and systems engineering hours. Assembly code programs, which demand low-level control over the computer machine state and have no variable names, are particularly difficult for humans to analyze. Existing conventional program translators guarantee correctness, but are hand-engineered for the source and target programming languages in question. Learned transpilation, i.e. automatic translation of code, offers an alternative to manual re-writing and engineering efforts. Automated symbolic program translation approaches guarantee correctness but struggle to scale to longer programs due to the exponentially large search space. Their rigid rule-based systems also limit their expressivity, so they can only reason about a reduced space of programs. Probabilistic neural language models (LMs) produce plausible outputs for every input, but do so at the cost of guaranteed correctness. In this work, we leverage the strengths of LMs and symbolic solvers in a neurosymbolic approach to learned transpilation for assembly code. Assembly code is an appropriate setting for a neurosymbolic approach, since assembly code can be divided into shorter non-branching basic blocks amenable to the use of symbolic methods. Guess & Sketch extracts alignment and confidence information from features of the LM then passes it to a symbolic solver to resolve semantic equivalence of the transpilation input and output. We test Guess & Sketch on three different test sets of assembly transpilation tasks, varying in difficulty, and show that it successfully transpiles 57.6% more examples than GPT-4 and 39.6% more examples than an engineered transpiler. We also share a training and evaluation dataset for this task.

{{</citation>}}


### (120/125) The Influence of Cognitive Biases on Architectural Technical Debt (Klara Borowa et al., 2023)

{{<citation>}}

Klara Borowa, Andrzej Zalewski, Szymon Kijas. (2023)  
**The Influence of Cognitive Biases on Architectural Technical Debt**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.14175v1)  

---


**ABSTRACT**  
Cognitive biases exert a significant influence on human thinking and decision-making. In order to identify how they influence the occurrence of architectural technical debt, a series of semi-structured interviews with software architects was performed. The results show which classes of architectural technical debt originate from cognitive biases, and reveal the antecedents of technical debt items (classes) through biases. This way, we analysed how and when cognitive biases lead to the creation of technical debt. We also identified a set of debiasing techniques that can be used in order to prevent the negative influence of cognitive biases. The observations of the role of organisational culture in the avoidance of inadvertent technical debt throw a new light on that issue.

{{</citation>}}


## cs.CE (1)



### (121/125) Autonomous Vehicles an overview on system, cyber security, risks, issues, and a way forward (Md Aminul Islam et al., 2023)

{{<citation>}}

Md Aminul Islam, Sarah Alqahtani. (2023)  
**Autonomous Vehicles an overview on system, cyber security, risks, issues, and a way forward**  

---
Primary Category: cs.CE  
Categories: cs-CE, cs-CL, cs.CE  
Keywords: AI, Cyber Security, Security, Smart Car  
[Paper Link](http://arxiv.org/abs/2309.14213v1)  

---


**ABSTRACT**  
This chapter explores the complex realm of autonomous cars, analyzing their fundamental components and operational characteristics. The initial phase of the discussion is elucidating the internal mechanics of these automobiles, encompassing the crucial involvement of sensors, artificial intelligence (AI) identification systems, control mechanisms, and their integration with cloud-based servers within the framework of the Internet of Things (IoT). It delves into practical implementations of autonomous cars, emphasizing their utilization in forecasting traffic patterns and transforming the dynamics of transportation. The text also explores the topic of Robotic Process Automation (RPA), illustrating the impact of autonomous cars on different businesses through the automation of tasks. The primary focus of this investigation lies in the realm of cybersecurity, specifically in the context of autonomous vehicles. A comprehensive analysis will be conducted to explore various risk management solutions aimed at protecting these vehicles from potential threats including ethical, environmental, legal, professional, and social dimensions, offering a comprehensive perspective on their societal implications. A strategic plan for addressing the challenges and proposing strategies for effectively traversing the complex terrain of autonomous car systems, cybersecurity, hazards, and other concerns are some resources for acquiring an understanding of the intricate realm of autonomous cars and their ramifications in contemporary society, supported by a comprehensive compilation of resources for additional investigation.   Keywords: RPA, Cyber Security, AV, Risk, Smart Cars

{{</citation>}}


## cs.DC (1)



### (122/125) SPIRT: A Fault-Tolerant and Reliable Peer-to-Peer Serverless ML Training Architecture (Amine Barrak et al., 2023)

{{<citation>}}

Amine Barrak, Mayssa Jaziri, Ranim Trabelsi, Fehmi Jaafar, Fabio Petrillo. (2023)  
**SPIRT: A Fault-Tolerant and Reliable Peer-to-Peer Serverless ML Training Architecture**  

---
Primary Category: cs.DC  
Categories: cs-AI, cs-DC, cs.DC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14148v1)  

---


**ABSTRACT**  
The advent of serverless computing has ushered in notable advancements in distributed machine learning, particularly within parameter server-based architectures. Yet, the integration of serverless features within peer-to-peer (P2P) distributed networks remains largely uncharted. In this paper, we introduce SPIRT, a fault-tolerant, reliable, and secure serverless P2P ML training architecture. designed to bridge this existing gap.   Capitalizing on the inherent robustness and reliability innate to P2P systems, SPIRT employs RedisAI for in-database operations, leading to an 82\% reduction in the time required for model updates and gradient averaging across a variety of models and batch sizes. This architecture showcases resilience against peer failures and adeptly manages the integration of new peers, thereby highlighting its fault-tolerant characteristics and scalability. Furthermore, SPIRT ensures secure communication between peers, enhancing the reliability of distributed machine learning tasks. Even in the face of Byzantine attacks, the system's robust aggregation algorithms maintain high levels of accuracy. These findings illuminate the promising potential of serverless architectures in P2P distributed machine learning, offering a significant stride towards the development of more efficient, scalable, and resilient applications.

{{</citation>}}


## hep-ph (1)



### (123/125) HyperTrack: Neural Combinatorics for High Energy Physics (Mikael Mieskolainen, 2023)

{{<citation>}}

Mikael Mieskolainen. (2023)  
**HyperTrack: Neural Combinatorics for High Energy Physics**  

---
Primary Category: hep-ph  
Categories: cs-LG, hep-ex, hep-ph, hep-ph  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14113v1)  

---


**ABSTRACT**  
Combinatorial inverse problems in high energy physics span enormous algorithmic challenges. This work presents a new deep learning driven clustering algorithm that utilizes a space-time non-local trainable graph constructor, a graph neural network, and a set transformer. The model is trained with loss functions at the graph node, edge and object level, including contrastive learning and meta-supervision. The algorithm can be applied to problems such as charged particle tracking, calorimetry, pile-up discrimination, jet physics, and beyond. We showcase the effectiveness of this cutting-edge AI approach through particle tracking simulations. The code is available online.

{{</citation>}}


## math.NA (1)



### (124/125) Deep Reinforcement Learning for the Heat Transfer Control of Pulsating Impinging Jets (Sajad Salavatidezfouli et al., 2023)

{{<citation>}}

Sajad Salavatidezfouli, Giovanni Stabile, Gianluigi Rozza. (2023)  
**Deep Reinforcement Learning for the Heat Transfer Control of Pulsating Impinging Jets**  

---
Primary Category: math.NA  
Categories: cs-LG, cs-NA, math-NA, math.NA  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.13955v1)  

---


**ABSTRACT**  
This research study explores the applicability of Deep Reinforcement Learning (DRL) for thermal control based on Computational Fluid Dynamics. To accomplish that, the forced convection on a hot plate prone to a pulsating cooling jet with variable velocity has been investigated. We begin with evaluating the efficiency and viability of a vanilla Deep Q-Network (DQN) method for thermal control. Subsequently, a comprehensive comparison between different variants of DRL is conducted. Soft Double and Duel DQN achieved better thermal control performance among all the variants due to their efficient learning and action prioritization capabilities. Results demonstrate that the soft Double DQN outperforms the hard Double DQN. Moreover, soft Double and Duel can maintain the temperature in the desired threshold for more than 98% of the control cycle. These findings demonstrate the promising potential of DRL in effectively addressing thermal control systems.

{{</citation>}}


## cs.SI (1)



### (125/125) Graph Representation Learning Towards Patents Network Analysis (Mohammad Heydari et al., 2023)

{{<citation>}}

Mohammad Heydari, Babak Teimourpour. (2023)  
**Graph Representation Learning Towards Patents Network Analysis**  

---
Primary Category: cs.SI  
Categories: cs-LG, cs-SI, cs.SI  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2309.13888v1)  

---


**ABSTRACT**  
Patent analysis has recently been recognized as a powerful technique for large companies worldwide to lend them insight into the age of competition among various industries. This technique is considered a shortcut for developing countries since it can significantly accelerate their technology development. Therefore, as an inevitable process, patent analysis can be utilized to monitor rival companies and diverse industries. This research employed a graph representation learning approach to create, analyze, and find similarities in the patent data registered in the Iranian Official Gazette. The patent records were scrapped and wrangled through the Iranian Official Gazette portal. Afterward, the key entities were extracted from the scrapped patents dataset to create the Iranian patents graph from scratch based on novel natural language processing and entity resolution techniques. Finally, thanks to the utilization of novel graph algorithms and text mining methods, we identified new areas of industry and research from Iranian patent data, which can be used extensively to prevent duplicate patents, familiarity with similar and connected inventions, Awareness of legal entities supporting patents and knowledge of researchers and linked stakeholders in a particular research field.

{{</citation>}}
