---
draft: false
title: "arXiv @ 2023.09.28"
date: 2023-09-28
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.09.28"
    identifier: arxiv_20230928
    parent: 202309_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.CL (19)](#cscl-19)
- [cs.CV (27)](#cscv-27)
- [cs.RO (10)](#csro-10)
- [cs.LG (22)](#cslg-22)
- [cs.DB (1)](#csdb-1)
- [cs.AI (4)](#csai-4)
- [cs.CY (4)](#cscy-4)
- [cs.CR (4)](#cscr-4)
- [eess.AS (4)](#eessas-4)
- [cs.HC (3)](#cshc-3)
- [cs.IR (3)](#csir-3)
- [stat.ME (1)](#statme-1)
- [eess.SY (2)](#eesssy-2)
- [cs.SE (3)](#csse-3)
- [eess.SP (1)](#eesssp-1)
- [q-bio.BM (1)](#q-biobm-1)
- [cond-mat.dis-nn (1)](#cond-matdis-nn-1)
- [cs.SD (2)](#cssd-2)
- [cs.DC (1)](#csdc-1)
- [cs.IT (1)](#csit-1)
- [eess.IV (1)](#eessiv-1)

## cs.CL (19)



### (1/115) Joint Prediction and Denoising for Large-scale Multilingual Self-supervised Learning (William Chen et al., 2023)

{{<citation>}}

William Chen, Jiatong Shi, Brian Yan, Dan Berrebbi, Wangyou Zhang, Yifan Peng, Xuankai Chang, Soumi Maiti, Shinji Watanabe. (2023)  
**Joint Prediction and Denoising for Large-scale Multilingual Self-supervised Learning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: BERT, Multilingual  
[Paper Link](http://arxiv.org/abs/2309.15317v2)  

---


**ABSTRACT**  
Multilingual self-supervised learning (SSL) has often lagged behind state-of-the-art (SOTA) methods due to the expenses and complexity required to handle many languages. This further harms the reproducibility of SSL, which is already limited to few research groups due to its resource usage. We show that more powerful techniques can actually lead to more efficient pre-training, opening SSL to more research groups. We propose WavLabLM, which extends WavLM's joint prediction and denoising to 40k hours of data across 136 languages. To build WavLabLM, we devise a novel multi-stage pre-training method, designed to address the language imbalance of multilingual data. WavLabLM achieves comparable performance to XLS-R on ML-SUPERB with less than 10% of the training data, making SSL realizable with academic compute. We show that further efficiency can be achieved with a vanilla HuBERT Base model, which can maintain 94% of XLS-R's performance with only 3% of the data, 4 GPUs, and limited trials. We open-source all code and models in ESPnet.

{{</citation>}}


### (2/115) Unsupervised Pre-Training for Vietnamese Automatic Speech Recognition in the HYKIST Project (Khai Le-Duc, 2023)

{{<citation>}}

Khai Le-Duc. (2023)  
**Unsupervised Pre-Training for Vietnamese Automatic Speech Recognition in the HYKIST Project**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.15869v1)  

---


**ABSTRACT**  
In today's interconnected globe, moving abroad is more and more prevalent, whether it's for employment, refugee resettlement, or other causes. Language difficulties between natives and immigrants present a common issue on a daily basis, especially in medical domain. This can make it difficult for patients and doctors to communicate during anamnesis or in the emergency room, which compromises patient care. The goal of the HYKIST Project is to develop a speech translation system to support patient-doctor communication with ASR and MT.   ASR systems have recently displayed astounding performance on particular tasks for which enough quantities of training data are available, such as LibriSpeech. Building a good model is still difficult due to a variety of speaking styles, acoustic and recording settings, and a lack of in-domain training data. In this thesis, we describe our efforts to construct ASR systems for a conversational telephone speech recognition task in the medical domain for Vietnamese language to assist emergency room contact between doctors and patients across linguistic barriers. In order to enhance the system's performance, we investigate various training schedules and data combining strategies. We also examine how best to make use of the little data that is available. The use of publicly accessible models like XLSR-53 is compared to the use of customized pre-trained models, and both supervised and unsupervised approaches are utilized using wav2vec 2.0 as architecture.

{{</citation>}}


### (3/115) Low-rank Adaptation of Large Language Model Rescoring for Parameter-Efficient Speech Recognition (Yu Yu et al., 2023)

{{<citation>}}

Yu Yu, Chao-Han Huck Yang, Jari Kolehmainen, Prashanth G. Shivakumar, Yile Gu, Sungho Ryu, Roger Ren, Qi Luo, Aditya Gourav, I-Fan Chen, Yi-Chieh Liu, Tuan Dinh, Ankur Gandhe, Denis Filimonov, Shalini Ghosh, Andreas Stolcke, Ariya Rastow, Ivan Bulyko. (2023)  
**Low-rank Adaptation of Large Language Model Rescoring for Parameter-Efficient Speech Recognition**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs-NE, cs-SD, cs.CL, eess-AS  
Keywords: BERT, Language Model, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.15223v1)  

---


**ABSTRACT**  
We propose a neural language modeling system based on low-rank adaptation (LoRA) for speech recognition output rescoring. Although pretrained language models (LMs) like BERT have shown superior performance in second-pass rescoring, the high computational cost of scaling up the pretraining stage and adapting the pretrained models to specific domains limit their practical use in rescoring. Here we present a method based on low-rank decomposition to train a rescoring BERT model and adapt it to new domains using only a fraction (0.08%) of the pretrained parameters. These inserted matrices are optimized through a discriminative training objective along with a correlation-based regularization loss. The proposed low-rank adaptation Rescore-BERT (LoRB) architecture is evaluated on LibriSpeech and internal datasets with decreased training times by factors between 5.4 and 3.6.

{{</citation>}}


### (4/115) STANCE-C3: Domain-adaptive Cross-target Stance Detection via Contrastive Learning and Counterfactual Generation (Nayoung Kim et al., 2023)

{{<citation>}}

Nayoung Kim, David Mosallanezhad, Lu Cheng, Michelle V. Mancenido, Huan Liu. (2023)  
**STANCE-C3: Domain-adaptive Cross-target Stance Detection via Contrastive Learning and Counterfactual Generation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SI, cs.CL  
Keywords: Contrastive Learning, Stance Detection  
[Paper Link](http://arxiv.org/abs/2309.15176v1)  

---


**ABSTRACT**  
Stance detection is the process of inferring a person's position or standpoint on a specific issue to deduce prevailing perceptions toward topics of general or controversial interest, such as health policies during the COVID-19 pandemic. Existing models for stance detection are trained to perform well for a single domain (e.g., COVID-19) and a specific target topic (e.g., masking protocols), but are generally ineffectual in other domains or targets due to distributional shifts in the data. However, constructing high-performing, domain-specific stance detection models requires an extensive corpus of labeled data relevant to the targeted domain, yet such datasets are not readily available. This poses a challenge as the process of annotating data is costly and time-consuming. To address these challenges, we introduce a novel stance detection model coined domain-adaptive Cross-target STANCE detection via Contrastive learning and Counterfactual generation (STANCE-C3) that uses counterfactual data augmentation to enhance domain-adaptive training by enriching the target domain dataset during the training process and requiring significantly less information from the new domain. We also propose a modified self-supervised contrastive learning as a component of STANCE-C3 to prevent overfitting for the existing domain and target and enable cross-target stance detection. Through experiments on various datasets, we show that STANCE-C3 shows performance improvement over existing state-of-the-art methods.

{{</citation>}}


### (5/115) Attention Satisfies: A Constraint-Satisfaction Lens on Factual Errors of Language Models (Mert Yuksekgonul et al., 2023)

{{<citation>}}

Mert Yuksekgonul, Varun Chandrasekaran, Erik Jones, Suriya Gunasekar, Ranjita Naik, Hamid Palangi, Ece Kamar, Besmira Nushi. (2023)  
**Attention Satisfies: A Constraint-Satisfaction Lens on Factual Errors of Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Attention, Language Model, Transformer  
[Paper Link](http://arxiv.org/abs/2309.15098v1)  

---


**ABSTRACT**  
We investigate the internal behavior of Transformer-based Large Language Models (LLMs) when they generate factually incorrect text. We propose modeling factual queries as Constraint Satisfaction Problems and use this framework to investigate how the model interacts internally with factual constraints. Specifically, we discover a strong positive relation between the model's attention to constraint tokens and the factual accuracy of its responses. In our curated suite of 11 datasets with over 40,000 prompts, we study the task of predicting factual errors with the Llama-2 family across all scales (7B, 13B, 70B). We propose SAT Probe, a method probing self-attention patterns, that can predict constraint satisfaction and factual errors, and allows early error identification. The approach and findings demonstrate how using the mechanistic understanding of factuality in LLMs can enhance reliability.

{{</citation>}}


### (6/115) How to Catch an AI Liar: Lie Detection in Black-Box LLMs by Asking Unrelated Questions (Lorenzo Pacchiardi et al., 2023)

{{<citation>}}

Lorenzo Pacchiardi, Alex J. Chan, Sören Mindermann, Ilan Moscovitz, Alexa Y. Pan, Yarin Gal, Owain Evans, Jan Brauner. (2023)  
**How to Catch an AI Liar: Lie Detection in Black-Box LLMs by Asking Unrelated Questions**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: AI, GPT, GPT-3.5  
[Paper Link](http://arxiv.org/abs/2309.15840v1)  

---


**ABSTRACT**  
Large language models (LLMs) can "lie", which we define as outputting false statements despite "knowing" the truth in a demonstrable sense. LLMs might "lie", for example, when instructed to output misinformation. Here, we develop a simple lie detector that requires neither access to the LLM's activations (black-box) nor ground-truth knowledge of the fact in question. The detector works by asking a predefined set of unrelated follow-up questions after a suspected lie, and feeding the LLM's yes/no answers into a logistic regression classifier. Despite its simplicity, this lie detector is highly accurate and surprisingly general. When trained on examples from a single setting -- prompting GPT-3.5 to lie about factual questions -- the detector generalises out-of-distribution to (1) other LLM architectures, (2) LLMs fine-tuned to lie, (3) sycophantic lies, and (4) lies emerging in real-life scenarios such as sales. These results indicate that LLMs have distinctive lie-related behavioural patterns, consistent across architectures and contexts, which could enable general-purpose lie detection.

{{</citation>}}


### (7/115) Large Language Model Alignment: A Survey (Tianhao Shen et al., 2023)

{{<citation>}}

Tianhao Shen, Renren Jin, Yufei Huang, Chuang Liu, Weilong Dong, Zishan Guo, Xinwei Wu, Yan Liu, Deyi Xiong. (2023)  
**Large Language Model Alignment: A Survey**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2309.15025v1)  

---


**ABSTRACT**  
Recent years have witnessed remarkable progress made in large language models (LLMs). Such advancements, while garnering significant attention, have concurrently elicited various concerns. The potential of these models is undeniably vast; however, they may yield texts that are imprecise, misleading, or even detrimental. Consequently, it becomes paramount to employ alignment techniques to ensure these models to exhibit behaviors consistent with human values.   This survey endeavors to furnish an extensive exploration of alignment methodologies designed for LLMs, in conjunction with the extant capability research in this domain. Adopting the lens of AI alignment, we categorize the prevailing methods and emergent proposals for the alignment of LLMs into outer and inner alignment. We also probe into salient issues including the models' interpretability, and potential vulnerabilities to adversarial attacks. To assess LLM alignment, we present a wide variety of benchmarks and evaluation methodologies. After discussing the state of alignment research for LLMs, we finally cast a vision toward the future, contemplating the promising avenues of research that lie ahead.   Our aspiration for this survey extends beyond merely spurring research interests in this realm. We also envision bridging the gap between the AI alignment research community and the researchers engrossed in the capability exploration of LLMs for both capable and safe LLMs.

{{</citation>}}


### (8/115) Question-Answering Approach to Evaluate Legal Summaries (Huihui Xu et al., 2023)

{{<citation>}}

Huihui Xu, Kevin Ashley. (2023)  
**Question-Answering Approach to Evaluate Legal Summaries**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4, Legal  
[Paper Link](http://arxiv.org/abs/2309.15016v1)  

---


**ABSTRACT**  
Traditional evaluation metrics like ROUGE compare lexical overlap between the reference and generated summaries without taking argumentative structure into account, which is important for legal summaries. In this paper, we propose a novel legal summarization evaluation framework that utilizes GPT-4 to generate a set of question-answer pairs that cover main points and information in the reference summary. GPT-4 is then used to generate answers based on the generated summary for the questions from the reference summary. Finally, GPT-4 grades the answers from the reference summary and the generated summary. We examined the correlation between GPT-4 grading with human grading. The results suggest that this question-answering approach with GPT-4 can be a useful tool for gauging the quality of the summary.

{{</citation>}}


### (9/115) Updated Corpora and Benchmarks for Long-Form Speech Recognition (Jennifer Drexler Fox et al., 2023)

{{<citation>}}

Jennifer Drexler Fox, Desh Raj, Natalie Delworth, Quinn McNamara, Corey Miller, Migüel Jetté. (2023)  
**Updated Corpora and Benchmarks for Long-Form Speech Recognition**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-SD, cs.CL, eess-AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.15013v1)  

---


**ABSTRACT**  
The vast majority of ASR research uses corpora in which both the training and test data have been pre-segmented into utterances. In most real-word ASR use-cases, however, test audio is not segmented, leading to a mismatch between inference-time conditions and models trained on segmented utterances. In this paper, we re-release three standard ASR corpora - TED-LIUM 3, Gigapeech, and VoxPopuli-en - with updated transcription and alignments to enable their use for long-form ASR research. We use these reconstituted corpora to study the train-test mismatch problem for transducers and attention-based encoder-decoders (AEDs), confirming that AEDs are more susceptible to this issue. Finally, we benchmark a simple long-form training for these models, showing its efficacy for model robustness under this domain shift.

{{</citation>}}


### (10/115) Automating question generation from educational text (Ayan Kumar Bhowmick et al., 2023)

{{<citation>}}

Ayan Kumar Bhowmick, Ashish Jagmohan, Aditya Vempaty, Prasenjit Dey, Leigh Hall, Jeremy Hartman, Ravi Kokku, Hema Maheshwari. (2023)  
**Automating question generation from educational text**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15004v1)  

---


**ABSTRACT**  
The use of question-based activities (QBAs) is wide-spread in education, traditionally forming an integral part of the learning and assessment process. In this paper, we design and evaluate an automated question generation tool for formative and summative assessment in schools. We present an expert survey of one hundred and four teachers, demonstrating the need for automated generation of QBAs, as a tool that can significantly reduce the workload of teachers and facilitate personalized learning experiences. Leveraging the recent advancements in generative AI, we then present a modular framework employing transformer based language models for automatic generation of multiple-choice questions (MCQs) from textual content. The presented solution, with distinct modules for question generation, correct answer prediction, and distractor formulation, enables us to evaluate different language models and generation techniques. Finally, we perform an extensive quantitative and qualitative evaluation, demonstrating trade-offs in the use of different techniques and models.

{{</citation>}}


### (11/115) Interactively Learning Social Media Representations Improves News Source Factuality Detection (Nikhil Mehta et al., 2023)

{{<citation>}}

Nikhil Mehta, Dan Goldwasser. (2023)  
**Interactively Learning Social Media Representations Improves News Source Factuality Detection**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-SI, cs.CL  
Keywords: Social Media  
[Paper Link](http://arxiv.org/abs/2309.14966v1)  

---


**ABSTRACT**  
The rise of social media has enabled the widespread propagation of fake news, text that is published with an intent to spread misinformation and sway beliefs. Rapidly detecting fake news, especially as new events arise, is important to prevent misinformation.   While prior works have tackled this problem using supervised learning systems, automatedly modeling the complexities of the social media landscape that enables the spread of fake news is challenging. On the contrary, having humans fact check all news is not scalable. Thus, in this paper, we propose to approach this problem interactively, where humans can interact to help an automated system learn a better social media representation quality. On real world events, our experiments show performance improvements in detecting factuality of news sources, even after few human interactions.

{{</citation>}}


### (12/115) Segmentation-Free Streaming Machine Translation (Javier Iranzo-Sánchez et al., 2023)

{{<citation>}}

Javier Iranzo-Sánchez, Jorge Iranzo-Sánchez, Adrià Giménez, Jorge Civera, Alfons Juan. (2023)  
**Segmentation-Free Streaming Machine Translation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Machine Translation, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.14823v1)  

---


**ABSTRACT**  
Streaming Machine Translation (MT) is the task of translating an unbounded input text stream in real-time. The traditional cascade approach, which combines an Automatic Speech Recognition (ASR) and an MT system, relies on an intermediate segmentation step which splits the transcription stream into sentence-like units. However, the incorporation of a hard segmentation constrains the MT system and is a source of errors. This paper proposes a Segmentation-Free framework that enables the model to translate an unsegmented source stream by delaying the segmentation decision until the translation has been generated. Extensive experiments show how the proposed Segmentation-Free framework has better quality-latency trade-off than competing approaches that use an independent segmentation model. Software, data and models will be released upon paper acceptance.

{{</citation>}}


### (13/115) Fine-tuning and aligning question answering models for complex information extraction tasks (Matthias Engelbach et al., 2023)

{{<citation>}}

Matthias Engelbach, Dennis Klau, Felix Scheerer, Jens Drawehn, Maximilien Kintz. (2023)  
**Fine-tuning and aligning question answering models for complex information extraction tasks**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, ChatGPT, GPT, Language Model, NLP, QA  
[Paper Link](http://arxiv.org/abs/2309.14805v1)  

---


**ABSTRACT**  
The emergence of Large Language Models (LLMs) has boosted performance and possibilities in various NLP tasks. While the usage of generative AI models like ChatGPT opens up new opportunities for several business use cases, their current tendency to hallucinate fake content strongly limits their applicability to document analysis, such as information retrieval from documents. In contrast, extractive language models like question answering (QA) or passage retrieval models guarantee query results to be found within the boundaries of an according context document, which makes them candidates for more reliable information extraction in productive environments of companies. In this work we propose an approach that uses and integrates extractive QA models for improved feature extraction of German business documents such as insurance reports or medical leaflets into a document analysis solution. We further show that fine-tuning existing German QA models boosts performance for tailored extraction tasks of complex linguistic features like damage cause explanations or descriptions of medication appearance, even with using only a small set of annotated data. Finally, we discuss the relevance of scoring metrics for evaluating information extraction tasks and deduce a combined metric from Levenshtein distance, F1-Score, Exact Match and ROUGE-L to mimic the assessment criteria from human experts.

{{</citation>}}


### (14/115) Exploring Small Language Models with Prompt-Learning Paradigm for Efficient Domain-Specific Text Classification (Hengyu Luo et al., 2023)

{{<citation>}}

Hengyu Luo, Peng Liu, Stefan Esping. (2023)  
**Exploring Small Language Models with Prompt-Learning Paradigm for Efficient Domain-Specific Text Classification**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-3.5, Language Model, T5, Text Classification  
[Paper Link](http://arxiv.org/abs/2309.14779v1)  

---


**ABSTRACT**  
Domain-specific text classification faces the challenge of scarce labeled data due to the high cost of manual labeling. Prompt-learning, known for its efficiency in few-shot scenarios, is proposed as an alternative to traditional fine-tuning methods. And besides, although large language models (LLMs) have gained prominence, small language models (SLMs, with under 1B parameters) offer significant customizability, adaptability, and cost-effectiveness for domain-specific tasks, given industry constraints. In this study, we investigate the potential of SLMs combined with prompt-learning paradigm for domain-specific text classification, specifically within customer-agent interactions in retail. Our evaluations show that, in few-shot settings when prompt-based model fine-tuning is possible, T5-base, a typical SLM with 220M parameters, achieve approximately 75% accuracy with limited labeled data (up to 15% of full data), which shows great potentials of SLMs with prompt-learning. Based on this, We further validate the effectiveness of active few-shot sampling and the ensemble strategy in the prompt-learning pipeline that contribute to a remarkable performance gain. Besides, in zero-shot settings with a fixed model, we underscore a pivotal observation that, although the GPT-3.5-turbo equipped with around 154B parameters garners an accuracy of 55.16%, the power of well designed prompts becomes evident when the FLAN-T5-large, a model with a mere 0.5% of GPT-3.5-turbo's parameters, achieves an accuracy exceeding 31% with the optimized prompt, a leap from its sub-18% performance with an unoptimized one. Our findings underscore the promise of prompt-learning in classification tasks with SLMs, emphasizing the benefits of active few-shot sampling, and ensemble strategies in few-shot settings, and the importance of prompt engineering in zero-shot settings.

{{</citation>}}


### (15/115) Boosting In-Context Learning with Factual Knowledge (Jianing Wang et al., 2023)

{{<citation>}}

Jianing Wang, Chengyu Wang, Chuanqi Tan, Jun Huang, Ming Gao. (2023)  
**Boosting In-Context Learning with Factual Knowledge**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2309.14771v1)  

---


**ABSTRACT**  
In-Context Learning (ICL) over Large language models (LLMs) aims at solving previously unseen tasks by conditioning on a few training examples, eliminating the need for parameter updates and achieving competitive performance. In this paper, we demonstrate that factual knowledge is imperative for the performance of ICL in three core facets, i.e., the inherent knowledge learned in LLMs, the factual knowledge derived from the selected in-context examples, and the knowledge biases in LLMs for output generation. To unleash the power of LLMs in few-shot learning scenarios, we introduce a novel Knowledgeable In-Context Tuning (KICT) framework to further improve the performance of ICL: 1) injecting factual knowledge to LLMs during continual self-supervised pre-training, 2) judiciously selecting the examples with high knowledge relevance, and 3) calibrating the prediction results based on prior knowledge. We evaluate the proposed approaches on auto-regressive LLMs (e.g., GPT-style models) over multiple text classification and question answering tasks. Experimental results demonstrate that KICT substantially outperforms strong baselines, and improves by more than 13% and 7% of accuracy on text classification and question answering tasks, respectively.

{{</citation>}}


### (16/115) KERMIT: Knowledge Graph Completion of Enhanced Relation Modeling with Inverse Transformation (Haotian Li et al., 2023)

{{<citation>}}

Haotian Li, Lingzhi Wang, Yuliang Wei, Richard Yi Da Xu, Bailing Wang. (2023)  
**KERMIT: Knowledge Graph Completion of Enhanced Relation Modeling with Inverse Transformation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2309.14770v1)  

---


**ABSTRACT**  
Knowledge graph completion is a task that revolves around filling in missing triples based on the information available in a knowledge graph. Among the current studies, text-based methods complete the task by utilizing textual descriptions of triples. However, this modeling approach may encounter limitations, particularly when the description fails to accurately and adequately express the intended meaning. To overcome these challenges, we propose the augmentation of data through two additional mechanisms. Firstly, we employ ChatGPT as an external knowledge base to generate coherent descriptions to bridge the semantic gap between the queries and answers. Secondly, we leverage inverse relations to create a symmetric graph, thereby creating extra labeling and providing supplementary information for link prediction. This approach offers additional insights into the relationships between entities. Through these efforts, we have observed significant improvements in knowledge graph completion, as these mechanisms enhance the richness and diversity of the available data, leading to more accurate results.

{{</citation>}}


### (17/115) ConPET: Continual Parameter-Efficient Tuning for Large Language Models (Chenyang Song et al., 2023)

{{<citation>}}

Chenyang Song, Xu Han, Zheni Zeng, Kuai Li, Chen Chen, Zhiyuan Liu, Maosong Sun, Tao Yang. (2023)  
**ConPET: Continual Parameter-Efficient Tuning for Large Language Models**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14763v1)  

---


**ABSTRACT**  
Continual learning necessitates the continual adaptation of models to newly emerging tasks while minimizing the catastrophic forgetting of old ones. This is extremely challenging for large language models (LLMs) with vanilla full-parameter tuning due to high computation costs, memory consumption, and forgetting issue. Inspired by the success of parameter-efficient tuning (PET), we propose Continual Parameter-Efficient Tuning (ConPET), a generalizable paradigm for continual task adaptation of LLMs with task-number-independent training complexity. ConPET includes two versions with different application scenarios. First, Static ConPET can adapt former continual learning methods originally designed for relatively smaller models to LLMs through PET and a dynamic replay strategy, which largely reduces the tuning costs and alleviates the over-fitting and forgetting issue. Furthermore, to maintain scalability, Dynamic ConPET adopts separate PET modules for different tasks and a PET module selector for dynamic optimal selection. In our extensive experiments, the adaptation of Static ConPET helps multiple former methods reduce the scale of tunable parameters by over 3,000 times and surpass the PET-only baseline by at least 5 points on five smaller benchmarks, while Dynamic ConPET gains its advantage on the largest dataset. The codes and datasets are available at https://github.com/Raincleared-Song/ConPET.

{{</citation>}}


### (18/115) Program Repair with Minimal Edits Using CodeT5 (Atsushi Shirafuji et al., 2023)

{{<citation>}}

Atsushi Shirafuji, Md. Mostafizer Rahman, Md Faizul Ibne Amin, Yutaka Watanobe. (2023)  
**Program Repair with Minimal Edits Using CodeT5**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-SE, cs.CL  
Keywords: T5  
[Paper Link](http://arxiv.org/abs/2309.14760v1)  

---


**ABSTRACT**  
Programmers often struggle to identify and fix bugs in their programs. In recent years, many language models (LMs) have been proposed to fix erroneous programs and support error recovery. However, the LMs tend to generate solutions that differ from the original input programs. This leads to potential comprehension difficulties for users. In this paper, we propose an approach to suggest a correct program with minimal repair edits using CodeT5. We fine-tune a pre-trained CodeT5 on code pairs of wrong and correct programs and evaluate its performance with several baseline models. The experimental results show that the fine-tuned CodeT5 achieves a pass@100 of 91.95% and an average edit distance of the most similar correct program of 6.84, which indicates that at least one correct program can be suggested by generating 100 candidate programs. We demonstrate the effectiveness of LMs in suggesting program repair with minimal edits for solving introductory programming problems.

{{</citation>}}


### (19/115) Comparative Analysis of Artificial Intelligence for Indian Legal Question Answering (AILQA) Using Different Retrieval and QA Models (Shubham Kumar Nigam et al., 2023)

{{<citation>}}

Shubham Kumar Nigam, Shubham Kumar Mishra, Ayush Kumar Mishra, Noel Shallum, Arnab Bhattacharya. (2023)  
**Comparative Analysis of Artificial Intelligence for Indian Legal Question Answering (AILQA) Using Different Retrieval and QA Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, GPT, Legal, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2309.14735v1)  

---


**ABSTRACT**  
Legal question-answering (QA) systems have the potential to revolutionize the way legal professionals interact with case law documents. This paper conducts a comparative analysis of existing artificial intelligence models for their utility in answering legal questions within the Indian legal system, specifically focusing on Indian Legal Question Answering (AILQA) and our study investigates the efficacy of different retrieval and QA algorithms currently available. Utilizing the OpenAI GPT model as a benchmark, along with query prompts, our investigation shows that existing AILQA systems can automatically interpret natural language queries from users and generate highly accurate responses. This research is particularly focused on applications within the Indian criminal justice domain, which has its own set of challenges due to its complexity and resource constraints. In order to rigorously assess the performance of these models, empirical evaluations are complemented by feedback from practicing legal professionals, thereby offering a multifaceted view on the capabilities and limitations of AI in the context of Indian legal question-answering.

{{</citation>}}


## cs.CV (27)



### (20/115) Cross-City Matters: A Multimodal Remote Sensing Benchmark Dataset for Cross-City Semantic Segmentation using High-Resolution Domain Adaptation Networks (Danfeng Hong et al., 2023)

{{<citation>}}

Danfeng Hong, Bing Zhang, Hao Li, Yuxuan Li, Jing Yao, Chenyu Li, Martin Werner, Jocelyn Chanussote, Alexander Zipf, Xiao Xiang Zhu. (2023)  
**Cross-City Matters: A Multimodal Remote Sensing Benchmark Dataset for Cross-City Semantic Segmentation using High-Resolution Domain Adaptation Networks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: AI, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2309.16499v1)  

---


**ABSTRACT**  
Artificial intelligence (AI) approaches nowadays have gained remarkable success in single-modality-dominated remote sensing (RS) applications, especially with an emphasis on individual urban environments (e.g., single cities or regions). Yet these AI models tend to meet the performance bottleneck in the case studies across cities or regions, due to the lack of diverse RS information and cutting-edge solutions with high generalization ability. To this end, we build a new set of multimodal remote sensing benchmark datasets (including hyperspectral, multispectral, SAR) for the study purpose of the cross-city semantic segmentation task (called C2Seg dataset), which consists of two cross-city scenes, i.e., Berlin-Augsburg (in Germany) and Beijing-Wuhan (in China). Beyond the single city, we propose a high-resolution domain adaptation network, HighDAN for short, to promote the AI model's generalization ability from the multi-city environments. HighDAN is capable of retaining the spatially topological structure of the studied urban scene well in a parallel high-to-low resolution fusion fashion but also closing the gap derived from enormous differences of RS image representations between different cities by means of adversarial learning. In addition, the Dice loss is considered in HighDAN to alleviate the class imbalance issue caused by factors across cities. Extensive experiments conducted on the C2Seg dataset show the superiority of our HighDAN in terms of segmentation performance and generalization ability, compared to state-of-the-art competitors. The C2Seg dataset and the semantic segmentation toolbox (involving the proposed HighDAN) will be available publicly at https://github.com/danfenghong.

{{</citation>}}


### (21/115) SEPT: Towards Efficient Scene Representation Learning for Motion Prediction (Zhiqian Lan et al., 2023)

{{<citation>}}

Zhiqian Lan, Yuxuan Jiang, Yao Mu, Chen Chen, Shengbo Eben Li, Hang Zhao, Keqiang Li. (2023)  
**SEPT: Towards Efficient Scene Representation Learning for Motion Prediction**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2309.15289v1)  

---


**ABSTRACT**  
Motion prediction is crucial for autonomous vehicles to operate safely in complex traffic environments. Extracting effective spatiotemporal relationships among traffic elements is key to accurate forecasting. Inspired by the successful practice of pretrained large language models, this paper presents SEPT, a modeling framework that leverages self-supervised learning to develop powerful spatiotemporal understanding for complex traffic scenes. Specifically, our approach involves three masking-reconstruction modeling tasks on scene inputs including agents' trajectories and road network, pretraining the scene encoder to capture kinematics within trajectory, spatial structure of road network, and interactions among roads and agents. The pretrained encoder is then finetuned on the downstream forecasting task. Extensive experiments demonstrate that SEPT, without elaborate architectural design or manual feature engineering, achieves state-of-the-art performance on the Argoverse 1 and Argoverse 2 motion forecasting benchmarks, outperforming previous methods on all main metrics by a large margin.

{{</citation>}}


### (22/115) Boosting High Resolution Image Classification with Scaling-up Transformers (Yi Wang, 2023)

{{<citation>}}

Yi Wang. (2023)  
**Boosting High Resolution Image Classification with Scaling-up Transformers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Image Classification, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2309.15277v1)  

---


**ABSTRACT**  
We present a holistic approach for high resolution image classification that won second place in the ICCV/CVPPA2023 Deep Nutrient Deficiency Challenge. The approach consists of a full pipeline of: 1) data distribution analysis to check potential domain shift, 2) backbone selection for a strong baseline model that scales up for high resolution input, 3) transfer learning that utilizes published pretrained models and continuous fine-tuning on small sub-datasets, 4) data augmentation for the diversity of training data and to prevent overfitting, 5) test-time augmentation to improve the prediction's robustness, and 6) "data soups" that conducts cross-fold model prediction average for smoothened final test results.

{{</citation>}}


### (23/115) Efficient Low-rank Backpropagation for Vision Transformer Adaptation (Yuedong Yang et al., 2023)

{{<citation>}}

Yuedong Yang, Hung-Yueh Chiang, Guihong Li, Diana Marculescu, Radu Marculescu. (2023)  
**Efficient Low-rank Backpropagation for Vision Transformer Adaptation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.15275v1)  

---


**ABSTRACT**  
The increasing scale of vision transformers (ViT) has made the efficient fine-tuning of these large models for specific needs a significant challenge in various applications. This issue originates from the computationally demanding matrix multiplications required during the backpropagation process through linear layers in ViT. In this paper, we tackle this problem by proposing a new Low-rank BackPropagation via Walsh-Hadamard Transformation (LBP-WHT) method. Intuitively, LBP-WHT projects the gradient into a low-rank space and carries out backpropagation. This approach substantially reduces the computation needed for adapting ViT, as matrix multiplication in the low-rank space is far less resource-intensive. We conduct extensive experiments with different models (ViT, hybrid convolution-ViT model) on multiple datasets to demonstrate the effectiveness of our method. For instance, when adapting an EfficientFormer-L1 model on CIFAR100, our LBP-WHT achieves 10.4% higher accuracy than the state-of-the-art baseline, while requiring 9 MFLOPs less computation. As the first work to accelerate ViT adaptation with low-rank backpropagation, our LBP-WHT method is complementary to many prior efforts and can be combined with them for better performance.

{{</citation>}}


### (24/115) GasMono: Geometry-Aided Self-Supervised Monocular Depth Estimation for Indoor Scenes (Chaoqiang Zhao et al., 2023)

{{<citation>}}

Chaoqiang Zhao, Matteo Poggi, Fabio Tosi, Lei Zhou, Qiyu Sun, Yang Tang, Stefano Mattoccia. (2023)  
**GasMono: Geometry-Aided Self-Supervised Monocular Depth Estimation for Indoor Scenes**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.16019v1)  

---


**ABSTRACT**  
This paper tackles the challenges of self-supervised monocular depth estimation in indoor scenes caused by large rotation between frames and low texture. We ease the learning process by obtaining coarse camera poses from monocular sequences through multi-view geometry to deal with the former. However, we found that limited by the scale ambiguity across different scenes in the training dataset, a na\"ive introduction of geometric coarse poses cannot play a positive role in performance improvement, which is counter-intuitive. To address this problem, we propose to refine those poses during training through rotation and translation/scale optimization. To soften the effect of the low texture, we combine the global reasoning of vision transformers with an overfitting-aware, iterative self-distillation mechanism, providing more accurate depth guidance coming from the network itself. Experiments on NYUv2, ScanNet, 7scenes, and KITTI datasets support the effectiveness of each component in our framework, which sets a new state-of-the-art for indoor self-supervised monocular depth estimation, as well as outstanding generalization ability. Code and models are available at https://github.com/zxcqlf/GasMono

{{</citation>}}


### (25/115) InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition (Pan Zhang et al., 2023)

{{<citation>}}

Pan Zhang, Xiaoyi Dong, Bin Wang, Yuhang Cao, Chao Xu, Linke Ouyang, Zhiyuan Zhao, Shuangrui Ding, Songyang Zhang, Haodong Duan, Hang Yan, Xinyue Zhang, Wei Li, Jingwen Li, Kai Chen, Conghui He, Xingcheng Zhang, Yu Qiao, Dahua Lin, Jiaqi Wang. (2023)  
**InternLM-XComposer: A Vision-Language Large Model for Advanced Text-image Comprehension and Composition**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Multilingual  
[Paper Link](http://arxiv.org/abs/2309.15112v3)  

---


**ABSTRACT**  
We propose InternLM-XComposer, a vision-language large model that enables advanced image-text comprehension and composition. The innovative nature of our model is highlighted by three appealing properties: 1) Interleaved Text-Image Composition: InternLM-XComposer can effortlessly generate coherent and contextual articles that seamlessly integrate images, providing a more engaging and immersive reading experience. Simply provide a title, and our system will generate the corresponding manuscript. It can intelligently identify the areas in the text where images would enhance the content and automatically insert the most appropriate visual candidates. 2) Comprehension with Rich Multilingual Knowledge: The text-image comprehension is empowered by training on extensive multi-modal multilingual concepts with carefully crafted strategies, resulting in a deep understanding of visual content. 3) State-of-the-art Performance: Our model consistently achieves state-of-the-art results across various mainstream benchmarks for vision-language foundational models, including MME Benchmark, MMBench, MMBench-CN, Seed-Bench, and CCBench (Chinese Cultural Benchmark). Collectively, InternLM-XComposer seamlessly blends advanced text-image comprehension and composition, revolutionizing vision-language interaction and offering new insights and opportunities. The InternLM-XComposer model series with 7B parameters are publicly available at https://github.com/InternLM/InternLM-XComposer.

{{</citation>}}


### (26/115) DistillBEV: Boosting Multi-Camera 3D Object Detection with Cross-Modal Knowledge Distillation (Zeyu Wang et al., 2023)

{{<citation>}}

Zeyu Wang, Dingwen Li, Chenxu Luo, Cihang Xie, Xiaodong Yang. (2023)  
**DistillBEV: Boosting Multi-Camera 3D Object Detection with Cross-Modal Knowledge Distillation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Knowledge Distillation, Object Detection  
[Paper Link](http://arxiv.org/abs/2309.15109v1)  

---


**ABSTRACT**  
3D perception based on the representations learned from multi-camera bird's-eye-view (BEV) is trending as cameras are cost-effective for mass production in autonomous driving industry. However, there exists a distinct performance gap between multi-camera BEV and LiDAR based 3D object detection. One key reason is that LiDAR captures accurate depth and other geometry measurements, while it is notoriously challenging to infer such 3D information from merely image input. In this work, we propose to boost the representation learning of a multi-camera BEV based student detector by training it to imitate the features of a well-trained LiDAR based teacher detector. We propose effective balancing strategy to enforce the student to focus on learning the crucial features from the teacher, and generalize knowledge transfer to multi-scale layers with temporal fusion. We conduct extensive evaluations on multiple representative models of multi-camera BEV. Experiments reveal that our approach renders significant improvement over the student models, leading to the state-of-the-art performance on the popular benchmark nuScenes.

{{</citation>}}


### (27/115) VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning (Han Lin et al., 2023)

{{<citation>}}

Han Lin, Abhay Zala, Jaemin Cho, Mohit Bansal. (2023)  
**VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2309.15091v1)  

---


**ABSTRACT**  
Although recent text-to-video (T2V) generation methods have seen significant advancements, most of these works focus on producing short video clips of a single event with a single background (i.e., single-scene videos). Meanwhile, recent large language models (LLMs) have demonstrated their capability in generating layouts and programs to control downstream visual modules such as image generation models. This raises an important question: can we leverage the knowledge embedded in these LLMs for temporally consistent long video generation? In this paper, we propose VideoDirectorGPT, a novel framework for consistent multi-scene video generation that uses the knowledge of LLMs for video content planning and grounded video generation. Specifically, given a single text prompt, we first ask our video planner LLM (GPT-4) to expand it into a 'video plan', which involves generating the scene descriptions, the entities with their respective layouts, the background for each scene, and consistency groupings of the entities and backgrounds. Next, guided by this output from the video planner, our video generator, Layout2Vid, has explicit control over spatial layouts and can maintain temporal consistency of entities/backgrounds across scenes, while only trained with image-level annotations. Our experiments demonstrate that VideoDirectorGPT framework substantially improves layout and movement control in both single- and multi-scene video generation and can generate multi-scene videos with visual consistency across scenes, while achieving competitive performance with SOTAs in open-domain single-scene T2V generation. We also demonstrate that our framework can dynamically control the strength for layout guidance and can also generate videos with user-provided images. We hope our framework can inspire future work on better integrating the planning ability of LLMs into consistent long video generation.

{{</citation>}}


### (28/115) The Surveillance AI Pipeline (Pratyusha Ria Kalluri et al., 2023)

{{<citation>}}

Pratyusha Ria Kalluri, William Agnew, Myra Cheng, Kentrell Owens, Luca Soldaini, Abeba Birhane. (2023)  
**The Surveillance AI Pipeline**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-CY, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15084v1)  

---


**ABSTRACT**  
A rapidly growing number of voices have argued that AI research, and computer vision in particular, is closely tied to mass surveillance. Yet the direct path from computer vision research to surveillance has remained obscured and difficult to assess. This study reveals the Surveillance AI pipeline. We obtain three decades of computer vision research papers and downstream patents (more than 20,000 documents) and present a rich qualitative and quantitative analysis. This analysis exposes the nature and extent of the Surveillance AI pipeline, its institutional roots and evolution, and ongoing patterns of obfuscation. We first perform an in-depth content analysis of computer vision papers and downstream patents, identifying and quantifying key features and the many, often subtly expressed, forms of surveillance that appear. On the basis of this analysis, we present a topology of Surveillance AI that characterizes the prevalent targeting of human data, practices of data transferal, and institutional data use. We find stark evidence of close ties between computer vision and surveillance. The majority (68%) of annotated computer vision papers and patents self-report their technology enables data extraction about human bodies and body parts and even more (90%) enable data extraction about humans in general.

{{</citation>}}


### (29/115) IFT: Image Fusion Transformer for Ghost-free High Dynamic Range Imaging (Hailing Wang et al., 2023)

{{<citation>}}

Hailing Wang, Wei Li, Yuanyuan Xi, Jie Hu, Hanting Chen, Longyu Li, Yunhe Wang. (2023)  
**IFT: Image Fusion Transformer for Ghost-free High Dynamic Range Imaging**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.15019v1)  

---


**ABSTRACT**  
Multi-frame high dynamic range (HDR) imaging aims to reconstruct ghost-free images with photo-realistic details from content-complementary but spatially misaligned low dynamic range (LDR) images. Existing HDR algorithms are prone to producing ghosting artifacts as their methods fail to capture long-range dependencies between LDR frames with large motion in dynamic scenes. To address this issue, we propose a novel image fusion transformer, referred to as IFT, which presents a fast global patch searching (FGPS) module followed by a self-cross fusion module (SCF) for ghost-free HDR imaging. The FGPS searches the patches from supporting frames that have the closest dependency to each patch of the reference frame for long-range dependency modeling, while the SCF conducts intra-frame and inter-frame feature fusion on the patches obtained by the FGPS with linear complexity to input resolution. By matching similar patches between frames, objects with large motion ranges in dynamic scenes can be aligned, which can effectively alleviate the generation of artifacts. In addition, the proposed FGPS and SCF can be integrated into various deep HDR methods as efficient plug-in modules. Extensive experiments on multiple benchmarks show that our method achieves state-of-the-art performance both quantitatively and qualitatively.

{{</citation>}}


### (30/115) Unidirectional brain-computer interface: Artificial neural network encoding natural images to fMRI response in the visual cortex (Ruixing Liang et al., 2023)

{{<citation>}}

Ruixing Liang, Xiangyu Zhang, Qiong Li, Lai Wei, Hexin Liu, Avisha Kumar, Kelley M. Kempski Leadingham, Joshua Punnoose, Leibny Paola Garcia, Amir Manbachi. (2023)  
**Unidirectional brain-computer interface: Artificial neural network encoding natural images to fMRI response in the visual cortex**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-HC, cs.CV, q-bio-NC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15018v1)  

---


**ABSTRACT**  
While significant advancements in artificial intelligence (AI) have catalyzed progress across various domains, its full potential in understanding visual perception remains underexplored. We propose an artificial neural network dubbed VISION, an acronym for "Visual Interface System for Imaging Output of Neural activity," to mimic the human brain and show how it can foster neuroscientific inquiries. Using visual and contextual inputs, this multimodal model predicts the brain's functional magnetic resonance imaging (fMRI) scan response to natural images. VISION successfully predicts human hemodynamic responses as fMRI voxel values to visual inputs with an accuracy exceeding state-of-the-art performance by 45%. We further probe the trained networks to reveal representational biases in different visual areas, generate experimentally testable hypotheses, and formulate an interpretable metric to associate these hypotheses with cortical functions. With both a model and evaluation metric, the cost and time burdens associated with designing and implementing functional analysis on the visual cortex could be reduced. Our work suggests that the evolution of computational models may shed light on our fundamental understanding of the visual cortex and provide a viable approach toward reliable brain-machine interfaces.

{{</citation>}}


### (31/115) IAIFNet: An Illumination-Aware Infrared and Visible Image Fusion Network (Qiao Yang et al., 2023)

{{<citation>}}

Qiao Yang, Yu Zhang, Jian Zhang, Zijing Zhao, Shunli Zhang, Jinqiao Wang, Junzhe Chen. (2023)  
**IAIFNet: An Illumination-Aware Infrared and Visible Image Fusion Network**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14997v1)  

---


**ABSTRACT**  
Infrared and visible image fusion (IVIF) is used to generate fusion images with comprehensive features of both images, which is beneficial for downstream vision tasks. However, current methods rarely consider the illumination condition in low-light environments, and the targets in the fused images are often not prominent. To address the above issues, we propose an Illumination-Aware Infrared and Visible Image Fusion Network, named as IAIFNet. In our framework, an illumination enhancement network first estimates the incident illumination maps of input images. Afterwards, with the help of proposed adaptive differential fusion module (ADFM) and salient target aware module (STAM), an image fusion network effectively integrates the salient features of the illumination-enhanced infrared and visible images into a fusion image of high visual quality. Extensive experimental results verify that our method outperforms five state-of-the-art methods of fusing infrared and visible images.

{{</citation>}}


### (32/115) Robust Sequential DeepFake Detection (Rui Shao et al., 2023)

{{<citation>}}

Rui Shao, Tianxing Wu, Ziwei Liu. (2023)  
**Robust Sequential DeepFake Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reasoning, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14991v1)  

---


**ABSTRACT**  
Since photorealistic faces can be readily generated by facial manipulation technologies nowadays, potential malicious abuse of these technologies has drawn great concerns. Numerous deepfake detection methods are thus proposed. However, existing methods only focus on detecting one-step facial manipulation. As the emergence of easy-accessible facial editing applications, people can easily manipulate facial components using multi-step operations in a sequential manner. This new threat requires us to detect a sequence of facial manipulations, which is vital for both detecting deepfake media and recovering original faces afterwards. Motivated by this observation, we emphasize the need and propose a novel research problem called Detecting Sequential DeepFake Manipulation (Seq-DeepFake). Unlike the existing deepfake detection task only demanding a binary label prediction, detecting Seq-DeepFake manipulation requires correctly predicting a sequential vector of facial manipulation operations. To support a large-scale investigation, we construct the first Seq-DeepFake dataset, where face images are manipulated sequentially with corresponding annotations of sequential facial manipulation vectors. Based on this new dataset, we cast detecting Seq-DeepFake manipulation as a specific image-to-sequence task and propose a concise yet effective Seq-DeepFake Transformer (SeqFakeFormer). To better reflect real-world deepfake data distributions, we further apply various perturbations on the original Seq-DeepFake dataset and construct the more challenging Sequential DeepFake dataset with perturbations (Seq-DeepFake-P). To exploit deeper correlation between images and sequences when facing Seq-DeepFake-P, a dedicated Seq-DeepFake Transformer with Image-Sequence Reasoning (SeqFakeFormer++) is devised, which builds stronger correspondence between image-sequence pairs for more robust Seq-DeepFake detection.

{{</citation>}}


### (33/115) MoCaE: Mixture of Calibrated Experts Significantly Improves Object Detection (Kemal Oksuz et al., 2023)

{{<citation>}}

Kemal Oksuz, Selim Kuzucu, Tom Joy, Puneet K. Dokania. (2023)  
**MoCaE: Mixture of Calibrated Experts Significantly Improves Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2309.14976v2)  

---


**ABSTRACT**  
We propose an extremely simple and highly effective approach to faithfully combine different object detectors to obtain a Mixture of Experts (MoE) that has a superior accuracy to the individual experts in the mixture. We find that naively combining these experts in a similar way to the well-known Deep Ensembles (DEs), does not result in an effective MoE. We identify the incompatibility between the confidence score distribution of different detectors to be the primary reason for such failure cases. Therefore, to construct the MoE, our proposal is to first calibrate each individual detector against a target calibration function. Then, filter and refine all the predictions from different detectors in the mixture. We term this approach as MoCaE and demonstrate its effectiveness through extensive experiments on object detection, instance segmentation and rotated object detection tasks. Specifically, MoCaE improves (i) three strong object detectors on COCO test-dev by $2.4$ $\mathrm{AP}$ by reaching $59.0$ $\mathrm{AP}$; (ii) instance segmentation methods on the challenging long-tailed LVIS dataset by $2.3$ $\mathrm{AP}$; and (iii) all existing rotated object detectors by reaching $82.62$ $\mathrm{AP_{50}}$ on DOTA dataset, establishing a new state-of-the-art (SOTA). Code will be made public.

{{</citation>}}


### (34/115) Multi-Source Domain Adaptation for Object Detection with Prototype-based Mean-teacher (Atif Belal et al., 2023)

{{<citation>}}

Atif Belal, Akhil Meethal, Francisco Perdigon Romero, Marco Pedersoli, Eric Granger. (2023)  
**Multi-Source Domain Adaptation for Object Detection with Prototype-based Mean-teacher**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2309.14950v1)  

---


**ABSTRACT**  
Adapting visual object detectors to operational target domains is a challenging task, commonly achieved using unsupervised domain adaptation (UDA) methods. When the labeled dataset is coming from multiple source domains, treating them as separate domains and performing a multi-source domain adaptation (MSDA) improves the accuracy and robustness over mixing these source domains and performing a UDA, as observed by recent studies in MSDA. Existing MSDA methods learn domain invariant and domain-specific parameters (for each source domain) for the adaptation. However, unlike single-source UDA methods, learning domain-specific parameters makes them grow significantly proportional to the number of source domains used. This paper proposes a novel MSDA method called Prototype-based Mean-Teacher (PMT), which uses class prototypes instead of domain-specific subnets to preserve domain-specific information. These prototypes are learned using a contrastive loss, aligning the same categories across domains and separating different categories far apart. Because of the use of prototypes, the parameter size of our method does not increase significantly with the number of source domains, thus reducing memory issues and possible overfitting. Empirical studies show PMT outperforms state-of-the-art MSDA methods on several challenging object detection datasets.

{{</citation>}}


### (35/115) Noise-Tolerant Unsupervised Adapter for Vision-Language Models (Eman Ali et al., 2023)

{{<citation>}}

Eman Ali, Dayan Guan, Shijian Lu, Abdulmotaleb Elsaddik. (2023)  
**Noise-Tolerant Unsupervised Adapter for Vision-Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14928v1)  

---


**ABSTRACT**  
Recent advances in large-scale vision-language models have achieved very impressive performance in various zero-shot image classification tasks. While prior studies have demonstrated significant improvements by introducing few-shot labelled target samples, they still require labelling of target samples, which greatly degrades their scalability while handling various visual recognition tasks. We design NtUA, a Noise-tolerant Unsupervised Adapter that allows learning superior target models with few-shot unlabelled target samples. NtUA works as a key-value cache that formulates visual features and predicted pseudo-labels of the few-shot unlabelled target samples as key-value pairs. It consists of two complementary designs. The first is adaptive cache formation that combats pseudo-label noises by weighting the key-value pairs according to their prediction confidence. The second is pseudo-label rectification, which corrects both pair values (i.e., pseudo-labels) and cache weights by leveraging knowledge distillation from large-scale vision language models. Extensive experiments show that NtUA achieves superior performance consistently across multiple widely adopted benchmarks.

{{</citation>}}


### (36/115) Pre-training-free Image Manipulation Localization through Non-Mutually Exclusive Contrastive Learning (Jizhe Zhou et al., 2023)

{{<citation>}}

Jizhe Zhou, Xiaochen Ma, Xia Du, Ahmed Y. Alhammadi, Wentao Feng. (2023)  
**Pre-training-free Image Manipulation Localization through Non-Mutually Exclusive Contrastive Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2309.14900v2)  

---


**ABSTRACT**  
Deep Image Manipulation Localization (IML) models suffer from training data insufficiency and thus heavily rely on pre-training. We argue that contrastive learning is more suitable to tackle the data insufficiency problem for IML. Crafting mutually exclusive positives and negatives is the prerequisite for contrastive learning. However, when adopting contrastive learning in IML, we encounter three categories of image patches: tampered, authentic, and contour patches. Tampered and authentic patches are naturally mutually exclusive, but contour patches containing both tampered and authentic pixels are non-mutually exclusive to them. Simply abnegating these contour patches results in a drastic performance loss since contour patches are decisive to the learning outcomes. Hence, we propose the Non-mutually exclusive Contrastive Learning (NCL) framework to rescue conventional contrastive learning from the above dilemma. In NCL, to cope with the non-mutually exclusivity, we first establish a pivot structure with dual branches to constantly switch the role of contour patches between positives and negatives while training. Then, we devise a pivot-consistent loss to avoid spatial corruption caused by the role-switching process. In this manner, NCL both inherits the self-supervised merits to address the data insufficiency and retains a high manipulation localization accuracy. Extensive experiments verify that our NCL achieves state-of-the-art performance on all five benchmarks without any pre-training and is more robust on unseen real-life samples. The code is available at: https://github.com/Knightzjz/NCL-IML.

{{</citation>}}


### (37/115) Nearest Neighbor Guidance for Out-of-Distribution Detection (Jaewoo Park et al., 2023)

{{<citation>}}

Jaewoo Park, Yoon Gyo Jung, Andrew Beng Jin Teoh. (2023)  
**Nearest Neighbor Guidance for Out-of-Distribution Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.14888v1)  

---


**ABSTRACT**  
Detecting out-of-distribution (OOD) samples are crucial for machine learning models deployed in open-world environments. Classifier-based scores are a standard approach for OOD detection due to their fine-grained detection capability. However, these scores often suffer from overconfidence issues, misclassifying OOD samples distant from the in-distribution region. To address this challenge, we propose a method called Nearest Neighbor Guidance (NNGuide) that guides the classifier-based score to respect the boundary geometry of the data manifold. NNGuide reduces the overconfidence of OOD samples while preserving the fine-grained capability of the classifier-based score. We conduct extensive experiments on ImageNet OOD detection benchmarks under diverse settings, including a scenario where the ID data undergoes natural distribution shift. Our results demonstrate that NNGuide provides a significant performance improvement on the base detection scores, achieving state-of-the-art results on both AUROC, FPR95, and AUPR metrics. The code is given at \url{https://github.com/roomo7time/nnguide}.

{{</citation>}}


### (38/115) Cross-Dataset-Robust Method for Blind Real-World Image Quality Assessment (Yuan Chen et al., 2023)

{{<citation>}}

Yuan Chen, Zhiliang Ma, Yang Zhao. (2023)  
**Cross-Dataset-Robust Method for Blind Real-World Image Quality Assessment**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV, eess-IV  
Keywords: QA, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14868v1)  

---


**ABSTRACT**  
Although many effective models and real-world datasets have been presented for blind image quality assessment (BIQA), recent BIQA models usually tend to fit specific training set. Hence, it is still difficult to accurately and robustly measure the visual quality of an arbitrary real-world image. In this paper, a robust BIQA method, is designed based on three aspects, i.e., robust training strategy, large-scale real-world dataset, and powerful backbone. First, many individual models based on popular and state-of-the-art (SOTA) Swin-Transformer (SwinT) are trained on different real-world BIQA datasets respectively. Then, these biased SwinT-based models are jointly used to generate pseudo-labels, which adopts the probability of relative quality of two random images instead of fixed quality score. A large-scale real-world image dataset with 1,000,000 image pairs and pseudo-labels is then proposed for training the final cross-dataset-robust model. Experimental results on cross-dataset tests show that the performance of the proposed method is even better than some SOTA methods that are directly trained on these datasets, thus verifying the robustness and generalization of our method.

{{</citation>}}


### (39/115) ADU-Depth: Attention-based Distillation with Uncertainty Modeling for Depth Estimation (Zizhang Wu et al., 2023)

{{<citation>}}

Zizhang Wu, Zhuozheng Li, Zhi-Gang Fan, Yunzhe Wu, Xiaoquan Wang, Rui Tang, Jian Pu. (2023)  
**ADU-Depth: Attention-based Distillation with Uncertainty Modeling for Depth Estimation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.14744v1)  

---


**ABSTRACT**  
Monocular depth estimation is challenging due to its inherent ambiguity and ill-posed nature, yet it is quite important to many applications. While recent works achieve limited accuracy by designing increasingly complicated networks to extract features with limited spatial geometric cues from a single RGB image, we intend to introduce spatial cues by training a teacher network that leverages left-right image pairs as inputs and transferring the learned 3D geometry-aware knowledge to the monocular student network. Specifically, we present a novel knowledge distillation framework, named ADU-Depth, with the goal of leveraging the well-trained teacher network to guide the learning of the student network, thus boosting the precise depth estimation with the help of extra spatial scene information. To enable domain adaptation and ensure effective and smooth knowledge transfer from teacher to student, we apply both attention-adapted feature distillation and focal-depth-adapted response distillation in the training stage. In addition, we explicitly model the uncertainty of depth estimation to guide distillation in both feature space and result space to better produce 3D-aware knowledge from monocular observations and thus enhance the learning for hard-to-predict image regions. Our extensive experiments on the real depth estimation datasets KITTI and DrivingStereo demonstrate the effectiveness of the proposed method, which ranked 1st on the challenging KITTI online benchmark.

{{</citation>}}


### (40/115) Explaining Deep Face Algorithms through Visualization: A Survey (Thrupthi Ann John et al., 2023)

{{<citation>}}

Thrupthi Ann John, Vineeth N Balasubramanian, C. V. Jawahar. (2023)  
**Explaining Deep Face Algorithms through Visualization: A Survey**  

---
Primary Category: cs.CV  
Categories: I-2-10; I-4-10; I-5-1, cs-CV, cs-HC, cs-LG, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14715v1)  

---


**ABSTRACT**  
Although current deep models for face tasks surpass human performance on some benchmarks, we do not understand how they work. Thus, we cannot predict how it will react to novel inputs, resulting in catastrophic failures and unwanted biases in the algorithms. Explainable AI helps bridge the gap, but currently, there are very few visualization algorithms designed for faces. This work undertakes a first-of-its-kind meta-analysis of explainability algorithms in the face domain. We explore the nuances and caveats of adapting general-purpose visualization algorithms to the face domain, illustrated by computing visualizations on popular face models. We review existing face explainability works and reveal valuable insights into the structure and hierarchy of face networks. We also determine the design considerations for practical face visualizations accessible to AI practitioners by conducting a user study on the utility of various explainability algorithms.

{{</citation>}}


### (41/115) Tile Classification Based Viewport Prediction with Multi-modal Fusion Transformer (Zhihao Zhang et al., 2023)

{{<citation>}}

Zhihao Zhang, Yiwei Chen, Weizhan Zhang, Caixia Yan, Qinghua Zheng, Qi Wang, Wangdu Chen. (2023)  
**Tile Classification Based Viewport Prediction with Multi-modal Fusion Transformer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14704v2)  

---


**ABSTRACT**  
Viewport prediction is a crucial aspect of tile-based 360 video streaming system. However, existing trajectory based methods lack of robustness, also oversimplify the process of information construction and fusion between different modality inputs, leading to the error accumulation problem. In this paper, we propose a tile classification based viewport prediction method with Multi-modal Fusion Transformer, namely MFTR. Specifically, MFTR utilizes transformer-based networks to extract the long-range dependencies within each modality, then mine intra- and inter-modality relations to capture the combined impact of user historical inputs and video contents on future viewport selection. In addition, MFTR categorizes future tiles into two categories: user interested or not, and selects future viewport as the region that contains most user interested tiles. Comparing with predicting head trajectories, choosing future viewport based on tile's binary classification results exhibits better robustness and interpretability. To evaluate our proposed MFTR, we conduct extensive experiments on two widely used PVS-HM and Xu-Gaze dataset. MFTR shows superior performance over state-of-the-art methods in terms of average prediction accuracy and overlap ratio, also presents competitive computation efficiency.

{{</citation>}}


### (42/115) Structure Invariant Transformation for better Adversarial Transferability (Xiaosen Wang et al., 2023)

{{<citation>}}

Xiaosen Wang, Zeliang Zhang, Jianping Zhang. (2023)  
**Structure Invariant Transformation for better Adversarial Transferability**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2309.14700v1)  

---


**ABSTRACT**  
Given the severe vulnerability of Deep Neural Networks (DNNs) against adversarial examples, there is an urgent need for an effective adversarial attack to identify the deficiencies of DNNs in security-sensitive applications. As one of the prevalent black-box adversarial attacks, the existing transfer-based attacks still cannot achieve comparable performance with the white-box attacks. Among these, input transformation based attacks have shown remarkable effectiveness in boosting transferability. In this work, we find that the existing input transformation based attacks transform the input image globally, resulting in limited diversity of the transformed images. We postulate that the more diverse transformed images result in better transferability. Thus, we investigate how to locally apply various transformations onto the input image to improve such diversity while preserving the structure of image. To this end, we propose a novel input transformation based attack, called Structure Invariant Attack (SIA), which applies a random image transformation onto each image block to craft a set of diverse images for gradient calculation. Extensive experiments on the standard ImageNet dataset demonstrate that SIA exhibits much better transferability than the existing SOTA input transformation based attacks on CNN-based and transformer-based models, showing its generality and superiority in boosting transferability. Code is available at https://github.com/xiaosen-wang/SIT.

{{</citation>}}


### (43/115) A Simple Text to Video Model via Transformer (Gang Chen, 2023)

{{<citation>}}

Gang Chen. (2023)  
**A Simple Text to Video Model via Transformer**  

---
Primary Category: cs.CV  
Categories: 68T10, I-2-6, cs-CL, cs-CV, cs.CV  
Keywords: GPT, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14683v1)  

---


**ABSTRACT**  
We present a general and simple text to video model based on Transformer. Since both text and video are sequential data, we encode both texts and images into the same hidden space, which are further fed into Transformer to capture the temporal consistency and then decoder to generate either text or images. Considering the image signal may become weak in the long sequence, we introduce the U-Net to reconstruct image from its noised version. Specifically, we increase the noise level to the original image in the long sequence, then use the $down$ module from U-Net to encode noised images, which are further input to transformer to predict next clear images. We also add a constraint to promote motion between any generated image pair in the video. We use GPT2 and test our approach on UCF101 dataset and show it can generate promising videos.

{{</citation>}}


### (44/115) ZiCo-BC: A Bias Corrected Zero-Shot NAS for Vision Tasks (Kartikeya Bhardwaj et al., 2023)

{{<citation>}}

Kartikeya Bhardwaj, Hsin-Pai Cheng, Sweta Priyadarshi, Zhuojin Li. (2023)  
**ZiCo-BC: A Bias Corrected Zero-Shot NAS for Vision Tasks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Bias, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2309.14666v1)  

---


**ABSTRACT**  
Zero-Shot Neural Architecture Search (NAS) approaches propose novel training-free metrics called zero-shot proxies to substantially reduce the search time compared to the traditional training-based NAS. Despite the success on image classification, the effectiveness of zero-shot proxies is rarely evaluated on complex vision tasks such as semantic segmentation and object detection. Moreover, existing zero-shot proxies are shown to be biased towards certain model characteristics which restricts their broad applicability. In this paper, we empirically study the bias of state-of-the-art (SOTA) zero-shot proxy ZiCo across multiple vision tasks and observe that ZiCo is biased towards thinner and deeper networks, leading to sub-optimal architectures. To solve the problem, we propose a novel bias correction on ZiCo, called ZiCo-BC. Our extensive experiments across various vision tasks (image classification, object detection and semantic segmentation) show that our approach can successfully search for architectures with higher accuracy and significantly lower latency on Samsung Galaxy S10 devices.

{{</citation>}}


### (45/115) Divide and Conquer in Video Anomaly Detection: A Comprehensive Review and New Approach (Jian Xiao et al., 2023)

{{<citation>}}

Jian Xiao, Tianyuan Liu, Genlin Ji. (2023)  
**Divide and Conquer in Video Anomaly Detection: A Comprehensive Review and New Approach**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2309.14622v1)  

---


**ABSTRACT**  
Video anomaly detection is a complex task, and the principle of "divide and conquer" is often regarded as an effective approach to tackling intricate issues. It's noteworthy that recent methods in video anomaly detection have revealed the application of the divide and conquer philosophy (albeit with distinct perspectives from traditional usage), yielding impressive outcomes. This paper systematically reviews these literatures from six dimensions, aiming to enhance the use of the divide and conquer strategy in video anomaly detection. Furthermore, based on the insights gained from this review, a novel approach is presented, which integrates human skeletal frameworks with video data analysis techniques. This method achieves state-of-the-art performance on the ShanghaiTech dataset, surpassing all existing advanced methods.

{{</citation>}}


### (46/115) Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline (Xiao Wang et al., 2023)

{{<citation>}}

Xiao Wang, Shiao Wang, Chuanming Tang, Lin Zhu, Bo Jiang, Yonghong Tian, Jin Tang. (2023)  
**Event Stream-based Visual Object Tracking: A High-Resolution Benchmark Dataset and A Novel Baseline**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-NE, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14611v1)  

---


**ABSTRACT**  
Tracking using bio-inspired event cameras has drawn more and more attention in recent years. Existing works either utilize aligned RGB and event data for accurate tracking or directly learn an event-based tracker. The first category needs more cost for inference and the second one may be easily influenced by noisy events or sparse spatial resolution. In this paper, we propose a novel hierarchical knowledge distillation framework that can fully utilize multi-modal / multi-view information during training to facilitate knowledge transfer, enabling us to achieve high-speed and low-latency visual tracking during testing by using only event signals. Specifically, a teacher Transformer-based multi-modal tracking framework is first trained by feeding the RGB frame and event stream simultaneously. Then, we design a new hierarchical knowledge distillation strategy which includes pairwise similarity, feature representation, and response maps-based knowledge distillation to guide the learning of the student Transformer network. Moreover, since existing event-based tracking datasets are all low-resolution ($346 \times 260$), we propose the first large-scale high-resolution ($1280 \times 720$) dataset named EventVOT. It contains 1141 videos and covers a wide range of categories such as pedestrians, vehicles, UAVs, ping pongs, etc. Extensive experiments on both low-resolution (FE240hz, VisEvent, COESOT), and our newly proposed high-resolution EventVOT dataset fully validated the effectiveness of our proposed method. The dataset, evaluation toolkit, and source code are available on \url{https://github.com/Event-AHU/EventVOT_Benchmark}

{{</citation>}}


## cs.RO (10)



### (47/115) Self-Supervised Terrain Representation Learning from Unconstrained Robot Experience (Haresh Karnan et al., 2023)

{{<citation>}}

Haresh Karnan, Elvin Yang, Daniel Farkash, Garrett Warnell, Joydeep Biswas, Peter Stone. (2023)  
**Self-Supervised Terrain Representation Learning from Unconstrained Robot Experience**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-CV, cs-LG, cs-RO, cs.RO  
Keywords: Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.15302v1)  

---


**ABSTRACT**  
Terrain awareness, i.e., the ability to identify and distinguish different types of terrain, is a critical ability that robots must have to succeed at autonomous off-road navigation. Current approaches that provide robots with this awareness either rely on labeled data which is expensive to collect, engineered features and cost functions that may not generalize, or expert human demonstrations which may not be available. Towards endowing robots with terrain awareness without these limitations, we introduce Self-supervised TErrain Representation LearnING (STERLING), a novel approach for learning terrain representations that relies solely on easy-to-collect, unconstrained (e.g., non-expert), and unlabelled robot experience, with no additional constraints on data collection. STERLING employs a novel multi-modal self-supervision objective through non-contrastive representation learning to learn relevant terrain representations for terrain-aware navigation. Through physical robot experiments in off-road environments, we evaluate STERLING features on the task of preference-aligned visual navigation and find that STERLING features perform on par with fully supervised approaches and outperform other state-of-the-art methods with respect to preference alignment. Additionally, we perform a large-scale experiment of autonomously hiking a 3-mile long trail which STERLING completes successfully with only two manual interventions, demonstrating its robustness to real-world off-road conditions.

{{</citation>}}


### (48/115) Out of Sight, Still in Mind: Reasoning and Planning about Unobserved Objects with Video Tracking Enabled Memory Models (Yixuan Huang et al., 2023)

{{<citation>}}

Yixuan Huang, Jialin Yuan, Chanho Kim, Pupul Pradhan, Bryan Chen, Li Fuxin, Tucker Hermans. (2023)  
**Out of Sight, Still in Mind: Reasoning and Planning about Unobserved Objects with Video Tracking Enabled Memory Models**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-CV, cs-LG, cs-RO, cs.RO  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2309.15278v1)  

---


**ABSTRACT**  
Robots need to have a memory of previously observed, but currently occluded objects to work reliably in realistic environments. We investigate the problem of encoding object-oriented memory into a multi-object manipulation reasoning and planning framework. We propose DOOM and LOOM, which leverage transformer relational dynamics to encode the history of trajectories given partial-view point clouds and an object discovery and tracking engine. Our approaches can perform multiple challenging tasks including reasoning with occluded objects, novel objects appearance, and object reappearance. Throughout our extensive simulation and real-world experiments, we find that our approaches perform well in terms of different numbers of objects and different numbers of distractor actions. Furthermore, we show our approaches outperform an implicit memory baseline.

{{</citation>}}


### (49/115) Zero-Shot Constrained Motion Planning Transformers Using Learned Sampling Dictionaries (Jacob J. Johnson et al., 2023)

{{<citation>}}

Jacob J. Johnson, Ahmed H. Qureshi, Michael C. Yip. (2023)  
**Zero-Shot Constrained Motion Planning Transformers Using Learned Sampling Dictionaries**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Transformer, Transformers, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2309.15272v1)  

---


**ABSTRACT**  
Constrained robot motion planning is a ubiquitous need for robots interacting with everyday environments, but it is a notoriously difficult problem to solve. Many sampled points in a sample-based planner need to be rejected as they fall outside the constraint manifold, or require significant iterative effort to correct. Given this, few solutions exist that present a constraint-satisfying trajectory for robots, in reasonable time and of low path cost. In this work, we present a transformer-based model for motion planning with task space constraints for manipulation systems. Vector Quantized-Motion Planning Transformer (VQ-MPT) is a recent learning-based model that reduces the search space for unconstrained planning for sampling-based motion planners. We propose to adapt a pre-trained VQ-MPT model to reduce the search space for constraint planning without retraining or finetuning the model. We also propose to update the neural network output to move sampling regions closer to the constraint manifold. Our experiments show how VQ-MPT improves planning times and accuracy compared to traditional planners in simulated and real-world environments. Unlike previous learning methods, which require task-related data, our method uses pre-trained neural network models and requires no additional data for training and finetuning the model making this a \textit{one-shot} process. We also tested our method on a physical Franka Panda robot with real-world sensor data, demonstrating the generalizability of our algorithm. We anticipate this approach to be an accessible and broadly useful for transferring learned neural planners to various robotic-environment interaction scenarios.

{{</citation>}}


### (50/115) Multi-Robot Cooperative Socially-Aware Navigation Using Multi-Agent Reinforcement Learning (Weizheng Wang et al., 2023)

{{<citation>}}

Weizheng Wang, Le Mao, Ruiqi Wang, Byung-Cheol Min. (2023)  
**Multi-Robot Cooperative Socially-Aware Navigation Using Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.15234v1)  

---


**ABSTRACT**  
In public spaces shared with humans, ensuring multi-robot systems navigate without collisions while respecting social norms is challenging, particularly with limited communication. Although current robot social navigation techniques leverage advances in reinforcement learning and deep learning, they frequently overlook robot dynamics in simulations, leading to a simulation-to-reality gap. In this paper, we bridge this gap by presenting a new multi-robot social navigation environment crafted using Dec-POSMDP and multi-agent reinforcement learning. Furthermore, we introduce SAMARL: a novel benchmark for cooperative multi-robot social navigation. SAMARL employs a unique spatial-temporal transformer combined with multi-agent reinforcement learning. This approach effectively captures the complex interactions between robots and humans, thus promoting cooperative tendencies in multi-robot systems. Our extensive experiments reveal that SAMARL outperforms existing baseline and ablation models in our designed environment. Demo videos for this work can be found at: https://sites.google.com/view/samarl

{{</citation>}}


### (51/115) Language-EXtended Indoor SLAM (LEXIS): A Versatile System for Real-time Visual Scene Understanding (Christina Kassab et al., 2023)

{{<citation>}}

Christina Kassab, Matias Mattamala, Lintong Zhang, Maurice Fallon. (2023)  
**Language-EXtended Indoor SLAM (LEXIS): A Versatile System for Real-time Visual Scene Understanding**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO, eess-IV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.15065v1)  

---


**ABSTRACT**  
Versatile and adaptive semantic understanding would enable autonomous systems to comprehend and interact with their surroundings. Existing fixed-class models limit the adaptability of indoor mobile and assistive autonomous systems. In this work, we introduce LEXIS, a real-time indoor Simultaneous Localization and Mapping (SLAM) system that harnesses the open-vocabulary nature of Large Language Models (LLMs) to create a unified approach to scene understanding and place recognition. The approach first builds a topological SLAM graph of the environment (using visual-inertial odometry) and embeds Contrastive Language-Image Pretraining (CLIP) features in the graph nodes. We use this representation for flexible room classification and segmentation, serving as a basis for room-centric place recognition. This allows loop closure searches to be directed towards semantically relevant places. Our proposed system is evaluated using both public, simulated data and real-world data, covering office and home environments. It successfully categorizes rooms with varying layouts and dimensions and outperforms the state-of-the-art (SOTA). For place recognition and trajectory estimation tasks we achieve equivalent performance to the SOTA, all also utilizing the same pre-trained model. Lastly, we demonstrate the system's potential for planning.

{{</citation>}}


### (52/115) When Prolog meets generative models: a new approach for managing knowledge and planning in robotic applications (Enrico Saccon et al., 2023)

{{<citation>}}

Enrico Saccon, Ahmet Tikna, Davide De Martini, Edoardo Lamon, Marco Roveri, Luigi Palopoli. (2023)  
**When Prolog meets generative models: a new approach for managing knowledge and planning in robotic applications**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.15049v1)  

---


**ABSTRACT**  
In this paper, we propose a robot oriented knowledge management system based on the use of the Prolog language. Our framework hinges on a special organisation of knowledge base that enables: 1. its efficient population from natural language texts using semi-automated procedures based on Large Language Models, 2. the bumpless generation of temporal parallel plans for multi-robot systems through a sequence of transformations, 3. the automated translation of the plan into an executable formalism (the behaviour trees). The framework is supported by a set of open source tools and is shown on a realistic application.

{{</citation>}}


### (53/115) Integration of Large Language Models within Cognitive Architectures for Autonomous Robots (Miguel Á. González-Santamarta et al., 2023)

{{<citation>}}

Miguel Á. González-Santamarta, Francisco J. Rodríguez-Lera, Ángel Manuel Guerrero-Higueras, Vicente Matellán-Olivera. (2023)  
**Integration of Large Language Models within Cognitive Architectures for Autonomous Robots**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14945v1)  

---


**ABSTRACT**  
The usage of Large Language Models (LLMs) has increased recently, not only due to the significant improvements in their accuracy but also because of the use of the quantization that allows running these models without intense hardware requirements. As a result, the LLMs have proliferated. It implies the creation of a great variety of LLMs with different capabilities. This way, this paper proposes the integration of LLMs in cognitive architectures for autonomous robots. Specifically, we present the design, development and deployment of the llama\_ros tool that allows the easy use and integration of LLMs in ROS 2-based environments, afterward integrated with the state-of-the-art cognitive architecture MERLIN2 for updating a PDDL-based planner system. This proposal is evaluated quantitatively and qualitatively, measuring the impact of incorporating the LLMs in the cognitive architecture.

{{</citation>}}


### (54/115) Graph Neural Network Based Method for Path Planning Problem (Xingrong Diao et al., 2023)

{{<citation>}}

Xingrong Diao, Wenzheng Chi, Jiankun Wang. (2023)  
**Graph Neural Network Based Method for Path Planning Problem**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.14845v1)  

---


**ABSTRACT**  
Sampling-based path planning is a widely used method in robotics, particularly in high-dimensional state space. Among the whole process of the path planning, collision detection is the most time-consuming operation. In this paper, we propose a learning-based path planning method that aims to reduce the number of collision detection. We develop an efficient neural network model based on Graph Neural Networks (GNN) and use the environment map as input. The model outputs weights for each neighbor based on the input and current vertex information, which are used to guide the planner in avoiding obstacles. We evaluate the proposed method's efficiency through simulated random worlds and real-world experiments, respectively. The results demonstrate that the proposed method significantly reduces the number of collision detection and improves the path planning speed in high-dimensional environments.

{{</citation>}}


### (55/115) Realtime Motion Generation with Active Perception Using Attention Mechanism for Cooking Robot (Namiko Saito et al., 2023)

{{<citation>}}

Namiko Saito, Mayu Hiramoto, Ayuna Kubo, Kanata Suzuki, Hiroshi Ito, Shigeki Sugano, Tetsuya Ogata. (2023)  
**Realtime Motion Generation with Active Perception Using Attention Mechanism for Cooking Robot**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs.RO  
Keywords: AI, Attention  
[Paper Link](http://arxiv.org/abs/2309.14837v1)  

---


**ABSTRACT**  
To support humans in their daily lives, robots are required to autonomously learn, adapt to objects and environments, and perform the appropriate actions. We tackled on the task of cooking scrambled eggs using real ingredients, in which the robot needs to perceive the states of the egg and adjust stirring movement in real time, while the egg is heated and the state changes continuously. In previous works, handling changing objects was found to be challenging because sensory information includes dynamical, both important or noisy information, and the modality which should be focused on changes every time, making it difficult to realize both perception and motion generation in real time. We propose a predictive recurrent neural network with an attention mechanism that can weigh the sensor input, distinguishing how important and reliable each modality is, that realize quick and efficient perception and motion generation. The model is trained with learning from the demonstration, and allows the robot to acquire human-like skills. We validated the proposed technique using the robot, Dry-AIREC, and with our learning model, it could perform cooking eggs with unknown ingredients. The robot could change the method of stirring and direction depending on the status of the egg, as in the beginning it stirs in the whole pot, then subsequently, after the egg started being heated, it starts flipping and splitting motion targeting specific areas, although we did not explicitly indicate them.

{{</citation>}}


### (56/115) Less Is More: Robust Robot Learning via Partially Observable Multi-Agent Reinforcement Learning (Wenshuai Zhao et al., 2023)

{{<citation>}}

Wenshuai Zhao, Eetu-Aleksi Rantala, Joni Pajarinen, Jorge Peña Queralta. (2023)  
**Less Is More: Robust Robot Learning via Partially Observable Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14792v1)  

---


**ABSTRACT**  
In many multi-agent and high-dimensional robotic tasks, the controller can be designed in either a centralized or decentralized way. Correspondingly, it is possible to use either single-agent reinforcement learning (SARL) or multi-agent reinforcement learning (MARL) methods to learn such controllers. However, the relationship between these two paradigms remains under-studied in the literature. This work explores research questions in terms of robustness and performance of SARL and MARL approaches to the same task, in order to gain insight into the most suitable methods. We start by analytically showing the equivalence between these two paradigms under the full-state observation assumption. Then, we identify a broad subclass of \textit{Dec-POMDP} tasks where the agents are weakly or partially interacting. In these tasks, we show that partial observations of each agent are sufficient for near-optimal decision-making. Furthermore, we propose to exploit such partially observable MARL to improve the robustness of robots when joint or agent failures occur. Our experiments on both simulated multi-agent tasks and a real robot task with a mobile manipulator validate the presented insights and the effectiveness of the proposed robust robot learning method via partially observable MARL.

{{</citation>}}


## cs.LG (22)



### (57/115) Maximum Diffusion Reinforcement Learning (Thomas A. Berrueta et al., 2023)

{{<citation>}}

Thomas A. Berrueta, Allison Pinosky, Todd D. Murphey. (2023)  
**Maximum Diffusion Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cond-mat-stat-mech, cs-AI, cs-LG, cs-RO, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.15293v2)  

---


**ABSTRACT**  
The assumption that data are independent and identically distributed underpins all machine learning. When data are collected sequentially from agent experiences this assumption does not generally hold, as in reinforcement learning. Here, we derive a method that overcomes these limitations by exploiting the statistical mechanics of ergodic processes, which we term maximum diffusion reinforcement learning. By decorrelating agent experiences, our approach provably enables agents to learn continually in single-shot deployments regardless of how they are initialized. Moreover, we prove our approach generalizes well-known maximum entropy techniques, and show that it robustly exceeds state-of-the-art performance across popular benchmarks. Our results at the nexus of physics, learning, and control pave the way towards more transparent and reliable decision-making in reinforcement learning agents, such as locomoting robots and self-driving cars.

{{</citation>}}


### (58/115) Scaling Representation Learning from Ubiquitous ECG with State-Space Models (Kleanthis Avramidis et al., 2023)

{{<citation>}}

Kleanthis Avramidis, Dominika Kunc, Bartosz Perz, Kranti Adsul, Tiantian Feng, Przemysław Kazienko, Stanisław Saganowski, Shrikanth Narayanan. (2023)  
**Scaling Representation Learning from Ubiquitous ECG with State-Space Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, eess-SP  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2309.15292v1)  

---


**ABSTRACT**  
Ubiquitous sensing from wearable devices in the wild holds promise for enhancing human well-being, from diagnosing clinical conditions and measuring stress to building adaptive health promoting scaffolds. But the large volumes of data therein across heterogeneous contexts pose challenges for conventional supervised learning approaches. Representation Learning from biological signals is an emerging realm catalyzed by the recent advances in computational modeling and the abundance of publicly shared databases. The electrocardiogram (ECG) is the primary researched modality in this context, with applications in health monitoring, stress and affect estimation. Yet, most studies are limited by small-scale controlled data collection and over-parameterized architecture choices. We introduce \textbf{WildECG}, a pre-trained state-space model for representation learning from ECG signals. We train this model in a self-supervised manner with 275,000 10s ECG recordings collected in the wild and evaluate it on a range of downstream tasks. The proposed model is a robust backbone for ECG analysis, providing competitive performance on most of the tasks considered, while demonstrating efficacy in low-resource regimes. The code and pre-trained weights are shared publicly at https://github.com/klean2050/tiles_ecg_model.

{{</citation>}}


### (59/115) A Physics Enhanced Residual Learning (PERL) Framework for Traffic State Prediction (Keke Long et al., 2023)

{{<citation>}}

Keke Long, Haotian Shi, Zihao Sheng, Xiaopeng Li, Sikai Chen. (2023)  
**A Physics Enhanced Residual Learning (PERL) Framework for Traffic State Prediction**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2309.15284v1)  

---


**ABSTRACT**  
In vehicle trajectory prediction, physics models and data-driven models are two predominant methodologies. However, each approach presents its own set of challenges: physics models fall short in predictability, while data-driven models lack interpretability. Addressing these identified shortcomings, this paper proposes a novel framework, the Physics-Enhanced Residual Learning (PERL) model. PERL integrates the strengths of physics-based and data-driven methods for traffic state prediction. PERL contains a physics model and a residual learning model. Its prediction is the sum of the physics model result and a predicted residual as a correction to it. It preserves the interpretability inherent to physics-based models and has reduced data requirements compared to data-driven methods. Experiments were conducted using a real-world vehicle trajectory dataset. We proposed a PERL model, with the Intelligent Driver Model (IDM) as its physics car-following model and Long Short-Term Memory (LSTM) as its residual learning model. We compare this PERL model with the physics car-following model, data-driven model, and other physics-informed neural network (PINN) models. The result reveals that PERL achieves better prediction with a small dataset, compared to the physics model, data-driven model, and PINN model. Second, the PERL model showed faster convergence during training, offering comparable performance with fewer training samples than the data-driven model and PINN model. Sensitivity analysis also proves comparable performance of PERL using another residual learning model and a physics car-following model.

{{</citation>}}


### (60/115) Auto-grading C programming assignments with CodeBERT and Random Forest Regressor (Roshan Vasu Muddaluru et al., 2023)

{{<citation>}}

Roshan Vasu Muddaluru, Sharvaani Ravikumar Thoguluva, Shruti Prabha, Dr. Peeta Basa Pati, Ms. Roshni M Balakrishnan. (2023)  
**Auto-grading C programming assignments with CodeBERT and Random Forest Regressor**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: BERT, LSTM  
[Paper Link](http://arxiv.org/abs/2309.15216v1)  

---


**ABSTRACT**  
Grading coding assignments manually is challenging due to complexity and subjectivity. However, auto-grading with deep learning simplifies the task. It objectively assesses code quality, detects errors, and assigns marks accurately, reducing the burden on instructors while ensuring efficient and fair assessment. This study provides an analysis of auto-grading of the C programming assignments using machine learning and deep learning approaches like regression, convolutional neural networks (CNN) and long short-term memory (LSTM). Using a code-based transformer word embedding model called CodeBERT, the textual code inputs were transformed into vectors, and the vectors were then fed into several models. The testing findings demonstrated the efficacy of the suggested strategy with a root mean squared error (RMSE) of 1.89. The contrast between statistical methods and deep learning techniques is discussed in the study.

{{</citation>}}


### (61/115) Balancing Computational Efficiency and Forecast Error in Machine Learning-based Time-Series Forecasting: Insights from Live Experiments on Meteorological Nowcasting (Elin Törnquist et al., 2023)

{{<citation>}}

Elin Törnquist, Wagner Costa Santos, Timothy Pogue, Nicholas Wingle, Robert A. Caulk. (2023)  
**Balancing Computational Efficiency and Forecast Error in Machine Learning-based Time-Series Forecasting: Insights from Live Experiments on Meteorological Nowcasting**  

---
Primary Category: cs.LG  
Categories: I-2; J-2, cs-LG, cs.LG  
Keywords: LSTM, Transformer  
[Paper Link](http://arxiv.org/abs/2309.15207v1)  

---


**ABSTRACT**  
Machine learning for time-series forecasting remains a key area of research. Despite successful application of many machine learning techniques, relating computational efficiency to forecast error remains an under-explored domain. This paper addresses this topic through a series of real-time experiments to quantify the relationship between computational cost and forecast error using meteorological nowcasting as an example use-case. We employ a variety of popular regression techniques (XGBoost, FC-MLP, Transformer, and LSTM) for multi-horizon, short-term forecasting of three variables (temperature, wind speed, and cloud cover) for multiple locations. During a 5-day live experiment, 4000 data sources were streamed for training and inferencing 144 models per hour. These models were parameterized to explore forecast error for two computational cost minimization methods: a novel auto-adaptive data reduction technique (Variance Horizon) and a performance-based concept drift-detection mechanism. Forecast error of all model variations were benchmarked in real-time against a state-of-the-art numerical weather prediction model. Performance was assessed using classical and novel evaluation metrics. Results indicate that using the Variance Horizon reduced computational usage by more than 50\%, while increasing between 0-15\% in error. Meanwhile, performance-based retraining reduced computational usage by up to 90\% while \emph{also} improving forecast error by up to 10\%. Finally, the combination of both the Variance Horizon and performance-based retraining outperformed other model configurations by up to 99.7\% when considering error normalized to computational usage.

{{</citation>}}


### (62/115) Revealing the Power of Spatial-Temporal Masked Autoencoders in Multivariate Time Series Forecasting (Jiarui Sun et al., 2023)

{{<citation>}}

Jiarui Sun, Yujie Fan, Chin-Chia Michael Yeh, Wei Zhang, Girish Chowdhary. (2023)  
**Revealing the Power of Spatial-Temporal Masked Autoencoders in Multivariate Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2309.15169v1)  

---


**ABSTRACT**  
Multivariate time series (MTS) forecasting involves predicting future time series data based on historical observations. Existing research primarily emphasizes the development of complex spatial-temporal models that capture spatial dependencies and temporal correlations among time series variables explicitly. However, recent advances have been impeded by challenges relating to data scarcity and model robustness. To address these issues, we propose Spatial-Temporal Masked Autoencoders (STMAE), an MTS forecasting framework that leverages masked autoencoders to enhance the performance of spatial-temporal baseline models. STMAE consists of two learning stages. In the pretraining stage, an encoder-decoder architecture is employed. The encoder processes the partially visible MTS data produced by a novel dual-masking strategy, including biased random walk-based spatial masking and patch-based temporal masking. Subsequently, the decoders aim to reconstruct the masked counterparts from both spatial and temporal perspectives. The pretraining stage establishes a challenging pretext task, compelling the encoder to learn robust spatial-temporal patterns. In the fine-tuning stage, the pretrained encoder is retained, and the original decoder from existing spatial-temporal models is appended for forecasting. Extensive experiments are conducted on multiple MTS benchmarks. The promising results demonstrate that integrating STMAE into various spatial-temporal models can largely enhance their MTS forecasting capability.

{{</citation>}}


### (63/115) A Review on AI Algorithms for Energy Management in E-Mobility Services (Sen Yan et al., 2023)

{{<citation>}}

Sen Yan, Maqsood Hussain Shah, Ji Li, Noel O'Connor, Mingming Liu. (2023)  
**A Review on AI Algorithms for Energy Management in E-Mobility Services**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SY, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15140v1)  

---


**ABSTRACT**  
E-mobility, or electric mobility, has emerged as a pivotal solution to address pressing environmental and sustainability concerns in the transportation sector. The depletion of fossil fuels, escalating greenhouse gas emissions, and the imperative to combat climate change underscore the significance of transitioning to electric vehicles (EVs). This paper seeks to explore the potential of artificial intelligence (AI) in addressing various challenges related to effective energy management in e-mobility systems (EMS). These challenges encompass critical factors such as range anxiety, charge rate optimization, and the longevity of energy storage in EVs. By analyzing existing literature, we delve into the role that AI can play in tackling these challenges and enabling efficient energy management in EMS. Our objectives are twofold: to provide an overview of the current state-of-the-art in this research domain and propose effective avenues for future investigations. Through this analysis, we aim to contribute to the advancement of sustainable and efficient e-mobility solutions, shaping a greener and more sustainable future for transportation.

{{</citation>}}


### (64/115) Combining Survival Analysis and Machine Learning for Mass Cancer Risk Prediction using EHR data (Petr Philonenko et al., 2023)

{{<citation>}}

Petr Philonenko, Vladimir Kokh, Pavel Blinov. (2023)  
**Combining Survival Analysis and Machine Learning for Mass Cancer Risk Prediction using EHR data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-AP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15039v1)  

---


**ABSTRACT**  
Purely medical cancer screening methods are often costly, time-consuming, and weakly applicable on a large scale. Advanced Artificial Intelligence (AI) methods greatly help cancer detection but require specific or deep medical data. These aspects affect the mass implementation of cancer screening methods. For these reasons, it is a disruptive change for healthcare to apply AI methods for mass personalized assessment of the cancer risk among patients based on the existing Electronic Health Records (EHR) volume.   This paper presents a novel method for mass cancer risk prediction using EHR data. Among other methods, our one stands out by the minimum data greedy policy, requiring only a history of medical service codes and diagnoses from EHR. We formulate the problem as a binary classification. This dataset contains 175 441 de-identified patients (2 861 diagnosed with cancer). As a baseline, we implement a solution based on a recurrent neural network (RNN). We propose a method that combines machine learning and survival analysis since these approaches are less computationally heavy, can be combined into an ensemble (the Survival Ensemble), and can be reproduced in most medical institutions.   We test the Survival Ensemble in some studies. Firstly, we obtain a significant difference between values of the primary metric (Average Precision) with 22.8% (ROC AUC 83.7%, F1 17.8%) for the Survival Ensemble versus 15.1% (ROC AUC 84.9%, F1 21.4%) for the Baseline. Secondly, the performance of the Survival Ensemble is also confirmed during the ablation study. Thirdly, our method exceeds age baselines by a significant margin. Fourthly, in the blind retrospective out-of-time experiment, the proposed method is reliable in cancer patient detection (9 out of 100 selected). Such results exceed the estimates of medical screenings, e.g., the best Number Needed to Screen (9 out of 1000 screenings).

{{</citation>}}


### (65/115) Tempo Adaption in Non-stationary Reinforcement Learning (Hyunin Lee et al., 2023)

{{<citation>}}

Hyunin Lee, Yuhao Ding, Jongmin Lee, Ming Jin, Javad Lavaei, Somayeh Sojoudi. (2023)  
**Tempo Adaption in Non-stationary Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14989v1)  

---


**ABSTRACT**  
We first raise and tackle ``time synchronization'' issue between the agent and the environment in non-stationary reinforcement learning (RL), a crucial factor hindering its real-world applications. In reality, environmental changes occur over wall-clock time ($\mathfrak{t}$) rather than episode progress ($k$), where wall-clock time signifies the actual elapsed time within the fixed duration $\mathfrak{t} \in [0, T]$. In existing works, at episode $k$, the agent rollouts a trajectory and trains a policy before transitioning to episode $k+1$. In the context of the time-desynchronized environment, however, the agent at time $\mathfrak{t}_k$ allocates $\Delta \mathfrak{t}$ for trajectory generation and training, subsequently moves to the next episode at $\mathfrak{t}_{k+1}=\mathfrak{t}_{k}+\Delta \mathfrak{t}$. Despite a fixed total episode ($K$), the agent accumulates different trajectories influenced by the choice of \textit{interaction times} ($\mathfrak{t}_1,\mathfrak{t}_2,...,\mathfrak{t}_K$), significantly impacting the sub-optimality gap of policy. We propose a Proactively Synchronizing Tempo (ProST) framework that computes optimal $\{ \mathfrak{t}_1,\mathfrak{t}_2,...,\mathfrak{t}_K \} (= \{ \mathfrak{t} \}_{1:K})$. Our main contribution is that we show optimal $\{ \mathfrak{t} \}_{1:K}$ trades-off between the policy training time (agent tempo) and how fast the environment changes (environment tempo). Theoretically, this work establishes an optimal $\{ \mathfrak{t} \}_{1:K}$ as a function of the degree of the environment's non-stationarity while also achieving a sublinear dynamic regret. Our experimental evaluation on various high dimensional non-stationary environments shows that the ProST framework achieves a higher online return at optimal $\{ \mathfrak{t} \}_{1:K}$ than the existing methods.

{{</citation>}}


### (66/115) Label Deconvolution for Node Representation Learning on Large-scale Attributed Graphs against Learning Bias (Zhihao Shi et al., 2023)

{{<citation>}}

Zhihao Shi, Jie Wang, Fanghua Lu, Hanzhu Chen, Defu Lian, Zheng Wang, Jieping Ye, Feng Wu. (2023)  
**Label Deconvolution for Node Representation Learning on Large-scale Attributed Graphs against Learning Bias**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Bias, GNN, Representation Learning  
[Paper Link](http://arxiv.org/abs/2309.14907v1)  

---


**ABSTRACT**  
Node representation learning on attributed graphs -- whose nodes are associated with rich attributes (e.g., texts and protein sequences) -- plays a crucial role in many important downstream tasks. To encode the attributes and graph structures simultaneously, recent studies integrate pre-trained models with graph neural networks (GNNs), where pre-trained models serve as node encoders (NEs) to encode the attributes. As jointly training large NEs and GNNs on large-scale graphs suffers from severe scalability issues, many methods propose to train NEs and GNNs separately. Consequently, they do not take feature convolutions in GNNs into consideration in the training phase of NEs, leading to a significant learning bias from that by the joint training. To address this challenge, we propose an efficient label regularization technique, namely Label Deconvolution (LD), to alleviate the learning bias by a novel and highly scalable approximation to the inverse mapping of GNNs. The inverse mapping leads to an objective function that is equivalent to that by the joint training, while it can effectively incorporate GNNs in the training phase of NEs against the learning bias. More importantly, we show that LD converges to the optimal objective function values by thejoint training under mild assumptions. Experiments demonstrate LD significantly outperforms state-of-the-art methods on Open Graph Benchmark datasets.

{{</citation>}}


### (67/115) Credit Card Fraud Detection with Subspace Learning-based One-Class Classification (Zaffar Zaffar et al., 2023)

{{<citation>}}

Zaffar Zaffar, Fahad Sohrab, Juho Kanniainen, Moncef Gabbouj. (2023)  
**Credit Card Fraud Detection with Subspace Learning-based One-Class Classification**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Fraud Detection  
[Paper Link](http://arxiv.org/abs/2309.14880v1)  

---


**ABSTRACT**  
In an increasingly digitalized commerce landscape, the proliferation of credit card fraud and the evolution of sophisticated fraudulent techniques have led to substantial financial losses. Automating credit card fraud detection is a viable way to accelerate detection, reducing response times and minimizing potential financial losses. However, addressing this challenge is complicated by the highly imbalanced nature of the datasets, where genuine transactions vastly outnumber fraudulent ones. Furthermore, the high number of dimensions within the feature set gives rise to the ``curse of dimensionality". In this paper, we investigate subspace learning-based approaches centered on One-Class Classification (OCC) algorithms, which excel in handling imbalanced data distributions and possess the capability to anticipate and counter the transactions carried out by yet-to-be-invented fraud techniques. The study highlights the potential of subspace learning-based OCC algorithms by investigating the limitations of current fraud detection strategies and the specific challenges of credit card fraud detection. These algorithms integrate subspace learning into the data description; hence, the models transform the data into a lower-dimensional subspace optimized for OCC. Through rigorous experimentation and analysis, the study validated that the proposed approach helps tackle the curse of dimensionality and the imbalanced nature of credit card data for automatic fraud detection to mitigate financial losses caused by fraudulent activities.

{{</citation>}}


### (68/115) A Comparative Study of Population-Graph Construction Methods and Graph Neural Networks for Brain Age Regression (Kyriaki-Margarita Bintsi et al., 2023)

{{<citation>}}

Kyriaki-Margarita Bintsi, Tamara T. Mueller, Sophie Starck, Vasileios Baltatzis, Alexander Hammers, Daniel Rueckert. (2023)  
**A Comparative Study of Population-Graph Construction Methods and Graph Neural Networks for Brain Age Regression**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Attention, GNN, Graph Attention Network, Graph Convolutional Network, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.14816v1)  

---


**ABSTRACT**  
The difference between the chronological and biological brain age of a subject can be an important biomarker for neurodegenerative diseases, thus brain age estimation can be crucial in clinical settings. One way to incorporate multimodal information into this estimation is through population graphs, which combine various types of imaging data and capture the associations among individuals within a population. In medical imaging, population graphs have demonstrated promising results, mostly for classification tasks. In most cases, the graph structure is pre-defined and remains static during training. However, extracting population graphs is a non-trivial task and can significantly impact the performance of Graph Neural Networks (GNNs), which are sensitive to the graph structure. In this work, we highlight the importance of a meaningful graph construction and experiment with different population-graph construction methods and their effect on GNN performance on brain age estimation. We use the homophily metric and graph visualizations to gain valuable quantitative and qualitative insights on the extracted graph structures. For the experimental evaluation, we leverage the UK Biobank dataset, which offers many imaging and non-imaging phenotypes. Our results indicate that architectures highly sensitive to the graph structure, such as Graph Convolutional Network (GCN) and Graph Attention Network (GAT), struggle with low homophily graphs, while other architectures, such as GraphSage and Chebyshev, are more robust across different homophily ratios. We conclude that static graph construction approaches are potentially insufficient for the task of brain age estimation and make recommendations for alternative research directions.

{{</citation>}}


### (69/115) Age Minimization in Massive IoT via UAV Swarm: A Multi-agent Reinforcement Learning Approach (Eslam Eldeeb et al., 2023)

{{<citation>}}

Eslam Eldeeb, Mohammad Shehab, Hirley Alves. (2023)  
**Age Minimization in Massive IoT via UAV Swarm: A Multi-agent Reinforcement Learning Approach**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14757v1)  

---


**ABSTRACT**  
In many massive IoT communication scenarios, the IoT devices require coverage from dynamic units that can move close to the IoT devices and reduce the uplink energy consumption. A robust solution is to deploy a large number of UAVs (UAV swarm) to provide coverage and a better line of sight (LoS) for the IoT network. However, the study of these massive IoT scenarios with a massive number of serving units leads to high dimensional problems with high complexity. In this paper, we apply multi-agent deep reinforcement learning to address the high-dimensional problem that results from deploying a swarm of UAVs to collect fresh information from IoT devices. The target is to minimize the overall age of information in the IoT network. The results reveal that both cooperative and partially cooperative multi-agent deep reinforcement learning approaches are able to outperform the high-complexity centralized deep reinforcement learning approach, which stands helpless in large-scale networks.

{{</citation>}}


### (70/115) QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models (Yuhui Xu et al., 2023)

{{<citation>}}

Yuhui Xu, Lingxi Xie, Xiaotao Gu, Xin Chen, Heng Chang, Hengheng Zhang, Zhensu Chen, Xiaopeng Zhang, Qi Tian. (2023)  
**QA-LoRA: Quantization-Aware Low-Rank Adaptation of Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: LLaMA, Language Model, QA, Quantization  
[Paper Link](http://arxiv.org/abs/2309.14717v1)  

---


**ABSTRACT**  
Recently years have witnessed a rapid development of large language models (LLMs). Despite the strong ability in many language-understanding tasks, the heavy computational burden largely restricts the application of LLMs especially when one needs to deploy them onto edge devices. In this paper, we propose a quantization-aware low-rank adaptation (QA-LoRA) algorithm. The motivation lies in the imbalanced degrees of freedom of quantization and adaptation, and the solution is to use group-wise operators which increase the degree of freedom of quantization meanwhile decreasing that of adaptation. QA-LoRA is easily implemented with a few lines of code, and it equips the original LoRA with two-fold abilities: (i) during fine-tuning, the LLM's weights are quantized (e.g., into INT4) to reduce time and memory usage; (ii) after fine-tuning, the LLM and auxiliary weights are naturally integrated into a quantized model without loss of accuracy. We apply QA-LoRA to the LLaMA and LLaMA2 model families and validate its effectiveness in different fine-tuning datasets and downstream scenarios. Code will be made available at https://github.com/yuhuixu1993/qa-lora.

{{</citation>}}


### (71/115) On the Computational Complexity and Formal Hierarchy of Second Order Recurrent Neural Networks (Ankur Mali et al., 2023)

{{<citation>}}

Ankur Mali, Alexander Ororbia, Daniel Kifer, Lee Giles. (2023)  
**On the Computational Complexity and Formal Hierarchy of Second Order Recurrent Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-CC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14691v1)  

---


**ABSTRACT**  
Artificial neural networks (ANNs) with recurrence and self-attention have been shown to be Turing-complete (TC). However, existing work has shown that these ANNs require multiple turns or unbounded computation time, even with unbounded precision in weights, in order to recognize TC grammars. However, under constraints such as fixed or bounded precision neurons and time, ANNs without memory are shown to struggle to recognize even context-free languages. In this work, we extend the theoretical foundation for the $2^{nd}$-order recurrent network ($2^{nd}$ RNN) and prove there exists a class of a $2^{nd}$ RNN that is Turing-complete with bounded time. This model is capable of directly encoding a transition table into its recurrent weights, enabling bounded time computation and is interpretable by design. We also demonstrate that $2$nd order RNNs, without memory, under bounded weights and time constraints, outperform modern-day models such as vanilla RNNs and gated recurrent units in recognizing regular grammars. We provide an upper bound and a stability analysis on the maximum number of neurons required by $2$nd order RNNs to recognize any class of regular grammar. Extensive experiments on the Tomita grammars support our findings, demonstrating the importance of tensor connections in crafting computationally efficient RNNs. Finally, we show $2^{nd}$ order RNNs are also interpretable by extraction and can extract state machines with higher success rates as compared to first-order RNNs. Our results extend the theoretical foundations of RNNs and offer promising avenues for future explainable AI research.

{{</citation>}}


### (72/115) FedCompass: Efficient Cross-Silo Federated Learning on Heterogeneous Client Devices using a Computing Power Aware Scheduler (Zilinghan Li et al., 2023)

{{<citation>}}

Zilinghan Li, Pranshu Chaturvedi, Shilan He, Han Chen, Gagandeep Singh, Volodymyr Kindratenko, E. A. Huerta, Kibaek Kim, Ravi Madduri. (2023)  
**FedCompass: Efficient Cross-Silo Federated Learning on Heterogeneous Client Devices using a Computing Power Aware Scheduler**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14675v1)  

---


**ABSTRACT**  
Cross-silo federated learning offers a promising solution to collaboratively train robust and generalized AI models without compromising the privacy of local datasets, e.g., healthcare, financial, as well as scientific projects that lack a centralized data facility. Nonetheless, because of the disparity of computing resources among different clients (i.e., device heterogeneity), synchronous federated learning algorithms suffer from degraded efficiency when waiting for straggler clients. Similarly, asynchronous federated learning algorithms experience degradation in the convergence rate and final model accuracy on non-identically and independently distributed (non-IID) heterogeneous datasets due to stale local models and client drift. To address these limitations in cross-silo federated learning with heterogeneous clients and data, we propose FedCompass, an innovative semi-asynchronous federated learning algorithm with a computing power aware scheduler on the server side, which adaptively assigns varying amounts of training tasks to different clients using the knowledge of the computing power of individual clients. FedCompass ensures that multiple locally trained models from clients are received almost simultaneously as a group for aggregation, effectively reducing the staleness of local models. At the same time, the overall training process remains asynchronous, eliminating prolonged waiting periods from straggler clients. Using diverse non-IID heterogeneous distributed datasets, we demonstrate that FedCompass achieves faster convergence and higher accuracy than other asynchronous algorithms while remaining more efficient than synchronous algorithms when performing federated learning on heterogeneous clients.

{{</citation>}}


### (73/115) Leveraging Herpangina Data to Enhance Hospital-level Prediction of Hand-Foot-and-Mouth Disease Admissions Using UPTST (Guoqi Yu et al., 2023)

{{<citation>}}

Guoqi Yu, Hailun Yao, Huan Zheng, Ximing Xu. (2023)  
**Leveraging Herpangina Data to Enhance Hospital-level Prediction of Hand-Foot-and-Mouth Disease Admissions Using UPTST**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series, Transformer  
[Paper Link](http://arxiv.org/abs/2309.14674v1)  

---


**ABSTRACT**  
Outbreaks of hand-foot-and-mouth disease(HFMD) have been associated with significant morbidity and, in severe cases, mortality. Accurate forecasting of daily admissions of pediatric HFMD patients is therefore crucial for aiding the hospital in preparing for potential outbreaks and mitigating nosocomial transmissions. To address this pressing need, we propose a novel transformer-based model with a U-net shape, utilizing the patching strategy and the joint prediction strategy that capitalizes on insights from herpangina, a disease closely correlated with HFMD. This model also integrates representation learning by introducing reconstruction loss as an auxiliary loss. The results show that our U-net Patching Time Series Transformer (UPTST) model outperforms existing approaches in both long- and short-arm prediction accuracy of HFMD at hospital-level. Furthermore, the exploratory extension experiments show that the model's capabilities extend beyond prediction of infectious disease, suggesting broader applicability in various domains.

{{</citation>}}


### (74/115) ALEX: Towards Effective Graph Transfer Learning with Noisy Labels (Jingyang Yuan et al., 2023)

{{<citation>}}

Jingyang Yuan, Xiao Luo, Yifang Qin, Zhengyang Mao, Wei Ju, Ming Zhang. (2023)  
**ALEX: Towards Effective Graph Transfer Learning with Noisy Labels**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-IR, cs-LG, cs-SI, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2309.14673v1)  

---


**ABSTRACT**  
Graph Neural Networks (GNNs) have garnered considerable interest due to their exceptional performance in a wide range of graph machine learning tasks. Nevertheless, the majority of GNN-based approaches have been examined using well-annotated benchmark datasets, leading to suboptimal performance in real-world graph learning scenarios. To bridge this gap, the present paper investigates the problem of graph transfer learning in the presence of label noise, which transfers knowledge from a noisy source graph to an unlabeled target graph. We introduce a novel technique termed Balance Alignment and Information-aware Examination (ALEX) to address this challenge. ALEX first employs singular value decomposition to generate different views with crucial structural semantics, which help provide robust node representations using graph contrastive learning. To mitigate both label shift and domain shift, we estimate a prior distribution to build subgraphs with balanced label distributions. Building on this foundation, an adversarial domain discriminator is incorporated for the implicit domain alignment of complex multi-modal distributions. Furthermore, we project node representations into a different space, optimizing the mutual information between the projected features and labels. Subsequently, the inconsistency of similarity structures is evaluated to identify noisy samples with potential overfitting. Comprehensive experiments on various benchmark datasets substantiate the outstanding superiority of the proposed ALEX in different settings.

{{</citation>}}


### (75/115) Tranformer-based classification of user queries for medical consultancy with respect to expert specialisation (Dmitry Lyutkin et al., 2023)

{{<citation>}}

Dmitry Lyutkin, Andrey Soloviev, Dmitry Zhukov, Denis Pozdnyakov, Muhammad Shahid Iqbal Malik, Dmitry I. Ignatov. (2023)  
**Tranformer-based classification of user queries for medical consultancy with respect to expert specialisation**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-IR, cs-LG, cs.LG  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2309.14662v1)  

---


**ABSTRACT**  
The need for skilled medical support is growing in the era of digital healthcare. This research presents an innovative strategy, utilising the RuBERT model, for categorising user inquiries in the field of medical consultation with a focus on expert specialisation. By harnessing the capabilities of transformers, we fine-tuned the pre-trained RuBERT model on a varied dataset, which facilitates precise correspondence between queries and particular medical specialisms. Using a comprehensive dataset, we have demonstrated our approach's superior performance with an F1-score of over 92%, calculated through both cross-validation and the traditional split of test and train datasets. Our approach has shown excellent generalisation across medical domains such as cardiology, neurology and dermatology. This methodology provides practical benefits by directing users to appropriate specialists for prompt and targeted medical advice. It also enhances healthcare system efficiency, reduces practitioner burden, and improves patient care quality. In summary, our suggested strategy facilitates the attainment of specific medical knowledge, offering prompt and precise advice within the digital healthcare field.

{{</citation>}}


### (76/115) Gray-box Adversarial Attack of Deep Reinforcement Learning-based Trading Agents (Foozhan Ataiefard et al., 2023)

{{<citation>}}

Foozhan Ataiefard, Hadi Hemmati. (2023)  
**Gray-box Adversarial Attack of Deep Reinforcement Learning-based Trading Agents**  

---
Primary Category: cs.LG  
Categories: cs-CE, cs-LG, cs.LG, q-fin-TR  
Keywords: Adversarial Attack, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14615v1)  

---


**ABSTRACT**  
In recent years, deep reinforcement learning (Deep RL) has been successfully implemented as a smart agent in many systems such as complex games, self-driving cars, and chat-bots. One of the interesting use cases of Deep RL is its application as an automated stock trading agent. In general, any automated trading agent is prone to manipulations by adversaries in the trading environment. Thus studying their robustness is vital for their success in practice. However, typical mechanism to study RL robustness, which is based on white-box gradient-based adversarial sample generation techniques (like FGSM), is obsolete for this use case, since the models are protected behind secure international exchange APIs, such as NASDAQ. In this research, we demonstrate that a "gray-box" approach for attacking a Deep RL-based trading agent is possible by trading in the same stock market, with no extra access to the trading agent. In our proposed approach, an adversary agent uses a hybrid Deep Neural Network as its policy consisting of Convolutional layers and fully-connected layers. On average, over three simulated trading market configurations, the adversary policy proposed in this research is able to reduce the reward values by 214.17%, which results in reducing the potential profits of the baseline by 139.4%, ensemble method by 93.7%, and an automated trading software developed by our industrial partner by 85.5%, while consuming significantly less budget than the victims (427.77%, 187.16%, and 66.97%, respectively).

{{</citation>}}


### (77/115) Efficient Post-training Quantization with FP8 Formats (Haihao Shen et al., 2023)

{{<citation>}}

Haihao Shen, Naveen Mellempudi, Xin He, Qun Gao, Chang Wang, Mengni Wang. (2023)  
**Efficient Post-training Quantization with FP8 Formats**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: NLP, Quantization  
[Paper Link](http://arxiv.org/abs/2309.14592v1)  

---


**ABSTRACT**  
Recent advances in deep learning methods such as LLMs and Diffusion models have created a need for improved quantization methods that can meet the computational demands of these modern architectures while maintaining accuracy. Towards this goal, we study the advantages of FP8 data formats for post-training quantization across 75 unique network architectures covering a wide range of tasks, including machine translation, language modeling, text generation, image classification, generation, and segmentation. We examine three different FP8 representations (E5M2, E4M3, and E3M4) to study the effects of varying degrees of trade-off between dynamic range and precision on model accuracy. Based on our extensive study, we developed a quantization workflow that generalizes across different network architectures. Our empirical results show that FP8 formats outperform INT8 in multiple aspects, including workload coverage (92.64% vs. 65.87%), model accuracy and suitability for a broader range of operations. Furthermore, our findings suggest that E4M3 is better suited for NLP models, whereas E3M4 performs marginally better than E4M3 on computer vision tasks. The code is publicly available on Intel Neural Compressor: https://github.com/intel/neural-compressor.

{{</citation>}}


### (78/115) Joint Communication and Computation Framework for Goal-Oriented Semantic Communication with Distortion Rate Resilience (Minh-Duong Nguyen et al., 2023)

{{<citation>}}

Minh-Duong Nguyen, Quang-Vinh Do, Zhaohui Yang, Quoc-Viet Pham, Won-Joo Hwang. (2023)  
**Joint Communication and Computation Framework for Goal-Oriented Semantic Communication with Distortion Rate Resilience**  

---
Primary Category: cs.LG  
Categories: 68T05, F-1-3, cs-AI, cs-DC, cs-IT, cs-LG, cs.LG, eess-SP, math-IT  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14587v1)  

---


**ABSTRACT**  
Recent research efforts on semantic communication have mostly considered accuracy as a main problem for optimizing goal-oriented communication systems. However, these approaches introduce a paradox: the accuracy of artificial intelligence (AI) tasks should naturally emerge through training rather than being dictated by network constraints. Acknowledging this dilemma, this work introduces an innovative approach that leverages the rate-distortion theory to analyze distortions induced by communication and semantic compression, thereby analyzing the learning process. Specifically, we examine the distribution shift between the original data and the distorted data, thus assessing its impact on the AI model's performance. Founding upon this analysis, we can preemptively estimate the empirical accuracy of AI tasks, making the goal-oriented semantic communication problem feasible. To achieve this objective, we present the theoretical foundation of our approach, accompanied by simulations and experiments that demonstrate its effectiveness. The experimental results indicate that our proposed method enables accurate AI task performance while adhering to network constraints, establishing it as a valuable contribution to the field of signal processing. Furthermore, this work advances research in goal-oriented semantic communication and highlights the significance of data-driven approaches in optimizing the performance of intelligent systems.

{{</citation>}}


## cs.DB (1)



### (79/115) Consistent Query Answering for Primary Keys on Path Queries (Paraschos Koutris et al., 2023)

{{<citation>}}

Paraschos Koutris, Xiating Ouyang, Jef Wijsen. (2023)  
**Consistent Query Answering for Primary Keys on Path Queries**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: AI, QA  
[Paper Link](http://arxiv.org/abs/2309.15270v1)  

---


**ABSTRACT**  
We study the data complexity of consistent query answering (CQA) on databases that may violate the primary key constraints. A repair is a maximal consistent subset of the database. For a Boolean query $q$, the problem $\mathsf{CERTAINTY}(q)$ takes a database as input, and asks whether or not each repair satisfies $q$. It is known that for any self-join-free Boolean conjunctive query $q$, $\mathsf{CERTAINTY}(q)$ is in $\mathbf{FO}$, $\mathbf{LSPACE}$-complete, or $\mathbf{coNP}$-complete. In particular, $\mathsf{CERTAINTY}(q)$ is in $\mathbf{FO}$ for any self-join-free Boolean path query $q$. In this paper, we show that if self-joins are allowed, the complexity of $\mathsf{CERTAINTY}(q)$ for Boolean path queries $q$ exhibits a tetrachotomy between $\mathbf{FO}$, $\mathbf{NL}$-complete, $\mathbf{PTIME}$-complete, and $\mathbf{coNP}$-complete. Moreover, it is decidable, in polynomial time in the size of the query~$q$, which of the four cases applies.

{{</citation>}}


## cs.AI (4)



### (80/115) SeMAnD: Self-Supervised Anomaly Detection in Multimodal Geospatial Datasets (Daria Reshetova et al., 2023)

{{<citation>}}

Daria Reshetova, Swetava Ganguli, C. V. Krishnakumar Iyer, Vipul Pandey. (2023)  
**SeMAnD: Self-Supervised Anomaly Detection in Multimodal Geospatial Datasets**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CV, cs-LG, cs.AI  
Keywords: Anomaly Detection, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2309.15245v1)  

---


**ABSTRACT**  
We propose a Self-supervised Anomaly Detection technique, called SeMAnD, to detect geometric anomalies in Multimodal geospatial datasets. Geospatial data comprises of acquired and derived heterogeneous data modalities that we transform to semantically meaningful, image-like tensors to address the challenges of representation, alignment, and fusion of multimodal data. SeMAnD is comprised of (i) a simple data augmentation strategy, called RandPolyAugment, capable of generating diverse augmentations of vector geometries, and (ii) a self-supervised training objective with three components that incentivize learning representations of multimodal data that are discriminative to local changes in one modality which are not corroborated by the other modalities. Detecting local defects is crucial for geospatial anomaly detection where even small anomalies (e.g., shifted, incorrectly connected, malformed, or missing polygonal vector geometries like roads, buildings, landcover, etc.) are detrimental to the experience and safety of users of geospatial applications like mapping, routing, search, and recommendation systems. Our empirical study on test sets of different types of real-world geometric geospatial anomalies across 3 diverse geographical regions demonstrates that SeMAnD is able to detect real-world defects and outperforms domain-agnostic anomaly detection strategies by 4.8-19.7% as measured using anomaly classification AUC. We also show that model performance increases (i) up to 20.4% as the number of input modalities increase and (ii) up to 22.9% as the diversity and strength of training data augmentations increase.

{{</citation>}}


### (81/115) PlotMap: Automated Layout Design for Building Game Worlds (Yi Wang et al., 2023)

{{<citation>}}

Yi Wang, Jieliang Luo, Adam Gaier, Evan Atherton, Hilmar Koch. (2023)  
**PlotMap: Automated Layout Design for Building Game Worlds**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.15242v1)  

---


**ABSTRACT**  
World-building, the process of developing both the narrative and physical world of a game, plays a vital role in the game's experience. Critically acclaimed independent and AAA video games are praised for strong world building, with game maps that masterfully intertwine with and elevate the narrative, captivating players and leaving a lasting impression. However, designing game maps that support a desired narrative is challenging, as it requires satisfying complex constraints from various considerations. Most existing map generation methods focus on considerations about gameplay mechanics or map topography, while the need to support the story is typically neglected. As a result, extensive manual adjustment is still required to design a game world that facilitates particular stories. In this work, we approach this problem by introducing an extra layer of plot facility layout design that is independent of the underlying map generation method in a world-building pipeline. Concretely, we present a system that leverages Reinforcement Learning (RL) to automatically assign concrete locations on a game map to abstract locations mentioned in a given story (plot facilities), following spatial constraints derived from the story. A decision-making agent moves the plot facilities around, considering their relationship to the map and each other, to locations on the map that best satisfy the constraints of the story. Our system considers input from multiple modalities: map images as pixels, facility locations as real values, and story constraints expressed in natural language. We develop a method of generating datasets of facility layout tasks, create an RL environment to train and evaluate RL models, and further analyze the behaviors of the agents through a group of comprehensive experiments and ablation studies, aiming to provide insights for RL-based plot facility layout design.

{{</citation>}}


### (82/115) Forgetting-aware Linear Bias for Attentive Knowledge Tracing (Yoonjin Im et al., 2023)

{{<citation>}}

Yoonjin Im, Eunseong Choi, Heejin Kook, Jongwuk Lee. (2023)  
**Forgetting-aware Linear Bias for Attentive Knowledge Tracing**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2309.14796v1)  

---


**ABSTRACT**  
Knowledge Tracing (KT) aims to track proficiency based on a question-solving history, allowing us to offer a streamlined curriculum. Recent studies actively utilize attention-based mechanisms to capture the correlation between questions and combine it with the learner's characteristics for responses. However, our empirical study shows that existing attention-based KT models neglect the learner's forgetting behavior, especially as the interaction history becomes longer. This problem arises from the bias that overprioritizes the correlation of questions while inadvertently ignoring the impact of forgetting behavior. This paper proposes a simple-yet-effective solution, namely Forgetting-aware Linear Bias (FoLiBi), to reflect forgetting behavior as a linear bias. Despite its simplicity, FoLiBi is readily equipped with existing attentive KT models by effectively decomposing question correlations with forgetting behavior. FoLiBi plugged with several KT models yields a consistent improvement of up to 2.58% in AUC over state-of-the-art KT models on four benchmark datasets.

{{</citation>}}


### (83/115) Optimizing delegation between human and AI collaborative agents (Andrew Fuchs et al., 2023)

{{<citation>}}

Andrew Fuchs, Andrea Passarella, Marco Conti. (2023)  
**Optimizing delegation between human and AI collaborative agents**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14718v1)  

---


**ABSTRACT**  
In the context of humans operating with artificial or autonomous agents in a hybrid team, it is essential to accurately identify when to authorize those team members to perform actions. Given past examples where humans and autonomous systems can either succeed or fail at tasks, we seek to train a delegating manager agent to make delegation decisions with respect to these potential performance deficiencies. Additionally, we cannot always expect the various agents to operate within the same underlying model of the environment. It is possible to encounter cases where the actions and transitions would vary between agents. Therefore, our framework provides a manager model which learns through observations of team performance without restricting agents to matching dynamics. Our results show our manager learns to perform delegation decisions with teams of agents operating under differing representations of the environment, significantly outperforming alternative methods to manage the team.

{{</citation>}}


## cs.CY (4)



### (84/115) ChatGPT & Mechanical Engineering: Examining performance on the FE Mechanical Engineering and Undergraduate Exams (Matthew Frenkel et al., 2023)

{{<citation>}}

Matthew Frenkel, Hebah Emara. (2023)  
**ChatGPT & Mechanical Engineering: Examining performance on the FE Mechanical Engineering and Undergraduate Exams**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI, ChatGPT, GPT, GPT-3.5, GPT-4  
[Paper Link](http://arxiv.org/abs/2309.15866v1)  

---


**ABSTRACT**  
The launch of ChatGPT at the end of 2022 generated large interest into possible applications of artificial intelligence in STEM education and among STEM professions. As a result many questions surrounding the capabilities of generative AI tools inside and outside of the classroom have been raised and are starting to be explored. This study examines the capabilities of ChatGPT within the discipline of mechanical engineering. It aims to examine use cases and pitfalls of such a technology in the classroom and professional settings. ChatGPT was presented with a set of questions from junior and senior level mechanical engineering exams provided at a large private university, as well as a set of practice questions for the Fundamentals of Engineering Exam (FE) in Mechanical Engineering. The responses of two ChatGPT models, one free to use and one paid subscription, were analyzed. The paper found that the subscription model (GPT-4) greatly outperformed the free version (GPT-3.5), achieving 76% correct vs 51% correct, but the limitation of text only input on both models makes neither likely to pass the FE exam. The results confirm findings in the literature with regards to types of errors and pitfalls made by ChatGPT. It was found that due to its inconsistency and a tendency to confidently produce incorrect answers the tool is best suited for users with expert knowledge.

{{</citation>}}


### (85/115) User Experience Design Professionals' Perceptions of Generative Artificial Intelligence (Jie Li et al., 2023)

{{<citation>}}

Jie Li, Hancheng Cao, Laura Lin, Youyang Hou, Ruihao Zhu, Abdallah El Ali. (2023)  
**User Experience Design Professionals' Perceptions of Generative Artificial Intelligence**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs-ET, cs-HC, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.15237v1)  

---


**ABSTRACT**  
Among creative professionals, Generative Artificial Intelligence (GenAI) has sparked excitement over its capabilities and fear over unanticipated consequences. How does GenAI impact User Experience Design (UXD) practice, and are fears warranted? We interviewed 20 UX Designers, with diverse experience and across companies (startups to large enterprises). We probed them to characterize their practices, and sample their attitudes, concerns, and expectations. We found that experienced designers are confident in their originality, creativity, and empathic skills, and find GenAI's role as assistive. They emphasized the unique human factors of "enjoyment" and "agency", where humans remain the arbiters of "AI alignment". However, skill degradation, job replacement, and creativity exhaustion can adversely impact junior designers. We discuss implications for human-GenAI collaboration, specifically copyright and ownership, human creativity and agency, and AI literacy and access. Through the lens of responsible and participatory AI, we contribute a deeper understanding of GenAI fears and opportunities for UXD.

{{</citation>}}


### (86/115) APPRAISE: a framework for managing AI compliance (Diptish Dey et al., 2023)

{{<citation>}}

Diptish Dey, Debarati Bhaumik. (2023)  
**APPRAISE: a framework for managing AI compliance**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14876v1)  

---


**ABSTRACT**  
As AI systems increasingly impact society, the EU AI Act (AIA) is the first serious attempt to contain its less desired effects. Among others the act proposes audit as a mechanism and compliance products as tools for organizations to demonstrate compliance. In this paper, a framework for managing AI compliance, APPRAISE, is proposed. The framework is built upon the rationale that driving a balance between generating shareholder value through innovation in AI systems and managing compliance through organizational processes will eventually result in value that is responsible. By adhering to AIA compliance products, the framework operationalizes and hence safeguards compliance. Furthermore, a two-phase experiment with a limited scope is presented. The experiment aims to measure the extent to which companies coordinate technical elements of AI systems to ultimately comply with the AIA. In the first phase a survey is conducted and in the second phase the survey results are validated with a couple of respondents to generate additional in-depth insights and root causes.

{{</citation>}}


### (87/115) Towards A Unified Utilitarian Ethics Framework for Healthcare Artificial Intelligence (Forhan Bin Emdad et al., 2023)

{{<citation>}}

Forhan Bin Emdad, Shuyuan Mary Ho, Benhur Ravuri, Shezin Hussain. (2023)  
**Towards A Unified Utilitarian Ethics Framework for Healthcare Artificial Intelligence**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14617v1)  

---


**ABSTRACT**  
Artificial Intelligence (AI) aims to elevate healthcare to a pinnacle by aiding clinical decision support. Overcoming the challenges related to the design of ethical AI will enable clinicians, physicians, healthcare professionals, and other stakeholders to use and trust AI in healthcare settings. This study attempts to identify the major ethical principles influencing the utility performance of AI at different technological levels such as data access, algorithms, and systems through a thematic analysis. We observed that justice, privacy, bias, lack of regulations, risks, and interpretability are the most important principles to consider for ethical AI. This data-driven study has analyzed secondary survey data from the Pew Research Center (2020) of 36 AI experts to categorize the top ethical principles of AI design. To resolve the ethical issues identified by the meta-analysis and domain experts, we propose a new utilitarian ethics-based theoretical framework for designing ethical AI for the healthcare domain.

{{</citation>}}


## cs.CR (4)



### (88/115) Critical Infrastructure Security Goes to Space: Leveraging Lessons Learned on the Ground (Tim Ellis et al., 2023)

{{<citation>}}

Tim Ellis, Briland Hitaj, Ulf Lindqvist, Deborah Shands, Laura Tinnel, Bruce DeBruhl. (2023)  
**Critical Infrastructure Security Goes to Space: Leveraging Lessons Learned on the Ground**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SY, cs.CR, eess-SY  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2309.15232v1)  

---


**ABSTRACT**  
Space systems enable essential communications, navigation, imaging and sensing for a variety of domains, including agriculture, commerce, transportation, and emergency operations by first responders. Protecting the cybersecurity of these critical infrastructure systems is essential. While the space environment brings unique constraints to managing cybersecurity risks, lessons learned about risks and effective defenses in other critical infrastructure domains can help us to design effective defenses for space systems. In particular, discoveries regarding cybersecurity for industrial control systems (ICS) for energy, manufacturing, transportation, and the consumer and industrial Internet of Things (IoT) offer insights into cybersecurity for the space domain. This paper provides an overview of ICS and space system commonalities, lessons learned about cybersecurity for ICS that can be applied to space systems, and recommendations for future research and development to secure increasingly critical space systems.

{{</citation>}}


### (89/115) Eve Said Yes: AirBone Authentication for Head-Wearable Smart Voice Assistant (Chenpei Huang et al., 2023)

{{<citation>}}

Chenpei Huang, Hui Zhong, Jie Lian, Pavana Prakash, Dian Shi, Yuan Xu, Miao Pan. (2023)  
**Eve Said Yes: AirBone Authentication for Head-Wearable Smart Voice Assistant**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-HC, cs.CR, eess-SP  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2309.15203v1)  

---


**ABSTRACT**  
Recent advances in machine learning and natural language processing have fostered the enormous prosperity of smart voice assistants and their services, e.g., Alexa, Google Home, Siri, etc. However, voice spoofing attacks are deemed to be one of the major challenges of voice control security, and never stop evolving such as deep-learning-based voice conversion and speech synthesis techniques. To solve this problem outside the acoustic domain, we focus on head-wearable devices, such as earbuds and virtual reality (VR) headsets, which are feasible to continuously monitor the bone-conducted voice in the vibration domain. Specifically, we identify that air and bone conduction (AC/BC) from the same vocalization are coupled (or concurrent) and user-level unique, which makes them suitable behavior and biometric factors for multi-factor authentication (MFA). The legitimate user can defeat acoustic domain and even cross-domain spoofing samples with the proposed two-stage AirBone authentication. The first stage answers \textit{whether air and bone conduction utterances are time domain consistent (TC)} and the second stage runs \textit{bone conduction speaker recognition (BC-SR)}. The security level is hence increased for two reasons: (1) current acoustic attacks on smart voice assistants cannot affect bone conduction, which is in the vibration domain; (2) even for advanced cross-domain attacks, the unique bone conduction features can detect adversary's impersonation and machine-induced vibration. Finally, AirBone authentication has good usability (the same level as voice authentication) compared with traditional MFA and those specially designed to enhance smart voice security. Our experimental results show that the proposed AirBone authentication is usable and secure, and can be easily equipped by commercial off-the-shelf head wearables with good user experience.

{{</citation>}}


### (90/115) A Quantitative Information Flow Analysis of the Topics API (Mário S. Alvim et al., 2023)

{{<citation>}}

Mário S. Alvim, Natasha Fernandes, Annabelle McIver, Gabriel H. Nunes. (2023)  
**A Quantitative Information Flow Analysis of the Topics API**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-IT, cs.CR, math-IT  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2309.14746v1)  

---


**ABSTRACT**  
Third-party cookies have been a privacy concern since cookies were first developed in the mid 1990s, but more strict cookie policies were only introduced by Internet browser vendors in the early 2010s. More recently, due to regulatory changes, browser vendors have started to completely block third-party cookies, with both Firefox and Safari already compliant.   The Topics API is being proposed by Google as an additional and less intrusive source of information for interest-based advertising (IBA), following the upcoming deprecation of third-party cookies. Initial results published by Google estimate the probability of a correct re-identification of a random individual would be below 3% while still supporting IBA.   In this paper, we analyze the re-identification risk for individual Internet users introduced by the Topics API from the perspective of Quantitative Information Flow (QIF), an information- and decision-theoretic framework. Our model allows a theoretical analysis of both privacy and utility aspects of the API and their trade-off, and we show that the Topics API does have better privacy than third-party cookies. We leave the utility analyses for future work.

{{</citation>}}


### (91/115) XGV-BERT: Leveraging Contextualized Language Model and Graph Neural Network for Efficient Software Vulnerability Detection (Vu Le Anh Quan et al., 2023)

{{<citation>}}

Vu Le Anh Quan, Chau Thuan Phat, Kiet Van Nguyen, Phan The Duy, Van-Hau Pham. (2023)  
**XGV-BERT: Leveraging Contextualized Language Model and Graph Neural Network for Efficient Software Vulnerability Detection**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: BERT, Graph Neural Network, Language Model, Vulnerability Detection  
[Paper Link](http://arxiv.org/abs/2309.14677v1)  

---


**ABSTRACT**  
With the advancement of deep learning (DL) in various fields, there are many attempts to reveal software vulnerabilities by data-driven approach. Nonetheless, such existing works lack the effective representation that can retain the non-sequential semantic characteristics and contextual relationship of source code attributes. Hence, in this work, we propose XGV-BERT, a framework that combines the pre-trained CodeBERT model and Graph Neural Network (GCN) to detect software vulnerabilities. By jointly training the CodeBERT and GCN modules within XGV-BERT, the proposed model leverages the advantages of large-scale pre-training, harnessing vast raw data, and transfer learning by learning representations for training data through graph convolution. The research results demonstrate that the XGV-BERT method significantly improves vulnerability detection accuracy compared to two existing methods such as VulDeePecker and SySeVR. For the VulDeePecker dataset, XGV-BERT achieves an impressive F1-score of 97.5%, significantly outperforming VulDeePecker, which achieved an F1-score of 78.3%. Again, with the SySeVR dataset, XGV-BERT achieves an F1-score of 95.5%, surpassing the results of SySeVR with an F1-score of 83.5%.

{{</citation>}}


## eess.AS (4)



### (92/115) Collaborative Watermarking for Adversarial Speech Synthesis (Lauri Juvela et al., 2023)

{{<citation>}}

Lauri Juvela, Xin Wang. (2023)  
**Collaborative Watermarking for Adversarial Speech Synthesis**  

---
Primary Category: eess.AS  
Categories: cs-AI, cs-LG, cs-SD, eess-AS, eess.AS  
Keywords: Speaker Verification  
[Paper Link](http://arxiv.org/abs/2309.15224v1)  

---


**ABSTRACT**  
Advances in neural speech synthesis have brought us technology that is not only close to human naturalness, but is also capable of instant voice cloning with little data, and is highly accessible with pre-trained models available. Naturally, the potential flood of generated content raises the need for synthetic speech detection and watermarking. Recently, considerable research effort in synthetic speech detection has been related to the Automatic Speaker Verification and Spoofing Countermeasure Challenge (ASVspoof), which focuses on passive countermeasures. This paper takes a complementary view to generated speech detection: a synthesis system should make an active effort to watermark the generated speech in a way that aids detection by another machine, but remains transparent to a human listener. We propose a collaborative training scheme for synthetic speech watermarking and show that a HiFi-GAN neural vocoder collaborating with the ASVspoof 2021 baseline countermeasure models consistently improves detection performance over conventional classifier training. Furthermore, we demonstrate how collaborative training can be paired with augmentation strategies for added robustness against noise and time-stretching. Finally, listening tests demonstrate that collaborative training has little adverse effect on perceptual quality of vocoded speech.

{{</citation>}}


### (93/115) Segment-Level Vectorized Beam Search Based on Partially Autoregressive Inference (Masao Someki et al., 2023)

{{<citation>}}

Masao Someki, Nicholas Eng, Yosuke Higuchi, Shinji Watanabe. (2023)  
**Segment-Level Vectorized Beam Search Based on Partially Autoregressive Inference**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.14922v1)  

---


**ABSTRACT**  
Attention-based encoder-decoder models with autoregressive (AR) decoding have proven to be the dominant approach for automatic speech recognition (ASR) due to their superior accuracy. However, they often suffer from slow inference. This is primarily attributed to the incremental calculation of the decoder. This work proposes a partially AR framework, which employs segment-level vectorized beam search for improving the inference speed of an ASR model based on the hybrid connectionist temporal classification (CTC) attention-based architecture. It first generates an initial hypothesis using greedy CTC decoding, identifying low-confidence tokens based on their output probabilities. We then utilize the decoder to perform segment-level vectorized beam search on these tokens, re-predicting in parallel with minimal decoder calculations. Experimental results show that our method is 12 to 13 times faster in inference on the LibriSpeech corpus over AR decoding whilst preserving high accuracy.

{{</citation>}}


### (94/115) Learning from Flawed Data: Weakly Supervised Automatic Speech Recognition (Dongji Gao et al., 2023)

{{<citation>}}

Dongji Gao, Hainan Xu, Desh Raj, Leibny Paola Garcia Perera, Daniel Povey, Sanjeev Khudanpur. (2023)  
**Learning from Flawed Data: Weakly Supervised Automatic Speech Recognition**  

---
Primary Category: eess.AS  
Categories: cs-CL, cs-LG, eess-AS, eess.AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2309.15796v1)  

---


**ABSTRACT**  
Training automatic speech recognition (ASR) systems requires large amounts of well-curated paired data. However, human annotators usually perform "non-verbatim" transcription, which can result in poorly trained models. In this paper, we propose Omni-temporal Classification (OTC), a novel training criterion that explicitly incorporates label uncertainties originating from such weak supervision. This allows the model to effectively learn speech-text alignments while accommodating errors present in the training transcripts. OTC extends the conventional CTC objective for imperfect transcripts by leveraging weighted finite state transducers. Through experiments conducted on the LibriSpeech and LibriVox datasets, we demonstrate that training ASR models with OTC avoids performance degradation even with transcripts containing up to 70% errors, a scenario where CTC models fail completely. Our implementation is available at https://github.com/k2-fsa/icefall.

{{</citation>}}


### (95/115) Rethinking Session Variability: Leveraging Session Embeddings for Session Robustness in Speaker Verification (Hee-Soo Heo et al., 2023)

{{<citation>}}

Hee-Soo Heo, KiHyun Nam, Bong-Jin Lee, Youngki Kwon, Minjae Lee, You Jin Kim, Joon Son Chung. (2023)  
**Rethinking Session Variability: Leveraging Session Embeddings for Session Robustness in Speaker Verification**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Embedding, Speaker Verification  
[Paper Link](http://arxiv.org/abs/2309.14741v1)  

---


**ABSTRACT**  
In the field of speaker verification, session or channel variability poses a significant challenge. While many contemporary methods aim to disentangle session information from speaker embeddings, we introduce a novel approach using an additional embedding to represent the session information. This is achieved by training an auxiliary network appended to the speaker embedding extractor which remains fixed in this training process. This results in two similarity scores: one for the speakers information and one for the session information. The latter score acts as a compensator for the former that might be skewed due to session variations. Our extensive experiments demonstrate that session information can be effectively compensated without retraining of the embedding extractor.

{{</citation>}}


## cs.HC (3)



### (96/115) A Tale of Two Cultures: Comparing Interpersonal Information Disclosure Norms on Twitter (Mainack Mondal et al., 2023)

{{<citation>}}

Mainack Mondal, Anju Punuru, Tyng-Wen Scott Cheng, Kenneth Vargas, Chaz Gundry, Nathan S Driggs, Noah Schill, Nathaniel Carlson, Josh Bedwell, Jaden Q Lorenc, Isha Ghosh, Yao Li, Nancy Fulda, Xinru Page. (2023)  
**A Tale of Two Cultures: Comparing Interpersonal Information Disclosure Norms on Twitter**  

---
Primary Category: cs.HC  
Categories: cs-CY, cs-HC, cs-SI, cs.HC  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2309.15197v1)  

---


**ABSTRACT**  
We present an exploration of cultural norms surrounding online disclosure of information about one's interpersonal relationships (such as information about family members, colleagues, friends, or lovers) on Twitter. The literature identifies the cultural dimension of individualism versus collectivism as being a major determinant of offline communication differences in terms of emotion, topic, and content disclosed. We decided to study whether such differences also occur online in context of Twitter when comparing tweets posted in an individualistic (U.S.) versus a collectivist (India) society. We collected more than 2 million tweets posted in the U.S. and India over a 3 month period which contain interpersonal relationship keywords. A card-sort study was used to develop this culturally-sensitive saturated taxonomy of keywords that represent interpersonal relationships (e.g., ma, mom, mother). Then we developed a high-accuracy interpersonal disclosure detector based on dependency-parsing (F1-score: 86%) to identify when the words refer to a personal relationship of the poster (e.g., "my mom" as opposed to "a mom"). This allowed us to identify the 400K+ tweets in our data set which actually disclose information about the poster's interpersonal relationships. We used a mixed methods approach to analyze these tweets (e.g., comparing the amount of joy expressed about one's family) and found differences in emotion, topic, and content disclosed between tweets from the U.S. versus India. Our analysis also reveals how a combination of qualitative and quantitative methods are needed to uncover these differences; Using just one or the other can be misleading. This study extends the prior literature on Multi-Party Privacy and provides guidance for researchers and designers of culturally-sensitive systems.

{{</citation>}}


### (97/115) A Democratic Platform for Engaging with Disabled Community in Generative AI Development (Deepak Giri et al., 2023)

{{<citation>}}

Deepak Giri, Erin Brady. (2023)  
**A Democratic Platform for Engaging with Disabled Community in Generative AI Development**  

---
Primary Category: cs.HC  
Categories: I-2, cs-AI, cs-HC, cs.HC  
Keywords: AI, ChatGPT, GPT, Generative AI  
[Paper Link](http://arxiv.org/abs/2309.14921v1)  

---


**ABSTRACT**  
Artificial Intelligence (AI) systems, especially generative AI technologies are becoming more relevant in our society. Tools like ChatGPT are being used by members of the disabled community e.g., Autistic people may use it to help compose emails. The growing impact and popularity of generative AI tools have prompted us to examine their relevance within the disabled community. The design and development phases often neglect this marginalized group, leading to inaccurate predictions and unfair discrimination directed towards them. This could result from bias in data sets, algorithms, and systems at various phases of creation and implementation. This workshop paper proposes a platform to involve the disabled community while building generative AI systems. With this platform, our aim is to gain insight into the factors that contribute to bias in the outputs generated by generative AI when used by the disabled community. Furthermore, we expect to comprehend which algorithmic factors are the main contributors to the output's incorrectness or irrelevancy. The proposed platform calls on both disabled and non-disabled people from various geographical and cultural backgrounds to collaborate asynchronously and remotely in a democratic approach to decision-making.

{{</citation>}}


### (98/115) Explainable Sustainability for AI in the Arts (Petra Jääskeläinen, 2023)

{{<citation>}}

Petra Jääskeläinen. (2023)  
**Explainable Sustainability for AI in the Arts**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14877v2)  

---


**ABSTRACT**  
AI is becoming increasingly popular in artistic practices, but the tools for informing practitioners about the environmental impact (and other sustainability implications) of AI are adapted for other contexts than creative practices -- making the tools and sustainability implications of AI not accessible for artists and creative practitioners. In this position paper, I describe two empirical studies that aim to develop environmental sustainability reflection systems for AI Arts, and discuss and introduce Explainable Sustainability in for AI Arts.

{{</citation>}}


## cs.IR (3)



### (99/115) RankVicuna: Zero-Shot Listwise Document Reranking with Open-Source Large Language Models (Ronak Pradeep et al., 2023)

{{<citation>}}

Ronak Pradeep, Sahel Sharifymoghaddam, Jimmy Lin. (2023)  
**RankVicuna: Zero-Shot Listwise Document Reranking with Open-Source Large Language Models**  

---
Primary Category: cs.IR  
Categories: cs-CL, cs-IR, cs.IR  
Keywords: ChatGPT, GPT, GPT-3.5, GPT-4, Language Model, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2309.15088v1)  

---


**ABSTRACT**  
Researchers have successfully applied large language models (LLMs) such as ChatGPT to reranking in an information retrieval context, but to date, such work has mostly been built on proprietary models hidden behind opaque API endpoints. This approach yields experimental results that are not reproducible and non-deterministic, threatening the veracity of outcomes that build on such shaky foundations. To address this significant shortcoming, we present RankVicuna, the first fully open-source LLM capable of performing high-quality listwise reranking in a zero-shot setting. Experimental results on the TREC 2019 and 2020 Deep Learning Tracks show that we can achieve effectiveness comparable to zero-shot reranking with GPT-3.5 with a much smaller 7B parameter model, although our effectiveness remains slightly behind reranking with GPT-4. We hope our work provides the foundation for future research on reranking with modern LLMs. All the code necessary to reproduce our results is available at https://github.com/castorini/rank_llm.

{{</citation>}}


### (100/115) The Role of Document Embedding in Research Paper Recommender Systems: To Breakdown or to Bolster Disciplinary Borders? (Eoghan Cunningham et al., 2023)

{{<citation>}}

Eoghan Cunningham, Derek Greene, Barry Smyth. (2023)  
**The Role of Document Embedding in Research Paper Recommender Systems: To Breakdown or to Bolster Disciplinary Borders?**  

---
Primary Category: cs.IR  
Categories: cs-DL, cs-IR, cs.IR  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2309.14984v1)  

---


**ABSTRACT**  
In the extensive recommender systems literature, novelty and diversity have been identified as key properties of useful recommendations. However, these properties have received limited attention in the specific sub-field of research paper recommender systems. In this work, we argue for the importance of offering novel and diverse research paper recommendations to scientists. This approach aims to reduce siloed reading, break down filter bubbles, and promote interdisciplinary research. We propose a novel framework for evaluating the novelty and diversity of research paper recommendations that leverages methods from network analysis and natural language processing. Using this framework, we show that the choice of representational method within a larger research paper recommendation system can have a measurable impact on the nature of downstream recommendations, specifically on their novelty and diversity. We introduce a novel paper embedding method, which we demonstrate offers more innovative and diverse recommendations without sacrificing precision, compared to other state-of-the-art baselines.

{{</citation>}}


### (101/115) Modeling Multi-aspect Preferences and Intents for Multi-behavioral Sequential Recommendation (Haobing Liu et al., 2023)

{{<citation>}}

Haobing Liu, Jianyu Ding, Yanmin Zhu, Feilong Tang, Jiadi Yu, Ruobing Jiang, Zhongwen Guo. (2023)  
**Modeling Multi-aspect Preferences and Intents for Multi-behavioral Sequential Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: AI, LSTM  
[Paper Link](http://arxiv.org/abs/2309.14938v1)  

---


**ABSTRACT**  
Multi-behavioral sequential recommendation has recently attracted increasing attention. However, existing methods suffer from two major limitations. Firstly, user preferences and intents can be described in fine-grained detail from multiple perspectives; yet, these methods fail to capture their multi-aspect nature. Secondly, user behaviors may contain noises, and most existing methods could not effectively deal with noises. In this paper, we present an attentive recurrent model with multiple projections to capture Multi-Aspect preferences and INTents (MAINT in short). To extract multi-aspect preferences from target behaviors, we propose a multi-aspect projection mechanism for generating multiple preference representations from multiple aspects. To extract multi-aspect intents from multi-typed behaviors, we propose a behavior-enhanced LSTM and a multi-aspect refinement attention mechanism. The attention mechanism can filter out noises and generate multiple intent representations from different aspects. To adaptively fuse user preferences and intents, we propose a multi-aspect gated fusion mechanism. Extensive experiments conducted on real-world datasets have demonstrated the effectiveness of our model.

{{</citation>}}


## stat.ME (1)



### (102/115) Targeting Relative Risk Heterogeneity with Causal Forests (Vik Shirvaikar et al., 2023)

{{<citation>}}

Vik Shirvaikar, Chris Holmes. (2023)  
**Targeting Relative Risk Heterogeneity with Causal Forests**  

---
Primary Category: stat.ME  
Categories: cs-LG, stat-ME, stat-ML, stat.ME  
Keywords: GLM  
[Paper Link](http://arxiv.org/abs/2309.15793v1)  

---


**ABSTRACT**  
Treatment effect heterogeneity (TEH), or variability in treatment effect for different subgroups within a population, is of significant interest in clinical trial analysis. Causal forests (Wager and Athey, 2018) is a highly popular method for this problem, but like many other methods for detecting TEH, its criterion for separating subgroups focuses on differences in absolute risk. This can dilute statistical power by masking nuance in the relative risk, which is often a more appropriate quantity of clinical interest. In this work, we propose and implement a methodology for modifying causal forests to target relative risk using a novel node-splitting procedure based on generalized linear model (GLM) comparison. We present results on simulated and real-world data that suggest relative risk causal forests can capture otherwise unobserved sources of heterogeneity.

{{</citation>}}


## eess.SY (2)



### (103/115) Constrained Deep Reinforcement Learning for Fronthaul Compression Optimization (Axel Grönland et al., 2023)

{{<citation>}}

Axel Grönland, Alessio Russo, Yassir Jedra, Bleron Klaiqi, Xavier Gelabert. (2023)  
**Constrained Deep Reinforcement Learning for Fronthaul Compression Optimization**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.15060v2)  

---


**ABSTRACT**  
In the Centralized-Radio Access Network (C-RAN) architecture, functions can be placed in the central or distributed locations. This architecture can offer higher capacity and cost savings but also puts strict requirements on the fronthaul (FH). Adaptive FH compression schemes that adapt the compression amount to varying FH traffic are promising approaches to deal with stringent FH requirements. In this work, we design such a compression scheme using a model-free off policy deep reinforcement learning algorithm which accounts for FH latency and packet loss constraints. Furthermore, this algorithm is designed for model transparency and interpretability which is crucial for AI trustworthiness in performance critical domains. We show that our algorithm can successfully choose an appropriate compression scheme while satisfying the constraints and exhibits a roughly 70\% increase in FH utilization compared to a reference scheme.

{{</citation>}}


### (104/115) Effective Multi-Agent Deep Reinforcement Learning Control with Relative Entropy Regularization (Chenyang Miao et al., 2023)

{{<citation>}}

Chenyang Miao, Yunduan Cui, Huiyun Li, Xinyu Wu. (2023)  
**Effective Multi-Agent Deep Reinforcement Learning Control with Relative Entropy Regularization**  

---
Primary Category: eess.SY  
Categories: cs-AI, cs-LG, cs-SY, eess-SY, eess.SY  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2309.14727v1)  

---


**ABSTRACT**  
In this paper, a novel Multi-agent Reinforcement Learning (MARL) approach, Multi-Agent Continuous Dynamic Policy Gradient (MACDPP) was proposed to tackle the issues of limited capability and sample efficiency in various scenarios controlled by multiple agents. It alleviates the inconsistency of multiple agents' policy updates by introducing the relative entropy regularization to the Centralized Training with Decentralized Execution (CTDE) framework with the Actor-Critic (AC) structure. Evaluated by multi-agent cooperation and competition tasks and traditional control tasks including OpenAI benchmarks and robot arm manipulation, MACDPP demonstrates significant superiority in learning capability and sample efficiency compared with both related multi-agent and widely implemented signal-agent baselines and therefore expands the potential of MARL in effectively learning challenging control scenarios.

{{</citation>}}


## cs.SE (3)



### (105/115) Exploring ChatGPT Approach to Bidirectional Traceability Problem between Design Models and Code (Hideyuki Kanuka et al., 2023)

{{<citation>}}

Hideyuki Kanuka, Genta Koreki, Ryo Soga, Kazu Nishikawa. (2023)  
**Exploring ChatGPT Approach to Bidirectional Traceability Problem between Design Models and Code**  

---
Primary Category: cs.SE  
Categories: K-6-3, cs-SE, cs.SE  
Keywords: AI, ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2309.14992v1)  

---


**ABSTRACT**  
This study explores the capabilities of Large Language Models (LLMs), particularly OpenAI's ChatGPT, in addressing the challenges associated with software modeling, explicitly focusing on the bidirectional traceability problem between design models and code. The objective of this study is to demonstrate the proficiency of ChatGPT in understanding and integrating specific requirements into design models and code and its potential to offer solutions to the bidirectional traceability problem through a case study. The findings indicate that ChatGPT is capable of generating design models and code from natural language requirements, thereby bridging the gap between these requirements and software modeling. Despite its limitations in suggesting a specific method to resolve the problem using ChatGPT itself, it exhibited the capacity to provide corrections to be consistent between design models and code. As a result, the study concludes that achieving bidirectional traceability between design models and code is feasible using ChatGPT.

{{</citation>}}


### (106/115) DAnTE: a taxonomy for the automation degree of software engineering tasks (Jorge Melegati et al., 2023)

{{<citation>}}

Jorge Melegati, Eduardo Guerra. (2023)  
**DAnTE: a taxonomy for the automation degree of software engineering tasks**  

---
Primary Category: cs.SE  
Categories: D-2-0; I-2-2, cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14903v1)  

---


**ABSTRACT**  
Software engineering researchers and practitioners have pursued manners to reduce the amount of time and effort required to develop code and increase productivity since the emergence of the discipline. Generative language models are just another step in this journey, but it will probably not be the last one. In this chapter, we propose DAnTE, a Degree of Automation Taxonomy for software Engineering, describing several levels of automation based on the idiosyncrasies of the field. Based on the taxonomy, we evaluated several tools used in the past and in the present for software engineering practices. Then, we give particular attention to AI-based tools, including generative language models, discussing how they are located within the proposed taxonomy, and reasoning about possible limitations they currently have. Based on this analysis, we discuss what novel tools could emerge in the middle and long term.

{{</citation>}}


### (107/115) Supersonic: Learning to Generate Source Code Optimisations in C/C++ (Zimin Chen et al., 2023)

{{<citation>}}

Zimin Chen, Sen Fang, Martin Monperrus. (2023)  
**Supersonic: Learning to Generate Source Code Optimisations in C/C++**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-SE, cs.SE  
Keywords: AI, GPT, GPT-3.5, GPT-4  
[Paper Link](http://arxiv.org/abs/2309.14846v2)  

---


**ABSTRACT**  
Software optimization refines programs for resource efficiency while preserving functionality. Traditionally, it is a process done by developers and compilers. This paper introduces a third option, automated optimization at the source code level. We present Supersonic, a neural approach targeting minor source code modifications for optimization. Using a seq2seq model, Supersonic is trained on C/C++ program pairs ($x_{t}$, $x_{t+1}$), where $x_{t+1}$ is an optimized version of $x_{t}$, and outputs a diff. Supersonic's performance is benchmarked against OpenAI's GPT-3.5-Turbo and GPT-4 on competitive programming tasks. The experiments show that Supersonic not only outperforms both models on the code optimization task but also minimizes the extent of the change with a model more than 600x smaller than GPT-3.5-Turbo and 3700x smaller than GPT-4.

{{</citation>}}


## eess.SP (1)



### (108/115) A multi-modal approach for identifying schizophrenia using cross-modal attention (Gowtham Premananth et al., 2023)

{{<citation>}}

Gowtham Premananth, Yashish M. Siriwardena, Philip Resnik, Carol Espy-Wilson. (2023)  
**A multi-modal approach for identifying schizophrenia using cross-modal attention**  

---
Primary Category: eess.SP  
Categories: cs-MM, cs-SD, eess-AS, eess-IV, eess-SP, eess.SP  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2309.15136v1)  

---


**ABSTRACT**  
This study focuses on how different modalities of human communication can be used to distinguish between healthy controls and subjects with schizophrenia who exhibit strong positive symptoms. We developed a multi-modal schizophrenia classification system using audio, video, and text. Facial action units and vocal tract variables were extracted as low-level features from video and audio respectively, which were then used to compute high-level coordination features that served as the inputs to the audio and video modalities. Context-independent text embeddings extracted from transcriptions of speech were used as the input for the text modality. The multi-modal system is developed by fusing a segment-to-session-level classifier for video and audio modalities with a text model based on a Hierarchical Attention Network (HAN) with cross-modal attention. The proposed multi-modal system outperforms the previous state-of-the-art multi-modal system by 8.53% in the weighted average F1 score.

{{</citation>}}


## q-bio.BM (1)



### (109/115) Addressing preferred orientation in single-particle cryo-EM through AI-generated auxiliary particles (Hui Zhang et al., 2023)

{{<citation>}}

Hui Zhang, Dihan Zheng, Qiurong Wu, Nieng Yan, Zuoqiang Shi, Mingxu Hu, Chenglong Bao. (2023)  
**Addressing preferred orientation in single-particle cryo-EM through AI-generated auxiliary particles**  

---
Primary Category: q-bio.BM  
Categories: cs-AI, q-bio-BM, q-bio.BM  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2309.14954v1)  

---


**ABSTRACT**  
The single-particle cryo-EM field faces the persistent challenge of preferred orientation, lacking general computational solutions. We introduce cryoPROS, an AI-based approach designed to address the above issue. By generating the auxiliary particles with a conditional deep generative model, cryoPROS addresses the intrinsic bias in orientation estimation for the observed particles. We effectively employed cryoPROS in the cryo-EM single particle analysis of the hemagglutinin trimer, showing the ability to restore the near-atomic resolution structure on non-tilt data. Moreover, the enhanced version named cryoPROS-MP significantly improves the resolution of the membrane protein NaX using the no-tilted data that contains the effects of micelles. Compared to the classical approaches, cryoPROS does not need special experimental or image acquisition techniques, providing a purely computational yet effective solution for the preferred orientation problem. Finally, we conduct extensive experiments that establish the low risk of model bias and the high robustness of cryoPROS.

{{</citation>}}


## cond-mat.dis-nn (1)



### (110/115) Robustness of the Random Language Model (Fatemeh Lalegani et al., 2023)

{{<citation>}}

Fatemeh Lalegani, Eric De Giuli. (2023)  
**Robustness of the Random Language Model**  

---
Primary Category: cond-mat.dis-nn  
Categories: cond-mat-dis-nn, cond-mat.dis-nn, cs-CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2309.14913v1)  

---


**ABSTRACT**  
The Random Language Model (De Giuli 2019) is an ensemble of stochastic context-free grammars, quantifying the syntax of human and computer languages. The model suggests a simple picture of first language learning as a type of annealing in the vast space of potential languages. In its simplest formulation, it implies a single continuous transition to grammatical syntax, at which the symmetry among potential words and categories is spontaneously broken. Here this picture is scrutinized by considering its robustness against explicit symmetry breaking, an inevitable component of learning in the real world. It is shown that the scenario is robust to such symmetry breaking. Comparison with human data on the clustering coefficient of syntax networks suggests that the observed transition is equivalent to that normally experienced by children at age 24 months.

{{</citation>}}


## cs.SD (2)



### (111/115) Emphasized Non-Target Speaker Knowledge in Knowledge Distillation for Automatic Speaker Verification (Duc-Tuan Truong et al., 2023)

{{<citation>}}

Duc-Tuan Truong, Ruijie Tao, Jia Qi Yip, Kong Aik Lee, Eng Siong Chng. (2023)  
**Emphasized Non-Target Speaker Knowledge in Knowledge Distillation for Automatic Speaker Verification**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: Knowledge Distillation, Speaker Verification  
[Paper Link](http://arxiv.org/abs/2309.14838v1)  

---


**ABSTRACT**  
Knowledge distillation (KD) is used to enhance automatic speaker verification performance by ensuring consistency between large teacher networks and lightweight student networks at the embedding level or label level. However, the conventional label-level KD overlooks the significant knowledge from non-target speakers, particularly their classification probabilities, which can be crucial for automatic speaker verification. In this paper, we first demonstrate that leveraging a larger number of training non-target speakers improves the performance of automatic speaker verification models. Inspired by this finding about the importance of non-target speakers' knowledge, we modified the conventional label-level KD by disentangling and emphasizing the classification probabilities of non-target speakers during knowledge distillation. The proposed method is applied to three different student model architectures and achieves an average of 13.67% improvement in EER on the VoxCeleb dataset compared to embedding-level and conventional label-level KD methods.

{{</citation>}}


### (112/115) Speech Audio Synthesis from Tagged MRI and Non-Negative Matrix Factorization via Plastic Transformer (Xiaofeng Liu et al., 2023)

{{<citation>}}

Xiaofeng Liu, Fangxu Xing, Maureen Stone, Jiachen Zhuo, Sidney Fels, Jerry L. Prince, Georges El Fakhri, Jonghye Woo. (2023)  
**Speech Audio Synthesis from Tagged MRI and Non-Negative Matrix Factorization via Plastic Transformer**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-CV, cs-SD, cs.SD, eess-AS, eess-SP  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2309.14586v1)  

---


**ABSTRACT**  
The tongue's intricate 3D structure, comprising localized functional units, plays a crucial role in the production of speech. When measured using tagged MRI, these functional units exhibit cohesive displacements and derived quantities that facilitate the complex process of speech production. Non-negative matrix factorization-based approaches have been shown to estimate the functional units through motion features, yielding a set of building blocks and a corresponding weighting map. Investigating the link between weighting maps and speech acoustics can offer significant insights into the intricate process of speech production. To this end, in this work, we utilize two-dimensional spectrograms as a proxy representation, and develop an end-to-end deep learning framework for translating weighting maps to their corresponding audio waveforms. Our proposed plastic light transformer (PLT) framework is based on directional product relative position bias and single-level spatial pyramid pooling, thus enabling flexible processing of weighting maps with variable size to fixed-size spectrograms, without input information loss or dimension expansion. Additionally, our PLT framework efficiently models the global correlation of wide matrix input. To improve the realism of our generated spectrograms with relatively limited training samples, we apply pair-wise utterance consistency with Maximum Mean Discrepancy constraint and adversarial training. Experimental results on a dataset of 29 subjects speaking two utterances demonstrated that our framework is able to synthesize speech audio waveforms from weighting maps, outperforming conventional convolution and transformer models.

{{</citation>}}


## cs.DC (1)



### (113/115) Expedited Data Transfers for Serverless Clouds (Dmitrii Ustiugov et al., 2023)

{{<citation>}}

Dmitrii Ustiugov, Shyam Jesalpura, Mert Bora Alper, Michal Baczun, Rustem Feyzkhanov, Edouard Bugnion, Boris Grot, Marios Kogias. (2023)  
**Expedited Data Transfers for Serverless Clouds**  

---
Primary Category: cs.DC  
Categories: 68, D-4-4, cs-DC, cs-OS, cs.DC  
Keywords: AWS  
[Paper Link](http://arxiv.org/abs/2309.14821v1)  

---


**ABSTRACT**  
Serverless computing has emerged as a popular cloud deployment paradigm. In serverless, the developers implement their application as a set of chained functions that form a workflow in which functions invoke each other. The cloud providers are responsible for automatically scaling the number of instances for each function on demand and forwarding the requests in a workflow to the appropriate function instance. Problematically, today's serverless clouds lack efficient support for cross-function data transfers in a workflow, preventing the efficient execution of data-intensive serverless applications. In production clouds, functions transmit intermediate, i.e., ephemeral, data to other functions either as part of invocation HTTP requests (i.e., inline) or via third-party services, such as AWS S3 storage or AWS ElastiCache in-memory cache. The former approach is restricted to small transfer sizes, while the latter supports arbitrary transfers but suffers from performance and cost overheads. This work introduces Expedited Data Transfers (XDT), an API-preserving high-performance data communication method for serverless that enables direct function-to-function transfers. With XDT, a trusted component of the sender function buffers the payload in its memory and sends a secure reference to the receiver, which is picked by the load balancer and autoscaler based on the current load. Using the reference, the receiver instance pulls the transmitted data directly from the sender's memory. XDT is natively compatible with existing autoscaling infrastructure, preserves function invocation semantics, is secure, and avoids the cost and performance overheads of using an intermediate service for data transfers. We prototype our system in vHive/Knative deployed on a cluster of AWS EC2 nodes, showing that XDT improves latency, bandwidth, and cost over AWS S3 and ElasticCache.

{{</citation>}}


## cs.IT (1)



### (114/115) Design of Energy-Efficient Artificial Noise for Physical Layer Security in Visible Light Communications (Thanh V. Pham et al., 2023)

{{<citation>}}

Thanh V. Pham, Anh T. Pham, Susumu Ishihara. (2023)  
**Design of Energy-Efficient Artificial Noise for Physical Layer Security in Visible Light Communications**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs-SY, cs.IT, eess-SY, math-IT  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2309.14636v1)  

---


**ABSTRACT**  
This paper studies the design of energy-efficient artificial noise (AN) schemes in the context of physical layer security in visible light communications (VLC). Two different transmission schemes termed $\textit{selective AN-aided single-input single-output (SISO)}$ and $\textit{AN-aided multiple-input single-output (MISO)}$ are examined and compared in terms of secrecy energy efficiency (SEE). In the former, the closest LED luminaire to the legitimate user (Bob) is the information-bearing signal's transmitter. At the same time, the rest of the luminaries act as jammers transmitting AN to degrade the channels of eavesdroppers (Eves). In the latter, the information-bearing signal and AN are combined and transmitted by all luminaries. When Eves' CSI is unknown, an indirect design to improve the SEE is formulated by maximizing Bob's channel's energy efficiency. A low-complexity design based on the zero-forcing criterion is also proposed. In the case of known Eves' CSI, we study the design that maximizes the minimum SEE among those corresponding to all eavesdroppers. At their respective optimal SEEs, simulation results reveal that when Eves' CSI is unknown, the selective AN-aided SISO transmission can archive twice better SEE as the AN-aided MISO does. In contrast, when Eves' CSI is known, the AN-aided MISO outperforms by 30%.

{{</citation>}}


## eess.IV (1)



### (115/115) Applications of Sequential Learning for Medical Image Classification (Sohaib Naim et al., 2023)

{{<citation>}}

Sohaib Naim, Brian Caffo, Haris I Sair, Craig K Jones. (2023)  
**Applications of Sequential Learning for Medical Image Classification**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Image Classification  
[Paper Link](http://arxiv.org/abs/2309.14591v1)  

---


**ABSTRACT**  
Purpose: The aim of this work is to develop a neural network training framework for continual training of small amounts of medical imaging data and create heuristics to assess training in the absence of a hold-out validation or test set.   Materials and Methods: We formulated a retrospective sequential learning approach that would train and consistently update a model on mini-batches of medical images over time. We address problems that impede sequential learning such as overfitting, catastrophic forgetting, and concept drift through PyTorch convolutional neural networks (CNN) and publicly available Medical MNIST and NIH Chest X-Ray imaging datasets. We begin by comparing two methods for a sequentially trained CNN with and without base pre-training. We then transition to two methods of unique training and validation data recruitment to estimate full information extraction without overfitting. Lastly, we consider an example of real-life data that shows how our approach would see mainstream research implementation.   Results: For the first experiment, both approaches successfully reach a ~95% accuracy threshold, although the short pre-training step enables sequential accuracy to plateau in fewer steps. The second experiment comparing two methods showed better performance with the second method which crosses the ~90% accuracy threshold much sooner. The final experiment showed a slight advantage with a pre-training step that allows the CNN to cross ~60% threshold much sooner than without pre-training.   Conclusion: We have displayed sequential learning as a serviceable multi-classification technique statistically comparable to traditional CNNs that can acquire data in small increments feasible for clinically realistic scenarios.

{{</citation>}}
