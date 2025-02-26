---
draft: false
title: "arXiv @ 2023.12.13"
date: 2023-12-13
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.12.13"
    identifier: arxiv_20231213
    parent: 202312_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (34)](#cslg-34)
- [cs.RO (5)](#csro-5)
- [cs.CV (45)](#cscv-45)
- [cs.CY (1)](#cscy-1)
- [physics.space-ph (1)](#physicsspace-ph-1)
- [cs.AI (17)](#csai-17)
- [cs.IT (1)](#csit-1)
- [cs.IR (3)](#csir-3)
- [cs.HC (1)](#cshc-1)
- [cs.CL (23)](#cscl-23)
- [physics.soc-ph (1)](#physicssoc-ph-1)
- [math.OC (1)](#mathoc-1)
- [cs.NE (1)](#csne-1)
- [eess.SP (3)](#eesssp-3)
- [cs.SD (4)](#cssd-4)
- [eess.IV (3)](#eessiv-3)
- [cs.CR (6)](#cscr-6)
- [cs.DL (1)](#csdl-1)
- [cs.DB (1)](#csdb-1)
- [cs.SE (3)](#csse-3)
- [cs.NI (1)](#csni-1)
- [eess.AS (2)](#eessas-2)
- [eess.SY (1)](#eesssy-1)
- [quant-ph (1)](#quant-ph-1)
- [cs.LO (1)](#cslo-1)

## cs.LG (34)



### (1/161) DYAD: A Descriptive Yet Abjuring Density efficient approximation to linear neural network layers (Sarin Chandy et al., 2023)

{{<citation>}}

Sarin Chandy, Varun Gangal, Yi Yang, Gabriel Maggiotti. (2023)  
**DYAD: A Descriptive Yet Abjuring Density efficient approximation to linear neural network layers**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: GLUE, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06881v1)  

---


**ABSTRACT**  
We devise, implement and performance-asses DYAD, a layer which can serve as a faster and more memory-efficient approximate replacement for linear layers, (nn.Linear() in Pytorch). These layers appear in common subcomponents, such as in the ff module of Transformers. DYAD is based on a bespoke near-sparse matrix structure which approximates the dense "weight" matrix W that matrix-multiplies the input in the typical realization of such a layer, a.k.a DENSE. Our alternative near-sparse matrix structure is decomposable to a sum of 2 matrices permutable to a block-sparse counterpart. These can be represented as 3D tensors, which in unison allow a faster execution of matrix multiplication with the mini-batched input matrix X compared to DENSE (O(rows(W ) x cols(W )) --> O( rows(W ) x cols(W ) # of blocks )). As the crux of our experiments, we pretrain both DYAD and DENSE variants of 2 sizes of the OPT arch and 1 size of the Pythia arch, including at different token scales of the babyLM benchmark. We find DYAD to be competitive (>= 90%) of DENSE performance on zero-shot (e.g. BLIMP), few-shot (OPENLM) and finetuning (GLUE) benchmarks, while being >=7-15% faster to train on-GPU even at 125m scale, besides surfacing larger speedups at increasing scale and model width.

{{</citation>}}


### (2/161) A Novel Differentiable Loss Function for Unsupervised Graph Neural Networks in Graph Partitioning (Vivek Chaudhary, 2023)

{{<citation>}}

Vivek Chaudhary. (2023)  
**A Novel Differentiable Loss Function for Unsupervised Graph Neural Networks in Graph Partitioning**  

---
Primary Category: cs.LG  
Categories: I-2-8, cs-LG, cs.LG  
Keywords: Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.06877v1)  

---


**ABSTRACT**  
In this paper, we explore the graph partitioning problem, a pivotal combina-torial optimization challenge with extensive applications in various fields such as science, technology, and business. Recognized as an NP-hard prob-lem, graph partitioning lacks polynomial-time algorithms for its resolution. Recently, there has been a burgeoning interest in leveraging machine learn-ing, particularly approaches like supervised, unsupervised, and reinforce-ment learning, to tackle such NP-hard problems. However, these methods face significant hurdles: supervised learning is constrained by the necessity of labeled solution instances, which are often computationally impractical to obtain; reinforcement learning grapples with instability in the learning pro-cess; and unsupervised learning contends with the absence of a differentia-ble loss function, a consequence of the discrete nature of most combinatorial optimization problems. Addressing these challenges, our research introduces a novel pipeline employing an unsupervised graph neural network to solve the graph partitioning problem. The core innovation of this study is the for-mulation of a differentiable loss function tailored for this purpose. We rigor-ously evaluate our methodology against contemporary state-of-the-art tech-niques, focusing on metrics: cuts and balance, and our findings reveal that our is competitive with these leading methods.

{{</citation>}}


### (3/161) Dozerformer: Sequence Adaptive Sparse Transformer for Multivariate Time Series Forecasting (Yifan Zhang et al., 2023)

{{<citation>}}

Yifan Zhang, Rui Wu, Sergiu M. Dascalu, Frederick C. Harris Jr. (2023)  
**Dozerformer: Sequence Adaptive Sparse Transformer for Multivariate Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Attention, Time Series, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06874v1)  

---


**ABSTRACT**  
Transformers have achieved remarkable performance in multivariate time series(MTS) forecasting due to their capability to capture long-term dependencies. However, the canonical attention mechanism has two key limitations: (1) its quadratic time complexity limits the sequence length, and (2) it generates future values from the entire historical sequence. To address this, we propose a Dozer Attention mechanism consisting of three sparse components: (1) Local, each query exclusively attends to keys within a localized window of neighboring time steps. (2) Stride, enables each query to attend to keys at predefined intervals. (3) Vary, allows queries to selectively attend to keys from a subset of the historical sequence. Notably, the size of this subset dynamically expands as forecasting horizons extend. Those three components are designed to capture essential attributes of MTS data, including locality, seasonality, and global temporal dependencies. Additionally, we present the Dozerformer Framework, incorporating the Dozer Attention mechanism for the MTS forecasting task. We evaluated the proposed Dozerformer framework with recent state-of-the-art methods on nine benchmark datasets and confirmed its superior performance. The code will be released after the manuscript is accepted.

{{</citation>}}


### (4/161) Improving age prediction: Utilizing LSTM-based dynamic forecasting for data augmentation in multivariate time series analysis (Yutong Gao et al., 2023)

{{<citation>}}

Yutong Gao, Charles A. Ellis, Vince D. Calhoun, Robyn L. Miller. (2023)  
**Improving age prediction: Utilizing LSTM-based dynamic forecasting for data augmentation in multivariate time series analysis**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2312.08383v1)  

---


**ABSTRACT**  
The high dimensionality and complexity of neuroimaging data necessitate large datasets to develop robust and high-performing deep learning models. However, the neuroimaging field is notably hampered by the scarcity of such datasets. In this work, we proposed a data augmentation and validation framework that utilizes dynamic forecasting with Long Short-Term Memory (LSTM) networks to enrich datasets. We extended multivariate time series data by predicting the time courses of independent component networks (ICNs) in both one-step and recursive configurations. The effectiveness of these augmented datasets was then compared with the original data using various deep learning models designed for chronological age prediction tasks. The results suggest that our approach improves model performance, providing a robust solution to overcome the challenges presented by the limited size of neuroimaging datasets.

{{</citation>}}


### (5/161) Multimodal Pretraining of Medical Time Series and Notes (Ryan King et al., 2023)

{{<citation>}}

Ryan King, Tianbao Yang, Bobak Mortazavi. (2023)  
**Multimodal Pretraining of Medical Time Series and Notes**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2312.06855v1)  

---


**ABSTRACT**  
Within the intensive care unit (ICU), a wealth of patient data, including clinical measurements and clinical notes, is readily available. This data is a valuable resource for comprehending patient health and informing medical decisions, but it also contains many challenges in analysis. Deep learning models show promise in extracting meaningful patterns, but they require extensive labeled data, a challenge in critical care. To address this, we propose a novel approach employing self-supervised pretraining, focusing on the alignment of clinical measurements and notes. Our approach combines contrastive and masked token prediction tasks during pretraining. Semi-supervised experiments on the MIMIC-III dataset demonstrate the effectiveness of our self-supervised pretraining. In downstream tasks, including in-hospital mortality prediction and phenotyping, our pretrained model outperforms baselines in settings where only a fraction of the data is labeled, emphasizing its ability to enhance ICU data analysis. Notably, our method excels in situations where very few labels are available, as evidenced by an increase in the AUC-ROC for in-hospital mortality by 0.17 and in AUC-PR for phenotyping by 0.1 when only 1% of labels are accessible. This work advances self-supervised learning in the healthcare domain, optimizing clinical insights from abundant yet challenging ICU data.

{{</citation>}}


### (6/161) Optimizing Likelihood-free Inference using Self-supervised Neural Symmetry Embeddings (Deep Chatterjee et al., 2023)

{{<citation>}}

Deep Chatterjee, Philip C. Harris, Maanas Goel, Malina Desai, Michael W. Coughlin, Erik Katsavounidis. (2023)  
**Optimizing Likelihood-free Inference using Self-supervised Neural Symmetry Embeddings**  

---
Primary Category: cs.LG  
Categories: astro-ph-IM, cs-LG, cs.LG  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2312.07615v1)  

---


**ABSTRACT**  
Likelihood-free inference is quickly emerging as a powerful tool to perform fast/effective parameter estimation. We demonstrate a technique of optimizing likelihood-free inference to make it even faster by marginalizing symmetries in a physical problem. In this approach, physical symmetries, for example, time-translation are learned using joint-embedding via self-supervised learning with symmetry data augmentations. Subsequently, parameter inference is performed using a normalizing flow where the embedding network is used to summarize the data before conditioning the parameters. We present this approach on two simple physical problems and we show faster convergence in a smaller number of parameters compared to a normalizing flow that does not use a pre-trained symmetry-informed representation.

{{</citation>}}


### (7/161) The unreasonable effectiveness of AI CADe polyp detectors to generalize to new countries (Joel Shor et al., 2023)

{{<citation>}}

Joel Shor, Hiro-o Yamano, Daisuke Tsurumaru, Yotami Intrator, Hiroki Kayama, Joe Ledsam, Atsushi Hamabe, Koji Ando, Mitsuhiko Ota, Haruei Ogino, Hiroshi Nakase, Kaho Kobayashi, Eiji Oki, Roman Goldenberg, Ehud Rivlin, Ichiro Takemasa. (2023)  
**The unreasonable effectiveness of AI CADe polyp detectors to generalize to new countries**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-CY, cs-LG, cs.LG  
Keywords: AI, Embedding  
[Paper Link](http://arxiv.org/abs/2312.06833v1)  

---


**ABSTRACT**  
$\textbf{Background and aims}$: Artificial Intelligence (AI) Computer-Aided Detection (CADe) is commonly used for polyp detection, but data seen in clinical settings can differ from model training. Few studies evaluate how well CADe detectors perform on colonoscopies from countries not seen during training, and none are able to evaluate performance without collecting expensive and time-intensive labels.   $\textbf{Methods}$: We trained a CADe polyp detector on Israeli colonoscopy videos (5004 videos, 1106 hours) and evaluated on Japanese videos (354 videos, 128 hours) by measuring the True Positive Rate (TPR) versus false alarms per minute (FAPM). We introduce a colonoscopy dissimilarity measure called "MAsked mediCal Embedding Distance" (MACE) to quantify differences between colonoscopies, without labels. We evaluated CADe on all Japan videos and on those with the highest MACE.   $\textbf{Results}$: MACE correctly quantifies that narrow-band imaging (NBI) and chromoendoscopy (CE) frames are less similar to Israel data than Japan whitelight (bootstrapped z-test, |z| > 690, p < $10^{-8}$ for both). Despite differences in the data, CADe performance on Japan colonoscopies was non-inferior to Israel ones without additional training (TPR at 0.5 FAPM: 0.957 and 0.972 for Israel and Japan; TPR at 1.0 FAPM: 0.972 and 0.989 for Israel and Japan; superiority test t > 45.2, p < $10^{-8}$). Despite not being trained on NBI or CE, TPR on those subsets were non-inferior to Japan overall (non-inferiority test t > 47.3, p < $10^{-8}$, $\delta$ = 1.5% for both).   $\textbf{Conclusion}$: Differences that prevent CADe detectors from performing well in non-medical settings do not degrade the performance of our AI CADe polyp detector when applied to data from a new country. MACE can help medical AI models internationalize by identifying the most "dissimilar" data on which to evaluate models.

{{</citation>}}


### (8/161) Model Breadcrumbs: Scaling Multi-Task Model Merging with Sparse Masks (MohammadReza Davari et al., 2023)

{{<citation>}}

MohammadReza Davari, Eugene Belilovsky. (2023)  
**Model Breadcrumbs: Scaling Multi-Task Model Merging with Sparse Masks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06795v1)  

---


**ABSTRACT**  
The rapid development of AI systems has been greatly influenced by the emergence of foundation models. A common approach for targeted problems involves fine-tuning these pre-trained foundation models for specific target tasks, resulting in a rapid spread of models fine-tuned across a diverse array of tasks. This work focuses on the problem of merging multiple fine-tunings of the same foundation model derived from a spectrum of auxiliary tasks. We introduce a new simple method, Model Breadcrumbs, which consists of a sparsely defined set of weights that carve out a trajectory within the weight space of a pre-trained model, enhancing task performance when traversed. These breadcrumbs are constructed by subtracting the weights from a pre-trained model before and after fine-tuning, followed by a sparsification process that eliminates weight outliers and negligible perturbations. Our experiments demonstrate the effectiveness of Model Breadcrumbs to simultaneously improve performance across multiple tasks. This contribution aligns with the evolving paradigm of updatable machine learning, reminiscent of the collaborative principles underlying open-source software development, fostering a community-driven effort to reliably update machine learning models. Our method is shown to be more efficient and unlike previous proposals does not require hyperparameter tuning for each new task added. Through extensive experimentation involving various models, tasks, and modalities we establish that integrating Model Breadcrumbs offers a simple, efficient, and highly effective approach for constructing multi-task models and facilitating updates to foundation models.

{{</citation>}}


### (9/161) Mixture-of-Linear-Experts for Long-term Time Series Forecasting (Ronghao Ni et al., 2023)

{{<citation>}}

Ronghao Ni, Zinan Lin, Shuaiqi Wang, Giulia Fanti. (2023)  
**Mixture-of-Linear-Experts for Long-term Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2312.06786v1)  

---


**ABSTRACT**  
Long-term time series forecasting (LTSF) aims to predict future values of a time series given the past values. The current state-of-the-art (SOTA) on this problem is attained in some cases by linear-centric models, which primarily feature a linear mapping layer. However, due to their inherent simplicity, they are not able to adapt their prediction rules to periodic changes in time series patterns. To address this challenge, we propose a Mixture-of-Experts-style augmentation for linear-centric models and propose Mixture-of-Linear-Experts (MoLE). Instead of training a single model, MoLE trains multiple linear-centric models (i.e., experts) and a router model that weighs and mixes their outputs. While the entire framework is trained end-to-end, each expert learns to specialize in a specific temporal pattern, and the router model learns to compose the experts adaptively. Experiments show that MoLE reduces forecasting error of linear-centric models, including DLinear, RLinear, and RMLP, in over 78% of the datasets and settings we evaluated. By using MoLE existing linear-centric models can achieve SOTA LTSF results in 68% of the experiments that PatchTST reports and we compare to, whereas existing single-head linear-centric models achieve SOTA results in only 25% of cases. Additionally, MoLE models achieve SOTA in all settings for the newly released Weather2K datasets.

{{</citation>}}


### (10/161) Gated Linear Attention Transformers with Hardware-Efficient Training (Songlin Yang et al., 2023)

{{<citation>}}

Songlin Yang, Bailin Wang, Yikang Shen, Rameswar Panda, Yoon Kim. (2023)  
**Gated Linear Attention Transformers with Hardware-Efficient Training**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Attention, LLaMA, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06635v2)  

---


**ABSTRACT**  
Transformers with linear attention allow for efficient parallel training but can simultaneously be formulated as an RNN with 2D (matrix-valued) hidden states, thus enjoying linear (with respect to output length) inference complexity. Recent works such as RetNet (Sun et al., 2023) and TransNormerLLM (Qin et al., 2023a) observe that adding a global decay term to the additive RNN update rule greatly improves performance, sometimes outperforming standard Transformers with softmax attention when trained at scale. In this work we show that adding a data-dependent gating mechanism further improves performance. We derive a parallel form of this gated linear attention layer that enables efficient training. However, a straightforward, numerically stable implementation of this parallel form requires generalized matrix multiplications in log-space for numerical stability, and thus cannot take advantage of tensor cores on modern GPUs which are optimized for standard matrix multiplications. We develop a hardware-efficient version of the parallel form that can still make use of tensor cores through block-parallel computations over sequence chunks. Experiments on moderate-scale language modeling (340M-parameter models trained on 15B tokens, 1.3B-parameter models trained on 100B tokens) show that gated linear attention (GLA) Transformers perform competitively against a strong LLaMA-architecture Transformer baseline (Touvron et al., 2023) as well as Mamba (Gu & Dao, 2023), a recently introduced state-space model with a data-dependent state transition mechanism. For training speed, our Triton-based implementation performs comparably to CUDA-optimized FlashAttention-2 (Dao, 2023) under the regular 2048 training length setting, while outperforming FlashAttention-2 when training on longer sequences beyond 4096.

{{</citation>}}


### (11/161) Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models (Avi Singh et al., 2023)

{{<citation>}}

Avi Singh, John D. Co-Reyes, Rishabh Agarwal, Ankesh Anand, Piyush Patil, Peter J. Liu, James Harrison, Jaehoon Lee, Kelvin Xu, Aaron Parisi, Abhishek Kumar, Alex Alemi, Alex Rizkowsky, Azade Nova, Ben Adlam, Bernd Bohnet, Gamaleldin Elsayed, Hanie Sedghi, Igor Mordatch, Isabelle Simpson, Izzeddin Gur, Jasper Snoek, Jeffrey Pennington, Jiri Hron, Kathleen Kenealy, Kevin Swersky, Kshiteej Mahajan, Laura Culp, Lechao Xiao, Maxwell L. Bileschi, Noah Constant, Roman Novak, Rosanne Liu, Tris Warkentin, Yundi Qian, Ethan Dyer, Behnam Neyshabur, Jascha Sohl-Dickstein, Noah Fiedel. (2023)  
**Beyond Human Data: Scaling Self-Training for Problem-Solving with Language Models**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Language Model, PaLM  
[Paper Link](http://arxiv.org/abs/2312.06585v2)  

---


**ABSTRACT**  
Fine-tuning language models~(LMs) on human-generated data remains a prevalent practice. However, the performance of such models is often limited by the quantity and diversity of high-quality human data. In this paper, we explore whether we can go beyond human data on tasks where we have access to scalar feedback, for example, on math problems where one can verify correctness. To do so, we investigate a simple self-training method based on expectation-maximization, which we call ReST$^{EM}$, where we (1) generate samples from the model and filter them using binary feedback, (2) fine-tune the model on these samples, and (3) repeat this process a few times. Testing on advanced MATH reasoning and APPS coding benchmarks using PaLM-2 models, we find that ReST$^{EM}$ scales favorably with model size and significantly surpasses fine-tuning only on human data. Overall, our findings suggest self-training with feedback can substantially reduce dependence on human-generated data.

{{</citation>}}


### (12/161) HyPE-GT: where Graph Transformers meet Hyperbolic Positional Encodings (Kushal Bose et al., 2023)

{{<citation>}}

Kushal Bose, Swagatam Das. (2023)  
**HyPE-GT: where Graph Transformers meet Hyperbolic Positional Encodings**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06576v1)  

---


**ABSTRACT**  
Graph Transformers (GTs) facilitate the comprehension of graph-structured data by calculating the self-attention of node pairs without considering node position information. To address this limitation, we introduce an innovative and efficient framework that introduces Positional Encodings (PEs) into the Transformer, generating a set of learnable positional encodings in the hyperbolic space, a non-Euclidean domain. This approach empowers us to explore diverse options for optimal selection of PEs for specific downstream tasks, leveraging hyperbolic neural networks or hyperbolic graph convolutional networks. Additionally, we repurpose these positional encodings to mitigate the impact of over-smoothing in deep Graph Neural Networks (GNNs). Comprehensive experiments on molecular benchmark datasets, co-author, and co-purchase networks substantiate the effectiveness of hyperbolic positional encodings in enhancing the performance of deep GNNs.

{{</citation>}}


### (13/161) Sparse but Strong: Crafting Adversarially Robust Graph Lottery Tickets (Subhajit Dutta Chowdhury et al., 2023)

{{<citation>}}

Subhajit Dutta Chowdhury, Zhiyu Ni, Qingyuan Peng, Souvik Kundu, Pierluigi Nuzzo. (2023)  
**Sparse but Strong: Crafting Adversarially Robust Graph Lottery Tickets**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2312.06568v1)  

---


**ABSTRACT**  
Graph Lottery Tickets (GLTs), comprising a sparse adjacency matrix and a sparse graph neural network (GNN), can significantly reduce the inference latency and compute footprint compared to their dense counterparts. Despite these benefits, their performance against adversarial structure perturbations remains to be fully explored. In this work, we first investigate the resilience of GLTs against different structure perturbation attacks and observe that they are highly vulnerable and show a large drop in classification accuracy. Based on this observation, we then present an adversarially robust graph sparsification (ARGS) framework that prunes the adjacency matrix and the GNN weights by optimizing a novel loss function capturing the graph homophily property and information associated with both the true labels of the train nodes and the pseudo labels of the test nodes. By iteratively applying ARGS to prune both the perturbed graph adjacency matrix and the GNN model weights, we can find adversarially robust graph lottery tickets that are highly sparse yet achieve competitive performance under different untargeted training-time structure attacks. Evaluations conducted on various benchmarks, considering different poisoning structure attacks, namely, PGD, MetaAttack, Meta-PGD, and PR-BCD demonstrate that the GLTs generated by ARGS can significantly improve the robustness, even when subjected to high levels of sparsity.

{{</citation>}}


### (14/161) Robust Graph Neural Network based on Graph Denoising (Victor M. Tenorio et al., 2023)

{{<citation>}}

Victor M. Tenorio, Samuel Rey, Antonio G. Marques. (2023)  
**Robust Graph Neural Network based on Graph Denoising**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, eess-SP  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.06557v1)  

---


**ABSTRACT**  
Graph Neural Networks (GNNs) have emerged as a notorious alternative to address learning problems dealing with non-Euclidean datasets. However, although most works assume that the graph is perfectly known, the observed topology is prone to errors stemming from observational noise, graph-learning limitations, or adversarial attacks. If ignored, these perturbations may drastically hinder the performance of GNNs. To address this limitation, this work proposes a robust implementation of GNNs that explicitly accounts for the presence of perturbations in the observed topology. For any task involving GNNs, our core idea is to i) solve an optimization problem not only over the learnable parameters of the GNN but also over the true graph, and ii) augment the fitting cost with a term accounting for discrepancies on the graph. Specifically, we consider a convolutional GNN based on graph filters and follow an alternating optimization approach to handle the (non-differentiable and constrained) optimization problem by combining gradient descent and projected proximal updates. The resulting algorithm is not limited to a particular type of graph and is amenable to incorporating prior information about the perturbations. Finally, we assess the performance of the proposed method through several numerical experiments.

{{</citation>}}


### (15/161) Transformers Implement Functional Gradient Descent to Learn Non-Linear Functions In Context (Xiang Cheng et al., 2023)

{{<citation>}}

Xiang Cheng, Yuxin Chen, Suvrit Sra. (2023)  
**Transformers Implement Functional Gradient Descent to Learn Non-Linear Functions In Context**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06528v2)  

---


**ABSTRACT**  
Many neural network architectures have been shown to be Turing Complete, and can thus implement arbitrary algorithms. However, Transformers are unique in that they can implement gradient-based learning algorithms \emph{under simple parameter configurations}. A line of recent work shows that linear Transformers naturally learn to implement gradient descent (GD) when trained on a linear regression in-context learning task. But the linearity assumption (either in the Transformer architecture or in the learning task) is far from realistic settings where non-linear activations crucially enable Transformers to learn complicated non-linear functions. In this paper, we provide theoretical and empirical evidence that non-linear Transformers can, and \emph{in fact do}, learn to implement learning algorithms to learn non-linear functions in context. Our results apply to a broad class of combinations of non-linear architectures, and non-linear in-context learning tasks. Interestingly, we show that the optimal choice of non-linear activation depends in a natural way on the non-linearity of the learning task.

{{</citation>}}


### (16/161) An Explainable Machine Learning Framework for the Accurate Diagnosis of Ovarian Cancer (Asif Newaz et al., 2023)

{{<citation>}}

Asif Newaz, Abdullah Taharat, Md Sakibul Islam, A. G. M. Fuad Hasan Akanda. (2023)  
**An Explainable Machine Learning Framework for the Accurate Diagnosis of Ovarian Cancer**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08381v1)  

---


**ABSTRACT**  
Ovarian cancer (OC) is one of the most prevalent types of cancer in women. Early and accurate diagnosis is crucial for the survival of the patients. However, the majority of women are diagnosed in advanced stages due to the lack of effective biomarkers and accurate screening tools. While previous studies sought a common biomarker, our study suggests different biomarkers for the premenopausal and postmenopausal populations. This can provide a new perspective in the search for novel predictors for the effective diagnosis of OC. Lack of explainability is one major limitation of current AI systems. The stochastic nature of the ML algorithms raises concerns about the reliability of the system as it is difficult to interpret the reasons behind the decisions. To increase the trustworthiness and accountability of the diagnostic system as well as to provide transparency and explanations behind the predictions, explainable AI has been incorporated into the ML framework. SHAP is employed to quantify the contributions of the selected biomarkers and determine the most discriminative features. A hybrid decision support system has been established that can eliminate the bottlenecks caused by the black-box nature of the ML algorithms providing a safe and trustworthy AI tool. The diagnostic accuracy obtained from the proposed system outperforms the existing methods as well as the state-of-the-art ROMA algorithm by a substantial margin which signifies its potential to be an effective tool in the differential diagnosis of OC.

{{</citation>}}


### (17/161) A GAN Approach for Node Embedding in Heterogeneous Graphs Using Subgraph Sampling (Hung Chun Hsu et al., 2023)

{{<citation>}}

Hung Chun Hsu, Bo-Jun Wu, Ming-Yi Hong, Che Lin, Chih-Yu Wang. (2023)  
**A GAN Approach for Node Embedding in Heterogeneous Graphs Using Subgraph Sampling**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: Amazon, Embedding, GNN  
[Paper Link](http://arxiv.org/abs/2312.06519v1)  

---


**ABSTRACT**  
Our research addresses class imbalance issues in heterogeneous graphs using graph neural networks (GNNs). We propose a novel method combining the strengths of Generative Adversarial Networks (GANs) with GNNs, creating synthetic nodes and edges that effectively balance the dataset. This approach directly targets and rectifies imbalances at the data level. The proposed framework resolves issues such as neglecting graph structures during data generation and creating synthetic structures usable with GNN-based classifiers in downstream tasks. It processes node and edge information concurrently, improving edge balance through node augmentation and subgraph sampling. Additionally, our framework integrates a threshold strategy, aiding in determining optimal edge thresholds during training without time-consuming parameter adjustments. Experiments on the Amazon and Yelp Review datasets highlight the effectiveness of the framework we proposed, especially in minority node identification, where it consistently outperforms baseline models across key performance metrics, demonstrating its potential in the field.

{{</citation>}}


### (18/161) Decoupling Meta-Reinforcement Learning with Gaussian Task Contexts and Skills (Hongcai He et al., 2023)

{{<citation>}}

Hongcai He, Anjie Zhu, Shuang Liang, Feiyu Chen, Jie Shao. (2023)  
**Decoupling Meta-Reinforcement Learning with Gaussian Task Contexts and Skills**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06518v1)  

---


**ABSTRACT**  
Offline meta-reinforcement learning (meta-RL) methods, which adapt to unseen target tasks with prior experience, are essential in robot control tasks. Current methods typically utilize task contexts and skills as prior experience, where task contexts are related to the information within each task and skills represent a set of temporally extended actions for solving subtasks. However, these methods still suffer from limited performance when adapting to unseen target tasks, mainly because the learned prior experience lacks generalization, i.e., they are unable to extract effective prior experience from meta-training tasks by exploration and learning of continuous latent spaces. We propose a framework called decoupled meta-reinforcement learning (DCMRL), which (1) contrastively restricts the learning of task contexts through pulling in similar task contexts within the same task and pushing away different task contexts of different tasks, and (2) utilizes a Gaussian quantization variational autoencoder (GQ-VAE) for clustering the Gaussian distributions of the task contexts and skills respectively, and decoupling the exploration and learning processes of their spaces. These cluster centers which serve as representative and discrete distributions of task context and skill are stored in task context codebook and skill codebook, respectively. DCMRL can acquire generalizable prior experience and achieve effective adaptation to unseen target tasks during the meta-testing phase. Experiments in the navigation and robot manipulation continuous control tasks show that DCMRL is more effective than previous meta-RL methods with more generalizable prior experience.

{{</citation>}}


### (19/161) Revisiting Graph-based Fraud Detection in Sight of Heterophily and Spectrum (Fan Xu et al., 2023)

{{<citation>}}

Fan Xu, Nan Wang, Hao Wu, Xuezhi Wen, Xibin Zhao. (2023)  
**Revisiting Graph-based Fraud Detection in Sight of Heterophily and Spectrum**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: Fraud Detection, GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.06441v1)  

---


**ABSTRACT**  
Graph-based fraud detection (GFD) can be regarded as a challenging semi-supervised node binary classification task. In recent years, Graph Neural Networks(GNN) have been widely applied to GFD, characterizing the anomalous possibility of a node by aggregating neighbor information. However, fraud graphs are inherently heterophilic, thus most of GNNs perform poorly due to their assumption of homophily. In addition, due to the existence of heterophily and class imbalance problem, the existing models do not fully utilize the precious node label information. To address the above issues, this paper proposes a semi-supervised GNN-based fraud detector SEC-GFD. This detector includes a hybrid filtering module and a local environmental constraint module, the two modules are utilized to solve heterophily and label utilization problem respectively. The first module starts from the perspective of the spectral domain, and solves the heterophily problem to a certain extent. Specifically, it divides the spectrum into multiple mixed frequency bands according to the correlation between spectrum energy distribution and heterophily. Then in order to make full use of the node label information, a local environmental constraint module is adaptively designed. The comprehensive experimental results on four real-world fraud detection datasets show that SEC-GFD outperforms other competitive graph-based fraud detectors.

{{</citation>}}


### (20/161) Reward Certification for Policy Smoothed Reinforcement Learning (Ronghui Mu et al., 2023)

{{<citation>}}

Ronghui Mu, Leandro Soriano Marcolino, Tianle Zhang, Yanghao Zhang, Xiaowei Huang, Wenjie Ruan. (2023)  
**Reward Certification for Policy Smoothed Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06436v2)  

---


**ABSTRACT**  
Reinforcement Learning (RL) has achieved remarkable success in safety-critical areas, but it can be weakened by adversarial attacks. Recent studies have introduced "smoothed policies" in order to enhance its robustness. Yet, it is still challenging to establish a provable guarantee to certify the bound of its total reward. Prior methods relied primarily on computing bounds using Lipschitz continuity or calculating the probability of cumulative reward above specific thresholds. However, these techniques are only suited for continuous perturbations on the RL agent's observations and are restricted to perturbations bounded by the $l_2$-norm. To address these limitations, this paper proposes a general black-box certification method capable of directly certifying the cumulative reward of the smoothed policy under various $l_p$-norm bounded perturbations. Furthermore, we extend our methodology to certify perturbations on action spaces. Our approach leverages f-divergence to measure the distinction between the original distribution and the perturbed distribution, subsequently determining the certification bound by solving a convex optimisation problem. We provide a comprehensive theoretical analysis and run sufficient experiments in multiple environments. Our results show that our method not only improves the certified lower bound of mean cumulative reward but also demonstrates better efficiency than state-of-the-art techniques.

{{</citation>}}


### (21/161) Federated Full-Parameter Tuning of Billion-Sized Language Models with Communication Cost under 18 Kilobytes (Zhen Qin et al., 2023)

{{<citation>}}

Zhen Qin, Daoyuan Chen, Bingchen Qian, Bolin Ding, Yaliang Li, Shuiguang Deng. (2023)  
**Federated Full-Parameter Tuning of Billion-Sized Language Models with Communication Cost under 18 Kilobytes**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06353v1)  

---


**ABSTRACT**  
Pre-trained large language models (LLMs) require fine-tuning to improve their responsiveness to natural language instructions. Federated learning (FL) offers a way to perform fine-tuning using the abundant data on end devices without compromising data privacy. Most existing federated fine-tuning methods for LLMs rely on parameter-efficient fine-tuning techniques, which may not reach the performance heights possible with full-parameter tuning. However, the communication overhead associated with full-parameter tuning is prohibitively high for both servers and clients. This work introduces FedKSeed, a novel approach that employs zeroth-order optimization (ZOO) with a set of random seeds. It enables federated full-parameter tuning of billion-sized LLMs directly on devices. Our method significantly reduces transmission requirements between the server and clients to just a few scalar gradients and random seeds, amounting to only a few thousand bytes. Building on this, we develop a strategy to assess the significance of ZOO perturbations for FL, allowing for probability-differentiated seed sampling. This prioritizes perturbations that have a greater impact on model accuracy. Experiments across six scenarios with different LLMs, datasets and data partitions demonstrate that our approach outperforms existing federated LLM fine-tuning methods in terms of both communication efficiency and new task generalization.

{{</citation>}}


### (22/161) DiffAIL: Diffusion Adversarial Imitation Learning (Bingzheng Wang et al., 2023)

{{<citation>}}

Bingzheng Wang, Guoqiang Wu, Teng Pang, Yan Zhang, Yilong Yin. (2023)  
**DiffAIL: Diffusion Adversarial Imitation Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06348v2)  

---


**ABSTRACT**  
Imitation learning aims to solve the problem of defining reward functions in real-world decision-making tasks. The current popular approach is the Adversarial Imitation Learning (AIL) framework, which matches expert state-action occupancy measures to obtain a surrogate reward for forward reinforcement learning. However, the traditional discriminator is a simple binary classifier and doesn't learn an accurate distribution, which may result in failing to identify expert-level state-action pairs induced by the policy interacting with the environment. To address this issue, we propose a method named diffusion adversarial imitation learning (DiffAIL), which introduces the diffusion model into the AIL framework. Specifically, DiffAIL models the state-action pairs as unconditional diffusion models and uses diffusion loss as part of the discriminator's learning objective, which enables the discriminator to capture better expert demonstrations and improve generalization. Experimentally, the results show that our method achieves state-of-the-art performance and significantly surpasses expert demonstration on two benchmark tasks, including the standard state-action setting and state-only settings. Our code can be available at the link https://github.com/ML-Group-SDU/DiffAIL.

{{</citation>}}


### (23/161) RankMatch: A Novel Approach to Semi-Supervised Label Distribution Learning Leveraging Inter-label Correlations (Kouzhiqiang Yucheng Xie et al., 2023)

{{<citation>}}

Kouzhiqiang Yucheng Xie, Jing Wang, Yuheng Jia, Boyu Shi, Xin Geng. (2023)  
**RankMatch: A Novel Approach to Semi-Supervised Label Distribution Learning Leveraging Inter-label Correlations**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2312.06343v1)  

---


**ABSTRACT**  
This paper introduces RankMatch, an innovative approach for Semi-Supervised Label Distribution Learning (SSLDL). Addressing the challenge of limited labeled data, RankMatch effectively utilizes a small number of labeled examples in conjunction with a larger quantity of unlabeled data, reducing the need for extensive manual labeling in Deep Neural Network (DNN) applications. Specifically, RankMatch introduces an ensemble learning-inspired averaging strategy that creates a pseudo-label distribution from multiple weakly augmented images. This not only stabilizes predictions but also enhances the model's robustness. Beyond this, RankMatch integrates a pairwise relevance ranking (PRR) loss, capturing the complex inter-label correlations and ensuring that the predicted label distributions align with the ground truth.   We establish a theoretical generalization bound for RankMatch, and through extensive experiments, demonstrate its superiority in performance against existing SSLDL methods.

{{</citation>}}


### (24/161) Detecting Contextual Network Anomalies with Graph Neural Networks (Hamid Latif-Martínez et al., 2023)

{{<citation>}}

Hamid Latif-Martínez, José Suárez-Varela, Albert Cabellos-Aparicio, Pere Barlet-Ros. (2023)  
**Detecting Contextual Network Anomalies with Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-NI, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.06342v1)  

---


**ABSTRACT**  
Detecting anomalies on network traffic is a complex task due to the massive amount of traffic flows in today's networks, as well as the highly-dynamic nature of traffic over time. In this paper, we propose the use of Graph Neural Networks (GNN) for network traffic anomaly detection. We formulate the problem as contextual anomaly detection on network traffic measurements, and propose a custom GNN-based solution that detects traffic anomalies on origin-destination flows. In our evaluation, we use real-world data from Abilene (6 months), and make a comparison with other widely used methods for the same task (PCA, EWMA, RNN). The results show that the anomalies detected by our solution are quite complementary to those captured by the baselines (with a max. of 36.33% overlapping anomalies for PCA). Moreover, we manually inspect the anomalies detected by our method, and find that a large portion of them can be visually validated by a network expert (64% with high confidence, 18% with mid confidence, 18% normal traffic). Lastly, we analyze the characteristics of the anomalies through two paradigmatic cases that are quite representative of the bulk of anomalies.

{{</citation>}}


### (25/161) Vehicle Lane Change Prediction based on Knowledge Graph Embeddings and Bayesian Inference (M. Manzour et al., 2023)

{{<citation>}}

M. Manzour, A. Ballardini, R. Izquierdo, M. A. Sotelo. (2023)  
**Vehicle Lane Change Prediction based on Knowledge Graph Embeddings and Bayesian Inference**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-NE, cs.LG  
Keywords: Embedding, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2312.06336v1)  

---


**ABSTRACT**  
Prediction of vehicle lane change maneuvers has gained a lot of momentum in the last few years. Some recent works focus on predicting a vehicle's intention by predicting its trajectory first. This is not enough, as it ignores the context of the scene and the state of the surrounding vehicles (as they might be risky to the target vehicle). Other works assessed the risk made by the surrounding vehicles only by considering their existence around the target vehicle, or by considering the distance and relative velocities between them and the target vehicle as two separate numerical features. In this work, we propose a solution that leverages Knowledge Graphs (KGs) to anticipate lane changes based on linguistic contextual information in a way that goes well beyond the capabilities of current perception systems. Our solution takes the Time To Collision (TTC) with surrounding vehicles as input to assess the risk on the target vehicle. Moreover, our KG is trained on the HighD dataset using the TransE model to obtain the Knowledge Graph Embeddings (KGE). Then, we apply Bayesian inference on top of the KG using the embeddings learned during training. Finally, the model can predict lane changes two seconds ahead with 97.95% f1-score, which surpassed the state of the art, and three seconds before changing lanes with 93.60% f1-score.

{{</citation>}}


### (26/161) TPRNN: A Top-Down Pyramidal Recurrent Neural Network for Time Series Forecasting (Ling Chen et al., 2023)

{{<citation>}}

Ling Chen, Jiahua Cui. (2023)  
**TPRNN: A Top-Down Pyramidal Recurrent Neural Network for Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-NE, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2312.06328v1)  

---


**ABSTRACT**  
Time series refer to a series of data points indexed in time order, which can be found in various fields, e.g., transportation, healthcare, and finance. Accurate time series forecasting can enhance optimization planning and decision-making support. Time series have multi-scale characteristics, i.e., different temporal patterns at different scales, which presents a challenge for time series forecasting. In this paper, we propose TPRNN, a Top-down Pyramidal Recurrent Neural Network for time series forecasting. We first construct subsequences of different scales from the input, forming a pyramid structure. Then by executing a multi-scale information interaction module from top to bottom, we model both the temporal dependencies of each scale and the influences of subsequences of different scales, resulting in a complete modeling of multi-scale temporal patterns in time series. Experiments on seven real-world datasets demonstrate that TPRNN has achieved the state-of-the-art performance with an average improvement of 8.13% in MSE compared to the best baseline.

{{</citation>}}


### (27/161) Regional Correlation Aided Mobile Traffic Prediction with Spatiotemporal Deep Learning (JeongJun Park et al., 2023)

{{<citation>}}

JeongJun Park, Lusungu J. Mwasinga, Huigyu Yang, Syed M. Raza, Duc-Tai Le, Moonseong Kim, Min Young Chung, Hyunseung Choo. (2023)  
**Regional Correlation Aided Mobile Traffic Prediction with Spatiotemporal Deep Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2312.06279v1)  

---


**ABSTRACT**  
Mobile traffic data in urban regions shows differentiated patterns during different hours of the day. The exploitation of these patterns enables highly accurate mobile traffic prediction for proactive network management. However, recent Deep Learning (DL) driven studies have only exploited spatiotemporal features and have ignored the geographical correlations, causing high complexity and erroneous mobile traffic predictions. This paper addresses these limitations by proposing an enhanced mobile traffic prediction scheme that combines the clustering strategy of daily mobile traffic peak time and novel multi Temporal Convolutional Network with a Long Short Term Memory (multi TCN-LSTM) model. The mobile network cells that exhibit peak traffic during the same hour of the day are clustered together. Our experiments on large-scale real-world mobile traffic data show up to 28% performance improvement compared to state-of-the-art studies, which confirms the efficacy and viability of the proposed approach.

{{</citation>}}


### (28/161) No Prior Mask: Eliminate Redundant Action for Deep Reinforcement Learning (Dianyu Zhong et al., 2023)

{{<citation>}}

Dianyu Zhong, Yiqin Yang, Qianchuan Zhao. (2023)  
**No Prior Mask: Eliminate Redundant Action for Deep Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06258v1)  

---


**ABSTRACT**  
The large action space is one fundamental obstacle to deploying Reinforcement Learning methods in the real world. The numerous redundant actions will cause the agents to make repeated or invalid attempts, even leading to task failure. Although current algorithms conduct some initial explorations for this issue, they either suffer from rule-based systems or depend on expert demonstrations, which significantly limits their applicability in many real-world settings. In this work, we examine the theoretical analysis of what action can be eliminated in policy optimization and propose a novel redundant action filtering mechanism. Unlike other works, our method constructs the similarity factor by estimating the distance between the state distributions, which requires no prior knowledge. In addition, we combine the modified inverse model to avoid extensive computation in high-dimensional state space. We reveal the underlying structure of action spaces and propose a simple yet efficient redundant action filtering mechanism named No Prior Mask (NPM) based on the above techniques. We show the superior performance of our method by conducting extensive experiments on high-dimensional, pixel-input, and stochastic problems with various action redundancy. Our code is public online at https://github.com/zhongdy15/npm.

{{</citation>}}


### (29/161) Improving Startup Success with Text Analysis (Emily Gavrilenko et al., 2023)

{{<citation>}}

Emily Gavrilenko, Foaad Khosmood, Mahdi Rastad, Sadra Amiri Moghaddam. (2023)  
**Improving Startup Success with Text Analysis**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-IR, cs-LG, cs.LG  
Keywords: Google, Twitter  
[Paper Link](http://arxiv.org/abs/2312.06236v1)  

---


**ABSTRACT**  
Investors are interested in predicting future success of startup companies, preferably using publicly available data which can be gathered using free online sources. Using public-only data has been shown to work, but there is still much room for improvement. Two of the best performing prediction experiments use 17 and 49 features respectively, mostly numeric and categorical in nature. In this paper, we significantly expand and diversify both the sources and the number of features (to 171) to achieve better prediction. Data collected from Crunchbase, the Google Search API, and Twitter (now X) are used to predict whether a company will raise a round of funding within a fixed time horizon. Much of the new features are textual and the Twitter subset include linguistic metrics such as measures of passive voice and parts-of-speech. A total of ten machine learning models are also evaluated for best performance. The adaptable model can be used to predict funding 1-5 years into the future, with a variable cutoff threshold to favor either precision or recall. Prediction with comparable assumptions generally achieves F scores above 0.730 which outperforms previous attempts in the literature (0.531), and does so with fewer examples. Furthermore, we find that the vast majority of the performance impact comes from the top 18 of 171 features which are mostly generic company observations, including the best performing individual feature which is the free-form text description of the company.

{{</citation>}}


### (30/161) Dance of Channel and Sequence: An Efficient Attention-Based Approach for Multivariate Time Series Forecasting (Haoxin Wang et al., 2023)

{{<citation>}}

Haoxin Wang, Yipeng Mo, Nan Yin, Honghe Dai, Bixiong Li, Songhai Fan, Site Mo. (2023)  
**Dance of Channel and Sequence: An Efficient Attention-Based Approach for Multivariate Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Attention, Time Series  
[Paper Link](http://arxiv.org/abs/2312.06220v1)  

---


**ABSTRACT**  
In recent developments, predictive models for multivariate time series analysis have exhibited commendable performance through the adoption of the prevalent principle of channel independence. Nevertheless, it is imperative to acknowledge the intricate interplay among channels, which fundamentally influences the outcomes of multivariate predictions. Consequently, the notion of channel independence, while offering utility to a certain extent, becomes increasingly impractical, leading to information degradation. In response to this pressing concern, we present CSformer, an innovative framework characterized by a meticulously engineered two-stage self-attention mechanism. This mechanism is purposefully designed to enable the segregated extraction of sequence-specific and channel-specific information, while sharing parameters to promote synergy and mutual reinforcement between sequences and channels. Simultaneously, we introduce sequence adapters and channel adapters, ensuring the model's ability to discern salient features across various dimensions. Rigorous experimentation, spanning multiple real-world datasets, underscores the robustness of our approach, consistently establishing its position at the forefront of predictive performance across all datasets. This augmentation substantially enhances the capacity for feature extraction inherent to multivariate time series data, facilitating a more comprehensive exploitation of the available information.

{{</citation>}}


### (31/161) Why 'classic' Transformers are shallow and how to make them go deep (Yueyao Yu et al., 2023)

{{<citation>}}

Yueyao Yu, Yin Zhang. (2023)  
**Why 'classic' Transformers are shallow and how to make them go deep**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-NE, cs.LG  
Keywords: AI, Attention, Self-Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06182v1)  

---


**ABSTRACT**  
Since its introduction in 2017, Transformer has emerged as the leading neural network architecture, catalyzing revolutionary advancements in many AI disciplines. The key innovation in Transformer is a Self-Attention (SA) mechanism designed to capture contextual information. However, extending the original Transformer design to models of greater depth has proven exceedingly challenging, if not impossible. Even though various modifications have been proposed in order to stack more layers of SA mechanism into deeper models, a full understanding of this depth problem remains elusive. In this paper, we conduct a comprehensive investigation, both theoretically and empirically, to substantiate the claim that the depth problem is caused by \emph{token similarity escalation}; that is, tokens grow increasingly alike after repeated applications of the SA mechanism. Our analysis reveals that, driven by the invariant leading eigenspace and large spectral gaps of attention matrices, token similarity provably escalates at a linear rate. Based on the gained insight, we propose a simple strategy that, unlike most existing methods, surgically removes excessive similarity without discounting the SA mechanism as a whole. Preliminary experimental results confirm the effectiveness of the proposed approach on moderate-scale post-norm Transformer models.

{{</citation>}}


### (32/161) Open Datasheets: Machine-readable Documentation for Open Datasets and Responsible AI Assessments (Anthony Cintron Roman et al., 2023)

{{<citation>}}

Anthony Cintron Roman, Jennifer Wortman Vaughan, Valerie See, Steph Ballard, Nicolas Schifano, Jehu Torres, Caleb Robinson, Juan M. Lavista Ferres. (2023)  
**Open Datasheets: Machine-readable Documentation for Open Datasets and Responsible AI Assessments**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-HC, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06153v1)  

---


**ABSTRACT**  
This paper introduces a no-code, machine-readable documentation framework for open datasets, with a focus on Responsible AI (RAI) considerations. The framework aims to improve the accessibility, comprehensibility, and usability of open datasets, facilitating easier discovery and use, better understanding of content and context, and evaluation of dataset quality and accuracy. The proposed framework is designed to streamline the evaluation of datasets, helping researchers, data scientists, and other open data users quickly identify datasets that meet their needs and/or organizational policies or regulations. The paper also discusses the implementation of the framework and provides recommendations to maximize its potential. The framework is expected to enhance the quality and reliability of data used in research and decision-making, fostering the development of more responsible and trustworthy AI systems.

{{</citation>}}


### (33/161) Spreeze: High-Throughput Parallel Reinforcement Learning Framework (Jing Hou et al., 2023)

{{<citation>}}

Jing Hou, Guang Chen, Ruiqi Zhang, Zhijun Li, Shangding Gu, Changjun Jiang. (2023)  
**Spreeze: High-Throughput Parallel Reinforcement Learning Framework**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-DC, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06126v1)  

---


**ABSTRACT**  
The promotion of large-scale applications of reinforcement learning (RL) requires efficient training computation. While existing parallel RL frameworks encompass a variety of RL algorithms and parallelization techniques, the excessively burdensome communication frameworks hinder the attainment of the hardware's limit for final throughput and training effects on a single desktop. In this paper, we propose Spreeze, a lightweight parallel framework for RL that efficiently utilizes a single desktop hardware resource to approach the throughput limit. We asynchronously parallelize the experience sampling, network update, performance evaluation, and visualization operations, and employ multiple efficient data transmission techniques to transfer various types of data between processes. The framework can automatically adjust the parallelization hyperparameters based on the computing ability of the hardware device in order to perform efficient large-batch updates. Based on the characteristics of the "Actor-Critic" RL algorithm, our framework uses dual GPUs to independently update the network of actors and critics in order to further improve throughput. Simulation results show that our framework can achieve up to 15,000Hz experience sampling and 370,000Hz network update frame rate using only a personal desktop computer, which is an order of magnitude higher than other mainstream parallel RL frameworks, resulting in a 73% reduction of training time. Our work on fully utilizing the hardware resources of a single desktop computer is fundamental to enabling efficient large-scale distributed RL training.

{{</citation>}}


### (34/161) TabMT: Generating tabular data with masked transformers (Manbir S Gulati et al., 2023)

{{<citation>}}

Manbir S Gulati, Paul F Roysdon. (2023)  
**TabMT: Generating tabular data with masked transformers**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: NLP, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06089v1)  

---


**ABSTRACT**  
Autoregressive and Masked Transformers are incredibly effective as generative models and classifiers. While these models are most prevalent in NLP, they also exhibit strong performance in other domains, such as vision. This work contributes to the exploration of transformer-based models in synthetic data generation for diverse application domains. In this paper, we present TabMT, a novel Masked Transformer design for generating synthetic tabular data. TabMT effectively addresses the unique challenges posed by heterogeneous data fields and is natively able to handle missing data. Our design leverages improved masking techniques to allow for generation and demonstrates state-of-the-art performance from extremely small to extremely large tabular datasets. We evaluate TabMT for privacy-focused applications and find that it is able to generate high quality data with superior privacy tradeoffs.

{{</citation>}}


## cs.RO (5)



### (35/161) Interactive Planning Using Large Language Models for Partially Observable Robotics Tasks (Lingfeng Sun et al., 2023)

{{<citation>}}

Lingfeng Sun, Devesh K. Jha, Chiori Hori, Siddarth Jain, Radu Corcodel, Xinghao Zhu, Masayoshi Tomizuka, Diego Romeres. (2023)  
**Interactive Planning Using Large Language Models for Partially Observable Robotics Tasks**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: AI, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06876v1)  

---


**ABSTRACT**  
Designing robotic agents to perform open vocabulary tasks has been the long-standing goal in robotics and AI. Recently, Large Language Models (LLMs) have achieved impressive results in creating robotic agents for performing open vocabulary tasks. However, planning for these tasks in the presence of uncertainties is challenging as it requires \enquote{chain-of-thought} reasoning, aggregating information from the environment, updating state estimates, and generating actions based on the updated state estimates. In this paper, we present an interactive planning technique for partially observable tasks using LLMs. In the proposed method, an LLM is used to collect missing information from the environment using a robot and infer the state of the underlying problem from collected observations while guiding the robot to perform the required actions. We also use a fine-tuned Llama 2 model via self-instruct and compare its performance against a pre-trained LLM like GPT-4. Results are demonstrated on several tasks in simulation as well as real-world environments. A video describing our work along with some results could be found here.

{{</citation>}}


### (36/161) Scalable Decentralized Cooperative Platoon using Multi-Agent Deep Reinforcement Learning (Ahmed Abdelrahman et al., 2023)

{{<citation>}}

Ahmed Abdelrahman, Omar M. Shehata, Yarah Basyoni, Elsayed I. Morgan. (2023)  
**Scalable Decentralized Cooperative Platoon using Multi-Agent Deep Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-MA, cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06858v1)  

---


**ABSTRACT**  
Cooperative autonomous driving plays a pivotal role in improving road capacity and safety within intelligent transportation systems, particularly through the deployment of autonomous vehicles on urban streets. By enabling vehicle-to-vehicle communication, these systems expand the vehicles environmental awareness, allowing them to detect hidden obstacles and thereby enhancing safety and reducing crash rates compared to human drivers who rely solely on visual perception. A key application of this technology is vehicle platooning, where connected vehicles drive in a coordinated formation. This paper introduces a vehicle platooning approach designed to enhance traffic flow and safety. Developed using deep reinforcement learning in the Unity 3D game engine, known for its advanced physics, this approach aims for a high-fidelity physical simulation that closely mirrors real-world conditions. The proposed platooning model focuses on scalability, decentralization, and fostering positive cooperation through the introduced predecessor-follower "sharing and caring" communication framework. The study demonstrates how these elements collectively enhance autonomous driving performance and robustness, both for individual vehicles and for the platoon as a whole, in an urban setting. This results in improved road safety and reduced traffic congestion.

{{</citation>}}


### (37/161) From Text to Motion: Grounding GPT-4 in a Humanoid Robot 'Alter3' (Takahide Yoshida et al., 2023)

{{<citation>}}

Takahide Yoshida, Atsushi Masumori, Takashi Ikegami. (2023)  
**From Text to Motion: Grounding GPT-4 in a Humanoid Robot 'Alter3'**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06571v1)  

---


**ABSTRACT**  
We report the development of Alter3, a humanoid robot capable of generating spontaneous motion using a Large Language Model (LLM), specifically GPT-4. This achievement was realized by integrating GPT-4 into our proprietary android, Alter3, thereby effectively grounding the LLM with Alter's bodily movement. Typically, low-level robot control is hardware-dependent and falls outside the scope of LLM corpora, presenting challenges for direct LLM-based robot control. However, in the case of humanoid robots like Alter3, direct control is feasible by mapping the linguistic expressions of human actions onto the robot's body through program code. Remarkably, this approach enables Alter3 to adopt various poses, such as a 'selfie' stance or 'pretending to be a ghost,' and generate sequences of actions over time without explicit programming for each body part. This demonstrates the robot's zero-shot learning capabilities. Additionally, verbal feedback can adjust poses, obviating the need for fine-tuning. A video of Alter3's generated motions is available at https://tnoinkwms.github.io/ALTER-LLM/

{{</citation>}}


### (38/161) Partial End-to-end Reinforcement Learning for Robustness Against Modelling Error in Autonomous Racing (Andrew Murdoch et al., 2023)

{{<citation>}}

Andrew Murdoch, Johannes Cornelius Schoeman, Hendrik Willem Jordaan. (2023)  
**Partial End-to-end Reinforcement Learning for Robustness Against Modelling Error in Autonomous Racing**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06406v1)  

---


**ABSTRACT**  
In this paper, we address the issue of increasing the performance of reinforcement learning (RL) solutions for autonomous racing cars when navigating under conditions where practical vehicle modelling errors (commonly known as \emph{model mismatches}) are present. To address this challenge, we propose a partial end-to-end algorithm that decouples the planning and control tasks. Within this framework, an RL agent generates a trajectory comprising a path and velocity, which is subsequently tracked using a pure pursuit steering controller and a proportional velocity controller, respectively. In contrast, many current learning-based (i.e., reinforcement and imitation learning) algorithms utilise an end-to-end approach whereby a deep neural network directly maps from sensor data to control commands. By leveraging the robustness of a classical controller, our partial end-to-end driving algorithm exhibits better robustness towards model mismatches than standard end-to-end algorithms.

{{</citation>}}


### (39/161) BAT: Behavior-Aware Human-Like Trajectory Prediction for Autonomous Driving (Haicheng Liao et al., 2023)

{{<citation>}}

Haicheng Liao, Zhenning Li, Huanming Shen, Wenxuan Zeng, Guofa Li, Shengbo Eben Li, Chengzhong Xu. (2023)  
**BAT: Behavior-Aware Human-Like Trajectory Prediction for Autonomous Driving**  

---
Primary Category: cs.RO  
Categories: cs-AI, cs-RO, cs.RO  
Keywords: Drone  
[Paper Link](http://arxiv.org/abs/2312.06371v1)  

---


**ABSTRACT**  
The ability to accurately predict the trajectory of surrounding vehicles is a critical hurdle to overcome on the journey to fully autonomous vehicles. To address this challenge, we pioneer a novel behavior-aware trajectory prediction model (BAT) that incorporates insights and findings from traffic psychology, human behavior, and decision-making. Our model consists of behavior-aware, interaction-aware, priority-aware, and position-aware modules that perceive and understand the underlying interactions and account for uncertainty and variability in prediction, enabling higher-level learning and flexibility without rigid categorization of driving behavior. Importantly, this approach eliminates the need for manual labeling in the training process and addresses the challenges of non-continuous behavior labeling and the selection of appropriate time windows. We evaluate BAT's performance across the Next Generation Simulation (NGSIM), Highway Drone (HighD), Roundabout Drone (RounD), and Macao Connected Autonomous Driving (MoCAD) datasets, showcasing its superiority over prevailing state-of-the-art (SOTA) benchmarks in terms of prediction accuracy and efficiency. Remarkably, even when trained on reduced portions of the training data (25%), our model outperforms most of the baselines, demonstrating its robustness and efficiency in predicting vehicle trajectories, and the potential to reduce the amount of data required to train autonomous vehicles, especially in corner cases. In conclusion, the behavior-aware model represents a significant advancement in the development of autonomous vehicles capable of predicting trajectories with the same level of proficiency as human drivers. The project page is available at https://github.com/Petrichor625/BATraj-Behavior-aware-Model.

{{</citation>}}


## cs.CV (45)



### (40/161) RAFIC: Retrieval-Augmented Few-shot Image Classification (Hangfei Lin et al., 2023)

{{<citation>}}

Hangfei Lin, Li Miao, Amir Ziai. (2023)  
**RAFIC: Retrieval-Augmented Few-shot Image Classification**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: AI, Image Classification  
[Paper Link](http://arxiv.org/abs/2312.06868v1)  

---


**ABSTRACT**  
Few-shot image classification is the task of classifying unseen images to one of N mutually exclusive classes, using only a small number of training examples for each class. The limited availability of these examples (denoted as K) presents a significant challenge to classification accuracy in some cases. To address this, we have developed a method for augmenting the set of K with an addition set of A retrieved images. We call this system Retrieval-Augmented Few-shot Image Classification (RAFIC). Through a series of experiments, we demonstrate that RAFIC markedly improves performance of few-shot image classification across two challenging datasets. RAFIC consists of two main components: (a) a retrieval component which uses CLIP, LAION-5B, and faiss, in order to efficiently retrieve images similar to the supplied images, and (b) retrieval meta-learning, which learns to judiciously utilize the retrieved images. Code and data is available at github.com/amirziai/rafic.

{{</citation>}}


### (41/161) NDELS: A Novel Approach for Nighttime Dehazing, Low-Light Enhancement, and Light Suppression (Silvano A. Bernabel et al., 2023)

{{<citation>}}

Silvano A. Bernabel, Sos S. Agaian. (2023)  
**NDELS: A Novel Approach for Nighttime Dehazing, Low-Light Enhancement, and Light Suppression**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.06850v1)  

---


**ABSTRACT**  
This paper tackles the intricate challenge of improving the quality of nighttime images under hazy and low-light conditions. Overcoming issues including nonuniform illumination glows, texture blurring, glow effects, color distortion, noise disturbance, and overall, low light have proven daunting. Despite the inherent difficulties, this paper introduces a pioneering solution named Nighttime Dehazing, Low-Light Enhancement, and Light Suppression (NDELS). NDELS utilizes a unique network that combines three essential processes to enhance visibility, brighten low-light regions, and effectively suppress glare from bright light sources. In contrast to limited progress in nighttime dehazing, unlike its daytime counterpart, NDELS presents a comprehensive and innovative approach. The efficacy of NDELS is rigorously validated through extensive comparisons with eight state-of-the-art algorithms across four diverse datasets. Experimental results showcase the superior performance of our method, demonstrating its outperformance in terms of overall image quality, including color and edge enhancement. Quantitative (PSNR, SSIM) and qualitative metrics (CLIPIQA, MANIQA, TRES), measure these results.

{{</citation>}}


### (42/161) Encoding Surgical Videos as Latent Spatiotemporal Graphs for Object and Anatomy-Driven Reasoning (Aditya Murali et al., 2023)

{{<citation>}}

Aditya Murali, Deepak Alapatt, Pietro Mascagni, Armine Vardazaryan, Alain Garcia, Nariaki Okamoto, Didier Mutter, Nicolas Padoy. (2023)  
**Encoding Surgical Videos as Latent Spatiotemporal Graphs for Object and Anatomy-Driven Reasoning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2312.06829v1)  

---


**ABSTRACT**  
Recently, spatiotemporal graphs have emerged as a concise and elegant manner of representing video clips in an object-centric fashion, and have shown to be useful for downstream tasks such as action recognition. In this work, we investigate the use of latent spatiotemporal graphs to represent a surgical video in terms of the constituent anatomical structures and tools and their evolving properties over time. To build the graphs, we first predict frame-wise graphs using a pre-trained model, then add temporal edges between nodes based on spatial coherence and visual and semantic similarity. Unlike previous approaches, we incorporate long-term temporal edges in our graphs to better model the evolution of the surgical scene and increase robustness to temporary occlusions. We also introduce a novel graph-editing module that incorporates prior knowledge and temporal coherence to correct errors in the graph, enabling improved downstream task performance. Using our graph representations, we evaluate two downstream tasks, critical view of safety prediction and surgical phase recognition, obtaining strong results that demonstrate the quality and flexibility of the learned representations. Code is available at github.com/CAMMA-public/SurgLatentGraph.

{{</citation>}}


### (43/161) ADOD: Adaptive Domain-Aware Object Detection with Residual Attention for Underwater Environments (Lyes Saad Saoud et al., 2023)

{{<citation>}}

Lyes Saad Saoud, Zhenwei Niu, Atif Sultan, Lakmal Seneviratne, Irfan Hussain. (2023)  
**ADOD: Adaptive Domain-Aware Object Detection with Residual Attention for Underwater Environments**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-RO, cs.CV  
Keywords: Attention, Object Detection  
[Paper Link](http://arxiv.org/abs/2312.06801v1)  

---


**ABSTRACT**  
This research presents ADOD, a novel approach to address domain generalization in underwater object detection. Our method enhances the model's ability to generalize across diverse and unseen domains, ensuring robustness in various underwater environments. The first key contribution is Residual Attention YOLOv3, a novel variant of the YOLOv3 framework empowered by residual attention modules. These modules enable the model to focus on informative features while suppressing background noise, leading to improved detection accuracy and adaptability to different domains. The second contribution is the attention-based domain classification module, vital during training. This module helps the model identify domain-specific information, facilitating the learning of domain-invariant features. Consequently, ADOD can generalize effectively to underwater environments with distinct visual characteristics. Extensive experiments on diverse underwater datasets demonstrate ADOD's superior performance compared to state-of-the-art domain generalization methods, particularly in challenging scenarios. The proposed model achieves exceptional detection performance in both seen and unseen domains, showcasing its effectiveness in handling domain shifts in underwater object detection tasks. ADOD represents a significant advancement in adaptive object detection, providing a promising solution for real-world applications in underwater environments. With the prevalence of domain shifts in such settings, the model's strong generalization ability becomes a valuable asset for practical underwater surveillance and marine research endeavors.

{{</citation>}}


### (44/161) Photorealistic Video Generation with Diffusion Models (Agrim Gupta et al., 2023)

{{<citation>}}

Agrim Gupta, Lijun Yu, Kihyuk Sohn, Xiuye Gu, Meera Hahn, Li Fei-Fei, Irfan Essa, Lu Jiang, José Lezama. (2023)  
**Photorealistic Video Generation with Diffusion Models**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2312.06662v1)  

---


**ABSTRACT**  
We present W.A.L.T, a transformer-based approach for photorealistic video generation via diffusion modeling. Our approach has two key design decisions. First, we use a causal encoder to jointly compress images and videos within a unified latent space, enabling training and generation across modalities. Second, for memory and training efficiency, we use a window attention architecture tailored for joint spatial and spatiotemporal generative modeling. Taken together these design decisions enable us to achieve state-of-the-art performance on established video (UCF-101 and Kinetics-600) and image (ImageNet) generation benchmarks without using classifier free guidance. Finally, we also train a cascade of three models for the task of text-to-video generation consisting of a base latent video diffusion model, and two video super-resolution diffusion models to generate videos of $512 \times 896$ resolution at $8$ frames per second.

{{</citation>}}


### (45/161) UpFusion: Novel View Diffusion from Unposed Sparse View Observations (Bharath Raj Nagoor Kani et al., 2023)

{{<citation>}}

Bharath Raj Nagoor Kani, Hsin-Ying Lee, Sergey Tulyakov, Shubham Tulsiani. (2023)  
**UpFusion: Novel View Diffusion from Unposed Sparse View Observations**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Google  
[Paper Link](http://arxiv.org/abs/2312.06661v1)  

---


**ABSTRACT**  
We propose UpFusion, a system that can perform novel view synthesis and infer 3D representations for an object given a sparse set of reference images without corresponding pose information. Current sparse-view 3D inference methods typically rely on camera poses to geometrically aggregate information from input views, but are not robust in-the-wild when such information is unavailable/inaccurate. In contrast, UpFusion sidesteps this requirement by learning to implicitly leverage the available images as context in a conditional generative model for synthesizing novel views. We incorporate two complementary forms of conditioning into diffusion models for leveraging the input views: a) via inferring query-view aligned features using a scene-level transformer, b) via intermediate attentional layers that can directly observe the input image tokens. We show that this mechanism allows generating high-fidelity novel views while improving the synthesis quality given additional (unposed) images. We evaluate our approach on the Co3Dv2 and Google Scanned Objects datasets and demonstrate the benefits of our method over pose-reliant sparse-view methods as well as single-view methods that cannot leverage additional views. Finally, we also show that our learned model can generalize beyond the training categories and even allow reconstruction from self-captured images of generic objects in-the-wild.

{{</citation>}}


### (46/161) Honeybee: Locality-enhanced Projector for Multimodal LLM (Junbum Cha et al., 2023)

{{<citation>}}

Junbum Cha, Wooyoung Kang, Jonghwan Mun, Byungseok Roh. (2023)  
**Honeybee: Locality-enhanced Projector for Multimodal LLM**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CL, cs-CV, cs-LG, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06742v1)  

---


**ABSTRACT**  
In Multimodal Large Language Models (MLLMs), a visual projector plays a crucial role in bridging pre-trained vision encoders with LLMs, enabling profound visual understanding while harnessing the LLMs' robust capabilities. Despite the importance of the visual projector, it has been relatively less explored. In this study, we first identify two essential projector properties: (i) flexibility in managing the number of visual tokens, crucial for MLLMs' overall efficiency, and (ii) preservation of local context from visual features, vital for spatial understanding. Based on these findings, we propose a novel projector design that is both flexible and locality-enhanced, effectively satisfying the two desirable properties. Additionally, we present comprehensive strategies to effectively utilize multiple and multifaceted instruction datasets. Through extensive experiments, we examine the impact of individual design choices. Finally, our proposed MLLM, Honeybee, remarkably outperforms previous state-of-the-art methods across various benchmarks, including MME, MMBench, SEED-Bench, and LLaVA-Bench, achieving significantly higher efficiency. Code and models are available at https://github.com/kakaobrain/honeybee.

{{</citation>}}


### (47/161) 4M: Massively Multimodal Masked Modeling (David Mizrahi et al., 2023)

{{<citation>}}

David Mizrahi, Roman Bachmann, Oğuzhan Fatih Kar, Teresa Yeo, Mingfei Gao, Afshin Dehghan, Amir Zamir. (2023)  
**4M: Massively Multimodal Masked Modeling**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06647v1)  

---


**ABSTRACT**  
Current machine learning models for vision are often highly specialized and limited to a single modality and task. In contrast, recent large language models exhibit a wide range of capabilities, hinting at a possibility for similarly versatile models in computer vision. In this paper, we take a step in this direction and propose a multimodal training scheme called 4M. It consists of training a single unified Transformer encoder-decoder using a masked modeling objective across a wide range of input/output modalities - including text, images, geometric, and semantic modalities, as well as neural network feature maps. 4M achieves scalability by unifying the representation space of all modalities through mapping them into discrete tokens and performing multimodal masked modeling on a small randomized subset of tokens.   4M leads to models that exhibit several key capabilities: (1) they can perform a diverse set of vision tasks out of the box, (2) they excel when fine-tuned for unseen downstream tasks or new input modalities, and (3) they can function as a generative model that can be conditioned on arbitrary modalities, enabling a wide variety of expressive multimodal editing capabilities with remarkable flexibility.   Through experimental analyses, we demonstrate the potential of 4M for training versatile and scalable foundation models for vision tasks, setting the stage for further exploration in multimodal learning for vision and other domains.

{{</citation>}}


### (48/161) Beyond Classification: Definition and Density-based Estimation of Calibration in Object Detection (Teodora Popordanoska et al., 2023)

{{<citation>}}

Teodora Popordanoska, Aleksei Tiulpin, Matthew B. Blaschko. (2023)  
**Beyond Classification: Definition and Density-based Estimation of Calibration in Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2312.06645v1)  

---


**ABSTRACT**  
Despite their impressive predictive performance in various computer vision tasks, deep neural networks (DNNs) tend to make overly confident predictions, which hinders their widespread use in safety-critical applications. While there have been recent attempts to calibrate DNNs, most of these efforts have primarily been focused on classification tasks, thus neglecting DNN-based object detectors. Although several recent works addressed calibration for object detection and proposed differentiable penalties, none of them are consistent estimators of established concepts in calibration. In this work, we tackle the challenge of defining and estimating calibration error specifically for this task. In particular, we adapt the definition of classification calibration error to handle the nuances associated with object detection, and predictions in structured output spaces more generally. Furthermore, we propose a consistent and differentiable estimator of the detection calibration error, utilizing kernel density estimation. Our experiments demonstrate the effectiveness of our estimator against competing train-time and post-hoc calibration methods, while maintaining similar detection performance.

{{</citation>}}


### (49/161) AnyHome: Open-Vocabulary Generation of Structured and Textured 3D Homes (Zehao Wen et al., 2023)

{{<citation>}}

Zehao Wen, Zichen Liu, Srinath Sridhar, Rao Fu. (2023)  
**AnyHome: Open-Vocabulary Generation of Structured and Textured 3D Homes**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-GR, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06644v1)  

---


**ABSTRACT**  
We introduce AnyHome, a framework that translates open-vocabulary descriptions, ranging from simple labels to elaborate paragraphs, into well-structured and textured 3D indoor scenes at a house-scale. Inspired by cognition theories, AnyHome employs an amodal structured representation to capture 3D spatial cues from textual narratives and then uses egocentric inpainting to enrich these scenes. To this end, we begin by using specially designed template prompts for Large Language Models (LLMs), which enable precise control over the textual input. We then utilize intermediate representations to maintain the spatial structure's consistency, ensuring that the 3D scenes align closely with the textual description. Then, we apply a Score Distillation Sampling process to refine the placement of objects. Lastly, an egocentric inpainting process is incorporated to enhance the realism and appearance of the scenes. AnyHome stands out due to its hierarchical structured representation combined with the versatility of open-vocabulary text interpretation. This allows for extensive customization of indoor scenes at various levels of granularity. We demonstrate that AnyHome can reliably generate a range of diverse indoor scenes, characterized by their detailed spatial structures and textures, all corresponding to the free-form textual inputs.

{{</citation>}}


### (50/161) Upscale-A-Video: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution (Shangchen Zhou et al., 2023)

{{<citation>}}

Shangchen Zhou, Peiqing Yang, Jianyi Wang, Yihang Luo, Chen Change Loy. (2023)  
**Upscale-A-Video: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06640v1)  

---


**ABSTRACT**  
Text-based diffusion models have exhibited remarkable success in generation and editing, showing great promise for enhancing visual content with their generative prior. However, applying these models to video super-resolution remains challenging due to the high demands for output fidelity and temporal consistency, which is complicated by the inherent randomness in diffusion models. Our study introduces Upscale-A-Video, a text-guided latent diffusion framework for video upscaling. This framework ensures temporal coherence through two key mechanisms: locally, it integrates temporal layers into U-Net and VAE-Decoder, maintaining consistency within short sequences; globally, without training, a flow-guided recurrent latent propagation module is introduced to enhance overall video stability by propagating and fusing latent across the entire sequences. Thanks to the diffusion paradigm, our model also offers greater flexibility by allowing text prompts to guide texture creation and adjustable noise levels to balance restoration and generation, enabling a trade-off between fidelity and quality. Extensive experiments show that Upscale-A-Video surpasses existing methods in both synthetic and real-world benchmarks, as well as in AI-generated videos, showcasing impressive visual realism and temporal consistency.

{{</citation>}}


### (51/161) AttenScribble: Attentive Similarity Learning for Scribble-Supervised Medical Image Segmentation (Mu Tian et al., 2023)

{{<citation>}}

Mu Tian, Qinzhu Yang, Yi Gao. (2023)  
**AttenScribble: Attentive Similarity Learning for Scribble-Supervised Medical Image Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.06614v1)  

---


**ABSTRACT**  
The success of deep networks in medical image segmentation relies heavily on massive labeled training data. However, acquiring dense annotations is a time-consuming process. Weakly-supervised methods normally employ less expensive forms of supervision, among which scribbles started to gain popularity lately thanks to its flexibility. However, due to lack of shape and boundary information, it is extremely challenging to train a deep network on scribbles that generalizes on unlabeled pixels. In this paper, we present a straightforward yet effective scribble supervised learning framework. Inspired by recent advances of transformer based segmentation, we create a pluggable spatial self-attention module which could be attached on top of any internal feature layers of arbitrary fully convolutional network (FCN) backbone. The module infuses global interaction while keeping the efficiency of convolutions. Descended from this module, we construct a similarity metric based on normalized and symmetrized attention. This attentive similarity leads to a novel regularization loss that imposes consistency between segmentation prediction and visual affinity. This attentive similarity loss optimizes the alignment of FCN encoders, attention mapping and model prediction. Ultimately, the proposed FCN+Attention architecture can be trained end-to-end guided by a combination of three learning objectives: partial segmentation loss, a customized masked conditional random fields and the proposed attentive similarity loss. Extensive experiments on public datasets (ACDC and CHAOS) showed that our framework not just out-performs existing state-of-the-art, but also delivers close performance to fully-supervised benchmark. Code will be available upon publication.

{{</citation>}}


### (52/161) Neural Text to Articulate Talk: Deep Text to Audiovisual Speech Synthesis achieving both Auditory and Photo-realism (Georgios Milis et al., 2023)

{{<citation>}}

Georgios Milis, Panagiotis P. Filntisis, Anastasios Roussos, Petros Maragos. (2023)  
**Neural Text to Articulate Talk: Deep Text to Audiovisual Speech Synthesis achieving both Auditory and Photo-realism**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-SD, cs.CV, eess-AS  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06613v1)  

---


**ABSTRACT**  
Recent advances in deep learning for sequential data have given rise to fast and powerful models that produce realistic videos of talking humans. The state of the art in talking face generation focuses mainly on lip-syncing, being conditioned on audio clips. However, having the ability to synthesize talking humans from text transcriptions rather than audio is particularly beneficial for many applications and is expected to receive more and more attention, following the recent breakthroughs in large language models. For that, most methods implement a cascaded 2-stage architecture of a text-to-speech module followed by an audio-driven talking face generator, but this ignores the highly complex interplay between audio and visual streams that occurs during speaking. In this paper, we propose the first, to the best of our knowledge, text-driven audiovisual speech synthesizer that uses Transformers and does not follow a cascaded approach. Our method, which we call NEUral Text to ARticulate Talk (NEUTART), is a talking face generator that uses a joint audiovisual feature space, as well as speech-informed 3D facial reconstructions and a lip-reading loss for visual supervision. The proposed model produces photorealistic talking face videos with human-like articulation and well-synced audiovisual streams. Our experiments on audiovisual datasets as well as in-the-wild videos reveal state-of-the-art generation quality both in terms of objective metrics and human evaluation.

{{</citation>}}


### (53/161) DiAD: A Diffusion-based Framework for Multi-class Anomaly Detection (Haoyang He et al., 2023)

{{<citation>}}

Haoyang He, Jiangning Zhang, Hongxu Chen, Xuhai Chen, Zhishan Li, Xu Chen, Yabiao Wang, Chengjie Wang, Lei Xie. (2023)  
**DiAD: A Diffusion-based Framework for Multi-class Anomaly Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Anomaly Detection  
[Paper Link](http://arxiv.org/abs/2312.06607v1)  

---


**ABSTRACT**  
Reconstruction-based approaches have achieved remarkable outcomes in anomaly detection. The exceptional image reconstruction capabilities of recently popular diffusion models have sparked research efforts to utilize them for enhanced reconstruction of anomalous images. Nonetheless, these methods might face challenges related to the preservation of image categories and pixel-wise structural integrity in the more practical multi-class setting. To solve the above problems, we propose a Difusion-based Anomaly Detection (DiAD) framework for multi-class anomaly detection, which consists of a pixel-space autoencoder, a latent-space Semantic-Guided (SG) network with a connection to the stable diffusion's denoising network, and a feature-space pre-trained feature extractor. Firstly, The SG network is proposed for reconstructing anomalous regions while preserving the original image's semantic information. Secondly, we introduce Spatial-aware Feature Fusion (SFF) block to maximize reconstruction accuracy when dealing with extensively reconstructed areas. Thirdly, the input and reconstructed images are processed by a pre-trained feature extractor to generate anomaly maps based on features extracted at different scales. Experiments on MVTec-AD and VisA datasets demonstrate the effectiveness of our approach which surpasses the state-of-the-art methods, e.g., achieving 96.8/52.6 and 97.2/99.0 (AUROC/AP) for localization and detection respectively on multi-class MVTec-AD dataset. Code will be available at https://lewandofskee.github.io/projects/diad.

{{</citation>}}


### (54/161) SmartEdit: Exploring Complex Instruction-based Image Editing with Multimodal Large Language Models (Yuzhou Huang et al., 2023)

{{<citation>}}

Yuzhou Huang, Liangbin Xie, Xintao Wang, Ziyang Yuan, Xiaodong Cun, Yixiao Ge, Jiantao Zhou, Chao Dong, Rui Huang, Ruimao Zhang, Ying Shan. (2023)  
**SmartEdit: Exploring Complex Instruction-based Image Editing with Multimodal Large Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06739v1)  

---


**ABSTRACT**  
Current instruction-based editing methods, such as InstructPix2Pix, often fail to produce satisfactory results in complex scenarios due to their dependence on the simple CLIP text encoder in diffusion models. To rectify this, this paper introduces SmartEdit, a novel approach to instruction-based image editing that leverages Multimodal Large Language Models (MLLMs) to enhance their understanding and reasoning capabilities. However, direct integration of these elements still faces challenges in situations requiring complex reasoning. To mitigate this, we propose a Bidirectional Interaction Module that enables comprehensive bidirectional information interactions between the input image and the MLLM output. During training, we initially incorporate perception data to boost the perception and understanding capabilities of diffusion models. Subsequently, we demonstrate that a small amount of complex instruction editing data can effectively stimulate SmartEdit's editing capabilities for more complex instructions. We further construct a new evaluation dataset, Reason-Edit, specifically tailored for complex instruction-based image editing. Both quantitative and qualitative results on this evaluation dataset indicate that our SmartEdit surpasses previous methods, paving the way for the practical application of complex instruction-based image editing.

{{</citation>}}


### (55/161) Grounded Question-Answering in Long Egocentric Videos (Shangzhe Di et al., 2023)

{{<citation>}}

Shangzhe Di, Weidi Xie. (2023)  
**Grounded Question-Answering in Long Egocentric Videos**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.06505v1)  

---


**ABSTRACT**  
Existing approaches to video understanding, mainly designed for short videos from a third-person perspective, are limited in their applicability in certain fields, such as robotics. In this paper, we delve into open-ended question-answering (QA) in long, egocentric videos, which allows individuals or robots to inquire about their own past visual experiences. This task presents unique challenges, including the complexity of temporally grounding queries within extensive video content, the high resource demands for precise data annotation, and the inherent difficulty of evaluating open-ended answers due to their ambiguous nature. Our proposed approach tackles these challenges by (i) integrating query grounding and answering within a unified model to reduce error propagation; (ii) employing large language models for efficient and scalable data synthesis; and (iii) introducing a close-ended QA task for evaluation, to manage answer ambiguity. Extensive experiments demonstrate the effectiveness of our method, which also achieves state-of-the-art performance on the QAEgo4D and Ego4D-NLQ benchmarks. We plan to publicly release the codes, model, and constructed datasets for future research.

{{</citation>}}


### (56/161) Detecting Events in Crowds Through Changes in Geometrical Dimensions of Pedestrians (Matheus Schreiner Homrich da Silva et al., 2023)

{{<citation>}}

Matheus Schreiner Homrich da Silva, Paulo Brossard de Souza Pinto Neto, Rodolfo Migon Favaretto, Soraia Raupp Musse. (2023)  
**Detecting Events in Crowds Through Changes in Geometrical Dimensions of Pedestrians**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.06495v1)  

---


**ABSTRACT**  
Security is an important topic in our contemporary world, and the ability to automate the detection of any events of interest that can take place in a crowd is of great interest to a population. We hypothesize that the detection of events in videos is correlated with significant changes in pedestrian behaviors. In this paper, we examine three different scenarios of crowd behavior, containing both the cases where an event triggers a change in the behavior of the crowd and two video sequences where the crowd and its motion remain mostly unchanged. With both the videos and the tracking of the individual pedestrians (performed in a pre-processed phase), we use Geomind, a software we developed to extract significant data about the scene, in particular, the geometrical features, personalities, and emotions of each person. We then examine the output, seeking a significant change in the way each person acts as a function of the time, that could be used as a basis to identify events or to model realistic crowd actions. When applied to the games area, our method can use the detected events to find some sort of pattern to be then used in agent simulation. Results indicate that our hypothesis seems valid in the sense that the visually observed events could be automatically detected using GeoMind.

{{</citation>}}


### (57/161) SqueezeSAM: User friendly mobile interactive segmentation (Balakrishnan Varadarajan et al., 2023)

{{<citation>}}

Balakrishnan Varadarajan, Bilge Soran, Forrest Iandola, Xiaoyu Xiang, Yunyang Xiong, Lemeng Wu, Chenchen Zhu, Raghuraman Krishnamoorthi, Vikas Chandra. (2023)  
**SqueezeSAM: User friendly mobile interactive segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06736v1)  

---


**ABSTRACT**  
Segment Anything Model (SAM) is a foundation model for interactive segmentation, and it has catalyzed major advances in generative AI, computational photography, and medical imaging. This model takes in an arbitrary user input and provides segmentation masks of the corresponding objects. It is our goal to develop a version of SAM that is appropriate for use in a photography app. The original SAM model has a few challenges in this setting. First, original SAM a 600 million parameter based on ViT-H, and its high computational cost and large model size that are not suitable for todays mobile hardware. We address this by proposing the SqueezeSAM model architecture, which is 50x faster and 100x smaller than SAM. Next, when a user takes a photo on their phone, it might not occur to them to click on the image and get a mask. Our solution is to use salient object detection to generate the first few clicks. This produces an initial segmentation mask that the user can interactively edit. Finally, when a user clicks on an object, they typically expect all related pieces of the object to be segmented. For instance, if a user clicks on a person t-shirt in a photo, they expect the whole person to be segmented, but SAM typically segments just the t-shirt. We address this with a new data augmentation scheme, and the end result is that if the user clicks on a person holding a basketball, the person and the basketball are all segmented together.

{{</citation>}}


### (58/161) Relevant Intrinsic Feature Enhancement Network for Few-Shot Semantic Segmentation (Xiaoyi Bao et al., 2023)

{{<citation>}}

Xiaoyi Bao, Jie Qin, Siyang Sun, Yun Zheng, Xingang Wang. (2023)  
**Relevant Intrinsic Feature Enhancement Network for Few-Shot Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Few-Shot, Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2312.06474v1)  

---


**ABSTRACT**  
For few-shot semantic segmentation, the primary task is to extract class-specific intrinsic information from limited labeled data. However, the semantic ambiguity and inter-class similarity of previous methods limit the accuracy of pixel-level foreground-background classification. To alleviate these issues, we propose the Relevant Intrinsic Feature Enhancement Network (RiFeNet). To improve the semantic consistency of foreground instances, we propose an unlabeled branch as an efficient data utilization method, which teaches the model how to extract intrinsic features robust to intra-class differences. Notably, during testing, the proposed unlabeled branch is excluded without extra unlabeled data and computation. Furthermore, we extend the inter-class variability between foreground and background by proposing a novel multi-level prototype generation and interaction module. The different-grained complementarity between global and local prototypes allows for better distinction between similar categories. The qualitative and quantitative performance of RiFeNet surpasses the state-of-the-art methods on PASCAL-5i and COCO benchmarks.

{{</citation>}}


### (59/161) ASF-YOLO: A Novel YOLO Model with Attentional Scale Sequence Fusion for Cell Instance Segmentation (Ming Kang et al., 2023)

{{<citation>}}

Ming Kang, Chee-Ming Ting, Fung Fung Ting, Raphaël C. -W. Phan. (2023)  
**ASF-YOLO: A Novel YOLO Model with Attentional Scale Sequence Fusion for Cell Instance Segmentation**  

---
Primary Category: cs.CV  
Categories: 68U10 (Primary) 68T10, 68T07, 62P10 (Secondary), I-4-6; I-5-1; J-3, cs-CV, cs.CV, eess-SP, stat-AP  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.06458v1)  

---


**ABSTRACT**  
We propose a novel Attentional Scale Sequence Fusion based You Only Look Once (YOLO) framework (ASF-YOLO) which combines spatial and scale features for accurate and fast cell instance segmentation. Built on the YOLO segmentation framework, we employ the Scale Sequence Feature Fusion (SSFF) module to enhance the multi-scale information extraction capability of the network, and the Triple Feature Encoder (TPE) module to fuse feature maps of different scales to increase detailed information. We further introduce a Channel and Position Attention Mechanism (CPAM) to integrate both the SSFF and TPE modules, which focus on informative channels and spatial position-related small objects for improved detection and segmentation performance. Experimental validations on two cell datasets show remarkable segmentation accuracy and speed of the proposed ASF-YOLO model. It achieves a box mAP of 0.91, mask mAP of 0.887, and an inference speed of 47.3 FPS on the 2018 Data Science Bowl dataset, outperforming the state-of-the-art methods. The source code is available at https://github.com/mkang315/ASF-YOLO.

{{</citation>}}


### (60/161) VisionTraj: A Noise-Robust Trajectory Recovery Framework based on Large-scale Camera Network (Zhishuai Li et al., 2023)

{{<citation>}}

Zhishuai Li, Ziyue Li, Xiaoru Hu, Guoqing Du, Yunhao Nie, Feng Zhu, Lei Bai, Rui Zhao. (2023)  
**VisionTraj: A Noise-Robust Trajectory Recovery Framework based on Large-scale Camera Network**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs-IR, cs-LG, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06428v1)  

---


**ABSTRACT**  
Trajectory recovery based on the snapshots from the city-wide multi-camera network facilitates urban mobility sensing and driveway optimization. The state-of-the-art solutions devoted to such a vision-based scheme typically incorporate predefined rules or unsupervised iterative feedback, struggling with multi-fold challenges such as lack of open-source datasets for training the whole pipeline, and the vulnerability to the noises from visual inputs. In response to the dilemma, this paper proposes VisionTraj, the first learning-based model that reconstructs vehicle trajectories from snapshots recorded by road network cameras. Coupled with it, we elaborate on two rational vision-trajectory datasets, which produce extensive trajectory data along with corresponding visual snapshots, enabling supervised vision-trajectory interplay extraction. Following the data creation, based on the results from the off-the-shelf multi-modal vehicle clustering, we first re-formulate the trajectory recovery problem as a generative task and introduce the canonical Transformer as the autoregressive backbone. Then, to identify clustering noises (e.g., false positives) with the bound on the snapshots' spatiotemporal dependencies, a GCN-based soft-denoising module is conducted based on the fine- and coarse-grained Re-ID clusters. Additionally, we harness strong semantic information extracted from the tracklet to provide detailed insights into the vehicle's entry and exit actions during trajectory recovery. The denoising and tracklet components can also act as plug-and-play modules to boost baselines. Experimental results on the two hand-crafted datasets show that the proposed VisionTraj achieves a maximum +11.5% improvement against the sub-best model.

{{</citation>}}


### (61/161) Compound Text-Guided Prompt Tuning via Image-Adaptive Cues (Hao Tan et al., 2023)

{{<citation>}}

Hao Tan, Jun Li, Yizhuang Zhou, Jun Wan, Zhen Lei, Xiangyu Zhang. (2023)  
**Compound Text-Guided Prompt Tuning via Image-Adaptive Cues**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06401v1)  

---


**ABSTRACT**  
Vision-Language Models (VLMs) such as CLIP have demonstrated remarkable generalization capabilities to downstream tasks. However, existing prompt tuning based frameworks need to parallelize learnable textual inputs for all categories, suffering from massive GPU memory consumption when there is a large number of categories in the target dataset. Moreover, previous works require to include category names within prompts, exhibiting subpar performance when dealing with ambiguous category names. To address these shortcomings, we propose Compound Text-Guided Prompt Tuning (TGP-T) that significantly reduces resource demand while achieving superior performance. We introduce text supervision to the optimization of prompts, which enables two benefits: 1) releasing the model reliance on the pre-defined category names during inference, thereby enabling more flexible prompt generation; 2) reducing the number of inputs to the text encoder, which decreases GPU memory consumption significantly. Specifically, we found that compound text supervisions, i.e., category-wise and content-wise, is highly effective, since they provide inter-class separability and capture intra-class variations, respectively. Moreover, we condition the prompt generation on visual features through a module called Bonder, which facilitates the alignment between prompts and visual features. Extensive experiments on few-shot recognition and domain generalization demonstrate that TGP-T achieves superior performance with consistently lower training costs. It reduces GPU memory usage by 93% and attains a 2.5% performance gain on 16-shot ImageNet. The code is available at https://github.com/EricTan7/TGP-T.

{{</citation>}}


### (62/161) NuScenes-MQA: Integrated Evaluation of Captions and QA for Autonomous Driving Datasets using Markup Annotations (Yuichi Inoue et al., 2023)

{{<citation>}}

Yuichi Inoue, Yuki Yada, Kotaro Tanahashi, Yu Yamaguchi. (2023)  
**NuScenes-MQA: Integrated Evaluation of Captions and QA for Autonomous Driving Datasets using Markup Annotations**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs.CV  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2312.06352v1)  

---


**ABSTRACT**  
Visual Question Answering (VQA) is one of the most important tasks in autonomous driving, which requires accurate recognition and complex situation evaluations. However, datasets annotated in a QA format, which guarantees precise language generation and scene recognition from driving scenes, have not been established yet. In this work, we introduce Markup-QA, a novel dataset annotation technique in which QAs are enclosed within markups. This approach facilitates the simultaneous evaluation of a model's capabilities in sentence generation and VQA. Moreover, using this annotation methodology, we designed the NuScenes-MQA dataset. This dataset empowers the development of vision language models, especially for autonomous driving tasks, by focusing on both descriptive capabilities and precise QA. The dataset is available at https://github.com/turingmotors/NuScenes-MQA.

{{</citation>}}


### (63/161) Evaluation of Large Language Models for Decision Making in Autonomous Driving (Kotaro Tanahashi et al., 2023)

{{<citation>}}

Kotaro Tanahashi, Yuichi Inoue, Yu Yamaguchi, Hidetatsu Yaginuma, Daiki Shiotsuka, Hiroyuki Shimatani, Kohei Iwamasa, Yoshiaki Inoue, Takafumi Yamaguchi, Koki Igari, Tsukasa Horinouchi, Kento Tokuhiro, Yugo Tokuchi, Shunsuke Aoki. (2023)  
**Evaluation of Large Language Models for Decision Making in Autonomous Driving**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs-RO, cs.CV  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06351v1)  

---


**ABSTRACT**  
Various methods have been proposed for utilizing Large Language Models (LLMs) in autonomous driving. One strategy of using LLMs for autonomous driving involves inputting surrounding objects as text prompts to the LLMs, along with their coordinate and velocity information, and then outputting the subsequent movements of the vehicle. When using LLMs for such purposes, capabilities such as spatial recognition and planning are essential. In particular, two foundational capabilities are required: (1) spatial-aware decision making, which is the ability to recognize space from coordinate information and make decisions to avoid collisions, and (2) the ability to adhere to traffic rules. However, quantitative research has not been conducted on how accurately different types of LLMs can handle these problems. In this study, we quantitatively evaluated these two abilities of LLMs in the context of autonomous driving. Furthermore, to conduct a Proof of Concept (POC) for the feasibility of implementing these abilities in actual vehicles, we developed a system that uses LLMs to drive a vehicle.

{{</citation>}}


### (64/161) Learning Hierarchical Prompt with Structured Linguistic Knowledge for Vision-Language Models (Yubin Wang et al., 2023)

{{<citation>}}

Yubin Wang, Xinyang Jiang, De Cheng, Dongsheng Li, Cairong Zhao. (2023)  
**Learning Hierarchical Prompt with Structured Linguistic Knowledge for Vision-Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06323v1)  

---


**ABSTRACT**  
Prompt learning has become a prevalent strategy for adapting vision-language foundation models to downstream tasks. As large language models (LLMs) have emerged, recent studies have explored the use of category-related descriptions as input to enhance prompt effectiveness. Nevertheless, conventional descriptions fall short of structured information that effectively represents the interconnections among entities or attributes linked to a particular category. To address this limitation and prioritize harnessing structured knowledge, this paper advocates for leveraging LLMs to build a graph for each description to model the entities and attributes describing the category, as well as their correlations. Preexisting prompt tuning methods exhibit inadequacies in managing this structured knowledge. Consequently, we propose a novel approach called Hierarchical Prompt Tuning (HPT), which enables simultaneous modeling of both structured and conventional linguistic knowledge. Specifically, we introduce a relationship-guided attention module to capture pair-wise associations among entities and attributes for low-level prompt learning. In addition, by incorporating high-level and global-level prompts modeling overall semantics, the proposed hierarchical structure forges cross-level interlinks and empowers the model to handle more complex and long-term relationships. Extensive experiments demonstrate that our HPT shows strong effectiveness and generalizes much better than existing SOTA methods. Our code is available at https://github.com/Vill-Lab/2024-AAAI-HPT.

{{</citation>}}


### (65/161) SemiSAM: Exploring SAM for Enhancing Semi-Supervised Medical Image Segmentation with Extremely Limited Annotations (Yichi Zhang et al., 2023)

{{<citation>}}

Yichi Zhang, Yuan Cheng, Yuan Qi. (2023)  
**SemiSAM: Exploring SAM for Enhancing Semi-Supervised Medical Image Segmentation with Extremely Limited Annotations**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2312.06316v1)  

---


**ABSTRACT**  
Semi-supervised learning has attracted much attention due to its less dependence on acquiring abundant annotations from experts compared to fully supervised methods, which is especially important for medical image segmentation which typically requires intensive pixel/voxel-wise labeling by domain experts. Although semi-supervised methods can improve the performance by utilizing unlabeled data, there are still gaps between fully supervised methods under extremely limited annotation scenarios. In this paper, we propose a simple yet efficient strategy to explore the usage of the Segment Anything Model (SAM) for enhancing semi-supervised medical image segmentation. Concretely, the segmentation model trained with domain knowledge provides information for localization and generating input prompts to the SAM. Then the generated pseudo-labels of SAM are utilized as additional supervision to assist in the learning procedure of the semi-supervised framework. Experimental results demonstrate that SAM's assistance significantly enhances the performance of existing semi-supervised frameworks, especially when only one or a few labeled images are available.

{{</citation>}}


### (66/161) Attribute Annotation and Bias Evaluation in Visual Datasets for Autonomous Driving (David Fernández Llorca et al., 2023)

{{<citation>}}

David Fernández Llorca, Pedro Frau, Ignacio Parra, Rubén Izquierdo, Emilia Gómez. (2023)  
**Attribute Annotation and Bias Evaluation in Visual Datasets for Autonomous Driving**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2312.06306v1)  

---


**ABSTRACT**  
This paper addresses the often overlooked issue of fairness in the autonomous driving domain, particularly in vision-based perception and prediction systems, which play a pivotal role in the overall functioning of Autonomous Vehicles (AVs). We focus our analysis on biases present in some of the most commonly used visual datasets for training person and vehicle detection systems. We introduce an annotation methodology and a specialised annotation tool, both designed to annotate protected attributes of agents in visual datasets. We validate our methodology through an inter-rater agreement analysis and provide the distribution of attributes across all datasets. These include annotations for the attributes age, sex, skin tone, group, and means of transport for more than 90K people, as well as vehicle type, colour, and car type for over 50K vehicles. Generally, diversity is very low for most attributes, with some groups, such as children, wheelchair users, or personal mobility vehicle users, being extremely underrepresented in the analysed datasets. The study contributes significantly to efforts to consider fairness in the evaluation of perception and prediction systems for AVs. This paper follows reproducibility principles. The annotation tool, scripts and the annotated attributes can be accessed publicly at https://github.com/ec-jrc/humaint_annotator.

{{</citation>}}


### (67/161) TULIP: Transformer for Upsampling of LiDAR Point Cloud (Bin Yang et al., 2023)

{{<citation>}}

Bin Yang, Patrick Pfreundschuh, Roland Siegwart, Marco Hutter, Peyman Moghadam, Vaishakh Patil. (2023)  
**TULIP: Transformer for Upsampling of LiDAR Point Cloud**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06733v2)  

---


**ABSTRACT**  
LiDAR Upsampling is a challenging task for the perception systems of robots and autonomous vehicles, due to the sparse and irregular structure of large-scale scene contexts. Recent works propose to solve this problem by converting LiDAR data from 3D Euclidean space into an image super-resolution problem in 2D image space. Although their methods can generate high-resolution range images with fine-grained details, the resulting 3D point clouds often blur out details and predict invalid points. In this paper, we propose TULIP, a new method to reconstruct high-resolution LiDAR point clouds from low-resolution LiDAR input. We also follow a range image-based approach but specifically modify the patch and window geometries of a Swin-Transformer-based network to better fit the characteristics of range images. We conducted several experiments on three different public real-world and simulated datasets. TULIP outperforms state-of-the-art methods in all relevant metrics and generates robust and more realistic point clouds than prior works.

{{</citation>}}


### (68/161) U-MixFormer: UNet-like Transformer with Mix-Attention for Efficient Semantic Segmentation (Seul-Ki Yeom et al., 2023)

{{<citation>}}

Seul-Ki Yeom, Julian von Klitzing. (2023)  
**U-MixFormer: UNet-like Transformer with Mix-Attention for Efficient Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Semantic Segmentation, Transformer  
[Paper Link](http://arxiv.org/abs/2312.06272v1)  

---


**ABSTRACT**  
Semantic segmentation has witnessed remarkable advancements with the adaptation of the Transformer architecture. Parallel to the strides made by the Transformer, CNN-based U-Net has seen significant progress, especially in high-resolution medical imaging and remote sensing. This dual success inspired us to merge the strengths of both, leading to the inception of a U-Net-based vision transformer decoder tailored for efficient contextual encoding. Here, we propose a novel transformer decoder, U-MixFormer, built upon the U-Net structure, designed for efficient semantic segmentation. Our approach distinguishes itself from the previous transformer methods by leveraging lateral connections between the encoder and decoder stages as feature queries for the attention modules, apart from the traditional reliance on skip connections. Moreover, we innovatively mix hierarchical feature maps from various encoder and decoder stages to form a unified representation for keys and values, giving rise to our unique mix-attention module. Our approach demonstrates state-of-the-art performance across various configurations. Extensive experiments show that U-MixFormer outperforms SegFormer, FeedFormer, and SegNeXt by a large margin. For example, U-MixFormer-B0 surpasses SegFormer-B0 and FeedFormer-B0 with 3.8% and 2.0% higher mIoU and 27.3% and 21.8% less computation and outperforms SegNext with 3.3% higher mIoU with MSCAN-T encoder on ADE20K. Code available at https://github.com/julian-klitzing/u-mixformer.

{{</citation>}}


### (69/161) Adaptive Annotation Distribution for Weakly Supervised Point Cloud Semantic Segmentation (Zhiyi Pan et al., 2023)

{{<citation>}}

Zhiyi Pan, Nan Zhang, Wei Gao, Shan Liu, Ge Li. (2023)  
**Adaptive Annotation Distribution for Weakly Supervised Point Cloud Semantic Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semantic Segmentation  
[Paper Link](http://arxiv.org/abs/2312.06259v1)  

---


**ABSTRACT**  
Weakly supervised point cloud semantic segmentation has attracted a lot of attention due to its ability to alleviate the heavy reliance on fine-grained annotations of point clouds. However, in practice, sparse annotation usually exhibits a distinct non-uniform distribution in point cloud, which poses challenges for weak supervision. To address these issues, we propose an adaptive annotation distribution method for weakly supervised point cloud semantic segmentation. Specifically, we introduce the probability density function into the gradient sampling approximation analysis and investigate the impact of sparse annotations distributions. Based on our analysis, we propose a label-aware point cloud downsampling strategy to increase the proportion of annotations involved in the training stage. Furthermore, we design the multiplicative dynamic entropy as the gradient calibration function to mitigate the gradient bias caused by non-uniformly distributed sparse annotations and explicitly reduce the epistemic uncertainty. Without any prior restrictions and additional information, our proposed method achieves comprehensive performance improvements at multiple label rates with different annotation distributions on S3DIS, ScanNetV2 and SemanticKITTI.

{{</citation>}}


### (70/161) Style Injection in Diffusion: A Training-free Approach for Adapting Large-scale Diffusion Models for Style Transfer (Jiwoo Chung et al., 2023)

{{<citation>}}

Jiwoo Chung, Sangeek Hyun, Jae-Pil Heo. (2023)  
**Style Injection in Diffusion: A Training-free Approach for Adapting Large-scale Diffusion Models for Style Transfer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Style Transfer  
[Paper Link](http://arxiv.org/abs/2312.09008v1)  

---


**ABSTRACT**  
Despite the impressive generative capabilities of diffusion models, existing diffusion model-based style transfer methods require inference-stage optimization (e.g. fine-tuning or textual inversion of style) which is time-consuming, or fails to leverage the generative ability of large-scale diffusion models. To address these issues, we introduce a novel artistic style transfer method based on a pre-trained large-scale diffusion model without any optimization. Specifically, we manipulate the features of self-attention layers as the way the cross-attention mechanism works; in the generation process, substituting the key and value of content with those of style image. This approach provides several desirable characteristics for style transfer including 1) preservation of content by transferring similar styles into similar image patches and 2) transfer of style based on similarity of local texture (e.g. edge) between content and style images. Furthermore, we introduce query preservation and attention temperature scaling to mitigate the issue of disruption of original content, and initial latent Adaptive Instance Normalization (AdaIN) to deal with the disharmonious color (failure to transfer the colors of style). Our experimental results demonstrate that our proposed method surpasses state-of-the-art methods in both conventional and diffusion-based style transfer baselines.

{{</citation>}}


### (71/161) Genixer: Empowering Multimodal Large Language Models as a Powerful Data Generator (Henry Hengyuan Zhao et al., 2023)

{{<citation>}}

Henry Hengyuan Zhao, Pan Zhou, Mike Zheng Shou. (2023)  
**Genixer: Empowering Multimodal Large Language Models as a Powerful Data Generator**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: GPT, GPT-4, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.06731v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) excel in understanding human instructions, driving the development of Multimodal LLMs (MLLMs) with instruction tuning. However, acquiring high-quality multimodal instruction tuning data poses a significant challenge. Previous approaches relying on GPT-4 for data generation proved expensive and exhibited unsatisfactory performance for certain tasks. To solve this, we present Genixer, an innovative data generation pipeline producing high-quality multimodal instruction tuning data for various tasks. Genixer collects datasets for ten prevalent multimodal tasks and designs instruction templates to transform these datasets into instruction-tuning data. It then trains pretrained MLLMs to generate task-specific instruction data and proposes an effective data filtering strategy to ensure high quality. To evaluate Genixer, a base MLLM model, Kakapo, is built and achieves SoTA performance in image captioning and visual question answering (VQA) tasks across multiple datasets. Experimental results show that filtered data from Genixer continually improves Kakapo for image captioning and VQA tasks. For the SoTA Shikra MLLM model on the image-region-related tasks, e.g., region caption and detection, Genixer also successfully generates corresponding data and improves its performance. Genixer opens avenues for generating high-quality multimodal instruction data for diverse tasks, enabling innovative applications across domains. The code and models will be released soon.

{{</citation>}}


### (72/161) Invariant Representation Learning via Decoupling Style and Spurious Features (Ruimeng Li et al., 2023)

{{<citation>}}

Ruimeng Li, Yuanhao Pu, Zhaoyi Li, Hong Xie, Defu Lian. (2023)  
**Invariant Representation Learning via Decoupling Style and Spurious Features**  

---
Primary Category: cs.CV  
Categories: I-2-6; I-2-10, cs-AI, cs-CV, cs.CV  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2312.06226v1)  

---


**ABSTRACT**  
This paper considers the out-of-distribution (OOD) generalization problem under the setting that both style distribution shift and spurious features exist and domain labels are missing. This setting frequently arises in real-world applications and is underlooked because previous approaches mainly handle either of these two factors. The critical challenge is decoupling style and spurious features in the absence of domain labels. To address this challenge, we first propose a structural causal model (SCM) for the image generation process, which captures both style distribution shift and spurious features. The proposed SCM enables us to design a new framework called IRSS, which can gradually separate style distribution and spurious features from images by introducing adversarial neural networks and multi-environment optimization, thus achieving OOD generalization. Moreover, it does not require additional supervision (e.g., domain labels) other than the images and their corresponding labels. Experiments on benchmark datasets demonstrate that IRSS outperforms traditional OOD methods and solves the problem of Invariant risk minimization (IRM) degradation, enabling the extraction of invariant features under distribution shift.

{{</citation>}}


### (73/161) Towards Transferable Adversarial Attacks with Centralized Perturbation (Shangbo Wu et al., 2023)

{{<citation>}}

Shangbo Wu, Yu-an Tan, Yajie Wang, Ruinan Ma, Wencong Ma, Yuanzhang Li. (2023)  
**Towards Transferable Adversarial Attacks with Centralized Perturbation**  

---
Primary Category: cs.CV  
Categories: cs-CR, cs-CV, cs-LG, cs.CV  
Keywords: Adversarial Attack  
[Paper Link](http://arxiv.org/abs/2312.06199v1)  

---


**ABSTRACT**  
Adversarial transferability enables black-box attacks on unknown victim deep neural networks (DNNs), rendering attacks viable in real-world scenarios. Current transferable attacks create adversarial perturbation over the entire image, resulting in excessive noise that overfit the source model. Concentrating perturbation to dominant image regions that are model-agnostic is crucial to improving adversarial efficacy. However, limiting perturbation to local regions in the spatial domain proves inadequate in augmenting transferability. To this end, we propose a transferable adversarial attack with fine-grained perturbation optimization in the frequency domain, creating centralized perturbation. We devise a systematic pipeline to dynamically constrain perturbation optimization to dominant frequency coefficients. The constraint is optimized in parallel at each iteration, ensuring the directional alignment of perturbation optimization with model prediction. Our approach allows us to centralize perturbation towards sample-specific important frequency features, which are shared by DNNs, effectively mitigating source model overfitting. Experiments demonstrate that by dynamically centralizing perturbation on dominating frequency coefficients, crafted adversarial examples exhibit stronger transferability, and allowing them to bypass various defenses.

{{</citation>}}


### (74/161) Bag of Tricks: Semi-Supervised Cross-domain Crater Detection with Poor Data Quality (Yifan Liu et al., 2023)

{{<citation>}}

Yifan Liu, Tiecheng Song. (2023)  
**Bag of Tricks: Semi-Supervised Cross-domain Crater Detection with Poor Data Quality**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2312.06169v1)  

---


**ABSTRACT**  
With the development of spaceflight and the exploration of extraterrestrial planets, exoplanet crater detection has gradually gained attention. However, with the current scarcity of relevant datasets, high sample background complexity, and large inter-domain differences, few existing detection models can achieve good robustness and generalization across domains by training on data with more background interference. To obtain a better robust model with better cross-domain generalization in the presence of poor data quality, we propose the SCPQ model, in which we first propose a method for fusing shallow information using attention mechanism (FSIAM), which utilizes feature maps fused with deep convolved feature maps after fully extracting the global sensory field of shallow information via the attention mechanism module, which can fully fit the data to obtain a better sense of the domain in the presence of poor data, and thus better multiscale adaptability. Secondly, we propose a pseudo-label and data augment strategy (PDAS) and a smooth hard example mining (SHEM) loss function to improve cross-domain performance. PDAS adopts high-quality pseudo-labeled data from the target domain to the finetune model, and adopts different strong and weak data enhancement strategies for different domains, which mitigates the different distribution of information inherent in the source and target domains, and obtains a better generalization effect. Meanwhile, our proposed SHEM loss function can solve the problem of poor robustness of hard examples due to partial background interference learning during the training process. The SHEM loss function can smooth this interference and has generalization while learning hard examples. Experimental results show that we achieved better performance on the DACD dataset and improved the Recall of cross-domain detection by 24.04\% over baseline.

{{</citation>}}


### (75/161) Textual Prompt Guided Image Restoration (Qiuhai Yan et al., 2023)

{{<citation>}}

Qiuhai Yan, Aiwen Jiang, Kang Chen, Long Peng, Qiaosi Yi, Chunjie Zhang. (2023)  
**Textual Prompt Guided Image Restoration**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI, BERT  
[Paper Link](http://arxiv.org/abs/2312.06162v1)  

---


**ABSTRACT**  
Image restoration has always been a cutting-edge topic in the academic and industrial fields of computer vision. Since degradation signals are often random and diverse, "all-in-one" models that can do blind image restoration have been concerned in recent years. Early works require training specialized headers and tails to handle each degradation of concern, which are manually cumbersome. Recent works focus on learning visual prompts from data distribution to identify degradation type. However, the prompts employed in most of models are non-text, lacking sufficient emphasis on the importance of human-in-the-loop. In this paper, an effective textual prompt guided image restoration model has been proposed. In this model, task-specific BERT is fine-tuned to accurately understand user's instructions and generating textual prompt guidance. Depth-wise multi-head transposed attentions and gated convolution modules are designed to bridge the gap between textual prompts and visual features. The proposed model has innovatively introduced semantic prompts into low-level visual domain. It highlights the potential to provide a natural, precise, and controllable way to perform image restoration tasks. Extensive experiments have been done on public denoising, dehazing and deraining datasets. The experiment results demonstrate that, compared with popular state-of-the-art methods, the proposed model can obtain much more superior performance, achieving accurate recognition and removal of degradation without increasing model's complexity. Related source codes and data will be publicly available on github site https://github.com/MoTong-AI-studio/TextPromptIR.

{{</citation>}}


### (76/161) Adaptive Feature Selection for No-Reference Image Quality Assessment using Contrastive Mitigating Semantic Noise Sensitivity (Xudong Li et al., 2023)

{{<citation>}}

Xudong Li, Timin Gao, Xiawu Zheng, Runze Hu, Jingyuan Zheng, Yunhang Shen, Ke Li, Yutao Liu, Pingyang Dai, Yan Zhang, Rongrong Ji. (2023)  
**Adaptive Feature Selection for No-Reference Image Quality Assessment using Contrastive Mitigating Semantic Noise Sensitivity**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.06158v1)  

---


**ABSTRACT**  
The current state-of-the-art No-Reference Image Quality Assessment (NR-IQA) methods typically use feature extraction in upstream backbone networks, which assumes that all extracted features are relevant. However, we argue that not all features are beneficial, and some may even be harmful, necessitating careful selection. Empirically, we find that many image pairs with small feature spatial distances can have vastly different quality scores. To address this issue, we propose a Quality-Aware Feature Matching IQA metric(QFM-IQM) that employs contrastive learning to remove harmful features from the upstream task. Specifically, our approach enhances the semantic noise distinguish capabilities of neural networks by comparing image pairs with similar semantic features but varying quality scores and adaptively adjusting the upstream task's features by introducing disturbance. Furthermore, we utilize a distillation framework to expand the dataset and improve the model's generalization ability. Our approach achieves superior performance to the state-of-the-art NR-IQA methods on 8 standard NR-IQA datasets, achieving PLCC values of 0.932 (vs. 0.908 in TID2013) and 0.913 (vs. 0.894 in LIVEC).

{{</citation>}}


### (77/161) BACTrack: Building Appearance Collection for Aerial Tracking (Xincong Liu et al., 2023)

{{<citation>}}

Xincong Liu, Tingfa Xu, Ying Wang, Zhinong Yu, Xiaoying Yuan, Haolin Qin, Jianan Li. (2023)  
**BACTrack: Building Appearance Collection for Aerial Tracking**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06136v1)  

---


**ABSTRACT**  
Siamese network-based trackers have shown remarkable success in aerial tracking. Most previous works, however, usually perform template matching only between the initial template and the search region and thus fail to deal with rapidly changing targets that often appear in aerial tracking. As a remedy, this work presents Building Appearance Collection Tracking (BACTrack). This simple yet effective tracking framework builds a dynamic collection of target templates online and performs efficient multi-template matching to achieve robust tracking. Specifically, BACTrack mainly comprises a Mixed-Temporal Transformer (MTT) and an appearance discriminator. The former is responsible for efficiently building relationships between the search region and multiple target templates in parallel through a mixed-temporal attention mechanism. At the same time, the appearance discriminator employs an online adaptive template-update strategy to ensure that the collected multiple templates remain reliable and diverse, allowing them to closely follow rapid changes in the target's appearance and suppress background interference during tracking. Extensive experiments show that our BACTrack achieves top performance on four challenging aerial tracking benchmarks while maintaining an impressive speed of over 87 FPS on a single GPU. Speed tests on embedded platforms also validate our potential suitability for deployment on UAV platforms.

{{</citation>}}


### (78/161) ArtBank: Artistic Style Transfer with Pre-trained Diffusion Model and Implicit Style Prompt Bank (Zhanjie Zhang et al., 2023)

{{<citation>}}

Zhanjie Zhang, Quanwei Zhang, Guangyuan Li, Wei Xing, Lei Zhao, Jiakai Sun, Zehua Lan, Junsheng Luan, Yiling Huang, Huaizhong Lin. (2023)  
**ArtBank: Artistic Style Transfer with Pre-trained Diffusion Model and Implicit Style Prompt Bank**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Style Transfer  
[Paper Link](http://arxiv.org/abs/2312.06135v1)  

---


**ABSTRACT**  
Artistic style transfer aims to repaint the content image with the learned artistic style. Existing artistic style transfer methods can be divided into two categories: small model-based approaches and pre-trained large-scale model-based approaches. Small model-based approaches can preserve the content strucuture, but fail to produce highly realistic stylized images and introduce artifacts and disharmonious patterns; Pre-trained large-scale model-based approaches can generate highly realistic stylized images but struggle with preserving the content structure. To address the above issues, we propose ArtBank, a novel artistic style transfer framework, to generate highly realistic stylized images while preserving the content structure of the content images. Specifically, to sufficiently dig out the knowledge embedded in pre-trained large-scale models, an Implicit Style Prompt Bank (ISPB), a set of trainable parameter matrices, is designed to learn and store knowledge from the collection of artworks and behave as a visual prompt to guide pre-trained large-scale models to generate highly realistic stylized images while preserving content structure. Besides, to accelerate training the above ISPB, we propose a novel Spatial-Statistical-based self-Attention Module (SSAM). The qualitative and quantitative experiments demonstrate the superiority of our proposed method over state-of-the-art artistic style transfer methods.

{{</citation>}}


### (79/161) SimMining-3D: Altitude-Aware 3D Object Detection in Complex Mining Environments: A Novel Dataset and ROS-Based Automatic Annotation Pipeline (Mehala Balamurali et al., 2023)

{{<citation>}}

Mehala Balamurali, Ehsan Mihankhah. (2023)  
**SimMining-3D: Altitude-Aware 3D Object Detection in Complex Mining Environments: A Novel Dataset and ROS-Based Automatic Annotation Pipeline**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2312.06113v1)  

---


**ABSTRACT**  
Accurate and efficient object detection is crucial for safe and efficient operation of earth-moving equipment in mining. Traditional 2D image-based methods face limitations in dynamic and complex mine environments. To overcome these challenges, 3D object detection using point cloud data has emerged as a comprehensive approach. However, training models for mining scenarios is challenging due to sensor height variations, viewpoint changes, and the need for diverse annotated datasets. This paper presents novel contributions to address these challenges. We introduce a synthetic dataset SimMining 3D [1] specifically designed for 3D object detection in mining environments. The dataset captures objects and sensors positioned at various heights within mine benches, accurately reflecting authentic mining scenarios. An automatic annotation pipeline through ROS interface reduces manual labor and accelerates dataset creation. We propose evaluation metrics accounting for sensor-to-object height variations and point cloud density, enabling accurate model assessment in mining scenarios. Real data tests validate our models effectiveness in object prediction. Our ablation study emphasizes the importance of altitude and height variation augmentations in improving accuracy and reliability. The publicly accessible synthetic dataset [1] serves as a benchmark for supervised learning and advances object detection techniques in mining with complimentary pointwise annotations for each scene. In conclusion, our work bridges the gap between synthetic and real data, addressing the domain shift challenge in 3D object detection for mining. We envision robust object detection systems enhancing safety and efficiency in mining and related domains.

{{</citation>}}


### (80/161) Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models (Haoran Wei et al., 2023)

{{<citation>}}

Haoran Wei, Lingyu Kong, Jinyue Chen, Liang Zhao, Zheng Ge, Jinrong Yang, Jianjian Sun, Chunrui Han, Xiangyu Zhang. (2023)  
**Vary: Scaling up the Vision Vocabulary for Large Vision-Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT, Language Model, OCR, QA  
[Paper Link](http://arxiv.org/abs/2312.06109v1)  

---


**ABSTRACT**  
Modern Large Vision-Language Models (LVLMs) enjoy the same vision vocabulary -- CLIP, which can cover most common vision tasks. However, for some special vision task that needs dense and fine-grained vision perception, e.g., document-level OCR or chart understanding, especially in non-English scenarios, the CLIP-style vocabulary may encounter low efficiency in tokenizing the vision knowledge and even suffer out-of-vocabulary problem. Accordingly, we propose Vary, an efficient and effective method to scale up the vision vocabulary of LVLMs. The procedures of Vary are naturally divided into two folds: the generation and integration of a new vision vocabulary. In the first phase, we devise a vocabulary network along with a tiny decoder-only transformer to produce the desired vocabulary via autoregression. In the next, we scale up the vanilla vision vocabulary by merging the new one with the original one (CLIP), enabling the LVLMs can quickly garner new features. Compared to the popular BLIP-2, MiniGPT4, and LLaVA, Vary can maintain its vanilla capabilities while enjoying more excellent fine-grained perception and understanding ability. Specifically, Vary is competent in new document parsing features (OCR or markdown conversion) while achieving 78.2% ANLS in DocVQA and 36.2% in MMVet. Our code will be publicly available on the homepage.

{{</citation>}}


### (81/161) EgoPlan-Bench: Benchmarking Egocentric Embodied Planning with Multimodal Large Language Models (Yi Chen et al., 2023)

{{<citation>}}

Yi Chen, Yuying Ge, Yixiao Ge, Mingyu Ding, Bohao Li, Rui Wang, Ruifeng Xu, Ying Shan, Xihui Liu. (2023)  
**EgoPlan-Bench: Benchmarking Egocentric Embodied Planning with Multimodal Large Language Models**  

---
Primary Category: cs.CV  
Categories: cs-CL, cs-CV, cs-RO, cs.CV  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06722v1)  

---


**ABSTRACT**  
Multimodal Large Language Models (MLLMs), building upon the powerful Large Language Models (LLMs) with exceptional reasoning and generalization capability, have opened up new avenues for embodied task planning. MLLMs excel in their ability to integrate diverse environmental inputs, such as real-time task progress, visual observations, and open-form language instructions, which are crucial for executable task planning. In this work, we introduce a benchmark with human annotations, EgoPlan-Bench, to quantitatively investigate the potential of MLLMs as embodied task planners in real-world scenarios. Our benchmark is distinguished by realistic tasks derived from real-world videos, a diverse set of actions involving interactions with hundreds of different objects, and complex visual observations from varied environments. We evaluate various open-source MLLMs, revealing that these models have not yet evolved into embodied planning generalists (even GPT-4V). We further construct an instruction-tuning dataset EgoPlan-IT from videos of human-object interactions, to facilitate the learning of high-level task planning in intricate real-world situations. The experiment results demonstrate that the model tuned on EgoPlan-IT not only significantly improves performance on our benchmark, but also effectively acts as embodied planner in simulations.

{{</citation>}}


### (82/161) Audio-Visual LLM for Video Understanding (Fangxun Shu et al., 2023)

{{<citation>}}

Fangxun Shu, Lei Zhang, Hao Jiang, Cihang Xie. (2023)  
**Audio-Visual LLM for Video Understanding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT, GPT-4, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.06720v2)  

---


**ABSTRACT**  
This paper presents Audio-Visual LLM, a Multimodal Large Language Model that takes both visual and auditory inputs for holistic video understanding. A key design is the modality-augmented training, which involves the integration of modality-specific tokens engineered to activate the appropriate visual and/or auditory encoder selectively. This mechanism is pivotal in enabling end-to-end joint training with video data at different modalities, including visual-only, audio-only, and audio-visual formats. Moreover, we introduce a high-quality video instruction dataset, derived from GPT-4. This dataset allows Audio-Visual LLM to adeptly process a variety of task-oriented video instructions, ranging from multi-turn conversations and audio-visual narratives to complex reasoning tasks. Extensive experiments demonstrate that Audio-Visual LLM impressively achieves strong zero-shot results across a range of video understanding tasks. For example, Audio-Visual LLM achieves an accuracy of 53.7% on MSRVTT-QA, outperforming non-LLM-based InterVideo by 6.6% and LLM-based Valley by 4.4%, respectively. Additionally, our Audio-Visual LLM also achieves competitive performance on audio tasks (e.g., AudioCaps).

{{</citation>}}


### (83/161) Mining Gaze for Contrastive Learning toward Computer-Assisted Diagnosis (Zihao Zhao et al., 2023)

{{<citation>}}

Zihao Zhao, Sheng Wang, Qian Wang, Dinggang Shen. (2023)  
**Mining Gaze for Contrastive Learning toward Computer-Assisted Diagnosis**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.06069v2)  

---


**ABSTRACT**  
Obtaining large-scale radiology reports can be difficult for medical images due to various reasons, limiting the effectiveness of contrastive pre-training in the medical image domain and underscoring the need for alternative methods. In this paper, we propose eye-tracking as an alternative to text reports, as it allows for the passive collection of gaze signals without disturbing radiologist's routine diagnosis process. By tracking the gaze of radiologists as they read and diagnose medical images, we can understand their visual attention and clinical reasoning. When a radiologist has similar gazes for two medical images, it may indicate semantic similarity for diagnosis, and these images should be treated as positive pairs when pre-training a computer-assisted diagnosis (CAD) network through contrastive learning. Accordingly, we introduce the Medical contrastive Gaze Image Pre-training (McGIP) as a plug-and-play module for contrastive learning frameworks. McGIP uses radiologist's gaze to guide contrastive pre-training. We evaluate our method using two representative types of medical images and two common types of gaze data. The experimental results demonstrate the practicality of McGIP, indicating its high potential for various clinical scenarios and applications.

{{</citation>}}


### (84/161) Contrastive Multi-view Subspace Clustering of Hyperspectral Images based on Graph Convolutional Networks (Renxiang Guan et al., 2023)

{{<citation>}}

Renxiang Guan, Zihao Li, Xianju Li, Chang Tang, Ruyi Feng. (2023)  
**Contrastive Multi-view Subspace Clustering of Hyperspectral Images based on Graph Convolutional Networks**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Graph Convolutional Network  
[Paper Link](http://arxiv.org/abs/2312.06068v1)  

---


**ABSTRACT**  
High-dimensional and complex spectral structures make the clustering of hyperspectral images (HSI) a challenging task. Subspace clustering is an effective approach for addressing this problem. However, current subspace clustering algorithms are primarily designed for a single view and do not fully exploit the spatial or textural feature information in HSI. In this study, contrastive multi-view subspace clustering of HSI was proposed based on graph convolutional networks. Pixel neighbor textural and spatial-spectral information were sent to construct two graph convolutional subspaces to learn their affinity matrices. To maximize the interaction between different views, a contrastive learning algorithm was introduced to promote the consistency of positive samples and assist the model in extracting robust features. An attention-based fusion module was used to adaptively integrate these affinity matrices, constructing a more discriminative affinity matrix. The model was evaluated using four popular HSI datasets: Indian Pines, Pavia University, Houston, and Xu Zhou. It achieved overall accuracies of 97.61%, 96.69%, 87.21%, and 97.65%, respectively, and significantly outperformed state-of-the-art clustering methods. In conclusion, the proposed model effectively improves the clustering accuracy of HSI.

{{</citation>}}


## cs.CY (1)



### (85/161) Disentangling Perceptions of Offensiveness: Cultural and Moral Correlates (Aida Davani et al., 2023)

{{<citation>}}

Aida Davani, Mark Díaz, Dylan Baker, Vinodkumar Prabhakaran. (2023)  
**Disentangling Perceptions of Offensiveness: Cultural and Moral Correlates**  

---
Primary Category: cs.CY  
Categories: cs-CL, cs-CY, cs.CY  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2312.06861v1)  

---


**ABSTRACT**  
Perception of offensiveness is inherently subjective, shaped by the lived experiences and socio-cultural values of the perceivers. Recent years have seen substantial efforts to build AI-based tools that can detect offensive language at scale, as a means to moderate social media platforms, and to ensure safety of conversational AI technologies such as ChatGPT and Bard. However, existing approaches treat this task as a technical endeavor, built on top of data annotated for offensiveness by a global crowd workforce without any attention to the crowd workers' provenance or the values their perceptions reflect. We argue that cultural and psychological factors play a vital role in the cognitive processing of offensiveness, which is critical to consider in this context. We re-frame the task of determining offensiveness as essentially a matter of moral judgment -- deciding the boundaries of ethically wrong vs. right language within an implied set of socio-cultural norms. Through a large-scale cross-cultural study based on 4309 participants from 21 countries across 8 cultural regions, we demonstrate substantial cross-cultural differences in perceptions of offensiveness. More importantly, we find that individual moral values play a crucial role in shaping these variations: moral concerns about Care and Purity are significant mediating factors driving cross-cultural differences. These insights are of crucial importance as we build AI models for the pluralistic world, where the values they espouse should aim to respect and account for moral values in diverse geo-cultural contexts.

{{</citation>}}


## physics.space-ph (1)



### (86/161) Self-supervised Machine Learning Based Approach to Orbit Modelling Applied to Space Traffic Management (Emma Stevenson et al., 2023)

{{<citation>}}

Emma Stevenson, Victor Rodriguez-Fernandez, Hodei Urrutxua, Vincent Morand, David Camacho. (2023)  
**Self-supervised Machine Learning Based Approach to Orbit Modelling Applied to Space Traffic Management**  

---
Primary Category: physics.space-ph  
Categories: cs-LG, physics-space-ph, physics.space-ph  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2312.06854v1)  

---


**ABSTRACT**  
This paper presents a novel methodology for improving the performance of machine learning based space traffic management tasks through the use of a pre-trained orbit model. Taking inspiration from BERT-like self-supervised language models in the field of natural language processing, we introduce ORBERT, and demonstrate the ability of such a model to leverage large quantities of readily available orbit data to learn meaningful representations that can be used to aid in downstream tasks. As a proof of concept of this approach we consider the task of all vs. all conjunction screening, phrased here as a machine learning time series classification task. We show that leveraging unlabelled orbit data leads to improved performance, and that the proposed approach can be particularly beneficial for tasks where the availability of labelled data is limited.

{{</citation>}}


## cs.AI (17)



### (87/161) LLF-Bench: Benchmark for Interactive Learning from Language Feedback (Ching-An Cheng et al., 2023)

{{<citation>}}

Ching-An Cheng, Andrey Kolobov, Dipendra Misra, Allen Nie, Adith Swaminathan. (2023)  
**LLF-Bench: Benchmark for Interactive Learning from Language Feedback**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06853v2)  

---


**ABSTRACT**  
We introduce a new benchmark, LLF-Bench (Learning from Language Feedback Benchmark; pronounced as "elf-bench"), to evaluate the ability of AI agents to interactively learn from natural language feedback and instructions. Learning from language feedback (LLF) is essential for people, largely because the rich information this feedback provides can help a learner avoid much of trial and error and thereby speed up the learning process. Large Language Models (LLMs) have recently enabled AI agents to comprehend natural language -- and hence AI agents can potentially benefit from language feedback during learning like humans do. But existing interactive benchmarks do not assess this crucial capability: they either use numeric reward feedback or require no learning at all (only planning or information retrieval). LLF-Bench is designed to fill this omission. LLF-Bench is a diverse collection of sequential decision-making tasks that includes user recommendation, poem writing, navigation, and robot control. The objective of an agent is to interactively solve these tasks based on their natural-language instructions and the feedback received after taking actions. Crucially, to ensure that the agent actually "learns" from the feedback, LLF-Bench implements several randomization techniques (such as paraphrasing and environment randomization) to ensure that the task isn't familiar to the agent and that the agent is robust to various verbalizations. In addition, LLF-Bench provides a unified OpenAI Gym interface for all its tasks and allows the users to easily configure the information the feedback conveys (among suggestion, explanation, and instantaneous performance) to study how agents respond to different types of feedback. Together, these features make LLF-Bench a unique research platform for developing and testing LLF agents.

{{</citation>}}


### (88/161) User Friendly and Adaptable Discriminative AI: Using the Lessons from the Success of LLMs and Image Generation Models (Son The Nguyen et al., 2023)

{{<citation>}}

Son The Nguyen, Theja Tulabandhula, Mary Beth Watson-Manheim. (2023)  
**User Friendly and Adaptable Discriminative AI: Using the Lessons from the Success of LLMs and Image Generation Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-HC, cs.AI  
Keywords: AI, GPT  
[Paper Link](http://arxiv.org/abs/2312.06826v1)  

---


**ABSTRACT**  
While there is significant interest in using generative AI tools as general-purpose models for specific ML applications, discriminative models are much more widely deployed currently. One of the key shortcomings of these discriminative AI tools that have been already deployed is that they are not adaptable and user-friendly compared to generative AI tools (e.g., GPT4, Stable Diffusion, Bard, etc.), where a non-expert user can iteratively refine model inputs and give real-time feedback that can be accounted for immediately, allowing users to build trust from the start. Inspired by this emerging collaborative workflow, we develop a new system architecture that enables users to work with discriminative models (such as for object detection, sentiment classification, etc.) in a fashion similar to generative AI tools, where they can easily provide immediate feedback as well as adapt the deployed models as desired. Our approach has implications on improving trust, user-friendliness, and adaptability of these versatile but traditional prediction models.

{{</citation>}}


### (89/161) Extracting Self-Consistent Causal Insights from Users Feedback with LLMs and In-context Learning (Sara Abdali et al., 2023)

{{<citation>}}

Sara Abdali, Anjali Parikh, Steve Lim, Emre Kiciman. (2023)  
**Extracting Self-Consistent Causal Insights from Users Feedback with LLMs and In-context Learning**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI, stat-ME  
Keywords: Language Model, Microsoft  
[Paper Link](http://arxiv.org/abs/2312.06820v1)  

---


**ABSTRACT**  
Microsoft Windows Feedback Hub is designed to receive customer feedback on a wide variety of subjects including critical topics such as power and battery. Feedback is one of the most effective ways to have a grasp of users' experience with Windows and its ecosystem. However, the sheer volume of feedback received by Feedback Hub makes it immensely challenging to diagnose the actual cause of reported issues. To better understand and triage issues, we leverage Double Machine Learning (DML) to associate users' feedback with telemetry signals. One of the main challenges we face in the DML pipeline is the necessity of domain knowledge for model design (e.g., causal graph), which sometimes is either not available or hard to obtain. In this work, we take advantage of reasoning capabilities in Large Language Models (LLMs) to generate a prior model that which to some extent compensates for the lack of domain knowledge and could be used as a heuristic for measuring feedback informativeness. Our LLM-based approach is able to extract previously known issues, uncover new bugs, and identify sequences of events that lead to a bug, while minimizing out-of-domain outputs.

{{</citation>}}


### (90/161) Building Domain-Specific LLMs Faithful To The Islamic Worldview: Mirage or Technical Possibility? (Shabaz Patel et al., 2023)

{{<citation>}}

Shabaz Patel, Hassan Kane, Rayhan Patel. (2023)  
**Building Domain-Specific LLMs Faithful To The Islamic Worldview: Mirage or Technical Possibility?**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06652v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated remarkable performance across numerous natural language understanding use cases. However, this impressive performance comes with inherent limitations, such as the tendency to perpetuate stereotypical biases or fabricate non-existent facts. In the context of Islam and its representation, accurate and factual representation of its beliefs and teachings rooted in the Quran and Sunnah is key. This work focuses on the challenge of building domain-specific LLMs faithful to the Islamic worldview and proposes ways to build and evaluate such systems. Firstly, we define this open-ended goal as a technical problem and propose various solutions. Subsequently, we critically examine known challenges inherent to each approach and highlight evaluation methodologies that can be used to assess such systems. This work highlights the need for high-quality datasets, evaluations, and interdisciplinary work blending machine learning with Islamic scholarship.

{{</citation>}}


### (91/161) Computational Copyright: Towards A Royalty Model for AI Music Generation Platforms (Junwei Deng et al., 2023)

{{<citation>}}

Junwei Deng, Jiaqi Ma. (2023)  
**Computational Copyright: Towards A Royalty Model for AI Music Generation Platforms**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06646v1)  

---


**ABSTRACT**  
The advancement of generative AI has given rise to pressing copyright challenges, particularly in music industry. This paper focuses on the economic aspects of these challenges, emphasizing that the economic impact constitutes a central issue in the copyright arena. The complexity of the black-box generative AI technologies not only suggests but necessitates algorithmic solutions. However, such solutions have been largely missing, leading to regulatory challenges in this landscape. We aim to bridge the gap in current approaches by proposing potential royalty models for revenue sharing on AI music generation platforms. Our methodology involves a detailed analysis of existing royalty models in platforms like Spotify and YouTube, and adapting these to the unique context of AI-generated music. A significant challenge we address is the attribution of AI-generated music to influential copyrighted content in the training data. To this end, we present algorithmic solutions employing data attribution techniques. Our experimental results verify the effectiveness of these solutions. This research represents a pioneering effort in integrating technical advancements with economic and legal considerations in the field of generative AI, offering a computational copyright solution for the challenges posed by the opaque nature of AI technologies.

{{</citation>}}


### (92/161) Control Risk for Potential Misuse of Artificial Intelligence in Science (Jiyan He et al., 2023)

{{<citation>}}

Jiyan He, Weitao Feng, Yaosen Min, Jingwei Yi, Kunsheng Tang, Shuai Li, Jie Zhang, Kejiang Chen, Wenbo Zhou, Xing Xie, Weiming Zhang, Nenghai Yu, Shuxin Zheng. (2023)  
**Control Risk for Potential Misuse of Artificial Intelligence in Science**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06632v1)  

---


**ABSTRACT**  
The expanding application of Artificial Intelligence (AI) in scientific fields presents unprecedented opportunities for discovery and innovation. However, this growth is not without risks. AI models in science, if misused, can amplify risks like creation of harmful substances, or circumvention of established regulations. In this study, we aim to raise awareness of the dangers of AI misuse in science, and call for responsible AI development and use in this domain. We first itemize the risks posed by AI in scientific contexts, then demonstrate the risks by highlighting real-world examples of misuse in chemical science. These instances underscore the need for effective risk management strategies. In response, we propose a system called SciGuard to control misuse risks for AI models in science. We also propose a red-teaming benchmark SciMT-Safety to assess the safety of different systems. Our proposed SciGuard shows the least harmful impact in the assessment without compromising performance in benign tests. Finally, we highlight the need for a multidisciplinary and collaborative effort to ensure the safe and ethical use of AI models in science. We hope that our study can spark productive discussions on using AI ethically in science among researchers, practitioners, policymakers, and the public, to maximize benefits and minimize the risks of misuse.

{{</citation>}}


### (93/161) Can Reinforcement Learning support policy makers? A preliminary study with Integrated Assessment Models (Theodore Wolf et al., 2023)

{{<citation>}}

Theodore Wolf, Nantas Nardelli, John Shawe-Taylor, Maria Perez-Ortiz. (2023)  
**Can Reinforcement Learning support policy makers? A preliminary study with Integrated Assessment Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CE, cs.AI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06527v1)  

---


**ABSTRACT**  
Governments around the world aspire to ground decision-making on evidence. Many of the foundations of policy making - e.g. sensing patterns that relate to societal needs, developing evidence-based programs, forecasting potential outcomes of policy changes, and monitoring effectiveness of policy programs - have the potential to benefit from the use of large-scale datasets or simulations together with intelligent algorithms. These could, if designed and deployed in a way that is well grounded on scientific evidence, enable a more comprehensive, faster, and rigorous approach to policy making. Integrated Assessment Models (IAM) is a broad umbrella covering scientific models that attempt to link main features of society and economy with the biosphere into one modelling framework. At present, these systems are probed by policy makers and advisory groups in a hypothesis-driven manner. In this paper, we empirically demonstrate that modern Reinforcement Learning can be used to probe IAMs and explore the space of solutions in a more principled manner. While the implication of our results are modest since the environment is simplistic, we believe that this is a stepping stone towards more ambitious use cases, which could allow for effective exploration of policies and understanding of their consequences and limitations.

{{</citation>}}


### (94/161) Large Language Models with Retrieval-Augmented Generation for Zero-Shot Disease Phenotyping (Will E. Thompson et al., 2023)

{{<citation>}}

Will E. Thompson, David M. Vidmar, Jessica K. De Freitas, John M. Pfeifer, Brandon K. Fornwalt, Ruijun Chen, Gabriel Altay, Kabir Manghnani, Andrew C. Nelsen, Kellie Morland, Martin C. Stumpe, Riccardo Miotto. (2023)  
**Large Language Models with Retrieval-Augmented Generation for Zero-Shot Disease Phenotyping**  

---
Primary Category: cs.AI  
Categories: I-2-7, cs-AI, cs-CL, cs-IR, cs.AI  
Keywords: Language Model, Zero-Shot  
[Paper Link](http://arxiv.org/abs/2312.06457v1)  

---


**ABSTRACT**  
Identifying disease phenotypes from electronic health records (EHRs) is critical for numerous secondary uses. Manually encoding physician knowledge into rules is particularly challenging for rare diseases due to inadequate EHR coding, necessitating review of clinical notes. Large language models (LLMs) offer promise in text understanding but may not efficiently handle real-world clinical documentation. We propose a zero-shot LLM-based method enriched by retrieval-augmented generation and MapReduce, which pre-identifies disease-related text snippets to be used in parallel as queries for the LLM to establish diagnosis. We show that this method as applied to pulmonary hypertension (PH), a rare disease characterized by elevated arterial pressures in the lungs, significantly outperforms physician logic rules ($F_1$ score of 0.62 vs. 0.75). This method has the potential to enhance rare disease cohort identification, expanding the scope of robust clinical research and care gap identification.

{{</citation>}}


### (95/161) Internet of Federated Digital Twins (IoFDT): Connecting Twins Beyond Borders for Society 5.0 (Tao Yu et al., 2023)

{{<citation>}}

Tao Yu, Zongdian Li, Kei Sakaguchi, Omar Hashash, Walid Saad, Merouane Debbah. (2023)  
**Internet of Federated Digital Twins (IoFDT): Connecting Twins Beyond Borders for Society 5.0**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06432v1)  

---


**ABSTRACT**  
The concept of digital twin (DT), which enables the creation of a programmable, digital representation of physical systems, is expected to revolutionize future industries and will lie at the heart of the vision of a future smart society, namely, Society 5.0, in which high integration between cyber (digital) and physical spaces is exploited to bring economic and societal advancements. However, the success of such a DT-driven Society 5.0 requires a synergistic convergence of artificial intelligence and networking technologies into an integrated, programmable system that can coordinate networks of DTs to effectively deliver diverse Society 5.0 services. Prior works remain restricted to either qualitative study, simple analysis or software implementations of a single DT, and thus, they cannot provide the highly synergistic integration of digital and physical spaces as required by Society 5.0. In contrast, this paper envisions a novel concept of an Internet of Federated Digital Twins (IoFDT) that holistically integrates heterogeneous and physically separated DTs representing different Society 5.0 services within a single framework and system. For this concept of IoFDT, we first introduce a hierarchical architecture that integrates federated DTs through horizontal and vertical interactions, bridging the cyber and physical spaces to unlock new possibilities. Then, we discuss the challenges of realizing IoFDT, highlighting the intricacies across communication, computing, and AI-native networks while also underscoring potential innovative solutions. Subsequently, we elaborate on the importance of the implementation of a unified IoFDT platform that integrates all technical components and orchestrates their interactions, emphasizing the necessity of practical experimental platforms with a focus on real-world applications in areas like smart mobility.

{{</citation>}}


### (96/161) DiT-Head: High-Resolution Talking Head Synthesis using Diffusion Transformers (Aaron Mir et al., 2023)

{{<citation>}}

Aaron Mir, Eduardo Alonso, Esther Mondragón. (2023)  
**DiT-Head: High-Resolution Talking Head Synthesis using Diffusion Transformers**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CV, cs-LG, cs.AI  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.06400v1)  

---


**ABSTRACT**  
We propose a novel talking head synthesis pipeline called "DiT-Head", which is based on diffusion transformers and uses audio as a condition to drive the denoising process of a diffusion model. Our method is scalable and can generalise to multiple identities while producing high-quality results. We train and evaluate our proposed approach and compare it against existing methods of talking head synthesis. We show that our model can compete with these methods in terms of visual quality and lip-sync accuracy. Our results highlight the potential of our proposed approach to be used for a wide range of applications, including virtual assistants, entertainment, and education. For a video demonstration of the results and our user study, please refer to our supplementary material.

{{</citation>}}


### (97/161) MMICT: Boosting Multi-Modal Fine-Tuning with In-Context Examples (Tao Chen et al., 2023)

{{<citation>}}

Tao Chen, Enwei Zhang, Yuting Gao, Ke Li, Xing Sun, Yan Zhang, Hui Li. (2023)  
**MMICT: Boosting Multi-Modal Fine-Tuning with In-Context Examples**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06363v2)  

---


**ABSTRACT**  
Although In-Context Learning (ICL) brings remarkable performance gains to Large Language Models (LLMs), the improvements remain lower than fine-tuning on downstream tasks. This paper introduces Multi-Modal In-Context Tuning (MMICT), a novel multi-modal fine-tuning paradigm that boosts multi-modal fine-tuning by fully leveraging the promising ICL capability of multi-modal LLMs (MM-LLMs). We propose the Multi-Modal Hub (M-Hub), a unified module that captures various multi-modal features according to different inputs and objectives. Based on M-Hub, MMICT enables MM-LLMs to learn from in-context visual-guided textual features and subsequently generate outputs conditioned on the textual-guided visual features. Moreover, leveraging the flexibility of M-Hub, we design a variety of in-context demonstrations. Extensive experiments on a diverse range of downstream multi-modal tasks demonstrate that MMICT significantly outperforms traditional fine-tuning strategy and the vanilla ICT method that directly takes the concatenation of all information from different modalities as input.

{{</citation>}}


### (98/161) Survey on Foundation Models for Prognostics and Health Management in Industrial Cyber-Physical Systems (Ruonan Liu et al., 2023)

{{<citation>}}

Ruonan Liu, Quanhu Zhang, Te Han, Weidong Zhang, Di Lin, C. L. Philip Chen. (2023)  
**Survey on Foundation Models for Prognostics and Health Management in Industrial Cyber-Physical Systems**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, BERT, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2312.06261v1)  

---


**ABSTRACT**  
Industrial Cyber-Physical Systems (ICPS) integrate the disciplines of computer science, communication technology, and engineering, and have emerged as integral components of contemporary manufacturing and industries. However, ICPS encounters various challenges in long-term operation, including equipment failures, performance degradation, and security threats. To achieve efficient maintenance and management, prognostics and health management (PHM) finds widespread application in ICPS for critical tasks, including failure prediction, health monitoring, and maintenance decision-making. The emergence of large-scale foundation models (LFMs) like BERT and GPT signifies a significant advancement in AI technology, and ChatGPT stands as a remarkable accomplishment within this research paradigm, harboring potential for General Artificial Intelligence. Considering the ongoing enhancement in data acquisition technology and data processing capability, LFMs are anticipated to assume a crucial role in the PHM domain of ICPS. However, at present, a consensus is lacking regarding the application of LFMs to PHM in ICPS, necessitating systematic reviews and roadmaps to elucidate future directions. To bridge this gap, this paper elucidates the key components and recent advances in the underlying model.A comprehensive examination and comprehension of the latest advances in grand modeling for PHM in ICPS can offer valuable references for decision makers and researchers in the industrial field while facilitating further enhancements in the reliability, availability, and safety of ICPS.

{{</citation>}}


### (99/161) Offloading and Quality Control for AI Generated Content Services in Edge Computing Networks (Yitong Wang et al., 2023)

{{<citation>}}

Yitong Wang, Chang Liu, Jun Zhao. (2023)  
**Offloading and Quality Control for AI Generated Content Services in Edge Computing Networks**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-NI, cs-PF, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06203v1)  

---


**ABSTRACT**  
AI-Generated Content (AIGC), as a novel manner of providing Metaverse services in the forthcoming Internet paradigm, can resolve the obstacles of immersion requirements. Concurrently, edge computing, as an evolutionary paradigm of computing in communication systems, effectively augments real-time interactive services. In pursuit of enhancing the accessibility of AIGC services, the deployment of AIGC models (e.g., diffusion models) to edge servers and local devices has become a prevailing trend. Nevertheless, this approach faces constraints imposed by battery life and computational resources when tasks are offloaded to local devices, limiting the capacity to deliver high-quality content to users while adhering to stringent latency requirements. So there will be a tradeoff between the utility of AIGC models and offloading decisions in the edge computing paradigm. This paper proposes a joint optimization algorithm for offloading decisions, computation time, and diffusion steps of the diffusion models in the reverse diffusion stage. Moreover, we take the average error into consideration as the metric for evaluating the quality of the generated results. Experimental results conclusively demonstrate that the proposed algorithm achieves superior joint optimization performance compared to the baselines.

{{</citation>}}


### (100/161) Survey on Memory-Augmented Neural Networks: Cognitive Insights to AI Applications (Savya Khosla et al., 2023)

{{<citation>}}

Savya Khosla, Zhen Zhu, Yifei He. (2023)  
**Survey on Memory-Augmented Neural Networks: Cognitive Insights to AI Applications**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Attention, Computer Vision, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2312.06141v2)  

---


**ABSTRACT**  
This paper explores Memory-Augmented Neural Networks (MANNs), delving into how they blend human-like memory processes into AI. It covers different memory types, like sensory, short-term, and long-term memory, linking psychological theories with AI applications. The study investigates advanced architectures such as Hopfield Networks, Neural Turing Machines, Correlation Matrix Memories, Memformer, and Neural Attention Memory, explaining how they work and where they excel. It dives into real-world uses of MANNs across Natural Language Processing, Computer Vision, Multimodal Learning, and Retrieval Models, showing how memory boosters enhance accuracy, efficiency, and reliability in AI tasks. Overall, this survey provides a comprehensive view of MANNs, offering insights for future research in memory-based AI systems.

{{</citation>}}


### (101/161) XAI meets Biology: A Comprehensive Review of Explainable AI in Bioinformatics Applications (Zhongliang Zhou et al., 2023)

{{<citation>}}

Zhongliang Zhou, Mengxuan Hu, Mariah Salcedo, Nathan Gravel, Wayland Yeung, Aarya Venkat, Dongliang Guo, Jielu Zhang, Natarajan Kannan, Sheng Li. (2023)  
**XAI meets Biology: A Comprehensive Review of Explainable AI in Bioinformatics Applications**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI, q-bio-QM  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06082v1)  

---


**ABSTRACT**  
Artificial intelligence (AI), particularly machine learning and deep learning models, has significantly impacted bioinformatics research by offering powerful tools for analyzing complex biological data. However, the lack of interpretability and transparency of these models presents challenges in leveraging these models for deeper biological insights and for generating testable hypotheses. Explainable AI (XAI) has emerged as a promising solution to enhance the transparency and interpretability of AI models in bioinformatics. This review provides a comprehensive analysis of various XAI techniques and their applications across various bioinformatics domains including DNA, RNA, and protein sequence analysis, structural analysis, gene expression and genome analysis, and bioimaging analysis. We introduce the most pertinent machine learning and XAI methods, then discuss their diverse applications and address the current limitations of available XAI tools. By offering insights into XAI's potential and challenges, this review aims to facilitate its practical implementation in bioinformatics research and help researchers navigate the landscape of XAI tools.

{{</citation>}}


### (102/161) A Vision for Operationalising Diversity and Inclusion in AI (Muneera Bano et al., 2023)

{{<citation>}}

Muneera Bano, Didar Zowghi, Vincenzo Gervasi. (2023)  
**A Vision for Operationalising Diversity and Inclusion in AI**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-SE, cs.AI  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2312.06074v1)  

---


**ABSTRACT**  
The growing presence of Artificial Intelligence (AI) in various sectors necessitates systems that accurately reflect societal diversity. This study seeks to envision the operationalization of the ethical imperatives of diversity and inclusion (D&I) within AI ecosystems, addressing the current disconnect between ethical guidelines and their practical implementation. A significant challenge in AI development is the effective operationalization of D&I principles, which is critical to prevent the reinforcement of existing biases and ensure equity across AI applications. This paper proposes a vision of a framework for developing a tool utilizing persona-based simulation by Generative AI (GenAI). The approach aims to facilitate the representation of the needs of diverse users in the requirements analysis process for AI software. The proposed framework is expected to lead to a comprehensive persona repository with diverse attributes that inform the development process with detailed user narratives. This research contributes to the development of an inclusive AI paradigm that ensures future technological advances are designed with a commitment to the diverse fabric of humanity.

{{</citation>}}


### (103/161) Privacy Issues in Large Language Models: A Survey (Seth Neel et al., 2023)

{{<citation>}}

Seth Neel, Peter Chang. (2023)  
**Privacy Issues in Large Language Models: A Survey**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06717v1)  

---


**ABSTRACT**  
This is the first survey of the active area of AI research that focuses on privacy issues in Large Language Models (LLMs). Specifically, we focus on work that red-teams models to highlight privacy risks, attempts to build privacy into the training or inference process, enables efficient data deletion from trained models to comply with existing privacy regulations, and tries to mitigate copyright issues. Our focus is on summarizing technical research that develops algorithms, proves theorems, and runs empirical evaluations. While there is an extensive body of legal and policy work addressing these challenges from a different angle, that is not the focus of our survey. Nevertheless, these works, along with recent legal developments do inform how these technical problems are formalized, and so we discuss them briefly in Section 1. While we have made our best effort to include all the relevant work, due to the fast moving nature of this research we may have missed some recent work. If we have missed some of your work please contact us, as we will attempt to keep this survey relatively up to date. We are maintaining a repository with the list of papers covered in this survey and any relevant code that was publicly available at https://github.com/safr-ml-lab/survey-llm.

{{</citation>}}


## cs.IT (1)



### (104/161) Deep Learning based Modeling of Wireless Communication Channel with Fading (Lee Youngmin et al., 2023)

{{<citation>}}

Lee Youngmin, Ma Xiaomin, Lang S. I. D. Andrew, Valderrama-Araya F. Enrique, Chapuis L. Andrew. (2023)  
**Deep Learning based Modeling of Wireless Communication Channel with Fading**  

---
Primary Category: cs.IT  
Categories: J-2; I-2-6, cs-IT, cs.IT, eess-SP, math-IT  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.06849v1)  

---


**ABSTRACT**  
In the realm of wireless communication, stochastic modeling of channels is instrumental for the assessment and design of operational systems. Deep learning neural networks (DLNN), including generative adversarial networks (GANs), are being used to approximate wireless Orthogonal frequency-division multiplexing (OFDM) channels with fading and noise, using real measurement data. These models primarily focus on channel output (y) distribution given input x: p(y|x), limiting their application scope. DLNN channel models have been tested predominantly on simple simulated channels. In this paper, we build both GANs and feedforward neural networks (FNN) to approximate a more general channel model, which is represented by a conditional probability density function (PDF) of receiving signal or power of node receiving power Prx: f_p_rx|d(()), where is communication distance. The stochastic models are trained and tested for the impact of fading channels on transmissions of OFDM QAM modulated signal and transmissions of general signal regardless of modulations. New metrics are proposed for evaluation of modeling accuracy and comparisons of the GAN-based model with the FNN-based model. Extensive experiments on Nakagami fading channel show accuracy and the effectiveness of the approaches.

{{</citation>}}


## cs.IR (3)



### (105/161) memorAIs: an Optical Character Recognition and Rule-Based Medication Intake Reminder-Generating Solution (Eden Shaveet et al., 2023)

{{<citation>}}

Eden Shaveet, Utkarsh Singh, Nicholas Assaderaghi, Maximo Librandi. (2023)  
**memorAIs: an Optical Character Recognition and Rule-Based Medication Intake Reminder-Generating Solution**  

---
Primary Category: cs.IR  
Categories: cs-CY, cs-IR, cs.IR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06841v1)  

---


**ABSTRACT**  
Memory-based medication non-adherence is an unsolved problem that is responsible for considerable disease burden in the United States. Digital medication intake reminder solutions with minimal onboarding requirements that are usable at the point of medication acquisition may help to alleviate this problem by offering a low barrier way to help people remember to take their medications. In this paper, we propose memorAIs, a digital medication intake reminder solution that mitigates onboarding friction by leveraging optical character recognition strategies for text extraction from medication bottles and rule based expressions for text processing to create configured medication reminders as local device calendar invitations. We describe our ideation and development process, as well as limitations of the current implementation. memorAIs was the winner of the Patient Safety award at the 2023 Columbia University DivHacks Hackathon, presented by the Patient Safety Technology Challenge, sponsored by the Pittsburgh Regional Health Initiative.

{{</citation>}}


### (106/161) Cross Domain LifeLong Sequential Modeling for Online Click-Through Rate Prediction (Ruijie Hou et al., 2023)

{{<citation>}}

Ruijie Hou, Zhaoyang Yang, Yu Ming, Hongyu Lu, Zhuobin Zheng, Yu Chen, Qinsong Zeng, Ming Chen. (2023)  
**Cross Domain LifeLong Sequential Modeling for Online Click-Through Rate Prediction**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.06424v1)  

---


**ABSTRACT**  
Deep neural networks (DNNs) that incorporated lifelong sequential modeling (LSM) have brought great success to recommendation systems in various social media platforms. While continuous improvements have been made in domain-specific LSM, limited work has been done in cross-domain LSM, which considers modeling of lifelong sequences of both target domain and source domain. In this paper, we propose Lifelong Cross Network (LCN) to incorporate cross-domain LSM to improve the click-through rate (CTR) prediction in the target domain. The proposed LCN contains a LifeLong Attention Pyramid (LAP) module that comprises of three levels of cascaded attentions to effectively extract interest representations with respect to the candidate item from lifelong sequences. We also propose Cross Representation Production (CRP) module to enforce additional supervision on the learning and alignment of cross-domain representations so that they can be better reused on learning of the CTR prediction in the target domain. We conducted extensive experiments on WeChat Channels industrial dataset as well as on benchmark dataset. Results have revealed that the proposed LCN outperforms existing work in terms of both prediction accuracy and online performance.

{{</citation>}}


### (107/161) RecJPQ: Training Large-Catalogue Sequential Recommenders (Aleksandr V. Petrov et al., 2023)

{{<citation>}}

Aleksandr V. Petrov, Craig Macdonald. (2023)  
**RecJPQ: Training Large-Catalogue Sequential Recommenders**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2312.06165v1)  

---


**ABSTRACT**  
Sequential recommender systems rank items based on the likelihood of their next appearance in user-item interactions. Current models such as BERT4Rec and SASRec generate sequence embeddings and compute scores for catalogue items, but the increasing catalogue size makes training these models costly. The Joint Product Quantisation method, originally proposed for passage retrieval, markedly reduces the size of the retrieval index with minimal effect on model effectiveness by replacing passage embeddings with a limited number of shared centroid embeddings. This paper introduces RecJPQ, a novel adaptation of JPQ for sequential recommendations. We apply RecJPQ to SASRec, BERT4Rec, and GRU4rec models on three large-scale sequential datasets. Our results showed that RecJPQ could notably reduce the model size (e.g., 48x reduction for the Gowalla dataset with no effectiveness degradation). RecJPQ can also improve model performance through a regularisation effect (e.g. +0.96% NDCG@10 improvement on the Booking.com dataset).

{{</citation>}}


## cs.HC (1)



### (108/161) A Critique of Human-Autonomous Team Dynamics: Contrasting Qualitative and Quantitative Perspectives (Hanjing Shi, 2023)

{{<citation>}}

Hanjing Shi. (2023)  
**A Critique of Human-Autonomous Team Dynamics: Contrasting Qualitative and Quantitative Perspectives**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06789v1)  

---


**ABSTRACT**  
The critique paper provides an in-depth analysis of two influential studies in the field of Human-Autonomous Teams (HATs). Musick et al. explored qualitative dimensions of HAT dynamics, examining the influence of team composition on emotions, cognitive processes, and the development of team cognition. Their research revealed that teams with a majority of human members, known as Multi-Human HATs, generally surpass Multi-Agent HATs in performance, highlighting the critical influence of human perception on team dynamics. Employing qualitative interview analysis anchored in theoretical frameworks, Musick et al. captured the detailed subtleties of participants' experiences. In contrast, Schelble et al. utilized a quantitative methodology to provide data-driven insights into how the perception of AI teammates affects team performance. Despite the rich insights from Musick et al.'s qualitative research, their findings face limitations in terms of broader applicability. Both Musick et al. and Schelble et al. agree in their conclusions that Multi-Human HATs typically outperform their Multi-Agent counterparts, again emphasizing the crucial role of human perception in team dynamics. The critique paper suggests that future research should focus on understanding perceptions of teams heavily reliant on AI. Such investigations could illuminate how trust and skepticism are shaped in teams where AI plays a dominant role.

{{</citation>}}


## cs.CL (23)



### (109/161) Dense X Retrieval: What Retrieval Granularity Should We Use? (Tong Chen et al., 2023)

{{<citation>}}

Tong Chen, Hongwei Wang, Sihao Chen, Wenhao Yu, Kaixin Ma, Xinran Zhao, Hongming Zhang, Dong Yu. (2023)  
**Dense X Retrieval: What Retrieval Granularity Should We Use?**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs.CL  
Keywords: NLP, QA  
[Paper Link](http://arxiv.org/abs/2312.06648v2)  

---


**ABSTRACT**  
Dense retrieval has become a prominent method to obtain relevant context or world knowledge in open-domain NLP tasks. When we use a learned dense retriever on a retrieval corpus at inference time, an often-overlooked design choice is the retrieval unit in which the corpus is indexed, e.g. document, passage, or sentence. We discover that the retrieval unit choice significantly impacts the performance of both retrieval and downstream tasks. Distinct from the typical approach of using passages or sentences, we introduce a novel retrieval unit, proposition, for dense retrieval. Propositions are defined as atomic expressions within text, each encapsulating a distinct factoid and presented in a concise, self-contained natural language format. We conduct an empirical comparison of different retrieval granularity. Our results reveal that proposition-based retrieval significantly outperforms traditional passage or sentence-based methods in dense retrieval. Moreover, retrieval by proposition also enhances the performance of downstream QA tasks, since the retrieved texts are more condensed with question-relevant information, reducing the need for lengthy input tokens and minimizing the inclusion of extraneous, irrelevant information.

{{</citation>}}


### (110/161) LLM360: Towards Fully Transparent Open-Source LLMs (Zhengzhong Liu et al., 2023)

{{<citation>}}

Zhengzhong Liu, Aurick Qiao, Willie Neiswanger, Hongyi Wang, Bowen Tan, Tianhua Tao, Junbo Li, Yuqi Wang, Suqi Sun, Omkar Pangarkar, Richard Fan, Yi Gu, Victor Miller, Yonghao Zhuang, Guowei He, Haonan Li, Fajri Koto, Liping Tang, Nikhil Ranjan, Zhiqiang Shen, Xuguang Ren, Roberto Iriondo, Cun Mu, Zhiting Hu, Mark Schulze, Preslav Nakov, Tim Baldwin, Eric P. Xing. (2023)  
**LLM360: Towards Fully Transparent Open-Source LLMs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: AI, Falcon, LLaMA, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06550v1)  

---


**ABSTRACT**  
The recent surge in open-source Large Language Models (LLMs), such as LLaMA, Falcon, and Mistral, provides diverse options for AI practitioners and researchers. However, most LLMs have only released partial artifacts, such as the final model weights or inference code, and technical reports increasingly limit their scope to high-level design choices and surface statistics. These choices hinder progress in the field by degrading transparency into the training of LLMs and forcing teams to rediscover many details in the training process. We present LLM360, an initiative to fully open-source LLMs, which advocates for all training code and data, model checkpoints, and intermediate results to be made available to the community. The goal of LLM360 is to support open and collaborative AI research by making the end-to-end LLM training process transparent and reproducible by everyone. As a first step of LLM360, we release two 7B parameter LLMs pre-trained from scratch, Amber and CrystalCoder, including their training code, data, intermediate checkpoints, and analyses (at https://www.llm360.ai). We are committed to continually pushing the boundaries of LLMs through this open-source effort. More large-scale and stronger models are underway and will be released in the future.

{{</citation>}}


### (111/161) Label Smoothing for Enhanced Text Sentiment Classification (Yijie Gao et al., 2023)

{{<citation>}}

Yijie Gao, Shijing Si. (2023)  
**Label Smoothing for Enhanced Text Sentiment Classification**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: BERT  
[Paper Link](http://arxiv.org/abs/2312.06522v1)  

---


**ABSTRACT**  
Label smoothing is a widely used technique in various domains, such as image classification and speech recognition, known for effectively combating model overfitting. However, there is few research on its application to text sentiment classification. To fill in the gap, this study investigates the implementation of label smoothing for sentiment classification by utilizing different levels of smoothing. The primary objective is to enhance sentiment classification accuracy by transforming discrete labels into smoothed label distributions. Through extensive experiments, we demonstrate the superior performance of label smoothing in text sentiment classification tasks across eight diverse datasets and deep learning architectures: TextCNN, BERT, and RoBERTa, under two learning schemes: training from scratch and fine-tuning.

{{</citation>}}


### (112/161) Where exactly does contextualization in a PLM happen? (Soniya Vijayakumar et al., 2023)

{{<citation>}}

Soniya Vijayakumar, Tanja Bäumel, Simon Ostermann, Josef van Genabith. (2023)  
**Where exactly does contextualization in a PLM happen?**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BERT, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2312.06514v1)  

---


**ABSTRACT**  
Pre-trained Language Models (PLMs) have shown to be consistently successful in a plethora of NLP tasks due to their ability to learn contextualized representations of words (Ethayarajh, 2019). BERT (Devlin et al., 2018), ELMo (Peters et al., 2018) and other PLMs encode word meaning via textual context, as opposed to static word embeddings, which encode all meanings of a word in a single vector representation. In this work, we present a study that aims to localize where exactly in a PLM word contextualization happens. In order to find the location of this word meaning transformation, we investigate representations of polysemous words in the basic BERT uncased 12 layer architecture (Devlin et al., 2018), a masked language model trained on an additional sentence adjacency objective, using qualitative and quantitative measures.

{{</citation>}}


### (113/161) TaCo: Targeted Concept Removal in Output Embeddings for NLP via Information Theory and Explainability (Fanny Jourdan et al., 2023)

{{<citation>}}

Fanny Jourdan, Louis Béthune, Agustin Picard, Laurent Risser, Nicholas Asher. (2023)  
**TaCo: Targeted Concept Removal in Output Embeddings for NLP via Information Theory and Explainability**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL, stat-ML  
Keywords: AI, Embedding, NLP, Natural Language Processing  
[Paper Link](http://arxiv.org/abs/2312.06499v1)  

---


**ABSTRACT**  
The fairness of Natural Language Processing (NLP) models has emerged as a crucial concern. Information theory indicates that to achieve fairness, a model should not be able to predict sensitive variables, such as gender, ethnicity, and age. However, information related to these variables often appears implicitly in language, posing a challenge in identifying and mitigating biases effectively. To tackle this issue, we present a novel approach that operates at the embedding level of an NLP model, independent of the specific architecture. Our method leverages insights from recent advances in XAI techniques and employs an embedding transformation to eliminate implicit information from a selected variable. By directly manipulating the embeddings in the final layer, our approach enables a seamless integration into existing models without requiring significant modifications or retraining. In evaluation, we show that the proposed post-hoc approach significantly reduces gender-related associations in NLP models while preserving the overall performance and functionality of the models. An implementation of our method is available: https://github.com/fanny-jourdan/TaCo

{{</citation>}}


### (114/161) Contrastive News and Social Media Linking using BERT for Articles and Tweets across Dual Platforms (Jan Piotrowski et al., 2023)

{{<citation>}}

Jan Piotrowski, Marek Wachnicki, Mateusz Perlik, Jakub Podolak, Grzegorz Rucki, Michał Brzozowski, Paweł Olejnik, Julian Kozłowski, Tomasz Nocoń, Jakub Kozieł, Stanisław Giziński, Piotr Sankowski. (2023)  
**Contrastive News and Social Media Linking using BERT for Articles and Tweets across Dual Platforms**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-CL, cs-LG, cs.CL  
Keywords: AI, BERT, Social Media, Twitter  
[Paper Link](http://arxiv.org/abs/2312.07599v1)  

---


**ABSTRACT**  
X (formerly Twitter) has evolved into a contemporary agora, offering a platform for individuals to express opinions and viewpoints on current events. The majority of the topics discussed on Twitter are directly related to ongoing events, making it an important source for monitoring public discourse. However, linking tweets to specific news presents a significant challenge due to their concise and informal nature. Previous approaches, including topic models, graph-based models, and supervised classifiers, have fallen short in effectively capturing the unique characteristics of tweets and articles.   Inspired by the success of the CLIP model in computer vision, which employs contrastive learning to model similarities between images and captions, this paper introduces a contrastive learning approach for training a representation space where linked articles and tweets exhibit proximity. We present our contrastive learning approach, CATBERT (Contrastive Articles Tweets BERT), leveraging pre-trained BERT models. The model is trained and tested on a dataset containing manually labeled English and Polish tweets and articles related to the Russian-Ukrainian war. We evaluate CATBERT's performance against traditional approaches like LDA, and the novel method based on OpenAI embeddings, which has not been previously applied to this task. Our findings indicate that CATBERT demonstrates superior performance in associating tweets with relevant news articles. Furthermore, we demonstrate the performance of the models when applied to finding the main topic -- represented by an article -- of the whole cascade of tweets. In this new task, we report the performance of the different models in dependence on the cascade size.

{{</citation>}}


### (115/161) UstanceBR: a multimodal language resource for stance prediction (Camila Pereira et al., 2023)

{{<citation>}}

Camila Pereira, Matheus Pavan, Sungwon Yoon, Ricelli Ramos, Pablo Costa, Lais Cavalheiro, Ivandre Paraboni. (2023)  
**UstanceBR: a multimodal language resource for stance prediction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2312.06374v1)  

---


**ABSTRACT**  
This work introduces UstanceBR, a multimodal corpus in the Brazilian Portuguese Twitter domain for target-based stance prediction. The corpus comprises 86.8 k labelled stances towards selected target topics, and extensive network information about the users who published these stances on social media. In this article we describe the corpus multimodal data, and a number of usage examples in both in-domain and zero-shot stance prediction based on text- and network-related information, which are intended to provide initial baseline results for future studies in the field.

{{</citation>}}


### (116/161) Empirical Basis of Engineering Design Knowledge (L. Siddharth et al., 2023)

{{<citation>}}

L. Siddharth, Jianxi Luo. (2023)  
**Empirical Basis of Engineering Design Knowledge**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-DL, cs-IR, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2312.06355v1)  

---


**ABSTRACT**  
Engineering design knowledge is embodied in natural language text through intricate placement of entities and relationships. Ontological constructs of design knowledge often limit the performances of NLP techniques to extract design knowledge. Also, large-language models could be less useful for generating and explicating design knowledge, as these are trained predominantly on common-sense text. In this article, we present the constituents of design knowledge based on empirical observations from patent documents. We obtain a sample of 33,881 patents and populate over 24 million facts from the sentences in these. We conduct Zipf distribution analyses using the frequencies of unique entities and relationships that are present in the facts thus populated. While the literal entities cannot be generalised from the sample of patents, the relationships largely capture attributes ('of'), structure ('in', 'with'), purpose ('to', 'for'), hierarchy ('include'), exemplification ('such as'), and behaviour ('to', 'from'). The analyses reveal that over half of entities and relationships could be generalised to 64 and 24 linguistic syntaxes respectively, while hierarchical relationships include 75 syntaxes. These syntaxes represent the linguistic basis of engineering design knowledge. We combine facts within each patent into a knowledge graph, from which we discover motifs that are statistically over-represented subgraph patterns. Across all patents in the sample, we identify eight patterns that could be simplified into sequence [->...->], aggregation [->...<-], and hierarchy [<-...->] that form the structural basis of engineering design knowledge. We propose regulatory precepts for concretising abstract entities and relationships within subgraphs, while also explicating hierarchical structures. These precepts could be useful for better construction and management of knowledge in a design environment.

{{</citation>}}


### (117/161) BoschAI @ Causal News Corpus 2023: Robust Cause-Effect Span Extraction using Multi-Layer Sequence Tagging and Data Augmentation (Timo Pierre Schrader et al., 2023)

{{<citation>}}

Timo Pierre Schrader, Simon Razniewski, Lukas Lange, Annemarie Friedrich. (2023)  
**BoschAI @ Causal News Corpus 2023: Robust Cause-Effect Span Extraction using Multi-Layer Sequence Tagging and Data Augmentation**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: AI, Augmentation  
[Paper Link](http://arxiv.org/abs/2312.06338v1)  

---


**ABSTRACT**  
Understanding causality is a core aspect of intelligence. The Event Causality Identification with Causal News Corpus Shared Task addresses two aspects of this challenge: Subtask 1 aims at detecting causal relationships in texts, and Subtask 2 requires identifying signal words and the spans that refer to the cause or effect, respectively. Our system, which is based on pre-trained transformers, stacked sequence tagging, and synthetic data augmentation, ranks third in Subtask 1 and wins Subtask 2 with an F1 score of 72.8, corresponding to a margin of 13 pp. to the second-best system.

{{</citation>}}


### (118/161) GPTBIAS: A Comprehensive Framework for Evaluating Bias in Large Language Models (Jiaxu Zhao et al., 2023)

{{<citation>}}

Jiaxu Zhao, Meng Fang, Shirui Pan, Wenpeng Yin, Mykola Pechenizkiy. (2023)  
**GPTBIAS: A Comprehensive Framework for Evaluating Bias in Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs-LG, cs.CL  
Keywords: Bias, GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06315v1)  

---


**ABSTRACT**  
Warning: This paper contains content that may be offensive or upsetting. There has been a significant increase in the usage of large language models (LLMs) in various applications, both in their original form and through fine-tuned adaptations. As a result, LLMs have gained popularity and are being widely adopted by a large user community. However, one of the concerns with LLMs is the potential generation of socially biased content. The existing evaluation methods have many constraints, and their results exhibit a limited degree of interpretability. In this work, we propose a bias evaluation framework named GPTBIAS that leverages the high performance of LLMs (e.g., GPT-4 \cite{openai2023gpt4}) to assess bias in models. We also introduce prompts called Bias Attack Instructions, which are specifically designed for evaluating model bias. To enhance the credibility and interpretability of bias evaluation, our framework not only provides a bias score but also offers detailed information, including bias types, affected demographics, keywords, reasons behind the biases, and suggestions for improvement. We conduct extensive experiments to demonstrate the effectiveness and usability of our bias evaluation framework.

{{</citation>}}


### (119/161) EQ-Bench: An Emotional Intelligence Benchmark for Large Language Models (Samuel J. Paech, 2023)

{{<citation>}}

Samuel J. Paech. (2023)  
**EQ-Bench: An Emotional Intelligence Benchmark for Large Language Models**  

---
Primary Category: cs.CL  
Categories: I-2-7, cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.06281v1)  

---


**ABSTRACT**  
We introduce EQ-Bench, a novel benchmark designed to evaluate aspects of emotional intelligence in Large Language Models (LLMs). We assess the ability of LLMs to understand complex emotions and social interactions by asking them to predict the intensity of emotional states of characters in a dialogue. The benchmark is able to discriminate effectively between a wide range of models. We find that EQ-Bench correlates strongly with comprehensive multi-domain benchmarks like MMLU (Hendrycks et al., 2020) (r=0.97), indicating that we may be capturing similar aspects of broad intelligence. Our benchmark produces highly repeatable results using a set of 60 English-language questions. We also provide open-source code for an automated benchmarking pipeline at https://github.com/EQ-bench/EQ-Bench and a leaderboard at https://www.eqbench.com

{{</citation>}}


### (120/161) Creating Spoken Dialog Systems in Ultra-Low Resourced Settings (Moayad Elamin et al., 2023)

{{<citation>}}

Moayad Elamin, Muhammad Omer, Yonas Chanie, Henslaac Ndlovu. (2023)  
**Creating Spoken Dialog Systems in Ultra-Low Resourced Settings**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL, eess-AS  
Keywords: Dialog, Speech Recognition, Spoken Language Understanding  
[Paper Link](http://arxiv.org/abs/2312.06266v1)  

---


**ABSTRACT**  
Automatic Speech Recognition (ASR) systems are a crucial technology that is used today to design a wide variety of applications, most notably, smart assistants, such as Alexa. ASR systems are essentially dialogue systems that employ Spoken Language Understanding (SLU) to extract meaningful information from speech. The main challenge with designing such systems is that they require a huge amount of labeled clean data to perform competitively, such data is extremely hard to collect and annotate to respective SLU tasks, furthermore, when designing such systems for low resource languages, where data is extremely limited, the severity of the problem intensifies. In this paper, we focus on a fairly popular SLU task, that is, Intent Classification while working with a low resource language, namely, Flemish. Intent Classification is a task concerned with understanding the intents of the user interacting with the system. We build on existing light models for intent classification in Flemish, and our main contribution is applying different augmentation techniques on two levels -- the voice level, and the phonetic transcripts level -- to the existing models to counter the problem of scarce labeled data in low-resource languages. We find that our data augmentation techniques, on both levels, have improved the model performance on a number of tasks.

{{</citation>}}


### (121/161) Evaluating ChatGPT as a Question Answering System: A Comprehensive Analysis and Comparison with Existing Models (Hossein Bahak et al., 2023)

{{<citation>}}

Hossein Bahak, Farzaneh Taheri, Zahra Zojaji, Arefeh Kazemi. (2023)  
**Evaluating ChatGPT as a Question Answering System: A Comprehensive Analysis and Comparison with Existing Models**  

---
Primary Category: cs.CL  
Categories: I-2, I-7, cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, GPT-3.5, QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2312.07592v1)  

---


**ABSTRACT**  
In the current era, a multitude of language models has emerged to cater to user inquiries. Notably, the GPT-3.5 Turbo language model has gained substantial attention as the underlying technology for ChatGPT. Leveraging extensive parameters, this model adeptly responds to a wide range of questions. However, due to its reliance on internal knowledge, the accuracy of responses may not be absolute. This article scrutinizes ChatGPT as a Question Answering System (QAS), comparing its performance to other existing QASs. The primary focus is on evaluating ChatGPT's proficiency in extracting responses from provided paragraphs, a core QAS capability. Additionally, performance comparisons are made in scenarios without a surrounding passage. Multiple experiments, exploring response hallucination and considering question complexity, were conducted on ChatGPT. Evaluation employed well-known Question Answering (QA) datasets, including SQuAD, NewsQA, and PersianQuAD, across English and Persian languages. Metrics such as F-score, exact match, and accuracy were employed in the assessment. The study reveals that, while ChatGPT demonstrates competence as a generative model, it is less effective in question answering compared to task-specific models. Providing context improves its performance, and prompt engineering enhances precision, particularly for questions lacking explicit answers in provided paragraphs. ChatGPT excels at simpler factual questions compared to "how" and "why" question types. The evaluation highlights occurrences of hallucinations, where ChatGPT provides responses to questions without available answers in the provided context.

{{</citation>}}


### (122/161) KnowGPT: Black-Box Knowledge Injection for Large Language Models (Qinggang Zhang et al., 2023)

{{<citation>}}

Qinggang Zhang, Junnan Dong, Hao Chen, Xiao Huang, Daochen Zha, Zailiang Yu. (2023)  
**KnowGPT: Black-Box Knowledge Injection for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, GPT-4, Knowledge Graph, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.06185v1)  

---


**ABSTRACT**  
Generative Large Language Models (LLMs), such as ChatGPT, offer interactive APIs that can answer common questions at a human-expert level. However, these models often give inaccurate or incorrect responses when faced with questions requiring domain-specific or professional-specific knowledge not covered in their training corpus. Furthermore, many state-of-the-art LLMs are not open-source, making it challenging to inject knowledge with model APIs only. In this work, we introduce KnowGPT, a black-box knowledge injection framework for LLMs in question answering. KnowGPT leverages deep reinforcement learning (RL) to extract relevant knowledge from Knowledge Graphs (KGs) and use Multi-Armed Bandit (MAB) to construct the most suitable prompt for each question. Our extensive experiments on three benchmark datasets showcase that KnowGPT significantly enhances the existing methods. Notably, KnowGPT achieves an average improvement of 23.7% over ChatGPT and an average improvement of 2.9% over GPT-4. Additionally, KnowGPT attains a 91.6% accuracy on the OpenbookQA official leaderboard, which is comparable to human-level performance.

{{</citation>}}


### (123/161) ConvD: Attention Enhanced Dynamic Convolutional Embeddings for Knowledge Graph Completion (Wenbin Guo et al., 2023)

{{<citation>}}

Wenbin Guo, Zhao Li, Xin Wang, Zirui Chen. (2023)  
**ConvD: Attention Enhanced Dynamic Convolutional Embeddings for Knowledge Graph Completion**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Attention, Embedding, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2312.07589v1)  

---


**ABSTRACT**  
Knowledge graphs generally suffer from incompleteness, which can be alleviated by completing the missing information. Deep knowledge convolutional embedding models based on neural networks are currently popular methods for knowledge graph completion. However, most existing methods use external convolution kernels and traditional plain convolution processes, which limits the feature interaction capability of the model. In this paper, we propose a novel dynamic convolutional embedding model ConvD for knowledge graph completion, which directly reshapes the relation embeddings into multiple internal convolution kernels to improve the external convolution kernels of the traditional convolutional embedding model. The internal convolution kernels can effectively augment the feature interaction between the relation embeddings and entity embeddings, thus enhancing the model embedding performance. Moreover, we design a priori knowledge-optimized attention mechanism, which can assign different contribution weight coefficients to multiple relation convolution kernels for dynamic convolution to improve the expressiveness of the model further. Extensive experiments on various datasets show that our proposed model consistently outperforms the state-of-the-art baseline methods, with average improvements ranging from 11.30\% to 16.92\% across all model evaluation metrics. Ablation experiments verify the effectiveness of each component module of the ConvD model.

{{</citation>}}


### (124/161) Unlocking Anticipatory Text Generation: A Constrained Approach for Faithful Decoding with Large Language Models (Lifu Tu et al., 2023)

{{<citation>}}

Lifu Tu, Semih Yavuz, Jin Qu, Jiacheng Xu, Rui Meng, Caiming Xiong, Yingbo Zhou. (2023)  
**Unlocking Anticipatory Text Generation: A Constrained Approach for Faithful Decoding with Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model, Text Generation  
[Paper Link](http://arxiv.org/abs/2312.06149v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have demonstrated a powerful ability for text generation. However, achieving optimal results with a given prompt or instruction can be challenging, especially for billion-sized models. Additionally, undesired behaviors such as toxicity or hallucinations can manifest. While much larger models (e.g., ChatGPT) may demonstrate strength in mitigating these issues, there is still no guarantee of complete prevention. In this work, we propose formalizing text generation as a future-constrained generation problem to minimize undesirable behaviors and enforce faithfulness to instructions. The estimation of future constraint satisfaction, accomplished using LLMs, guides the text generation process. Our extensive experiments demonstrate the effectiveness of the proposed approach across three distinct text generation tasks: keyword-constrained generation (Lin et al., 2020), toxicity reduction (Gehman et al., 2020), and factual correctness in question-answering (Gao et al., 2023).

{{</citation>}}


### (125/161) Order Matters in the Presence of Dataset Imbalance for Multilingual Learning (Dami Choi et al., 2023)

{{<citation>}}

Dami Choi, Derrick Xin, Hamid Dadkhahi, Justin Gilmer, Ankush Garg, Orhan Firat, Chih-Kuan Yeh, Andrew M. Dai, Behrooz Ghorbani. (2023)  
**Order Matters in the Presence of Dataset Imbalance for Multilingual Learning**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Multilingual  
[Paper Link](http://arxiv.org/abs/2312.06134v1)  

---


**ABSTRACT**  
In this paper, we empirically study the optimization dynamics of multi-task learning, particularly focusing on those that govern a collection of tasks with significant data imbalance. We present a simple yet effective method of pre-training on high-resource tasks, followed by fine-tuning on a mixture of high/low-resource tasks. We provide a thorough empirical study and analysis of this method's benefits showing that it achieves consistent improvements relative to the performance trade-off profile of standard static weighting. We analyze under what data regimes this method is applicable and show its improvements empirically in neural machine translation (NMT) and multi-lingual language modeling.

{{</citation>}}


### (126/161) GTA: Gated Toxicity Avoidance for LM Performance Preservation (Heegyu Kim et al., 2023)

{{<citation>}}

Heegyu Kim, Hyunsouk Cho. (2023)  
**GTA: Gated Toxicity Avoidance for LM Performance Preservation**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: GPT, GPT-4, NLP, Text Generation  
[Paper Link](http://arxiv.org/abs/2312.06122v1)  

---


**ABSTRACT**  
Caution: This paper includes offensive words that could potentially cause unpleasantness. The fast-paced evolution of generative language models such as GPT-4 has demonstrated outstanding results in various NLP generation tasks. However, due to the potential generation of offensive words related to race or gender, various Controllable Text Generation (CTG) methods have been proposed to mitigate the occurrence of harmful words. However, existing CTG methods not only reduce toxicity but also negatively impact several aspects of the language model's generation performance, including topic consistency, grammar, and perplexity. This paper explores the limitations of previous methods and introduces a novel solution in the form of a simple Gated Toxicity Avoidance (GTA) that can be applied to any CTG method. We also evaluate the effectiveness of the proposed GTA by comparing it with state-of-the-art CTG methods across various datasets. Our findings reveal that gated toxicity avoidance efficiently achieves comparable levels of toxicity reduction to the original CTG methods while preserving the generation performance of the language model.

{{</citation>}}


### (127/161) Generative Large Language Models Are All-purpose Text Analytics Engines: Text-to-text Learning Is All Your Need (Cheng Peng et al., 2023)

{{<citation>}}

Cheng Peng, Xi Yang, Aokun Chen, Zehao Yu, Kaleb E Smith, Anthony B Costa, Mona G Flores, Jiang Bian, Yonghui Wu. (2023)  
**Generative Large Language Models Are All-purpose Text Analytics Engines: Text-to-text Learning Is All Your Need**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, Language Model, NLP, Transformer  
[Paper Link](http://arxiv.org/abs/2312.06099v1)  

---


**ABSTRACT**  
Objective To solve major clinical natural language processing (NLP) tasks using a unified text-to-text learning architecture based on a generative large language model (LLM) via prompt tuning. Methods We formulated 7 key clinical NLP tasks as text-to-text learning and solved them using one unified generative clinical LLM, GatorTronGPT, developed using GPT-3 architecture and trained with up to 20 billion parameters. We adopted soft prompts (i.e., trainable vectors) with frozen LLM, where the LLM parameters were not updated (i.e., frozen) and only the vectors of soft prompts were updated, known as prompt tuning. We added additional soft prompts as a prefix to the input layer, which were optimized during the prompt tuning. We evaluated the proposed method using 7 clinical NLP tasks and compared them with previous task-specific solutions based on Transformer models. Results and Conclusion The proposed approach achieved state-of-the-art performance for 5 out of 7 major clinical NLP tasks using one unified generative LLM. Our approach outperformed previous task-specific transformer models by ~3% for concept extraction and 7% for relation extraction applied to social determinants of health, 3.4% for clinical concept normalization, 3.4~10% for clinical abbreviation disambiguation, and 5.5~9% for natural language inference. Our approach also outperformed a previously developed prompt-based machine reading comprehension (MRC) model, GatorTron-MRC, for clinical concept and relation extraction. The proposed approach can deliver the ``one model for all`` promise from training to deployment using a unified generative LLM.

{{</citation>}}


### (128/161) MATK: The Meme Analytical Tool Kit (Ming Shan Hee et al., 2023)

{{<citation>}}

Ming Shan Hee, Aditi Kumaresan, Nguyen Khoi Hoang, Nirmalendu Prakash, Rui Cao, Roy Ka-Wei Lee. (2023)  
**MATK: The Meme Analytical Tool Kit**  

---
Primary Category: cs.CL  
Categories: I-1-4, cs-CL, cs-CV, cs-MM, cs.CL  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06094v1)  

---


**ABSTRACT**  
The rise of social media platforms has brought about a new digital culture called memes. Memes, which combine visuals and text, can strongly influence public opinions on social and cultural issues. As a result, people have become interested in categorizing memes, leading to the development of various datasets and multimodal models that show promising results in this field. However, there is currently a lack of a single library that allows for the reproduction, evaluation, and comparison of these models using fair benchmarks and settings. To fill this gap, we introduce the Meme Analytical Tool Kit (MATK), an open-source toolkit specifically designed to support existing memes datasets and cutting-edge multimodal models. MATK aims to assist researchers and engineers in training and reproducing these multimodal models for meme classification tasks, while also providing analysis techniques to gain insights into their strengths and weaknesses. To access MATK, please visit \url{https://github.com/Social-AI-Studio/MATK}.

{{</citation>}}


### (129/161) PromptMTopic: Unsupervised Multimodal Topic Modeling of Memes using Large Language Models (Nirmalendu Prakash et al., 2023)

{{<citation>}}

Nirmalendu Prakash, Han Wang, Nguyen Khoi Hoang, Ming Shan Hee, Roy Ka-Wei Lee. (2023)  
**PromptMTopic: Unsupervised Multimodal Topic Modeling of Memes using Large Language Models**  

---
Primary Category: cs.CL  
Categories: I-1-4; I-1-7, cs-CL, cs-CV, cs-MM, cs.CL  
Keywords: Language Model, Topic Model, Topic Modeling  
[Paper Link](http://arxiv.org/abs/2312.06093v1)  

---


**ABSTRACT**  
The proliferation of social media has given rise to a new form of communication: memes. Memes are multimodal and often contain a combination of text and visual elements that convey meaning, humor, and cultural significance. While meme analysis has been an active area of research, little work has been done on unsupervised multimodal topic modeling of memes, which is important for content moderation, social media analysis, and cultural studies. We propose \textsf{PromptMTopic}, a novel multimodal prompt-based model designed to learn topics from both text and visual modalities by leveraging the language modeling capabilities of large language models. Our model effectively extracts and clusters topics learned from memes, considering the semantic interaction between the text and visual modalities. We evaluate our proposed model through extensive experiments on three real-world meme datasets, which demonstrate its superiority over state-of-the-art topic modeling baselines in learning descriptive topics in memes. Additionally, our qualitative analysis shows that \textsf{PromptMTopic} can identify meaningful and culturally relevant topics from memes. Our work contributes to the understanding of the topics and themes of memes, a crucial form of communication in today's society.\\ \red{\textbf{Disclaimer: This paper contains sensitive content that may be disturbing to some readers.}}

{{</citation>}}


### (130/161) SECNN: Squeeze-and-Excitation Convolutional Neural Network for Sentence Classification (Shandong Yuan, 2023)

{{<citation>}}

Shandong Yuan. (2023)  
**SECNN: Squeeze-and-Excitation Convolutional Neural Network for Sentence Classification**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.06088v1)  

---


**ABSTRACT**  
Sentence classification is one of the basic tasks of natural language processing. Convolution neural network (CNN) has the ability to extract n-grams features through convolutional filters and capture local correlations between consecutive words in parallel, so CNN is a popular neural network architecture to dealing with the task. But restricted by the width of convolutional filters, it is difficult for CNN to capture long term contextual dependencies. Attention is a mechanism that considers global information and pays more attention to keywords in sentences, thus attention mechanism is cooperated with CNN network to improve performance in sentence classification task. In our work, we don't focus on keyword in a sentence, but on which CNN's output feature map is more important. We propose a Squeeze-and-Excitation Convolutional neural Network (SECNN) for sentence classification. SECNN takes the feature maps from multiple CNN as different channels of sentence representation, and then, we can utilize channel attention mechanism, that is SE attention mechanism, to enable the model to learn the attention weights of different channel features. The results show that our model achieves advanced performance in the sentence classification task.

{{</citation>}}


### (131/161) IEKG: A Commonsense Knowledge Graph for Idiomatic Expressions (Ziheng Zeng et al., 2023)

{{<citation>}}

Ziheng Zeng, Kellen Tan Cheng, Srihari Venkat Nanniyur, Jianing Zhou, Suma Bhat. (2023)  
**IEKG: A Commonsense Knowledge Graph for Idiomatic Expressions**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Commonsense Knowledge, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2312.06053v1)  

---


**ABSTRACT**  
Idiomatic expression (IE) processing and comprehension have challenged pre-trained language models (PTLMs) because their meanings are non-compositional. Unlike prior works that enable IE comprehension through fine-tuning PTLMs with sentences containing IEs, in this work, we construct IEKG, a commonsense knowledge graph for figurative interpretations of IEs. This extends the established ATOMIC2020 graph, converting PTLMs into knowledge models (KMs) that encode and infer commonsense knowledge related to IE use. Experiments show that various PTLMs can be converted into KMs with IEKG. We verify the quality of IEKG and the ability of the trained KMs with automatic and human evaluation. Through applications in natural language understanding, we show that a PTLM injected with knowledge from IEKG exhibits improved IE comprehension ability and can generalize to IEs unseen during training.

{{</citation>}}


## physics.soc-ph (1)



### (132/161) Emergence of Scale-Free Networks in Social Interactions among Large Language Models (Giordano De Marzo et al., 2023)

{{<citation>}}

Giordano De Marzo, Luciano Pietronero, David Garcia. (2023)  
**Emergence of Scale-Free Networks in Social Interactions among Large Language Models**  

---
Primary Category: physics.soc-ph  
Categories: cs-CY, physics-soc-ph, physics.soc-ph  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06619v1)  

---


**ABSTRACT**  
Scale-free networks are one of the most famous examples of emergent behavior and are ubiquitous in social systems, especially online social media in which users can follow each other. By analyzing the interactions of multiple generative agents using GPT3.5-turbo as a language model, we demonstrate their ability to not only mimic individual human linguistic behavior but also exhibit collective phenomena intrinsic to human societies, in particular the emergence of scale-free networks. We discovered that this process is disrupted by a skewed token prior distribution of GPT3.5-turbo, which can lead to networks with extreme centralization as a kind of alignment. We show how renaming agents removes these token priors and allows the model to generate a range of networks from random networks to more realistic scale-free networks.

{{</citation>}}


## math.OC (1)



### (133/161) Amazon Locker Capacity Management (Samyukta Sethuraman et al., 2023)

{{<citation>}}

Samyukta Sethuraman, Ankur Bansal, Setareh Mardan, Mauricio G. C. Resende, Timothy L. Jacobs. (2023)  
**Amazon Locker Capacity Management**  

---
Primary Category: math.OC  
Categories: 68T05, 90B05, 90B06, 90C90, G-1-6; I-2-6; I-2-8; I-6-3, cs-AI, math-OC, math.OC  
Keywords: Amazon  
[Paper Link](http://arxiv.org/abs/2312.06579v1)  

---


**ABSTRACT**  
Amazon Locker is a self-service delivery or pickup location where customers can pick up packages and drop off returns. A basic first-come-first-served policy for accepting package delivery requests to lockers results in lockers becoming full with standard shipping speed (3-5 day shipping) packages, and leaving no space left for expedited packages which are mostly Next-Day or Two-Day shipping. This paper proposes a solution to the problem of determining how much locker capacity to reserve for different ship-option packages. Yield management is a much researched field with popular applications in the airline, car rental, and hotel industries. However, Amazon Locker poses a unique challenge in this field since the number of days a package will wait in a locker (package dwell time) is, in general, unknown. The proposed solution combines machine learning techniques to predict locker demand and package dwell time, and linear programming to maximize throughput in lockers. The decision variables from this optimization provide optimal capacity reservation values for different ship options. This resulted in a year-over-year increase of 9% in Locker throughput worldwide during holiday season of 2018, impacting millions of customers.

{{</citation>}}


## cs.NE (1)



### (134/161) Deep Photonic Reservoir Computer for Speech Recognition (Enrico Picco et al., 2023)

{{<citation>}}

Enrico Picco, Alessandro Lupo, Serge Massar. (2023)  
**Deep Photonic Reservoir Computer for Speech Recognition**  

---
Primary Category: cs.NE  
Categories: cs-NE, cs-SD, cs.NE, eess-AS, physics-optics  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2312.06558v1)  

---


**ABSTRACT**  
Speech recognition is a critical task in the field of artificial intelligence and has witnessed remarkable advancements thanks to large and complex neural networks, whose training process typically requires massive amounts of labeled data and computationally intensive operations. An alternative paradigm, reservoir computing, is energy efficient and is well adapted to implementation in physical substrates, but exhibits limitations in performance when compared to more resource-intensive machine learning algorithms. In this work we address this challenge by investigating different architectures of interconnected reservoirs, all falling under the umbrella of deep reservoir computing. We propose a photonic-based deep reservoir computer and evaluate its effectiveness on different speech recognition tasks. We show specific design choices that aim to simplify the practical implementation of a reservoir computer while simultaneously achieving high-speed processing of high-dimensional audio signals. Overall, with the present work we hope to help the advancement of low-power and high-performance neuromorphic hardware.

{{</citation>}}


## eess.SP (3)



### (135/161) On the Impact of CDL and TDL Augmentation for RF Fingerprinting under Impaired Channels (Omer Melih Gul et al., 2023)

{{<citation>}}

Omer Melih Gul, Michel Kulhandjian, Burak Kantarci, Claude D'Amours, Azzedine Touazi, Cliff Ellement. (2023)  
**On the Impact of CDL and TDL Augmentation for RF Fingerprinting under Impaired Channels**  

---
Primary Category: eess.SP  
Categories: cs-CR, cs-SY, eess-SP, eess-SY, eess.SP  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2312.06555v1)  

---


**ABSTRACT**  
Cyber-physical systems have recently been used in several areas (such as connected and autonomous vehicles) due to their high maneuverability. On the other hand, they are susceptible to cyber-attacks. Radio frequency (RF) fingerprinting emerges as a promising approach. This work aims to analyze the impact of decoupling tapped delay line and clustered delay line (TDL+CDL) augmentation-driven deep learning (DL) on transmitter-specific fingerprints to discriminate malicious users from legitimate ones. This work also considers 5G-only-CDL, WiFi-only-TDL augmentation approaches. RF fingerprinting models are sensitive to changing channels and environmental conditions. For this reason, they should be considered during the deployment of a DL model. Data acquisition can be another option. Nonetheless, gathering samples under various conditions for a train set formation may be quite hard. Consequently, data acquisition may not be feasible. This work uses a dataset that includes 5G, 4G, and WiFi samples, and it empowers a CDL+TDL-based augmentation technique in order to boost the learning performance of the DL model. Numerical results show that CDL+TDL, 5G-only-CDL, and WiFi-only-TDL augmentation approaches achieve 87.59%, 81.63%, 79.21% accuracy on unobserved data while TDL/CDL augmentation technique and no augmentation approach result in 77.81% and 74.84% accuracy on unobserved data, respectively.

{{</citation>}}


### (136/161) IndoorGNN: A Graph Neural Network based approach for Indoor Localization using WiFi RSSI (Rahul Vishwakarma et al., 2023)

{{<citation>}}

Rahul Vishwakarma, Rucha Bhalchandra Joshi, Subhankar Mishra. (2023)  
**IndoorGNN: A Graph Neural Network based approach for Indoor Localization using WiFi RSSI**  

---
Primary Category: eess.SP  
Categories: cs-LG, eess-SP, eess.SP  
Keywords: GNN, Graph Neural Network  
[Paper Link](http://arxiv.org/abs/2312.07609v1)  

---


**ABSTRACT**  
Indoor localization is the process of determining the location of a person or object inside a building. Potential usage of indoor localization includes navigation, personalization, safety and security, and asset tracking. Commonly used technologies for indoor localization include WiFi, Bluetooth, RFID, and Ultra-wideband. Among these, WiFi's Received Signal Strength Indicator (RSSI)-based localization is preferred because of widely available WiFi Access Points (APs). We have two main contributions. First, we develop our method, 'IndoorGNN' which involves using a Graph Neural Network (GNN) based algorithm in a supervised manner to classify a specific location into a particular region based on the RSSI values collected at that location. Most of the ML algorithms that perform this classification require a large number of labeled data points (RSSI vectors with location information). Collecting such data points is a labor-intensive and time-consuming task. To overcome this challenge, as our second contribution, we demonstrate the performance of IndoorGNN on the restricted dataset. It shows a comparable prediction accuracy to that of the complete dataset. We performed experiments on the UJIIndoorLoc and MNAV datasets, which are real-world standard indoor localization datasets. Our experiments show that IndoorGNN gives better location prediction accuracies when compared with state-of-the-art existing conventional as well as GNN-based methods for this same task. It continues to outperform these algorithms even with restricted datasets. It is noteworthy that its performance does not decrease a lot with a decrease in the number of available data points. Our method can be utilized for navigation and wayfinding in complex indoor environments, asset tracking and building management, enhancing mobile applications with location-based services, and improving safety and security during emergencies.

{{</citation>}}


### (137/161) Sense, Predict, Adapt, Repeat: A Blueprint for Design of New Adaptive AI-Centric Sensing Systems (Soheil Hor et al., 2023)

{{<citation>}}

Soheil Hor, Amin Arbabian. (2023)  
**Sense, Predict, Adapt, Repeat: A Blueprint for Design of New Adaptive AI-Centric Sensing Systems**  

---
Primary Category: eess.SP  
Categories: cs-AI, cs-SY, eess-SP, eess-SY, eess.SP  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.07602v1)  

---


**ABSTRACT**  
As Moore's Law loses momentum, improving size, performance, and efficiency of processors has become increasingly challenging, ending the era of predictable improvements in hardware performance. Meanwhile, the widespread incorporation of high-definition sensors in consumer devices and autonomous technologies has fueled a significant upsurge in sensory data. Current global trends reveal that the volume of generated data already exceeds human consumption capacity, making AI algorithms the primary consumers of data worldwide. To address this, a novel approach to designing AI-centric sensing systems is needed that can bridge the gap between the increasing capabilities of high-definition sensors and the limitations of AI processors. This paper provides an overview of efficient sensing and perception methods in both AI and sensing domains, emphasizing the necessity of co-designing AI algorithms and sensing systems for dynamic perception. The proposed approach involves a framework for designing and analyzing dynamic AI-in-the-loop sensing systems, suggesting a fundamentally new method for designing adaptive sensing systems through inference-time AI-to-sensor feedback and end-to-end efficiency and performance optimization.

{{</citation>}}


## cs.SD (4)



### (138/161) Towards Domain-Specific Cross-Corpus Speech Emotion Recognition Approach (Yan Zhao et al., 2023)

{{<citation>}}

Yan Zhao, Yuan Zong, Hailun Lian, Cheng Lu, Jingang Shi, Wenming Zheng. (2023)  
**Towards Domain-Specific Cross-Corpus Speech Emotion Recognition Approach**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2312.06466v1)  

---


**ABSTRACT**  
Cross-corpus speech emotion recognition (SER) poses a challenge due to feature distribution mismatch, potentially degrading the performance of established SER methods. In this paper, we tackle this challenge by proposing a novel transfer subspace learning method called acoustic knowledgeguided transfer linear regression (AKTLR). Unlike existing approaches, which often overlook domain-specific knowledge related to SER and simply treat cross-corpus SER as a generic transfer learning task, our AKTLR method is built upon a well-designed acoustic knowledge-guided dual sparsity constraint mechanism. This mechanism emphasizes the potential of minimalistic acoustic parameter feature sets to alleviate classifier overadaptation, which is empirically validated acoustic knowledge in SER, enabling superior generalization in cross-corpus SER tasks compared to using large feature sets. Through this mechanism, we extend a simple transfer linear regression model to AKTLR. This extension harnesses its full capability to seek emotiondiscriminative and corpus-invariant features from established acoustic parameter feature sets used for describing speech signals across two scales: contributive acoustic parameter groups and constituent elements within each contributive group. Our proposed method is evaluated through extensive cross-corpus SER experiments on three widely-used speech emotion corpora: EmoDB, eNTERFACE, and CASIA. The results confirm the effectiveness and superior performance of our method, outperforming recent state-of-the-art transfer subspace learning and deep transfer learning-based cross-corpus SER methods. Furthermore, our work provides experimental evidence supporting the feasibility and superiority of incorporating domain-specific knowledge into the transfer learning model to address cross-corpus SER tasks.

{{</citation>}}


### (139/161) Deep Imbalanced Learning for Multimodal Emotion Recognition in Conversations (Tao Meng et al., 2023)

{{<citation>}}

Tao Meng, Yuntao Shou, Wei Ai, Nan Yin, Keqin Li. (2023)  
**Deep Imbalanced Learning for Multimodal Emotion Recognition in Conversations**  

---
Primary Category: cs.SD  
Categories: cs-CL, cs-SD, cs.SD, eess-AS  
Keywords: Emotion Recognition, Representation Learning  
[Paper Link](http://arxiv.org/abs/2312.06337v1)  

---


**ABSTRACT**  
The main task of Multimodal Emotion Recognition in Conversations (MERC) is to identify the emotions in modalities, e.g., text, audio, image and video, which is a significant development direction for realizing machine intelligence. However, many data in MERC naturally exhibit an imbalanced distribution of emotion categories, and researchers ignore the negative impact of imbalanced data on emotion recognition. To tackle this problem, we systematically analyze it from three aspects: data augmentation, loss sensitivity, and sampling strategy, and propose the Class Boundary Enhanced Representation Learning (CBERL) model. Concretely, we first design a multimodal generative adversarial network to address the imbalanced distribution of {emotion} categories in raw data. Secondly, a deep joint variational autoencoder is proposed to fuse complementary semantic information across modalities and obtain discriminative feature representations. Finally, we implement a multi-task graph neural network with mask reconstruction and classification optimization to solve the problem of overfitting and underfitting in class boundary learning, and achieve cross-modal emotion recognition. We have conducted extensive experiments on the IEMOCAP and MELD benchmark datasets, and the results show that CBERL has achieved a certain performance improvement in the effectiveness of emotion recognition. Especially on the minority class fear and disgust emotion labels, our model improves the accuracy and F1 value by 10% to 20%.

{{</citation>}}


### (140/161) Transformer Attractors for Robust and Efficient End-to-End Neural Diarization (Lahiru Samarakoon et al., 2023)

{{<citation>}}

Lahiru Samarakoon, Samuel J. Broughton, Marc Härkönen, Ivan Fung. (2023)  
**Transformer Attractors for Robust and Efficient End-to-End Neural Diarization**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: LSTM, Transformer  
[Paper Link](http://arxiv.org/abs/2312.06253v1)  

---


**ABSTRACT**  
End-to-end neural diarization with encoder-decoder based attractors (EEND-EDA) is a method to perform diarization in a single neural network. EDA handles the diarization of a flexible number of speakers by using an LSTM-based encoder-decoder that generates a set of speaker-wise attractors in an autoregressive manner. In this paper, we propose to replace EDA with a transformer-based attractor calculation (TA) module. TA is composed of a Combiner block and a Transformer decoder. The main function of the combiner block is to generate conversational dependent (CD) embeddings by incorporating learned conversational information into a global set of embeddings. These CD embeddings will then serve as the input for the transformer decoder. Results on public datasets show that EEND-TA achieves 2.68% absolute DER improvement over EEND-EDA. EEND-TA inference is 1.28 times faster than that of EEND-EDA.

{{</citation>}}


### (141/161) Speaker-Text Retrieval via Contrastive Learning (Xuechen Liu et al., 2023)

{{<citation>}}

Xuechen Liu, Xin Wang, Erica Cooper, Xiaoxiao Miao, Junichi Yamagishi. (2023)  
**Speaker-Text Retrieval via Contrastive Learning**  

---
Primary Category: cs.SD  
Categories: cs-SD, cs.SD, eess-AS  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.06055v1)  

---


**ABSTRACT**  
In this study, we introduce a novel cross-modal retrieval task involving speaker descriptions and their corresponding audio samples. Utilizing pre-trained speaker and text encoders, we present a simple learning framework based on contrastive learning. Additionally, we explore the impact of incorporating speaker labels into the training process. Our findings establish the effectiveness of linking speaker and text information for the task for both English and Japanese languages, across diverse data configurations. Additional visual analysis unveils potential nuanced associations between speaker clustering and retrieval performance.

{{</citation>}}


## eess.IV (3)



### (142/161) Point Transformer with Federated Learning for Predicting Breast Cancer HER2 Status from Hematoxylin and Eosin-Stained Whole Slide Images (Bao Li et al., 2023)

{{<citation>}}

Bao Li, Zhenyu Liu, Lizhi Shao, Bensheng Qiu, Hong Bu, Jie Tian. (2023)  
**Point Transformer with Federated Learning for Predicting Breast Cancer HER2 Status from Hematoxylin and Eosin-Stained Whole Slide Images**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06454v1)  

---


**ABSTRACT**  
Directly predicting human epidermal growth factor receptor 2 (HER2) status from widely available hematoxylin and eosin (HE)-stained whole slide images (WSIs) can reduce technical costs and expedite treatment selection. Accurately predicting HER2 requires large collections of multi-site WSIs. Federated learning enables collaborative training of these WSIs without gigabyte-size WSIs transportation and data privacy concerns. However, federated learning encounters challenges in addressing label imbalance in multi-site WSIs from the real world. Moreover, existing WSI classification methods cannot simultaneously exploit local context information and long-range dependencies in the site-end feature representation of federated learning. To address these issues, we present a point transformer with federated learning for multi-site HER2 status prediction from HE-stained WSIs. Our approach incorporates two novel designs. We propose a dynamic label distribution strategy and an auxiliary classifier, which helps to establish a well-initialized model and mitigate label distribution variations across sites. Additionally, we propose a farthest cosine sampling based on cosine distance. It can sample the most distinctive features and capture the long-range dependencies. Extensive experiments and analysis show that our method achieves state-of-the-art performance at four sites with a total of 2687 WSIs. Furthermore, we demonstrate that our model can generalize to two unseen sites with 229 WSIs.

{{</citation>}}


### (143/161) SP-DiffDose: A Conditional Diffusion Model for Radiation Dose Prediction Based on Multi-Scale Fusion of Anatomical Structures, Guided by SwinTransformer and Projector (Linjie Fu et al., 2023)

{{<citation>}}

Linjie Fu, Xia Li, Xiuding Cai, Yingkai Wang, Xueyao Wang, Yu Yao, Yali Shen. (2023)  
**SP-DiffDose: A Conditional Diffusion Model for Radiation Dose Prediction Based on Multi-Scale Fusion of Anatomical Structures, Guided by SwinTransformer and Projector**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.06187v1)  

---


**ABSTRACT**  
Radiation therapy serves as an effective and standard method for cancer treatment. Excellent radiation therapy plans always rely on high-quality dose distribution maps obtained through repeated trial and error by experienced experts. However, due to individual differences and complex clinical situations, even seasoned expert teams may need help to achieve the best treatment plan every time quickly. Many automatic dose distribution prediction methods have been proposed recently to accelerate the radiation therapy planning process and have achieved good results. However, these results suffer from over-smoothing issues, with the obtained dose distribution maps needing more high-frequency details, limiting their clinical application. To address these limitations, we propose a dose prediction diffusion model based on SwinTransformer and a projector, SP-DiffDose. To capture the direct correlation between anatomical structure and dose distribution maps, SP-DiffDose uses a structural encoder to extract features from anatomical images, then employs a conditional diffusion process to blend noise and anatomical images at multiple scales and gradually map them to dose distribution maps. To enhance the dose prediction distribution for organs at risk, SP-DiffDose utilizes SwinTransformer in the deeper layers of the network to capture features at different scales in the image. To learn good representations from the fused features, SP-DiffDose passes the fused features through a designed projector, improving dose prediction accuracy. Finally, we evaluate SP-DiffDose on an internal dataset. The results show that SP-DiffDose outperforms existing methods on multiple evaluation metrics, demonstrating the superiority and generalizability of our method.

{{</citation>}}


### (144/161) Hundred-Kilobyte Lookup Tables for Efficient Single-Image Super-Resolution (Binxiao Huang et al., 2023)

{{<citation>}}

Binxiao Huang, Jason Chun Lok Li, Jie Ran, Boyu Li, Jiajun Zhou, Dahai Yu, Ngai Wong. (2023)  
**Hundred-Kilobyte Lookup Tables for Efficient Single-Image Super-Resolution**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06101v1)  

---


**ABSTRACT**  
Conventional super-resolution (SR) schemes make heavy use of convolutional neural networks (CNNs), which involve intensive multiply-accumulate (MAC) operations, and require specialized hardware such as graphics processing units. This contradicts the regime of edge AI that often runs on devices strained by power, computing, and storage resources. Such a challenge has motivated a series of lookup table (LUT)-based SR schemes that employ simple LUT readout and largely elude CNN computation. Nonetheless, the multi-megabyte LUTs in existing methods still prohibit on-chip storage and necessitate off-chip memory transport. This work tackles this storage hurdle and innovates hundred-kilobyte LUT (HKLUT) models amenable to on-chip cache. Utilizing an asymmetric two-branch multistage network coupled with a suite of specialized kernel patterns, HKLUT demonstrates an uncompromising performance and superior hardware efficiency over existing LUT schemes.

{{</citation>}}


## cs.CR (6)



### (145/161) Numeric Truncation Security Predicate (Timofey Mezhuev et al., 2023)

{{<citation>}}

Timofey Mezhuev, Ilay Kobrin, Alexey Vishnyakov, Daniil Kuts. (2023)  
**Numeric Truncation Security Predicate**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SE, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.06425v1)  

---


**ABSTRACT**  
Numeric truncation is a widely spread error in software written in languages with static data typing, such as C/C++ or Java. It occurs when the significant bits of the value with a bigger type size are truncated during value conversion to the smaller type. Utilizing one of the most powerful methods for path exploration and automated bug detection called dynamic symbolic execution (DSE), we propose the symbolic security predicate for numeric truncation error detection, developed on top of DSE tool Sydr. Firstly, we execute the program on the data, which does not lead to any errors. During program execution we update symbolic shadow stack and shadow registers to track symbolic sizes of the symbolic variables to avoid false positives. Then, if we meet the instruction, which truncates the symbolic variable, we build the security predicate, try to solve it with the SMT-solver and in case of success save new input file to reproduce the error. We tested our approach on Juliet Dynamic test suite for CWE-197 and achieved 100% accuracy. We approved the workability of our approach by detecting 12 new errors of numeric truncation in 5 different real-world open source projects within OSS-Sydr-Fuzz project. All of the errors were reported, most of the reports were equipped with appropriate fixes, successfully confirmed and applied by project maintainers.

{{</citation>}}


### (146/161) On the Prediction of Hardware Security Properties of HLS Designs Using Graph Neural Networks (Amalia Artemis Koufopoulou et al., 2023)

{{<citation>}}

Amalia Artemis Koufopoulou, Athanasios Papadimitriou, Aggelos Pikrakis, Mihalis Psarakis, David Hely. (2023)  
**On the Prediction of Hardware Security Properties of HLS Designs Using Graph Neural Networks**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: GNN, Graph Neural Network, Graph Neural Networks, Security  
[Paper Link](http://arxiv.org/abs/2312.07594v1)  

---


**ABSTRACT**  
High-level synthesis (HLS) tools have provided significant productivity enhancements to the design flow of digital systems in recent years, resulting in highly-optimized circuits, in terms of area and latency. Given the evolution of hardware attacks, which can render them vulnerable, it is essential to consider security as a significant aspect of the HLS design flow. Yet the need to evaluate a huge number of functionally equivalent de-signs of the HLS design space challenges hardware security evaluation methods (e.g., fault injection - FI campaigns). In this work, we propose an evaluation methodology of hardware security properties of HLS-produced designs using state-of-the-art Graph Neural Network (GNN) approaches that achieves significant speedup and better scalability than typical evaluation methods (such as FI). We demonstrate the proposed methodology on a Double Modular Redundancy (DMR) coun-termeasure applied on an AES SBox implementation, en-hanced by diversifying the redundant modules through HLS directives. The experimental results show that GNNs can be efficiently trained to predict important hardware security met-rics concerning fault attacks (e.g., critical and detection error rates), by using regression. The proposed method predicts the fault vulnerability metrics of the HLS-based designs with high R-squared scores and achieves huge speedup compared to fault injection once the training of the GNN is completed.

{{</citation>}}


### (147/161) Security and Reliability Evaluation of Countermeasures implemented using High-Level Synthesis (Amalia Artemis Koufopoulou et al., 2023)

{{<citation>}}

Amalia Artemis Koufopoulou, Kalliopi Xevgeni, Athanasios Papadimitriou, Mihalis Psarakis, David Hely. (2023)  
**Security and Reliability Evaluation of Countermeasures implemented using High-Level Synthesis**  

---
Primary Category: cs.CR  
Categories: cs-AR, cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.06268v1)  

---


**ABSTRACT**  
As the complexity of digital circuits increases, High-Level Synthesis (HLS) is becoming a valuable tool to increase productivity and design reuse by utilizing relevant Electronic Design Automation (EDA) flows, either for Application-Specific Integrated Circuits (ASIC) or for Field Programmable Gate Arrays (FPGA). Side Channel Analysis (SCA) and Fault Injection (FI) attacks are powerful hardware attacks, capable of greatly weakening the theoretical security levels of secure implementations. Furthermore, critical applications demand high levels of reliability including fault tolerance. The lack of security and reliability driven optimizations in HLS tools makes it necessary for the HLS-based designs to validate that the properties of the algorithm and the countermeasures have not been compromised due to the HLS flow. In this work, we provide results on the resilience evaluation of HLS-based FPGA implementations for the aforementioned threats. As a test case, we use multiple versions of an on-the-fly SBOX algorithm integrating different countermeasures (hiding and masking), written in C and implemented using Vivado HLS. We perform extensive evaluations for all the designs and their optimization scenarios. The results provide evidence of issues arising due to HLS optimizations on the security and the reliability of cryptographic implementations. Furthermore, the results put HLS algorithms to the test of designing secure accelerators and can lead to improving them towards the goal of increasing productivity in the domain of secure and reliable cryptographic implementations.

{{</citation>}}


### (148/161) On The Effect of Replacement Policies on The Security of Randomized Cache Architectures (Moritz Peters et al., 2023)

{{<citation>}}

Moritz Peters, Nicolas Gaudin, Jan Philipp Thoma, Vianney Lapôtre, Pascal Cotret, Guy Gogniat, Tim Güneysu. (2023)  
**On The Effect of Replacement Policies on The Security of Randomized Cache Architectures**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.06235v1)  

---


**ABSTRACT**  
Randomizing the mapping of addresses to cache entries has proven to be an effective technique for hardening caches against contention-based attacks like Prime+Prome. While attacks and defenses are still evolving, it is clear that randomized caches significantly increase the security against such attacks. However, one aspect that is missing from most analyses of randomized cache architectures is the choice of the replacement policy. Often, only the random- and LRU replacement policies are investigated. However, LRU is not applicable to randomized caches due to its immense hardware overhead, while the random replacement policy is not ideal from a performance and security perspective.   In this paper, we explore replacement policies for randomized caches. We develop two new replacement policies and evaluate a total of five replacement policies regarding their security against Prime+Prune+Probe attackers. Moreover, we analyze the effect of the replacement policy on the system's performance and quantify the introduced hardware overhead. We implement randomized caches with configurable replacement policies in software and hardware using a custom cache simulator, gem5, and the CV32E40P RISC-V core. Among others, we show that the construction of eviction sets with our new policy, VARP-64, requires over 25-times more cache accesses than with the random replacement policy while also enhancing overall performance.

{{</citation>}}


### (149/161) Tackling Cyberattacks through AI-based Reactive Systems: A Holistic Review and Future Vision (Sergio Bernardez Molina et al., 2023)

{{<citation>}}

Sergio Bernardez Molina, Pantaleone Nespoli, Félix Gómez Mármol. (2023)  
**Tackling Cyberattacks through AI-based Reactive Systems: A Holistic Review and Future Vision**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06229v1)  

---


**ABSTRACT**  
There is no denying that the use of Information Technology (IT) is undergoing exponential growth in today's world. This digital transformation has also given rise to a multitude of security challenges, notably in the realm of cybercrime. In response to these growing threats, public and private sectors have prioritized the strengthening of IT security measures. In light of the growing security concern, Artificial Intelligence (AI) has gained prominence within the cybersecurity landscape. This paper presents a comprehensive survey of recent advancements in AI-driven threat response systems. To the best of our knowledge, the most recent survey covering the AI reaction domain was conducted in 2017. Since then, considerable literature has been published and therefore it is worth reviewing it. By means of several shared features, each of the studies is compared on a common ground. Through an analysis of the research papers conducted on a standardized basis, this survey aims to unravel the complexities and opportunities of integrating AI into cyber defense. The conclusions drawn from this collective analysis provide a comprehensive snapshot of the evolving landscape at the intersection of AI and cybersecurity. This landscape underscores the growing significance of not only anticipating and detecting threats but also responding to them effectively. Additionally, from these reviews, various research challenges for the future are presented. These challenges serve as a roadmap for researchers and practitioners in the field of AI-integrated reactive strategies.

{{</citation>}}


### (150/161) Poisoned ChatGPT Finds Work for Idle Hands: Exploring Developers' Coding Practices with Insecure Suggestions from Poisoned AI Models (Sanghak Oh et al., 2023)

{{<citation>}}

Sanghak Oh, Kiho Lee, Seonhye Park, Doowon Kim, Hyoungshick Kim. (2023)  
**Poisoned ChatGPT Finds Work for Idle Hands: Exploring Developers' Coding Practices with Insecure Suggestions from Poisoned AI Models**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: AI, ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2312.06227v1)  

---


**ABSTRACT**  
AI-powered coding assistant tools have revolutionized the software engineering ecosystem. However, prior work has demonstrated that these tools are vulnerable to poisoning attacks. In a poisoning attack, an attacker intentionally injects maliciously crafted insecure code snippets into training datasets to manipulate these tools. The poisoned tools can suggest insecure code to developers, resulting in vulnerabilities in their products that attackers can exploit. However, it is still little understood whether such poisoning attacks against the tools would be practical in real-world settings and how developers address the poisoning attacks during software development. To understand the real-world impact of poisoning attacks on developers who rely on AI-powered coding assistants, we conducted two user studies: an online survey and an in-lab study. The online survey involved 238 participants, including software developers and computer science students. The survey results revealed widespread adoption of these tools among participants, primarily to enhance coding speed, eliminate repetition, and gain boilerplate code. However, the survey also found that developers may misplace trust in these tools because they overlooked the risk of poisoning attacks. The in-lab study was conducted with 30 professional developers. The developers were asked to complete three programming tasks with a representative type of AI-powered coding assistant tool, running on Visual Studio Code. The in-lab study results showed that developers using a poisoned ChatGPT-like tool were more prone to including insecure code than those using an IntelliCode-like tool or no tool. This demonstrates the strong influence of these tools on the security of generated code. Our study results highlight the need for education and improved coding practices to address new security issues introduced by AI-powered coding assistant tools.

{{</citation>}}


## cs.DL (1)



### (151/161) Who Are Tweeting About Academic Publications? A Cochrane Systematic Review and Meta-Analysis of Altmetric Studies (Ashraf Maleki et al., 2023)

{{<citation>}}

Ashraf Maleki, Kim Holmberg. (2023)  
**Who Are Tweeting About Academic Publications? A Cochrane Systematic Review and Meta-Analysis of Altmetric Studies**  

---
Primary Category: cs.DL  
Categories: cs-DL, cs.DL  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2312.06399v1)  

---


**ABSTRACT**  
Previous studies have developed different categorizations of Twitter users who interact with scientific publications online, reflecting the difficulty in creating a unified approach. Using Cochrane Review meta-analysis to analyse earlier research (including 79,014 Twitter users, over twenty million tweets, and over five million tweeted publications from 23 studies), we created a consolidated robust categorization consisting of 11 user categories, at different dimensions, covering most of any future needs for user categorizations on Twitter and possibly also other social media platforms. Our findings showed, with moderate certainty, covering all the earlier different approaches employed, that the predominant Twitter group was individual users (66%), responsible for the majority of tweets (55%) and tweeted publications (50%), while organizations (22%, 27%, and 28%, respectively) and science communicators (16%, 13%, and 30%) clearly contributed smaller proportions. The cumulative findings from prior investigations indicated a statistically equal extent of academic individuals (33%) and other individuals (28%). While academic individuals shared more academic publications than other individuals (42% vs. 31%), they posted fewer tweets overall (22% vs. 30%), but these differences do not reach statistical significance. Despite significant heterogeneity arising from variations in categorization methods, the findings consistently indicate the importance of academics in disseminating academic publications.

{{</citation>}}


## cs.DB (1)



### (152/161) MUST: An Effective and Scalable Framework for Multimodal Search of Target Modality (Mengzhao Wang et al., 2023)

{{<citation>}}

Mengzhao Wang, Xiangyu Ke, Xiaoliang Xu, Lu Chen, Yunjun Gao, Pinpin Huang, Runkai Zhu. (2023)  
**MUST: An Effective and Scalable Framework for Multimodal Search of Target Modality**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs-IR, cs.DB  
Keywords: Computer Vision, Information Retrieval  
[Paper Link](http://arxiv.org/abs/2312.06397v1)  

---


**ABSTRACT**  
We investigate the problem of multimodal search of target modality, where the task involves enhancing a query in a specific target modality by integrating information from auxiliary modalities. The goal is to retrieve relevant objects whose contents in the target modality match the specified multimodal query. The paper first introduces two baseline approaches that integrate techniques from the Database, Information Retrieval, and Computer Vision communities. These baselines either merge the results of separate vector searches for each modality or perform a single-channel vector search by fusing all modalities. However, both baselines have limitations in terms of efficiency and accuracy as they fail to adequately consider the varying importance of fusing information across modalities. To overcome these limitations, the paper proposes a novel framework, called MUST. Our framework employs a hybrid fusion mechanism, combining different modalities at multiple stages. Notably, we leverage vector weight learning to determine the importance of each modality, thereby enhancing the accuracy of joint similarity measurement. Additionally, the proposed framework utilizes a fused proximity graph index, enabling efficient joint search for multimodal queries. MUST offers several other advantageous properties, including pluggable design to integrate any advanced embedding techniques, user flexibility to customize weight preferences, and modularized index construction. Extensive experiments on real-world datasets demonstrate the superiority of MUST over the baselines in terms of both search accuracy and efficiency. Our framework achieves over 10x faster search times while attaining an average of 93% higher accuracy. Furthermore, MUST exhibits scalability to datasets containing more than 10 million data elements.

{{</citation>}}


## cs.SE (3)



### (153/161) SciCat: A Curated Dataset of Scientific Software Repositories (Addi Malviya-Thakur et al., 2023)

{{<citation>}}

Addi Malviya-Thakur, Reed Milewicz, Lavinia Paganini, Ahmed Samir Imam Mahmoud, Audris Mockus. (2023)  
**SciCat: A Curated Dataset of Scientific Software Repositories**  

---
Primary Category: cs.SE  
Categories: cs-CE, cs-DL, cs-SE, cs.SE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.06382v1)  

---


**ABSTRACT**  
The proliferation of open-source scientific software for science and research presents opportunities and challenges. In this paper, we introduce the SciCat dataset -- a comprehensive collection of Free-Libre Open Source Software (FLOSS) projects, designed to address the need for a curated repository of scientific and research software. This collection is crucial for understanding the creation of scientific software and aiding in its development. To ensure extensive coverage, our approach involves selecting projects from a pool of 131 million deforked repositories from the World of Code data source. Subsequently, we analyze README.md files using OpenAI's advanced language models. Our classification focuses on software designed for scientific purposes, research-related projects, and research support software. The SciCat dataset aims to become an invaluable tool for researching science-related software, shedding light on emerging trends, prevalent practices, and challenges in the field of scientific software development. Furthermore, it includes data that can be linked to the World of Code, GitHub, and other platforms, providing a solid foundation for conducting comparative studies between scientific and non-scientific software.

{{</citation>}}


### (154/161) Can LLMs Configure Software Tools (Jai Kannan, 2023)

{{<citation>}}

Jai Kannan. (2023)  
**Can LLMs Configure Software Tools**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-SE, cs.SE  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2312.06121v1)  

---


**ABSTRACT**  
In software engineering, the meticulous configuration of software tools is crucial in ensuring optimal performance within intricate systems. However, the complexity inherent in selecting optimal configurations is exacerbated by the high-dimensional search spaces presented in modern applications. Conventional trial-and-error or intuition-driven methods are both inefficient and error-prone, impeding scalability and reproducibility. In this study, we embark on an exploration of leveraging Large-Language Models (LLMs) to streamline the software configuration process. We identify that the task of hyperparameter configuration for machine learning components within intelligent applications is particularly challenging due to the extensive search space and performance-critical nature. Existing methods, including Bayesian optimization, have limitations regarding initial setup, computational cost, and convergence efficiency. Our work presents a novel approach that employs LLMs, such as Chat-GPT, to identify starting conditions and narrow down the search space, improving configuration efficiency. We conducted a series of experiments to investigate the variability of LLM-generated responses, uncovering intriguing findings such as potential response caching and consistent behavior based on domain-specific keywords. Furthermore, our results from hyperparameter optimization experiments reveal the potential of LLMs in expediting initialization processes and optimizing configurations. While our initial insights are promising, they also indicate the need for further in-depth investigations and experiments in this domain.

{{</citation>}}


### (155/161) METAL: Metamorphic Testing Framework for Analyzing Large-Language Model Qualities (Sangwon Hyun et al., 2023)

{{<citation>}}

Sangwon Hyun, Mingyu Guo, M. Ali Babar. (2023)  
**METAL: Metamorphic Testing Framework for Analyzing Large-Language Model Qualities**  

---
Primary Category: cs.SE  
Categories: cs-AI, cs-CL, cs-SE, cs.SE  
Keywords: Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.06056v1)  

---


**ABSTRACT**  
Large-Language Models (LLMs) have shifted the paradigm of natural language data processing. However, their black-boxed and probabilistic characteristics can lead to potential risks in the quality of outputs in diverse LLM applications. Recent studies have tested Quality Attributes (QAs), such as robustness or fairness, of LLMs by generating adversarial input texts. However, existing studies have limited their coverage of QAs and tasks in LLMs and are difficult to extend. Additionally, these studies have only used one evaluation metric, Attack Success Rate (ASR), to assess the effectiveness of their approaches. We propose a MEtamorphic Testing for Analyzing LLMs (METAL) framework to address these issues by applying Metamorphic Testing (MT) techniques. This approach facilitates the systematic testing of LLM qualities by defining Metamorphic Relations (MRs), which serve as modularized evaluation metrics. The METAL framework can automatically generate hundreds of MRs from templates that cover various QAs and tasks. In addition, we introduced novel metrics that integrate the ASR method into the semantic qualities of text to assess the effectiveness of MRs accurately. Through the experiments conducted with three prominent LLMs, we have confirmed that the METAL framework effectively evaluates essential QAs on primary LLM tasks and reveals the quality risks in LLMs. Moreover, the newly proposed metrics can guide the optimal MRs for testing each task and suggest the most effective method for generating MRs.

{{</citation>}}


## cs.NI (1)



### (156/161) Mobile Edge Computing and AI Enabled Web3 Metaverse over 6G Wireless Communications: A Deep Reinforcement Learning Approach (Wenhan Yu et al., 2023)

{{<citation>}}

Wenhan Yu, Terence Jie Chua, Jun Zhao. (2023)  
**Mobile Edge Computing and AI Enabled Web3 Metaverse over 6G Wireless Communications: A Deep Reinforcement Learning Approach**  

---
Primary Category: cs.NI  
Categories: cs-AI, cs-NI, cs.NI  
Keywords: AI, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06293v1)  

---


**ABSTRACT**  
The Metaverse is gaining attention among academics as maturing technologies empower the promises and envisagements of a multi-purpose, integrated virtual environment. An interactive and immersive socialization experience between people is one of the promises of the Metaverse. In spite of the rapid advancements in current technologies, the computation required for a smooth, seamless and immersive socialization experience in the Metaverse is overbearing, and the accumulated user experience is essential to be considered. The computation burden calls for computation offloading, where the integration of virtual and physical world scenes is offloaded to an edge server. This paper introduces a novel Quality-of-Service (QoS) model for the accumulated experience in multi-user socialization on a multichannel wireless network. This QoS model utilizes deep reinforcement learning approaches to find the near-optimal channel resource allocation. Comprehensive experiments demonstrate that the adoption of the QoS model enhances the overall socialization experience.

{{</citation>}}


## eess.AS (2)



### (157/161) Testing Speech Emotion Recognition Machine Learning Models (Anna Derington et al., 2023)

{{<citation>}}

Anna Derington, Hagen Wierstorf, Ali Özkil, Florian Eyben, Felix Burkhardt, Björn W. Schuller. (2023)  
**Testing Speech Emotion Recognition Machine Learning Models**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Emotion Recognition  
[Paper Link](http://arxiv.org/abs/2312.06270v1)  

---


**ABSTRACT**  
Machine learning models for speech emotion recognition (SER) can be trained for different tasks and are usually evaluated on the basis of a few available datasets per task. Tasks could include arousal, valence, dominance, emotional categories, or tone of voice. Those models are mainly evaluated in terms of correlation or recall, and always show some errors in their predictions. The errors manifest themselves in model behaviour, which can be very different along different dimensions even if the same recall or correlation is achieved by the model. This paper investigates behavior of speech emotion recognition models with a testing framework which requires models to fulfill conditions in terms of correctness, fairness, and robustness.

{{</citation>}}


### (158/161) EEND-DEMUX: End-to-End Neural Speaker Diarization via Demultiplexed Speaker Embeddings (Sung Hwan Mun et al., 2023)

{{<citation>}}

Sung Hwan Mun, Min Hyun Han, Canyeong Moon, Nam Soo Kim. (2023)  
**EEND-DEMUX: End-to-End Neural Speaker Diarization via Demultiplexed Speaker Embeddings**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2312.06065v1)  

---


**ABSTRACT**  
In recent years, there have been studies to further improve the end-to-end neural speaker diarization (EEND) systems. This letter proposes the EEND-DEMUX model, a novel framework utilizing demultiplexed speaker embeddings. In this work, we focus on disentangling speaker-relevant information in the latent space and then transform each separated latent variable into its corresponding speech activity. EEND-DEMUX can directly obtain separated speaker embeddings through the demultiplexing operation in the inference phase without an external speaker diarization system, an embedding extractor, or a heuristic decoding technique. Furthermore, we employ a multi-head cross-attention mechanism to capture the correlation between mixture and separated speaker embeddings effectively. We formulate three loss functions based on matching, orthogonality, and sparsity constraints to learn robust demultiplexed speaker embeddings. The experimental results on the LibriMix dataset show consistently improved performance in both a fixed and flexible number of speakers scenarios.

{{</citation>}}


## eess.SY (1)



### (159/161) Robust and Decentralized Reinforcement Learning for UAV Path Planning in IoT Networks (Xueyuan Wang et al., 2023)

{{<citation>}}

Xueyuan Wang, M. Cenk Gursoy. (2023)  
**Robust and Decentralized Reinforcement Learning for UAV Path Planning in IoT Networks**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.06250v1)  

---


**ABSTRACT**  
Unmanned aerial vehicle (UAV)-based networks and Internet of Things (IoT) are being considered as integral components of current and next-generation wireless networks.   In particular, UAVs can provide IoT devices with seamless connectivity and high coverage and this can be accomplished with effective UAV path planning.   In this article, we study robust and decentralized UAV path planning for data collection in IoT networks in the presence of other noncooperative UAVs and adversarial jamming attacks. We address three different practical scenarios, including single UAV path planning, UAV swarm path planning, and single UAV path planning in the presence of an intelligent mobile UAV jammer. We advocate a reinforcement learning framework for UAV path planning in these three scenarios under practical constraints. The simulation results demonstrate that with learning-based path planning, the UAVs can complete their missions with high success rates and data collection rates. In addition, the UAVs can adapt and execute different trajectories as a defensive measure against the intelligent jammer.

{{</citation>}}


## quant-ph (1)



### (160/161) Improvement in Variational Quantum Algorithms by Measurement Simplification (Jaehoon Hahm et al., 2023)

{{<citation>}}

Jaehoon Hahm, Hayeon Kim, Young June Park. (2023)  
**Improvement in Variational Quantum Algorithms by Measurement Simplification**  

---
Primary Category: quant-ph  
Categories: cs-AI, quant-ph, quant-ph  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.06176v1)  

---


**ABSTRACT**  
Variational Quantum Algorithms (VQAs) are expected to be promising algorithms with quantum advantages that can be run at quantum computers in the close future. In this work, we review simple rules in basic quantum circuits, and propose a simplification method, Measurement Simplification, that simplifies the expression for the measurement of quantum circuit. By the Measurement Simplification, we simplified the specific result expression of VQAs and obtained large improvements in calculation time and required memory size. Here we applied Measurement Simplification to Variational Quantum Linear Solver (VQLS), Variational Quantum Eigensolver (VQE) and other Quantum Machine Learning Algorithms to show an example of speedup in the calculation time and required memory size.

{{</citation>}}


## cs.LO (1)



### (161/161) A Practical Formalization of Monadic Equational Reasoning in Dependent-type Theory (Reynald Affeldt et al., 2023)

{{<citation>}}

Reynald Affeldt, Jacques Garrigue, Takafumi Saikawa. (2023)  
**A Practical Formalization of Monadic Equational Reasoning in Dependent-type Theory**  

---
Primary Category: cs.LO  
Categories: cs-LO, cs.LO  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2312.06103v1)  

---


**ABSTRACT**  
One can perform equational reasoning about computational effects with a purely functional programming language thanks to monads. Even though equational reasoning for effectful programs is desirable, it is not yet mainstream. This is partly because it is difficult to maintain pencil-and-paper proofs of large examples. We propose a formalization of a hierarchy of effects using monads in the Coq proof assistant that makes monadic equational reasoning practical. Our main idea is to formalize the hierarchy of effects and algebraic laws as interfaces like it is done when formalizing hierarchy of algebras in dependent type theory. Thanks to this approach, we clearly separate equational laws from models. We can then take advantage of the sophisticated rewriting capabilities of Coq and build libraries of lemmas to achieve concise proofs of programs. We can also use the resulting framework to leverage on Coq's mathematical theories and formalize models of monads. In this article, we explain how we formalize a rich hierarchy of effects (nondeterminism, state, probability, etc.), how we mechanize examples of monadic equational reasoning from the literature, and how we apply our framework to the design of equational laws for a subset of ML with references.

{{</citation>}}
