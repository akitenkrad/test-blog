---
draft: false
title: "arXiv @ 2023.11.07"
date: 2023-11-07
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.11.07"
    identifier: arxiv_20231107
    parent: 202311_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.IT (1)](#csit-1)
- [cs.CL (8)](#cscl-8)
- [cs.CV (17)](#cscv-17)
- [cs.PL (1)](#cspl-1)
- [cs.LG (12)](#cslg-12)
- [cs.SD (1)](#cssd-1)
- [cs.AI (2)](#csai-2)
- [cs.AR (1)](#csar-1)
- [cs.IR (3)](#csir-3)
- [cs.DS (1)](#csds-1)
- [eess.SY (1)](#eesssy-1)
- [cs.DC (1)](#csdc-1)
- [cs.CY (1)](#cscy-1)
- [cs.NI (1)](#csni-1)
- [cs.SE (1)](#csse-1)
- [cs.DB (2)](#csdb-2)
- [cs.HC (1)](#cshc-1)

## cs.IT (1)



### (1/55) Optimal Construction of N-bit-delay Almost Instantaneous Fixed-to-Variable-Length Codes (Ryosuke Sugiura et al., 2023)

{{<citation>}}

Ryosuke Sugiura, Masaaki Nishino, Norihito Yasuda, Yutaka Kamamoto, Takehiro Moriya. (2023)  
**Optimal Construction of N-bit-delay Almost Instantaneous Fixed-to-Variable-Length Codes**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, math-IT  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.02797v1)  

---


**ABSTRACT**  
This paper presents an optimal construction of $N$-bit-delay almost instantaneous fixed-to-variable-length (AIFV) codes, the general form of binary codes we can make when finite bits of decoding delay are allowed. The presented method enables us to optimize lossless codes among a broader class of codes compared to the conventional FV and AIFV codes. The paper first discusses the problem of code construction, which contains some essential partial problems, and defines three classes of optimality to clarify how far we can solve the problems. The properties of the optimal codes are analyzed theoretically, showing the sufficient conditions for achieving the optimum. Then, we propose an algorithm for constructing $N$-bit-delay AIFV codes for given stationary memory-less sources. The optimality of the constructed codes is discussed both theoretically and empirically. They showed shorter expected code lengths when $N\ge 3$ than the conventional AIFV-$m$ and extended Huffman codes. Moreover, in the random numbers simulation, they performed higher compression efficiency than the 32-bit-precision range codes under reasonable conditions.

{{</citation>}}


## cs.CL (8)



### (2/55) CausalCite: A Causal Formulation of Paper Citations (Ishan Kumar et al., 2023)

{{<citation>}}

Ishan Kumar, Zhijing Jin, Ehsan Mokhtarian, Siyuan Guo, Yuen Chen, Negar Kiyavash, Mrinmaya Sachan, Bernhard Schoelkopf. (2023)  
**CausalCite: A Causal Formulation of Paper Citations**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CY, cs-IR, cs-LG, cs.CL  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2311.02790v1)  

---


**ABSTRACT**  
Evaluating the significance of a paper is pivotal yet challenging for the scientific community. While the citation count is the most commonly used proxy for this purpose, they are widely criticized for failing to accurately reflect a paper's true impact. In this work, we propose a causal inference method, TextMatch, which adapts the traditional matching framework to high-dimensional text embeddings. Specifically, we encode each paper using the text embeddings by large language models (LLMs), extract similar samples by cosine similarity, and synthesize a counterfactual sample by the weighted average of similar papers according to their similarity values. We apply the resulting metric, called CausalCite, as a causal formulation of paper citations. We show its effectiveness on various criteria, such as high correlation with paper impact as reported by scientific experts on a previous dataset of 1K papers, (test-of-time) awards for past papers, and its stability across various sub-fields of AI. We also provide a set of findings that can serve as suggested ways for future researchers to use our metric for a better understanding of a paper's quality. Our code and data are at https://github.com/causalNLP/causal-cite.

{{</citation>}}


### (3/55) Large language models implicitly learn to straighten neural sentence trajectories to construct a predictive representation of natural language (Eghbal A. Hosseini et al., 2023)

{{<citation>}}

Eghbal A. Hosseini, Evelina Fedorenko. (2023)  
**Large language models implicitly learn to straighten neural sentence trajectories to construct a predictive representation of natural language**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.04930v1)  

---


**ABSTRACT**  
Predicting upcoming events is critical to our ability to interact with our environment. Transformer models, trained on next-word prediction, appear to construct representations of linguistic input that can support diverse downstream tasks. But how does a predictive objective shape such representations? Inspired by recent work in vision (Henaff et al., 2019), we test a hypothesis about predictive representations of autoregressive transformers. In particular, we test whether the neural trajectory of a sentence becomes progressively straighter as it passes through the network layers. The key insight is that straighter trajectories should facilitate prediction via linear extrapolation. We quantify straightness using a 1-dimensional curvature metric, and present four findings in support of the trajectory straightening hypothesis: i) In trained models, the curvature decreases from the early to the deeper layers of the network. ii) Models that perform better on the next-word prediction objective exhibit greater decreases in curvature, suggesting that this improved ability to straighten sentence trajectories may be the driver of better language modeling performance. iii) Given the same linguistic context, the sequences that are generated by the model have lower curvature than the actual continuations observed in a language corpus, suggesting that the model favors straighter trajectories for making predictions. iv) A consistent relationship holds between the average curvature and the average surprisal of sentences in the deep model layers, such that sentences with straighter trajectories also have lower surprisal. Importantly, untrained models do not exhibit these behaviors. In tandem, these results support the trajectory straightening hypothesis and provide a possible mechanism for how the geometry of the internal representations of autoregressive models supports next word prediction.

{{</citation>}}


### (4/55) Rule Learning as Machine Translation using the Atomic Knowledge Bank (Kristoffer Æsøy et al., 2023)

{{<citation>}}

Kristoffer Æsøy, Ana Ozaki. (2023)  
**Rule Learning as Machine Translation using the Atomic Knowledge Bank**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Machine Translation  
[Paper Link](http://arxiv.org/abs/2311.02765v1)  

---


**ABSTRACT**  
Machine learning models, and in particular language models, are being applied to various tasks that require reasoning. While such models are good at capturing patterns their ability to reason in a trustable and controlled manner is frequently questioned. On the other hand, logic-based rule systems allow for controlled inspection and already established verification methods. However it is well-known that creating such systems manually is time-consuming and prone to errors. We explore the capability of transformers to translate sentences expressing rules in natural language into logical rules. We see reasoners as the most reliable tools for performing logical reasoning and focus on translating language into the format expected by such tools. We perform experiments using the DKET dataset from the literature and create a dataset for language to logic translation based on the Atomic knowledge bank.

{{</citation>}}


### (5/55) Extraction of Atypical Aspects from Customer Reviews: Datasets and Experiments with Language Models (Smita Nannaware et al., 2023)

{{<citation>}}

Smita Nannaware, Erfan Al-Hossami, Razvan Bunescu. (2023)  
**Extraction of Atypical Aspects from Customer Reviews: Datasets and Experiments with Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, Language Model, T5  
[Paper Link](http://arxiv.org/abs/2311.02702v1)  

---


**ABSTRACT**  
A restaurant dinner may become a memorable experience due to an unexpected aspect enjoyed by the customer, such as an origami-making station in the waiting area. If aspects that are atypical for a restaurant experience were known in advance, they could be leveraged to make recommendations that have the potential to engender serendipitous experiences, further increasing user satisfaction. Although relatively rare, whenever encountered, atypical aspects often end up being mentioned in reviews due to their memorable quality. Correspondingly, in this paper we introduce the task of detecting atypical aspects in customer reviews. To facilitate the development of extraction models, we manually annotate benchmark datasets of reviews in three domains - restaurants, hotels, and hair salons, which we use to evaluate a number of language models, ranging from fine-tuning the instruction-based text-to-text transformer Flan-T5 to zero-shot and few-shot prompting of GPT-3.5.

{{</citation>}}


### (6/55) Divide & Conquer for Entailment-aware Multi-hop Evidence Retrieval (Fan Luo et al., 2023)

{{<citation>}}

Fan Luo, Mihai Surdeanu. (2023)  
**Divide & Conquer for Entailment-aware Multi-hop Evidence Retrieval**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-IR, cs.CL  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2311.02616v1)  

---


**ABSTRACT**  
Lexical and semantic matches are commonly used as relevance measurements for information retrieval. Together they estimate the semantic equivalence between the query and the candidates. However, semantic equivalence is not the only relevance signal that needs to be considered when retrieving evidences for multi-hop questions. In this work, we demonstrate that textual entailment relation is another important relevance dimension that should be considered. To retrieve evidences that are either semantically equivalent to or entailed by the question simultaneously, we divide the task of evidence retrieval for multi-hop question answering (QA) into two sub-tasks, i.e., semantic textual similarity and inference similarity retrieval. We propose two ensemble models, EAR and EARnest, which tackle each of the sub-tasks separately and then jointly re-rank sentences with the consideration of the diverse relevance signals. Experimental results on HotpotQA verify that our models not only significantly outperform all the single retrieval models it is based on, but is also more effective than two intuitive ensemble baseline models.

{{</citation>}}


### (7/55) mahaNLP: A Marathi Natural Language Processing Library (Vidula Magdum et al., 2023)

{{<citation>}}

Vidula Magdum, Omkar Dhekane, Sharayu Hiwarkhedkar, Saloni Mittal, Raviraj Joshi. (2023)  
**mahaNLP: A Marathi Natural Language Processing Library**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: BERT, NER, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2311.02579v1)  

---


**ABSTRACT**  
We present mahaNLP, an open-source natural language processing (NLP) library specifically built for the Marathi language. It aims to enhance the support for the low-resource Indian language Marathi in the field of NLP. It is an easy-to-use, extensible, and modular toolkit for Marathi text analysis built on state-of-the-art MahaBERT-based transformer models. Our work holds significant importance as other existing Indic NLP libraries provide basic Marathi processing support and rely on older models with restricted performance. Our toolkit stands out by offering a comprehensive array of NLP tasks, encompassing both fundamental preprocessing tasks and advanced NLP tasks like sentiment analysis, NER, hate speech detection, and sentence completion. This paper focuses on an overview of the mahaNLP framework, its features, and its usage. This work is a part of the L3Cube MahaNLP initiative, more information about it can be found at https://github.com/l3cube-pune/MarathiNLP .

{{</citation>}}


### (8/55) BanMANI: A Dataset to Identify Manipulated Social Media News in Bangla (Mahammed Kamruzzaman et al., 2023)

{{<citation>}}

Mahammed Kamruzzaman, Md. Minul Islam Shovon, Gene Louis Kim. (2023)  
**BanMANI: A Dataset to Identify Manipulated Social Media News in Bangla**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: NLP, Social Media  
[Paper Link](http://arxiv.org/abs/2311.02570v1)  

---


**ABSTRACT**  
Initial work has been done to address fake news detection and misrepresentation of news in the Bengali language. However, no work in Bengali yet addresses the identification of specific claims in social media news that falsely manipulates a related news article. At this point, this problem has been tackled in English and a few other languages, but not in the Bengali language. In this paper, we curate a dataset of social media content labeled with information manipulation relative to reference articles, called BanMANI. The dataset collection method we describe works around the limitations of the available NLP tools in Bangla. We expect these techniques will carry over to building similar datasets in other low-resource languages. BanMANI forms the basis both for evaluating the capabilities of existing NLP systems and for training or fine-tuning new models specifically on this task. In our analysis, we find that this task challenges current LLMs both under zero-shot and fine-tuned settings.

{{</citation>}}


### (9/55) Relation Extraction Model Based on Semantic Enhancement Mechanism (Peiyu Liu et al., 2023)

{{<citation>}}

Peiyu Liu, Junping Du, Yingxia Shao, Zeli Guan. (2023)  
**Relation Extraction Model Based on Semantic Enhancement Mechanism**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Relation Extraction  
[Paper Link](http://arxiv.org/abs/2311.02564v1)  

---


**ABSTRACT**  
Relational extraction is one of the basic tasks related to information extraction in the field of natural language processing, and is an important link and core task in the fields of information extraction, natural language understanding, and information retrieval. None of the existing relation extraction methods can effectively solve the problem of triple overlap. The CasAug model proposed in this paper based on the CasRel framework combined with the semantic enhancement mechanism can solve this problem to a certain extent. The CasAug model enhances the semantics of the identified possible subjects by adding a semantic enhancement mechanism, First, based on the semantic coding of possible subjects, pre-classify the possible subjects, and then combine the subject lexicon to calculate the semantic similarity to obtain the similar vocabulary of possible subjects. According to the similar vocabulary obtained, each word in different relations is calculated through the attention mechanism. For the contribution of the possible subject, finally combine the relationship pre-classification results to weight the enhanced semantics of each relationship to find the enhanced semantics of the possible subject, and send the enhanced semantics combined with the possible subject to the object and relationship extraction module. Complete the final relation triplet extraction. The experimental results show that, compared with the baseline model, the CasAug model proposed in this paper has improved the effect of relation extraction, and CasAug's ability to deal with overlapping problems and extract multiple relations is also better than the baseline model, indicating that the semantic enhancement mechanism proposed in this paper It can further reduce the judgment of redundant relations and alleviate the problem of triple overlap.

{{</citation>}}


## cs.CV (17)



### (10/55) Towards Generic Anomaly Detection and Understanding: Large-scale Visual-linguistic Model (GPT-4V) Takes the Lead (Yunkang Cao et al., 2023)

{{<citation>}}

Yunkang Cao, Xiaohao Xu, Chen Sun, Xiaonan Huang, Weiming Shen. (2023)  
**Towards Generic Anomaly Detection and Understanding: Large-scale Visual-linguistic Model (GPT-4V) Takes the Lead**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Anomaly Detection, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2311.02782v1)  

---


**ABSTRACT**  
Anomaly detection is a crucial task across different domains and data types. However, existing anomaly detection models are often designed for specific domains and modalities. This study explores the use of GPT-4V(ision), a powerful visual-linguistic model, to address anomaly detection tasks in a generic manner. We investigate the application of GPT-4V in multi-modality, multi-domain anomaly detection tasks, including image, video, point cloud, and time series data, across multiple application areas, such as industrial, medical, logical, video, 3D anomaly detection, and localization tasks. To enhance GPT-4V's performance, we incorporate different kinds of additional cues such as class information, human expertise, and reference images as prompts.Based on our experiments, GPT-4V proves to be highly effective in detecting and explaining global and fine-grained semantic patterns in zero/one-shot anomaly detection. This enables accurate differentiation between normal and abnormal instances. Although we conducted extensive evaluations in this study, there is still room for future evaluation to further exploit GPT-4V's generic anomaly detection capacity from different aspects. These include exploring quantitative metrics, expanding evaluation benchmarks, incorporating multi-round interactions, and incorporating human feedback loops. Nevertheless, GPT-4V exhibits promising performance in generic anomaly detection and understanding, thus opening up a new avenue for anomaly detection.

{{</citation>}}


### (11/55) Attention Modules Improve Image-Level Anomaly Detection for Industrial Inspection: A DifferNet Case Study (André Luiz Buarque Vieira e Silva et al., 2023)

{{<citation>}}

André Luiz Buarque Vieira e Silva, Francisco Simões, Danny Kowerko, Tobias Schlosser, Felipe Battisti, Veronica Teichrieb. (2023)  
**Attention Modules Improve Image-Level Anomaly Detection for Industrial Inspection: A DifferNet Case Study**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection, Attention  
[Paper Link](http://arxiv.org/abs/2311.02747v2)  

---


**ABSTRACT**  
Within (semi-)automated visual industrial inspection, learning-based approaches for assessing visual defects, including deep neural networks, enable the processing of otherwise small defect patterns in pixel size on high-resolution imagery. The emergence of these often rarely occurring defect patterns explains the general need for labeled data corpora. To alleviate this issue and advance the current state of the art in unsupervised visual inspection, this work proposes a DifferNet-based solution enhanced with attention modules: AttentDifferNet. It improves image-level detection and classification capabilities on three visual anomaly detection datasets for industrial inspection: InsPLAD-fault, MVTec AD, and Semiconductor Wafer. In comparison to the state of the art, AttentDifferNet achieves improved results, which are, in turn, highlighted throughout our quali-quantitative study. Our quantitative evaluation shows an average improvement - compared to DifferNet - of 1.77 +/- 0.25 percentage points in overall AUROC considering all three datasets, reaching SOTA results in InsPLAD-fault, an industrial inspection in-the-wild dataset. As our variants to AttentDifferNet show great prospects in the context of currently investigated approaches, a baseline is formulated, emphasizing the importance of attention for industrial anomaly detection both in the wild and in controlled environments.

{{</citation>}}


### (12/55) ISAR: A Benchmark for Single- and Few-Shot Object Instance Segmentation and Re-Identification (Nicolas Gorlo et al., 2023)

{{<citation>}}

Nicolas Gorlo, Kenneth Blomqvist, Francesco Milano, Roland Siegwart. (2023)  
**ISAR: A Benchmark for Single- and Few-Shot Object Instance Segmentation and Re-Identification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: AI, Few-Shot  
[Paper Link](http://arxiv.org/abs/2311.02734v1)  

---


**ABSTRACT**  
Most object-level mapping systems in use today make use of an upstream learned object instance segmentation model. If we want to teach them about a new object or segmentation class, we need to build a large dataset and retrain the system. To build spatial AI systems that can quickly be taught about new objects, we need to effectively solve the problem of single-shot object detection, instance segmentation and re-identification. So far there is neither a method fulfilling all of these requirements in unison nor a benchmark that could be used to test such a method. Addressing this, we propose ISAR, a benchmark and baseline method for single- and few-shot object Instance Segmentation And Re-identification, in an effort to accelerate the development of algorithms that can robustly detect, segment, and re-identify objects from a single or a few sparse training examples. We provide a semi-synthetic dataset of video sequences with ground-truth semantic annotations, a standardized evaluation pipeline, and a baseline method. Our benchmark aligns with the emerging research trend of unifying Multi-Object Tracking, Video Object Segmentation, and Re-identification.

{{</citation>}}


### (13/55) AV-Lip-Sync+: Leveraging AV-HuBERT to Exploit Multimodal Inconsistency for Video Deepfake Detection (Sahibzada Adil Shahzad et al., 2023)

{{<citation>}}

Sahibzada Adil Shahzad, Ammarah Hashmi, Yan-Tsung Peng, Yu Tsao, Hsin-Min Wang. (2023)  
**AV-Lip-Sync+: Leveraging AV-HuBERT to Exploit Multimodal Inconsistency for Video Deepfake Detection**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs-MM, cs-SD, cs.CV, eess-AS  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2311.02733v1)  

---


**ABSTRACT**  
Multimodal manipulations (also known as audio-visual deepfakes) make it difficult for unimodal deepfake detectors to detect forgeries in multimedia content. To avoid the spread of false propaganda and fake news, timely detection is crucial. The damage to either modality (i.e., visual or audio) can only be discovered through multi-modal models that can exploit both pieces of information simultaneously. Previous methods mainly adopt uni-modal video forensics and use supervised pre-training for forgery detection. This study proposes a new method based on a multi-modal self-supervised-learning (SSL) feature extractor to exploit inconsistency between audio and visual modalities for multi-modal video forgery detection. We use the transformer-based SSL pre-trained Audio-Visual HuBERT (AV-HuBERT) model as a visual and acoustic feature extractor and a multi-scale temporal convolutional neural network to capture the temporal correlation between the audio and visual modalities. Since AV-HuBERT only extracts visual features from the lip region, we also adopt another transformer-based video model to exploit facial features and capture spatial and temporal artifacts caused during the deepfake generation process. Experimental results show that our model outperforms all existing models and achieves new state-of-the-art performance on the FakeAVCeleb and DeepfakeTIMIT datasets.

{{</citation>}}


### (14/55) Nepali Video Captioning using CNN-RNN Architecture (Bipesh Subedi et al., 2023)

{{<citation>}}

Bipesh Subedi, Saugat Singh, Bal Krishna Bal. (2023)  
**Nepali Video Captioning using CNN-RNN Architecture**  

---
Primary Category: cs.CV  
Categories: I-2-7; I-2-10, cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: BLEU, Google, LSTM  
[Paper Link](http://arxiv.org/abs/2311.02699v1)  

---


**ABSTRACT**  
This article presents a study on Nepali video captioning using deep neural networks. Through the integration of pre-trained CNNs and RNNs, the research focuses on generating precise and contextually relevant captions for Nepali videos. The approach involves dataset collection, data preprocessing, model implementation, and evaluation. By enriching the MSVD dataset with Nepali captions via Google Translate, the study trains various CNN-RNN architectures. The research explores the effectiveness of CNNs (e.g., EfficientNetB0, ResNet101, VGG16) paired with different RNN decoders like LSTM, GRU, and BiLSTM. Evaluation involves BLEU and METEOR metrics, with the best model being EfficientNetB0 + BiLSTM with 1024 hidden dimensions, achieving a BLEU-4 score of 17 and METEOR score of 46. The article also outlines challenges and future directions for advancing Nepali video captioning, offering a crucial resource for further research in this area.

{{</citation>}}


### (15/55) ChEF: A Comprehensive Evaluation Framework for Standardized Assessment of Multimodal Large Language Models (Zhelun Shi et al., 2023)

{{<citation>}}

Zhelun Shi, Zhipin Wang, Hongxing Fan, Zhenfei Yin, Lu Sheng, Yu Qiao, Jing Shao. (2023)  
**ChEF: A Comprehensive Evaluation Framework for Standardized Assessment of Multimodal Large Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.02692v1)  

---


**ABSTRACT**  
Multimodal Large Language Models (MLLMs) have shown impressive abilities in interacting with visual content with myriad potential downstream tasks. However, even though a list of benchmarks has been proposed, the capabilities and limitations of MLLMs are still not comprehensively understood, due to a lack of a standardized and holistic evaluation framework. To this end, we present the first Comprehensive Evaluation Framework (ChEF) that can holistically profile each MLLM and fairly compare different MLLMs. First, we structure ChEF as four modular components, i.e., Scenario as scalable multimodal datasets, Instruction as flexible instruction retrieving formulae, Inferencer as reliable question answering strategies, and Metric as indicative task-specific score functions. Based on them, ChEF facilitates versatile evaluations in a standardized framework, and new evaluations can be built by designing new Recipes (systematic selection of these four components). Notably, current MLLM benchmarks can be readily summarized as recipes of ChEF. Second, we introduce 6 new recipes to quantify competent MLLMs' desired capabilities (or called desiderata, i.e., calibration, in-context learning, instruction following, language performance, hallucination, and robustness) as reliable agents that can perform real-world multimodal interactions. Third, we conduct a large-scale evaluation of 9 prominent MLLMs on 9 scenarios and 6 desiderata. Our evaluation summarized over 20 valuable observations concerning the generalizability of MLLMs across various scenarios and the composite capability of MLLMs required for multimodal interactions. We will publicly release all the detailed implementations for further analysis, as well as an easy-to-use modular toolkit for the integration of new recipes and models, so that ChEF can be a growing evaluation framework for the MLLM community.

{{</citation>}}


### (16/55) Octavius: Mitigating Task Interference in MLLMs via MoE (Zeren Chen et al., 2023)

{{<citation>}}

Zeren Chen, Ziqin Wang, Zhen Wang, Huayang Liu, Zhenfei Yin, Si Liu, Lu Sheng, Wanli Ouyang, Yu Qiao, Jing Shao. (2023)  
**Octavius: Mitigating Task Interference in MLLMs via MoE**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2311.02684v1)  

---


**ABSTRACT**  
Recent studies have demonstrated Large Language Models (LLMs) can extend their zero-shot generalization capabilities to multimodal learning through instruction tuning. As more modalities and downstream tasks are introduced, negative conflicts and interference may have a worse impact on performance. While this phenomenon has been overlooked in previous work, we propose a novel and extensible framework, called \mname, for comprehensive studies and experimentation on multimodal learning with Multimodal Large Language Models (MLLMs). Specifically, we combine the well-known Mixture-of-Experts (MoE) and one of the representative PEFT techniques, \emph{i.e.,} LoRA, designing a novel LLM-based decoder, called LoRA-MoE, for multimodal learning. The experimental results (about 20\% improvement) have shown the effectiveness and versatility of our design in various 2D and 3D downstream tasks. Code and corresponding dataset will be available soon.

{{</citation>}}


### (17/55) CCMR: High Resolution Optical Flow Estimation via Coarse-to-Fine Context-Guided Motion Reasoning (Azin Jahedi et al., 2023)

{{<citation>}}

Azin Jahedi, Maximilian Luz, Marc Rivinius, Andrés Bruhn. (2023)  
**CCMR: High Resolution Optical Flow Estimation via Coarse-to-Fine Context-Guided Motion Reasoning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Reasoning  
[Paper Link](http://arxiv.org/abs/2311.02661v1)  

---


**ABSTRACT**  
Attention-based motion aggregation concepts have recently shown their usefulness in optical flow estimation, in particular when it comes to handling occluded regions. However, due to their complexity, such concepts have been mainly restricted to coarse-resolution single-scale approaches that fail to provide the detailed outcome of high-resolution multi-scale networks. In this paper, we hence propose CCMR: a high-resolution coarse-to-fine approach that leverages attention-based motion grouping concepts to multi-scale optical flow estimation. CCMR relies on a hierarchical two-step attention-based context-motion grouping strategy that first computes global multi-scale context features and then uses them to guide the actual motion grouping. As we iterate both steps over all coarse-to-fine scales, we adapt cross covariance image transformers to allow for an efficient realization while maintaining scale-dependent properties. Experiments and ablations demonstrate that our efforts of combining multi-scale and attention-based concepts pay off. By providing highly detailed flow fields with strong improvements in both occluded and non-occluded regions, our CCMR approach not only outperforms both the corresponding single-scale attention-based and multi-scale attention-free baselines by up to 23.0% and 21.6%, respectively, it also achieves state-of-the-art results, ranking first on KITTI 2015 and second on MPI Sintel Clean and Final. Code and trained models are available at https://github.com/cv-stuttgart /CCMR.

{{</citation>}}


### (18/55) New Approach for an Affective Computing-Driven Quality of Experience (QoE) Prediction (Joshua Bègue et al., 2023)

{{<citation>}}

Joshua Bègue, Mohamed Aymen Labiod, Abdelhamid Melloulk. (2023)  
**New Approach for an Affective Computing-Driven Quality of Experience (QoE) Prediction**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-HC, cs-MM, cs.CV  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2311.02647v1)  

---


**ABSTRACT**  
In human interactions, emotion recognition is crucial. For this reason, the topic of computer-vision approaches for automatic emotion recognition is currently being extensively researched. Processing multi-channel electroencephalogram (EEG) information is one of the most researched methods for automatic emotion recognition. This paper presents a new model for an affective computing-driven Quality of Experience (QoE) prediction. In order to validate the proposed model, a publicly available dataset is used. The dataset contains EEG, ECG, and respiratory data and is focused on a multimedia QoE assessment context. The EEG data are retained on which the differential entropy and the power spectral density are calculated with an observation window of three seconds. These two features were extracted to train several deep-learning models to investigate the possibility of predicting QoE with five different factors. The performance of these models is compared, and the best model is optimized to improve the results. The best results were obtained with an LSTM-based model, presenting an F1-score from 68% to 78%. An analysis of the model and its features shows that the Delta frequency band is the least necessary, that two electrodes have a higher importance, and that two other electrodes have a very low impact on the model's performances.

{{</citation>}}


### (19/55) PotholeGuard: A Pothole Detection Approach by Point Cloud Semantic Segmentation (Sahil Nawale et al., 2023)

{{<citation>}}

Sahil Nawale, Dhruv Khut, Daksh Dave, Gauransh Sawhney, Pushkar Aggrawal, Dr. Kailas Devadakar. (2023)  
**PotholeGuard: A Pothole Detection Approach by Point Cloud Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2311.02641v1)  

---


**ABSTRACT**  
Pothole detection is crucial for road safety and maintenance, traditionally relying on 2D image segmentation. However, existing 3D Semantic Pothole Segmentation research often overlooks point cloud sparsity, leading to suboptimal local feature capture and segmentation accuracy. Our research presents an innovative point cloud-based pothole segmentation architecture. Our model efficiently identifies hidden features and uses a feedback mechanism to enhance local characteristics, improving feature presentation. We introduce a local relationship learning module to understand local shape relationships, enhancing structural insights. Additionally, we propose a lightweight adaptive structure for refining local point features using the K nearest neighbor algorithm, addressing point cloud density differences and domain selection. Shared MLP Pooling is integrated to learn deep aggregation features, facilitating semantic data exploration and segmentation guidance. Extensive experiments on three public datasets confirm PotholeGuard's superior performance over state-of-the-art methods. Our approach offers a promising solution for robust and accurate 3D pothole segmentation, with applications in road maintenance and safety.

{{</citation>}}


### (20/55) Exploring Grounding Potential of VQA-oriented GPT-4V for Zero-shot Anomaly Detection (Jiangning Zhang et al., 2023)

{{<citation>}}

Jiangning Zhang, Xuhai Chen, Zhucun Xue, Yabiao Wang, Chengjie Wang, Yong Liu. (2023)  
**Exploring Grounding Potential of VQA-oriented GPT-4V for Zero-shot Anomaly Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection, GPT, GPT-4, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2311.02612v1)  

---


**ABSTRACT**  
Large Multimodal Model (LMM) GPT-4V(ision) endows GPT-4 with visual grounding capabilities, making it possible to handle certain tasks through the Visual Question Answering (VQA) paradigm. This paper explores the potential of VQA-oriented GPT-4V in the recently popular visual Anomaly Detection (AD) and is the first to conduct qualitative and quantitative evaluations on the popular MVTec AD and VisA datasets. Considering that this task requires both image-/pixel-level evaluations, the proposed GPT-4V-AD framework contains three components: 1) Granular Region Division, 2) Prompt Designing, 3) Text2Segmentation for easy quantitative evaluation, and have made some different attempts for comparative analysis. The results show that GPT-4V can achieve certain results in the zero-shot AD task through a VQA paradigm, such as achieving image-level 77.1/88.0 and pixel-level 68.0/76.6 AU-ROCs on MVTec AD and VisA datasets, respectively. However, its performance still has a certain gap compared to the state-of-the-art zero-shot method, e.g., WinCLIP ann CLIP-AD, and further research is needed. This study provides a baseline reference for the research of VQA-oriented LMM in the zero-shot AD task, and we also post several possible future works. Code is available at \url{https://github.com/zhangzjn/GPT-4V-AD}.

{{</citation>}}


### (21/55) Learning Class and Domain Augmentations for Single-Source Open-Domain Generalization (Prathmesh Bele et al., 2023)

{{<citation>}}

Prathmesh Bele, Valay Bundele, Avigyan Bhattacharya, Ankit Jha, Gemma Roig, Biplab Banerjee. (2023)  
**Learning Class and Domain Augmentations for Single-Source Open-Domain Generalization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2311.02599v1)  

---


**ABSTRACT**  
Single-source open-domain generalization (SS-ODG) addresses the challenge of labeled source domains with supervision during training and unlabeled novel target domains during testing. The target domain includes both known classes from the source domain and samples from previously unseen classes. Existing techniques for SS-ODG primarily focus on calibrating source-domain classifiers to identify open samples in the target domain. However, these methods struggle with visually fine-grained open-closed data, often misclassifying open samples as closed-set classes. Moreover, relying solely on a single source domain restricts the model's ability to generalize. To overcome these limitations, we propose a novel framework called SODG-Net that simultaneously synthesizes novel domains and generates pseudo-open samples using a learning-based objective, in contrast to the ad-hoc mixing strategies commonly found in the literature. Our approach enhances generalization by diversifying the styles of known class samples using a novel metric criterion and generates diverse pseudo-open samples to train a unified and confident multi-class classifier capable of handling both open and closed-set data. Extensive experimental evaluations conducted on multiple benchmarks consistently demonstrate the superior performance of SODG-Net compared to the literature.

{{</citation>}}


### (22/55) Automated Camera Calibration via Homography Estimation with GNNs (Giacomo D'Amicantonio et al., 2023)

{{<citation>}}

Giacomo D'Amicantonio, Egor Bondarev, Peter H. N. De With. (2023)  
**Automated Camera Calibration via Homography Estimation with GNNs**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.02598v1)  

---


**ABSTRACT**  
Over the past few decades, a significant rise of camera-based applications for traffic monitoring has occurred. Governments and local administrations are increasingly relying on the data collected from these cameras to enhance road safety and optimize traffic conditions. However, for effective data utilization, it is imperative to ensure accurate and automated calibration of the involved cameras. This paper proposes a novel approach to address this challenge by leveraging the topological structure of intersections. We propose a framework involving the generation of a set of synthetic intersection viewpoint images from a bird's-eye-view image, framed as a graph of virtual cameras to model these images. Using the capabilities of Graph Neural Networks, we effectively learn the relationships within this graph, thereby facilitating the estimation of a homography matrix. This estimation leverages the neighbourhood representation for any real-world camera and is enhanced by exploiting multiple images instead of a single match. In turn, the homography matrix allows the retrieval of extrinsic calibration parameters. As a result, the proposed framework demonstrates superior performance on both synthetic datasets and real-world cameras, setting a new state-of-the-art benchmark.

{{</citation>}}


### (23/55) Multiple Object Tracking based on Occlusion-Aware Embedding Consistency Learning (Yaoqi Hu et al., 2023)

{{<citation>}}

Yaoqi Hu, Axi Niu, Yu Zhu, Qingsen Yan, Jinqiu Sun, Yanning Zhang. (2023)  
**Multiple Object Tracking based on Occlusion-Aware Embedding Consistency Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2311.02572v1)  

---


**ABSTRACT**  
The Joint Detection and Embedding (JDE) framework has achieved remarkable progress for multiple object tracking. Existing methods often employ extracted embeddings to re-establish associations between new detections and previously disrupted tracks. However, the reliability of embeddings diminishes when the region of the occluded object frequently contains adjacent objects or clutters, especially in scenarios with severe occlusion. To alleviate this problem, we propose a novel multiple object tracking method based on visual embedding consistency, mainly including: 1) Occlusion Prediction Module (OPM) and 2) Occlusion-Aware Association Module (OAAM). The OPM predicts occlusion information for each true detection, facilitating the selection of valid samples for consistency learning of the track's visual embedding. The OAAM leverages occlusion cues and visual embeddings to generate two separate embeddings for each track, guaranteeing consistency in both unoccluded and occluded detections. By integrating these two modules, our method is capable of addressing track interruptions caused by occlusion in online tracking scenarios. Extensive experimental results demonstrate that our approach achieves promising performance levels in both unoccluded and occluded tracking scenarios.

{{</citation>}}


### (24/55) Rotation Invariant Transformer for Recognizing Object in UAVs (Shuoyi Chen et al., 2023)

{{<citation>}}

Shuoyi Chen, Mang Ye, Bo Du. (2023)  
**Rotation Invariant Transformer for Recognizing Object in UAVs**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reasoning, Transformer  
[Paper Link](http://arxiv.org/abs/2311.02559v1)  

---


**ABSTRACT**  
Recognizing a target of interest from the UAVs is much more challenging than the existing object re-identification tasks across multiple city cameras. The images taken by the UAVs usually suffer from significant size difference when generating the object bounding boxes and uncertain rotation variations. Existing methods are usually designed for city cameras, incapable of handing the rotation issue in UAV scenarios. A straightforward solution is to perform the image-level rotation augmentation, but it would cause loss of useful information when inputting the powerful vision transformer as patches. This motivates us to simulate the rotation operation at the patch feature level, proposing a novel rotation invariant vision transformer (RotTrans). This strategy builds on high-level features with the help of the specificity of the vision transformer structure, which enhances the robustness against large rotation differences. In addition, we design invariance constraint to establish the relationship between the original feature and the rotated features, achieving stronger rotation invariance. Our proposed transformer tested on the latest UAV datasets greatly outperforms the current state-of-the-arts, which is 5.9\% and 4.8\% higher than the highest mAP and Rank1. Notably, our model also performs competitively for the person re-identification task on traditional city cameras. In particular, our solution wins the first place in the UAV-based person re-recognition track in the Multi-Modal Video Reasoning and Analyzing Competition held in ICCV 2021. Code is available at https://github.com/whucsy/RotTrans.

{{</citation>}}


### (25/55) Augment the Pairs: Semantics-Preserving Image-Caption Pair Augmentation for Grounding-Based Vision and Language Models (Jingru Yi et al., 2023)

{{<citation>}}

Jingru Yi, Burak Uzkent, Oana Ignat, Zili Li, Amanmeet Garg, Xiang Yu, Linda Liu. (2023)  
**Augment the Pairs: Semantics-Preserving Image-Caption Pair Augmentation for Grounding-Based Vision and Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2311.02536v1)  

---


**ABSTRACT**  
Grounding-based vision and language models have been successfully applied to low-level vision tasks, aiming to precisely locate objects referred in captions. The effectiveness of grounding representation learning heavily relies on the scale of the training dataset. Despite being a useful data enrichment strategy, data augmentation has received minimal attention in existing vision and language tasks as augmentation for image-caption pairs is non-trivial. In this study, we propose a robust phrase grounding model trained with text-conditioned and text-unconditioned data augmentations. Specifically, we apply text-conditioned color jittering and horizontal flipping to ensure semantic consistency between images and captions. To guarantee image-caption correspondence in the training samples, we modify the captions according to pre-defined keywords when applying horizontal flipping. Additionally, inspired by recent masked signal reconstruction, we propose to use pixel-level masking as a novel form of data augmentation. While we demonstrate our data augmentation method with MDETR framework, the proposed approach is applicable to common grounding-based vision and language tasks with other frameworks. Finally, we show that image encoder pretrained on large-scale image and language datasets (such as CLIP) can further improve the results. Through extensive experiments on three commonly applied datasets: Flickr30k, referring expressions and GQA, our method demonstrates advanced performance over the state-of-the-arts with various metrics. Code can be found in https://github.com/amzn/augment-the-pairs-wacv2024.

{{</citation>}}


### (26/55) TokenMotion: Motion-Guided Vision Transformer for Video Camouflaged Object Detection Via Learnable Token Selection (Zifan Yu et al., 2023)

{{<citation>}}

Zifan Yu, Erfan Bank Tavakoli, Meida Chen, Suya You, Raghuveer Rao, Sanjeev Agarwal, Fengbo Ren. (2023)  
**TokenMotion: Motion-Guided Vision Transformer for Video Camouflaged Object Detection Via Learnable Token Selection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection, Transformer  
[Paper Link](http://arxiv.org/abs/2311.02535v1)  

---


**ABSTRACT**  
The area of Video Camouflaged Object Detection (VCOD) presents unique challenges in the field of computer vision due to texture similarities between target objects and their surroundings, as well as irregular motion patterns caused by both objects and camera movement. In this paper, we introduce TokenMotion (TMNet), which employs a transformer-based model to enhance VCOD by extracting motion-guided features using a learnable token selection. Evaluated on the challenging MoCA-Mask dataset, TMNet achieves state-of-the-art performance in VCOD. It outperforms the existing state-of-the-art method by a 12.8% improvement in weighted F-measure, an 8.4% enhancement in S-measure, and a 10.7% boost in mean IoU. The results demonstrate the benefits of utilizing motion-guided features via learnable token selection within a transformer-based framework to tackle the intricate task of VCOD.

{{</citation>}}


## cs.PL (1)



### (27/55) Architecting Intermediate Layers for Efficient Composition of Data Management and Machine Learning Systems (Supun Abeysinghe et al., 2023)

{{<citation>}}

Supun Abeysinghe, Fei Wang, Gregory Essertel, Tiark Rompf. (2023)  
**Architecting Intermediate Layers for Efficient Composition of Data Management and Machine Learning Systems**  

---
Primary Category: cs.PL  
Categories: cs-PL, cs.PL  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2311.02781v1)  

---


**ABSTRACT**  
Modern data analytics workloads combine relational data processing with machine learning (ML). Most DBMS handle these workloads by offloading these ML operations to external specialized ML systems. While both DBMS and ML systems go to great lengths to optimize performance for their specific workloads, significant performance is lost when used in combination, due to data movement across system boundaries, conversions between incompatible internal data formats, and the lack of cross system optimizations.   A key idea to remove these bottlenecks is to integrate existing data manipulation systems with ML systems by building a common intermediate layer (IR). Although this idea has been explored before (Weld, Delite), previous such attempts require significant re-engineering of prior systems and still fall short in achieving best-of-breed performance for individual tasks (e.g., SQL, Deep Learning). Specifically, they rely on re-implementing existing systems using a generic set of operators and fail to match best-of-breed individual performance due to the inability to recover high-level optimizations from this generic IR through compiler analysis.   We present Flern, the first intermediate-layer integration between DB and ML systems that are best-of-breed individually, competitive with the best compiled query engines such as HyPer on comprehensive relational benchmarks (TPC-H) and competitive with TensorFlow and PyTorch in state-of-the-art ML models (e.g., DeepSpeech, SqueezeNet, Transformers) and also represents a new state-of-the-art for integration. A key realization is to architect intermediate layers based on generative programming capabilities, which preserves high-level contextual information for cross optimizations and enables the construction of a variety of complex structures and cross system optimizations with minimal effort.

{{</citation>}}


## cs.LG (12)



### (28/55) ChaTA: Towards an Intelligent Question-Answer Teaching Assistant using Open-Source LLMs (Yann Hicke et al., 2023)

{{<citation>}}

Yann Hicke, Anmol Agarwal, Qianou Ma, Paul Denny. (2023)  
**ChaTA: Towards an Intelligent Question-Answer Teaching Assistant using Open-Source LLMs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: LLaMA, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2311.02775v1)  

---


**ABSTRACT**  
To address the challenges of scalable and intelligent question-answering (QA), we introduce an innovative solution that leverages open-source Large Language Models (LLMs) to ensure data privacy. We use models from the LLaMA-2 family and augmentations including retrieval augmented generation (RAG), supervised fine-tuning (SFT), and an alternative to reinforcement learning with human feedback (RLHF). We perform our experiments on a Piazza dataset from an introductory CS course with 10k QA pairs and 1.5k pairs of preferences data and conduct both human evaluations and automatic LLM evaluations on a small subset. We find preliminary evidence that modeling techniques collectively enhance the quality of answers by 33%, and RAG is an impactful addition. This work paves the way for the development of ChaTA, an intelligent QA assistant customizable for courses with an online QA platform.

{{</citation>}}


### (29/55) ELEGANT: Certified Defense on the Fairness of Graph Neural Networks (Yushun Dong et al., 2023)

{{<citation>}}

Yushun Dong, Binchi Zhang, Hanghang Tong, Jundong Li. (2023)  
**ELEGANT: Certified Defense on the Fairness of Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG, stat-ML  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2311.02757v1)  

---


**ABSTRACT**  
Graph Neural Networks (GNNs) have emerged as a prominent graph learning model in various graph-based tasks over the years. Nevertheless, due to the vulnerabilities of GNNs, it has been empirically proved that malicious attackers could easily corrupt the fairness level of their predictions by adding perturbations to the input graph data. In this paper, we take crucial steps to study a novel problem of certifiable defense on the fairness level of GNNs. Specifically, we propose a principled framework named ELEGANT and present a detailed theoretical certification analysis for the fairness of GNNs. ELEGANT takes any GNNs as its backbone, and the fairness level of such a backbone is theoretically impossible to be corrupted under certain perturbation budgets for attackers. Notably, ELEGANT does not have any assumption over the GNN structure or parameters, and does not require re-training the GNNs to realize certification. Hence it can serve as a plug-and-play framework for any optimized GNNs ready to be deployed. We verify the satisfactory effectiveness of ELEGANT in practice through extensive experiments on real-world datasets across different backbones of GNNs, where ELEGANT is also demonstrated to be beneficial for GNN debiasing. Open-source code can be found at https://github.com/yushundong/ELEGANT.

{{</citation>}}


### (30/55) Staged Reinforcement Learning for Complex Tasks through Decomposed Environments (Rafael Pina et al., 2023)

{{<citation>}}

Rafael Pina, Corentin Artaud, Xiaolan Liu, Varuna De Silva. (2023)  
**Staged Reinforcement Learning for Complex Tasks through Decomposed Environments**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02746v1)  

---


**ABSTRACT**  
Reinforcement Learning (RL) is an area of growing interest in the field of artificial intelligence due to its many notable applications in diverse fields. Particularly within the context of intelligent vehicle control, RL has made impressive progress. However, currently it is still in simulated controlled environments where RL can achieve its full super-human potential. Although how to apply simulation experience in real scenarios has been studied, how to approximate simulated problems to the real dynamic problems is still a challenge. In this paper, we discuss two methods that approximate RL problems to real problems. In the context of traffic junction simulations, we demonstrate that, if we can decompose a complex task into multiple sub-tasks, solving these tasks first can be advantageous to help minimising possible occurrences of catastrophic events in the complex task. From a multi-agent perspective, we introduce a training structuring mechanism that exploits the use of experience learned under the popular paradigm called Centralised Training Decentralised Execution (CTDE). This experience can then be leveraged in fully decentralised settings that are conceptually closer to real settings, where agents often do not have access to a central oracle and must be treated as isolated independent units. The results show that the proposed approaches improve agents performance in complex tasks related to traffic junctions, minimising potential safety-critical problems that might happen in these scenarios. Although still in simulation, the investigated situations are conceptually closer to real scenarios and thus, with these results, we intend to motivate further research in the subject.

{{</citation>}}


### (31/55) Learning Independently from Causality in Multi-Agent Environments (Rafael Pina et al., 2023)

{{<citation>}}

Rafael Pina, Varuna De Silva, Corentin Artaud. (2023)  
**Learning Independently from Causality in Multi-Agent Environments**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-MA, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02741v1)  

---


**ABSTRACT**  
Multi-Agent Reinforcement Learning (MARL) comprises an area of growing interest in the field of machine learning. Despite notable advances, there are still problems that require investigation. The lazy agent pathology is a famous problem in MARL that denotes the event when some of the agents in a MARL team do not contribute to the common goal, letting the teammates do all the work. In this work, we aim to investigate this problem from a causality-based perspective. We intend to create the bridge between the fields of MARL and causality and argue about the usefulness of this link. We study a fully decentralised MARL setup where agents need to learn cooperation strategies and show that there is a causal relation between individual observations and the team reward. The experiments carried show how this relation can be used to improve independent agents in MARL, resulting not only on better performances as a team but also on the rise of more intelligent behaviours on individual agents.

{{</citation>}}


### (32/55) Architecture Matters: Uncovering Implicit Mechanisms in Graph Contrastive Learning (Xiaojun Guo et al., 2023)

{{<citation>}}

Xiaojun Guo, Yifei Wang, Zeming Wei, Yisen Wang. (2023)  
**Architecture Matters: Uncovering Implicit Mechanisms in Graph Contrastive Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Contrastive Learning, GNN  
[Paper Link](http://arxiv.org/abs/2311.02687v1)  

---


**ABSTRACT**  
With the prosperity of contrastive learning for visual representation learning (VCL), it is also adapted to the graph domain and yields promising performance. However, through a systematic study of various graph contrastive learning (GCL) methods, we observe that some common phenomena among existing GCL methods that are quite different from the original VCL methods, including 1) positive samples are not a must for GCL; 2) negative samples are not necessary for graph classification, neither for node classification when adopting specific normalization modules; 3) data augmentations have much less influence on GCL, as simple domain-agnostic augmentations (e.g., Gaussian noise) can also attain fairly good performance. By uncovering how the implicit inductive bias of GNNs works in contrastive learning, we theoretically provide insights into the above intriguing properties of GCL. Rather than directly porting existing VCL methods to GCL, we advocate for more attention toward the unique architecture of graph learning and consider its implicit influence when designing GCL methods. Code is available at https: //github.com/PKU-ML/ArchitectureMattersGCL.

{{</citation>}}


### (33/55) A Critical Perceptual Pre-trained Model for Complex Trajectory Recovery (Dedong Li et al., 2023)

{{<citation>}}

Dedong Li, Ziyue Li, Zhishuai Li, Lei Bai, Qingyuan Gong, Lijun Sun, Wolfgang Ketter, Rui Zhao. (2023)  
**A Critical Perceptual Pre-trained Model for Complex Trajectory Recovery**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2311.02631v1)  

---


**ABSTRACT**  
The trajectory on the road traffic is commonly collected at a low sampling rate, and trajectory recovery aims to recover a complete and continuous trajectory from the sparse and discrete inputs. Recently, sequential language models have been innovatively adopted for trajectory recovery in a pre-trained manner: it learns road segment representation vectors, which will be used in the downstream tasks. However, existing methods are incapable of handling complex trajectories: when the trajectory crosses remote road segments or makes several turns, which we call critical nodes, the quality of learned representations deteriorates, and the recovered trajectories skip the critical nodes. This work is dedicated to offering a more robust trajectory recovery for complex trajectories. Firstly, we define the trajectory complexity based on the detour score and entropy score and construct the complexity-aware semantic graphs correspondingly. Then, we propose a Multi-view Graph and Complexity Aware Transformer (MGCAT) model to encode these semantics in trajectory pre-training from two aspects: 1) adaptively aggregate the multi-view graph features considering trajectory pattern, and 2) higher attention to critical nodes in a complex trajectory. Such that, our MGCAT is perceptual when handling the critical scenario of complex trajectories. Extensive experiments are conducted on large-scale datasets. The results prove that our method learns better representations for trajectory recovery, with 5.22% higher F1-score overall and 8.16% higher F1-score for complex trajectories particularly. The code is available at https://github.com/bonaldli/ComplexTraj.

{{</citation>}}


### (34/55) Neural Networks Are Implicit Decision Trees: The Hierarchical Simplicity Bias (Zhehang Du, 2023)

{{<citation>}}

Zhehang Du. (2023)  
**Neural Networks Are Implicit Decision Trees: The Hierarchical Simplicity Bias**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.02622v1)  

---


**ABSTRACT**  
Neural networks exhibit simplicity bias; they rely on simpler features while ignoring equally predictive but more complex features. In this work, we introduce a novel approach termed imbalanced label coupling to investigate scenarios where simple and complex features exhibit different levels of predictive power. In these cases, complex features still contribute to predictions. The trained networks make predictions in alignment with the ascending complexity of input features according to how they correlate with the label in the training set, irrespective of the underlying predictive power. For instance, even when simple spurious features distort predictions in CIFAR-10, most cats are predicted to be dogs, and most trucks are predicted to be automobiles! This observation provides direct evidence that the neural network learns core features in the presence of spurious features. We empirically show that last-layer retraining with target data distribution is effective, yet insufficient to fully recover core features when spurious features are perfectly correlated with the target labels in our synthetic dataset. We hope our research contributes to a deeper understanding of the implicit bias of neural networks.

{{</citation>}}


### (35/55) AIOps-Driven Enhancement of Log Anomaly Detection in Unsupervised Scenarios (Daksh Dave et al., 2023)

{{<citation>}}

Daksh Dave, Gauransh Sawhney, Dhruv Khut, Sahil Nawale, Pushkar Aggrawal, Prasenjit Bhavathankar. (2023)  
**AIOps-Driven Enhancement of Log Anomaly Detection in Unsupervised Scenarios**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-IR, cs-IT, cs-LG, cs.LG, math-IT  
Keywords: AI, Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2311.02621v1)  

---


**ABSTRACT**  
Artificial intelligence operations (AIOps) play a pivotal role in identifying, mitigating, and analyzing anomalous system behaviors and alerts. However, the research landscape in this field remains limited, leaving significant gaps unexplored. This study introduces a novel hybrid framework through an innovative algorithm that incorporates an unsupervised strategy. This strategy integrates Principal Component Analysis (PCA) and Artificial Neural Networks (ANNs) and uses a custom loss function to substantially enhance the effectiveness of log anomaly detection. The proposed approach encompasses the utilization of both simulated and real-world datasets, including logs from SockShop and Hadoop Distributed File System (HDFS). The experimental results are highly promising, demonstrating significant reductions in pseudo-positives. Moreover, this strategy offers notable advantages, such as the ability to process logs in their raw, unprocessed form, and the potential for further enhancements. The successful implementation of this approach showcases a remarkable reduction in anomalous logs, thus unequivocally establishing the efficacy of the proposed methodology. Ultimately, this study makes a substantial contribution to the advancement of log anomaly detection within AIOps platforms, addressing the critical need for effective and efficient log analysis in modern and complex systems.

{{</citation>}}


### (36/55) Differentially Private Pre-Trained Model Fusion using Decentralized Federated Graph Matching (Qian Chen et al., 2023)

{{<citation>}}

Qian Chen, Yiqiang Chen, Xinlong Jiang, Teng Zhang, Weiwei Dai, Wuliang Huang, Zhen Yan, Bo Ye. (2023)  
**Differentially Private Pre-Trained Model Fusion using Decentralized Federated Graph Matching**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: Pre-Trained Model  
[Paper Link](http://arxiv.org/abs/2311.03396v1)  

---


**ABSTRACT**  
Model fusion is becoming a crucial component in the context of model-as-a-service scenarios, enabling the delivery of high-quality model services to local users. However, this approach introduces privacy risks and imposes certain limitations on its applications. Ensuring secure model exchange and knowledge fusion among users becomes a significant challenge in this setting. To tackle this issue, we propose PrivFusion, a novel architecture that preserves privacy while facilitating model fusion under the constraints of local differential privacy. PrivFusion leverages a graph-based structure, enabling the fusion of models from multiple parties without necessitating retraining. By employing randomized mechanisms, PrivFusion ensures privacy guarantees throughout the fusion process. To enhance model privacy, our approach incorporates a hybrid local differentially private mechanism and decentralized federated graph matching, effectively protecting both activation values and weights. Additionally, we introduce a perturbation filter adapter to alleviate the impact of randomized noise, thereby preserving the utility of the fused model. Through extensive experiments conducted on diverse image datasets and real-world healthcare applications, we provide empirical evidence showcasing the effectiveness of PrivFusion in maintaining model performance while preserving privacy. Our contributions offer valuable insights and practical solutions for secure and collaborative data analysis within the domain of privacy-preserving model fusion.

{{</citation>}}


### (37/55) Ego-Network Transformer for Subsequence Classification in Time Series Data (Chin-Chia Michael Yeh et al., 2023)

{{<citation>}}

Chin-Chia Michael Yeh, Huiyuan Chen, Yujie Fan, Xin Dai, Yan Zheng, Vivian Lai, Junpeng Wang, Zhongfang Zhuang, Liang Wang, Wei Zhang, Eamonn Keogh. (2023)  
**Ego-Network Transformer for Subsequence Classification in Time Series Data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series, Transformer  
[Paper Link](http://arxiv.org/abs/2311.02561v1)  

---


**ABSTRACT**  
Time series classification is a widely studied problem in the field of time series data mining. Previous research has predominantly focused on scenarios where relevant or foreground subsequences have already been extracted, with each subsequence corresponding to a single label. However, real-world time series data often contain foreground subsequences that are intertwined with background subsequences. Successfully classifying these relevant subsequences requires not only distinguishing between different classes but also accurately identifying the foreground subsequences amidst the background. To address this challenge, we propose a novel subsequence classification method that represents each subsequence as an ego-network, providing crucial nearest neighbor information to the model. The ego-networks of all subsequences collectively form a time series subsequence graph, and we introduce an algorithm to efficiently construct this graph. Furthermore, we have demonstrated the significance of enforcing temporal consistency in the prediction of adjacent subsequences for the subsequence classification problem. To evaluate the effectiveness of our approach, we conducted experiments using 128 univariate and 30 multivariate time series datasets. The experimental results demonstrate the superior performance of our method compared to alternative approaches. Specifically, our method outperforms the baseline on 104 out of 158 datasets.

{{</citation>}}


### (38/55) Preliminary Analysis on Second-Order Convergence for Biased Policy Gradient Methods (Siqiao Mu et al., 2023)

{{<citation>}}

Siqiao Mu, Diego Klabjan. (2023)  
**Preliminary Analysis on Second-Order Convergence for Biased Policy Gradient Methods**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2311.02546v1)  

---


**ABSTRACT**  
Although the convergence of policy gradient algorithms to first-order stationary points is well-established, the objective functions of reinforcement learning problems are typically highly nonconvex. Therefore, recent work has focused on two extensions: ``global" convergence guarantees under regularity assumptions on the function structure, and second-order guarantees for escaping saddle points and convergence to true local minima. Our work expands on the latter approach, avoiding the restrictive assumptions of the former that may not apply to general objective functions. Existing results on vanilla policy gradient only consider an unbiased gradient estimator, but practical implementations under the infinite-horizon discounted setting, including both Monte-Carlo methods and actor-critic methods, involve gradient descent updates with a biased gradient estimator. We present preliminary results on the convergence of biased policy gradient algorithms to second-order stationary points, leveraging proof techniques from nonconvex optimization. In our next steps we aim to provide the first finite-time second-order convergence analysis for actor-critic algorithms.

{{</citation>}}


### (39/55) Nonlinear Multi-objective Reinforcement Learning with Provable Guarantees (Nianli Peng et al., 2023)

{{<citation>}}

Nianli Peng, Brandon Fain. (2023)  
**Nonlinear Multi-objective Reinforcement Learning with Provable Guarantees**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02544v1)  

---


**ABSTRACT**  
We describe RA-E3 (Reward-Aware Explicit Explore or Exploit), an algorithm with provable guarantees for solving a single or multi-objective Markov Decision Process (MDP) where we want to maximize the expected value of a nonlinear function over accumulated rewards. This allows us to model fairness-aware welfare optimization for multi-objective reinforcement learning as well as risk-aware reinforcement learning with nonlinear Von Neumann-Morgenstern utility functions in the single objective setting. RA-E3 extends the classic E3 algorithm that solves MDPs with scalar rewards and linear preferences. We first state a distinct reward-aware version of value iteration that calculates a non-stationary policy that is approximately optimal for a given model of the environment. This sub-procedure is based on an extended form of Bellman optimality for nonlinear optimization that explicitly considers time and current accumulated reward. We then describe how to use this optimization procedure in a larger algorithm that must simultaneously learn a model of the environment. The algorithm learns an approximately optimal policy in time that depends polynomially on the MDP size, desired approximation, and smoothness of the nonlinear function, and exponentially on the number of objectives.

{{</citation>}}


## cs.SD (1)



### (40/55) Attention or Convolution: Transformer Encoders in Audio Language Models for Inference Efficiency (Sungho Jeon et al., 2023)

{{<citation>}}

Sungho Jeon, Ching-Feng Yeh, Hakan Inan, Wei-Ning Hsu, Rashi Rungta, Yashar Mehdad, Daniel Bikel. (2023)  
**Attention or Convolution: Transformer Encoders in Audio Language Models for Inference Efficiency**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-SD, cs.SD, eess-AS  
Keywords: Attention, Language Model, Transformer  
[Paper Link](http://arxiv.org/abs/2311.02772v1)  

---


**ABSTRACT**  
In this paper, we show that a simple self-supervised pre-trained audio model can achieve comparable inference efficiency to more complicated pre-trained models with speech transformer encoders. These speech transformers rely on mixing convolutional modules with self-attention modules. They achieve state-of-the-art performance on ASR with top efficiency. We first show that employing these speech transformers as an encoder significantly improves the efficiency of pre-trained audio models as well. However, our study shows that we can achieve comparable efficiency with advanced self-attention solely. We demonstrate that this simpler approach is particularly beneficial with a low-bit weight quantization technique of a neural network to improve efficiency. We hypothesize that it prevents propagating the errors between different quantized modules compared to recent speech transformers mixing quantized convolution and the quantized self-attention modules.

{{</citation>}}


## cs.AI (2)



### (41/55) Causal Question Answering with Reinforcement Learning (Lukas Blübaum et al., 2023)

{{<citation>}}

Lukas Blübaum, Stefan Heindorf. (2023)  
**Causal Question Answering with Reinforcement Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-LG, cs.AI  
Keywords: Question Answering, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02760v1)  

---


**ABSTRACT**  
Causal questions inquire about causal relationships between different events or phenomena. Specifically, they often aim to determine whether there is a relationship between two phenomena, or to identify all causes/effects of a phenomenon. Causal questions are important for a variety of use cases, including virtual assistants and search engines. However, many current approaches to causal question answering cannot provide explanations or evidence for their answers. Hence, in this paper, we aim to answer causal questions with CauseNet, a large-scale dataset of causal relations and their provenance data. Inspired by recent, successful applications of reinforcement learning to knowledge graph tasks, such as link prediction and fact-checking, we explore the application of reinforcement learning on CauseNet for causal question answering. We introduce an Actor-Critic based agent which learns to search through the graph to answer causal questions. We bootstrap the agent with a supervised learning procedure to deal with large action spaces and sparse rewards. Our evaluation shows that the agent successfully prunes the search space to answer binary causal questions by visiting less than 30 nodes per question compared to over 3,000 nodes by a naive breadth-first search. Our ablation study indicates that our supervised learning strategy provides a strong foundation upon which our reinforcement learning agent improves. The paths returned by our agent explain the mechanisms by which a cause produces an effect. Moreover, for each edge on a path, CauseNet stores its original source on the web allowing for easy verification of paths.

{{</citation>}}


### (42/55) FloodBrain: Flood Disaster Reporting by Web-based Retrieval Augmented Generation with an LLM (Grace Colverd et al., 2023)

{{<citation>}}

Grace Colverd, Paul Darm, Leonard Silverberg, Noah Kasmanoff. (2023)  
**FloodBrain: Flood Disaster Reporting by Web-based Retrieval Augmented Generation with an LLM**  

---
Primary Category: cs.AI  
Categories: I-2-7, cs-AI, cs-CL, cs.AI  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2311.02597v1)  

---


**ABSTRACT**  
Fast disaster impact reporting is crucial in planning humanitarian assistance. Large Language Models (LLMs) are well known for their ability to write coherent text and fulfill a variety of tasks relevant to impact reporting, such as question answering or text summarization. However, LLMs are constrained by the knowledge within their training data and are prone to generating inaccurate, or "hallucinated", information. To address this, we introduce a sophisticated pipeline embodied in our tool FloodBrain (floodbrain.com), specialized in generating flood disaster impact reports by extracting and curating information from the web. Our pipeline assimilates information from web search results to produce detailed and accurate reports on flood events. We test different LLMs as backbones in our tool and compare their generated reports to human-written reports on different metrics. Similar to other studies, we find a notable correlation between the scores assigned by GPT-4 and the scores given by human evaluators when comparing our generated reports to human-authored ones. Additionally, we conduct an ablation study to test our single pipeline components and their relevancy for the final reports. With our tool, we aim to advance the use of LLMs for disaster impact reporting and reduce the time for coordination of humanitarian efforts in the wake of flood disasters.

{{</citation>}}


## cs.AR (1)



### (43/55) M4BRAM: Mixed-Precision Matrix-Matrix Multiplication in FPGA Block RAMs (Yuzong Chen et al., 2023)

{{<citation>}}

Yuzong Chen, Jordan Dotzel, Mohamed S. Abdelfattah. (2023)  
**M4BRAM: Mixed-Precision Matrix-Matrix Multiplication in FPGA Block RAMs**  

---
Primary Category: cs.AR  
Categories: cs-AR, cs.AR  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2311.02758v1)  

---


**ABSTRACT**  
Mixed-precision quantization is a popular approach for compressing deep neural networks (DNNs). However, it is challenging to scale the performance efficiently with mixed-precision DNNs given the current FPGA architecture and conventional accelerator dataflows. In this work, we enhance the FPGA's capability for accelerating mixed-precision DNNs by proposing M4BRAM, a novel compute-in-block RAM (BRAM) architecture that can compute mixed-precision matrix-matrix multiplication. On the precision side, M4BRAM supports a wide range of mixed-precision DNN configurations -- the weight precision can be 2/4/8 bits while the activation precision can vary from 2 to 8 bits. On the dataflow side, M4BRAM leverages a novel in-BRAM data duplication scheme to achieve high hardware utilization. Moreover, during M4BRAM computation, other FPGA resources can seamlessly access its data without the need for a separate buffer. Hence, unlike prior compute-in-BRAM proposals, M4BRAM can simultaneously perform mixed-precision computation and maintain full functionality as a memory unit to \textit{truly} complement the existing compute resources on FPGAs. Experiments show that adding M4BRAM to a tiled DNN accelerator can achieve an average speedup of 2.16$\times$ across various DNNs on the ImageNet classification task while incurring a negligible accuracy loss of $<$ 0.5%. Compared to the same tiled accelerator that employs a prior compute-in-BRAM architecture, M4BRAM delivers 1.43$\times$ higher performance on average across various DNNs.

{{</citation>}}


## cs.IR (3)



### (44/55) CIRCLE: Multi-Turn Query Clarifications with Reinforcement Learning (Pierre Erbacher et al., 2023)

{{<citation>}}

Pierre Erbacher, Laure Soulier. (2023)  
**CIRCLE: Multi-Turn Query Clarifications with Reinforcement Learning**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02737v1)  

---


**ABSTRACT**  
Users often have trouble formulating their information needs into words on the first try when searching online. This can lead to frustration, as they may have to reformulate their queries when retrieved information is not relevant. This can be due to a lack of familiarity with the specific terminology related to their search topic, or because queries are ambiguous and related to multiple topics. Most modern search engines have interactive features that suggest clarifications or similar queries based on what others have searched for. However, the proposed models are either based on a single interaction or evaluated on search logs, hindering the naturalness of the interactions. In this paper, we introduce CIRCLE, a generative model for multi-turn query Clarifications wIth ReinforCement LEarning that leverages multi-turn interactions through a user simulation framework. Our model aims at generating a diverse set of query clarifications using a pretrained language model fine-tuned using reinforcement learning. We evaluate it against well established google suggestions using a user simulation framework.

{{</citation>}}


### (45/55) Enhancing AI Research Paper Analysis: Methodology Component Extraction using Factored Transformer-based Sequence Modeling Approach (Madhusudan Ghosh et al., 2023)

{{<citation>}}

Madhusudan Ghosh, Debasis Ganguly, Partha Basuchowdhuri, Sudip Kumar Naskar. (2023)  
**Enhancing AI Research Paper Analysis: Methodology Component Extraction using Factored Transformer-based Sequence Modeling Approach**  

---
Primary Category: cs.IR  
Categories: cs-DL, cs-IR, cs-LG, cs.IR  
Keywords: AI, NLP, Transformer  
[Paper Link](http://arxiv.org/abs/2311.03401v1)  

---


**ABSTRACT**  
Research in scientific disciplines evolves, often rapidly, over time with the emergence of novel methodologies and their associated terminologies. While methodologies themselves being conceptual in nature and rather difficult to automatically extract and characterise, in this paper, we seek to develop supervised models for automatic extraction of the names of the various constituents of a methodology, e.g., `R-CNN', `ELMo' etc. The main research challenge for this task is effectively modeling the contexts around these methodology component names in a few-shot or even a zero-shot setting. The main contributions of this paper towards effectively identifying new evolving scientific methodology names are as follows: i) we propose a factored approach to sequence modeling, which leverages a broad-level category information of methodology domains, e.g., `NLP', `RL' etc.; ii) to demonstrate the feasibility of our proposed approach of identifying methodology component names under a practical setting of fast evolving AI literature, we conduct experiments following a simulated chronological setup (newer methodologies not seen during the training process); iii) our experiments demonstrate that the factored approach outperforms state-of-the-art baselines by margins of up to 9.257\% for the methodology extraction task with the few-shot setup.

{{</citation>}}


### (46/55) Temporal Treasure Hunt: Content-based Time Series Retrieval System for Discovering Insights (Chin-Chia Michael Yeh et al., 2023)

{{<citation>}}

Chin-Chia Michael Yeh, Huiyuan Chen, Xin Dai, Yan Zheng, Yujie Fan, Vivian Lai, Junpeng Wang, Audrey Der, Zhongfang Zhuang, Liang Wang, Wei Zhang. (2023)  
**Temporal Treasure Hunt: Content-based Time Series Retrieval System for Discovering Insights**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs-LG, cs.IR  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2311.02560v1)  

---


**ABSTRACT**  
Time series data is ubiquitous across various domains such as finance, healthcare, and manufacturing, but their properties can vary significantly depending on the domain they originate from. The ability to perform Content-based Time Series Retrieval (CTSR) is crucial for identifying unknown time series examples. However, existing CTSR works typically focus on retrieving time series from a single domain database, which can be inadequate if the user does not know the source of the query time series. This limitation motivates us to investigate the CTSR problem in a scenario where the database contains time series from multiple domains. To facilitate this investigation, we introduce a CTSR benchmark dataset that comprises time series data from a variety of domains, such as motion, power demand, and traffic. This dataset is sourced from a publicly available time series classification dataset archive, making it easily accessible to researchers in the field. We compare several popular methods for modeling and retrieving time series data using this benchmark dataset. Additionally, we propose a novel distance learning model that outperforms the existing methods. Overall, our study highlights the importance of addressing the CTSR problem across multiple domains and provides a useful benchmark dataset for future research.

{{</citation>}}


## cs.DS (1)



### (47/55) Highly Connected Steiner Subgraph -- Parameterized Algorithms and Applications to Hitting Set Problems (Eduard Eiben et al., 2023)

{{<citation>}}

Eduard Eiben, Diptapriyo Majumdar, M. S. Ramanujan. (2023)  
**Highly Connected Steiner Subgraph -- Parameterized Algorithms and Applications to Hitting Set Problems**  

---
Primary Category: cs.DS  
Categories: F-2-2; G-2-2, cs-DM, cs-DS, cs.DS  
Keywords: NER  
[Paper Link](http://arxiv.org/abs/2311.02708v1)  

---


**ABSTRACT**  
Given a simple connected undirected graph G = (V, E), a set X \subseteq V(G), and integers k and p, STEINER SUBGRAPH EXTENSION problem asks if there exists a set S \supseteq X with at most k vertices such that G[S] is p-edge-connected. This is a natural generalization of a well-studied problem STEINER TREE (set p=1 and X as the set of all terminals). In this paper, we initiate the study of STEINER SUBGRAPH EXTENSION from the perspective of parameterized complexity and give a fixed-parameter algorithm parameterized by k and p on graphs of bounded degeneracy. In case we remove the assumption of the input graph being bounded degenerate, then the STEINER SUBGRAPH EXTENSION problem becomes W[1]-hard. Besides being an independent advance on the parameterized complexity of network design problems, our result has natural applications. In particular, we use our result to obtain singly exponential-time FPT algorithms for several vertex deletion problem studied in the literature, where the goal is to delete a smallest set of vertices such that (i) the resulting graph belongs to a specific hereditary graph class, and (ii) the deleted set of vertices induces a p-edge-connected subgraph of the input graph.

{{</citation>}}


## eess.SY (1)



### (48/55) Regret Analysis of Learning-Based Linear Quadratic Gaussian Control with Additive Exploration (Archith Athrey et al., 2023)

{{<citation>}}

Archith Athrey, Othmane Mazhar, Meichen Guo, Bart De Schutter, Shengling Shi. (2023)  
**Regret Analysis of Learning-Based Linear Quadratic Gaussian Control with Additive Exploration**  

---
Primary Category: eess.SY  
Categories: cs-LG, cs-SY, eess-SY, eess.SY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.02679v1)  

---


**ABSTRACT**  
In this paper, we analyze the regret incurred by a computationally efficient exploration strategy, known as naive exploration, for controlling unknown partially observable systems within the Linear Quadratic Gaussian (LQG) framework. We introduce a two-phase control algorithm called LQG-NAIVE, which involves an initial phase of injecting Gaussian input signals to obtain a system model, followed by a second phase of an interplay between naive exploration and control in an episodic fashion. We show that LQG-NAIVE achieves a regret growth rate of $\tilde{\mathcal{O}}(\sqrt{T})$, i.e., $\mathcal{O}(\sqrt{T})$ up to logarithmic factors after $T$ time steps, and we validate its performance through numerical simulations. Additionally, we propose LQG-IF2E, which extends the exploration signal to a `closed-loop' setting by incorporating the Fisher Information Matrix (FIM). We provide compelling numerical evidence of the competitive performance of LQG-IF2E compared to LQG-NAIVE.

{{</citation>}}


## cs.DC (1)



### (49/55) GSC: Generalizable Service Coordination (Farzad Mohammadi et al., 2023)

{{<citation>}}

Farzad Mohammadi, Vahid Shah-Mansouri. (2023)  
**GSC: Generalizable Service Coordination**  

---
Primary Category: cs.DC  
Categories: cs-DC, cs.DC  
Keywords: GNN, Graph Neural Network, Graph Neural Networks, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2311.02657v1)  

---


**ABSTRACT**  
Services with distributed and interdependent components are becoming a popular option for harnessing dispersed resources available on cloud and edge networks. However, effective deployment and management of these services, namely service coordination, is a challenging task. Service coordination comprises the placement and scalability of components and scheduling incoming traffic requesting for services between deployed instances. Due to the online nature of the problem and the success of Deep Reinforcement Learning (DRL) methods, previous works considered DRL agents for solving service coordination problems, yet these solutions have to be retrained for every unseen scenario. Other works have tried to tackle this shortcoming by incorporating Graph Neural Networks (GNN) into their solutions, but they often focus on specific aspects (and disregard others) or cannot operate in dynamic and practical situations where there is no labeled dataset and feedback from the network might be delayed. In response to these challenges, we present GSC, a generalizable service coordinator that jointly considers service placement, scaling, and traffic scheduling. GSC can operate in unseen situations without significant performance degradation and outperforms existing state-of-the-art solutions by 40%, as determined by simulating real-world network situations.

{{</citation>}}


## cs.CY (1)



### (50/55) Compute at Scale -- A Broad Investigation into the Data Center Industry (Konstantin Pilz et al., 2023)

{{<citation>}}

Konstantin Pilz, Lennart Heim. (2023)  
**Compute at Scale -- A Broad Investigation into the Data Center Industry**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2311.02651v1)  

---


**ABSTRACT**  
This report characterizes the data center industry and its importance for AI development. Data centers are industrial facilities that efficiently provide compute at scale and thus constitute the engine rooms of today's digital economy. As large-scale AI training and inference become increasingly computationally expensive, they are dominantly executed from this designated infrastructure. Key features of data centers include large-scale compute clusters that require extensive cooling and consume large amounts of power, the need for fast connectivity both within the data center and to the internet, and an emphasis on security and reliability. The global industry is valued at approximately $250B and is expected to double over the next seven years. There are likely about 500 large (above 10 MW) data centers globally, with the US, Europe, and China constituting the most important markets. The report further covers important actors, business models, main inputs, and typical locations of data centers.

{{</citation>}}


## cs.NI (1)



### (51/55) Drone-Enabled Load Management for Solar Small Cell Networks in Next-Gen Communications Optimization for Solar Small Cells (Daksh Dave et al., 2023)

{{<citation>}}

Daksh Dave, Dhruv Khut, Sahil Nawale, Pushkar Aggrawal, Disha Rastogi, Kailas Devadkar. (2023)  
**Drone-Enabled Load Management for Solar Small Cell Networks in Next-Gen Communications Optimization for Solar Small Cells**  

---
Primary Category: cs.NI  
Categories: cs-LG, cs-NI, cs.NI  
Keywords: Drone  
[Paper Link](http://arxiv.org/abs/2311.02648v1)  

---


**ABSTRACT**  
In recent years, the cellular industry has witnessed a major evolution in communication technologies. It is evident that the Next Generation of cellular networks(NGN) will play a pivotal role in the acceptance of emerging IoT applications supporting high data rates, better Quality of Service(QoS), and reduced latency. However, the deployment of NGN will introduce a power overhead on the communication infrastructure. Addressing the critical energy constraints in 5G and beyond, this study introduces an innovative load transfer method using drone-carried airborne base stations (BSs) for stable and secure power reallocation within a green micro-grid network. This method effectively manages energy deficit by transferring aerial BSs from high to low-energy cells, depending on user density and the availability of aerial BSs, optimizing power distribution in advanced cellular networks. The complexity of the proposed system is significantly lower as compared to existing power cable transmission systems currently employed in powering the BSs. Furthermore, our proposed algorithm has been shown to reduce BS power outages while requiring a minimum number of drone exchanges. We have conducted a thorough review on real-world dataset to prove the efficacy of our proposed approach to support BS during high load demand times

{{</citation>}}


## cs.SE (1)



### (52/55) Assessing the Promise and Pitfalls of ChatGPT for Automated Code Generation (Muhammad Fawad Akbar Khan et al., 2023)

{{<citation>}}

Muhammad Fawad Akbar Khan, Max Ramsdell, Erik Falor, Hamid Karimi. (2023)  
**Assessing the Promise and Pitfalls of ChatGPT for Automated Code Generation**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-SE, cs.SE  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2311.02640v1)  

---


**ABSTRACT**  
This paper presents a comprehensive evaluation of the code generation capabilities of ChatGPT, a prominent large language model, compared to human programmers. A novel dataset of 131 code-generation prompts across 5 categories was curated to enable robust analysis. Code solutions were generated by both ChatGPT and humans for all prompts, resulting in 262 code samples. A meticulous manual assessment methodology prioritized evaluating correctness, comprehensibility, and security using 14 established code quality metrics. The key findings reveal ChatGPT's strengths in crafting concise, efficient code with advanced constructs, showcasing strengths in data analysis tasks (93.1% accuracy) but limitations in visual-graphical challenges. Comparative analysis with human code highlights ChatGPT's inclination towards modular design and superior error handling. Additionally, machine learning models effectively distinguished ChatGPT from human code with up to 88% accuracy, suggesting detectable coding style disparities. By providing profound insights into ChatGPT's code generation capabilities and limitations through quantitative metrics and qualitative analysis, this study makes valuable contributions toward advancing AI-based programming assistants. The curated dataset and methodology offer a robust foundation for future research in this nascent domain. All data and codes are available on https://github.com/DSAatUSU/ChatGPT-promises-and-pitfalls.

{{</citation>}}


## cs.DB (2)



### (53/55) Time Series Synthesis Using the Matrix Profile for Anonymization (Audrey Der et al., 2023)

{{<citation>}}

Audrey Der, Chin-Chia Michael Yeh, Yan Zheng, Junpeng Wang, Huiyuan Chen, Zhongfang Zhuang, Liang Wang, Wei Zhang, Eamonn Keogh. (2023)  
**Time Series Synthesis Using the Matrix Profile for Anonymization**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-CR, cs-DB, cs-LG, cs.DB  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2311.02563v1)  

---


**ABSTRACT**  
Publishing and sharing data is crucial for the data mining community, allowing collaboration and driving open innovation. However, many researchers cannot release their data due to privacy regulations or fear of leaking confidential business information. To alleviate such issues, we propose the Time Series Synthesis Using the Matrix Profile (TSSUMP) method, where synthesized time series can be released in lieu of the original data. The TSSUMP method synthesizes time series by preserving similarity join information (i.e., Matrix Profile) while reducing the correlation between the synthesized and the original time series. As a result, neither the values for the individual time steps nor the local patterns (or shapes) from the original data can be recovered, yet the resulting data can be used for downstream tasks that data analysts are interested in. We concentrate on similarity joins because they are one of the most widely applied time series data mining routines across different data mining tasks. We test our method on a case study of ECG and gender masking prediction. In this case study, the gender information is not only removed from the synthesized time series, but the synthesized time series also preserves enough information from the original time series. As a result, unmodified data mining tools can obtain near-identical performance on the synthesized time series as on the original time series.

{{</citation>}}


### (54/55) Sketching Multidimensional Time Series for Fast Discord Mining (Chin-Chia Michael Yeh et al., 2023)

{{<citation>}}

Chin-Chia Michael Yeh, Yan Zheng, Menghai Pan, Huiyuan Chen, Zhongfang Zhuang, Junpeng Wang, Liang Wang, Wei Zhang, Jeff M. Phillips, Eamonn Keogh. (2023)  
**Sketching Multidimensional Time Series for Fast Discord Mining**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-DB, cs.DB  
Keywords: Sketch, Time Series  
[Paper Link](http://arxiv.org/abs/2311.03393v1)  

---


**ABSTRACT**  
Time series discords are a useful primitive for time series anomaly detection, and the matrix profile is capable of capturing discord effectively. There exist many research efforts to improve the scalability of discord discovery with respect to the length of time series. However, there is surprisingly little work focused on reducing the time complexity of matrix profile computation associated with dimensionality of a multidimensional time series. In this work, we propose a sketch for discord mining among multi-dimensional time series. After an initial pre-processing of the sketch as fast as reading the data, the discord mining has runtime independent of the dimensionality of the original data. On several real world examples from water treatment and transportation, the proposed algorithm improves the throughput by at least an order of magnitude (50X) and only has minimal impact on the quality of the approximated solution. Additionally, the proposed method can handle the dynamic addition or deletion of dimensions inconsequential overhead. This allows a data analyst to consider "what-if" scenarios in real time while exploring the data.

{{</citation>}}


## cs.HC (1)



### (55/55) Evaluation of accessibility of open-source EHRs for visually impaired users (Megha M. Moncy et al., 2023)

{{<citation>}}

Megha M. Moncy, Manya Pilli, Manasi Somasundaram, Saptarshi Purkayastha, Cathy R. Fulton. (2023)  
**Evaluation of accessibility of open-source EHRs for visually impaired users**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AWS  
[Paper Link](http://arxiv.org/abs/2311.02531v1)  

---


**ABSTRACT**  
This study investigates the accessibility of open-source electronic health record (EHR) systems for individuals who are visually impaired or blind. Ensuring the accessibility of EHRs to visually impaired users is critical for the diversity, equity, and inclusion of all users. The study used a combination of automated and manual accessibility testing techniques like screen readers to evaluate the accessibility of three widely used open-source EHR systems. Our assessment focused on the performance of three popular screen readers, including JAWS (Windows), NVDA (Windows), and Apple VoiceOver (OSX). The evaluation revealed that although each of the three systems was partially accessible, there is room for improvement, particularly regarding keyboard navigation and screen reader compatibility. The study concludes with recommendations for making EHR systems more inclusive for all users and more accessible.

{{</citation>}}
