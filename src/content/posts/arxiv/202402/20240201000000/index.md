---
draft: false
title: "arXiv @ 2024.02.01"
date: 2024-02-01
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2024"]
menu:
  sidebar:
    name: "arXiv @ 2024.02.01"
    identifier: arxiv_20240201
    parent: 202402_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (36)](#cslg-36)
- [cs.DB (2)](#csdb-2)
- [cs.CL (41)](#cscl-41)
- [cs.CV (17)](#cscv-17)
- [math.OC (3)](#mathoc-3)
- [cs.HC (7)](#cshc-7)
- [cs.CR (10)](#cscr-10)
- [cs.CY (6)](#cscy-6)
- [cs.IT (6)](#csit-6)
- [cs.MA (1)](#csma-1)
- [cs.NE (1)](#csne-1)
- [cs.RO (6)](#csro-6)
- [cs.AR (4)](#csar-4)
- [stat.ML (3)](#statml-3)
- [cs.SD (3)](#cssd-3)
- [cs.IR (4)](#csir-4)
- [cs.SE (4)](#csse-4)
- [cs.MS (1)](#csms-1)
- [eess.IV (2)](#eessiv-2)
- [astro-ph.IM (1)](#astro-phim-1)
- [eess.AS (1)](#eessas-1)
- [cs.PL (1)](#cspl-1)
- [cs.AI (1)](#csai-1)
- [cs.NI (1)](#csni-1)

## cs.LG (36)



### (1/162) Arrows of Time for Large Language Models (Vassilis Papadopoulos et al., 2024)

{{<citation>}}

Vassilis Papadopoulos, Jérémie Wenger, Clément Hongler. (2024)  
**Arrows of Time for Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17505v1)  

---


**ABSTRACT**  
We study the probabilistic modeling performed by Autoregressive Large Language Models through the angle of time directionality. We empirically find a time asymmetry exhibited by such models in their ability to model natural language: a difference in the average log-perplexity when trying to predict the next token versus when trying to predict the previous one. This difference is at the same time subtle and very consistent across various modalities (language, model size, training time, ...). Theoretically, this is surprising: from an information-theoretic point of view, there should be no such difference. We provide a theoretical framework to explain how such an asymmetry can appear from sparsity and computational complexity considerations, and outline a number of perspectives opened by our results.

{{</citation>}}


### (2/162) Liquid Democracy for Low-Cost Ensemble Pruning (Ben Armstrong et al., 2024)

{{<citation>}}

Ben Armstrong, Kate Larson. (2024)  
**Liquid Democracy for Low-Cost Ensemble Pruning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-MA, cs.LG  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2401.17443v1)  

---


**ABSTRACT**  
We argue that there is a strong connection between ensemble learning and a delegative voting paradigm -- liquid democracy -- that can be leveraged to reduce ensemble training costs. We present an incremental training procedure that identifies and removes redundant classifiers from an ensemble via delegation mechanisms inspired by liquid democracy. Through both analysis and extensive experiments we show that this process greatly reduces the computational cost of training compared to training a full ensemble. By carefully selecting the underlying delegation mechanism, weight centralization in the classifier population is avoided, leading to higher accuracy than some boosting methods. Furthermore, this work serves as an exemplar of how frameworks from computational social choice literature can be applied to problems in nontraditional domains.

{{</citation>}}


### (3/162) Explaining Predictive Uncertainty by Exposing Second-Order Effects (Florian Bley et al., 2024)

{{<citation>}}

Florian Bley, Sebastian Lapuschkin, Wojciech Samek, Grégoire Montavon. (2024)  
**Explaining Predictive Uncertainty by Exposing Second-Order Effects**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17441v1)  

---


**ABSTRACT**  
Explainable AI has brought transparency into complex ML blackboxes, enabling, in particular, to identify which features these models use for their predictions. So far, the question of explaining predictive uncertainty, i.e. why a model 'doubts', has been scarcely studied. Our investigation reveals that predictive uncertainty is dominated by second-order effects, involving single features or product interactions between them. We contribute a new method for explaining predictive uncertainty based on these second-order effects. Computationally, our method reduces to a simple covariance computation over a collection of first-order explanations. Our method is generally applicable, allowing for turning common attribution techniques (LRP, Gradient x Input, etc.) into powerful second-order uncertainty explainers, which we call CovLRP, CovGI, etc. The accuracy of the explanations our method produces is demonstrated through systematic quantitative evaluations, and the overall usefulness of our method is demonstrated via two practical showcases.

{{</citation>}}


### (4/162) Can Large Language Models Replace Economic Choice Prediction Labs? (Eilam Shapira et al., 2024)

{{<citation>}}

Eilam Shapira, Omer Madmon, Roi Reichart, Moshe Tennenholtz. (2024)  
**Can Large Language Models Replace Economic Choice Prediction Labs?**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-GT, cs-HC, cs-LG, cs.LG  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2401.17435v2)  

---


**ABSTRACT**  
Economic choice prediction is an essential challenging task, often constrained by the difficulties in acquiring human choice data. Indeed, experimental economics studies had focused mostly on simple choice settings. The AI community has recently contributed to that effort in two ways: considering whether LLMs can substitute for humans in the above-mentioned simple choice prediction settings, and the study through ML lens of more elaborated but still rigorous experimental economics settings, employing incomplete information, repetitive play, and natural language communication, notably language-based persuasion games. This leaves us with a major inspiration: can LLMs be used to fully simulate the economic environment and generate data for efficient human choice prediction, substituting for the elaborated economic lab studies? We pioneer the study of this subject, demonstrating its feasibility. In particular, we show that a model trained solely on LLM-generated data can effectively predict human behavior in a language-based persuasion game, and can even outperform models trained on actual human data.

{{</citation>}}


### (5/162) Explainable AI for survival analysis: a median-SHAP approach (Lucile Ter-Minassian et al., 2024)

{{<citation>}}

Lucile Ter-Minassian, Sahra Ghalebikesabi, Karla Diaz-Ordaz, Chris Holmes. (2024)  
**Explainable AI for survival analysis: a median-SHAP approach**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, stat-ME, stat-ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.00072v1)  

---


**ABSTRACT**  
With the adoption of machine learning into routine clinical practice comes the need for Explainable AI methods tailored to medical applications. Shapley values have sparked wide interest for locally explaining models. Here, we demonstrate their interpretation strongly depends on both the summary statistic and the estimator for it, which in turn define what we identify as an 'anchor point'. We show that the convention of using a mean anchor point may generate misleading interpretations for survival analysis and introduce median-SHAP, a method for explaining black-box models predicting individual survival times.

{{</citation>}}


### (6/162) Superiority of Multi-Head Attention in In-Context Linear Regression (Yingqian Cui et al., 2024)

{{<citation>}}

Yingqian Cui, Jie Ren, Pengfei He, Jiliang Tang, Yue Xing. (2024)  
**Superiority of Multi-Head Attention in In-Context Linear Regression**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, stat-ML  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2401.17426v1)  

---


**ABSTRACT**  
We present a theoretical analysis of the performance of transformer with softmax attention in in-context learning with linear regression tasks. While the existing literature predominantly focuses on the convergence of transformers with single-/multi-head attention, our research centers on comparing their performance. We conduct an exact theoretical analysis to demonstrate that multi-head attention with a substantial embedding dimension performs better than single-head attention. When the number of in-context examples D increases, the prediction loss using single-/multi-head attention is in O(1/D), and the one for multi-head attention has a smaller multiplicative constant. In addition to the simplest data distribution setting, we consider more scenarios, e.g., noisy labels, local examples, correlated features, and prior knowledge. We observe that, in general, multi-head attention is preferred over single-head attention. Our results verify the effectiveness of the design of multi-head attention in the transformer architecture.

{{</citation>}}


### (7/162) ReacLLaMA: Merging chemical and textual information in chemical reactivity AI models (Aline Hartgers et al., 2024)

{{<citation>}}

Aline Hartgers, Ramil Nugmanov, Kostiantyn Chernichenko, Joerg Kurt Wegner. (2024)  
**ReacLLaMA: Merging chemical and textual information in chemical reactivity AI models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, q-bio-QM  
Keywords: AI, GPT, LLaMA, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2401.17267v1)  

---


**ABSTRACT**  
Chemical reactivity models are developed to predict chemical reaction outcomes in the form of classification (success/failure) or regression (product yield) tasks. The vast majority of the reported models are trained solely on chemical information such as reactants, products, reagents, and solvents, but not on the details of a synthetic protocol. Herein incorporation of procedural text with the aim to augment the Graphormer reactivity model and improve its accuracy is presented. Two major approaches are used: training an adapter Graphormer model that is provided with a GPT-2-derived latent representation of the text procedure (ReacLLaMA-Adapter) and labeling an unlabeled part of a dataset with the LLaMA 2 model followed by training the Graphormer on an extended dataset (Zero-Shot Labeling ReacLLaMA). Both methodologies enhance the discernment of unpromising reactions, thereby providing more accurate models with improved specificity.

{{</citation>}}


### (8/162) Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks (Andy Zhou et al., 2024)

{{<citation>}}

Andy Zhou, Bo Li, Haohan Wang. (2024)  
**Robust Prompt Optimization for Defending Language Models Against Jailbreaking Attacks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.LG  
Keywords: AI, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2401.17263v2)  

---


**ABSTRACT**  
Despite advances in AI alignment, language models (LM) remain vulnerable to adversarial attacks or jailbreaking, in which adversaries modify input prompts to induce harmful behavior. While some defenses have been proposed, they focus on narrow threat models and fall short of a strong defense, which we posit should be effective, universal, and practical. To achieve this, we propose the first adversarial objective for defending LMs against jailbreaking attacks and an algorithm, robust prompt optimization (RPO), that uses gradient-based token optimization to enforce harmless outputs. This results in an easily accessible suffix that significantly improves robustness to both jailbreaks seen during optimization and unknown, held-out jailbreaks, reducing the attack success rate on Starling-7B from 84% to 8.66% across 20 jailbreaks. In addition, we find that RPO has a minor effect on benign use, is successful under adaptive attacks, and can transfer to black-box models, reducing the success rate of the strongest attack on GPT-4, GUARD, from 92% to 6%.

{{</citation>}}


### (9/162) Timeseries Suppliers Allocation Risk Optimization via Deep Black Litterman Model (Jiayuan Luo et al., 2024)

{{<citation>}}

Jiayuan Luo, Wentao Zhang, Yuchen Fang, Xiaowei Gao, Dingyi Zhuang, Hao Chen, Xinke Jiang. (2024)  
**Timeseries Suppliers Allocation Risk Optimization via Deep Black Litterman Model**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Graph Neural Network  
[Paper Link](http://arxiv.org/abs/2401.17350v1)  

---


**ABSTRACT**  
We introduce the BL model and the Perspective Matrix to optimize supplier selection and order allocation, focusing on both temporal and spatial dynamics. Our development of a Supplier Relationship Network, using a Spatio-Temporal Graph Neural Network, enhances the understanding of complex supplier interdependencies. Additionally, we address credibility issues in zero-order scenarios with a Masked Ranking Mechanism, improving supplier ranking efficiency. Our model demonstrates superior results on two datasets compared to the traditional models. Our evaluations using real-world datasets highlight DBLM's superiority in providing accurate predictions and precise confidence intervals, particularly in high-resolution scenarios.

{{</citation>}}


### (10/162) NormEnsembleXAI: Unveiling the Strengths and Weaknesses of XAI Ensemble Techniques (Weronika Hryniewska-Guzik et al., 2024)

{{<citation>}}

Weronika Hryniewska-Guzik, Bartosz Sawicki, Przemysław Biecek. (2024)  
**NormEnsembleXAI: Unveiling the Strengths and Weaknesses of XAI Ensemble Techniques**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17200v1)  

---


**ABSTRACT**  
This paper presents a comprehensive comparative analysis of explainable artificial intelligence (XAI) ensembling methods. Our research brings three significant contributions. Firstly, we introduce a novel ensembling method, NormEnsembleXAI, that leverages minimum, maximum, and average functions in conjunction with normalization techniques to enhance interpretability. Secondly, we offer insights into the strengths and weaknesses of XAI ensemble methods. Lastly, we provide a library, facilitating the practical implementation of XAI ensembling, thus promoting the adoption of transparent and interpretable deep learning models.

{{</citation>}}


### (11/162) GraphViz2Vec: A Structure-aware Feature Generation Model to Improve Classification in GNNs (Shraban Kumar Chatterjee et al., 2024)

{{<citation>}}

Shraban Kumar Chatterjee, Suman Kundu. (2024)  
**GraphViz2Vec: A Structure-aware Feature Generation Model to Improve Classification in GNNs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2401.17178v1)  

---


**ABSTRACT**  
GNNs are widely used to solve various tasks including node classification and link prediction. Most of the GNN architectures assume the initial embedding to be random or generated from popular distributions. These initial embeddings require multiple layers of transformation to converge into a meaningful latent representation. While number of layers allow accumulation of larger neighbourhood of a node it also introduce the problem of over-smoothing. In addition, GNNs are inept at representing structural information. For example, the output embedding of a node does not capture its triangles participation. In this paper, we presented a novel feature extraction methodology GraphViz2Vec that can capture the structural information of a node's local neighbourhood to create meaningful initial embeddings for a GNN model. These initial embeddings helps existing models achieve state-of-the-art results in various classification tasks. Further, these initial embeddings help the model to produce desired results with only two layers which in turn reduce the problem of over-smoothing. The initial encoding of a node is obtained from an image classification model trained on multiple energy diagrams of its local neighbourhood. These energy diagrams are generated with the induced sub-graph of the nodes traversed by multiple random walks. The generated encodings increase the performance of existing models on classification tasks (with a mean increase of $4.65\%$ and $2.58\%$ for the node and link classification tasks, respectively), with some models achieving state-of-the-art results.

{{</citation>}}


### (12/162) Zero-Shot Reinforcement Learning via Function Encoders (Tyler Ingebrand et al., 2024)

{{<citation>}}

Tyler Ingebrand, Amy Zhang, Ufuk Topcu. (2024)  
**Zero-Shot Reinforcement Learning via Function Encoders**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2401.17173v1)  

---


**ABSTRACT**  
Although reinforcement learning (RL) can solve many challenging sequential decision making problems, achieving zero-shot transfer across related tasks remains a challenge. The difficulty lies in finding a good representation for the current task so that the agent understands how it relates to previously seen tasks. To achieve zero-shot transfer, we introduce the function encoder, a representation learning algorithm which represents a function as a weighted combination of learned, non-linear basis functions. By using a function encoder to represent the reward function or the transition function, the agent has information on how the current task relates to previously seen tasks via a coherent vector representation. Thus, the agent is able to achieve transfer between related tasks at run time with no additional training. We demonstrate state-of-the-art data efficiency, asymptotic performance, and training stability in three RL fields by augmenting basic RL algorithms with a function encoder task representation.

{{</citation>}}


### (13/162) Large Language Model Evaluation via Matrix Entropy (Lai Wei et al., 2024)

{{<citation>}}

Lai Wei, Zhiquan Tan, Chenghai Li, Jindong Wang, Weiran Huang. (2024)  
**Large Language Model Evaluation via Matrix Entropy**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-IT, cs-LG, cs.LG, math-IT  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17139v1)  

---


**ABSTRACT**  
Large language models (LLMs) have revolutionized the field of natural language processing, extending their strong capabilities into multi-modal domains. Thus, it is vital to define proper and diversified metrics for the evaluation of LLMs.   In this paper, we introduce matrix entropy, a novel metric rooted in information theory and geometry principles to quantify the data compression proficiency in LLMs. It reflects the model's ability to extract relevant information and eliminate unnecessary elements, thereby providing insight into the language model's intrinsic capability. Specifically, we demonstrate its applicability in both single-modal (language) and multi-modal settings. For language models, our findings reveal that the matrix entropy of representations follows a scaling law type reduction when the model scales up, serving as a complement to the traditional loss scaling law. For the multi-modal setting, we also propose an evaluation method based on matrix entropy for assessing alignment quality and we find that modern large multi-modal models exhibit great alignment performance.

{{</citation>}}


### (14/162) GPT4Battery: An LLM-driven Framework for Adaptive State of Health Estimation of Raw Li-ion Batteries (Yuyuan Feng et al., 2024)

{{<citation>}}

Yuyuan Feng, Guosheng Hu, Zhihong Zhang. (2024)  
**GPT4Battery: An LLM-driven Framework for Adaptive State of Health Estimation of Raw Li-ion Batteries**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2402.00068v1)  

---


**ABSTRACT**  
State of health (SOH) is a crucial indicator for assessing the degradation level of batteries that cannot be measured directly but requires estimation. Accurate SOH estimation enhances detection, control, and feedback for Li-ion batteries, allowing for safe and efficient energy management and guiding the development of new-generation batteries. Despite the significant progress in data-driven SOH estimation, the time and resource-consuming degradation experiments for generating lifelong training data pose a challenge in establishing one large model capable of handling diverse types of Li-ion batteries, e.g., cross-chemistry, cross-manufacturer, and cross-capacity. Hence, this paper utilizes the strong generalization capability of large language model (LLM) to proposes a novel framework for adaptable SOH estimation across diverse batteries. To match the real scenario where unlabeled data sequentially arrives in use with distribution shifts, the proposed model is modified by a test-time training technique to ensure estimation accuracy even at the battery's end of life. The validation results demonstrate that the proposed framework achieves state-of-the-art accuracy on four widely recognized datasets collected from 62 batteries. Furthermore, we analyze the theoretical challenges of cross-battery estimation and provide a quantitative explanation of the effectiveness of our method.

{{</citation>}}


### (15/162) Making Parametric Anomaly Detection on Tabular Data Non-Parametric Again (Hugo Thimonier et al., 2024)

{{<citation>}}

Hugo Thimonier, Fabrice Popineau, Arpad Rimmel, Bich-Liên Doan. (2024)  
**Making Parametric Anomaly Detection on Tabular Data Non-Parametric Again**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2401.17052v1)  

---


**ABSTRACT**  
Deep learning for tabular data has garnered increasing attention in recent years, yet employing deep models for structured data remains challenging. While these models excel with unstructured data, their efficacy with structured data has been limited. Recent research has introduced retrieval-augmented models to address this gap, demonstrating promising results in supervised tasks such as classification and regression. In this work, we investigate using retrieval-augmented models for anomaly detection on tabular data. We propose a reconstruction-based approach in which a transformer model learns to reconstruct masked features of \textit{normal} samples. We test the effectiveness of KNN-based and attention-based modules to select relevant samples to help in the reconstruction process of the target sample. Our experiments on a benchmark of 31 tabular datasets reveal that augmenting this reconstruction-based anomaly detection (AD) method with non-parametric relationships via retrieval modules may significantly boost performance.

{{</citation>}}


### (16/162) Forecasting VIX using Bayesian Deep Learning (Héctor J. Hortúa et al., 2024)

{{<citation>}}

Héctor J. Hortúa, Andrés Mora-Valencia. (2024)  
**Forecasting VIX using Bayesian Deep Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.17042v1)  

---


**ABSTRACT**  
Recently, deep learning techniques are gradually replacing traditional statistical and machine learning models as the first choice for price forecasting tasks. In this paper, we leverage probabilistic deep learning for inferring the volatility index VIX. We employ the probabilistic counterpart of WaveNet, Temporal Convolutional Network (TCN), and Transformers. We show that TCN outperforms all models with an RMSE around 0.189. In addition, it has been well known that modern neural networks provide inaccurate uncertainty estimates. For solving this problem, we use the standard deviation scaling to calibrate the networks. Furthermore, we found out that MNF with Gaussian prior outperforms Reparameterization Trick and Flipout models in terms of precision and uncertainty predictions. Finally, we claim that MNF with Cauchy and LogUniform prior distributions yield well calibrated TCN and WaveNet networks being the former that best infer the VIX values.

{{</citation>}}


### (17/162) A Latent Space Metric for Enhancing Prediction Confidence in Earth Observation Data (Ioannis Pitsiorlas et al., 2024)

{{<citation>}}

Ioannis Pitsiorlas, Argyro Tsantalidou, George Arvanitakis, Marios Kountouris, Charalambos Kontoes. (2024)  
**A Latent Space Metric for Enhancing Prediction Confidence in Earth Observation Data**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17342v1)  

---


**ABSTRACT**  
This study presents a new approach for estimating confidence in machine learning model predictions, specifically in regression tasks utilizing Earth Observation (EO) data, with a particular focus on mosquito abundance (MA) estimation. We take advantage of a Variational AutoEncoder architecture, to derive a confidence metric by the latent space representations of EO datasets. This methodology is pivotal in establishing a correlation between the Euclidean distance in latent representations and the Absolute Error (AE) in individual MA predictions. Our research focuses on EO datasets from the Veneto region in Italy and the Upper Rhine Valley in Germany, targeting areas significantly affected by mosquito populations. A key finding is a notable correlation of 0.46 between the AE of MA predictions and the proposed confidence metric. This correlation signifies a robust, new metric for quantifying the reliability and enhancing the trustworthiness of the AI model's predictions in the context of both EO data analysis and mosquito abundance studies.

{{</citation>}}


### (18/162) CORE: Towards Scalable and Efficient Causal Discovery with Reinforcement Learning (Andreas W. M. Sauter et al., 2024)

{{<citation>}}

Andreas W. M. Sauter, Nicolò Botteghi, Erman Acar, Aske Plaat. (2024)  
**CORE: Towards Scalable and Efficient Causal Discovery with Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: I-2-6; I-2-8, cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16974v1)  

---


**ABSTRACT**  
Causal discovery is the challenging task of inferring causal structure from data. Motivated by Pearl's Causal Hierarchy (PCH), which tells us that passive observations alone are not enough to distinguish correlation from causation, there has been a recent push to incorporate interventions into machine learning research. Reinforcement learning provides a convenient framework for such an active approach to learning. This paper presents CORE, a deep reinforcement learning-based approach for causal discovery and intervention planning. CORE learns to sequentially reconstruct causal graphs from data while learning to perform informative interventions. Our results demonstrate that CORE generalizes to unseen graphs and efficiently uncovers causal structures. Furthermore, CORE scales to larger graphs with up to 10 variables and outperforms existing approaches in structure estimation accuracy and sample efficiency. All relevant code and supplementary material can be found at https://github.com/sa-and/CORE

{{</citation>}}


### (19/162) Multi-modal Representation Learning for Cross-modal Prediction of Continuous Weather Patterns from Discrete Low-Dimensional Data (Alif Bin Abdul Qayyum et al., 2024)

{{<citation>}}

Alif Bin Abdul Qayyum, Xihaier Luo, Nathan M. Urban, Xiaoning Qian, Byung-Jun Yoon. (2024)  
**Multi-modal Representation Learning for Cross-modal Prediction of Continuous Weather Patterns from Discrete Low-Dimensional Data**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2401.16936v1)  

---


**ABSTRACT**  
World is looking for clean and renewable energy sources that do not pollute the environment, in an attempt to reduce greenhouse gas emissions that contribute to global warming. Wind energy has significant potential to not only reduce greenhouse emission, but also meet the ever increasing demand for energy. To enable the effective utilization of wind energy, addressing the following three challenges in wind data analysis is crucial. Firstly, improving data resolution in various climate conditions to ensure an ample supply of information for assessing potential energy resources. Secondly, implementing dimensionality reduction techniques for data collected from sensors/simulations to efficiently manage and store large datasets. Thirdly, extrapolating wind data from one spatial specification to another, particularly in cases where data acquisition may be impractical or costly. We propose a deep learning based approach to achieve multi-modal continuous resolution wind data prediction from discontinuous wind data, along with data dimensionality reduction.

{{</citation>}}


### (20/162) Energy-conserving equivariant GNN for elasticity of lattice architected metamaterials (Ivan Grega et al., 2024)

{{<citation>}}

Ivan Grega, Ilyes Batatia, Gábor Csányi, Sri Karlapati, Vikram S. Deshpande. (2024)  
**Energy-conserving equivariant GNN for elasticity of lattice architected metamaterials**  

---
Primary Category: cs.LG  
Categories: cond-mat-mtrl-sci, cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2401.16914v1)  

---


**ABSTRACT**  
Lattices are architected metamaterials whose properties strongly depend on their geometrical design. The analogy between lattices and graphs enables the use of graph neural networks (GNNs) as a faster surrogate model compared to traditional methods such as finite element modelling. In this work we present a higher-order GNN model trained to predict the fourth-order stiffness tensor of periodic strut-based lattices. The key features of the model are (i) SE(3) equivariance, and (ii) consistency with the thermodynamic law of conservation of energy. We compare the model to non-equivariant models based on a number of error metrics and demonstrate the benefits of the encoded equivariance and energy conservation in terms of predictive performance and reduced training requirements.

{{</citation>}}


### (21/162) Evaluating ML-Based Anomaly Detection Across Datasets of Varied Integrity: A Case Study (Adrian Pekar et al., 2024)

{{<citation>}}

Adrian Pekar, Richard Jozsa. (2024)  
**Evaluating ML-Based Anomaly Detection Across Datasets of Varied Integrity: A Case Study**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-NI, cs.LG  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2401.16843v1)  

---


**ABSTRACT**  
Cybersecurity remains a critical challenge in the digital age, with network traffic flow anomaly detection being a key pivotal instrument in the fight against cyber threats. In this study, we address the prevalent issue of data integrity in network traffic datasets, which are instrumental in developing machine learning (ML) models for anomaly detection. We introduce two refined versions of the CICIDS-2017 dataset, NFS-2023-nTE and NFS-2023-TE, processed using NFStream to ensure methodologically sound flow expiration and labeling. Our research contrasts the performance of the Random Forest (RF) algorithm across the original CICIDS-2017, its refined counterparts WTMC-2021 and CRiSIS-2022, and our NFStream-generated datasets, in both binary and multi-class classification contexts. We observe that the RF model exhibits exceptional robustness, achieving consistent high-performance metrics irrespective of the underlying dataset quality, which prompts a critical discussion on the actual impact of data integrity on ML efficacy. Our study underscores the importance of continual refinement and methodological rigor in dataset generation for network security research. As the landscape of network threats evolves, so must the tools and techniques used to detect and analyze them.

{{</citation>}}


### (22/162) Online Algorithm for Node Feature Forecasting in Temporal Graphs (Aniq Ur Rahman et al., 2024)

{{<citation>}}

Aniq Ur Rahman, Justin P. Coon. (2024)  
**Online Algorithm for Node Feature Forecasting in Temporal Graphs**  

---
Primary Category: cs.LG  
Categories: cs-DM, cs-LG, cs-SY, cs.LG, eess-SY  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2401.16800v1)  

---


**ABSTRACT**  
In this paper, we propose an online algorithm "mspace" for forecasting node features in temporal graphs, which adeptly captures spatial cross-correlation among different nodes as well as the temporal autocorrelation within a node. The algorithm can be used for both probabilistic and deterministic multi-step forecasting, making it applicable for estimation and generation tasks. Comparative evaluations against various baselines, including graph neural network (GNN) based models and classical Kalman filters, demonstrate that mspace performs at par with the state-of-the-art and even surpasses them on some datasets. Importantly, mspace demonstrates consistent robustness across datasets with varying training sizes, a notable advantage over GNN-based methods requiring abundant training samples to learn the spatiotemporal trends in the data effectively. Therefore, employing mspace is advantageous in scenarios where the training sample availability is limited. Additionally, we establish theoretical bounds on multi-step forecasting error of mspace and show that it scales as $O(q)$ for $q$-step forecast.

{{</citation>}}


### (23/162) Learnable Prompt as Pseudo-Imputation: Reassessing the Necessity of Traditional EHR Data Imputation in Downstream Clinical Prediction (Weibin Liao et al., 2024)

{{<citation>}}

Weibin Liao, Yinghao Zhu, Zixiang Wang, Xu Chu, Yasha Wang, Liantao Ma. (2024)  
**Learnable Prompt as Pseudo-Imputation: Reassessing the Necessity of Traditional EHR Data Imputation in Downstream Clinical Prediction**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI, Clinical  
[Paper Link](http://arxiv.org/abs/2401.16796v1)  

---


**ABSTRACT**  
Analyzing the health status of patients based on Electronic Health Records (EHR) is a fundamental research problem in medical informatics. The presence of extensive missing values in EHR makes it challenging for deep neural networks to directly model the patient's health status based on EHR. Existing deep learning training protocols require the use of statistical information or imputation models to reconstruct missing values; however, the protocols inject non-realistic data into downstream EHR analysis models, significantly limiting model performance. This paper introduces Learnable Prompt as Pseudo Imputation (PAI) as a new training protocol. PAI no longer introduces any imputed data but constructs a learnable prompt to model the implicit preferences of the downstream model for missing values, resulting in a significant performance improvement for all EHR analysis models. Additionally, our experiments show that PAI exhibits higher robustness in situations of data insufficiency and high missing rates. More importantly, in a real-world application involving cross-institutional data with zero-shot evaluation, PAI demonstrates stronger model generalization capabilities for non-overlapping features.

{{</citation>}}


### (24/162) Performance Insights-based AI-driven Football Transfer Fee Prediction (Daniil Sulimov, 2024)

{{<citation>}}

Daniil Sulimov. (2024)  
**Performance Insights-based AI-driven Football Transfer Fee Prediction**  

---
Primary Category: cs.LG  
Categories: 68T99, cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16795v1)  

---


**ABSTRACT**  
We developed an artificial intelligence approach to predict the transfer fee of a football player. This model can help clubs make better decisions about which players to buy and sell, which can lead to improved performance and increased club budgets. Having collected data on player performance, transfer fees, and other factors that might affect a player's value, we then used this data to train a machine learning model that can accurately predict a player's impact on the game. We further passed the obtained results as one of the features to the predictor of transfer fees. The model can help clubs identify players who are undervalued and who could be sold for a profit. It can also help clubs avoid overpaying for players. We believe that our model can be a valuable tool for football clubs. It can help them make better decisions about player recruitment and transfers.

{{</citation>}}


### (25/162) Accelerated Cloud for Artificial Intelligence (ACAI) (Dachi Chen et al., 2024)

{{<citation>}}

Dachi Chen, Weitian Ding, Chen Liang, Chang Xu, Junwei Zhang, Majd Sakr. (2024)  
**Accelerated Cloud for Artificial Intelligence (ACAI)**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16791v1)  

---


**ABSTRACT**  
Training an effective Machine learning (ML) model is an iterative process that requires effort in multiple dimensions. Vertically, a single pipeline typically includes an initial ETL (Extract, Transform, Load) of raw datasets, a model training stage, and an evaluation stage where the practitioners obtain statistics of the model performance. Horizontally, many such pipelines may be required to find the best model within a search space of model configurations. Many practitioners resort to maintaining logs manually and writing simple glue code to automate the workflow. However, carrying out this process on the cloud is not a trivial task in terms of resource provisioning, data management, and bookkeeping of job histories to make sure the results are reproducible. We propose an end-to-end cloud-based machine learning platform, Accelerated Cloud for AI (ACAI), to help improve the productivity of ML practitioners. ACAI achieves this goal by enabling cloud-based storage of indexed, labeled, and searchable data, as well as automatic resource provisioning, job scheduling, and experiment tracking. Specifically, ACAI provides practitioners (1) a data lake for storing versioned datasets and their corresponding metadata, and (2) an execution engine for executing ML jobs on the cloud with automatic resource provisioning (auto-provision), logging and provenance tracking. To evaluate ACAI, we test the efficacy of our auto-provisioner on the MNIST handwritten digit classification task, and we study the usability of our system using experiments and interviews. We show that our auto-provisioner produces a 1.7x speed-up and 39% cost reduction, and our system reduces experiment time for ML scientists by 20% on typical ML use cases.

{{</citation>}}


### (26/162) Graph Fairness Learning under Distribution Shifts (Yibo Li et al., 2024)

{{<citation>}}

Yibo Li, Xiao Wang, Yujie Xing, Shaohua Fan, Ruijia Wang, Yaoqi Liu, Chuan Shi. (2024)  
**Graph Fairness Learning under Distribution Shifts**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2401.16784v1)  

---


**ABSTRACT**  
Graph neural networks (GNNs) have achieved remarkable performance on graph-structured data. However, GNNs may inherit prejudice from the training data and make discriminatory predictions based on sensitive attributes, such as gender and race. Recently, there has been an increasing interest in ensuring fairness on GNNs, but all of them are under the assumption that the training and testing data are under the same distribution, i.e., training data and testing data are from the same graph. Will graph fairness performance decrease under distribution shifts? How does distribution shifts affect graph fairness learning? All these open questions are largely unexplored from a theoretical perspective. To answer these questions, we first theoretically identify the factors that determine bias on a graph. Subsequently, we explore the factors influencing fairness on testing graphs, with a noteworthy factor being the representation distances of certain groups between the training and testing graph. Motivated by our theoretical analysis, we propose our framework FatraGNN. Specifically, to guarantee fairness performance on unknown testing graphs, we propose a graph generator to produce numerous graphs with significant bias and under different distributions. Then we minimize the representation distances for each certain group between the training graph and generated graphs. This empowers our model to achieve high classification and fairness performance even on generated graphs with significant bias, thereby effectively handling unknown testing graphs. Experiments on real-world and semi-synthetic datasets demonstrate the effectiveness of our model in terms of both accuracy and fairness.

{{</citation>}}


### (27/162) Addressing Distribution Shift in Time Series Forecasting with Instance Normalization Flows (Wei Fan et al., 2024)

{{<citation>}}

Wei Fan, Shun Zheng, Pengyang Wang, Rui Xie, Jiang Bian, Yanjie Fu. (2024)  
**Addressing Distribution Shift in Time Series Forecasting with Instance Normalization Flows**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2401.16777v1)  

---


**ABSTRACT**  
Due to non-stationarity of time series, the distribution shift problem largely hinders the performance of time series forecasting. Existing solutions either fail for the shifts beyond simple statistics or the limited compatibility with forecasting models. In this paper, we propose a general decoupled formulation for time series forecasting, with no reliance on fixed statistics and no restriction on forecasting architectures. Then, we make such a formulation formalized into a bi-level optimization problem, to enable the joint learning of the transformation (outer loop) and forecasting (inner loop). Moreover, the special requirements of expressiveness and bi-direction for the transformation motivate us to propose instance normalization flows (IN-Flow), a novel invertible network for time series transformation. Extensive experiments demonstrate our method consistently outperforms state-of-the-art baselines on both synthetic and real-world data.

{{</citation>}}


### (28/162) Extrinsicaly Rewarded Soft Q Imitation Learning with Discriminator (Ryoma Furuyama et al., 2024)

{{<citation>}}

Ryoma Furuyama, Daiki Kuyoshi, Satoshi Yamane. (2024)  
**Extrinsicaly Rewarded Soft Q Imitation Learning with Discriminator**  

---
Primary Category: cs.LG  
Categories: I-2-6, cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16772v1)  

---


**ABSTRACT**  
Imitation learning is often used in addition to reinforcement learning in environments where reward design is difficult or where the reward is sparse, but it is difficult to be able to imitate well in unknown states from a small amount of expert data and sampling data. Supervised learning methods such as Behavioral Cloning do not require sampling data, but usually suffer from distribution shift. The methods based on reinforcement learning, such as inverse reinforcement learning and Generative Adversarial imitation learning (GAIL), can learn from only a few expert data. However, they often need to interact with the environment. Soft Q imitation learning (SQIL) addressed the problems, and it was shown that it could learn efficiently by combining Behavioral Cloning and soft Q-learning with constant rewards. In order to make this algorithm more robust to distribution shift, we propose more efficient and robust algorithm by adding to this method a reward function based on adversarial inverse reinforcement learning that rewards the agent for performing actions in status similar to the demo. We call this algorithm Discriminator Soft Q Imitation Learning (DSQIL). We evaluated it on MuJoCo environments.

{{</citation>}}


### (29/162) Detection and Recovery Against Deep Neural Network Fault Injection Attacks Based on Contrastive Learning (Chenan Wang et al., 2024)

{{<citation>}}

Chenan Wang, Pu Zhao, Siyue Wang, Xue Lin. (2024)  
**Detection and Recovery Against Deep Neural Network Fault Injection Attacks Based on Contrastive Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-CV, cs-LG, cs.LG  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2401.16766v1)  

---


**ABSTRACT**  
Deep Neural Network (DNN) models when implemented on executing devices as the inference engines are susceptible to Fault Injection Attacks (FIAs) that manipulate model parameters to disrupt inference execution with disastrous performance. This work introduces Contrastive Learning (CL) of visual representations i.e., a self-supervised learning approach into the deep learning training and inference pipeline to implement DNN inference engines with self-resilience under FIAs. Our proposed CL based FIA Detection and Recovery (CFDR) framework features (i) real-time detection with only a single batch of testing data and (ii) fast recovery effective even with only a small amount of unlabeled testing data. Evaluated with the CIFAR-10 dataset on multiple types of FIAs, our CFDR shows promising detection and recovery effectiveness.

{{</citation>}}


### (30/162) One-Step Forward and Backtrack: Overcoming Zig-Zagging in Loss-Aware Quantization Training (Lianbo Ma et al., 2024)

{{<citation>}}

Lianbo Ma, Yuee Zhou, Jianlun Ma, Guo Yu, Qing Li. (2024)  
**One-Step Forward and Backtrack: Overcoming Zig-Zagging in Loss-Aware Quantization Training**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2401.16760v1)  

---


**ABSTRACT**  
Weight quantization is an effective technique to compress deep neural networks for their deployment on edge devices with limited resources. Traditional loss-aware quantization methods commonly use the quantized gradient to replace the full-precision gradient. However, we discover that the gradient error will lead to an unexpected zig-zagging-like issue in the gradient descent learning procedures, where the gradient directions rapidly oscillate or zig-zag, and such issue seriously slows down the model convergence. Accordingly, this paper proposes a one-step forward and backtrack way for loss-aware quantization to get more accurate and stable gradient direction to defy this issue. During the gradient descent learning, a one-step forward search is designed to find the trial gradient of the next-step, which is adopted to adjust the gradient of current step towards the direction of fast convergence. After that, we backtrack the current step to update the full-precision and quantized weights through the current-step gradient and the trial gradient. A series of theoretical analysis and experiments on benchmark deep models have demonstrated the effectiveness and competitiveness of the proposed method, and our method especially outperforms others on the convergence performance.

{{</citation>}}


### (31/162) SwapNet: Efficient Swapping for DNN Inference on Edge AI Devices Beyond the Memory Budget (Kun Wang et al., 2024)

{{<citation>}}

Kun Wang, Jiani Cao, Zimu Zhou, Zhenjiang Li. (2024)  
**SwapNet: Efficient Swapping for DNN Inference on Edge AI Devices Beyond the Memory Budget**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-DC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16757v1)  

---


**ABSTRACT**  
Executing deep neural networks (DNNs) on edge artificial intelligence (AI) devices enables various autonomous mobile computing applications. However, the memory budget of edge AI devices restricts the number and complexity of DNNs allowed in such applications. Existing solutions, such as model compression or cloud offloading, reduce the memory footprint of DNN inference at the cost of decreased model accuracy or autonomy. To avoid these drawbacks, we divide DNN into blocks and swap them in and out in order, such that large DNNs can execute within a small memory budget. Nevertheless, naive swapping on edge AI devices induces significant delays due to the redundant memory operations in the DNN development ecosystem for edge AI devices. To this end, we develop SwapNet, an efficient DNN block swapping middleware for edge AI devices. We systematically eliminate the unnecessary memory operations during block swapping while retaining compatible with the deep learning frameworks, GPU backends, and hardware architectures of edge AI devices. We further showcase the utility of SwapNet via a multi-DNN scheduling scheme. Evaluations on eleven DNN inference tasks in three applications demonstrate that SwapNet achieves almost the same latency as the case with sufficient memory even when DNNs demand 2.32x to 5.81x memory beyond the available budget. The design of SwapNet also provides novel and feasible insights for deploying large language models (LLMs) on edge AI devices in the future.

{{</citation>}}


### (32/162) AI Oversight and Human Mistakes: Evidence from Centre Court (David Almog et al., 2024)

{{<citation>}}

David Almog, Romain Gauriot, Lionel Page, Daniel Martin. (2024)  
**AI Oversight and Human Mistakes: Evidence from Centre Court**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-LG, cs.LG, econ-GN, q-fin-EC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16754v1)  

---


**ABSTRACT**  
Powered by the increasing predictive capabilities of machine learning algorithms, artificial intelligence (AI) systems have begun to be used to overrule human mistakes in many settings. We provide the first field evidence this AI oversight carries psychological costs that can impact human decision-making. We investigate one of the highest visibility settings in which AI oversight has occurred: the Hawk-Eye review of umpires in top tennis tournaments. We find that umpires lowered their overall mistake rate after the introduction of Hawk-Eye review, in line with rational inattention given psychological costs of being overruled by AI. We also find that umpires increased the rate at which they called balls in, which produced a shift from making Type II errors (calling a ball out when in) to Type I errors (calling a ball in when out). We structurally estimate the psychological costs of being overruled by AI using a model of rational inattentive umpires, and our results suggest that because of these costs, umpires cared twice as much about Type II errors under AI oversight.

{{</citation>}}


### (33/162) SmartFRZ: An Efficient Training Framework using Attention-Based Layer Freezing (Sheng Li et al., 2024)

{{<citation>}}

Sheng Li, Geng Yuan, Yue Dai, Youtao Zhang, Yanzhi Wang, Xulong Tang. (2024)  
**SmartFRZ: An Efficient Training Framework using Attention-Based Layer Freezing**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2401.16720v1)  

---


**ABSTRACT**  
There has been a proliferation of artificial intelligence applications, where model training is key to promising high-quality services for these applications. However, the model training process is both time-intensive and energy-intensive, inevitably affecting the user's demand for application efficiency. Layer freezing, an efficient model training technique, has been proposed to improve training efficiency. Although existing layer freezing methods demonstrate the great potential to reduce model training costs, they still remain shortcomings such as lacking generalizability and compromised accuracy. For instance, existing layer freezing methods either require the freeze configurations to be manually defined before training, which does not apply to different networks, or use heuristic freezing criteria that is hard to guarantee decent accuracy in different scenarios. Therefore, there lacks a generic and smart layer freezing method that can automatically perform ``in-situation'' layer freezing for different networks during training processes. To this end, we propose a generic and efficient training framework (SmartFRZ). The core proposed technique in SmartFRZ is attention-guided layer freezing, which can automatically select the appropriate layers to freeze without compromising accuracy. Experimental results show that SmartFRZ effectively reduces the amount of computation in training and achieves significant training acceleration, and outperforms the state-of-the-art layer freezing approaches.

{{</citation>}}


### (34/162) Augmenting Replay in World Models for Continual Reinforcement Learning (Luke Yang et al., 2024)

{{<citation>}}

Luke Yang, Levin Kuhlmann, Gideon Kowadlo. (2024)  
**Augmenting Replay in World Models for Continual Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: I-2-6; I-5-0; I-5-1, cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16650v1)  

---


**ABSTRACT**  
In continual RL, the environment of a reinforcement learning (RL) agent undergoes change. A successful system should appropriately balance the conflicting requirements of retaining agent performance on already learned tasks, stability, whilst learning new tasks, plasticity. The first-in-first-out buffer is commonly used to enhance learning in such settings but requires significant memory. We explore the application of an augmentation to this buffer which alleviates the memory constraints, and use it with a world model model-based reinforcement learning algorithm, to evaluate its effectiveness in facilitating continual learning. We evaluate the effectiveness of our method in Procgen and Atari RL benchmarks and show that the distribution matching augmentation to the replay-buffer used in the context of latent world models can successfully prevent catastrophic forgetting with significantly reduced computational overhead. Yet, we also find such a solution to not be entirely infallible, and other failure modes such as the opposite -- lacking plasticity and being unable to learn a new task -- to be a potential limitation in continual learning systems.

{{</citation>}}


### (35/162) Using Motion Forecasting for Behavior-Based Virtual Reality (VR) Authentication (Mingjun Li et al., 2024)

{{<citation>}}

Mingjun Li, Natasha Kholgade Banerjee, Sean Banerjee. (2024)  
**Using Motion Forecasting for Behavior-Based Virtual Reality (VR) Authentication**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2401.16649v1)  

---


**ABSTRACT**  
Task-based behavioral biometric authentication of users interacting in virtual reality (VR) environments enables seamless continuous authentication by using only the motion trajectories of the person's body as a unique signature. Deep learning-based approaches for behavioral biometrics show high accuracy when using complete or near complete portions of the user trajectory, but show lower performance when using smaller segments from the start of the task. Thus, any systems designed with existing techniques are vulnerable while waiting for future segments of motion trajectories to become available. In this work, we present the first approach that predicts future user behavior using Transformer-based forecasting and using the forecasted trajectory to perform user authentication. Our work leverages the notion that given the current trajectory of a user in a task-based environment we can predict the future trajectory of the user as they are unlikely to dramatically shift their behavior since it would preclude the user from successfully completing their task goal. Using the publicly available 41-subject ball throwing dataset of Miller et al. we show improvement in user authentication when using forecasted data. When compared to no forecasting, our approach reduces the authentication equal error rate (EER) by an average of 23.85% and a maximum reduction of 36.14%.

{{</citation>}}


### (36/162) Improving Reinforcement Learning from Human Feedback with Efficient Reward Model Ensemble (Shun Zhang et al., 2024)

{{<citation>}}

Shun Zhang, Zhenfang Chen, Sunli Chen, Yikang Shen, Zhiqing Sun, Chuang Gan. (2024)  
**Improving Reinforcement Learning from Human Feedback with Efficient Reward Model Ensemble**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16635v1)  

---


**ABSTRACT**  
Reinforcement Learning from Human Feedback (RLHF) is a widely adopted approach for aligning large language models with human values. However, RLHF relies on a reward model that is trained with a limited amount of human preference data, which could lead to inaccurate predictions. As a result, RLHF may produce outputs that are misaligned with human values. To mitigate this issue, we contribute a reward ensemble method that allows the reward model to make more accurate predictions. As using an ensemble of large language model-based reward models can be computationally and resource-expensive, we explore efficient ensemble methods including linear-layer ensemble and LoRA-based ensemble. Empirically, we run Best-of-$n$ and Proximal Policy Optimization with our ensembled reward models, and verify that our ensemble methods help improve the alignment performance of RLHF outputs.

{{</citation>}}


## cs.DB (2)



### (37/162) When Large Language Models Meet Vector Databases: A Survey (Zhi Jing et al., 2024)

{{<citation>}}

Zhi Jing, Yongye Su, Yikun Han, Bo Yuan, Chunjiang Liu, Haiyun Xu, Kehai Chen. (2024)  
**When Large Language Models Meet Vector Databases: A Survey**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-CL, cs-DB, cs-LG, cs.DB  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2402.01763v1)  

---


**ABSTRACT**  
The recent burst in Large Language Models has opened new frontiers in human-like text processing and generation. However, alongside their remarkable growth, Large Language Models have encountered critical challenges including issues of hallucination, bias, real-time knowledge updates, and the high costs of implementation and maintenance in commercial settings. Vector Databases, another increasingly popular tool, offer potential solutions to these challenges. These databases are adept at handling high-dimensional data and are crucial for tasks such as efficient information retrieval and semantic search. By integrating with Large Language Models, they significantly enhance AI systems' ability to manage and utilize diverse data more effectively. This survey paper provides an in-depth and unique analysis of the intersection between Large Language Models and Vector Databases.

{{</citation>}}


### (38/162) Learning Approximation Sets for Exploratory Queries (Susan B. Davidson et al., 2024)

{{<citation>}}

Susan B. Davidson, Tova Milo, Kathy Razmadze, Gal Zeevi. (2024)  
**Learning Approximation Sets for Exploratory Queries**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.17059v1)  

---


**ABSTRACT**  
In data exploration, executing complex non-aggregate queries over large databases can be time-consuming. Our paper introduces a novel approach to address this challenge, focusing on finding an optimized subset of data, referred to as the approximation set, for query execution. The goal is to maximize query result quality while minimizing execution time. We formalize this problem as Approximate Non-Aggregates Query Processing (ANAQP) and establish its NP-completeness. To tackle this, we propose an approximate solution using advanced Reinforcement Learning architecture, termed ASQP-RL. This approach overcomes challenges related to the large action space and the need for generalization beyond a known query workload. Experimental results on two benchmarks demonstrate the superior performance of ASQP-RL, outperforming baselines by 30% in accuracy and achieving efficiency gains of 10-35X. Our research sheds light on the potential of reinforcement learning techniques for advancing data management tasks. Experimental results on two benchmarks show that ASQP-RL significantly outperforms the baselines both in terms of accuracy (30% better) and efficiency (10-35X). This research provides valuable insights into the potential of RL techniques for future advancements in data management tasks.

{{</citation>}}


## cs.CL (41)



### (39/162) Improving QA Model Performance with Cartographic Inoculation (Allen Chen et al., 2024)

{{<citation>}}

Allen Chen, Okan Tanrikulu. (2024)  
**Improving QA Model Performance with Cartographic Inoculation**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs.CL  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2401.17498v2)  

---


**ABSTRACT**  
QA models are faced with complex and open-ended contextual reasoning problems, but can often learn well-performing solution heuristics by exploiting dataset-specific patterns in their training data. These patterns, or "dataset artifacts", reduce the model's ability to generalize to real-world QA problems. Utilizing an ElectraSmallDiscriminator model trained for QA, we analyze the impacts and incidence of dataset artifacts using an adversarial challenge set designed to confuse models reliant on artifacts for prediction. Extending existing work on methods for mitigating artifact impacts, we propose cartographic inoculation, a novel method that fine-tunes models on an optimized subset of the challenge data to reduce model reliance on dataset artifacts. We show that by selectively fine-tuning a model on ambiguous adversarial examples from a challenge set, significant performance improvements can be made on the full challenge dataset with minimal loss of model generalizability to other challenging environments and QA datasets.

{{</citation>}}


### (40/162) Detecting mental disorder on social media: a ChatGPT-augmented explainable approach (Loris Belcastro et al., 2024)

{{<citation>}}

Loris Belcastro, Riccardo Cantini, Fabrizio Marozzo, Domenico Talia, Paolo Trunfio. (2024)  
**Detecting mental disorder on social media: a ChatGPT-augmented explainable approach**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs-SI, cs.CL  
Keywords: AI, BERT, ChatGPT, GPT, Language Model, Twitter  
[Paper Link](http://arxiv.org/abs/2401.17477v1)  

---


**ABSTRACT**  
In the digital era, the prevalence of depressive symptoms expressed on social media has raised serious concerns, necessitating advanced methodologies for timely detection. This paper addresses the challenge of interpretable depression detection by proposing a novel methodology that effectively combines Large Language Models (LLMs) with eXplainable Artificial Intelligence (XAI) and conversational agents like ChatGPT. In our methodology, explanations are achieved by integrating BERTweet, a Twitter-specific variant of BERT, into a novel self-explanatory model, namely BERT-XDD, capable of providing both classification and explanations via masked attention. The interpretability is further enhanced using ChatGPT to transform technical explanations into human-readable commentaries. By introducing an effective and modular approach for interpretable depression detection, our methodology can contribute to the development of socially responsible digital platforms, fostering early intervention and support for mental health challenges under the guidance of qualified healthcare professionals.

{{</citation>}}


### (41/162) D-Nikud: Enhancing Hebrew Diacritization with LSTM and Pretrained Models (Adi Rosenthal et al., 2024)

{{<citation>}}

Adi Rosenthal, Nadav Shaked. (2024)  
**D-Nikud: Enhancing Hebrew Diacritization with LSTM and Pretrained Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT, LSTM  
[Paper Link](http://arxiv.org/abs/2402.00075v1)  

---


**ABSTRACT**  
D-Nikud, a novel approach to Hebrew diacritization that integrates the strengths of LSTM networks and BERT-based (transformer) pre-trained model. Inspired by the methodologies employed in Nakdimon, we integrate it with the TavBERT pre-trained model, our system incorporates advanced architectural choices and diverse training data. Our experiments showcase state-of-the-art results on several benchmark datasets, with a particular emphasis on modern texts and more specified diacritization like gender.

{{</citation>}}


### (42/162) Efficient Tool Use with Chain-of-Abstraction Reasoning (Silin Gao et al., 2024)

{{<citation>}}

Silin Gao, Jane Dwivedi-Yu, Ping Yu, Xiaoqing Ellen Tan, Ramakanth Pasunuru, Olga Golovneva, Koustuv Sinha, Asli Celikyilmaz, Antoine Bosselut, Tianlu Wang. (2024)  
**Efficient Tool Use with Chain-of-Abstraction Reasoning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: QA, Reasoning  
[Paper Link](http://arxiv.org/abs/2401.17464v1)  

---


**ABSTRACT**  
To achieve faithful reasoning that aligns with human expectations, large language models (LLMs) need to ground their reasoning to real-world knowledge (e.g., web facts, math and physical rules). Tools help LLMs access this external knowledge, but there remains challenges for fine-tuning LLM agents (e.g., Toolformer) to invoke tools in multi-step reasoning problems, where inter-connected tool calls require holistic and efficient tool usage planning.   In this work, we propose a new method for LLMs to better leverage tools in multi-step reasoning. Our method, Chain-of-Abstraction (CoA), trains LLMs to first decode reasoning chains with abstract placeholders, and then call domain tools to reify each reasoning chain by filling in specific knowledge. This planning with abstract chains enables LLMs to learn more general reasoning strategies, which are robust to shifts of domain knowledge (e.g., math results) relevant to different reasoning questions. It also allows LLMs to perform decoding and calling of external tools in parallel, which avoids the inference delay caused by waiting for tool responses. In mathematical reasoning and Wiki QA domains, we show that our method consistently outperforms previous chain-of-thought and tool-augmented baselines on both in-distribution and out-of-distribution test sets, with an average ~6% absolute QA accuracy improvement. LLM agents trained with our method also show more efficient tool use, with inference speed being on average ~1.4x faster than baseline tool-augmented LLMs.

{{</citation>}}


### (43/162) Synthetic Dialogue Dataset Generation using LLM Agents (Yelaman Abdullin et al., 2024)

{{<citation>}}

Yelaman Abdullin, Diego Molla-Aliod, Bahadorreza Ofoghi, John Yearwood, Qingyang Li. (2024)  
**Synthetic Dialogue Dataset Generation using LLM Agents**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Dialog, Dialogue, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2401.17461v1)  

---


**ABSTRACT**  
Linear programming (LP) problems are pervasive in real-life applications. However, despite their apparent simplicity, an untrained user may find it difficult to determine the linear model of their specific problem. We envisage the creation of a goal-oriented conversational agent that will engage in conversation with the user to elicit all information required so that a subsequent agent can generate the linear model. In this paper, we present an approach for the generation of sample dialogues that can be used to develop and train such a conversational agent. Using prompt engineering, we develop two agents that "talk" to each other, one acting as the conversational agent, and the other acting as the user. Using a set of text descriptions of linear problems from NL4Opt available to the user only, the agent and the user engage in conversation until the agent has retrieved all key information from the original problem description. We also propose an extrinsic evaluation of the dialogues by assessing how well the summaries generated by the dialogues match the original problem descriptions. We conduct human and automatic evaluations, including an evaluation approach that uses GPT-4 to mimic the human evaluation metrics. The evaluation results show an overall good quality of the dialogues, though research is still needed to improve the quality of the GPT-4 evaluation metrics. The resulting dialogues, including the human annotations of a subset, are available to the research community. The conversational agent used for the generation of the dialogues can be used as a baseline.

{{</citation>}}


### (44/162) Fine-tuning Transformer-based Encoder for Turkish Language Understanding Tasks (Savas Yildirim, 2024)

{{<citation>}}

Savas Yildirim. (2024)  
**Fine-tuning Transformer-based Encoder for Turkish Language Understanding Tasks**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BERT, NLU, Question Answering, Sentiment Analysis, Text Classification, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.17396v1)  

---


**ABSTRACT**  
Deep learning-based and lately Transformer-based language models have been dominating the studies of natural language processing in the last years. Thanks to their accurate and fast fine-tuning characteristics, they have outperformed traditional machine learning-based approaches and achieved state-of-the-art results for many challenging natural language understanding (NLU) problems. Recent studies showed that the Transformer-based models such as BERT, which is Bidirectional Encoder Representations from Transformers, have reached impressive achievements on many tasks. Moreover, thanks to their transfer learning capacity, these architectures allow us to transfer pre-built models and fine-tune them to specific NLU tasks such as question answering. In this study, we provide a Transformer-based model and a baseline benchmark for the Turkish Language. We successfully fine-tuned a Turkish BERT model, namely BERTurk that is trained with base settings, to many downstream tasks and evaluated with a the Turkish Benchmark dataset. We showed that our studies significantly outperformed other existing baseline approaches for Named-Entity Recognition, Sentiment Analysis, Question Answering and Text Classification in Turkish Language. We publicly released these four fine-tuned models and resources in reproducibility and with the view of supporting other Turkish researchers and applications.

{{</citation>}}


### (45/162) Customizing Language Model Responses with Contrastive In-Context Learning (Xiang Gao et al., 2024)

{{<citation>}}

Xiang Gao, Kamalika Das. (2024)  
**Customizing Language Model Responses with Contrastive In-Context Learning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17390v1)  

---


**ABSTRACT**  
Large language models (LLMs) are becoming increasingly important for machine learning applications. However, it can be challenging to align LLMs with our intent, particularly when we want to generate content that is preferable over others or when we want the LLM to respond in a certain style or tone that is hard to describe. To address this challenge, we propose an approach that uses contrastive examples to better describe our intent. This involves providing positive examples that illustrate the true intent, along with negative examples that show what characteristics we want LLMs to avoid. The negative examples can be retrieved from labeled data, written by a human, or generated by the LLM itself. Before generating an answer, we ask the model to analyze the examples to teach itself what to avoid. This reasoning step provides the model with the appropriate articulation of the user's need and guides it towards generting a better answer. We tested our approach on both synthesized and real-world datasets, including StackExchange and Reddit, and found that it significantly improves performance compared to standard few-shot prompting

{{</citation>}}


### (46/162) Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens (Jiacheng Liu et al., 2024)

{{<citation>}}

Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi. (2024)  
**Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs.CL  
Keywords: Language Model, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.17377v1)  

---


**ABSTRACT**  
Are n-gram language models still relevant in this era of neural large language models (LLMs)? Our answer is yes, and we show their values in both text analysis and improving neural LLMs. Yet this necessitates modernizing n-gram models in two aspects. First, we train them at the same data scale as neural LLMs -- 1.4 trillion tokens. This is the largest n-gram model ever built. Second, existing n-gram models use small n which hinders their performance; we instead allow n to be arbitrarily large, by introducing a new $\infty$-gram LM with backoff. Instead of pre-computing n-gram count tables (which would be very expensive), we develop an engine named infini-gram -- powered by suffix arrays -- that can compute $\infty$-gram (as well as n-gram with arbitrary n) probabilities with millisecond-level latency. The $\infty$-gram framework and infini-gram engine enable us to conduct many novel and interesting analyses of human-written and machine-generated text: we find that the $\infty$-gram LM has fairly high accuracy for next-token prediction (47%), and can complement neural LLMs to greatly reduce their language modeling perplexities. When analyzing machine-generated text, we also observe irregularities in the machine--$\infty$-gram agreement level with respect to the suffix length, which indicates deficiencies in neural LLM pretraining and the positional embeddings of Transformers. We open-source our infini-gram engine in the hopes of enabling more study on how to best use verbatim information retrieved from large text corpora.

{{</citation>}}


### (47/162) Arabic Tweet Act: A Weighted Ensemble Pre-Trained Transformer Model for Classifying Arabic Speech Acts on Twitter (Khadejaa Alshehri et al., 2024)

{{<citation>}}

Khadejaa Alshehri, Areej Alhothali, Nahed Alowidi. (2024)  
**Arabic Tweet Act: A Weighted Ensemble Pre-Trained Transformer Model for Classifying Arabic Speech Acts on Twitter**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BERT, Transformer, Twitter  
[Paper Link](http://arxiv.org/abs/2401.17373v1)  

---


**ABSTRACT**  
Speech acts are a speakers actions when performing an utterance within a conversation, such as asking, recommending, greeting, or thanking someone, expressing a thought, or making a suggestion. Understanding speech acts helps interpret the intended meaning and actions behind a speakers or writers words. This paper proposes a Twitter dialectal Arabic speech act classification approach based on a transformer deep learning neural network. Twitter and social media, are becoming more and more integrated into daily life. As a result, they have evolved into a vital source of information that represents the views and attitudes of their users. We proposed a BERT based weighted ensemble learning approach to integrate the advantages of various BERT models in dialectal Arabic speech acts classification. We compared the proposed model against several variants of Arabic BERT models and sequence-based models. We developed a dialectal Arabic tweet act dataset by annotating a subset of a large existing Arabic sentiment analysis dataset (ASAD) based on six speech act categories. We also evaluated the models on a previously developed Arabic Tweet Act dataset (ArSAS). To overcome the class imbalance issue commonly observed in speech act problems, a transformer-based data augmentation model was implemented to generate an equal proportion of speech act categories. The results show that the best BERT model is araBERTv2-Twitter models with a macro-averaged F1 score and an accuracy of 0.73 and 0.84, respectively. The performance improved using a BERT-based ensemble method with a 0.74 and 0.85 averaged F1 score and accuracy on our dataset, respectively.

{{</citation>}}


### (48/162) Weaver: Foundation Models for Creative Writing (Tiannan Wang et al., 2024)

{{<citation>}}

Tiannan Wang, Jiamin Chen, Qingrui Jia, Shuai Wang, Ruoyu Fang, Huilin Wang, Zhaowei Gao, Chunzhao Xie, Chuou Xu, Jihong Dai, Yibin Liu, Jialong Wu, Shengwei Ding, Long Li, Zhiwei Huang, Xinle Deng, Teng Yu, Gangan Ma, Han Xiao, Zixin Chen, Danjun Xiang, Yunxia Wang, Yuanyuan Zhu, Yi Xiao, Jing Wang, Yiru Wang, Siran Ding, Jiayang Huang, Jiayi Xu, Yilihamu Tayier, Zhenyu Hu, Yuan Gao, Chengfeng Zheng, Yueshu Ye, Yihang Li, Lei Wan, Xinyue Jiang, Yujie Wang, Siyu Cheng, Zhule Song, Xiangru Tang, Xiaohua Xu, Ningyu Zhang, Huajun Chen, Yuchen Eleanor Jiang, Wangchunshu Zhou. (2024)  
**Weaver: Foundation Models for Creative Writing**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: AI, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2401.17268v1)  

---


**ABSTRACT**  
This work introduces Weaver, our first family of large language models (LLMs) dedicated to content creation. Weaver is pre-trained on a carefully selected corpus that focuses on improving the writing capabilities of large language models. We then fine-tune Weaver for creative and professional writing purposes and align it to the preference of professional writers using a suit of novel methods for instruction data synthesis and LLM alignment, making it able to produce more human-like texts and follow more diverse instructions for content creation. The Weaver family consists of models of Weaver Mini (1.8B), Weaver Base (6B), Weaver Pro (14B), and Weaver Ultra (34B) sizes, suitable for different applications and can be dynamically dispatched by a routing agent according to query complexity to balance response quality and computation cost. Evaluation on a carefully curated benchmark for assessing the writing capabilities of LLMs shows Weaver models of all sizes outperform generalist LLMs several times larger than them. Notably, our most-capable Weaver Ultra model surpasses GPT-4, a state-of-the-art generalist LLM, on various writing scenarios, demonstrating the advantage of training specialized LLMs for writing purposes. Moreover, Weaver natively supports retrieval-augmented generation (RAG) and function calling (tool usage). We present various use cases of these abilities for improving AI-assisted writing systems, including integration of external knowledge bases, tools, or APIs, and providing personalized writing assistance. Furthermore, we discuss and summarize a guideline and best practices for pre-training and fine-tuning domain-specific LLMs.

{{</citation>}}


### (49/162) Weak-to-Strong Jailbreaking on Large Language Models (Xuandong Zhao et al., 2024)

{{<citation>}}

Xuandong Zhao, Xianjun Yang, Tianyu Pang, Chao Du, Lei Li, Yu-Xiang Wang, William Yang Wang. (2024)  
**Weak-to-Strong Jailbreaking on Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17256v2)  

---


**ABSTRACT**  
Large language models (LLMs) are vulnerable to jailbreak attacks - resulting in harmful, unethical, or biased text generations. However, existing jailbreaking methods are computationally costly. In this paper, we propose the weak-to-strong jailbreaking attack, an efficient method to attack aligned LLMs to produce harmful text. Our key intuition is based on the observation that jailbroken and aligned models only differ in their initial decoding distributions. The weak-to-strong attack's key technical insight is using two smaller models (a safe and an unsafe one) to adversarially modify a significantly larger safe model's decoding probabilities. We evaluate the weak-to-strong attack on 5 diverse LLMs from 3 organizations. The results show our method can increase the misalignment rate to over 99% on two datasets with just one forward pass per example. Our study exposes an urgent safety issue that needs to be addressed when aligning LLMs. As an initial attempt, we propose a defense strategy to protect against such attacks, but creating more advanced defenses remains challenging. The code for replicating the method is available at https://github.com/XuandongZhao/weak-to-strong

{{</citation>}}


### (50/162) LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation (Yuan Chiang et al., 2024)

{{<citation>}}

Yuan Chiang, Chia-Hong Chou, Janosh Riebesell. (2024)  
**LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation**  

---
Primary Category: cs.CL  
Categories: cond-mat-mtrl-sci, cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, Language Model  
[Paper Link](http://arxiv.org/abs/2401.17244v1)  

---


**ABSTRACT**  
Reducing hallucination of Large Language Models (LLMs) is imperative for use in the sciences where reproducibility is crucial. However, LLMs inherently lack long-term memory, making it a nontrivial, ad hoc, and inevitably biased task to fine-tune them on domain-specific literature and data. Here we introduce LLaMP, a multimodal retrieval-augmented generation (RAG) framework of multiple data-aware reasoning-and-acting (ReAct) agents that dynamically interact with computational and experimental data on Materials Project (MP). Without fine-tuning, LLaMP demonstrates an ability to comprehend and integrate various modalities of materials science concepts, fetch relevant data stores on the fly, process higher-order data (such as crystal structures and elastic tensors), and summarize multi-step procedures for solid-state synthesis. We show that LLaMP effectively corrects errors in GPT-3.5's intrinsic knowledge, reducing a 5.21% MAPE on frequently-documented bandgaps and a significant 1103.54% MAPE on formation energies -- errors that GPT-3.5 seems to derive from mixed data sources. Additionally, LLaMP substantially reduces the hallucinated volumetric strain in a diamond cubic silicon structure from 66.3% to 0. The proposed framework offers an intuitive and nearly hallucination-free approach to exploring materials informatics and establishes a pathway for knowledge distillation and fine-tuning other language models. We envision the framework as a valuable component for scientific hypotheses and a foundation for future autonomous laboratories where multiple LLM agents communicate and cooperate with robotics to drive material synthesis and chemical reactions without hard-coded human logic and intervention.

{{</citation>}}


### (51/162) Morality is Non-Binary: Building a Pluralist Moral Sentence Embedding Space using Contrastive Learning (Jeongwoo Park et al., 2024)

{{<citation>}}

Jeongwoo Park, Enrico Liscio, Pradeep K. Murukannaiah. (2024)  
**Morality is Non-Binary: Building a Pluralist Moral Sentence Embedding Space using Contrastive Learning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Contrastive Learning, Embedding, NLP, Sentence Embedding  
[Paper Link](http://arxiv.org/abs/2401.17228v1)  

---


**ABSTRACT**  
Recent advances in NLP show that language models retain a discernible level of knowledge in deontological ethics and moral norms. However, existing works often treat morality as binary, ranging from right to wrong. This simplistic view does not capture the nuances of moral judgment. Pluralist moral philosophers argue that human morality can be deconstructed into a finite number of elements, respecting individual differences in moral judgment. In line with this view, we build a pluralist moral sentence embedding space via a state-of-the-art contrastive learning approach. We systematically investigate the embedding space by studying the emergence of relationships among moral elements, both quantitatively and qualitatively. Our results show that a pluralist approach to morality can be captured in an embedding space. However, moral pluralism is challenging to deduce via self-supervision alone and requires a supervised approach with human labels.

{{</citation>}}


### (52/162) Gazetteer-Enhanced Bangla Named Entity Recognition with BanglaBERT Semantic Embeddings K-Means-Infused CRF Model (Niloy Farhan et al., 2024)

{{<citation>}}

Niloy Farhan, Saman Sarker Joy, Tafseer Binte Mannan, Farig Sadeque. (2024)  
**Gazetteer-Enhanced Bangla Named Entity Recognition with BanglaBERT Semantic Embeddings K-Means-Infused CRF Model**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT, Embedding, NER, NLP, Named Entity Recognition, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2401.17206v1)  

---


**ABSTRACT**  
Named Entity Recognition (NER) is a sub-task of Natural Language Processing (NLP) that distinguishes entities from unorganized text into predefined categorization. In recent years, a lot of Bangla NLP subtasks have received quite a lot of attention; but Named Entity Recognition in Bangla still lags behind. In this research, we explored the existing state of research in Bangla Named Entity Recognition. We tried to figure out the limitations that current techniques and datasets face, and we would like to address these limitations in our research. Additionally, We developed a Gazetteer that has the ability to significantly boost the performance of NER. We also proposed a new NER solution by taking advantage of state-of-the-art NLP tools that outperform conventional techniques.

{{</citation>}}


### (53/162) Rethinking Interpretability in the Era of Large Language Models (Chandan Singh et al., 2024)

{{<citation>}}

Chandan Singh, Jeevana Priya Inala, Michel Galley, Rich Caruana, Jianfeng Gao. (2024)  
**Rethinking Interpretability in the Era of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01761v1)  

---


**ABSTRACT**  
Interpretable machine learning has exploded as an area of interest over the last decade, sparked by the rise of increasingly large datasets and deep neural networks. Simultaneously, large language models (LLMs) have demonstrated remarkable capabilities across a wide array of tasks, offering a chance to rethink opportunities in interpretable machine learning. Notably, the capability to explain in natural language allows LLMs to expand the scale and complexity of patterns that can be given to a human. However, these new capabilities raise new challenges, such as hallucinated explanations and immense computational costs.   In this position paper, we start by reviewing existing methods to evaluate the emerging field of LLM interpretation (both interpreting LLMs and using LLMs for explanation). We contend that, despite their limitations, LLMs hold the opportunity to redefine interpretability with a more ambitious scope across many applications, including in auditing LLMs themselves. We highlight two emerging research priorities for LLM interpretation: using LLMs to directly analyze new datasets and to generate interactive explanations.

{{</citation>}}


### (54/162) Single Word Change is All You Need: Designing Attacks and Defenses for Text Classifiers (Lei Xu et al., 2024)

{{<citation>}}

Lei Xu, Sarah Alnegheimish, Laure Berti-Equille, Alfredo Cuesta-Infante, Kalyan Veeramachaneni. (2024)  
**Single Word Change is All You Need: Designing Attacks and Defenses for Text Classifiers**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2401.17196v1)  

---


**ABSTRACT**  
In text classification, creating an adversarial example means subtly perturbing a few words in a sentence without changing its meaning, causing it to be misclassified by a classifier. A concerning observation is that a significant portion of adversarial examples generated by existing methods change only one word. This single-word perturbation vulnerability represents a significant weakness in classifiers, which malicious users can exploit to efficiently create a multitude of adversarial examples. This paper studies this problem and makes the following key contributions: (1) We introduce a novel metric \r{ho} to quantitatively assess a classifier's robustness against single-word perturbation. (2) We present the SP-Attack, designed to exploit the single-word perturbation vulnerability, achieving a higher attack success rate, better preserving sentence meaning, while reducing computation costs compared to state-of-the-art adversarial methods. (3) We propose SP-Defense, which aims to improve \r{ho} by applying data augmentation in learning. Experimental results on 4 datasets and BERT and distilBERT classifiers show that SP-Defense improves \r{ho} by 14.6% and 13.9% and decreases the attack success rate of SP-Attack by 30.4% and 21.2% on two classifiers respectively, and decreases the attack success rate of existing attack methods that involve multiple-word perturbations.

{{</citation>}}


### (55/162) Transfer Learning for Text Diffusion Models (Kehang Han et al., 2024)

{{<citation>}}

Kehang Han, Kathleen Kenealy, Aditya Barua, Noah Fiedel, Noah Constant. (2024)  
**Transfer Learning for Text Diffusion Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2401.17181v1)  

---


**ABSTRACT**  
In this report, we explore the potential for text diffusion to replace autoregressive (AR) decoding for the training and deployment of large language models (LLMs). We are particularly interested to see whether pretrained AR models can be transformed into text diffusion models through a lightweight adaptation procedure we call ``AR2Diff''. We begin by establishing a strong baseline setup for training text diffusion models. Comparing across multiple architectures and pretraining objectives, we find that training a decoder-only model with a prefix LM objective is best or near-best across several tasks. Building on this finding, we test various transfer learning setups for text diffusion models. On machine translation, we find that text diffusion underperforms the standard AR approach. However, on code synthesis and extractive QA, we find diffusion models trained from scratch outperform AR models in many cases. We also observe quality gains from AR2Diff -- adapting AR models to use diffusion decoding. These results are promising given that text diffusion is relatively underexplored and can be significantly faster than AR decoding for long text generation.

{{</citation>}}


### (56/162) Conditional and Modal Reasoning in Large Language Models (Wesley H. Holliday et al., 2024)

{{<citation>}}

Wesley H. Holliday, Matthew Mandelkern. (2024)  
**Conditional and Modal Reasoning in Large Language Models**  

---
Primary Category: cs.CL  
Categories: 68T50, 03B65, I-2-7, cs-AI, cs-CL, cs-LO, cs.CL  
Keywords: GPT, GPT-4, Language Model, Reasoning  
[Paper Link](http://arxiv.org/abs/2401.17169v1)  

---


**ABSTRACT**  
The reasoning abilities of large language models (LLMs) are the topic of a growing body of research in artificial intelligence and cognitive science. In this paper, we probe the extent to which a dozen LLMs are able to distinguish logically correct inferences from logically fallacious ones. We focus on inference patterns involving conditionals (e.g., 'If Ann has a queen, then Bob has a jack') and epistemic modals (e.g., 'Ann might have an ace', 'Bob must have a king'). These inference patterns have been of special interest to logicians, philosophers, and linguists, since they plausibly play a central role in human reasoning. Assessing LLMs on these inference patterns is thus highly relevant to the question of how much the reasoning abilities of LLMs match those of humans. Among the LLMs we tested, all but GPT-4 often make basic mistakes with conditionals. Moreover, even GPT-4 displays logically inconsistent judgments across inference patterns involving epistemic modals.

{{</citation>}}


### (57/162) Planning, Creation, Usage: Benchmarking LLMs for Comprehensive Tool Utilization in Real-World Complex Scenarios (Shijue Huang et al., 2024)

{{<citation>}}

Shijue Huang, Wanjun Zhong, Jianqiao Lu, Qi Zhu, Jiahui Gao, Weiwen Liu, Yutai Hou, Xingshan Zeng, Yasheng Wang, Lifeng Shang, Xin Jiang, Ruifeng Xu, Qun Liu. (2024)  
**Planning, Creation, Usage: Benchmarking LLMs for Comprehensive Tool Utilization in Real-World Complex Scenarios**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17167v1)  

---


**ABSTRACT**  
The recent trend of using Large Language Models (LLMs) as intelligent agents in real-world applications underscores the necessity for comprehensive evaluations of their capabilities, particularly in complex scenarios involving planning, creating, and using tools. However, existing benchmarks typically focus on simple synthesized queries that do not reflect real-world complexity, thereby offering limited perspectives in evaluating tool utilization. To address this issue, we present UltraTool, a novel benchmark designed to improve and evaluate LLMs' ability in tool utilization within real-world scenarios. UltraTool focuses on the entire process of using tools - from planning and creating to applying them in complex tasks. It emphasizes real-world complexities, demanding accurate, multi-step planning for effective problem-solving. A key feature of UltraTool is its independent evaluation of planning with natural language, which happens before tool usage and simplifies the task solving by mapping out the intermediate steps. Thus, unlike previous work, it eliminates the restriction of pre-defined toolset during planning. Through extensive experiments on various LLMs, we offer novel insights into the evaluation of capabilities of LLMs in tool utilization, thereby contributing a fresh perspective to this rapidly evolving field. The benchmark is publicly available at https://github.com/JoeYing1019/UltraTool.

{{</citation>}}


### (58/162) MT-Ranker: Reference-free machine translation evaluation by inter-system ranking (Ibraheem Muhammad Moosa et al., 2024)

{{<citation>}}

Ibraheem Muhammad Moosa, Rui Zhang, Wenpeng Yin. (2024)  
**MT-Ranker: Reference-free machine translation evaluation by inter-system ranking**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs.CL  
Keywords: Machine Translation  
[Paper Link](http://arxiv.org/abs/2401.17099v1)  

---


**ABSTRACT**  
Traditionally, Machine Translation (MT) Evaluation has been treated as a regression problem -- producing an absolute translation-quality score. This approach has two limitations: i) the scores lack interpretability, and human annotators struggle with giving consistent scores; ii) most scoring methods are based on (reference, translation) pairs, limiting their applicability in real-world scenarios where references are absent. In practice, we often care about whether a new MT system is better or worse than some competitors. In addition, reference-free MT evaluation is increasingly practical and necessary. Unfortunately, these two practical considerations have yet to be jointly explored. In this work, we formulate the reference-free MT evaluation into a pairwise ranking problem. Given the source sentence and a pair of translations, our system predicts which translation is better. In addition to proposing this new formulation, we further show that this new paradigm can demonstrate superior correlation with human judgments by merely using indirect supervision from natural language inference and weak supervision from our synthetic data. In the context of reference-free evaluation, MT-Ranker, trained without any human annotations, achieves state-of-the-art results on the WMT Shared Metrics Task benchmarks DARR20, MQM20, and MQM21. On a more challenging benchmark, ACES, which contains fine-grained evaluation criteria such as addition, omission, and mistranslation errors, MT-Ranker marks state-of-the-art against reference-free as well as reference-based baselines.

{{</citation>}}


### (59/162) SemScore: Automated Evaluation of Instruction-Tuned LLMs based on Semantic Textual Similarity (Ansar Aynetdinov et al., 2024)

{{<citation>}}

Ansar Aynetdinov, Alan Akbik. (2024)  
**SemScore: Automated Evaluation of Instruction-Tuned LLMs based on Semantic Textual Similarity**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model, Textual Similarity  
[Paper Link](http://arxiv.org/abs/2401.17072v2)  

---


**ABSTRACT**  
Instruction-tuned Large Language Models (LLMs) have recently showcased remarkable advancements in their ability to generate fitting responses to natural language instructions. However, many current works rely on manual evaluation to judge the quality of generated responses. Since such manual evaluation is time-consuming, it does not easily scale to the evaluation of multiple models and model variants. In this short paper, we propose a straightforward but remarkably effective evaluation metric called SemScore, in which we directly compare model outputs to gold target responses using semantic textual similarity (STS). We conduct a comparative evaluation of the model outputs of 12 prominent instruction-tuned LLMs using 8 widely-used evaluation metrics for text generation. We find that our proposed SemScore metric outperforms all other, in many cases more complex, evaluation metrics in terms of correlation to human evaluation. These findings indicate the utility of our proposed metric for the evaluation of instruction-tuned LLMs.

{{</citation>}}


### (60/162) CRUD-RAG: A Comprehensive Chinese Benchmark for Retrieval-Augmented Generation of Large Language Models (Yuanjie Lyu et al., 2024)

{{<citation>}}

Yuanjie Lyu, Zhiyu Li, Simin Niu, Feiyu Xiong, Bo Tang, Wenjin Wang, Hao Wu, Huanyong Liu, Tong Xu, Enhong Chen. (2024)  
**CRUD-RAG: A Comprehensive Chinese Benchmark for Retrieval-Augmented Generation of Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17043v1)  

---


**ABSTRACT**  
Retrieval-Augmented Generation (RAG) is a technique that enhances the capabilities of large language models (LLMs) by incorporating external knowledge sources. This method addresses common LLM limitations, including outdated information and the tendency to produce inaccurate "hallucinated" content. However, the evaluation of RAG systems is challenging, as existing benchmarks are limited in scope and diversity. Most of the current benchmarks predominantly assess question-answering applications, overlooking the broader spectrum of situations where RAG could prove advantageous. Moreover, they only evaluate the performance of the LLM component of the RAG pipeline in the experiments, and neglect the influence of the retrieval component and the external knowledge database. To address these issues, this paper constructs a large-scale and more comprehensive benchmark, and evaluates all the components of RAG systems in various RAG application scenarios. Specifically, we have categorized the range of RAG applications into four distinct types-Create, Read, Update, and Delete (CRUD), each representing a unique use case. "Create" refers to scenarios requiring the generation of original, varied content. "Read" involves responding to intricate questions in knowledge-intensive situations. "Update" focuses on revising and rectifying inaccuracies or inconsistencies in pre-existing texts. "Delete" pertains to the task of summarizing extensive texts into more concise forms. For each of these CRUD categories, we have developed comprehensive datasets to evaluate the performance of RAG systems. We also analyze the effects of various components of the RAG system, such as the retriever, the context length, the knowledge base construction, and the LLM. Finally, we provide useful insights for optimizing the RAG technology for different scenarios.

{{</citation>}}


### (61/162) Taking Action Towards Graceful Interaction: The Effects of Performing Actions on Modelling Policies for Instruction Clarification Requests (Brielen Madureira et al., 2024)

{{<citation>}}

Brielen Madureira, David Schlangen. (2024)  
**Taking Action Towards Graceful Interaction: The Effects of Performing Actions on Modelling Policies for Instruction Clarification Requests**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2401.17039v1)  

---


**ABSTRACT**  
Clarification requests are a mechanism to help solve communication problems, e.g. due to ambiguity or underspecification, in instruction-following interactions. Despite their importance, even skilful models struggle with producing or interpreting such repair acts. In this work, we test three hypotheses concerning the effects of action taking as an auxiliary task in modelling iCR policies. Contrary to initial expectations, we conclude that its contribution to learning an iCR policy is limited, but some information can still be extracted from prediction uncertainty. We present further evidence that even well-motivated, Transformer-based models fail to learn good policies for when to ask Instruction CRs (iCRs), while the task of determining what to ask about can be more successfully modelled. Considering the implications of these findings, we further discuss the shortcomings of the data-driven paradigm for learning meta-communication acts.

{{</citation>}}


### (62/162) Distinguishing Fictional Voices: a Study of Authorship Verification Models for Quotation Attribution (Gaspard Michel et al., 2024)

{{<citation>}}

Gaspard Michel, Elena V. Epure, Romain Hennequin, Christophe Cerisara. (2024)  
**Distinguishing Fictional Voices: a Study of Authorship Verification Models for Quotation Attribution**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog  
[Paper Link](http://arxiv.org/abs/2401.16968v1)  

---


**ABSTRACT**  
Recent approaches to automatically detect the speaker of an utterance of direct speech often disregard general information about characters in favor of local information found in the context, such as surrounding mentions of entities. In this work, we explore stylistic representations of characters built by encoding their quotes with off-the-shelf pretrained Authorship Verification models in a large corpus of English novels (the Project Dialogism Novel Corpus). Results suggest that the combination of stylistic and topical information captured in some of these models accurately distinguish characters among each other, but does not necessarily improve over semantic-only models when attributing quotes. However, these results vary across novels and more investigation of stylometric models particularly tailored for literary texts and the study of characters should be conducted.

{{</citation>}}


### (63/162) Two Heads Are Better Than One: Integrating Knowledge from Knowledge Graphs and Large Language Models for Entity Alignment (Linyao Yang et al., 2024)

{{<citation>}}

Linyao Yang, Hongyang Chen, Xiao Wang, Jing Yang, Fei-Yue Wang, Han Liu. (2024)  
**Two Heads Are Better Than One: Integrating Knowledge from Knowledge Graphs and Large Language Models for Entity Alignment**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Entity Alignment, Knowledge Graph, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16960v1)  

---


**ABSTRACT**  
Entity alignment, which is a prerequisite for creating a more comprehensive Knowledge Graph (KG), involves pinpointing equivalent entities across disparate KGs. Contemporary methods for entity alignment have predominantly utilized knowledge embedding models to procure entity embeddings that encapsulate various similarities-structural, relational, and attributive. These embeddings are then integrated through attention-based information fusion mechanisms. Despite this progress, effectively harnessing multifaceted information remains challenging due to inherent heterogeneity. Moreover, while Large Language Models (LLMs) have exhibited exceptional performance across diverse downstream tasks by implicitly capturing entity semantics, this implicit knowledge has yet to be exploited for entity alignment. In this study, we propose a Large Language Model-enhanced Entity Alignment framework (LLMEA), integrating structural knowledge from KGs with semantic knowledge from LLMs to enhance entity alignment. Specifically, LLMEA identifies candidate alignments for a given entity by considering both embedding similarities between entities across KGs and edit distances to a virtual equivalent entity. It then engages an LLM iteratively, posing multiple multi-choice questions to draw upon the LLM's inference capability. The final prediction of the equivalent entity is derived from the LLM's output. Experiments conducted on three public datasets reveal that LLMEA surpasses leading baseline models. Additional ablation studies underscore the efficacy of our proposed framework.

{{</citation>}}


### (64/162) Cross-Lingual Transfer from Related Languages: Treating Low-Resource Maltese as Multilingual Code-Switching (Kurt Micallef et al., 2024)

{{<citation>}}

Kurt Micallef, Nizar Habash, Claudia Borg, Fadhl Eryani, Houda Bouamor. (2024)  
**Cross-Lingual Transfer from Related Languages: Treating Low-Resource Maltese as Multilingual Code-Switching**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Low-Resource, Multilingual  
[Paper Link](http://arxiv.org/abs/2401.16895v2)  

---


**ABSTRACT**  
Although multilingual language models exhibit impressive cross-lingual transfer capabilities on unseen languages, the performance on downstream tasks is impacted when there is a script disparity with the languages used in the multilingual model's pre-training data. Using transliteration offers a straightforward yet effective means to align the script of a resource-rich language with a target language, thereby enhancing cross-lingual transfer capabilities. However, for mixed languages, this approach is suboptimal, since only a subset of the language benefits from the cross-lingual transfer while the remainder is impeded. In this work, we focus on Maltese, a Semitic language, with substantial influences from Arabic, Italian, and English, and notably written in Latin script. We present a novel dataset annotated with word-level etymology. We use this dataset to train a classifier that enables us to make informed decisions regarding the appropriate processing of each token in the Maltese language. We contrast indiscriminate transliteration or translation to mixing processing pipelines that only transliterate words of Arabic origin, thereby resulting in text with a mixture of scripts. We fine-tune the processed data on four downstream tasks and show that conditional transliteration based on word etymology yields the best results, surpassing fine-tuning with raw Maltese or Maltese processed with non-selective pipelines.

{{</citation>}}


### (65/162) State Value Generation with Prompt Learning and Self-Training for Low-Resource Dialogue State Tracking (Ming Gu et al., 2024)

{{<citation>}}

Ming Gu, Yan Yang, Chengcai Chen, Zhou Yu. (2024)  
**State Value Generation with Prompt Learning and Self-Training for Low-Resource Dialogue State Tracking**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue, Low-Resource  
[Paper Link](http://arxiv.org/abs/2401.16862v1)  

---


**ABSTRACT**  
Recently, low-resource dialogue state tracking (DST) has received increasing attention. First obtaining state values then based on values to generate slot types has made great progress in this task. However, obtaining state values is still an under-studied problem. Existing extraction-based approaches cannot capture values that require the understanding of context and are not generalizable either. To address these issues, we propose a novel State VAlue Generation based framework (SVAG), decomposing DST into state value generation and domain slot generation. Specifically, we propose to generate state values and use self-training to further improve state value generation. Moreover, we design an estimator aiming at detecting incomplete generation and incorrect generation for pseudo-labeled data selection during self-training. Experimental results on the MultiWOZ 2.1 dataset show that our method which has only less than 1 billion parameters achieves state-of-the-art performance under the data ratio settings of 5%, 10%, and 25% when limited to models under 100 billion parameters. Compared to models with more than 100 billion parameters, SVAG still reaches competitive results.

{{</citation>}}


### (66/162) Performance Assessment of ChatGPT vs Bard in Detecting Alzheimer's Dementia (Balamurali B T et al., 2024)

{{<citation>}}

Balamurali B T, Jer-Ming Chen. (2024)  
**Performance Assessment of ChatGPT vs Bard in Detecting Alzheimer's Dementia**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, GPT-3.5, GPT-4  
[Paper Link](http://arxiv.org/abs/2402.01751v1)  

---


**ABSTRACT**  
Large language models (LLMs) find increasing applications in many fields. Here, three LLM chatbots (ChatGPT-3.5, ChatGPT-4 and Bard) are assessed - in their current form, as publicly available - for their ability to recognize Alzheimer's Dementia (AD) and Cognitively Normal (CN) individuals using textual input derived from spontaneous speech recordings. Zero-shot learning approach is used at two levels of independent queries, with the second query (chain-of-thought prompting) eliciting more detailed than the first. Each LLM chatbot's performance is evaluated on the prediction generated in terms of accuracy, sensitivity, specificity, precision and F1 score. LLM chatbots generated three-class outcome ("AD", "CN", or "Unsure"). When positively identifying AD, Bard produced highest true-positives (89% recall) and highest F1 score (71%), but tended to misidentify CN as AD, with high confidence (low "Unsure" rates); for positively identifying CN, GPT-4 resulted in the highest true-negatives at 56% and highest F1 score (62%), adopting a diplomatic stance (moderate "Unsure" rates). Overall, three LLM chatbots identify AD vs CN surpassing chance-levels but do not currently satisfy clinical application.

{{</citation>}}


### (67/162) Can Large Language Models be Trusted for Evaluation? Scalable Meta-Evaluation of LLMs as Evaluators via Agent Debate (Steffi Chern et al., 2024)

{{<citation>}}

Steffi Chern, Ethan Chern, Graham Neubig, Pengfei Liu. (2024)  
**Can Large Language Models be Trusted for Evaluation? Scalable Meta-Evaluation of LLMs as Evaluators via Agent Debate**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2401.16788v1)  

---


**ABSTRACT**  
Despite the utility of Large Language Models (LLMs) across a wide range of tasks and scenarios, developing a method for reliably evaluating LLMs across varied contexts continues to be challenging. Modern evaluation approaches often use LLMs to assess responses generated by LLMs. However, the meta-evaluation conducted to assess the effectiveness of these LLMs as evaluators is typically constrained by the coverage of existing benchmarks or requires extensive human annotation. This underscores the urgency of methods for scalable meta-evaluation that can effectively, reliably, and efficiently evaluate the performance of LLMs as evaluators across diverse tasks and scenarios, particularly in potentially new, user-defined scenarios. To fill this gap, we propose ScaleEval, an agent-debate-assisted meta-evaluation framework that leverages the capabilities of multiple communicative LLM agents. This framework supports multi-round discussions to assist human annotators in discerning the most capable LLMs as evaluators, which significantly eases their workload in cases that used to require large-scale annotations during meta-evaluation. We release the code for our framework, which is publicly available at: \url{https://github.com/GAIR-NLP/scaleeval}.

{{</citation>}}


### (68/162) PACE: A Pragmatic Agent for Enhancing Communication Efficiency Using Large Language Models (Jiaxuan Li et al., 2024)

{{<citation>}}

Jiaxuan Li, Minxi Yang, Dahua Gao, Wenlong Xu, Guangming Shi. (2024)  
**PACE: A Pragmatic Agent for Enhancing Communication Efficiency Using Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.01750v1)  

---


**ABSTRACT**  
Current communication technologies face limitations in terms of theoretical capacity, spectrum availability, and power resources. Pragmatic communication, leveraging terminal intelligence for selective data transmission, offers resource conservation. Existing research lacks universal intention resolution tools, limiting applicability to specific tasks. This paper proposes an image pragmatic communication framework based on a Pragmatic Agent for Communication Efficiency (PACE) using Large Language Models (LLM). In this framework, PACE sequentially performs semantic perception, intention resolution, and intention-oriented coding. To ensure the effective utilization of LLM in communication, a knowledge base is designed to supplement the necessary knowledge, dedicated prompts are introduced to facilitate understanding of pragmatic communication scenarios and task requirements, and a chain of thought is designed to assist in making reasonable trade-offs between transmission efficiency and cost. For experimental validation, this paper constructs an image pragmatic communication dataset along with corresponding evaluation standards. Simulation results indicate that the proposed method outperforms traditional and non-LLM-based pragmatic communication in terms of transmission efficiency.

{{</citation>}}


### (69/162) Detecting Racist Text in Bengali: An Ensemble Deep Learning Framework (S. S. Saruar et al., 2024)

{{<citation>}}

S. S. Saruar, Nusrat, Sadia. (2024)  
**Detecting Racist Text in Bengali: An Ensemble Deep Learning Framework**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: BERT, Embedding, LSTM, NLP, Social Media  
[Paper Link](http://arxiv.org/abs/2401.16748v1)  

---


**ABSTRACT**  
Racism is an alarming phenomenon in our country as well as all over the world. Every day we have come across some racist comments in our daily life and virtual life. Though we can eradicate this racism from virtual life (such as Social Media). In this paper, we have tried to detect those racist comments with NLP and deep learning techniques. We have built a novel dataset in the Bengali Language. Further, we annotated the dataset and conducted data label validation. After extensive utilization of deep learning methodologies, we have successfully achieved text detection with an impressive accuracy rate of 87.94\% using the Ensemble approach. We have applied RNN and LSTM models using BERT Embeddings. However, the MCNN-LSTM model performed highest among all those models. Lastly, the Ensemble approach has been followed to combine all the model results to increase overall performance.

{{</citation>}}


### (70/162) MT-Eval: A Multi-Turn Capabilities Evaluation Benchmark for Large Language Models (Wai-Chung Kwan et al., 2024)

{{<citation>}}

Wai-Chung Kwan, Xingshan Zeng, Yuxin Jiang, Yufei Wang, Liangyou Li, Lifeng Shang, Xin Jiang, Qun Liu, Kam-Fai Wong. (2024)  
**MT-Eval: A Multi-Turn Capabilities Evaluation Benchmark for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-3.5, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16745v1)  

---


**ABSTRACT**  
Large language models (LLMs) are increasingly relied upon for complex multi-turn conversations across diverse real-world applications. However, existing benchmarks predominantly focus on single-turn evaluations, overlooking the models' capabilities in multi-turn interactions. To address this gap, we introduce MT-Eval, a comprehensive benchmark designed to evaluate multi-turn conversational abilities. By analyzing human-LLM conversations, we categorize interaction patterns into four types: recollection, expansion, refinement, and follow-up. We construct multi-turn queries for each category either by augmenting existing datasets or by creating new examples with GPT-4 to avoid data leakage. To study the factors impacting multi-turn abilities, we create single-turn versions of the 1170 multi-turn queries and compare performance. Our evaluation of 11 well-known LLMs shows that while closed-source models generally surpass open-source ones, certain open-source models exceed GPT-3.5-Turbo in specific tasks. We observe significant performance degradation in multi-turn settings compared to single-turn settings in most models, which is not correlated with the models' fundamental capabilities. Moreover, we identify the distance to relevant content and susceptibility to error propagation as the key factors influencing multi-turn performance. MT-Eval is released publicly to encourage future research towards more robust conversational models.

{{</citation>}}


### (71/162) Engineering A Large Language Model From Scratch (Abiodun Finbarrs Oketunji, 2024)

{{<citation>}}

Abiodun Finbarrs Oketunji. (2024)  
**Engineering A Large Language Model From Scratch**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs-CY, cs-LG, cs-SE, cs.CL  
Keywords: Language Model, NLP, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16736v3)  

---


**ABSTRACT**  
The proliferation of deep learning in natural language processing (NLP) has led to the development and release of innovative technologies capable of understanding and generating human language with remarkable proficiency. Atinuke, a Transformer-based neural network, optimises performance across various language tasks by utilising a unique configuration. The architecture interweaves layers for processing sequential data with attention mechanisms to draw meaningful affinities between inputs and outputs. Due to the configuration of its topology and hyperparameter tuning, it can emulate human-like language by extracting features and learning complex mappings. Atinuke is modular, extensible, and integrates seamlessly with existing machine learning pipelines. Advanced matrix operations like softmax, embeddings, and multi-head attention enable nuanced handling of textual, acoustic, and visual signals. By unifying modern deep learning techniques with software design principles and mathematical theory, the system achieves state-of-the-art results on natural language tasks whilst remaining interpretable and robust.

{{</citation>}}


### (72/162) Towards Generating Informative Textual Description for Neurons in Language Models (Shrayani Mondal et al., 2024)

{{<citation>}}

Shrayani Mondal, Rishabh Garodia, Arbaaz Qureshi, Taesung Lee, Youngja Park. (2024)  
**Towards Generating Informative Textual Description for Neurons in Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BERT, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16731v1)  

---


**ABSTRACT**  
Recent developments in transformer-based language models have allowed them to capture a wide variety of world knowledge that can be adapted to downstream tasks with limited resources. However, what pieces of information are understood in these models is unclear, and neuron-level contributions in identifying them are largely unknown. Conventional approaches in neuron explainability either depend on a finite set of pre-defined descriptors or require manual annotations for training a secondary model that can then explain the neurons of the primary model. In this paper, we take BERT as an example and we try to remove these constraints and propose a novel and scalable framework that ties textual descriptions to neurons. We leverage the potential of generative language models to discover human-interpretable descriptors present in a dataset and use an unsupervised approach to explain neurons with these descriptors. Through various qualitative and quantitative analyses, we demonstrate the effectiveness of this framework in generating useful data-specific descriptors with little human involvement in identifying the neurons that encode these descriptors. In particular, our experiment shows that the proposed approach achieves 75% precision@2, and 50% recall@2

{{</citation>}}


### (73/162) Security and Privacy Challenges of Large Language Models: A Survey (Badhan Chandra Das et al., 2024)

{{<citation>}}

Badhan Chandra Das, M. Hadi Amini, Yanzhao Wu. (2024)  
**Security and Privacy Challenges of Large Language Models: A Survey**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-CR, cs.CL  
Keywords: Language Model, Security  
[Paper Link](http://arxiv.org/abs/2402.00888v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated extraordinary capabilities and contributed to multiple fields, such as generating and summarizing text, language translation, and question-answering. Nowadays, LLM is becoming a very popular tool in computerized language processing tasks, with the capability to analyze complicated linguistic patterns and provide relevant and appropriate responses depending on the context. While offering significant advantages, these models are also vulnerable to security and privacy attacks, such as jailbreaking attacks, data poisoning attacks, and Personally Identifiable Information (PII) leakage attacks. This survey provides a thorough review of the security and privacy challenges of LLMs for both training data and users, along with the application-based risks in various domains, such as transportation, education, and healthcare. We assess the extent of LLM vulnerabilities, investigate emerging security and privacy attacks for LLMs, and review the potential defense mechanisms. Additionally, the survey outlines existing research gaps in this domain and highlights future research directions.

{{</citation>}}


### (74/162) Recent Advances in Hate Speech Moderation: Multimodality and the Role of Large Models (Ming Shan Hee et al., 2024)

{{<citation>}}

Ming Shan Hee, Shivam Sharma, Rui Cao, Palash Nandi, Tanmoy Chakraborty, Roy Ka-Wei Lee. (2024)  
**Recent Advances in Hate Speech Moderation: Multimodality and the Role of Large Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16727v2)  

---


**ABSTRACT**  
In the evolving landscape of online communication, moderating hate speech (HS) presents an intricate challenge, compounded by the multimodal nature of digital content. This comprehensive survey delves into the recent strides in HS moderation, spotlighting the burgeoning role of large language models (LLMs) and large multimodal models (LMMs). Our exploration begins with a thorough analysis of current literature, revealing the nuanced interplay between textual, visual, and auditory elements in propagating HS. We uncover a notable trend towards integrating these modalities, primarily due to the complexity and subtlety with which HS is disseminated. A significant emphasis is placed on the advances facilitated by LLMs and LMMs, which have begun to redefine the boundaries of detection and moderation capabilities. We identify existing gaps in research, particularly in the context of underrepresented languages and cultures, and the need for solutions to handle low-resource settings. The survey concludes with a forward-looking perspective, outlining potential avenues for future research, including the exploration of novel AI methodologies, the ethical governance of AI in moderation, and the development of more nuanced, context-aware systems. This comprehensive overview aims to catalyze further research and foster a collaborative effort towards more sophisticated, responsible, and human-centric approaches to HS moderation in the digital era. WARNING: This paper contains offensive examples.

{{</citation>}}


### (75/162) The Detection and Understanding of Fictional Discourse (Andrew Piper et al., 2024)

{{<citation>}}

Andrew Piper, Haiqi Zhou. (2024)  
**The Detection and Understanding of Fictional Discourse**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: GPT  
[Paper Link](http://arxiv.org/abs/2401.16678v1)  

---


**ABSTRACT**  
In this paper, we present a variety of classification experiments related to the task of fictional discourse detection. We utilize a diverse array of datasets, including contemporary professionally published fiction, historical fiction from the Hathi Trust, fanfiction, stories from Reddit, folk tales, GPT-generated stories, and anglophone world literature. Additionally, we introduce a new feature set of word "supersenses" that facilitate the goal of semantic generalization. The detection of fictional discourse can help enrich our knowledge of large cultural heritage archives and assist with the process of understanding the distinctive qualities of fictional storytelling more broadly.

{{</citation>}}


### (76/162) OWSM v3.1: Better and Faster Open Whisper-Style Speech Models based on E-Branchformer (Yifan Peng et al., 2024)

{{<citation>}}

Yifan Peng, Jinchuan Tian, William Chen, Siddhant Arora, Brian Yan, Yui Sudo, Muhammad Shakeel, Kwanghee Choi, Jiatong Shi, Xuankai Chang, Jee-weon Jung, Shinji Watanabe. (2024)  
**OWSM v3.1: Better and Faster Open Whisper-Style Speech Models based on E-Branchformer**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL, eess-AS  
Keywords: AI, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16658v1)  

---


**ABSTRACT**  
Recent studies have advocated for fully open foundation models to promote transparency and open science. As an initial step, the Open Whisper-style Speech Model (OWSM) reproduced OpenAI's Whisper using publicly available data and open-source toolkits. With the aim of reproducing Whisper, the previous OWSM v1 through v3 models were still based on Transformer, which might lead to inferior performance compared to other state-of-the-art speech encoders. In this work, we aim to improve the performance and efficiency of OWSM without extra training data. We present E-Branchformer based OWSM v3.1 models at two scales, i.e., 100M and 1B. The 1B model is the largest E-Branchformer based speech model that has been made publicly available. It outperforms the previous OWSM v3 in a vast majority of evaluation benchmarks, while demonstrating up to 25% faster inference speed. We publicly release the data preparation scripts, pre-trained models and training logs.

{{</citation>}}


### (77/162) Gradient-Based Language Model Red Teaming (Nevan Wichers et al., 2024)

{{<citation>}}

Nevan Wichers, Carson Denison, Ahmad Beirami. (2024)  
**Gradient-Based Language Model Red Teaming**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.16656v1)  

---


**ABSTRACT**  
Red teaming is a common strategy for identifying weaknesses in generative language models (LMs), where adversarial prompts are produced that trigger an LM to generate unsafe responses. Red teaming is instrumental for both model alignment and evaluation, but is labor-intensive and difficult to scale when done by humans. In this paper, we present Gradient-Based Red Teaming (GBRT), a red teaming method for automatically generating diverse prompts that are likely to cause an LM to output unsafe responses. GBRT is a form of prompt learning, trained by scoring an LM response with a safety classifier and then backpropagating through the frozen safety classifier and LM to update the prompt. To improve the coherence of input prompts, we introduce two variants that add a realism loss and fine-tune a pretrained model to generate the prompts instead of learning the prompts directly. Our experiments show that GBRT is more effective at finding prompts that trigger an LM to generate unsafe responses than a strong reinforcement learning-based red teaming approach, and succeeds even when the LM has been fine-tuned to produce safer outputs.

{{</citation>}}


### (78/162) Incoherent Probability Judgments in Large Language Models (Jian-Qiao Zhu et al., 2024)

{{<citation>}}

Jian-Qiao Zhu, Thomas L. Griffiths. (2024)  
**Incoherent Probability Judgments in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.16646v1)  

---


**ABSTRACT**  
Autoregressive Large Language Models (LLMs) trained for next-word prediction have demonstrated remarkable proficiency at producing coherent text. But are they equally adept at forming coherent probability judgments? We use probabilistic identities and repeated judgments to assess the coherence of probability judgments made by LLMs. Our results show that the judgments produced by these models are often incoherent, displaying human-like systematic deviations from the rules of probability theory. Moreover, when prompted to judge the same event, the mean-variance relationship of probability judgments produced by LLMs shows an inverted-U-shaped like that seen in humans. We propose that these deviations from rationality can be explained by linking autoregressive LLMs to implicit Bayesian inference and drawing parallels with the Bayesian Sampler model of human probability judgments.

{{</citation>}}


### (79/162) Breaking Free Transformer Models: Task-specific Context Attribution Promises Improved Generalizability Without Fine-tuning Pre-trained LLMs (Stepan Tytarenko et al., 2024)

{{<citation>}}

Stepan Tytarenko, Mohammad Ruhul Amin. (2024)  
**Breaking Free Transformer Models: Task-specific Context Attribution Promises Improved Generalizability Without Fine-tuning Pre-trained LLMs**  

---
Primary Category: cs.CL  
Categories: I-2-7; I-2-4, cs-AI, cs-CL, cs.CL  
Keywords: BERT, NLP, Natural Language Processing, Social Media, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16638v1)  

---


**ABSTRACT**  
Fine-tuning large pre-trained language models (LLMs) on particular datasets is a commonly employed strategy in Natural Language Processing (NLP) classification tasks. However, this approach usually results in a loss of models generalizability. In this paper, we present a framework that allows for maintaining generalizability, and enhances the performance on the downstream task by utilizing task-specific context attribution. We show that a linear transformation of the text representation from any transformer model using the task-specific concept operator results in a projection onto the latent concept space, referred to as context attribution in this paper. The specific concept operator is optimized during the supervised learning stage via novel loss functions. The proposed framework demonstrates that context attribution of the text representation for each task objective can improve the capacity of the discriminator function and thus achieve better performance for the classification task. Experimental results on three datasets, namely HateXplain, IMDB reviews, and Social Media Attributions, illustrate that the proposed model attains superior accuracy and generalizability. Specifically, for the non-fine-tuned BERT on the HateXplain dataset, we observe 8% improvement in accuracy and 10% improvement in F1-score. Whereas for the IMDB dataset, fine-tuned state-of-the-art XLNet is outperformed by 1% for both accuracy and F1-score. Furthermore, in an out-of-domain cross-dataset test, DistilBERT fine-tuned on the IMDB dataset in conjunction with the proposed model improves the F1-score on the HateXplain dataset by 7%. For the Social Media Attributions dataset of YouTube comments, we observe 5.2% increase in F1-metric. The proposed framework is implemented with PyTorch and provided open-source on GitHub.

{{</citation>}}


## cs.CV (17)



### (80/162) Towards Visual Syntactical Understanding (Sayeed Shafayet Chowdhury et al., 2024)

{{<citation>}}

Sayeed Shafayet Chowdhury, Soumyadeep Chandra, Kaushik Roy. (2024)  
**Towards Visual Syntactical Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: BERT, ImageNet  
[Paper Link](http://arxiv.org/abs/2401.17497v1)  

---


**ABSTRACT**  
Syntax is usually studied in the realm of linguistics and refers to the arrangement of words in a sentence. Similarly, an image can be considered as a visual 'sentence', with the semantic parts of the image acting as 'words'. While visual syntactic understanding occurs naturally to humans, it is interesting to explore whether deep neural networks (DNNs) are equipped with such reasoning. To that end, we alter the syntax of natural images (e.g. swapping the eye and nose of a face), referred to as 'incorrect' images, to investigate the sensitivity of DNNs to such syntactic anomaly. Through our experiments, we discover an intriguing property of DNNs where we observe that state-of-the-art convolutional neural networks, as well as vision transformers, fail to discriminate between syntactically correct and incorrect images when trained on only correct ones. To counter this issue and enable visual syntactic understanding with DNNs, we propose a three-stage framework- (i) the 'words' (or the sub-features) in the image are detected, (ii) the detected words are sequentially masked and reconstructed using an autoencoder, (iii) the original and reconstructed parts are compared at each location to determine syntactic correctness. The reconstruction module is trained with BERT-like masked autoencoding for images, with the motivation to leverage language model inspired training to better capture the syntax. Note, our proposed approach is unsupervised in the sense that the incorrect images are only used during testing and the correct versus incorrect labels are never used for training. We perform experiments on CelebA, and AFHQ datasets and obtain classification accuracy of 92.10%, and 90.89%, respectively. Notably, the approach generalizes well to ImageNet samples which share common classes with CelebA and AFHQ without explicitly training on them.

{{</citation>}}


### (81/162) YOLO-World: Real-Time Open-Vocabulary Object Detection (Tianheng Cheng et al., 2024)

{{<citation>}}

Tianheng Cheng, Lin Song, Yixiao Ge, Wenyu Liu, Xinggang Wang, Ying Shan. (2024)  
**YOLO-World: Real-Time Open-Vocabulary Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2401.17270v2)  

---


**ABSTRACT**  
The You Only Look Once (YOLO) series of detectors have established themselves as efficient and practical tools. However, their reliance on predefined and trained object categories limits their applicability in open scenarios. Addressing this limitation, we introduce YOLO-World, an innovative approach that enhances YOLO with open-vocabulary detection capabilities through vision-language modeling and pre-training on large-scale datasets. Specifically, we propose a new Re-parameterizable Vision-Language Path Aggregation Network (RepVL-PAN) and region-text contrastive loss to facilitate the interaction between visual and linguistic information. Our method excels in detecting a wide range of objects in a zero-shot manner with high efficiency. On the challenging LVIS dataset, YOLO-World achieves 35.4 AP with 52.0 FPS on V100, which outperforms many state-of-the-art methods in terms of both accuracy and speed. Furthermore, the fine-tuned YOLO-World achieves remarkable performance on several downstream tasks, including object detection and open-vocabulary instance segmentation.

{{</citation>}}


### (82/162) MouSi: Poly-Visual-Expert Vision-Language Models (Xiaoran Fan et al., 2024)

{{<citation>}}

Xiaoran Fan, Tao Ji, Changhao Jiang, Shuo Li, Senjie Jin, Sirui Song, Junke Wang, Boyang Hong, Lu Chen, Guodong Zheng, Ming Zhang, Caishuang Huang, Rui Zheng, Zhiheng Xi, Yuhao Zhou, Shihan Dou, Junjie Ye, Hang Yan, Tao Gui, Qi Zhang, Xipeng Qiu, Xuanjing Huang, Zuxuan Wu, Yu-Gang Jiang. (2024)  
**MouSi: Poly-Visual-Expert Vision-Language Models**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: Language Model, OCR  
[Paper Link](http://arxiv.org/abs/2401.17221v1)  

---


**ABSTRACT**  
Current large vision-language models (VLMs) often encounter challenges such as insufficient capabilities of a single visual component and excessively long visual tokens. These issues can limit the model's effectiveness in accurately interpreting complex visual information and over-lengthy contextual information. Addressing these challenges is crucial for enhancing the performance and applicability of VLMs. This paper proposes the use of ensemble experts technique to synergizes the capabilities of individual visual encoders, including those skilled in image-text matching, OCR, image segmentation, etc. This technique introduces a fusion network to unify the processing of outputs from different visual experts, while bridging the gap between image encoders and pre-trained LLMs. In addition, we explore different positional encoding schemes to alleviate the waste of positional encoding caused by lengthy image feature sequences, effectively addressing the issue of position overflow and length limitations. For instance, in our implementation, this technique significantly reduces the positional occupancy in models like SAM, from a substantial 4096 to a more efficient and manageable 64 or even down to 1. Experimental results demonstrate that VLMs with multiple experts exhibit consistently superior performance over isolated visual encoders and mark a significant performance boost as more experts are integrated. We have open-sourced the training code used in this report. All of these resources can be found on our project website.

{{</citation>}}


### (83/162) Self-Supervised Representation Learning for Nerve Fiber Distribution Patterns in 3D-PLI (Alexander Oberstrass et al., 2024)

{{<citation>}}

Alexander Oberstrass, Sascha E. A. Muenzing, Meiqi Niu, Nicola Palomero-Gallagher, Christian Schiffer, Markus Axer, Katrin Amunts, Timo Dickscheid. (2024)  
**Self-Supervised Representation Learning for Nerve Fiber Distribution Patterns in 3D-PLI**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning, Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2401.17207v1)  

---


**ABSTRACT**  
A comprehensive understanding of the organizational principles in the human brain requires, among other factors, well-quantifiable descriptors of nerve fiber architecture. Three-dimensional polarized light imaging (3D-PLI) is a microscopic imaging technique that enables insights into the fine-grained organization of myelinated nerve fibers with high resolution. Descriptors characterizing the fiber architecture observed in 3D-PLI would enable downstream analysis tasks such as multimodal correlation studies, clustering, and mapping. However, best practices for observer-independent characterization of fiber architecture in 3D-PLI are not yet available. To this end, we propose the application of a fully data-driven approach to characterize nerve fiber architecture in 3D-PLI images using self-supervised representation learning. We introduce a 3D-Context Contrastive Learning (CL-3D) objective that utilizes the spatial neighborhood of texture examples across histological brain sections of a 3D reconstructed volume to sample positive pairs for contrastive learning. We combine this sampling strategy with specifically designed image augmentations to gain robustness to typical variations in 3D-PLI parameter maps. The approach is demonstrated for the 3D reconstructed occipital lobe of a vervet monkey brain. We show that extracted features are highly sensitive to different configurations of nerve fibers, yet robust to variations between consecutive brain sections arising from histological processing. We demonstrate their practical applicability for retrieving clusters of homogeneous fiber architecture and performing data mining for interactively selected templates of specific components of fiber architecture such as U-fibers.

{{</citation>}}


### (84/162) Evaluation in Neural Style Transfer: A Review (Eleftherios Ioannou et al., 2024)

{{<citation>}}

Eleftherios Ioannou, Steve Maddock. (2024)  
**Evaluation in Neural Style Transfer: A Review**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs-NE, cs.CV  
Keywords: Style Transfer  
[Paper Link](http://arxiv.org/abs/2401.17109v1)  

---


**ABSTRACT**  
The field of Neural Style Transfer (NST) has witnessed remarkable progress in the past few years, with approaches being able to synthesize artistic and photorealistic images and videos of exceptional quality. To evaluate such results, a diverse landscape of evaluation methods and metrics is used, including authors' opinions based on side-by-side comparisons, human evaluation studies that quantify the subjective judgements of participants, and a multitude of quantitative computational metrics which objectively assess the different aspects of an algorithm's performance. However, there is no consensus regarding the most suitable and effective evaluation procedure that can guarantee the reliability of the results. In this review, we provide an in-depth analysis of existing evaluation techniques, identify the inconsistencies and limitations of current evaluation methods, and give recommendations for standardized evaluation practices. We believe that the development of a robust evaluation framework will not only enable more meaningful and fairer comparisons among NST methods but will also enhance the comprehension and interpretation of research findings in the field.

{{</citation>}}


### (85/162) OmniSCV: An Omnidirectional Synthetic Image Generator for Computer Vision (Bruno Berenguel-Baeta et al., 2024)

{{<citation>}}

Bruno Berenguel-Baeta, Jesus Bermudez-Cameo, Jose J. Guerrero. (2024)  
**OmniSCV: An Omnidirectional Synthetic Image Generator for Computer Vision**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Computer Vision  
[Paper Link](http://arxiv.org/abs/2401.17061v1)  

---


**ABSTRACT**  
Omnidirectional and 360{\deg} images are becoming widespread in industry and in consumer society, causing omnidirectional computer vision to gain attention. Their wide field of view allows the gathering of a great amount of information about the environment from only an image. However, the distortion of these images requires the development of specific algorithms for their treatment and interpretation. Moreover, a high number of images is essential for the correct training of computer vision algorithms based on learning. In this paper, we present a tool for generating datasets of omnidirectional images with semantic and depth information. These images are synthesized from a set of captures that are acquired in a realistic virtual environment for Unreal Engine 4 through an interface plugin. We gather a variety of well-known projection models such as equirectangular and cylindrical panoramas, different fish-eye lenses, catadioptric systems, and empiric models. Furthermore, we include in our tool photorealistic non-central-projection systems as non-central panoramas and non-central catadioptric systems. As far as we know, this is the first reported tool for generating photorealistic non-central images in the literature. Moreover, since the omnidirectional images are made virtually, we provide pixel-wise information about semantics and depth as well as perfect knowledge of the calibration parameters of the cameras. This allows the creation of ground-truth information with pixel precision for training learning algorithms and testing 3D vision approaches. To validate the proposed tool, different computer vision algorithms are tested as line extractions from dioptric and catadioptric central images, 3D Layout recovery and SLAM using equirectangular panoramas, and 3D reconstruction from non-central panoramas.

{{</citation>}}


### (86/162) YTCommentQA: Video Question Answerability in Instructional Videos (Saelyne Yang et al., 2024)

{{<citation>}}

Saelyne Yang, Sunghyun Park, Yunseok Jang, Moontae Lee. (2024)  
**YTCommentQA: Video Question Answerability in Instructional Videos**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2401.17343v1)  

---


**ABSTRACT**  
Instructional videos provide detailed how-to guides for various tasks, with viewers often posing questions regarding the content. Addressing these questions is vital for comprehending the content, yet receiving immediate answers is difficult. While numerous computational models have been developed for Video Question Answering (Video QA) tasks, they are primarily trained on questions generated based on video content, aiming to produce answers from within the content. However, in real-world situations, users may pose questions that go beyond the video's informational boundaries, highlighting the necessity to determine if a video can provide the answer. Discerning whether a question can be answered by video content is challenging due to the multi-modal nature of videos, where visual and verbal information are intertwined. To bridge this gap, we present the YTCommentQA dataset, which contains naturally-generated questions from YouTube, categorized by their answerability and required modality to answer -- visual, script, or both. Experiments with answerability classification tasks demonstrate the complexity of YTCommentQA and emphasize the need to comprehend the combined role of visual and script information in video reasoning. The dataset is available at https://github.com/lgresearch/YTCommentQA.

{{</citation>}}


### (87/162) Category-wise Fine-Tuning: Resisting Incorrect Pseudo-Labels in Multi-Label Image Classification with Partial Labels (Chak Fong Chong et al., 2024)

{{<citation>}}

Chak Fong Chong, Xinyi Fang, Jielong Guo, Yapeng Wang, Wei Ke, Chan-Tong Lam, Sio-Kei Im. (2024)  
**Category-wise Fine-Tuning: Resisting Incorrect Pseudo-Labels in Multi-Label Image Classification with Partial Labels**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Image Classification  
[Paper Link](http://arxiv.org/abs/2401.16991v1)  

---


**ABSTRACT**  
Large-scale image datasets are often partially labeled, where only a few categories' labels are known for each image. Assigning pseudo-labels to unknown labels to gain additional training signals has become prevalent for training deep classification models. However, some pseudo-labels are inevitably incorrect, leading to a notable decline in the model classification performance. In this paper, we propose a novel method called Category-wise Fine-Tuning (CFT), aiming to reduce model inaccuracies caused by the wrong pseudo-labels. In particular, CFT employs known labels without pseudo-labels to fine-tune the logistic regressions of trained models individually to calibrate each category's model predictions. Genetic Algorithm, seldom used for training deep models, is also utilized in CFT to maximize the classification performance directly. CFT is applied to well-trained models, unlike most existing methods that train models from scratch. Hence, CFT is general and compatible with models trained with different methods and schemes, as demonstrated through extensive experiments. CFT requires only a few seconds for each category for calibration with consumer-grade GPUs. We achieve state-of-the-art results on three benchmarking datasets, including the CheXpert chest X-ray competition dataset (ensemble mAUC 93.33%, single model 91.82%), partially labeled MS-COCO (average mAP 83.69%), and Open Image V3 (mAP 85.31%), outperforming the previous bests by 0.28%, 2.21%, 2.50%, and 0.91%, respectively. The single model on CheXpert has been officially evaluated by the competition server, endorsing the correctness of the result. The outstanding results and generalizability indicate that CFT could be substantial and prevalent for classification model development. Code is available at: https://github.com/maxium0526/category-wise-fine-tuning.

{{</citation>}}


### (88/162) Segmentation and Characterization of Macerated Fibers and Vessels Using Deep Learning (Saqib Qamar et al., 2024)

{{<citation>}}

Saqib Qamar, Abu Imran Baba, Stéphane Verger, Magnus Andersson. (2024)  
**Segmentation and Characterization of Macerated Fibers and Vessels Using Deep Learning**  

---
Primary Category: cs.CV  
Categories: I-5-1, cs-CV, cs-LG, cs.CV  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2401.16937v1)  

---


**ABSTRACT**  
Purpose: Wood comprises different cell types, such as fibers and vessels, defining its properties. Studying their shape, size, and arrangement in microscopic images is crucial for understanding wood samples. Typically, this involves macerating (soaking) samples in a solution to separate cells, then spreading them on slides for imaging with a microscope that covers a wide area, capturing thousands of cells. However, these cells often cluster and overlap in images, making the segmentation difficult and time-consuming using standard image-processing methods. Results: In this work, we develop an automatic deep learning segmentation approach that utilizes the one-stage YOLOv8 model for fast and accurate fiber and vessel segmentation and characterization in microscopy images. The model can analyze 32640 x 25920 pixels images and demonstrate effective cell detection and segmentation, achieving a mAP_0.5-0.95 of 78 %. To assess the model's robustness, we examined fibers from a genetically modified tree line known for longer fibers. The outcomes were comparable to previous manual measurements. Additionally, we created a user-friendly web application for image analysis and provided the code for use on Google Colab. Conclusion: By leveraging YOLOv8's advances, this work provides a deep learning solution to enable efficient quantification and analysis of wood cells suitable for practical applications.

{{</citation>}}


### (89/162) CAFCT: Contextual and Attentional Feature Fusions of Convolutional Neural Networks and Transformer for Liver Tumor Segmentation (Ming Kang et al., 2024)

{{<citation>}}

Ming Kang, Chee-Ming Ting, Fung Fung Ting, Raphaël Phan. (2024)  
**CAFCT: Contextual and Attentional Feature Fusions of Convolutional Neural Networks and Transformer for Liver Tumor Segmentation**  

---
Primary Category: cs.CV  
Categories: 68T07, 68T10, 68U10, 62P10, I-4-6; I-5-1; J-3, cs-CV, cs.CV, eess-SP, stat-AP  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16886v1)  

---


**ABSTRACT**  
Medical image semantic segmentation techniques can help identify tumors automatically from computed tomography (CT) scans. In this paper, we propose a Contextual and Attentional feature Fusions enhanced Convolutional Neural Network (CNN) and Transformer hybrid network (CAFCT) model for liver tumor segmentation. In the proposed model, three other modules are introduced in the network architecture: Attentional Feature Fusion (AFF), Atrous Spatial Pyramid Pooling (ASPP) of DeepLabv3, and Attention Gates (AGs) to improve contextual information related to tumor boundaries for accurate segmentation. Experimental results show that the proposed CAFCT achieves a mean Intersection over Union (IoU) of 90.38% and Dice score of 86.78%, respectively, on the Liver Tumor Segmentation Benchmark (LiTS) dataset, outperforming pure CNN or Transformer methods, e.g., Attention U-Net, and PVTFormer.

{{</citation>}}


### (90/162) EarthGPT: A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain (Wei Zhang et al., 2024)

{{<citation>}}

Wei Zhang, Miaoxin Cai, Tong Zhang, Yin Zhuang, Xuerui Mao. (2024)  
**EarthGPT: A Universal Multi-modal Large Language Model for Multi-sensor Image Comprehension in Remote Sensing Domain**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16822v2)  

---


**ABSTRACT**  
Multi-modal large language models (MLLMs) have demonstrated remarkable success in vision and visual-language tasks within the natural image domain. Owing to the significant diversities between the natural and remote sensing (RS) images, the development of MLLMs in the RS domain is still in the infant stage. To fill the gap, a pioneer MLLM named EarthGPT integrating various multi-sensor RS interpretation tasks uniformly is proposed in this paper for universal RS image comprehension. In EarthGPT, three key techniques are developed including a visual-enhanced perception mechanism, a cross-modal mutual comprehension approach, and a unified instruction tuning method for multi-sensor multi-task in the RS domain. More importantly, a dataset named MMRS-1M featuring large-scale multi-sensor multi-modal RS instruction-following is constructed, comprising over 1M image-text pairs based on 34 existing diverse RS datasets and including multi-sensor images such as optical, synthetic aperture radar (SAR), and infrared. The MMRS-1M dataset addresses the drawback of MLLMs on RS expert knowledge and stimulates the development of MLLMs in the RS domain. Extensive experiments are conducted, demonstrating the EarthGPT's superior performance in various RS visual interpretation tasks compared with the other specialist models and MLLMs, proving the effectiveness of the proposed EarthGPT and offering a versatile paradigm for open-set reasoning tasks.

{{</citation>}}


### (91/162) MuSc: Zero-Shot Industrial Anomaly Classification and Segmentation with Mutual Scoring of the Unlabeled Images (Xurui Li et al., 2024)

{{<citation>}}

Xurui Li, Ziming Huang, Feng Xue, Yu Zhou. (2024)  
**MuSc: Zero-Shot Industrial Anomaly Classification and Segmentation with Mutual Scoring of the Unlabeled Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2401.16753v1)  

---


**ABSTRACT**  
This paper studies zero-shot anomaly classification (AC) and segmentation (AS) in industrial vision. We reveal that the abundant normal and abnormal cues implicit in unlabeled test images can be exploited for anomaly determination, which is ignored by prior methods. Our key observation is that for the industrial product images, the normal image patches could find a relatively large number of similar patches in other unlabeled images, while the abnormal ones only have a few similar patches. We leverage such a discriminative characteristic to design a novel zero-shot AC/AS method by Mutual Scoring (MuSc) of the unlabeled images, which does not need any training or prompts. Specifically, we perform Local Neighborhood Aggregation with Multiple Degrees (LNAMD) to obtain the patch features that are capable of representing anomalies in varying sizes. Then we propose the Mutual Scoring Mechanism (MSM) to leverage the unlabeled test images to assign the anomaly score to each other. Furthermore, we present an optimization approach named Re-scoring with Constrained Image-level Neighborhood (RsCIN) for image-level anomaly classification to suppress the false positives caused by noises in normal images. The superior performance on the challenging MVTec AD and VisA datasets demonstrates the effectiveness of our approach. Compared with the state-of-the-art zero-shot approaches, MuSc achieves a $\textbf{21.1%}$ PRO absolute gain (from 72.7% to 93.8%) on MVTec AD, a $\textbf{19.4%}$ pixel-AP gain and a $\textbf{14.7%}$ pixel-AUROC gain on VisA. In addition, our zero-shot approach outperforms most of the few-shot approaches and is comparable to some one-class methods. Code is available at https://github.com/xrli-U/MuSc.

{{</citation>}}


### (92/162) Optimal-Landmark-Guided Image Blending for Face Morphing Attacks (Qiaoyun He et al., 2024)

{{<citation>}}

Qiaoyun He, Zongyong Deng, Zuyuan He, Qijun Zhao. (2024)  
**Optimal-Landmark-Guided Image Blending for Face Morphing Attacks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2401.16722v1)  

---


**ABSTRACT**  
In this paper, we propose a novel approach for conducting face morphing attacks, which utilizes optimal-landmark-guided image blending. Current face morphing attacks can be categorized into landmark-based and generation-based approaches. Landmark-based methods use geometric transformations to warp facial regions according to averaged landmarks but often produce morphed images with poor visual quality. Generation-based methods, which employ generation models to blend multiple face images, can achieve better visual quality but are often unsuccessful in generating morphed images that can effectively evade state-of-the-art face recognition systems~(FRSs). Our proposed method overcomes the limitations of previous approaches by optimizing the morphing landmarks and using Graph Convolutional Networks (GCNs) to combine landmark and appearance features. We model facial landmarks as nodes in a bipartite graph that is fully connected and utilize GCNs to simulate their spatial and structural relationships. The aim is to capture variations in facial shape and enable accurate manipulation of facial appearance features during the warping process, resulting in morphed facial images that are highly realistic and visually faithful. Experiments on two public datasets prove that our method inherits the advantages of previous landmark-based and generation-based methods and generates morphed images with higher quality, posing a more significant threat to state-of-the-art FRSs.

{{</citation>}}


### (93/162) LF Tracy: A Unified Single-Pipeline Approach for Salient Object Detection in Light Field Cameras (Fei Teng et al., 2024)

{{<citation>}}

Fei Teng, Jiaming Zhang, Jiawei Liu, Kunyu Peng, Xina Cheng, Zhiyong Li, Kailun Yang. (2024)  
**LF Tracy: A Unified Single-Pipeline Approach for Salient Object Detection in Light Field Cameras**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV, eess-IV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2401.16712v1)  

---


**ABSTRACT**  
Leveraging the rich information extracted from light field (LF) cameras is instrumental for dense prediction tasks. However, adapting light field data to enhance Salient Object Detection (SOD) still follows the traditional RGB methods and remains under-explored in the community. Previous approaches predominantly employ a custom two-stream design to discover the implicit angular feature within light field cameras, leading to significant information isolation between different LF representations. In this study, we propose an efficient paradigm (LF Tracy) to address this limitation. We eschew the conventional specialized fusion and decoder architecture for a dual-stream backbone in favor of a unified, single-pipeline approach. This comprises firstly a simple yet effective data augmentation strategy called MixLD to bridge the connection of spatial, depth, and implicit angular information under different LF representations. A highly efficient information aggregation (IA) module is then introduced to boost asymmetric feature-wise information fusion. Owing to this innovative approach, our model surpasses the existing state-of-the-art methods, particularly demonstrating a 23% improvement over previous results on the latest large-scale PKU dataset. By utilizing only 28.9M parameters, the model achieves a 10% increase in accuracy with 3M additional parameters compared to its backbone using RGB images and an 86% rise to its backbone using LF images. The source code will be made publicly available at https://github.com/FeiBryantkit/LF-Tracy.

{{</citation>}}


### (94/162) Multi-granularity Correspondence Learning from Long-term Noisy Videos (Yijie Lin et al., 2024)

{{<citation>}}

Yijie Lin, Jie Zhang, Zhenyu Huang, Jia Liu, Zujie Wen, Xi Peng. (2024)  
**Multi-granularity Correspondence Learning from Long-term Noisy Videos**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2401.16702v1)  

---


**ABSTRACT**  
Existing video-language studies mainly focus on learning short video clips, leaving long-term temporal dependencies rarely explored due to over-high computational cost of modeling long videos. To address this issue, one feasible solution is learning the correspondence between video clips and captions, which however inevitably encounters the multi-granularity noisy correspondence (MNC) problem. To be specific, MNC refers to the clip-caption misalignment (coarse-grained) and frame-word misalignment (fine-grained), hindering temporal learning and video understanding. In this paper, we propose NOise Robust Temporal Optimal traNsport (Norton) that addresses MNC in a unified optimal transport (OT) framework. In brief, Norton employs video-paragraph and clip-caption contrastive losses to capture long-term dependencies based on OT. To address coarse-grained misalignment in video-paragraph contrast, Norton filters out the irrelevant clips and captions through an alignable prompt bucket and realigns asynchronous clip-caption pairs based on transport distance. To address the fine-grained misalignment, Norton incorporates a soft-maximum operator to identify crucial words and key frames. Additionally, Norton exploits the potential faulty negative samples in clip-caption contrast by rectifying the alignment target with OT assignment to ensure precise temporal modeling. Extensive experiments on video retrieval, videoQA, and action segmentation verify the effectiveness of our method. Code is available at https://lin-yijie.github.io/projects/Norton.

{{</citation>}}


### (95/162) Towards Precise 3D Human Pose Estimation with Multi-Perspective Spatial-Temporal Relational Transformers (Jianbin Jiao et al., 2024)

{{<citation>}}

Jianbin Jiao, Xina Cheng, Weijie Chen, Xiaoting Yin, Hao Shi, Kailun Yang. (2024)  
**Towards Precise 3D Human Pose Estimation with Multi-Perspective Spatial-Temporal Relational Transformers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV, eess-IV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.16700v1)  

---


**ABSTRACT**  
3D human pose estimation captures the human joint points in three-dimensional space while keeping the depth information and physical structure. That is essential for applications that require precise pose information, such as human-computer interaction, scene understanding, and rehabilitation training. Due to the challenges in data collection, mainstream datasets of 3D human pose estimation are primarily composed of multi-view video data collected in laboratory environments, which contains rich spatial-temporal correlation information besides the image frame content. Given the remarkable self-attention mechanism of transformers, capable of capturing the spatial-temporal correlation from multi-view video datasets, we propose a multi-stage framework for 3D sequence-to-sequence (seq2seq) human pose detection. Firstly, the spatial module represents the human pose feature by intra-image content, while the frame-image relation module extracts temporal relationships and 3D spatial positional relationship features between the multi-perspective images. Secondly, the self-attention mechanism is adopted to eliminate the interference from non-human body parts and reduce computing resources. Our method is evaluated on Human3.6M, a popular 3D human pose detection dataset. Experimental results demonstrate that our approach achieves state-of-the-art performance on this dataset.

{{</citation>}}


### (96/162) The Why, When, and How to Use Active Learning in Large-Data-Driven 3D Object Detection for Safe Autonomous Driving: An Empirical Exploration (Ross Greer et al., 2024)

{{<citation>}}

Ross Greer, Bjørk Antoniussen, Mathias V. Andersen, Andreas Møgelmose, Mohan M. Trivedi. (2024)  
**The Why, When, and How to Use Active Learning in Large-Data-Driven 3D Object Detection for Safe Autonomous Driving: An Empirical Exploration**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Active Learning, Object Detection  
[Paper Link](http://arxiv.org/abs/2401.16634v1)  

---


**ABSTRACT**  
Active learning strategies for 3D object detection in autonomous driving datasets may help to address challenges of data imbalance, redundancy, and high-dimensional data. We demonstrate the effectiveness of entropy querying to select informative samples, aiming to reduce annotation costs and improve model performance. We experiment using the BEVFusion model for 3D object detection on the nuScenes dataset, comparing active learning to random sampling and demonstrating that entropy querying outperforms in most cases. The method is particularly effective in reducing the performance gap between majority and minority classes. Class-specific analysis reveals efficient allocation of annotated resources for limited data budgets, emphasizing the importance of selecting diverse and informative data for model training. Our findings suggest that entropy querying is a promising strategy for selecting data that enhances model learning in resource-constrained environments.

{{</citation>}}


## math.OC (3)



### (97/162) CLAIRE: Scalable GPU-Accelerated Algorithms for Diffeomorphic Image Registration in 3D (Andreas Mang, 2024)

{{<citation>}}

Andreas Mang. (2024)  
**CLAIRE: Scalable GPU-Accelerated Algorithms for Diffeomorphic Image Registration in 3D**  

---
Primary Category: math.OC  
Categories: 49M15, 49M41, 68W10, 65Y05, cs-DC, math-OC, math.OC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17493v1)  

---


**ABSTRACT**  
We present our work on scalable, GPU-accelerated algorithms for diffeomorphic image registration. The associated software package is termed CLAIRE. Image registration is a non-linear inverse problem. It is about computing a spatial mapping from one image of the same object or scene to another. In diffeomorphic image registration, the set of admissible spatial transformations is restricted to maps that are smooth, one-to-one, and have a smooth inverse. We formulate diffeomorphic image registration as a variational problem governed by transport equations. We use an inexact, globalized (Gauss--)Newton--Krylov method for numerical optimization. We consider semi-Lagrangian methods for numerical time integration. Our solver features mixed-precision, hardware-accelerated computational kernels for optimal computational throughput. We use the message-passing interface for distributed-memory parallelism and deploy our code on modern high-performance computing architectures. Our solver allows us to solve clinically relevant problems in under four seconds on a single GPU. It can also be applied to large-scale 3D imaging applications with data that is discretized on meshes with billions of voxels. We demonstrate that our numerical framework yields high-fidelity results in only a few seconds, even if we search for an optimal regularization parameter.

{{</citation>}}


### (98/162) Low Thrust Trajectory Design Using A Semi-Analytic Approach (Madhusudan Vijayakumar et al., 2024)

{{<citation>}}

Madhusudan Vijayakumar, Ossama Abdelkhalik. (2024)  
**Low Thrust Trajectory Design Using A Semi-Analytic Approach**  

---
Primary Category: math.OC  
Categories: cs-SY, eess-SY, math-OC, math.OC, physics-space-ph  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2401.17257v1)  

---


**ABSTRACT**  
Space missions that use low-thrust propulsion technology are becoming increasingly popular since they utilize propellant more efficiently and thus reduce mission costs. However, optimizing continuous-thrust trajectories is complex, time-consuming, and extremely sensitive to initial guesses. Hence, generating approximate trajectories that can be used as reliable initial guesses in trajectory generators is essential. This paper presents a semi-analytic approach for designing planar and three-dimensional trajectories using Hills equations. The spacecraft is assumed to be acted upon by a constant thrust acceleration magnitude. The proposed equations are employed in a Nonlinear Programming Problem (NLP) solver to obtain the thrust directions. Their applicability is tested for various design scenarios like orbit raising, orbit insertion, and rendezvous. The trajectory solutions are then validated as initial guesses in high-fidelity optimal control tools. The usefulness of this method lies in the preliminary stages of low-thrust mission design, where speed and reliability are key.

{{</citation>}}


### (99/162) Sub-Optimal Fast Fourier Series Approximation for Initial Trajectory Design (Caleb Gunsaulus et al., 2024)

{{<citation>}}

Caleb Gunsaulus, Carl De Vries, William Brown, Youngro Lee, Madhusudan Vijayakumar, Ossama Abdelkhalik. (2024)  
**Sub-Optimal Fast Fourier Series Approximation for Initial Trajectory Design**  

---
Primary Category: math.OC  
Categories: cs-SY, eess-SY, math-OC, math.OC, physics-space-ph  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2401.16963v1)  

---


**ABSTRACT**  
The Finite Fourier Series (FFS) Shape-Based (SB) trajectory approximation method has been used to rapidly generate initial trajectories that satisfy the dynamics, trajectory boundary conditions, and limitation on maximum thrust acceleration. The FFS SB approach solves a nonlinear programming problem (NLP) in searching for feasible trajectories. This paper extends the development of the FFS SB approach to generate sub optimal solutions. Specifically, the objective function of the NLP problem is modified to include also a measure for the time of flight. Numerical results presented in this paper show several solutions that differ from those of the original FFS SB ones. The sub-optimal trajectories generated using a time of flight minimization are shown to be physically feasible trajectories and potential candidates for direct solvers.

{{</citation>}}


## cs.HC (7)



### (100/162) A Scoping Study of Evaluation Practices for Responsible AI Tools: Steps Towards Effectiveness Evaluations (Glen Berman et al., 2024)

{{<citation>}}

Glen Berman, Nitesh Goyal, Michael Madaio. (2024)  
**A Scoping Study of Evaluation Practices for Responsible AI Tools: Steps Towards Effectiveness Evaluations**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17486v1)  

---


**ABSTRACT**  
Responsible design of AI systems is a shared goal across HCI and AI communities. Responsible AI (RAI) tools have been developed to support practitioners to identify, assess, and mitigate ethical issues during AI development. These tools take many forms (e.g., design playbooks, software toolkits, documentation protocols). However, research suggests that use of RAI tools is shaped by organizational contexts, raising questions about how effective such tools are in practice. To better understand how RAI tools are -- and might be -- evaluated, we conducted a qualitative analysis of 37 publications that discuss evaluations of RAI tools. We find that most evaluations focus on usability, while questions of tools' effectiveness in changing AI development are sidelined. While usability evaluations are an important approach to evaluate RAI tools, we draw on evaluation approaches from other fields to highlight developer- and community-level steps to support evaluations of RAI tools' effectiveness in shaping AI development practices and outcomes.

{{</citation>}}


### (101/162) GazeGPT: Augmenting Human Capabilities using Gaze-contingent Contextual AI for Smart Eyewear (Robert Konrad et al., 2024)

{{<citation>}}

Robert Konrad, Nitish Padmanaban, J. Gabriel Buckmaster, Kevin C. Boyle, Gordon Wetzstein. (2024)  
**GazeGPT: Augmenting Human Capabilities using Gaze-contingent Contextual AI for Smart Eyewear**  

---
Primary Category: cs.HC  
Categories: cs-CV, cs-HC, cs.HC  
Keywords: AI, GPT  
[Paper Link](http://arxiv.org/abs/2401.17217v2)  

---


**ABSTRACT**  
Multimodal large language models (LMMs) excel in world knowledge and problem-solving abilities. Through the use of a world-facing camera and contextual AI, emerging smart accessories aim to provide a seamless interface between humans and LMMs. Yet, these wearable computing systems lack an understanding of the user's attention. We introduce GazeGPT as a new user interaction paradigm for contextual AI. GazeGPT uses eye tracking to help the LMM understand which object in the world-facing camera view a user is paying attention to. Using extensive user evaluations, we show that this gaze-contingent mechanism is a faster and more accurate pointing mechanism than alternatives; that it augments human capabilities by significantly improving their accuracy in a dog-breed classification task; and that it is consistently ranked as more natural than head- or body-driven selection mechanisms for contextual AI. Moreover, we prototype a variety of application scenarios that suggest GazeGPT could be of significant value to users as part of future AI-driven personal assistants.

{{</citation>}}


### (102/162) Learning Agent-based Modeling with LLM Companions: Experiences of Novices and Experts Using ChatGPT & NetLogo Chat (John Chen et al., 2024)

{{<citation>}}

John Chen, Xi Lu, Michael Rejtig, David Du, Ruth Bagley, Michael S. Horn, Uri J. Wilensky. (2024)  
**Learning Agent-based Modeling with LLM Companions: Experiences of Novices and Experts Using ChatGPT & NetLogo Chat**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2401.17163v2)  

---


**ABSTRACT**  
Large Language Models (LLMs) have the potential to fundamentally change the way people engage in computer programming. Agent-based modeling (ABM) has become ubiquitous in natural and social sciences and education, yet no prior studies have explored the potential of LLMs to assist it. We designed NetLogo Chat to support the learning and practice of NetLogo, a programming language for ABM. To understand how users perceive, use, and need LLM-based interfaces, we interviewed 30 participants from global academia, industry, and graduate schools. Experts reported more perceived benefits than novices and were more inclined to adopt LLMs in their workflow. We found significant differences between experts and novices in their perceptions, behaviors, and needs for human-AI collaboration. We surfaced a knowledge gap between experts and novices as a possible reason for the benefit gap. We identified guidance, personalization, and integration as major needs for LLM-based interfaces to support the programming of ABM.

{{</citation>}}


### (103/162) PlantoGraphy: Incorporating Iterative Design Process into Generative Artificial Intelligence for Landscape Rendering (Rong Huang et al., 2024)

{{<citation>}}

Rong Huang, Hai-Chuan Lin, Chuanzhang Chen, Kang Zhang, Wei Zeng. (2024)  
**PlantoGraphy: Incorporating Iterative Design Process into Generative Artificial Intelligence for Landscape Rendering**  

---
Primary Category: cs.HC  
Categories: H-5-2, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17120v1)  

---


**ABSTRACT**  
Landscape renderings are realistic images of landscape sites, allowing stakeholders to perceive better and evaluate design ideas. While recent advances in Generative Artificial Intelligence (GAI) enable automated generation of landscape renderings, the end-to-end methods are not compatible with common design processes, leading to insufficient alignment with design idealizations and limited cohesion of iterative landscape design. Informed by a formative study for comprehending design requirements, we present PlantoGraphy, an iterative design system that allows for interactive configuration of GAI models to accommodate human-centered design practice. A two-stage pipeline is incorporated: first, concretization module transforms conceptual ideas into concrete scene layouts with a domain-oriented large language model; and second, illustration module converts scene layouts into realistic landscape renderings using a fine-tuned low-rank adaptation diffusion model. PlantoGraphy has undergone a series of performance evaluations and user studies, demonstrating its effectiveness in landscape rendering generation and the high recognition of its interactive functionality.

{{</citation>}}


### (104/162) Enhancing EEG Signal-Based Emotion Recognition with Synthetic Data: Diffusion Modeel Approach (Gourav Siddhad et al., 2024)

{{<citation>}}

Gourav Siddhad, Masakazu Iwamura, Partha Pratim Roy. (2024)  
**Enhancing EEG Signal-Based Emotion Recognition with Synthetic Data: Diffusion Modeel Approach**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2401.16878v1)  

---


**ABSTRACT**  
Emotions are crucial in human life, influencing perceptions, relationships, behaviour, and choices. Emotion recognition using Electroencephalography (EEG) in the Brain-Computer Interface (BCI) domain presents significant challenges, particularly the need for extensive datasets. This study aims to generate synthetic EEG samples that are similar to real samples but are distinct by augmenting noise to a conditional denoising diffusion probabilistic model, thus addressing the prevalent issue of data scarcity in EEG research. The proposed method is tested on the DEAP dataset, showcasing a 1.94% improvement in classification performance when using synthetic data. This is higher compared to the traditional GAN-based and DDPM-based approaches. The proposed diffusion-based approach for EEG data generation appears promising in refining the accuracy of emotion recognition systems and marks a notable contribution to EEG-based emotion recognition. Our research further evaluates the effectiveness of state-of-the-art classifiers on EEG data, employing both real and synthetic data with varying noise levels.

{{</citation>}}


### (105/162) Generative AI-based closed-loop fMRI system (Mikihiro Kasahara et al., 2024)

{{<citation>}}

Mikihiro Kasahara, Taiki Oka, Vincent Taschereau-Dumouchel, Mitsuo Kawato, Hiroki Takakura, Aurelio Cortese. (2024)  
**Generative AI-based closed-loop fMRI system**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-CR, cs-HC, cs-LG, cs.HC  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2401.16742v1)  

---


**ABSTRACT**  
While generative AI is now widespread and useful in society, there are potential risks of misuse, e.g., unconsciously influencing cognitive processes or decision-making. Although this causes a security problem in the cognitive domain, there has been no research about neural and computational mechanisms counteracting the impact of malicious generative AI in humans. We propose DecNefGAN, a novel framework that combines a generative adversarial system and a neural reinforcement model. More specifically, DecNefGAN bridges human and generative AI in a closed-loop system, with the AI creating stimuli that induce specific mental states, thus exerting external control over neural activity. The objective of the human is the opposite, to compete and reach an orthogonal mental state. This framework can contribute to elucidating how the human brain responds to and counteracts the potential influence of generative AI.

{{</citation>}}


### (106/162) Enabling BLV Developers with LLM-driven Code Debugging (Clark Saben et al., 2024)

{{<citation>}}

Clark Saben, Prashant Chandrasekar. (2024)  
**Enabling BLV Developers with LLM-driven Code Debugging**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2401.16654v1)  

---


**ABSTRACT**  
BLVRUN is a command line shell script designed to offer developers within the BLV community a succinct and insightful overview of traceback errors. Its primary function involves parsing errors and utilizing a refined large language model to generate informative error summaries. In terms of performance, our model rivals that of well-known models like ChatGPT or AI-chatbot plug-ins tailored for specific Integrated Development Environments (IDEs). Importantly, BLV users can seamlessly integrate this tool into their existing development workflows, eliminating the need for any modifications or adaptations to facilitate debugging tasks.

{{</citation>}}


## cs.CR (10)



### (107/162) A Preliminary Study on Using Large Language Models in Software Pentesting (Kumar Shashwat et al., 2024)

{{<citation>}}

Kumar Shashwat, Francis Hahn, Xinming Ou, Dmitry Goldgof, Lawrence Hall, Jay Ligatti, S. Raj Rajgopalan, Armin Ziaie Tabari. (2024)  
**A Preliminary Study on Using Large Language Models in Software Pentesting**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: AI, GPT, GPT-3.5, GPT-4, Google, Language Model  
[Paper Link](http://arxiv.org/abs/2401.17459v1)  

---


**ABSTRACT**  
Large language models (LLM) are perceived to offer promising potentials for automating security tasks, such as those found in security operation centers (SOCs). As a first step towards evaluating this perceived potential, we investigate the use of LLMs in software pentesting, where the main task is to automatically identify software security vulnerabilities in source code. We hypothesize that an LLM-based AI agent can be improved over time for a specific security task as human operators interact with it. Such improvement can be made, as a first step, by engineering prompts fed to the LLM based on the responses produced, to include relevant contexts and structures so that the model provides more accurate results. Such engineering efforts become sustainable if the prompts that are engineered to produce better results on current tasks, also produce better results on future unknown tasks. To examine this hypothesis, we utilize the OWASP Benchmark Project 1.2 which contains 2,740 hand-crafted source code test cases containing various types of vulnerabilities. We divide the test cases into training and testing data, where we engineer the prompts based on the training data (only), and evaluate the final system on the testing data. We compare the AI agent's performance on the testing data against the performance of the agent without the prompt engineering. We also compare the AI agent's results against those from SonarQube, a widely used static code analyzer for security testing. We built and tested multiple versions of the AI agent using different off-the-shelf LLMs -- Google's Gemini-pro, as well as OpenAI's GPT-3.5-Turbo and GPT-4-Turbo (with both chat completion and assistant APIs). The results show that using LLMs is a viable approach to build an AI agent for software pentesting that can improve through repeated use and prompt engineering.

{{</citation>}}


### (108/162) Large Language Models in Cybersecurity: State-of-the-Art (Farzad Nourmohammadzadeh Motlagh et al., 2024)

{{<citation>}}

Farzad Nourmohammadzadeh Motlagh, Mehrdad Hajizadeh, Mehryar Majd, Pejman Najafi, Feng Cheng, Christoph Meinel. (2024)  
**Large Language Models in Cybersecurity: State-of-the-Art**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CL, cs-CR, cs-LG, cs.CR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.00891v1)  

---


**ABSTRACT**  
The rise of Large Language Models (LLMs) has revolutionized our comprehension of intelligence bringing us closer to Artificial Intelligence. Since their introduction, researchers have actively explored the applications of LLMs across diverse fields, significantly elevating capabilities. Cybersecurity, traditionally resistant to data-driven solutions and slow to embrace machine learning, stands out as a domain. This study examines the existing literature, providing a thorough characterization of both defensive and adversarial applications of LLMs within the realm of cybersecurity. Our review not only surveys and categorizes the current landscape but also identifies critical research gaps. By evaluating both offensive and defensive applications, we aim to provide a holistic understanding of the potential risks and opportunities associated with LLM-driven cybersecurity.

{{</citation>}}


### (109/162) Utilizing Large Language Models to Translate RFC Protocol Specifications to CPSA Definitions (Martin Duclos et al., 2024)

{{<citation>}}

Martin Duclos, Ivan A. Fernandez, Kaneesha Moore, Sudip Mittal, Edward Zieglar. (2024)  
**Utilizing Large Language Models to Translate RFC Protocol Specifications to CPSA Definitions**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-NI, cs-SE, cs.CR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.00890v1)  

---


**ABSTRACT**  
This paper proposes the use of Large Language Models (LLMs) for translating Request for Comments (RFC) protocol specifications into a format compatible with the Cryptographic Protocol Shapes Analyzer (CPSA). This novel approach aims to reduce the complexities and efforts involved in protocol analysis, by offering an automated method for translating protocol specifications into structured models suitable for CPSA. In this paper we discuss the implementation of an RFC Protocol Translator, its impact on enhancing the accessibility of formal methods analysis, and its potential for improving the security of internet protocols.

{{</citation>}}


### (110/162) Systematically Assessing the Security Risks of AI/ML-enabled Connected Healthcare Systems (Mohammed Elnawawy et al., 2024)

{{<citation>}}

Mohammed Elnawawy, Mohammadreza Hallajiyan, Gargi Mitra, Shahrear Iqbal, Karthik Pattabiraman. (2024)  
**Systematically Assessing the Security Risks of AI/ML-enabled Connected Healthcare Systems**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-CY, cs-LG, cs.CR  
Keywords: AI, Security  
[Paper Link](http://arxiv.org/abs/2401.17136v1)  

---


**ABSTRACT**  
The adoption of machine-learning-enabled systems in the healthcare domain is on the rise. While the use of ML in healthcare has several benefits, it also expands the threat surface of medical systems. We show that the use of ML in medical systems, particularly connected systems that involve interfacing the ML engine with multiple peripheral devices, has security risks that might cause life-threatening damage to a patient's health in case of adversarial interventions. These new risks arise due to security vulnerabilities in the peripheral devices and communication channels. We present a case study where we demonstrate an attack on an ML-enabled blood glucose monitoring system by introducing adversarial data points during inference. We show that an adversary can achieve this by exploiting a known vulnerability in the Bluetooth communication channel connecting the glucose meter with the ML-enabled app. We further show that state-of-the-art risk assessment techniques are not adequate for identifying and assessing these new risks. Our study highlights the need for novel risk analysis methods for analyzing the security of AI-enabled connected health devices.

{{</citation>}}


### (111/162) Finetuning Large Language Models for Vulnerability Detection (Alexey Shestov et al., 2024)

{{<citation>}}

Alexey Shestov, Anton Cheshkov, Rodion Levichev, Ravil Mussabayev, Pavel Zadorozhny, Evgeny Maslov, Chibirev Vadim, Egor Bulychev. (2024)  
**Finetuning Large Language Models for Vulnerability Detection**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs-LG, cs.CR  
Keywords: BERT, Language Model, Vulnerability Detection  
[Paper Link](http://arxiv.org/abs/2401.17010v1)  

---


**ABSTRACT**  
This paper presents the results of finetuning large language models (LLMs) for the task of detecting vulnerabilities in source code. We leverage WizardCoder, a recent improvement of the state-of-the-art LLM StarCoder, and adapt it for vulnerability detection through further finetuning. To accelerate training, we modify WizardCoder's training procedure, also we investigate optimal training regimes. For the imbalanced dataset with many more negative examples than positive, we also explore different techniques to improve classification performance. The finetuned WizardCoder model achieves improvement in ROC AUC and F1 measures on balanced and imbalanced vulnerability datasets over CodeBERT-like model, demonstrating the effectiveness of adapting pretrained LLMs for vulnerability detection in source code. The key contributions are finetuning the state-of-the-art code LLM, WizardCoder, increasing its training speed without the performance harm, optimizing the training procedure and regimes, handling class imbalance, and improving performance on difficult vulnerability detection datasets. This demonstrates the potential for transfer learning by finetuning large pretrained language models for specialized source code analysis tasks.

{{</citation>}}


### (112/162) Randomized Key Encapsulation/Consolidation (Amir K. Khandani, 2024)

{{<citation>}}

Amir K. Khandani. (2024)  
**Randomized Key Encapsulation/Consolidation**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-IT, cs.CR, math-IT  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2401.16993v1)  

---


**ABSTRACT**  
This article bridges the gap between two topics used in sharing an encryption key: (i) Key Consolidation, i.e., extracting two identical strings of bits from two information sources with similarities (common randomness). (ii) Quantum-safe Key Encapsulation by incorporating randomness in Public/Private Key pairs. In the context of Key Consolidation, the proposed scheme adds to the complexity Eve faces in extracting useful data from leaked information. In this context, it is applied to the method proposed in [1] for establishing common randomness from round-trip travel times in a packet data network. The proposed method allows adapting the secrecy level to the amount of similarity in common randomness. It can even encapsulate a Quantum-safe encryption key in the extreme case that no common randomness is available. In the latter case, it is shown that the proposed scheme offers improvements with respect to the McEliece cryptosystem which currently forms the foundation for Quantum safe key encapsulation.   [1] A. K. Khandani, "Looping for Encryption Key Generation Over the Internet: A New Frontier in Physical Layer Security," 2023 Biennial Symposium on Communications (BSC), Montreal, QC, Canada, 2023, pp. 59-64

{{</citation>}}


### (113/162) Provably Robust Multi-bit Watermarking for AI-generated Text via Error Correction Code (Wenjie Qu et al., 2024)

{{<citation>}}

Wenjie Qu, Dong Yin, Zixin He, Wei Zou, Tianyang Tao, Jinyuan Jia, Jiaheng Zhang. (2024)  
**Provably Robust Multi-bit Watermarking for AI-generated Text via Error Correction Code**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16820v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have been widely deployed for their remarkable capability to generate texts resembling human language. However, they could be misused by criminals to create deceptive content, such as fake news and phishing emails, which raises ethical concerns. Watermarking is a key technique to mitigate the misuse of LLMs, which embeds a watermark (e.g., a bit string) into a text generated by a LLM. Consequently, this enables the detection of texts generated by a LLM as well as the tracing of generated texts to a specific user. The major limitation of existing watermark techniques is that they cannot accurately or efficiently extract the watermark from a text, especially when the watermark is a long bit string. This key limitation impedes their deployment for real-world applications, e.g., tracing generated texts to a specific user.   This work introduces a novel watermarking method for LLM-generated text grounded in \textbf{error-correction codes} to address this challenge. We provide strong theoretical analysis, demonstrating that under bounded adversarial word/token edits (insertion, deletion, and substitution), our method can correctly extract watermarks, offering a provable robustness guarantee. This breakthrough is also evidenced by our extensive experimental results. The experiments show that our method substantially outperforms existing baselines in both accuracy and robustness on benchmark datasets. For instance, when embedding a bit string of length 12 into a 200-token generated text, our approach attains an impressive match rate of $98.4\%$, surpassing the performance of Yoo et al. (state-of-the-art baseline) at $85.6\%$. When subjected to a copy-paste attack involving the injection of 50 tokens to generated texts with 200 words, our method maintains a substantial match rate of $90.8\%$, while the match rate of Yoo et al. diminishes to below $65\%$.

{{</citation>}}


### (114/162) A Cross-Language Investigation into Jailbreak Attacks in Large Language Models (Jie Li et al., 2024)

{{<citation>}}

Jie Li, Yi Liu, Chongyang Liu, Ling Shi, Xiaoning Ren, Yaowen Zheng, Yang Liu, Yinxing Xue. (2024)  
**A Cross-Language Investigation into Jailbreak Attacks in Large Language Models**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: GPT, GPT-4, Language Model, Multilingual  
[Paper Link](http://arxiv.org/abs/2401.16765v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have become increasingly popular for their advanced text generation capabilities across various domains. However, like any software, they face security challenges, including the risk of 'jailbreak' attacks that manipulate LLMs to produce prohibited content. A particularly underexplored area is the Multilingual Jailbreak attack, where malicious questions are translated into various languages to evade safety filters. Currently, there is a lack of comprehensive empirical studies addressing this specific threat.   To address this research gap, we conducted an extensive empirical study on Multilingual Jailbreak attacks. We developed a novel semantic-preserving algorithm to create a multilingual jailbreak dataset and conducted an exhaustive evaluation on both widely-used open-source and commercial LLMs, including GPT-4 and LLaMa. Additionally, we performed interpretability analysis to uncover patterns in Multilingual Jailbreak attacks and implemented a fine-tuning mitigation method. Our findings reveal that our mitigation strategy significantly enhances model defense, reducing the attack success rate by 96.2%. This study provides valuable insights into understanding and mitigating Multilingual Jailbreak attacks.

{{</citation>}}


### (115/162) Flash: A Hybrid Private Inference Protocol for Deep CNNs with High Accuracy and Low Latency on CPU (Hyeri Roh et al., 2024)

{{<citation>}}

Hyeri Roh, Jinsu Yeo, Yeongil Ko, Gu-Yeon Wei, David Brooks, Woo-Seok Choi. (2024)  
**Flash: A Hybrid Private Inference Protocol for Deep CNNs with High Accuracy and Low Latency on CPU**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2401.16732v1)  

---


**ABSTRACT**  
This paper presents Flash, an optimized private inference (PI) hybrid protocol utilizing both homomorphic encryption (HE) and secure two-party computation (2PC), which can reduce the end-to-end PI latency for deep CNN models less than 1 minute with CPU. To this end, first, Flash proposes a low-latency convolution algorithm built upon a fast slot rotation operation and a novel data encoding scheme, which results in 4-94x performance gain over the state-of-the-art. Second, to minimize the communication cost introduced by the standard nonlinear activation function ReLU, Flash replaces the entire ReLUs with the polynomial $x^2+x$ and trains deep CNN models with the new activation function. The trained models improve the inference accuracy for CIFAR-10/100 and TinyImageNet by 16% on average (up to 40% for ResNet-32) compared to prior art. Last, Flash proposes an efficient 2PC-based $x^2+x$ evaluation protocol that does not require any offline communication and that reduces the total communication cost to process the activation layer by 84-196x over the state-of-the-art. As a result, the end-to-end PI latency of Flash implemented on CPU is 0.02 minute for CIFAR-100 and 0.57 minute for TinyImageNet classification, while the total data communication is 0.07GB for CIFAR-100 and 0.22GB for TinyImageNet. Flash improves the state-of-the-art PI by 16-45x in latency and 84-196x in communication cost. Moreover, even for ImageNet, Flash can deliver the latency less than 1 minute on CPU with the total communication less than 1GB.

{{</citation>}}


### (116/162) Revisiting Gradient Pruning: A Dual Realization for Defending against Gradient Attacks (Lulu Xue et al., 2024)

{{<citation>}}

Lulu Xue, Shengshan Hu, Ruizhi Zhao, Leo Yu Zhang, Shengqing Hu, Lichao Sun, Dezhong Yao. (2024)  
**Revisiting Gradient Pruning: A Dual Realization for Defending against Gradient Attacks**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-LG, cs.CR  
Keywords: Pruning  
[Paper Link](http://arxiv.org/abs/2401.16687v1)  

---


**ABSTRACT**  
Collaborative learning (CL) is a distributed learning framework that aims to protect user privacy by allowing users to jointly train a model by sharing their gradient updates only. However, gradient inversion attacks (GIAs), which recover users' training data from shared gradients, impose severe privacy threats to CL. Existing defense methods adopt different techniques, e.g., differential privacy, cryptography, and perturbation defenses, to defend against the GIAs. Nevertheless, all current defense methods suffer from a poor trade-off between privacy, utility, and efficiency. To mitigate the weaknesses of existing solutions, we propose a novel defense method, Dual Gradient Pruning (DGP), based on gradient pruning, which can improve communication efficiency while preserving the utility and privacy of CL. Specifically, DGP slightly changes gradient pruning with a stronger privacy guarantee. And DGP can also significantly improve communication efficiency with a theoretical analysis of its convergence and generalization. Our extensive experiments show that DGP can effectively defend against the most powerful GIAs and reduce the communication cost without sacrificing the model's utility.

{{</citation>}}


## cs.CY (6)



### (117/162) Integrating Generative AI in Hackathons: Opportunities, Challenges, and Educational Implications (Ramteja Sajja et al., 2024)

{{<citation>}}

Ramteja Sajja, Carlos Erazo Ramirez, Zhouyayan Li, Bekir Z. Demiray, Yusuf Sermet, Ibrahim Demir. (2024)  
**Integrating Generative AI in Hackathons: Opportunities, Challenges, and Educational Implications**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs-HC, cs.CY  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2401.17434v2)  

---


**ABSTRACT**  
Hackathons and software competitions, increasingly pivotal in the software industry, serve as vital catalysts for innovation and skill development for both organizations and students. These platforms enable companies to prototype ideas swiftly, while students gain enriched learning experiences, enhancing their practical skills. Over the years, hackathons have transitioned from mere competitive events to significant educational tools, fusing theoretical knowledge with real-world problem-solving. The integration of hackathons into computer science and software engineering curricula aims to align educational proficiencies within a collaborative context, promoting peer connectivity and enriched learning via industry-academia collaborations. However, the infusion of advanced technologies, notably artificial intelligence (AI), and machine learning, into hackathons is revolutionizing their structure and outcomes. This evolution brings forth both opportunities, like enhanced learning experiences, and challenges, such as ethical concerns. This study delves into the impact of generative AI, examining its influence on student's technological choices based on a case study on the University of Iowa 2023 event. The exploration provides insights into AI's role in hackathons, and its educational implications, and offers a roadmap for the integration of such technologies in future events, ensuring innovation is balanced with ethical and educational considerations.

{{</citation>}}


### (118/162) Metaverse Perspectives from Japan: A Participatory Speculative Design Case Study (Michel Hohendanner et al., 2024)

{{<citation>}}

Michel Hohendanner, Chiara Ullstein, Dohjin Miyamoto, Emma Fukuwatari Huffman, Gudrun Socher, Jens Grossklags, Hirotaka Osawa. (2024)  
**Metaverse Perspectives from Japan: A Participatory Speculative Design Case Study**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs-HC, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17428v1)  

---


**ABSTRACT**  
Currently, the development of the metaverse lies in the hands of industry. Citizens have little influence on this process. Instead, to do justice to the pluralism of (digital) societies, we should strive for an open discourse including many different perspectives on the metaverse and its core technologies such as AI. We utilize a participatory speculative design (PSD) approach to explore Japanese citizens' perspectives on future metaverse societies, as well as social and ethical implications. Our contributions are twofold. Firstly, we demonstrate the effectiveness of PSD in engaging citizens in critical discourse on emerging technologies like the metaverse, offering our workshop framework as a methodological contribution. Secondly, we identify key themes from participants' perspectives, providing insights for culturally sensitive design and development of virtual environments. Our analysis shows that participants imagine the metaverse to have the potential to solve a variety of societal issues; for example, breaking down barriers of physical environments for communication, social interaction, crisis preparation, and political participation, or tackling identity-related issues. Regarding future metaverse societies, participants' imaginations raise critical questions about human-AI relations, technical solutionism, politics and technology, globalization and local cultures, and immersive technologies. We discuss implications and contribute to expanding conversations on metaverse developments.

{{</citation>}}


### (119/162) Commercial AI, Conflict, and Moral Responsibility: A theoretical analysis and practical approach to the moral responsibilities associated with dual-use AI technology (Daniel Trusilo et al., 2024)

{{<citation>}}

Daniel Trusilo, David Danks. (2024)  
**Commercial AI, Conflict, and Moral Responsibility: A theoretical analysis and practical approach to the moral responsibilities associated with dual-use AI technology**  

---
Primary Category: cs.CY  
Categories: K-4-1; K-5-2, cs-AI, cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01762v1)  

---


**ABSTRACT**  
This paper presents a theoretical analysis and practical approach to the moral responsibilities when developing AI systems for non-military applications that may nonetheless be used for conflict applications. We argue that AI represents a form of crossover technology that is different from previous historical examples of dual- or multi-use technology as it has a multiplicative effect across other technologies. As a result, existing analyses of ethical responsibilities around dual-use technologies do not necessarily work for AI systems. We instead argue that stakeholders involved in the AI system lifecycle are morally responsible for uses of their systems that are reasonably foreseeable. The core idea is that an agent's moral responsibility for some action is not necessarily determined by their intentions alone; we must also consider what the agent could reasonably have foreseen to be potential outcomes of their action, such as the potential use of a system in conflict even when it is not designed for that. In particular, we contend that it is reasonably foreseeable that: (1) civilian AI systems will be applied to active conflict, including conflict support activities, (2) the use of civilian AI systems in conflict will impact applications of the law of armed conflict, and (3) crossover AI technology will be applied to conflicts that fall short of armed conflict. Given these reasonably foreseeably outcomes, we present three technically feasible actions that developers of civilian AIs can take to potentially mitigate their moral responsibility: (a) establishing systematic approaches to multi-perspective capability testing, (b) integrating digital watermarking in model weight matrices, and (c) utilizing monitoring and reporting mechanisms for conflict-related AI applications.

{{</citation>}}


### (120/162) Trust and ethical considerations in a multi-modal, explainable AI-driven chatbot tutoring system: The case of collaboratively solving Rubik's Cube (Kausik Lakkaraju et al., 2024)

{{<citation>}}

Kausik Lakkaraju, Vedant Khandelwal, Biplav Srivastava, Forest Agostinelli, Hengtao Tang, Prathamjeet Singh, Dezhi Wu, Matt Irvin, Ashish Kundu. (2024)  
**Trust and ethical considerations in a multi-modal, explainable AI-driven chatbot tutoring system: The case of collaboratively solving Rubik's Cube**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.01760v1)  

---


**ABSTRACT**  
Artificial intelligence (AI) has the potential to transform education with its power of uncovering insights from massive data about student learning patterns. However, ethical and trustworthy concerns of AI have been raised but are unsolved. Prominent ethical issues in high school AI education include data privacy, information leakage, abusive language, and fairness. This paper describes technological components that were built to address ethical and trustworthy concerns in a multi-modal collaborative platform (called ALLURE chatbot) for high school students to collaborate with AI to solve the Rubik's cube. In data privacy, we want to ensure that the informed consent of children, parents, and teachers, is at the center of any data that is managed. Since children are involved, language, whether textual, audio, or visual, is acceptable both from users and AI and the system can steer interaction away from dangerous situations. In information management, we also want to ensure that the system, while learning to improve over time, does not leak information about users from one group to another.

{{</citation>}}


### (121/162) Aalap: AI Assistant for Legal & Paralegal Functions in India (Aman Tiwari et al., 2024)

{{<citation>}}

Aman Tiwari, Prathamesh Kalamkar, Atreyo Banerjee, Saurabh Karn, Varun Hemachandran, Smita Gupta. (2024)  
**Aalap: AI Assistant for Legal & Paralegal Functions in India**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CL, cs-CY, cs.CY  
Keywords: AI, GPT, Language Model, Legal  
[Paper Link](http://arxiv.org/abs/2402.01758v1)  

---


**ABSTRACT**  
Using proprietary Large Language Models on legal tasks poses challenges due to data privacy issues, domain data heterogeneity, domain knowledge sophistication, and domain objectives uniqueness. We created Aalalp, a fine-tuned Mistral 7B model on instructions data related to specific Indian legal tasks. The performance of Aalap is better than gpt-3.5-turbo in 31\% of our test data and obtains an equivalent score in 34\% of the test data as evaluated by GPT4. Training Aalap mainly focuses on teaching legal reasoning rather than legal recall. Aalap is definitely helpful for the day-to-day activities of lawyers, judges, or anyone working in legal systems.

{{</citation>}}


### (122/162) Towards Urban General Intelligence: A Review and Outlook of Urban Foundation Models (Weijia Zhang et al., 2024)

{{<citation>}}

Weijia Zhang, Jindong Han, Zhao Xu, Hang Ni, Hao Liu, Hui Xiong. (2024)  
**Towards Urban General Intelligence: A Review and Outlook of Urban Foundation Models**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs-LG, cs.CY  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2402.01749v1)  

---


**ABSTRACT**  
Machine learning techniques are now integral to the advancement of intelligent urban services, playing a crucial role in elevating the efficiency, sustainability, and livability of urban environments. The recent emergence of foundation models such as ChatGPT marks a revolutionary shift in the fields of machine learning and artificial intelligence. Their unparalleled capabilities in contextual understanding, problem solving, and adaptability across a wide range of tasks suggest that integrating these models into urban domains could have a transformative impact on the development of smart cities. Despite growing interest in Urban Foundation Models~(UFMs), this burgeoning field faces challenges such as a lack of clear definitions, systematic reviews, and universalizable solutions. To this end, this paper first introduces the concept of UFM and discusses the unique challenges involved in building them. We then propose a data-centric taxonomy that categorizes current UFM-related works, based on urban data modalities and types. Furthermore, to foster advancement in this field, we present a promising framework aimed at the prospective realization of UFMs, designed to overcome the identified challenges. Additionally, we explore the application landscape of UFMs, detailing their potential impact in various urban contexts. Relevant papers and open-source resources have been collated and are continuously updated at https://github.com/usail-hkust/Awesome-Urban-Foundation-Models.

{{</citation>}}


## cs.IT (6)



### (123/162) Few-Shot Channel-Agnostic Analog Coding: A Near-Optimal Scheme (Mohammad Ali Maddah-Ali et al., 2024)

{{<citation>}}

Mohammad Ali Maddah-Ali, Soheil Mohajer. (2024)  
**Few-Shot Channel-Agnostic Analog Coding: A Near-Optimal Scheme**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, math-IT  
Keywords: Few-Shot  
[Paper Link](http://arxiv.org/abs/2401.17419v1)  

---


**ABSTRACT**  
In this paper, we investigate the problem of transmitting an analog source to a destination over $N$ uses of an additive-white-Gaussian-noise (AWGN) channel, where $N$ is very small (in the order of 10 or even less). The proposed coding scheme is based on representing the source symbol using a novel progressive expansion technique, partitioning the digits of expansion into $N$ ordered sets, and finally mapping the symbols in each set to a real number by applying the reverse progressive expansion. In the last step, we introduce some gaps between the signal levels to prevent the carry-over of the additive noise from propagation to other levels. This shields the most significant levels of the signal from an additive noise, hitting the signal at a less significant level. The parameters of the progressive expansion and the shielding procedure are opportunistically independent of the $\SNR$ so that the proposed scheme achieves a distortion $D$, where $-\log(D)$ is within $O(\log\log(\SNR))$ of the optimal performance for all values of $\SNR$, leading to a channel-agnostic scheme.

{{</citation>}}


### (124/162) Quantum $X$-Secure $B$-Byzantine $T$-Colluding Private Information Retrieval (Mohamed Nomeir et al., 2024)

{{<citation>}}

Mohamed Nomeir, Alptug Aytekin, Sennur Ulukus. (2024)  
**Quantum $X$-Secure $B$-Byzantine $T$-Colluding Private Information Retrieval**  

---
Primary Category: cs.IT  
Categories: cs-CR, cs-IT, cs-NI, cs.IT, eess-SP, math-IT, quant-ph  
Keywords: Information Retrieval  
[Paper Link](http://arxiv.org/abs/2401.17252v1)  

---


**ABSTRACT**  
We consider the problems arising from the presence of Byzantine servers in a quantum private information retrieval (QPIR) setting. This is the first work to precisely define what the capabilities of Byzantine servers could be in a QPIR context. We show that quantum Byzantine servers have more capabilities than their classical counterparts due to the possibilities created by the quantum encoding procedure. We focus on quantum Byzantine servers that can apply any reversible operations on their individual qudits. In this case, the Byzantine servers can generate any error, i.e., this covers \emph{all} possible single qudit operations that can be done by the Byzantine servers on their qudits. We design a scheme that is resilient to these kinds of manipulations. We show that the scheme designed achieves superdense coding gain in all cases, i.e., $R_Q= \max \left\{0,\min\left\{1,2\left(1-\frac{X+T+2B}{N}\right)\right\}\right\}$.

{{</citation>}}


### (125/162) Nested Construction of Polar Codes via Transformers (Sravan Kumar Ankireddy et al., 2024)

{{<citation>}}

Sravan Kumar Ankireddy, S Ashwin Hebbar, Heping Wan, Joonyoung Cho, Charlie Zhang. (2024)  
**Nested Construction of Polar Codes via Transformers**  

---
Primary Category: cs.IT  
Categories: cs-AI, cs-IT, cs.IT, math-IT  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.17188v1)  

---


**ABSTRACT**  
Tailoring polar code construction for decoding algorithms beyond successive cancellation has remained a topic of significant interest in the field. However, despite the inherent nested structure of polar codes, the use of sequence models in polar code construction is understudied. In this work, we propose using a sequence modeling framework to iteratively construct a polar code for any given length and rate under various channel conditions. Simulations show that polar codes designed via sequential modeling using transformers outperform both 5G-NR sequence and Density Evolution based approaches for both AWGN and Rayleigh fading channels.

{{</citation>}}


### (126/162) Age of Actuated Information and Age of Actuation in a Data-Caching Energy Harvesting Actuator (Ali Nikkhah et al., 2024)

{{<citation>}}

Ali Nikkhah, Anthony Ephremides, Nikolaos Pappas. (2024)  
**Age of Actuated Information and Age of Actuation in a Data-Caching Energy Harvesting Actuator**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, math-IT  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17011v1)  

---


**ABSTRACT**  
In this paper, we introduce two metrics, namely, age of actuation (AoA) and age of actuated information (AoAI), within a discrete-time system model that integrates data caching and energy harvesting (EH). AoA evaluates the timeliness of actions irrespective of the age of the information, while AoAI considers the freshness of the utilized data packet. We use Markov Chain analysis to model the system's evolution. Furthermore, we employ three-dimensional Markov Chain analysis to characterize the stationary distributions for AoA and AoAI and calculate their average values. Our findings from the analysis, validated by simulations, show that while AoAI consistently decreases with increased data and energy packet arrival rates, AoA presents a more complex behavior, with potential increases under conditions of limited data or energy resources. These metrics go towards the semantics of information and goal-oriented communications since they consider the timeliness of utilizing the information to perform an action.

{{</citation>}}


### (127/162) Deep Contextual Bandit and Reinforcement Learning for IRS-Assisted MU-MIMO Systems (Dariel Pereira-Ruisánchez et al., 2024)

{{<citation>}}

Dariel Pereira-Ruisánchez, Óscar Fresnedo, Darian Pérez-Adán, Luis Castedo. (2024)  
**Deep Contextual Bandit and Reinforcement Learning for IRS-Assisted MU-MIMO Systems**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, eess-SP, math-IT  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16901v1)  

---


**ABSTRACT**  
The combination of multiple-input multiple-output (MIMO) systems and intelligent reflecting surfaces (IRSs) is foreseen as a critical enabler of beyond 5G (B5G) and 6G. In this work, two different approaches are considered for the joint optimization of the IRS phase-shift matrix and MIMO precoders of an IRS-assisted multi-stream (MS) multi-user MIMO (MU-MIMO) system. Both approaches aim to maximize the system sum-rate for every channel realization. The first proposed solution is a novel contextual bandit (CB) framework with continuous state and action spaces called deep contextual bandit-oriented deep deterministic policy gradient (DCB-DDPG). The second is an innovative deep reinforcement learning (DRL) formulation where the states, actions, and rewards are selected such that the Markov decision process (MDP) property of reinforcement learning (RL) is appropriately met. Both proposals perform remarkably better than state-of-the-art heuristic methods in scenarios with high multi-user interference.

{{</citation>}}


### (128/162) Achieving Capacity of PIR with Private Side Information with Low Sub-packetization and without MDS Codes (Leila Erhili et al., 2024)

{{<citation>}}

Leila Erhili, Anoosheh Heidarzadeh. (2024)  
**Achieving Capacity of PIR with Private Side Information with Low Sub-packetization and without MDS Codes**  

---
Primary Category: cs.IT  
Categories: cs-IT, cs.IT, math-IT  
Keywords: Information Retrieval  
[Paper Link](http://arxiv.org/abs/2401.16630v1)  

---


**ABSTRACT**  
This paper revisits the problem of multi-server Private Information Retrieval with Private Side Information (PIR-PSI). In this problem, $N$ non-colluding servers store identical copies of $K$ messages, each comprising $L$ symbols from $\mathbb{F}_q$, and a user, who knows $M$ of these messages, wants to retrieve one of the remaining $K-M$ messages. The user's goal is to retrieve the desired message by downloading the minimum amount of information from the servers while revealing no information about the identities of the desired message and side information messages to any server. The capacity of PIR-PSI, defined as the maximum achievable download rate, was previously characterized for all $N$, $K$, and $M$ when $L$ and $q$ are sufficiently large -- specifically, growing exponentially with $K$, to ensure the divisibility of each message into $N^K$ sub-packets and to guarantee the existence of an MDS code with its length and dimension being exponential in $K$. In this work, we propose a new capacity-achieving PIR-PSI scheme that is applicable to all $N$, $K$, $M$, $L$, and $q$ where $N\geq M+1$ and $N-1\mid L$. The proposed scheme operates with a sub-packetization level of $N-1$, independent of $K$, and works over any finite field without requiring an MDS code.

{{</citation>}}


## cs.MA (1)



### (129/162) Camouflage Adversarial Attacks on Multiple Agent Systems (Ziqing Lu et al., 2024)

{{<citation>}}

Ziqing Lu, Guanlin Liu, Lifeng Lai, Weiyu Xu. (2024)  
**Camouflage Adversarial Attacks on Multiple Agent Systems**  

---
Primary Category: cs.MA  
Categories: cs-MA, cs.MA  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2401.17405v1)  

---


**ABSTRACT**  
The multi-agent reinforcement learning systems (MARL) based on the Markov decision process (MDP) have emerged in many critical applications. To improve the robustness/defense of MARL systems against adversarial attacks, the study of various adversarial attacks on reinforcement learning systems is very important. Previous works on adversarial attacks considered some possible features to attack in MDP, such as the action poisoning attacks, the reward poisoning attacks, and the state perception attacks. In this paper, we propose a brand-new form of attack called the camouflage attack in the MARL systems. In the camouflage attack, the attackers change the appearances of some objects without changing the actual objects themselves; and the camouflaged appearances may look the same to all the targeted recipient (victim) agents. The camouflaged appearances can mislead the recipient agents to misguided actions. We design algorithms that give the optimal camouflage attacks minimizing the rewards of recipient agents. Our numerical and theoretical results show that camouflage attacks can rival the more conventional, but likely more difficult state perception attacks. We also investigate cost-constrained camouflage attacks and showed numerically how cost budgets affect the attack performance.

{{</citation>}}


## cs.NE (1)



### (130/162) EvoMerge: Neuroevolution for Large Language Models (Yushu Jiang, 2024)

{{<citation>}}

Yushu Jiang. (2024)  
**EvoMerge: Neuroevolution for Large Language Models**  

---
Primary Category: cs.NE  
Categories: cs-AI, cs-CL, cs-LG, cs-NE, cs.NE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2402.00070v1)  

---


**ABSTRACT**  
Extensive fine-tuning on Large Language Models does not always yield better results. Oftentimes, models tend to get better at imitating one form of data without gaining greater reasoning ability and may even end up losing some intelligence. Here I introduce EvoMerge, a systematic approach to large language model training and merging. Leveraging model merging for weight crossover and fine-tuning for weight mutation, EvoMerge establishes an evolutionary process aimed at pushing models beyond the limits of conventional fine-tuning.

{{</citation>}}


## cs.RO (6)



### (131/162) ATPPNet: Attention based Temporal Point cloud Prediction Network (Kaustab Pal et al., 2024)

{{<citation>}}

Kaustab Pal, Aditya Sharma, Avinash Sharma, K. Madhava Krishna. (2024)  
**ATPPNet: Attention based Temporal Point cloud Prediction Network**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Attention, LSTM  
[Paper Link](http://arxiv.org/abs/2401.17399v1)  

---


**ABSTRACT**  
Point cloud prediction is an important yet challenging task in the field of autonomous driving. The goal is to predict future point cloud sequences that maintain object structures while accurately representing their temporal motion. These predicted point clouds help in other subsequent tasks like object trajectory estimation for collision avoidance or estimating locations with the least odometry drift. In this work, we present ATPPNet, a novel architecture that predicts future point cloud sequences given a sequence of previous time step point clouds obtained with LiDAR sensor. ATPPNet leverages Conv-LSTM along with channel-wise and spatial attention dually complemented by a 3D-CNN branch for extracting an enhanced spatio-temporal context to recover high quality fidel predictions of future point clouds. We conduct extensive experiments on publicly available datasets and report impressive performance outperforming the existing methods. We also conduct a thorough ablative study of the proposed architecture and provide an application study that highlights the potential of our model for tasks like odometry estimation.

{{</citation>}}


### (132/162) Online Robot Navigation and and Manipulation with Distilled Vision-Language Models (Kangcheng Liu et al., 2024)

{{<citation>}}

Kangcheng Liu, Xinhu Zheng, Chaoqun Wang, Hesheng Wang, Ming Liu, Kai Tang. (2024)  
**Online Robot Navigation and and Manipulation with Distilled Vision-Language Models**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17083v1)  

---


**ABSTRACT**  
Autonomous robot navigation within the dynamic unknown environment is of crucial significance for mobile robotic applications including robot navigation in last-mile delivery and robot-enabled automated supplies in industrial and hospital delivery applications. Current solutions still suffer from limitations, such as the robot cannot recognize unknown objects in real time and cannot navigate freely in a dynamic, narrow, and complex environment. We propose a complete software framework for autonomous robot perception and navigation within very dense obstacles and dense human crowds. First, we propose a framework that accurately detects and segments open-world object categories in a zero-shot manner, which overcomes the over-segmentation limitation of the current SAM model. Second, we proposed the distillation strategy to distill the knowledge to segment the free space of the walkway for robot navigation without the label. In the meantime, we design the trimming strategy that works collaboratively with distillation to enable lightweight inference to deploy the neural network on edge devices such as NVIDIA-TX2 or Xavier NX during autonomous navigation. Integrated into the robot navigation system, extensive experiments demonstrate that our proposed framework has achieved superior performance in terms of both accuracy and efficiency in robot scene perception and autonomous robot navigation.

{{</citation>}}


### (133/162) M2CURL: Sample-Efficient Multimodal Reinforcement Learning via Self-Supervised Representation Learning for Robotic Manipulation (Fotios Lygerakis et al., 2024)

{{<citation>}}

Fotios Lygerakis, Vedant Dave, Elmar Rueckert. (2024)  
**M2CURL: Sample-Efficient Multimodal Reinforcement Learning via Self-Supervised Representation Learning for Robotic Manipulation**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning, Representation Learning, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2401.17032v1)  

---


**ABSTRACT**  
One of the most critical aspects of multimodal Reinforcement Learning (RL) is the effective integration of different observation modalities. Having robust and accurate representations derived from these modalities is key to enhancing the robustness and sample efficiency of RL algorithms. However, learning representations in RL settings for visuotactile data poses significant challenges, particularly due to the high dimensionality of the data and the complexity involved in correlating visual and tactile inputs with the dynamic environment and task objectives. To address these challenges, we propose Multimodal Contrastive Unsupervised Reinforcement Learning (M2CURL). Our approach employs a novel multimodal self-supervised learning technique that learns efficient representations and contributes to faster convergence of RL algorithms. Our method is agnostic to the RL algorithm, thus enabling its integration with any available RL algorithm. We evaluate M2CURL on the Tactile Gym 2 simulator and we show that it significantly enhances the learning efficiency in different manipulation tasks. This is evidenced by faster convergence rates and higher cumulative rewards per episode, compared to standard RL algorithms without our representation learning approach.

{{</citation>}}


### (134/162) Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control (Zhongyu Li et al., 2024)

{{<citation>}}

Zhongyu Li, Xue Bin Peng, Pieter Abbeel, Sergey Levine, Glen Berseth, Koushil Sreenath. (2024)  
**Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16889v1)  

---


**ABSTRACT**  
This paper presents a comprehensive study on using deep reinforcement learning (RL) to create dynamic locomotion controllers for bipedal robots. Going beyond focusing on a single locomotion skill, we develop a general control solution that can be used for a range of dynamic bipedal skills, from periodic walking and running to aperiodic jumping and standing. Our RL-based controller incorporates a novel dual-history architecture, utilizing both a long-term and short-term input/output (I/O) history of the robot. This control architecture, when trained through the proposed end-to-end RL approach, consistently outperforms other methods across a diverse range of skills in both simulation and the real world.The study also delves into the adaptivity and robustness introduced by the proposed RL system in developing locomotion controllers. We demonstrate that the proposed architecture can adapt to both time-invariant dynamics shifts and time-variant changes, such as contact events, by effectively using the robot's I/O history. Additionally, we identify task randomization as another key source of robustness, fostering better task generalization and compliance to disturbances. The resulting control policies can be successfully deployed on Cassie, a torque-controlled human-sized bipedal robot. This work pushes the limits of agility for bipedal robots through extensive real-world experiments. We demonstrate a diverse range of locomotion skills, including: robust standing, versatile walking, fast running with a demonstration of a 400-meter dash, and a diverse set of jumping skills, such as standing long jumps and high jumps.

{{</citation>}}


### (135/162) OptiState: State Estimation of Legged Robots using Gated Networks with Transformer-based Vision and Kalman Filtering (Alexander Schperberg et al., 2024)

{{<citation>}}

Alexander Schperberg, Yusuke Tanaka, Saviz Mowlavi, Feng Xu, Bharathan Balaji, Dennis Hong. (2024)  
**OptiState: State Estimation of Legged Robots using Gated Networks with Transformer-based Vision and Kalman Filtering**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2401.16719v2)  

---


**ABSTRACT**  
State estimation for legged robots is challenging due to their highly dynamic motion and limitations imposed by sensor accuracy. By integrating Kalman filtering, optimization, and learning-based modalities, we propose a hybrid solution that combines proprioception and exteroceptive information for estimating the state of the robot's trunk. Leveraging joint encoder and IMU measurements, our Kalman filter is enhanced through a single-rigid body model that incorporates ground reaction force control outputs from convex Model Predictive Control optimization. The estimation is further refined through Gated Recurrent Units, which also considers semantic insights and robot height from a Vision Transformer autoencoder applied on depth images. This framework not only furnishes accurate robot state estimates, including uncertainty evaluations, but can minimize the nonlinear errors that arise from sensor measurements and model simplifications through learning. The proposed methodology is evaluated in hardware using a quadruped robot on various terrains, yielding a 65% improvement on the Root Mean Squared Error compared to our VIO SLAM baseline. Code example: https://github.com/AlexS28/OptiState

{{</citation>}}


### (136/162) ILBiT: Imitation Learning for Robot Using Position and Torque Information based on Bilateral Control with Transformer (Masato Kobayashi et al., 2024)

{{<citation>}}

Masato Kobayashi, Thanpimon Buamanee, Yuki Uranishi, Haruo Takemura. (2024)  
**ILBiT: Imitation Learning for Robot Using Position and Torque Information based on Bilateral Control with Transformer**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: LSTM, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16653v2)  

---


**ABSTRACT**  
Autonomous manipulation in robot arms is a complex and evolving field of study in robotics. This paper introduces an innovative approach to this challenge by focusing on imitation learning (IL). Unlike traditional imitation methods, our approach uses IL based on bilateral control, allowing for more precise and adaptable robot movements. The conventional IL based on bilateral control method have relied on Long Short-Term Memory (LSTM) networks. In this paper, we present the IL for robot using position and torque information based on Bilateral control with Transformer (ILBiT). This proposed method employs the Transformer model, known for its robust performance in handling diverse datasets and its capability to surpass LSTM's limitations, especially in tasks requiring detailed force adjustments. A standout feature of ILBiT is its high-frequency operation at 100 Hz, which significantly improves the system's adaptability and response to varying environments and objects of different hardness levels. The effectiveness of the Transformer-based ILBiT method can be seen through comprehensive real-world experiments.

{{</citation>}}


## cs.AR (4)



### (137/162) Using the Abstract Computer Architecture Description Language to Model AI Hardware Accelerators (Mika Markus Müller et al., 2024)

{{<citation>}}

Mika Markus Müller, Alexander Richard Manfred Borst, Konstantin Lübeck, Alexander Louis-Ferdinand Jung, Oliver Bringmann. (2024)  
**Using the Abstract Computer Architecture Description Language to Model AI Hardware Accelerators**  

---
Primary Category: cs.AR  
Categories: cs-AI, cs-AR, cs.AR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2402.00069v1)  

---


**ABSTRACT**  
Artificial Intelligence (AI) has witnessed remarkable growth, particularly through the proliferation of Deep Neural Networks (DNNs). These powerful models drive technological advancements across various domains. However, to harness their potential in real-world applications, specialized hardware accelerators are essential. This demand has sparked a market for parameterizable AI hardware accelerators offered by different vendors.   Manufacturers of AI-integrated products face a critical challenge: selecting an accelerator that aligns with their product's performance requirements. The decision involves choosing the right hardware and configuring a suitable set of parameters. However, comparing different accelerator design alternatives remains a complex task. Often, engineers rely on data sheets, spreadsheet calculations, or slow black-box simulators, which only offer a coarse understanding of the performance characteristics.   The Abstract Computer Architecture Description Language (ACADL) is a concise formalization of computer architecture block diagrams, which helps to communicate computer architecture on different abstraction levels and allows for inferring performance characteristics. In this paper, we demonstrate how to use the ACADL to model AI hardware accelerators, use their ACADL description to map DNNs onto them, and explain the timing simulation semantics to gather performance results.

{{</citation>}}


### (138/162) SAL-PIM: A Subarray-level Processing-in-Memory Architecture with LUT-based Linear Interpolation for Transformer-based Text Generation (Wontak Han et al., 2024)

{{<citation>}}

Wontak Han, Hyunjun Cho, Donghyuk Kim, Joo-Young Kim. (2024)  
**SAL-PIM: A Subarray-level Processing-in-Memory Architecture with LUT-based Linear Interpolation for Transformer-based Text Generation**  

---
Primary Category: cs.AR  
Categories: cs-AR, cs.AR  
Keywords: GPT, Text Generation, Transformer  
[Paper Link](http://arxiv.org/abs/2401.17005v1)  

---


**ABSTRACT**  
Text generation is a compelling sub-field of natural language processing, aiming to generate human-readable text from input words. In particular, the decoder-only generative models, such as generative pre-trained transformer (GPT), are widely used for text generation, with two major computational stages: summarization and generation. Unlike the summarization stage, which can process the input tokens in parallel, the generation stage is difficult to accelerate due to its sequential generation of output tokens through iteration. Moreover, each iteration requires reading a whole model with little data reuse opportunity. Therefore, the workload of transformer-based text generation is severely memory-bound, making the external memory bandwidth system bottleneck. In this paper, we proposed a subarray-level processing-in-memory architecture named SAL-PIM, HBM-based PIM architecture for the end-to-end acceleration of transformer-based text generation. The SAL-PIM architecture includes three architectural features. First, the SAL-PIM architecture utilizes higher internal bandwidth by integrating multiple subarray-level arithmetic logic units with optimized data mapping schemes. Second, the SAL-PIM architecture adopts LUT-based linear interpolation to perform complex non-linear functions in PIM. Third, the SAL-PIM architecture accelerates end-to-end inference on PIM in text generation. Furthermore, to validate the SAL-PIM architecture, we built cycle-accurate simulator and implemented the SAL-PIM's logic units in 28-nm CMOS technology. As a result, when the input size is from 32 to 128 and the output size is from 1 to 256, SAL-PIM achieves a maximum of 4.72 times speedup and an average of 1.83 times speedup for the text generation based on the GPT-2 medium model compared to the server-level GPU.

{{</citation>}}


### (139/162) WideSA: A High Array Utilization Mapping Scheme for Uniform Recurrences on the Versal ACAP Architecture (Tuo Dai et al., 2024)

{{<citation>}}

Tuo Dai, Bizhao Shi, Guojie Luo. (2024)  
**WideSA: A High Array Utilization Mapping Scheme for Uniform Recurrences on the Versal ACAP Architecture**  

---
Primary Category: cs.AR  
Categories: cs-AR, cs.AR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16792v1)  

---


**ABSTRACT**  
The Versal Adaptive Compute Acceleration Platform (ACAP) is a new architecture that combines AI Engines (AIEs) with reconfigurable fabric. This architecture offers significant acceleration potential for uniform recurrences in various domains, such as deep learning, high-performance computation, and signal processing. However, efficiently mapping these computations onto the Versal ACAP architecture while achieving high utilization of AIEs poses a challenge.   To address this issue, we propose a mapping scheme called \fname, which aims to accelerate uniform recurrences on the Versal ACAP architecture by leveraging the features of both the hardware and the computations. Considering the array architecture of AIEs, our approach utilizes space-time transformations based on the polyhedral model to generate legally optimized systolic array mappings. Concurrently, we have developed a routing-aware PLIO assignment algorithm tailored for communication on the AIE array, and the algorithm aims at successful compilation while maximizing array utilization. Furthermore, we introduce an automatic mapping framework. This framework is designed to generate the corresponding executable code for uniform recurrences, which encompasses the AIE kernel program, programmable logic bitstreams, and the host program. The experimental results validate the effectiveness of our mapping scheme. Specifically, when applying our scheme to matrix multiplication computations on the VCK5000 board, we achieve a throughput of 4.15TOPS on float data type, which is 1.11$\times$ higher compared to the state-of-the-art accelerator on the Versal ACAP architecture.

{{</citation>}}


### (140/162) T3: Transparent Tracking & Triggering for Fine-grained Overlap of Compute & Collectives (Suchita Pati et al., 2024)

{{<citation>}}

Suchita Pati, Shaizeen Aga, Mahzabeen Islam, Nuwan Jayasena, Matthew D. Sinclair. (2024)  
**T3: Transparent Tracking & Triggering for Fine-grained Overlap of Compute & Collectives**  

---
Primary Category: cs.AR  
Categories: C-2-4; C-1-2, cs-AR, cs-DC, cs-LG, cs.AR  
Keywords: Language Model, Transformer  
[Paper Link](http://arxiv.org/abs/2401.16677v1)  

---


**ABSTRACT**  
Large Language Models increasingly rely on distributed techniques for their training and inference. These techniques require communication across devices which can reduce scaling efficiency as the number of devices increases. While some distributed techniques can overlap, and thus, hide this communication with independent computations, techniques such as Tensor Parallelism (TP) inherently serialize communication with model execution. One approach to hide this serialized communication is to interleave it with the producer operation (of the communicated data) in a fine-grained manner. However, this fine-grained interleaving of communication and computation in software can be difficult. Furthermore, as with any concurrent execution, it requires compute and memory resources to be shared between computation and communication, causing resource contention that reduces overlapping efficacy.   To overcome these challenges, we propose T3 which applies hardware-software co-design to transparently overlap serialized communication while minimizing resource contention with compute. T3 transparently fuses producer operations with the subsequent communication via a simple configuration of the producer's output address space and requires minor software changes. At the hardware level, T3 adds a lightweight track and trigger mechanism to orchestrate the producer's compute, and communication. It further uses compute-enhanced memories for communication's attendant compute. As a result, T3 reduces resource contention, and efficiently overlaps serialized communication with computation. For important Transformer models like T-NLG, T3 speeds up communication-heavy sublayers by 30% geomean (max 47%) and reduces data movement by 22% geomean (max 36%). Furthermore, T3's benefits persist as models scale: geomean 29% for sublayers in $\sim$500-billion parameter models, PALM and MT-NLG.

{{</citation>}}


## stat.ML (3)



### (141/162) Effect of Weight Quantization on Learning Models by Typical Case Analysis (Shuhei Kashiwamura et al., 2024)

{{<citation>}}

Shuhei Kashiwamura, Ayaka Sakata, Masaaki Imaizumi. (2024)  
**Effect of Weight Quantization on Learning Models by Typical Case Analysis**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Quantization  
[Paper Link](http://arxiv.org/abs/2401.17269v1)  

---


**ABSTRACT**  
This paper examines the quantization methods used in large-scale data analysis models and their hyperparameter choices. The recent surge in data analysis scale has significantly increased computational resource requirements. To address this, quantizing model weights has become a prevalent practice in data analysis applications such as deep learning. Quantization is particularly vital for deploying large models on devices with limited computational resources. However, the selection of quantization hyperparameters, like the number of bits and value range for weight quantization, remains an underexplored area. In this study, we employ the typical case analysis from statistical physics, specifically the replica method, to explore the impact of hyperparameters on the quantization of simple learning models. Our analysis yields three key findings: (i) an unstable hyperparameter phase, known as replica symmetry breaking, occurs with a small number of bits and a large quantization width; (ii) there is an optimal quantization width that minimizes error; and (iii) quantization delays the onset of overparameterization, helping to mitigate overfitting as indicated by the double descent phenomenon. We also discover that non-uniform quantization can enhance stability. Additionally, we develop an approximate message-passing algorithm to validate our theoretical results.

{{</citation>}}


### (142/162) Adaptive Experiment Design with Synthetic Controls (Alihan Hüyük et al., 2024)

{{<citation>}}

Alihan Hüyük, Zhaozhi Qian, Mihaela van der Schaar. (2024)  
**Adaptive Experiment Design with Synthetic Controls**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: Clinical  
[Paper Link](http://arxiv.org/abs/2401.17205v1)  

---


**ABSTRACT**  
Clinical trials are typically run in order to understand the effects of a new treatment on a given population of patients. However, patients in large populations rarely respond the same way to the same treatment. This heterogeneity in patient responses necessitates trials that investigate effects on multiple subpopulations - especially when a treatment has marginal or no benefit for the overall population but might have significant benefit for a particular subpopulation. Motivated by this need, we propose Syntax, an exploratory trial design that identifies subpopulations with positive treatment effect among many subpopulations. Syntax is sample efficient as it (i) recruits and allocates patients adaptively and (ii) estimates treatment effects by forming synthetic controls for each subpopulation that combines control samples from other subpopulations. We validate the performance of Syntax and provide insights into when it might have an advantage over conventional trial designs through experiments.

{{</citation>}}


### (143/162) Causal Machine Learning for Cost-Effective Allocation of Development Aid (Milan Kuzmanovic et al., 2024)

{{<citation>}}

Milan Kuzmanovic, Dennis Frauen, Tobias Hatt, Stefan Feuerriegel. (2024)  
**Causal Machine Learning for Cost-Effective Allocation of Development Aid**  

---
Primary Category: stat.ML  
Categories: cs-LG, stat-ML, stat.ML  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16986v2)  

---


**ABSTRACT**  
The Sustainable Development Goals (SDGs) of the United Nations provide a blueprint of a better future by 'leaving no one behind', and, to achieve the SDGs by 2030, poor countries require immense volumes of development aid. In this paper, we develop a causal machine learning framework for predicting heterogeneous treatment effects of aid disbursements to inform effective aid allocation. Specifically, our framework comprises three components: (i) a balancing autoencoder that uses representation learning to embed high-dimensional country characteristics while addressing treatment selection bias; (ii) a counterfactual generator to compute counterfactual outcomes for varying aid volumes to address small sample-size settings; and (iii) an inference model that is used to predict heterogeneous treatment-response curves. We demonstrate the effectiveness of our framework using data with official development aid earmarked to end HIV/AIDS in 105 countries, amounting to more than USD 5.2 billion. For this, we first show that our framework successfully computes heterogeneous treatment-response curves using semi-synthetic data. Then, we demonstrate our framework using real-world HIV data. Our framework points to large opportunities for a more effective aid allocation, suggesting that the total number of new HIV infections could be reduced by up to 3.3% (~50,000 cases) compared to the current allocation practice.

{{</citation>}}


## cs.SD (3)



### (144/162) Proactive Detection of Voice Cloning with Localized Watermarking (Robin San Roman et al., 2024)

{{<citation>}}

Robin San Roman, Pierre Fernandez, Alexandre Défossez, Teddy Furon, Tuan Tran, Hady Elsahar. (2024)  
**Proactive Detection of Voice Cloning with Localized Watermarking**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-CR, cs-SD, cs.SD  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17264v1)  

---


**ABSTRACT**  
In the rapidly evolving field of speech generative models, there is a pressing need to ensure audio authenticity against the risks of voice cloning. We present AudioSeal, the first audio watermarking technique designed specifically for localized detection of AI-generated speech. AudioSeal employs a generator/detector architecture trained jointly with a localization loss to enable localized watermark detection up to the sample level, and a novel perceptual loss inspired by auditory masking, that enables AudioSeal to achieve better imperceptibility. AudioSeal achieves state-of-the-art performance in terms of robustness to real life audio manipulations and imperceptibility based on automatic and human evaluation metrics. Additionally, AudioSeal is designed with a fast, single-pass detector, that significantly surpasses existing models in speed - achieving detection up to two orders of magnitude faster, making it ideal for large-scale and real-time applications.

{{</citation>}}


### (145/162) SpeechBERTScore: Reference-Aware Automatic Evaluation of Speech Generation Leveraging NLP Evaluation Metrics (Takaaki Saeki et al., 2024)

{{<citation>}}

Takaaki Saeki, Soumi Maiti, Shinnosuke Takamichi, Shinji Watanabe, Hiroshi Saruwatari. (2024)  
**SpeechBERTScore: Reference-Aware Automatic Evaluation of Speech Generation Leveraging NLP Evaluation Metrics**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: BERT, BLEU, NLP  
[Paper Link](http://arxiv.org/abs/2401.16812v1)  

---


**ABSTRACT**  
While subjective assessments have been the gold standard for evaluating speech generation, there is a growing need for objective metrics that are highly correlated with human subjective judgments due to their cost efficiency. This paper proposes reference-aware automatic evaluation methods for speech generation inspired by evaluation metrics in natural language processing. The proposed SpeechBERTScore computes the BERTScore for self-supervised dense speech features of the generated and reference speech, which can have different sequential lengths. We also propose SpeechBLEU and SpeechTokenDistance, which are computed on speech discrete tokens. The evaluations on synthesized speech show that our method correlates better with human subjective ratings than mel cepstral distortion and a recent mean opinion score prediction model. Also, they are effective in noisy speech evaluation and have cross-lingual applicability.

{{</citation>}}


### (146/162) PBSCSR: The Piano Bootleg Score Composer Style Recognition Dataset (Arhan Jain et al., 2024)

{{<citation>}}

Arhan Jain, Alec Bunn, TJ Tsai. (2024)  
**PBSCSR: The Piano Bootleg Score Composer Style Recognition Dataset**  

---
Primary Category: cs.SD  
Categories: cs-LG, cs-SD, cs.SD, eess-AS  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2401.16803v1)  

---


**ABSTRACT**  
This article motivates, describes, and presents the PBSCSR dataset for studying composer style recognition of piano sheet music. Our overarching goal was to create a dataset for studying composer style recognition that is "as accessible as MNIST and as challenging as ImageNet." To achieve this goal, we sample fixed-length bootleg score fragments from piano sheet music images on IMSLP. The dataset itself contains 40,000 62x64 bootleg score images for a 9-way classification task, 100,000 62x64 bootleg score images for a 100-way classification task, and 29,310 unlabeled variable-length bootleg score images for pretraining. The labeled data is presented in a form that mirrors MNIST images, in order to make it extremely easy to visualize, manipulate, and train models in an efficient manner. Additionally, we include relevant metadata to allow access to the underlying raw sheet music images and other related data on IMSLP. We describe several research tasks that could be studied with the dataset, including variations of composer style recognition in a few-shot or zero-shot setting. For tasks that have previously proposed models, we release code and baseline results for future works to compare against. We also discuss open research questions that the PBSCSR data is especially well suited to facilitate research on and areas of fruitful exploration in future work.

{{</citation>}}


## cs.IR (4)



### (147/162) Data-efficient Fine-tuning for LLM-based Recommendation (Xinyu Lin et al., 2024)

{{<citation>}}

Xinyu Lin, Wenjie Wang, Yongqi Li, Shuo Yang, Fuli Feng, Yinwei Wei, Tat-Seng Chua. (2024)  
**Data-efficient Fine-tuning for LLM-based Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17197v1)  

---


**ABSTRACT**  
Leveraging Large Language Models (LLMs) for recommendation has recently garnered considerable attention, where fine-tuning plays a key role in LLMs' adaptation. However, the cost of fine-tuning LLMs on rapidly expanding recommendation data limits their practical application. To address this challenge, few-shot fine-tuning offers a promising approach to quickly adapt LLMs to new recommendation data. We propose the task of data pruning for efficient LLM-based recommendation, aimed at identifying representative samples tailored for LLMs' few-shot fine-tuning. While coreset selection is closely related to the proposed task, existing coreset selection methods often rely on suboptimal heuristic metrics or entail costly optimization on large-scale recommendation data.   To tackle these issues, we introduce two objectives for the data pruning task in the context of LLM-based recommendation: 1) high accuracy aims to identify the influential samples that can lead to high overall performance; and 2) high efficiency underlines the low costs of the data pruning process. To pursue the two objectives, we propose a novel data pruning method based on two scores, i.e., influence score and effort score, to efficiently identify the influential samples. Particularly, the influence score is introduced to accurately estimate the influence of sample removal on the overall performance. To achieve low costs of the data pruning process, we use a small-sized surrogate model to replace LLMs to obtain the influence score. Considering the potential gap between the surrogate model and LLMs, we further propose an effort score to prioritize some hard samples specifically for LLMs. Empirical results on three real-world datasets validate the effectiveness of our proposed method. In particular, the proposed method uses only 2% samples to surpass the full data fine-tuning, reducing time costs by 97%.

{{</citation>}}


### (148/162) Re3val: Reinforced and Reranked Generative Retrieval (EuiYul Song et al., 2024)

{{<citation>}}

EuiYul Song, Sangryul Kim, Haeju Lee, Joonkee Kim, James Thorne. (2024)  
**Re3val: Reinforced and Reranked Generative Retrieval**  

---
Primary Category: cs.IR  
Categories: 94C06, H-3-3, cs-IR, cs.IR  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2401.16979v1)  

---


**ABSTRACT**  
Generative retrieval models encode pointers to information in a corpus as an index within the model's parameters. These models serve as part of a larger pipeline, where retrieved information conditions generation for knowledge-intensive NLP tasks. However, we identify two limitations: the generative retrieval does not account for contextual information. Secondly, the retrieval can't be tuned for the downstream readers as decoding the page title is a non-differentiable operation. This paper introduces Re3val, trained with generative reranking and reinforcement learning using limited data. Re3val leverages context acquired via Dense Passage Retrieval to rerank the retrieved page titles and utilizes REINFORCE to maximize rewards generated by constrained decoding. Additionally, we generate questions from our pre-training dataset to mitigate epistemic uncertainty and bridge the domain gap between the pre-training and fine-tuning datasets. Subsequently, we extract and rerank contexts from the KILT database using the rerank page titles. Upon grounding the top five reranked contexts, Re3val demonstrates the Top 1 KILT scores compared to all other generative retrieval models across five KILT datasets.

{{</citation>}}


### (149/162) Detecting LLM-Assisted Writing in Scientific Communication: Are We There Yet? (Teddy Lazebnik et al., 2024)

{{<citation>}}

Teddy Lazebnik, Ariel Rosenfeld. (2024)  
**Detecting LLM-Assisted Writing in Scientific Communication: Are We There Yet?**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs.IR  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2401.16807v1)  

---


**ABSTRACT**  
Large Language Models (LLMs), exemplified by ChatGPT, have significantly reshaped text generation, particularly in the realm of writing assistance. While ethical considerations underscore the importance of transparently acknowledging LLM use, especially in scientific communication, genuine acknowledgment remains infrequent. A potential avenue to encourage accurate acknowledging of LLM-assisted writing involves employing automated detectors. Our evaluation of four cutting-edge LLM-generated text detectors reveals their suboptimal performance compared to a simple ad-hoc detector designed to identify abrupt writing style changes around the time of LLM proliferation. We contend that the development of specialized detectors exclusively dedicated to LLM-assisted writing detection is necessary. Such detectors could play a crucial role in fostering more authentic recognition of LLM involvement in scientific communication, addressing the current challenges in acknowledgment practices.

{{</citation>}}


### (150/162) AutoIE: An Automated Framework for Information Extraction from Scientific Literature (Yangyang Liu et al., 2024)

{{<citation>}}

Yangyang Liu, Shoubin Li. (2024)  
**AutoIE: An Automated Framework for Information Extraction from Scientific Literature**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-CE, cs-IR, cs.IR  
Keywords: BERT, Information Extraction  
[Paper Link](http://arxiv.org/abs/2401.16672v1)  

---


**ABSTRACT**  
In the rapidly evolving field of scientific research, efficiently extracting key information from the burgeoning volume of scientific papers remains a formidable challenge. This paper introduces an innovative framework designed to automate the extraction of vital data from scientific PDF documents, enabling researchers to discern future research trajectories more readily. AutoIE uniquely integrates four novel components: (1) A multi-semantic feature fusion-based approach for PDF document layout analysis; (2) Advanced functional block recognition in scientific texts; (3) A synergistic technique for extracting and correlating information on molecular sieve synthesis; (4) An online learning paradigm tailored for molecular sieve literature. Our SBERT model achieves high Marco F1 scores of 87.19 and 89.65 on CoNLL04 and ADE datasets. In addition, a practical application of AutoIE in the petrochemical molecular sieve synthesis domain demonstrates its efficacy, evidenced by an impressive 78\% accuracy rate. This research paves the way for enhanced data management and interpretation in molecular sieve synthesis. It is a valuable asset for seasoned experts and newcomers in this specialized field.

{{</citation>}}


## cs.SE (4)



### (151/162) GAISSALabel: A tool for energy labeling of ML models (Pau Duran et al., 2024)

{{<citation>}}

Pau Duran, Joel Castaño, Cristina Gómez, Silverio Martínez-Fernández. (2024)  
**GAISSALabel: A tool for energy labeling of ML models**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17150v1)  

---


**ABSTRACT**  
Background: The increasing environmental impact of Information Technologies, particularly in Machine Learning (ML), highlights the need for sustainable practices in software engineering. The escalating complexity and energy consumption of ML models need tools for assessing and improving their energy efficiency. Goal: This paper introduces GAISSALabel, a web-based tool designed to evaluate and label the energy efficiency of ML models. Method: GAISSALabel is a technology transfer development from a former research on energy efficiency classification of ML, consisting of a holistic tool for assessing both the training and inference phases of ML models, considering various metrics such as power draw, model size efficiency, CO2e emissions and more. Results: GAISSALabel offers a labeling system for energy efficiency, akin to labels on consumer appliances, making it accessible to ML stakeholders of varying backgrounds. The tool's adaptability allows for customization in the proposed labeling system, ensuring its relevance in the rapidly evolving ML field. Conclusions: GAISSALabel represents a significant step forward in sustainable software engineering, offering a solution for balancing high-performance ML models with environmental impacts. The tool's effectiveness and market relevance will be further assessed through planned evaluations using the Technology Acceptance Model.

{{</citation>}}


### (152/162) Towards Generating Executable Metamorphic Relations Using Large Language Models (Seung Yeob Shin et al., 2024)

{{<citation>}}

Seung Yeob Shin, Fabrizio Pastore, Domenico Bianculli, Alexandra Baicoianu. (2024)  
**Towards Generating Executable Metamorphic Relations Using Large Language Models**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17019v1)  

---


**ABSTRACT**  
Metamorphic testing (MT) has proven to be a successful solution to automating testing and addressing the oracle problem. However, it entails manually deriving metamorphic relations (MRs) and converting them into an executable form; these steps are time-consuming and may prevent the adoption of MT. In this paper, we propose an approach for automatically deriving executable MRs (EMRs) from requirements using large language models (LLMs). Instead of merely asking the LLM to produce EMRs, our approach relies on a few-shot prompting strategy to instruct the LLM to perform activities in the MT process, by providing requirements and API specifications, as one would do with software engineers. To assess the feasibility of our approach, we conducted a questionnaire-based survey in collaboration with Siemens Industry Software, focusing on four of their software applications. Additionally, we evaluated the accuracy of the generated EMRs for a web application. The outcomes of our study are highly promising, as they demonstrate the capability of our approach to generate MRs and EMRs that are both comprehensible and pertinent for testing purposes.

{{</citation>}}


### (153/162) Depends-Kotlin: A Cross-Language Kotlin Dependency Extractor (Qiong Feng et al., 2024)

{{<citation>}}

Qiong Feng, Xiaotian Ma, Huan Ji, Peng Liang. (2024)  
**Depends-Kotlin: A Cross-Language Kotlin Dependency Extractor**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2401.16865v1)  

---


**ABSTRACT**  
Since Google introduced Kotlin as an official programming language for developing Android apps in 2017, Kotlin has gained widespread adoption in Android development. However, compared to Java, there is limited support for Kotlin code dependency analysis, which is the foundation to software analysis. To bridge this gap, we developed Depends-Kotlin to extract entities and their dependencies in Kotlin source code. Not only does Depends-Kotlin support extracting entities' dependencies in Kotlin code, but it can also extract dependency relations between Kotlin and Java. The extraction of such cross-language dependencies can help developers understand the migration process from Java to Kotlin. Additionally, we used a Java project with confirmed dependencies as a benchmark and converted this project to two projects: Kotlin-only and a combination of Kotlin and Java. The dependencies in these two projects were then extracted using our tool. The consistency observed among dependency relations in all three projects confirms the accuracy of Depends-Kotlin. Furthermore, the performance of Depends-Kotlin was assessed using another three projects of varying sizes. The source code of Depends-Kotlin and the dataset used in this demo paper have been uploaded to https://github.com/XYZboom/depends-kotlin. We also provided a screencast presenting Depends-Kotlin https://youtu.be/daZuXOwn1Ls.

{{</citation>}}


### (154/162) IRCoCo: Immediate Rewards-Guided Deep Reinforcement Learning for Code Completion (Bolun Li et al., 2024)

{{<citation>}}

Bolun Li, Zhihong Sun, Tao Huang, Hongyu Zhang, Yao Wan, Ge Li, Zhi Jin, Chen Lyu. (2024)  
**IRCoCo: Immediate Rewards-Guided Deep Reinforcement Learning for Code Completion**  

---
Primary Category: cs.SE  
Categories: D-2-2, cs-SE, cs.SE  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2401.16637v2)  

---


**ABSTRACT**  
Code completion aims to enhance programming productivity by predicting potential code based on the current programming context. Recently, pretrained language models (LMs) have become prominent in this field. Various approaches have been proposed to fine-tune LMs using supervised fine-tuning (SFT) techniques for code completion. However, the inherent exposure bias of these models can cause errors to accumulate early in the sequence completion, leading to even more errors in subsequent completions. To address this problem, deep reinforcement learning (DRL) is an alternative technique for fine-tuning LMs for code completion, which can improve the generalization capabilities and overall performance. Nevertheless, integrating DRL-based strategies into code completion faces two major challenges: 1) The dynamic nature of the code context requires the completion model to quickly adapt to changes, which poses difficulties for conventional DRL strategies that focus on delayed rewarding of the final code state. 2) It is difficult to evaluate the correctness of partial code, thus the reward redistribution-based strategies cannot be adapted to code completion. To tackle these challenges, we propose IRCoCo, a code completion-specific DRL-based fine-tuning framework. This framework is designed to provide immediate rewards as feedback for detecting dynamic context changes arising from continuous edits during code completion. With the aid of immediate feedback, the fine-tuned LM can gain a more precise understanding of the current context, thereby enabling effective adjustment of the LM and optimizing code completion in a more refined manner. Experimental results demonstrate that fine-tuning pretrained LMs with IRCoCo leads to significant improvements in the code completion task, outperforming both SFT-based and other DRL-based baselines.

{{</citation>}}


## cs.MS (1)



### (155/162) Reproducibility, energy efficiency and performance of pseudorandom number generators in machine learning: a comparative study of python, numpy, tensorflow, and pytorch implementations (Benjamin Antunes et al., 2024)

{{<citation>}}

Benjamin Antunes, David R. C Hill. (2024)  
**Reproducibility, energy efficiency and performance of pseudorandom number generators in machine learning: a comparative study of python, numpy, tensorflow, and pytorch implementations**  

---
Primary Category: cs.MS  
Categories: cs-LG, cs-MS, cs.MS  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.17345v1)  

---


**ABSTRACT**  
Pseudo-Random Number Generators (PRNGs) have become ubiquitous in machine learning technologies because they are interesting for numerous methods. The field of machine learning holds the potential for substantial advancements across various domains, as exemplified by recent breakthroughs in Large Language Models (LLMs). However, despite the growing interest, persistent concerns include issues related to reproducibility and energy consumption. Reproducibility is crucial for robust scientific inquiry and explainability, while energy efficiency underscores the imperative to conserve finite global resources. This study delves into the investigation of whether the leading Pseudo-Random Number Generators (PRNGs) employed in machine learning languages, libraries, and frameworks uphold statistical quality and numerical reproducibility when compared to the original C implementation of the respective PRNG algorithms. Additionally, we aim to evaluate the time efficiency and energy consumption of various implementations. Our experiments encompass Python, NumPy, TensorFlow, and PyTorch, utilizing the Mersenne Twister, PCG, and Philox algorithms. Remarkably, we verified that the temporal performance of machine learning technologies closely aligns with that of C-based implementations, with instances of achieving even superior performances. On the other hand, it is noteworthy that ML technologies consumed only 10% more energy than their C-implementation counterparts. However, while statistical quality was found to be comparable, achieving numerical reproducibility across different platforms for identical seeds and algorithms was not achieved.

{{</citation>}}


## eess.IV (2)



### (156/162) H-SynEx: Using synthetic images and ultra-high resolution ex vivo MRI for hypothalamus subregion segmentation (Livia Rodrigues et al., 2024)

{{<citation>}}

Livia Rodrigues, Martina Bocchetta, Oula Puonti, Douglas Greve, Ana Carolina Londe, Marcondes França, Simone Appenzeller, Juan Eugenio Iglesias, Leticia Rittner. (2024)  
**H-SynEx: Using synthetic images and ultra-high resolution ex vivo MRI for hypothalamus subregion segmentation**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.17104v1)  

---


**ABSTRACT**  
Purpose: To develop a method for automated segmentation of hypothalamus subregions informed by ultra-high resolution ex vivo magnetic resonance images (MRI), which generalizes across MRI sequences and resolutions without retraining.   Materials and Methods: We trained our deep learning method, H-synEx, with synthetic images derived from label maps built from ultra-high resolution ex vivo MRI scans, which enables finer-grained manual segmentation when compared with 1mm isometric in vivo images. We validated this retrospective study using 1535 in vivo images from six datasets and six MRI sequences. The quantitative evaluation used the Dice Coefficient (DC) and Average Hausdorff distance (AVD). Statistical analysis compared hypothalamic subregion volumes in controls, Alzheimer's disease (AD), and behavioral variant frontotemporal dementia (bvFTD) subjects using the area under the curve (AUC) and Wilcoxon rank sum test.   Results: H-SynEx can segment the hypothalamus across various MRI sequences, encompassing FLAIR sequences with significant slice spacing (5mm). Using hypothalamic volumes on T1w images to distinguish control from AD and bvFTD patients, we observed AUC values of 0.74 and 0.79 respectively. Additionally, AUC=0.66 was found for volume variation on FLAIR scans when comparing control and non-patients.   Conclusion: Our results show that H-SynEx successfully leverages information from ultra-high resolution scans to segment in vivo from different MRI sequences such as T1w, T2w, PD, qT1, FA, and FLAIR. We also found that our automated segmentation was able to discriminate controls versus patients on FLAIR images with 5mm spacing. H-SynEx is openly available at https://github.com/liviamarodrigues/hsynex.

{{</citation>}}


### (157/162) A Literature Review on Fetus Brain Motion Correction in MRI (Haoran Zhang et al., 2024)

{{<citation>}}

Haoran Zhang, Yun Wang. (2024)  
**A Literature Review on Fetus Brain Motion Correction in MRI**  

---
Primary Category: eess.IV  
Categories: cs-LG, eess-IV, eess.IV  
Keywords: LSTM, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2401.16782v1)  

---


**ABSTRACT**  
This paper provides a comprehensive review of the latest advancements in fetal motion correction in MRI. We delve into various contemporary methodologies and technological advancements aimed at overcoming these challenges. It includes traditional 3D fetal MRI correction methods like Slice to Volume Registration (SVR), deep learning-based techniques such as Convolutional Neural Networks (CNNs), Long Short-Term Memory (LSTM) Networks, Transformers, Generative Adversarial Networks (GANs) and most recent advancements of Diffusion Models. The insights derived from this literature review reflect a thorough understanding of both the technical intricacies and practical implications of fetal motion in MRI studies, offering a reasoned perspective on potential solutions and future improvements in this field.

{{</citation>}}


## astro-ph.IM (1)



### (158/162) Selection of gamma events from IACT images with deep learning methods (E. O. Gres et al., 2024)

{{<citation>}}

E. O. Gres, A. P. Kryukov, A. P. Demichev, J. J. Dubenskaya, S. P. Polyakov, A. A. Vlaskina, D. P. Zhurov. (2024)  
**Selection of gamma events from IACT images with deep learning methods**  

---
Primary Category: astro-ph.IM  
Categories: astro-ph-HE, astro-ph-IM, astro-ph.IM, cs-LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2401.16981v1)  

---


**ABSTRACT**  
Imaging Atmospheric Cherenkov Telescopes (IACTs) of gamma ray observatory TAIGA detect the Extesnive Air Showers (EASs) originating from the cosmic or gamma rays interactions with the atmosphere. Thereby, telescopes obtain images of the EASs. The ability to segregate gamma rays images from the hadronic cosmic ray background is one of the main features of this type of detectors. However, in actual IACT observations simultaneous observation of the background and the source of gamma ray is needed. This observation mode (called wobbling) modifies images of events, which affects the quality of selection by neural networks.   Thus, in this work, the results of the application of neural networks (NN) for image classification task on Monte Carlo (MC) images of TAIGA-IACTs are presented. The wobbling mode is considered together with the image adaptation for adequate analysis by NNs. Simultaneously, we explore several neural network structures that classify events both directly from images or through Hillas parameters extracted from images. In addition, by employing NNs, MC simulation data are used to evaluate the quality of the segregation of rare gamma events with the account of all necessary image modifications.

{{</citation>}}


## eess.AS (1)



### (159/162) Identifying False Content and Hate Speech in Sinhala YouTube Videos by Analyzing the Audio (W. A. K. M. Wickramaarachchi et al., 2024)

{{<citation>}}

W. A. K. M. Wickramaarachchi, Sameeri Sathsara Subasinghe, K. K. Rashani Tharushika Wijerathna, A. Sahashra Udani Athukorala, Lakmini Abeywardhana, A. Karunasena. (2024)  
**Identifying False Content and Hate Speech in Sinhala YouTube Videos by Analyzing the Audio**  

---
Primary Category: eess.AS  
Categories: cs-AI, cs-CL, cs-LG, cs-SD, eess-AS, eess.AS  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2402.01752v1)  

---


**ABSTRACT**  
YouTube faces a global crisis with the dissemination of false information and hate speech. To counter these issues, YouTube has implemented strict rules against uploading content that includes false information or promotes hate speech. While numerous studies have been conducted to reduce offensive English-language content, there's a significant lack of research on Sinhala content. This study aims to address the aforementioned gap by proposing a solution to minimize the spread of violence and misinformation in Sinhala YouTube videos. The approach involves developing a rating system that assesses whether a video contains false information by comparing the title and description with the audio content and evaluating whether the video includes hate speech. The methodology encompasses several steps, including audio extraction using the Pytube library, audio transcription via the fine-tuned Whisper model, hate speech detection employing the distilroberta-base model and a text classification LSTM model, and text summarization through the fine-tuned BART-Large- XSUM model. Notably, the Whisper model achieved a 48.99\% word error rate, while the distilroberta-base model demonstrated an F1 score of 0.856 and a recall value of 0.861 in comparison to the LSTM model, which exhibited signs of overfitting.

{{</citation>}}


## cs.PL (1)



### (160/162) Enhancing Translation Validation of Compiler Transformations with Large Language Models (Yanzhao Wang et al., 2024)

{{<citation>}}

Yanzhao Wang, Fei Xie. (2024)  
**Enhancing Translation Validation of Compiler Transformations with Large Language Models**  

---
Primary Category: cs.PL  
Categories: cs-PL, cs-SE, cs.PL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.16797v2)  

---


**ABSTRACT**  
This paper presents a framework that integrates Large Language Models (LLMs) into translation validation, targeting LLVM compiler transformations where formal verification tools fall short. Our framework first utilizes existing formal verification tools for translation validation. In this work, we use Alive2, a well-known tool in LLVM compiler verification, as an example. When formal verification tools are unable to confirm a transformation's soundness, our framework employs fine-tuned LLMs for prediction. It then applies fuzzing to transformations predicted as potentially unsound by the LLMs due to return values or memory inconsistencies, aiming to find counterexamples. In cases where transformations are unsound for other reasons or sound, or if no counterexamples emerge, the framework directly reports these outcomes without further fuzzing. This methodology has shown effectiveness in complex application such as deep-learning accelerator designs, where traditional formal verification tools struggle.

{{</citation>}}


## cs.AI (1)



### (161/162) Recovering Mental Representations from Large Language Models with Markov Chain Monte Carlo (Jian-Qiao Zhu et al., 2024)

{{<citation>}}

Jian-Qiao Zhu, Haijiang Yan, Thomas L. Griffiths. (2024)  
**Recovering Mental Representations from Large Language Models with Markov Chain Monte Carlo**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2401.16657v1)  

---


**ABSTRACT**  
Simulating sampling algorithms with people has proven a useful method for efficiently probing and understanding their mental representations. We propose that the same methods can be used to study the representations of Large Language Models (LLMs). While one can always directly prompt either humans or LLMs to disclose their mental representations introspectively, we show that increased efficiency can be achieved by using LLMs as elements of a sampling algorithm. We explore the extent to which we recover human-like representations when LLMs are interrogated with Direct Sampling and Markov chain Monte Carlo (MCMC). We found a significant increase in efficiency and performance using adaptive sampling algorithms based on MCMC. We also highlight the potential of our method to yield a more general method of conducting Bayesian inference \textit{with} LLMs.

{{</citation>}}


## cs.NI (1)



### (162/162) Large Multi-Modal Models (LMMs) as Universal Foundation Models for AI-Native Wireless Systems (Shengzhe Xu et al., 2024)

{{<citation>}}

Shengzhe Xu, Christo Kurisummoottil Thomas, Omar Hashash, Nikhil Muralidhar, Walid Saad, Naren Ramakrishnan. (2024)  
**Large Multi-Modal Models (LMMs) as Universal Foundation Models for AI-Native Wireless Systems**  

---
Primary Category: cs.NI  
Categories: cs-AI, cs-CL, cs-IT, cs-LG, cs-NI, cs.NI, math-IT  
Keywords: AI, NLP  
[Paper Link](http://arxiv.org/abs/2402.01748v1)  

---


**ABSTRACT**  
Large language models (LLMs) and foundation models have been recently touted as a game-changer for 6G systems. However, recent efforts on LLMs for wireless networks are limited to a direct application of existing language models that were designed for natural language processing (NLP) applications. To address this challenge and create wireless-centric foundation models, this paper presents a comprehensive vision on how to design universal foundation models that are tailored towards the deployment of artificial intelligence (AI)-native networks. Diverging from NLP-based foundation models, the proposed framework promotes the design of large multi-modal models (LMMs) fostered by three key capabilities: 1) processing of multi-modal sensing data, 2) grounding of physical symbol representations in real-world wireless systems using causal reasoning and retrieval-augmented generation (RAG), and 3) enabling instructibility from the wireless environment feedback to facilitate dynamic network adaptation thanks to logical and mathematical reasoning facilitated by neuro-symbolic AI. In essence, these properties enable the proposed LMM framework to build universal capabilities that cater to various cross-layer networking tasks and alignment of intents across different domains. Preliminary results from experimental evaluation demonstrate the efficacy of grounding using RAG in LMMs, and showcase the alignment of LMMs with wireless system designs. Furthermore, the enhanced rationale exhibited in the responses to mathematical questions by LMMs, compared to vanilla LLMs, demonstrates the logical and mathematical reasoning capabilities inherent in LMMs. Building on those results, we present a sequel of open questions and challenges for LMMs. We then conclude with a set of recommendations that ignite the path towards LMM-empowered AI-native systems.

{{</citation>}}
