---
draft: false
title: "arXiv @ 2023.08.01"
date: 2023-08-01
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.08.01"
    identifier: arxiv_20230801
    parent: 202308_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.LG (11)](#cslg-11)
- [cs.CL (12)](#cscl-12)
- [cs.CY (1)](#cscy-1)
- [quant-ph (1)](#quant-ph-1)
- [cs.CR (1)](#cscr-1)
- [physics.flu-dyn (1)](#physicsflu-dyn-1)
- [cs.CV (10)](#cscv-10)
- [eess.IV (4)](#eessiv-4)
- [cs.AI (3)](#csai-3)
- [cs.IR (1)](#csir-1)
- [cs.DB (1)](#csdb-1)
- [cs.RO (3)](#csro-3)
- [cs.NE (2)](#csne-2)
- [cs.MA (2)](#csma-2)
- [eess.SY (1)](#eesssy-1)
- [cs.SD (1)](#cssd-1)
- [cs.HC (3)](#cshc-3)

## cs.LG (11)



### (1/58) Rating-based Reinforcement Learning (Devin White et al., 2023)

{{<citation>}}

Devin White, Mingkang Wu, Ellen Novoseller, Vernon Lawhern, Nick Waytowich, Yongcan Cao. (2023)  
**Rating-based Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-RO, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16348v1)  

---


**ABSTRACT**  
This paper develops a novel rating-based reinforcement learning approach that uses human ratings to obtain human guidance in reinforcement learning. Different from the existing preference-based and ranking-based reinforcement learning paradigms, based on human relative preferences over sample pairs, the proposed rating-based reinforcement learning approach is based on human evaluation of individual trajectories without relative comparisons between sample pairs. The rating-based reinforcement learning approach builds on a new prediction model for human ratings and a novel multi-class loss function. We conduct several experimental studies based on synthetic ratings and real human ratings to evaluate the effectiveness and benefits of the new rating-based reinforcement learning approach.

{{</citation>}}


### (2/58) Predicting delays in Indian lower courts using AutoML and Decision Forests (Mohit Bhatnagar et al., 2023)

{{<citation>}}

Mohit Bhatnagar, Shivraj Huchhanavar. (2023)  
**Predicting delays in Indian lower courts using AutoML and Decision Forests**  

---
Primary Category: cs.LG  
Categories: I-2-1, cs-AI, cs-CY, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16285v1)  

---


**ABSTRACT**  
This paper presents a classification model that predicts delays in Indian lower courts based on case information available at filing. The model is built on a dataset of 4.2 million court cases filed in 2010 and their outcomes over a 10-year period. The data set is drawn from 7000+ lower courts in India. The authors employed AutoML to develop a multi-class classification model over all periods of pendency and then used binary decision forest classifiers to improve predictive accuracy for the classification of delays. The best model achieved an accuracy of 81.4%, and the precision, recall, and F1 were found to be 0.81. The study demonstrates the feasibility of AI models for predicting delays in Indian courts, based on relevant data points such as jurisdiction, court, judge, subject, and the parties involved. The paper also discusses the results in light of relevant literature and suggests areas for improvement and future research. The authors have made the dataset and Python code files used for the analysis available for further research in the crucial and contemporary field of Indian judicial reform.

{{</citation>}}


### (3/58) zkDL: Efficient Zero-Knowledge Proofs of Deep Learning Training (Haochen Sun et al., 2023)

{{<citation>}}

Haochen Sun, Hongyang Zhang. (2023)  
**zkDL: Efficient Zero-Knowledge Proofs of Deep Learning Training**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16273v1)  

---


**ABSTRACT**  
The recent advancements in deep learning have brought about significant changes in various aspects of people's lives. Meanwhile, these rapid developments have raised concerns about the legitimacy of the training process of deep networks. However, to protect the intellectual properties of untrusted AI developers, directly examining the training process by accessing the model parameters and training data by verifiers is often prohibited.   In response to this challenge, we present zkDL, an efficient zero-knowledge proof of deep learning training. At the core of zkDL is zkReLU, a specialized zero-knowledge proof protocol with optimized proving time and proof size for the ReLU activation function, a major obstacle in verifiable training due to its non-arithmetic nature. To integrate zkReLU into the proof system for the entire training process, we devise a novel construction of an arithmetic circuit from neural networks. By leveraging the abundant parallel computation resources, this construction reduces proving time and proof sizes by a factor of the network depth. As a result, zkDL enables the generation of complete and sound proofs, taking less than a minute with a size of less than 20 kB per training step, for a 16-layer neural network with 200M parameters, while ensuring the privacy of data and model parameters.

{{</citation>}}


### (4/58) DRL4Route: A Deep Reinforcement Learning Framework for Pick-up and Delivery Route Prediction (Xiaowei Mao et al., 2023)

{{<citation>}}

Xiaowei Mao, Haomin Wen, Hengrui Zhang, Huaiyu Wan, Lixia Wu, Jianbin Zheng, Haoyuan Hu, Youfang Lin. (2023)  
**DRL4Route: A Deep Reinforcement Learning Framework for Pick-up and Delivery Route Prediction**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16246v1)  

---


**ABSTRACT**  
Pick-up and Delivery Route Prediction (PDRP), which aims to estimate the future service route of a worker given his current task pool, has received rising attention in recent years. Deep neural networks based on supervised learning have emerged as the dominant model for the task because of their powerful ability to capture workers' behavior patterns from massive historical data. Though promising, they fail to introduce the non-differentiable test criteria into the training process, leading to a mismatch in training and test criteria. Which considerably trims down their performance when applied in practical systems. To tackle the above issue, we present the first attempt to generalize Reinforcement Learning (RL) to the route prediction task, leading to a novel RL-based framework called DRL4Route. It combines the behavior-learning abilities of previous deep learning models with the non-differentiable objective optimization ability of reinforcement learning. DRL4Route can serve as a plug-and-play component to boost the existing deep learning models. Based on the framework, we further implement a model named DRL4Route-GAE for PDRP in logistic service. It follows the actor-critic architecture which is equipped with a Generalized Advantage Estimator that can balance the bias and variance of the policy gradient estimates, thus achieving a more optimal policy. Extensive offline experiments and the online deployment show that DRL4Route-GAE improves Location Square Deviation (LSD) by 0.9%-2.7%, and Accuracy@3 (ACC@3) by 2.4%-3.2% over existing methods on the real-world dataset.

{{</citation>}}


### (5/58) Text Analysis Using Deep Neural Networks in Digital Humanities and Information Science (Omri Suissa et al., 2023)

{{<citation>}}

Omri Suissa, Avshalom Elmalech, Maayan Zhitomirsky-Geffet. (2023)  
**Text Analysis Using Deep Neural Networks in Digital Humanities and Information Science**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CL, cs-LG, cs.LG  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2307.16217v1)  

---


**ABSTRACT**  
Combining computational technologies and humanities is an ongoing effort aimed at making resources such as texts, images, audio, video, and other artifacts digitally available, searchable, and analyzable. In recent years, deep neural networks (DNN) dominate the field of automatic text analysis and natural language processing (NLP), in some cases presenting a super-human performance. DNNs are the state-of-the-art machine learning algorithms solving many NLP tasks that are relevant for Digital Humanities (DH) research, such as spell checking, language detection, entity extraction, author detection, question answering, and other tasks. These supervised algorithms learn patterns from a large number of "right" and "wrong" examples and apply them to new examples. However, using DNNs for analyzing the text resources in DH research presents two main challenges: (un)availability of training data and a need for domain adaptation. This paper explores these challenges by analyzing multiple use-cases of DH studies in recent literature and their possible solutions and lays out a practical decision model for DH experts for when and how to choose the appropriate deep learning approaches for their research. Moreover, in this paper, we aim to raise awareness of the benefits of utilizing deep learning models in the DH community.

{{</citation>}}


### (6/58) Robust Multi-Agent Reinforcement Learning with State Uncertainty (Sihong He et al., 2023)

{{<citation>}}

Sihong He, Songyang Han, Sanbao Su, Shuo Han, Shaofeng Zou, Fei Miao. (2023)  
**Robust Multi-Agent Reinforcement Learning with State Uncertainty**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-GT, cs-LG, cs-MA, cs-SY, cs.LG, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16212v1)  

---


**ABSTRACT**  
In real-world multi-agent reinforcement learning (MARL) applications, agents may not have perfect state information (e.g., due to inaccurate measurement or malicious attacks), which challenges the robustness of agents' policies. Though robustness is getting important in MARL deployment, little prior work has studied state uncertainties in MARL, neither in problem formulation nor algorithm design. Motivated by this robustness issue and the lack of corresponding studies, we study the problem of MARL with state uncertainty in this work. We provide the first attempt to the theoretical and empirical analysis of this challenging problem. We first model the problem as a Markov Game with state perturbation adversaries (MG-SPA) by introducing a set of state perturbation adversaries into a Markov Game. We then introduce robust equilibrium (RE) as the solution concept of an MG-SPA. We conduct a fundamental analysis regarding MG-SPA such as giving conditions under which such a robust equilibrium exists. Then we propose a robust multi-agent Q-learning (RMAQ) algorithm to find such an equilibrium, with convergence guarantees. To handle high-dimensional state-action space, we design a robust multi-agent actor-critic (RMAAC) algorithm based on an analytical expression of the policy gradient derived in the paper. Our experiments show that the proposed RMAQ algorithm converges to the optimal value function; our RMAAC algorithm outperforms several MARL and robust MARL methods in multiple multi-agent environments when state uncertainty is present. The source code is public on \url{https://github.com/sihongho/robust_marl_with_state_uncertainty}.

{{</citation>}}


### (7/58) Shuffled Differentially Private Federated Learning for Time Series Data Analytics (Chenxi Huang et al., 2023)

{{<citation>}}

Chenxi Huang, Chaoyang Jiang, Zhenghua Chen. (2023)  
**Shuffled Differentially Private Federated Learning for Time Series Data Analytics**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2307.16196v1)  

---


**ABSTRACT**  
Trustworthy federated learning aims to achieve optimal performance while ensuring clients' privacy. Existing privacy-preserving federated learning approaches are mostly tailored for image data, lacking applications for time series data, which have many important applications, like machine health monitoring, human activity recognition, etc. Furthermore, protective noising on a time series data analytics model can significantly interfere with temporal-dependent learning, leading to a greater decline in accuracy. To address these issues, we develop a privacy-preserving federated learning algorithm for time series data. Specifically, we employ local differential privacy to extend the privacy protection trust boundary to the clients. We also incorporate shuffle techniques to achieve a privacy amplification, mitigating the accuracy decline caused by leveraging local differential privacy. Extensive experiments were conducted on five time series datasets. The evaluation results reveal that our algorithm experienced minimal accuracy loss compared to non-private federated learning in both small and large client scenarios. Under the same level of privacy protection, our algorithm demonstrated improved accuracy compared to the centralized differentially private federated learning in both scenarios.

{{</citation>}}


### (8/58) Variance Control for Distributional Reinforcement Learning (Qi Kuang et al., 2023)

{{<citation>}}

Qi Kuang, Zhoufan Zhu, Liwen Zhang, Fan Zhou. (2023)  
**Variance Control for Distributional Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16152v1)  

---


**ABSTRACT**  
Although distributional reinforcement learning (DRL) has been widely examined in the past few years, very few studies investigate the validity of the obtained Q-function estimator in the distributional setting. To fully understand how the approximation errors of the Q-function affect the whole training process, we do some error analysis and theoretically show how to reduce both the bias and the variance of the error terms. With this new understanding, we construct a new estimator \emph{Quantiled Expansion Mean} (QEM) and introduce a new DRL algorithm (QEMRL) from the statistical perspective. We extensively evaluate our QEMRL algorithm on a variety of Atari and Mujoco benchmark tasks and demonstrate that QEMRL achieves significant improvement over baseline algorithms in terms of sample efficiency and convergence performance.

{{</citation>}}


### (9/58) An Effective LSTM-DDPM Scheme for Energy Theft Detection and Forecasting in Smart Grid (Xun Yuan et al., 2023)

{{<citation>}}

Xun Yuan, Yang Yang, Arwa Alromih, Prosanta Gope, Biplab Sikdar. (2023)  
**An Effective LSTM-DDPM Scheme for Energy Theft Detection and Forecasting in Smart Grid**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CR, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2307.16149v2)  

---


**ABSTRACT**  
Energy theft detection (ETD) and energy consumption forecasting (ECF) are two interconnected challenges in smart grid systems. Addressing these issues collectively is crucial for ensuring system security. This paper addresses the interconnected challenges of ETD and ECF in smart grid systems. The proposed solution combines long short-term memory (LSTM) and a denoising diffusion probabilistic model (DDPM) to generate input reconstruction and forecasting. By leveraging the reconstruction and forecasting errors, the system identifies instances of energy theft, with the methods based on reconstruction error and forecasting error complementing each other in detecting different types of attacks. Through extensive experiments on real-world and synthetic datasets, the proposed scheme outperforms baseline methods in ETD and ECF problems. The ensemble method significantly enhances ETD performance, accurately detecting energy theft attacks that baseline methods fail to detect. The research offers a comprehensive and effective solution for addressing ETD and ECF challenges, demonstrating promising results and improved security in smart grid systems.

{{</citation>}}


### (10/58) Deep Unrolling Networks with Recurrent Momentum Acceleration for Nonlinear Inverse Problems (Qingping Zhou et al., 2023)

{{<citation>}}

Qingping Zhou, Jiayu Qian, Junqi Tang, Jinglai Li. (2023)  
**Deep Unrolling Networks with Recurrent Momentum Acceleration for Nonlinear Inverse Problems**  

---
Primary Category: cs.LG  
Categories: 68U10, 94A08, 68T99, cs-LG, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2307.16120v1)  

---


**ABSTRACT**  
Combining the strengths of model-based iterative algorithms and data-driven deep learning solutions, deep unrolling networks (DuNets) have become a popular tool to solve inverse imaging problems. While DuNets have been successfully applied to many linear inverse problems, nonlinear problems tend to impair the performance of the method. Inspired by momentum acceleration techniques that are often used in optimization algorithms, we propose a recurrent momentum acceleration (RMA) framework that uses a long short-term memory recurrent neural network (LSTM-RNN) to simulate the momentum acceleration process. The RMA module leverages the ability of the LSTM-RNN to learn and retain knowledge from the previous gradients. We apply RMA to two popular DuNets -- the learned proximal gradient descent (LPGD) and the learned primal-dual (LPD) methods, resulting in LPGD-RMA and LPD-RMA respectively. We provide experimental results on two nonlinear inverse problems: a nonlinear deconvolution problem, and an electrical impedance tomography problem with limited boundary measurements. In the first experiment we have observed that the improvement due to RMA largely increases with respect to the nonlinearity of the problem. The results of the second example further demonstrate that the RMA schemes can significantly improve the performance of DuNets in strongly ill-posed problems.

{{</citation>}}


### (11/58) AI Increases Global Access to Reliable Flood Forecasts (Grey Nearing et al., 2023)

{{<citation>}}

Grey Nearing, Deborah Cohen, Vusumuzi Dube, Martin Gauch, Oren Gilon, Shaun Harrigan, Avinatan Hassidim, Frederik Kratzert, Asher Metzger, Sella Nevo, Florian Pappenberger, Christel Prudhomme, Guy Shalev, Shlomo Shenzis, Tadele Tekalign, Dana Weitzner, Yoss Matias. (2023)  
**AI Increases Global Access to Reliable Flood Forecasts**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG, physics-soc-ph  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16104v1)  

---


**ABSTRACT**  
Floods are one of the most common and impactful natural disasters, with a disproportionate impact in developing countries that often lack dense streamflow monitoring networks. Accurate and timely warnings are critical for mitigating flood risks, but accurate hydrological simulation models typically must be calibrated to long data records in each watershed where they are applied. We developed an Artificial Intelligence (AI) model to predict extreme hydrological events at timescales up to 7 days in advance. This model significantly outperforms current state of the art global hydrology models (the Copernicus Emergency Management Service Global Flood Awareness System) across all continents, lead times, and return periods. AI is especially effective at forecasting in ungauged basins, which is important because only a few percent of the world's watersheds have stream gauges, with a disproportionate number of ungauged basins in developing countries that are especially vulnerable to the human impacts of flooding. We produce forecasts of extreme events in South America and Africa that achieve reliability approaching the current state of the art in Europe and North America, and we achieve reliability at between 4 and 6-day lead times that are similar to current state of the art nowcasts (0-day lead time). Additionally, we achieve accuracies over 10-year return period events that are similar to current accuracies over 2-year return period events, meaning that AI can provide warnings earlier and over larger and more impactful events. The model that we develop in this paper has been incorporated into an operational early warning system that produces publicly available (free and open) forecasts in real time in over 80 countries. This work using AI and open data highlights a need for increasing the availability of hydrological data to continue to improve global access to reliable flood warnings.

{{</citation>}}


## cs.CL (12)



### (12/58) Distractor generation for multiple-choice questions with predictive prompting and large language models (Semere Kiros Bitew et al., 2023)

{{<citation>}}

Semere Kiros Bitew, Johannes Deleu, Chris Develder, Thomas Demeester. (2023)  
**Distractor generation for multiple-choice questions with predictive prompting and large language models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2307.16338v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) such as ChatGPT have demonstrated remarkable performance across various tasks and have garnered significant attention from both researchers and practitioners. However, in an educational context, we still observe a performance gap in generating distractors -- i.e., plausible yet incorrect answers -- with LLMs for multiple-choice questions (MCQs). In this study, we propose a strategy for guiding LLMs such as ChatGPT, in generating relevant distractors by prompting them with question items automatically retrieved from a question bank as well-chosen in-context examples. We evaluate our LLM-based solutions using a quantitative assessment on an existing test set, as well as through quality annotations by human experts, i.e., teachers. We found that on average 53% of the generated distractors presented to the teachers were rated as high-quality, i.e., suitable for immediate use as is, outperforming the state-of-the-art model. We also show the gains of our approach 1 in generating high-quality distractors by comparing it with a zero-shot ChatGPT and a few-shot ChatGPT prompted with static examples.

{{</citation>}}


### (13/58) LaFiCMIL: Rethinking Large File Classification from the Perspective of Correlated Multiple Instance Learning (Tiezhu Sun et al., 2023)

{{<citation>}}

Tiezhu Sun, Weiguo Pian, Nadia Daoudi, Kevin Allix, Tegawendé F. Bissyandé, Jacques Klein. (2023)  
**LaFiCMIL: Rethinking Large File Classification from the Perspective of Correlated Multiple Instance Learning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: BERT, Natural Language Processing, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2308.01413v1)  

---


**ABSTRACT**  
Transformer-based models have revolutionized the performance of a wide range of language tasks. Intuitively, one might expect text classification, which does not necessitate as many high-level representations as generative tasks, to be comprehensively addressed with the powerful representation capabilities of Transformers. However, in reality, there remains significant potential for enhancement, particularly in the areas of multi-class and multi-label classification of lengthy textual documents and other large files. The performance of Transformer-based models is mainly hindered by a major limitation: a restricted input length, e.g., 512 tokens for BERT. While an increase in GPU memory can marginally extend this limit, practical real-world applications often operate under constrained GPU resources. In this work, we tackle the input limit problem from the perspective of correlated multiple instance learning. The proposed approach, LaFiCMIL, serves as a versatile framework applicable to various large file classification tasks covering binary, multi-class, and multi-label classification tasks, spanning various domains including Natural Language Processing, Programming Language Processing, and Android Analysis. To evaluate its effectiveness, we employ eight benchmark datasets pertaining to Long Document Classification, Code Defect Detection, and Android Malware Detection. Leveraging BERT-family models as feature extractors, our experimental results demonstrate that LaFiCMIL achieves new state-of-the-art performance across all benchmark datasets. This is largely attributable to its capability of scaling BERT up to nearly 20K tokens, running on a single Tesla V-100 GPU with 32G of memory.

{{</citation>}}


### (14/58) Recent Advances in Hierarchical Multi-label Text Classification: A Survey (Rundong Liu et al., 2023)

{{<citation>}}

Rundong Liu, Wenhan Liang, Weijun Luo, Yuxiang Song, He Zhang, Ruohua Xu, Yunfeng Li, Ming Liu. (2023)  
**Recent Advances in Hierarchical Multi-label Text Classification: A Survey**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Text Classification  
[Paper Link](http://arxiv.org/abs/2307.16265v1)  

---


**ABSTRACT**  
Hierarchical multi-label text classification aims to classify the input text into multiple labels, among which the labels are structured and hierarchical. It is a vital task in many real world applications, e.g. scientific literature archiving. In this paper, we survey the recent progress of hierarchical multi-label text classification, including the open sourced data sets, the main methods, evaluation metrics, learning strategies and the current challenges. A few future research directions are also listed for community to further improve this field.

{{</citation>}}


### (15/58) A Private Watermark for Large Language Models (Aiwei Liu et al., 2023)

{{<citation>}}

Aiwei Liu, Leyi Pan, Xuming Hu, Shu'ang Li, Lijie Wen, Irwin King, Philip S. Yu. (2023)  
**A Private Watermark for Large Language Models**  

---
Primary Category: cs.CL  
Categories: 68T50, I-2-7, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2307.16230v2)  

---


**ABSTRACT**  
Recently, text watermarking algorithms for large language models (LLMs) have been mitigating the potential harms of text generated by the LLMs, including fake news and copyright issues. However, the watermark detection of current text algorithms requires the key from the generation process, making them susceptible to breaches and counterfeiting. In this work, we propose the first private watermarking algorithm, which extends the current text watermarking algorithms by using two different neural networks respectively for watermark generation and detection, rather than using the same key at both stages. Meanwhile, part of the parameters of the watermark generation and detection networks are shared, which makes the detection network achieve a high accuracy very efficiently. Experiments show that our algorithm ensures high detection accuracy with minimal impact on generation and detection speed, due to the small parameter size of both networks. Additionally, our subsequent analysis demonstrates the difficulty of reverting the watermark generation rules from the detection network.

{{</citation>}}


### (16/58) Optimizing the Neural Network Training for OCR Error Correction of Historical Hebrew Texts (Omri Suissa et al., 2023)

{{<citation>}}

Omri Suissa, Avshalom Elmalech, Maayan Zhitomirsky-Geffet. (2023)  
**Optimizing the Neural Network Training for OCR Error Correction of Historical Hebrew Texts**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: OCR  
[Paper Link](http://arxiv.org/abs/2307.16220v1)  

---


**ABSTRACT**  
Over the past few decades, large archives of paper-based documents such as books and newspapers have been digitized using Optical Character Recognition. This technology is error-prone, especially for historical documents. To correct OCR errors, post-processing algorithms have been proposed based on natural language analysis and machine learning techniques such as neural networks. Neural network's disadvantage is the vast amount of manually labeled data required for training, which is often unavailable. This paper proposes an innovative method for training a light-weight neural network for Hebrew OCR post-correction using significantly less manually created data. The main research goal is to develop a method for automatically generating language and task-specific training data to improve the neural network results for OCR post-correction, and to investigate which type of dataset is the most effective for OCR post-correction of historical documents. To this end, a series of experiments using several datasets was conducted. The evaluation corpus was based on Hebrew newspapers from the JPress project. An analysis of historical OCRed newspapers was done to learn common language and corpus-specific OCR errors. We found that training the network using the proposed method is more effective than using randomly generated errors. The results also show that the performance of the neural network for OCR post-correction strongly depends on the genre and area of the training data. Moreover, neural networks that were trained with the proposed method outperform other state-of-the-art neural networks for OCR post-correction and complex spellcheckers. These results may have practical implications for many digital humanities projects.

{{</citation>}}


### (17/58) Question Answering with Deep Neural Networks for Semi-Structured Heterogeneous Genealogical Knowledge Graphs (Omri Suissa et al., 2023)

{{<citation>}}

Omri Suissa, Maayan Zhitomirsky-Geffet, Avshalom Elmalech. (2023)  
**Question Answering with Deep Neural Networks for Semi-Structured Heterogeneous Genealogical Knowledge Graphs**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: BERT, Knowledge Graph, Question Answering  
[Paper Link](http://arxiv.org/abs/2307.16214v1)  

---


**ABSTRACT**  
With the rising popularity of user-generated genealogical family trees, new genealogical information systems have been developed. State-of-the-art natural question answering algorithms use deep neural network (DNN) architecture based on self-attention networks. However, some of these models use sequence-based inputs and are not suitable to work with graph-based structure, while graph-based DNN models rely on high levels of comprehensiveness of knowledge graphs that is nonexistent in the genealogical domain. Moreover, these supervised DNN models require training datasets that are absent in the genealogical domain. This study proposes an end-to-end approach for question answering using genealogical family trees by: 1) representing genealogical data as knowledge graphs, 2) converting them to texts, 3) combining them with unstructured texts, and 4) training a trans-former-based question answering model. To evaluate the need for a dedicated approach, a comparison between the fine-tuned model (Uncle-BERT) trained on the auto-generated genealogical dataset and state-of-the-art question-answering models was per-formed. The findings indicate that there are significant differences between answering genealogical questions and open-domain questions. Moreover, the proposed methodology reduces complexity while increasing accuracy and may have practical implications for genealogical research and real-world projects, making genealogical data accessible to experts as well as the general public.

{{</citation>}}


### (18/58) Toward a Period-Specific Optimized Neural Network for OCR Error Correction of Historical Hebrew Texts (Omri Suissa et al., 2023)

{{<citation>}}

Omri Suissa, Maayan Zhitomirsky-Geffet, Avshalom Elmalech. (2023)  
**Toward a Period-Specific Optimized Neural Network for OCR Error Correction of Historical Hebrew Texts**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: OCR  
[Paper Link](http://arxiv.org/abs/2307.16213v1)  

---


**ABSTRACT**  
Over the past few decades, large archives of paper-based historical documents, such as books and newspapers, have been digitized using the Optical Character Recognition (OCR) technology. Unfortunately, this broadly used technology is error-prone, especially when an OCRed document was written hundreds of years ago. Neural networks have shown great success in solving various text processing tasks, including OCR post-correction. The main disadvantage of using neural networks for historical corpora is the lack of sufficiently large training datasets they require to learn from, especially for morphologically-rich languages like Hebrew. Moreover, it is not clear what are the optimal structure and values of hyperparameters (predefined parameters) of neural networks for OCR error correction in Hebrew due to its unique features. Furthermore, languages change across genres and periods. These changes may affect the accuracy of OCR post-correction neural network models. To overcome these challenges, we developed a new multi-phase method for generating artificial training datasets with OCR errors and hyperparameters optimization for building an effective neural network for OCR post-correction in Hebrew.

{{</citation>}}


### (19/58) Around the GLOBE: Numerical Aggregation Question-Answering on Heterogeneous Genealogical Knowledge Graphs with Deep Neural Networks (Omri Suissa et al., 2023)

{{<citation>}}

Omri Suissa, Maayan Zhitomirsky-Geffet, Avshalom Elmalech. (2023)  
**Around the GLOBE: Numerical Aggregation Question-Answering on Heterogeneous Genealogical Knowledge Graphs with Deep Neural Networks**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-IR, cs-LG, cs.CL  
Keywords: AI, Knowledge Graph, QA  
[Paper Link](http://arxiv.org/abs/2307.16208v1)  

---


**ABSTRACT**  
One of the key AI tools for textual corpora exploration is natural language question-answering (QA). Unlike keyword-based search engines, QA algorithms receive and process natural language questions and produce precise answers to these questions, rather than long lists of documents that need to be manually scanned by the users. State-of-the-art QA algorithms based on DNNs were successfully employed in various domains. However, QA in the genealogical domain is still underexplored, while researchers in this field (and other fields in humanities and social sciences) can highly benefit from the ability to ask questions in natural language, receive concrete answers and gain insights hidden within large corpora. While some research has been recently conducted for factual QA in the genealogical domain, to the best of our knowledge, there is no previous research on the more challenging task of numerical aggregation QA (i.e., answering questions combining aggregation functions, e.g., count, average, max). Numerical aggregation QA is critical for distant reading and analysis for researchers (and the general public) interested in investigating cultural heritage domains. Therefore, in this study, we present a new end-to-end methodology for numerical aggregation QA for genealogical trees that includes: 1) an automatic method for training dataset generation; 2) a transformer-based table selection method, and 3) an optimized transformer-based numerical aggregation QA model. The findings indicate that the proposed architecture, GLOBE, outperforms the state-of-the-art models and pipelines by achieving 87% accuracy for this task compared to only 21% by current state-of-the-art models. This study may have practical implications for genealogical information centers and museums, making genealogical data research easy and scalable for experts as well as the general public.

{{</citation>}}


### (20/58) A Knowledge-enhanced Two-stage Generative Framework for Medical Dialogue Information Extraction (Zefa Hu et al., 2023)

{{<citation>}}

Zefa Hu, Ziyi Ni, Jing Shi, Shuang Xu, Bo Xu. (2023)  
**A Knowledge-enhanced Two-stage Generative Framework for Medical Dialogue Information Extraction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue, Information Extraction  
[Paper Link](http://arxiv.org/abs/2307.16200v1)  

---


**ABSTRACT**  
This paper focuses on term-status pair extraction from medical dialogues (MD-TSPE), which is essential in diagnosis dialogue systems and the automatic scribe of electronic medical records (EMRs). In the past few years, works on MD-TSPE have attracted increasing research attention, especially after the remarkable progress made by generative methods. However, these generative methods output a whole sequence consisting of term-status pairs in one stage and ignore integrating prior knowledge, which demands a deeper understanding to model the relationship between terms and infer the status of each term. This paper presents a knowledge-enhanced two-stage generative framework (KTGF) to address the above challenges. Using task-specific prompts, we employ a single model to complete the MD-TSPE through two phases in a unified generative form: we generate all terms the first and then generate the status of each generated term. In this way, the relationship between terms can be learned more effectively from the sequence containing only terms in the first phase, and our designed knowledge-enhanced prompt in the second phase can leverage the category and status candidates of the generated term for status generation. Furthermore, our proposed special status ``not mentioned" makes more terms available and enriches the training data in the second phase, which is critical in the low-resource setting. The experiments on the Chunyu and CMDD datasets show that the proposed method achieves superior results compared to the state-of-the-art models in the full training and low-resource settings.

{{</citation>}}


### (21/58) Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models (Keyu Pan et al., 2023)

{{<citation>}}

Keyu Pan, Yawen Zeng. (2023)  
**Do LLMs Possess a Personality? Making the MBTI Test an Amazing Evaluation for Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2307.16180v1)  

---


**ABSTRACT**  
The field of large language models (LLMs) has made significant progress, and their knowledge storage capacity is approaching that of human beings. Furthermore, advanced techniques, such as prompt learning and reinforcement learning, are being employed to address ethical concerns and hallucination problems associated with LLMs, bringing them closer to aligning with human values. This situation naturally raises the question of whether LLMs with human-like abilities possess a human-like personality? In this paper, we aim to investigate the feasibility of using the Myers-Briggs Type Indicator (MBTI), a widespread human personality assessment tool, as an evaluation metric for LLMs. Specifically, extensive experiments will be conducted to explore: 1) the personality types of different LLMs, 2) the possibility of changing the personality types by prompt engineering, and 3) How does the training dataset affect the model's personality. Although the MBTI is not a rigorous assessment, it can still reflect the similarity between LLMs and human personality. In practice, the MBTI has the potential to serve as a rough indicator. Our codes are available at https://github.com/HarderThenHarder/transformers_tasks/tree/main/LLM/llms_mbti.

{{</citation>}}


### (22/58) User-Controlled Knowledge Fusion in Large Language Models: Balancing Creativity and Hallucination (Chen Zhang, 2023)

{{<citation>}}

Chen Zhang. (2023)  
**User-Controlled Knowledge Fusion in Large Language Models: Balancing Creativity and Hallucination**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs-LG, cs.CL  
Keywords: BERT, Language Model  
[Paper Link](http://arxiv.org/abs/2307.16139v1)  

---


**ABSTRACT**  
In modern dialogue systems, the use of Large Language Models (LLMs) has grown exponentially due to their capacity to generate diverse, relevant, and creative responses. Despite their strengths, striking a balance between the LLMs' creativity and their faithfulness to external knowledge remains a key challenge. This paper presents an innovative user-controllable mechanism that modulates the balance between an LLM's imaginative capabilities and its adherence to factual information. Our approach incorporates a numerical tag during the fine-tuning phase of the LLM's training, representing the degree of faithfulness to the reference knowledge in the generated responses. This degree is computed through an automated process that measures lexical overlap using ROUGE scores, semantic similarity using Sentence-BERT embeddings, and an LLM's self-evaluation score. During model inference, users can manipulate this numerical tag, thus controlling the degree of the LLM's reliance on external knowledge. We conduct extensive experiments across various scenarios, demonstrating the adaptability of our method and its efficacy in ensuring the quality and accuracy of the LLM's responses. The results highlight the potential of our approach to enhance the versatility of LLMs while maintaining a balance between creativity and hallucination.

{{</citation>}}


### (23/58) SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension (Bohao Li et al., 2023)

{{<citation>}}

Bohao Li, Rui Wang, Guangzhi Wang, Yuying Ge, Yixiao Ge, Ying Shan. (2023)  
**SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CV, cs.CL  
Keywords: GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2307.16125v2)  

---


**ABSTRACT**  
Based on powerful Large Language Models (LLMs), recent generative Multimodal Large Language Models (MLLMs) have gained prominence as a pivotal research area, exhibiting remarkable capability for both comprehension and generation. In this work, we address the evaluation of generative comprehension in MLLMs as a preliminary step towards a comprehensive assessment of generative models, by introducing a benchmark named SEED-Bench. SEED-Bench consists of 19K multiple choice questions with accurate human annotations (x 6 larger than existing benchmarks), which spans 12 evaluation dimensions including the comprehension of both the image and video modality. We develop an advanced pipeline for generating multiple-choice questions that target specific evaluation dimensions, integrating both automatic filtering and manual verification processes. Multiple-choice questions with groundtruth options derived from human annotation enables an objective and efficient assessment of model performance, eliminating the need for human or GPT intervention during evaluation. We further evaluate the performance of 18 models across all 12 dimensions, covering both the spatial and temporal understanding. By revealing the limitations of existing MLLMs through evaluation results, we aim for SEED-Bench to provide insights for motivating future research. We will launch and consistently maintain a leaderboard to provide a platform for the community to assess and investigate model capability.

{{</citation>}}


## cs.CY (1)



### (24/58) Anatomy of an AI-powered malicious social botnet (Kai-Cheng Yang et al., 2023)

{{<citation>}}

Kai-Cheng Yang, Filippo Menczer. (2023)  
**Anatomy of an AI-powered malicious social botnet**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs-SI, cs.CY  
Keywords: AI, ChatGPT, GPT, Twitter  
[Paper Link](http://arxiv.org/abs/2307.16336v1)  

---


**ABSTRACT**  
Large language models (LLMs) exhibit impressive capabilities in generating realistic text across diverse subjects. Concerns have been raised that they could be utilized to produce fake content with a deceptive intention, although evidence thus far remains anecdotal. This paper presents a case study about a Twitter botnet that appears to employ ChatGPT to generate human-like content. Through heuristics, we identify 1,140 accounts and validate them via manual annotation. These accounts form a dense cluster of fake personas that exhibit similar behaviors, including posting machine-generated content and stolen images, and engage with each other through replies and retweets. ChatGPT-generated content promotes suspicious websites and spreads harmful comments. While the accounts in the AI botnet can be detected through their coordination patterns, current state-of-the-art LLM content classifiers fail to discriminate between them and human accounts in the wild. These findings highlight the threats posed by AI-enabled social bots.

{{</citation>}}


## quant-ph (1)



### (25/58) Quantum Approximate Bayesian Optimization Algorithms with Two Mixers and Uncertainty Quantification (Jungin E. Kim et al., 2023)

{{<citation>}}

Jungin E. Kim, Yan Wang. (2023)  
**Quantum Approximate Bayesian Optimization Algorithms with Two Mixers and Uncertainty Quantification**  

---
Primary Category: quant-ph  
Categories: cs-CE, quant-ph, quant-ph  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2307.16335v1)  

---


**ABSTRACT**  
The searching efficiency of the quantum approximate optimization algorithm is dependent on both the classical and quantum sides of the algorithm. Recently a quantum approximate Bayesian optimization algorithm (QABOA) that includes two mixers was developed, where surrogate-based Bayesian optimization is applied to improve the sampling efficiency of the classical optimizer. A continuous-time quantum walk mixer is used to enhance exploration, and the generalized Grover mixer is also applied to improve exploitation. In this paper, an extension of the QABOA is proposed to further improve its searching efficiency. The searching efficiency is enhanced through two aspects. First, two mixers, including one for exploration and the other for exploitation, are applied in an alternating fashion. Second, uncertainty of the quantum circuit is quantified with a new quantum Mat\'ern kernel based on the kurtosis of the basis state distribution, which increases the chance of obtaining the optimum. The proposed new two-mixer QABOAs with and without uncertainty quantification are compared with three single-mixer QABOAs on two discrete and four mixed-integer problems. The results show that the proposed two-mixer QABOA with uncertainty quantification has the best performance in efficiency and consistency for five out of the six problems. The results also show that QABOA with the generalized Grover mixer performs the best among the single-mixer algorithms, thereby demonstrating the benefit of exploitation and the importance of dynamic exploration-exploitation balance in improving searching efficiency.

{{</citation>}}


## cs.CR (1)



### (26/58) 'False negative -- that one is going to kill you': Understanding Industry Perspectives of Static Analysis based Security Testing (Amit Seal Ami et al., 2023)

{{<citation>}}

Amit Seal Ami, Kevin Moran, Denys Poshyvanyk, Adwait Nadkarni. (2023)  
**'False negative -- that one is going to kill you': Understanding Industry Perspectives of Static Analysis based Security Testing**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SE, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2307.16325v2)  

---


**ABSTRACT**  
The demand for automated security analysis techniques, such as static analysis based security testing (SAST) tools continues to increase. To develop SASTs that are effectively leveraged by developers for finding vulnerabilities, researchers and tool designers must understand how developers perceive, select, and use SASTs, what they expect from the tools, whether they know of the limitations of the tools, and how they address those limitations. This paper describes a qualitative study that explores the assumptions, expectations, beliefs, and challenges experienced by developers who use SASTs. We perform in-depth, semi-structured interviews with 20 practitioners who possess a diverse range of software development expertise, as well as a variety of unique security, product, and organizational backgrounds. We identify $17$ key findings that shed light on developer perceptions and desires related to SASTs, and also expose gaps in the status quo - challenging long-held beliefs in SAST design priorities. Finally, we provide concrete future directions for researchers and practitioners rooted in an analysis of our findings.

{{</citation>}}


## physics.flu-dyn (1)



### (27/58) RoseNNa: A performant, portable library for neural network inference with application to computational fluid dynamics (Ajay Bati et al., 2023)

{{<citation>}}

Ajay Bati, Spencer H. Bryngelson. (2023)  
**RoseNNa: A performant, portable library for neural network inference with application to computational fluid dynamics**  

---
Primary Category: physics.flu-dyn  
Categories: cs-LG, physics-flu-dyn, physics.flu-dyn  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2307.16322v1)  

---


**ABSTRACT**  
The rise of neural network-based machine learning ushered in high-level libraries, including TensorFlow and PyTorch, to support their functionality. Computational fluid dynamics (CFD) researchers have benefited from this trend and produced powerful neural networks that promise shorter simulation times. For example, multilayer perceptrons (MLPs) and Long Short Term Memory (LSTM) recurrent-based (RNN) architectures can represent sub-grid physical effects, like turbulence. Implementing neural networks in CFD solvers is challenging because the programming languages used for machine learning and CFD are mostly non-overlapping, We present the roseNNa library, which bridges the gap between neural network inference and CFD. RoseNNa is a non-invasive, lightweight (1000 lines), and performant tool for neural network inference, with focus on the smaller networks used to augment PDE solvers, like those of CFD, which are typically written in C/C++ or Fortran. RoseNNa accomplishes this by automatically converting trained models from typical neural network training packages into a high-performance Fortran library with C and Fortran APIs. This reduces the effort needed to access trained neural networks and maintains performance in the PDE solvers that CFD researchers build and rely upon. Results show that RoseNNa reliably outperforms PyTorch (Python) and libtorch (C++) on MLPs and LSTM RNNs with less than 100 hidden layers and 100 neurons per layer, even after removing the overhead cost of API calls. Speedups range from a factor of about 10 and 2 faster than these established libraries for the smaller and larger ends of the neural network size ranges tested.

{{</citation>}}


## cs.CV (10)



### (28/58) Self-Supervised Learning of Gait-Based Biomarkers (R. James Cotton et al., 2023)

{{<citation>}}

R. James Cotton, J. D. Peiffer, Kunal Shah, Allison DeLillo, Anthony Cimorelli, Shawana Anarwala, Kayan Abdou, Tasos Karakostas. (2023)  
**Self-Supervised Learning of Gait-Based Biomarkers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Self-Supervised  
[Paper Link](http://arxiv.org/abs/2307.16321v1)  

---


**ABSTRACT**  
Markerless motion capture (MMC) is revolutionizing gait analysis in clinical settings by making it more accessible, raising the question of how to extract the most clinically meaningful information from gait data. In multiple fields ranging from image processing to natural language processing, self-supervised learning (SSL) from large amounts of unannotated data produces very effective representations for downstream tasks. However, there has only been limited use of SSL to learn effective representations of gait and movement, and it has not been applied to gait analysis with MMC. One SSL objective that has not been applied to gait is contrastive learning, which finds representations that place similar samples closer together in the learned space. If the learned similarity metric captures clinically meaningful differences, this could produce a useful representation for many downstream clinical tasks. Contrastive learning can also be combined with causal masking to predict future timesteps, which is an appealing SSL objective given the dynamical nature of gait. We applied these techniques to gait analyses performed with MMC in a rehabilitation hospital from a diverse clinical population. We find that contrastive learning on unannotated gait data learns a representation that captures clinically meaningful information. We probe this learned representation using the framework of biomarkers and show it holds promise as both a diagnostic and response biomarker, by showing it can accurately classify diagnosis from gait and is responsive to inpatient therapy, respectively. We ultimately hope these learned representations will enable predictive and prognostic gait-based biomarkers that can facilitate precision rehabilitation through greater use of MMC to quantify movement in rehabilitation.

{{</citation>}}


### (29/58) Implementing Edge Based Object Detection For Microplastic Debris (Amardeep Singh et al., 2023)

{{<citation>}}

Amardeep Singh, Prof. Charles Jia, Prof. Donald Kirk. (2023)  
**Implementing Edge Based Object Detection For Microplastic Debris**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Computer Vision, Object Detection  
[Paper Link](http://arxiv.org/abs/2307.16289v1)  

---


**ABSTRACT**  
Plastic has imbibed itself as an indispensable part of our day to day activities, becoming a source of problems due to its non-biodegradable nature and cheaper production prices. With these problems, comes the challenge of mitigating and responding to the aftereffects of disposal or the lack of proper disposal which leads to waste concentrating in locations and disturbing ecosystems for both plants and animals. As plastic debris levels continue to rise with the accumulation of waste in garbage patches in landfills and more hazardously in natural water bodies, swift action is necessary to plug or cease this flow. While manual sorting operations and detection can offer a solution, they can be augmented using highly advanced computer imagery linked with robotic appendages for removing wastes. The primary application of focus in this report are the much-discussed Computer Vision and Open Vision which have gained novelty for their light dependence on internet and ability to relay information in remote areas. These applications can be applied to the creation of edge-based mobility devices that can as a counter to the growing problem of plastic debris in oceans and rivers, demanding little connectivity and still offering the same results with reasonably timed maintenance. The principal findings of this project cover the various methods that were tested and deployed to detect waste in images, as well as comparing them against different waste types. The project has been able to produce workable models that can perform on time detection of sampled images using an augmented CNN approach. Latter portions of the project have also achieved a better interpretation of the necessary preprocessing steps required to arrive at the best accuracies, including the best hardware for expanding waste detection studies to larger environments.

{{</citation>}}


### (30/58) InfoStyler: Disentanglement Information Bottleneck for Artistic Style Transfer (Yueming Lyu et al., 2023)

{{<citation>}}

Yueming Lyu, Yue Jiang, Bo Peng, Jing Dong. (2023)  
**InfoStyler: Disentanglement Information Bottleneck for Artistic Style Transfer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Style Transfer  
[Paper Link](http://arxiv.org/abs/2307.16227v1)  

---


**ABSTRACT**  
Artistic style transfer aims to transfer the style of an artwork to a photograph while maintaining its original overall content. Many prior works focus on designing various transfer modules to transfer the style statistics to the content image. Although effective, ignoring the clear disentanglement of the content features and the style features from the first beginning, they have difficulty in balancing between content preservation and style transferring. To tackle this problem, we propose a novel information disentanglement method, named InfoStyler, to capture the minimal sufficient information for both content and style representations from the pre-trained encoding network. InfoStyler formulates the disentanglement representation learning as an information compression problem by eliminating style statistics from the content image and removing the content structure from the style image. Besides, to further facilitate disentanglement learning, a cross-domain Information Bottleneck (IB) learning strategy is proposed by reconstructing the content and style domains. Extensive experiments demonstrate that our InfoStyler can synthesize high-quality stylized images while balancing content structure preservation and style pattern richness.

{{</citation>}}


### (31/58) ScribbleVC: Scribble-supervised Medical Image Segmentation with Vision-Class Embedding (Zihan Li et al., 2023)

{{<citation>}}

Zihan Li, Yuan Zheng, Xiangde Luo, Dandan Shan, Qingqi Hong. (2023)  
**ScribbleVC: Scribble-supervised Medical Image Segmentation with Vision-Class Embedding**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs.CV  
Keywords: Embedding, Transformer  
[Paper Link](http://arxiv.org/abs/2307.16226v1)  

---


**ABSTRACT**  
Medical image segmentation plays a critical role in clinical decision-making, treatment planning, and disease monitoring. However, accurate segmentation of medical images is challenging due to several factors, such as the lack of high-quality annotation, imaging noise, and anatomical differences across patients. In addition, there is still a considerable gap in performance between the existing label-efficient methods and fully-supervised methods. To address the above challenges, we propose ScribbleVC, a novel framework for scribble-supervised medical image segmentation that leverages vision and class embeddings via the multimodal information enhancement mechanism. In addition, ScribbleVC uniformly utilizes the CNN features and Transformer features to achieve better visual feature extraction. The proposed method combines a scribble-based approach with a segmentation network and a class-embedding module to produce accurate segmentation masks. We evaluate ScribbleVC on three benchmark datasets and compare it with state-of-the-art methods. The experimental results demonstrate that our method outperforms existing approaches in terms of accuracy, robustness, and efficiency. The datasets and code are released on GitHub.

{{</citation>}}


### (32/58) Open-Set Domain Adaptation with Visual-Language Foundation Models (Qing Yu et al., 2023)

{{<citation>}}

Qing Yu, Go Irie, Kiyoharu Aizawa. (2023)  
**Open-Set Domain Adaptation with Visual-Language Foundation Models**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2307.16204v1)  

---


**ABSTRACT**  
Unsupervised domain adaptation (UDA) has proven to be very effective in transferring knowledge obtained from a source domain with labeled data to a target domain with unlabeled data. Owing to the lack of labeled data in the target domain and the possible presence of unknown classes, open-set domain adaptation (ODA) has emerged as a potential solution to identify these classes during the training phase. Although existing ODA approaches aim to solve the distribution shifts between the source and target domains, most methods fine-tuned ImageNet pre-trained models on the source domain with the adaptation on the target domain. Recent visual-language foundation models (VLFM), such as Contrastive Language-Image Pre-Training (CLIP), are robust to many distribution shifts and, therefore, should substantially improve the performance of ODA. In this work, we explore generic ways to adopt CLIP, a popular VLFM, for ODA. We investigate the performance of zero-shot prediction using CLIP, and then propose an entropy optimization strategy to assist the ODA models with the outputs of CLIP. The proposed approach achieves state-of-the-art results on various benchmarks, demonstrating its effectiveness in addressing the ODA problem.

{{</citation>}}


### (33/58) Unified Model for Image, Video, Audio and Language Tasks (Mustafa Shukor et al., 2023)

{{<citation>}}

Mustafa Shukor, Corentin Dancette, Alexandre Rame, Matthieu Cord. (2023)  
**Unified Model for Image, Video, Audio and Language Tasks**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs-MM, cs-SD, cs.CV, eess-AS  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2307.16184v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have made the ambitious quest for generalist agents significantly far from being a fantasy. A key hurdle for building such general models is the diversity and heterogeneity of tasks and modalities. A promising solution is unification, allowing the support of a myriad of tasks and modalities within one unified framework. While few large models (e.g., Flamingo (Alayrac et al., 2022), trained on massive datasets, can support more than two modalities, current small to mid-scale unified models are still limited to 2 modalities, usually image-text or video-text. The question that we ask is: is it possible to build efficiently a unified model that can support all modalities? To answer this, we propose UnIVAL, a step further towards this ambitious goal. Without relying on fancy datasets sizes or models with billions of parameters, the ~ 0.25B parameter UnIVAL model goes beyond two modalities and unifies text, images, video, and audio into a single model. Our model is efficiently pretrained on many tasks, based on task balancing and multimodal curriculum learning. UnIVAL shows competitive performance to existing state-of-the-art approaches, across image and video-text tasks. The feature representations learned from image and video-text modalities, allows the model to achieve competitive performance when finetuned on audio-text tasks, despite not being pretrained on audio. Thanks to the unified model, we propose a novel study on multimodal model merging via weight interpolation of models trained on different multimodal tasks, showing their benefits in particular for out-of-distribution generalization. Finally, we motivate unification by showing the synergy between tasks. The model weights and code are released here: https://github.com/mshukor/UnIVAL.

{{</citation>}}


### (34/58) InvVis: Large-Scale Data Embedding for Invertible Visualization (Huayuan Ye et al., 2023)

{{<citation>}}

Huayuan Ye, Chenhui Li, Yang Li, Changbo Wang. (2023)  
**InvVis: Large-Scale Data Embedding for Invertible Visualization**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2307.16176v1)  

---


**ABSTRACT**  
We present InvVis, a new approach for invertible visualization, which is reconstructing or further modifying a visualization from an image. InvVis allows the embedding of a significant amount of data, such as chart data, chart information, source code, etc., into visualization images. The encoded image is perceptually indistinguishable from the original one. We propose a new method to efficiently express chart data in the form of images, enabling large-capacity data embedding. We also outline a model based on the invertible neural network to achieve high-quality data concealing and revealing. We explore and implement a variety of application scenarios of InvVis. Additionally, we conduct a series of evaluation experiments to assess our method from multiple perspectives, including data embedding quality, data restoration accuracy, data encoding capacity, etc. The result of our experiments demonstrates the great potential of InvVis in invertible visualization.

{{</citation>}}


### (35/58) StylePrompter: All Styles Need Is Attention (Chenyi Zhuang et al., 2023)

{{<citation>}}

Chenyi Zhuang, Pan Gao, Aljosa Smolic. (2023)  
**StylePrompter: All Styles Need Is Attention**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Transformer  
[Paper Link](http://arxiv.org/abs/2307.16151v1)  

---


**ABSTRACT**  
GAN inversion aims at inverting given images into corresponding latent codes for Generative Adversarial Networks (GANs), especially StyleGAN where exists a disentangled latent space that allows attribute-based image manipulation at latent level. As most inversion methods build upon Convolutional Neural Networks (CNNs), we transfer a hierarchical vision Transformer backbone innovatively to predict $\mathcal{W^+}$ latent codes at token level. We further apply a Style-driven Multi-scale Adaptive Refinement Transformer (SMART) in $\mathcal{F}$ space to refine the intermediate style features of the generator. By treating style features as queries to retrieve lost identity information from the encoder's feature maps, SMART can not only produce high-quality inverted images but also surprisingly adapt to editing tasks. We then prove that StylePrompter lies in a more disentangled $\mathcal{W^+}$ and show the controllability of SMART. Finally, quantitative and qualitative experiments demonstrate that StylePrompter can achieve desirable performance in balancing reconstruction quality and editability, and is "smart" enough to fit into most edits, outperforming other $\mathcal{F}$-involved inversion methods.

{{</citation>}}


### (36/58) Video Frame Interpolation with Flow Transformer (Pan Gao et al., 2023)

{{<citation>}}

Pan Gao, Haoyue Tian, Jie Qin. (2023)  
**Video Frame Interpolation with Flow Transformer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-MM, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2307.16144v1)  

---


**ABSTRACT**  
Video frame interpolation has been actively studied with the development of convolutional neural networks. However, due to the intrinsic limitations of kernel weight sharing in convolution, the interpolated frame generated by it may lose details. In contrast, the attention mechanism in Transformer can better distinguish the contribution of each pixel, and it can also capture long-range pixel dependencies, which provides great potential for video interpolation. Nevertheless, the original Transformer is commonly used for 2D images; how to develop a Transformer-based framework with consideration of temporal self-attention for video frame interpolation remains an open issue. In this paper, we propose Video Frame Interpolation Flow Transformer to incorporate motion dynamics from optical flows into the self-attention mechanism. Specifically, we design a Flow Transformer Block that calculates the temporal self-attention in a matched local area with the guidance of flow, making our framework suitable for interpolating frames with large motion while maintaining reasonably low complexity. In addition, we construct a multi-scale architecture to account for multi-scale motion, further improving the overall performance. Extensive experiments on three benchmarks demonstrate that the proposed method can generate interpolated frames with better visual quality than state-of-the-art methods.

{{</citation>}}


### (37/58) Uncertainty-Encoded Multi-Modal Fusion for Robust Object Detection in Autonomous Driving (Yang Lou et al., 2023)

{{<citation>}}

Yang Lou, Qun Song, Qian Xu, Rui Tan, Jianping Wang. (2023)  
**Uncertainty-Encoded Multi-Modal Fusion for Robust Object Detection in Autonomous Driving**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2307.16121v1)  

---


**ABSTRACT**  
Multi-modal fusion has shown initial promising results for object detection of autonomous driving perception. However, many existing fusion schemes do not consider the quality of each fusion input and may suffer from adverse conditions on one or more sensors. While predictive uncertainty has been applied to characterize single-modal object detection performance at run time, incorporating uncertainties into the multi-modal fusion still lacks effective solutions due primarily to the uncertainty's cross-modal incomparability and distinct sensitivities to various adverse conditions. To fill this gap, this paper proposes Uncertainty-Encoded Mixture-of-Experts (UMoE) that explicitly incorporates single-modal uncertainties into LiDAR-camera fusion. UMoE uses individual expert network to process each sensor's detection result together with encoded uncertainty. Then, the expert networks' outputs are analyzed by a gating network to determine the fusion weights. The proposed UMoE module can be integrated into any proposal fusion pipeline. Evaluation shows that UMoE achieves a maximum of 10.67%, 3.17%, and 5.40% performance gain compared with the state-of-the-art proposal-level multi-modal object detectors under extreme weather, adversarial, and blinding attack scenarios.

{{</citation>}}


## eess.IV (4)



### (38/58) Mask-guided Data Augmentation for Multiparametric MRI Generation with a Rare Hepatocellular Carcinoma (Karen Sanchez et al., 2023)

{{<citation>}}

Karen Sanchez, Carlos Hinojosa, Kevin Arias, Henry Arguello, Denis Kouame, Olivier Meyrignac, Adrian Basarab. (2023)  
**Mask-guided Data Augmentation for Multiparametric MRI Generation with a Rare Hepatocellular Carcinoma**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2307.16314v1)  

---


**ABSTRACT**  
Data augmentation is classically used to improve the overall performance of deep learning models. It is, however, challenging in the case of medical applications, and in particular for multiparametric datasets. For example, traditional geometric transformations used in several applications to generate synthetic images can modify in a non-realistic manner the patients' anatomy. Therefore, dedicated image generation techniques are necessary in the medical field to, for example, mimic a given pathology realistically. This paper introduces a new data augmentation architecture that generates synthetic multiparametric (T1 arterial, T1 portal, and T2) magnetic resonance images (MRI) of massive macrotrabecular subtype hepatocellular carcinoma with their corresponding tumor masks through a generative deep learning approach. The proposed architecture creates liver tumor masks and abdominal edges used as input in a Pix2Pix network for synthetic data creation. The method's efficiency is demonstrated by training it on a limited multiparametric dataset of MRI triplets from $89$ patients with liver lesions to generate $1,000$ synthetic triplets and their corresponding liver tumor masks. The resulting Frechet Inception Distance score was $86.55$. The proposed approach was among the winners of the 2021 data augmentation challenge organized by the French Society of Radiology.

{{</citation>}}


### (39/58) An objective validation of polyp and instrument segmentation methods in colonoscopy through Medico 2020 polyp segmentation and MedAI 2021 transparency challenges (Debesh Jha et al., 2023)

{{<citation>}}

Debesh Jha, Vanshali Sharma, Debapriya Banik, Debayan Bhattacharya, Kaushiki Roy, Steven A. Hicks, Nikhil Kumar Tomar, Vajira Thambawita, Adrian Krenzer, Ge-Peng Ji, Sahadev Poudel, George Batchkala, Saruar Alam, Awadelrahman M. A. Ahmed, Quoc-Huy Trinh, Zeshan Khan, Tien-Phat Nguyen, Shruti Shrestha, Sabari Nathan, Jeonghwan Gwak, Ritika K. Jha, Zheyuan Zhang, Alexander Schlaefer, Debotosh Bhattacharjee, M. K. Bhuyan, Pradip K. Das, Sravanthi Parsa, Sharib Ali, Michael A. Riegler, Pål Halvorsen, Ulas Bagci, Thomas De Lange. (2023)  
**An objective validation of polyp and instrument segmentation methods in colonoscopy through Medico 2020 polyp segmentation and MedAI 2021 transparency challenges**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16262v1)  

---


**ABSTRACT**  
Automatic analysis of colonoscopy images has been an active field of research motivated by the importance of early detection of precancerous polyps. However, detecting polyps during the live examination can be challenging due to various factors such as variation of skills and experience among the endoscopists, lack of attentiveness, and fatigue leading to a high polyp miss-rate. Deep learning has emerged as a promising solution to this challenge as it can assist endoscopists in detecting and classifying overlooked polyps and abnormalities in real time. In addition to the algorithm's accuracy, transparency and interpretability are crucial to explaining the whys and hows of the algorithm's prediction. Further, most algorithms are developed in private data, closed source, or proprietary software, and methods lack reproducibility. Therefore, to promote the development of efficient and transparent methods, we have organized the "Medico automatic polyp segmentation (Medico 2020)" and "MedAI: Transparency in Medical Image Segmentation (MedAI 2021)" competitions. We present a comprehensive summary and analyze each contribution, highlight the strength of the best-performing methods, and discuss the possibility of clinical translations of such methods into the clinic. For the transparency task, a multi-disciplinary team, including expert gastroenterologists, accessed each submission and evaluated the team based on open-source practices, failure case analysis, ablation studies, usability and understandability of evaluations to gain a deeper understanding of the models' credibility for clinical deployment. Through the comprehensive analysis of the challenge, we not only highlight the advancements in polyp and surgical instrument segmentation but also encourage qualitative evaluation for building more transparent and understandable AI-based colonoscopy systems.

{{</citation>}}


### (40/58) Unsupervised Decomposition Networks for Bias Field Correction in MR Image (Dong Liang et al., 2023)

{{<citation>}}

Dong Liang, Xingyu Qiu, Kuanquan Wang, Gongning Luo, Wei Wang, Yashu Liu. (2023)  
**Unsupervised Decomposition Networks for Bias Field Correction in MR Image**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2307.16219v1)  

---


**ABSTRACT**  
Bias field, which is caused by imperfect MR devices or imaged objects, introduces intensity inhomogeneity into MR images and degrades the performance of MR image analysis methods. Many retrospective algorithms were developed to facilitate the bias correction, to which the deep learning-based methods outperformed. However, in the training phase, the supervised deep learning-based methods heavily rely on the synthesized bias field. As the formation of the bias field is extremely complex, it is difficult to mimic the true physical property of MR images by synthesized data. While bias field correction and image segmentation are strongly related, the segmentation map is precisely obtained by decoupling the bias field from the original MR image, and the bias value is indicated by the segmentation map in reverse. Thus, we proposed novel unsupervised decomposition networks that are trained only with biased data to obtain the bias-free MR images. Networks are made up of: a segmentation part to predict the probability of every pixel belonging to each class, and an estimation part to calculate the bias field, which are optimized alternately. Furthermore, loss functions based on the combination of fuzzy clustering and the multiplicative bias field are also devised. The proposed loss functions introduce the smoothness of bias field and construct the soft relationships among different classes under intra-consistency constraints. Extensive experiments demonstrate that the proposed method can accurately estimate bias fields and produce better bias correction results. The code is available on the link: https://github.com/LeongDong/Bias-Decomposition-Networks.

{{</citation>}}


### (41/58) StarSRGAN: Improving Real-World Blind Super-Resolution (Khoa D. Vo et al., 2023)

{{<citation>}}

Khoa D. Vo, Len T. Bui. (2023)  
**StarSRGAN: Improving Real-World Blind Super-Resolution**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2307.16169v1)  

---


**ABSTRACT**  
The aim of blind super-resolution (SR) in computer vision is to improve the resolution of an image without prior knowledge of the degradation process that caused the image to be low-resolution. The State of the Art (SOTA) model Real-ESRGAN has advanced perceptual loss and produced visually compelling outcomes using more complex degradation models to simulate real-world degradations. However, there is still room to improve the super-resolved quality of Real-ESRGAN by implementing recent techniques. This research paper introduces StarSRGAN, a novel GAN model designed for blind super-resolution tasks that utilize 5 various architectures. Our model provides new SOTA performance with roughly 10% better on the MANIQA and AHIQ measures, as demonstrated by experimental comparisons with Real-ESRGAN. In addition, as a compact version, StarSRGAN Lite provides approximately 7.5 times faster reconstruction speed (real-time upsampling from 540p to 4K) but can still keep nearly 90% of image quality, thereby facilitating the development of a real-time SR experience for future research. Our codes are released at https://github.com/kynthesis/StarSRGAN.

{{</citation>}}


## cs.AI (3)



### (42/58) Representing and Reasoning with Multi-Stakeholder Qualitative Preference Queries (Samik Basu et al., 2023)

{{<citation>}}

Samik Basu, Vasant Honavar, Ganesh Ram Santhanam, Jia Tao. (2023)  
**Representing and Reasoning with Multi-Stakeholder Qualitative Preference Queries**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-DB, cs-LO, cs.AI  
Keywords: Reasoning  
[Paper Link](http://arxiv.org/abs/2307.16307v1)  

---


**ABSTRACT**  
Many decision-making scenarios, e.g., public policy, healthcare, business, and disaster response, require accommodating the preferences of multiple stakeholders. We offer the first formal treatment of reasoning with multi-stakeholder qualitative preferences in a setting where stakeholders express their preferences in a qualitative preference language, e.g., CP-net, CI-net, TCP-net, CP-Theory. We introduce a query language for expressing queries against such preferences over sets of outcomes that satisfy specified criteria, e.g., $\mlangpref{\psi_1}{\psi_2}{A}$ (read loosely as the set of outcomes satisfying $\psi_1$ that are preferred over outcomes satisfying $\psi_2$ by a set of stakeholders $A$). Motivated by practical application scenarios, we introduce and analyze several alternative semantics for such queries, and examine their interrelationships. We provide a provably correct algorithm for answering multi-stakeholder qualitative preference queries using model checking in alternation-free $\mu$-calculus. We present experimental results that demonstrate the feasibility of our approach.

{{</citation>}}


### (43/58) Rethinking Uncertainly Missing and Ambiguous Visual Modality in Multi-Modal Entity Alignment (Zhuo Chen et al., 2023)

{{<citation>}}

Zhuo Chen, Lingbing Guo, Yin Fang, Yichi Zhang, Jiaoyan Chen, Jeff Z. Pan, Yangning Li, Huajun Chen, Wen Zhang. (2023)  
**Rethinking Uncertainly Missing and Ambiguous Visual Modality in Multi-Modal Entity Alignment**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CV, cs-LG, cs-MM, cs.AI  
Keywords: Entity Alignment  
[Paper Link](http://arxiv.org/abs/2307.16210v2)  

---


**ABSTRACT**  
As a crucial extension of entity alignment (EA), multi-modal entity alignment (MMEA) aims to identify identical entities across disparate knowledge graphs (KGs) by exploiting associated visual information. However, existing MMEA approaches primarily concentrate on the fusion paradigm of multi-modal entity features, while neglecting the challenges presented by the pervasive phenomenon of missing and intrinsic ambiguity of visual images. In this paper, we present a further analysis of visual modality incompleteness, benchmarking latest MMEA models on our proposed dataset MMEA-UMVM, where the types of alignment KGs covering bilingual and monolingual, with standard (non-iterative) and iterative training paradigms to evaluate the model performance. Our research indicates that, in the face of modality incompleteness, models succumb to overfitting the modality noise, and exhibit performance oscillations or declines at high rates of missing modality. This proves that the inclusion of additional multi-modal data can sometimes adversely affect EA. To address these challenges, we introduce UMAEA , a robust multi-modal entity alignment approach designed to tackle uncertainly missing and ambiguous visual modalities. It consistently achieves SOTA performance across all 97 benchmark splits, significantly surpassing existing baselines with limited parameters and time consumption, while effectively alleviating the identified limitations of other models. Our code and benchmark data are available at https://github.com/zjukg/UMAEA.

{{</citation>}}


### (44/58) Synthesizing Event-centric Knowledge Graphs of Daily Activities Using Virtual Space (Shusaku Egami et al., 2023)

{{<citation>}}

Shusaku Egami, Takanori Ugai, Mikiko Oono, Koji Kitamura, Ken Fukuda. (2023)  
**Synthesizing Event-centric Knowledge Graphs of Daily Activities Using Virtual Space**  

---
Primary Category: cs.AI  
Categories: I-2-4; H-4-2; H-3-3; H-3-1, cs-AI, cs-DB, cs-IR, cs-MM, cs.AI  
Keywords: AI, Knowledge Graph  
[Paper Link](http://arxiv.org/abs/2307.16206v1)  

---


**ABSTRACT**  
Artificial intelligence (AI) is expected to be embodied in software agents, robots, and cyber-physical systems that can understand the various contextual information of daily life in the home environment to support human behavior and decision making in various situations. Scene graph and knowledge graph (KG) construction technologies have attracted much attention for knowledge-based embodied question answering meeting this expectation. However, collecting and managing real data on daily activities under various experimental conditions in a physical space are quite costly, and developing AI that understands the intentions and contexts is difficult. In the future, data from both virtual spaces, where conditions can be easily modified, and physical spaces, where conditions are difficult to change, are expected to be combined to analyze daily living activities. However, studies on the KG construction of daily activities using virtual space and their application have yet to progress. The potential and challenges must still be clarified to facilitate AI development for human daily life. Thus, this study proposes the VirtualHome2KG framework to generate synthetic KGs of daily life activities in virtual space. This framework augments both the synthetic video data of daily activities and the contextual semantic data corresponding to the video contents based on the proposed event-centric schema and virtual space simulation results. Therefore, context-aware data can be analyzed, and various applications that have conventionally been difficult to develop due to the insufficient availability of relevant data and semantic information can be developed. We also demonstrate herein the utility and potential of the proposed VirtualHome2KG framework through several use cases, including the analysis of daily activities by querying, embedding, and clustering, and fall risk detection among ...

{{</citation>}}


## cs.IR (1)



### (45/58) Time-Aware Item Weighting for the Next Basket Recommendations (Aleksey Romanov et al., 2023)

{{<citation>}}

Aleksey Romanov, Oleg Lashinin, Marina Ananyeva, Sergey Kolesnikov. (2023)  
**Time-Aware Item Weighting for the Next Basket Recommendations**  

---
Primary Category: cs.IR  
Categories: cs-IR, cs.IR  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16297v1)  

---


**ABSTRACT**  
In this paper we study the next basket recommendation problem. Recent methods use different approaches to achieve better performance. However, many of them do not use information about the time of prediction and time intervals between baskets. To fill this gap, we propose a novel method, Time-Aware Item-based Weighting (TAIW), which takes timestamps and intervals into account. We provide experiments on three real-world datasets, and TAIW outperforms well-tuned state-of-the-art baselines for next-basket recommendations. In addition, we show the results of an ablation study and a case study of a few items.

{{</citation>}}


## cs.DB (1)



### (46/58) Towards Learned Predictability of Storage Systems (Chenyuan Wu, 2023)

{{<citation>}}

Chenyuan Wu. (2023)  
**Towards Learned Predictability of Storage Systems**  

---
Primary Category: cs.DB  
Categories: cs-AI, cs-DB, cs-OS, cs.DB  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16288v1)  

---


**ABSTRACT**  
With the rapid development of cloud computing and big data technologies, storage systems have become a fundamental building block of datacenters, incorporating hardware innovations such as flash solid state drives and non-volatile memories, as well as software infrastructures such as RAID and distributed file systems. Despite the growing popularity and interests in storage, designing and implementing reliable storage systems remains challenging, due to their performance instability and prevailing hardware failures.   Proactive prediction greatly strengthens the reliability of storage systems. There are two dimensions of prediction: performance and failure. Ideally, through detecting in advance the slow IO requests, and predicting device failures before they really happen, we can build storage systems with especially low tail latency and high availability. While its importance is well recognized, such proactive prediction in storage systems, on the other hand, is particularly difficult. To move towards predictability of storage systems, various mechanisms and field studies have been proposed in the past few years. In this report, we present a survey of these mechanisms and field studies, focusing on machine learning based black-box approaches. Based on three representative research works, we discuss where and how machine learning should be applied in this field. The strengths and limitations of each research work are also evaluated in detail.

{{</citation>}}


## cs.RO (3)



### (47/58) Robust Unmanned Surface Vehicle Navigation with Distributional Reinforcement Learning (Xi Lin et al., 2023)

{{<citation>}}

Xi Lin, John McConnell, Brendan Englot. (2023)  
**Robust Unmanned Surface Vehicle Navigation with Distributional Reinforcement Learning**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16240v1)  

---


**ABSTRACT**  
Autonomous navigation of Unmanned Surface Vehicles (USV) in marine environments with current flows is challenging, and few prior works have addressed the sensorbased navigation problem in such environments under no prior knowledge of the current flow and obstacles. We propose a Distributional Reinforcement Learning (RL) based local path planner that learns return distributions which capture the uncertainty of action outcomes, and an adaptive algorithm that automatically tunes the level of sensitivity to the risk in the environment. The proposed planner achieves a more stable learning performance and converges to safer policies than a traditional RL based planner. Computational experiments demonstrate that comparing to a traditional RL based planner and classical local planning methods such as Artificial Potential Fields and the Bug Algorithm, the proposed planner is robust against environmental flows, and is able to plan trajectories that are superior in safety, time and energy consumption.

{{</citation>}}


### (48/58) MTD-GPT: A Multi-Task Decision-Making GPT Model for Autonomous Driving at Unsignalized Intersections (Jiaqi Liu et al., 2023)

{{<citation>}}

Jiaqi Liu, Peng Hang, Xiao qi, Jianqiang Wang, Jian Sun. (2023)  
**MTD-GPT: A Multi-Task Decision-Making GPT Model for Autonomous Driving at Unsignalized Intersections**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs.RO  
Keywords: GPT, Transformer  
[Paper Link](http://arxiv.org/abs/2307.16118v1)  

---


**ABSTRACT**  
Autonomous driving technology is poised to transform transportation systems. However, achieving safe and accurate multi-task decision-making in complex scenarios, such as unsignalized intersections, remains a challenge for autonomous vehicles. This paper presents a novel approach to this issue with the development of a Multi-Task Decision-Making Generative Pre-trained Transformer (MTD-GPT) model. Leveraging the inherent strengths of reinforcement learning (RL) and the sophisticated sequence modeling capabilities of the Generative Pre-trained Transformer (GPT), the MTD-GPT model is designed to simultaneously manage multiple driving tasks, such as left turns, straight-ahead driving, and right turns at unsignalized intersections. We initially train a single-task RL expert model, sample expert data in the environment, and subsequently utilize a mixed multi-task dataset for offline GPT training. This approach abstracts the multi-task decision-making problem in autonomous driving as a sequence modeling task. The MTD-GPT model is trained and evaluated across several decision-making tasks, demonstrating performance that is either superior or comparable to that of state-of-the-art single-task decision-making models.

{{</citation>}}


### (49/58) TransFusion: A Practical and Effective Transformer-based Diffusion Model for 3D Human Motion Prediction (Sibo Tian et al., 2023)

{{<citation>}}

Sibo Tian, Minghui Zheng, Xiao Liang. (2023)  
**TransFusion: A Practical and Effective Transformer-based Diffusion Model for 3D Human Motion Prediction**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2307.16106v1)  

---


**ABSTRACT**  
Predicting human motion plays a crucial role in ensuring a safe and effective human-robot close collaboration in intelligent remanufacturing systems of the future. Existing works can be categorized into two groups: those focusing on accuracy, predicting a single future motion, and those generating diverse predictions based on observations. The former group fails to address the uncertainty and multi-modal nature of human motion, while the latter group often produces motion sequences that deviate too far from the ground truth or become unrealistic within historical contexts. To tackle these issues, we propose TransFusion, an innovative and practical diffusion-based model for 3D human motion prediction which can generate samples that are more likely to happen while maintaining a certain level of diversity. Our model leverages Transformer as the backbone with long skip connections between shallow and deep layers. Additionally, we employ the discrete cosine transform to model motion sequences in the frequency space, thereby improving performance. In contrast to prior diffusion-based models that utilize extra modules like cross-attention and adaptive layer normalization to condition the prediction on past observed motion, we treat all inputs, including conditions, as tokens to create a more lightweight model compared to existing approaches. Extensive experimental studies are conducted on benchmark datasets to validate the effectiveness of our human motion prediction model.

{{</citation>}}


## cs.NE (2)



### (50/58) Synaptic Plasticity Models and Bio-Inspired Unsupervised Deep Learning: A Survey (Gabriele Lagani et al., 2023)

{{<citation>}}

Gabriele Lagani, Fabrizio Falchi, Claudio Gennaro, Giuseppe Amato. (2023)  
**Synaptic Plasticity Models and Bio-Inspired Unsupervised Deep Learning: A Survey**  

---
Primary Category: cs.NE  
Categories: cs-AI, cs-CV, cs-LG, cs-NE, cs.NE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16236v1)  

---


**ABSTRACT**  
Recently emerged technologies based on Deep Learning (DL) achieved outstanding results on a variety of tasks in the field of Artificial Intelligence (AI). However, these encounter several challenges related to robustness to adversarial inputs, ecological impact, and the necessity of huge amounts of training data. In response, researchers are focusing more and more interest on biologically grounded mechanisms, which are appealing due to the impressive capabilities exhibited by biological brains. This survey explores a range of these biologically inspired models of synaptic plasticity, their application in DL scenarios, and the connections with models of plasticity in Spiking Neural Networks (SNNs). Overall, Bio-Inspired Deep Learning (BIDL) represents an exciting research direction, aiming at advancing not only our current technologies but also our understanding of intelligence.

{{</citation>}}


### (51/58) Spiking Neural Networks and Bio-Inspired Supervised Deep Learning: A Survey (Gabriele Lagani et al., 2023)

{{<citation>}}

Gabriele Lagani, Fabrizio Falchi, Claudio Gennaro, Giuseppe Amato. (2023)  
**Spiking Neural Networks and Bio-Inspired Supervised Deep Learning: A Survey**  

---
Primary Category: cs.NE  
Categories: cs-AI, cs-CV, cs-LG, cs-NE, cs.NE  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2307.16235v1)  

---


**ABSTRACT**  
For a long time, biology and neuroscience fields have been a great source of inspiration for computer scientists, towards the development of Artificial Intelligence (AI) technologies. This survey aims at providing a comprehensive review of recent biologically-inspired approaches for AI. After introducing the main principles of computation and synaptic plasticity in biological neurons, we provide a thorough presentation of Spiking Neural Network (SNN) models, and we highlight the main challenges related to SNN training, where traditional backprop-based optimization is not directly applicable. Therefore, we discuss recent bio-inspired training methods, which pose themselves as alternatives to backprop, both for traditional and spiking networks. Bio-Inspired Deep Learning (BIDL) approaches towards advancing the computational capabilities and biological plausibility of current models.

{{</citation>}}


## cs.MA (2)



### (52/58) Robust Electric Vehicle Balancing of Autonomous Mobility-On-Demand System: A Multi-Agent Reinforcement Learning Approach (Sihong He et al., 2023)

{{<citation>}}

Sihong He, Shuo Han, Fei Miao. (2023)  
**Robust Electric Vehicle Balancing of Autonomous Mobility-On-Demand System: A Multi-Agent Reinforcement Learning Approach**  

---
Primary Category: cs.MA  
Categories: cs-AI, cs-LG, cs-MA, cs-SY, cs.MA, eess-SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16228v1)  

---


**ABSTRACT**  
Electric autonomous vehicles (EAVs) are getting attention in future autonomous mobility-on-demand (AMoD) systems due to their economic and societal benefits. However, EAVs' unique charging patterns (long charging time, high charging frequency, unpredictable charging behaviors, etc.) make it challenging to accurately predict the EAVs supply in E-AMoD systems. Furthermore, the mobility demand's prediction uncertainty makes it an urgent and challenging task to design an integrated vehicle balancing solution under supply and demand uncertainties. Despite the success of reinforcement learning-based E-AMoD balancing algorithms, state uncertainties under the EV supply or mobility demand remain unexplored. In this work, we design a multi-agent reinforcement learning (MARL)-based framework for EAVs balancing in E-AMoD systems, with adversarial agents to model both the EAVs supply and mobility demand uncertainties that may undermine the vehicle balancing solutions. We then propose a robust E-AMoD Balancing MARL (REBAMA) algorithm to train a robust EAVs balancing policy to balance both the supply-demand ratio and charging utilization rate across the whole city. Experiments show that our proposed robust method performs better compared with a non-robust MARL method that does not consider state uncertainties; it improves the reward, charging utilization fairness, and supply-demand fairness by 19.28%, 28.18%, and 3.97%, respectively. Compared with a robust optimization-based method, the proposed MARL algorithm can improve the reward, charging utilization fairness, and supply-demand fairness by 8.21%, 8.29%, and 9.42%, respectively.

{{</citation>}}


### (53/58) ESP: Exploiting Symmetry Prior for Multi-Agent Reinforcement Learning (Xin Yu et al., 2023)

{{<citation>}}

Xin Yu, Rongye Shi, Pu Feng, Yongkai Tian, Jie Luo, Wenjun Wu. (2023)  
**ESP: Exploiting Symmetry Prior for Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.MA  
Categories: cs-AI, cs-LG, cs-MA, cs-RO, cs.MA  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2307.16186v1)  

---


**ABSTRACT**  
Multi-agent reinforcement learning (MARL) has achieved promising results in recent years. However, most existing reinforcement learning methods require a large amount of data for model training. In addition, data-efficient reinforcement learning requires the construction of strong inductive biases, which are ignored in the current MARL approaches. Inspired by the symmetry phenomenon in multi-agent systems, this paper proposes a framework for exploiting prior knowledge by integrating data augmentation and a well-designed consistency loss into the existing MARL methods. In addition, the proposed framework is model-agnostic and can be applied to most of the current MARL algorithms. Experimental tests on multiple challenging tasks demonstrate the effectiveness of the proposed framework. Moreover, the proposed framework is applied to a physical multi-robot testbed to show its superiority.

{{</citation>}}


## eess.SY (1)



### (54/58) Data-Driven Modeling with Experimental Augmentation for the Modulation Strategy of the Dual-Active-Bridge Converter (Xinze Li et al., 2023)

{{<citation>}}

Xinze Li, Josep Pou, Jiaxin Dong, Fanfan Lin, Changyun Wen, Suvajit Mukherjee, Xin Zhang. (2023)  
**Data-Driven Modeling with Experimental Augmentation for the Modulation Strategy of the Dual-Active-Bridge Converter**  

---
Primary Category: eess.SY  
Categories: cs-AI, cs-SY, eess-SY, eess.SY  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2307.16173v2)  

---


**ABSTRACT**  
For the performance modeling of power converters, the mainstream approaches are essentially knowledge-based, suffering from heavy manpower burden and low modeling accuracy. Recent emerging data-driven techniques greatly relieve human reliance by automatic modeling from simulation data. However, model discrepancy may occur due to unmodeled parasitics, deficient thermal and magnetic models, unpredictable ambient conditions, etc. These inaccurate data-driven models based on pure simulation cannot represent the practical performance in physical world, hindering their applications in power converter modeling. To alleviate model discrepancy and improve accuracy in practice, this paper proposes a novel data-driven modeling with experimental augmentation (D2EA), leveraging both simulation data and experimental data. In D2EA, simulation data aims to establish basic functional landscape, and experimental data focuses on matching actual performance in real world. The D2EA approach is instantiated for the efficiency optimization of a hybrid modulation for neutral-point-clamped dual-active-bridge (NPC-DAB) converter. The proposed D2EA approach realizes 99.92% efficiency modeling accuracy, and its feasibility is comprehensively validated in 2-kW hardware experiments, where the peak efficiency of 98.45% is attained. Overall, D2EA is data-light and can achieve highly accurate and highly practical data-driven models in one shot, and it is scalable to other applications, effortlessly.

{{</citation>}}


## cs.SD (1)



### (55/58) HierVST: Hierarchical Adaptive Zero-shot Voice Style Transfer (Sang-Hoon Lee et al., 2023)

{{<citation>}}

Sang-Hoon Lee, Ha-Yeong Choi, Hyung-Seok Oh, Seong-Whan Lee. (2023)  
**HierVST: Hierarchical Adaptive Zero-shot Voice Style Transfer**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-MM, cs-SD, cs.SD, eess-AS  
Keywords: Style Transfer  
[Paper Link](http://arxiv.org/abs/2307.16171v1)  

---


**ABSTRACT**  
Despite rapid progress in the voice style transfer (VST) field, recent zero-shot VST systems still lack the ability to transfer the voice style of a novel speaker. In this paper, we present HierVST, a hierarchical adaptive end-to-end zero-shot VST model. Without any text transcripts, we only use the speech dataset to train the model by utilizing hierarchical variational inference and self-supervised representation. In addition, we adopt a hierarchical adaptive generator that generates the pitch representation and waveform audio sequentially. Moreover, we utilize unconditional generation to improve the speaker-relative acoustic capacity in the acoustic representation. With a hierarchical adaptive structure, the model can adapt to a novel voice style and convert speech progressively. The experimental results demonstrate that our method outperforms other VST models in zero-shot VST scenarios. Audio samples are available at \url{https://hiervst.github.io/}.

{{</citation>}}


## cs.HC (3)



### (56/58) RealityCanvas: Augmented Reality Sketching for Embedded and Responsive Scribble Animation Effects (Zhijie Xia et al., 2023)

{{<citation>}}

Zhijie Xia, Kyzyl Monteiro, Kevin Van, Ryo Suzuki. (2023)  
**RealityCanvas: Augmented Reality Sketching for Embedded and Responsive Scribble Animation Effects**  

---
Primary Category: cs.HC  
Categories: cs-GR, cs-HC, cs.HC  
Keywords: Sketch  
[Paper Link](http://arxiv.org/abs/2307.16116v1)  

---


**ABSTRACT**  
We introduce RealityCanvas, a mobile AR sketching tool that can easily augment real-world physical motion with responsive hand-drawn animation. Recent research in AR sketching tools has enabled users to not only embed static drawings into the real world but also dynamically animate them with physical motion. However, existing tools often lack the flexibility and expressiveness of possible animations, as they primarily support simple line-based geometry. To address this limitation, we explore both expressive and improvisational AR sketched animation by introducing a set of responsive scribble animation techniques that can be directly embedded through sketching interactions: 1) object binding, 2) flip-book animation, 3) action trigger, 4) particle effects, 5) motion trajectory, and 6) contour highlight. These six animation effects were derived from the analysis of 172 existing video-edited scribble animations. We showcase these techniques through various applications, such as video creation, augmented education, storytelling, and AR prototyping. The results of our user study and expert interviews confirm that our tool can lower the barrier to creating AR-based sketched animation, while allowing creative, expressive, and improvisational AR sketching experiences.

{{</citation>}}


### (57/58) HoloBots: Augmenting Holographic Telepresence with Mobile Robots for Tangible Remote Collaboration in Mixed Reality (Keiichi Ihara et al., 2023)

{{<citation>}}

Keiichi Ihara, Mehrad Faridan, Ayumi Ichikawa, Ikkaku Kawaguchi, Ryo Suzuki. (2023)  
**HoloBots: Augmenting Holographic Telepresence with Mobile Robots for Tangible Remote Collaboration in Mixed Reality**  

---
Primary Category: cs.HC  
Categories: cs-HC, cs-RO, cs.HC  
Keywords: Azure  
[Paper Link](http://arxiv.org/abs/2307.16114v1)  

---


**ABSTRACT**  
This paper introduces HoloBots, a mixed reality remote collaboration system that augments holographic telepresence with synchronized mobile robots. Beyond existing mixed reality telepresence, HoloBots lets remote users not only be visually and spatially present, but also physically engage with local users and their environment. HoloBots allows the users to touch, grasp, manipulate, and interact with the remote physical environment as if they were co-located in the same shared space. We achieve this by synchronizing holographic user motion (Hololens 2 and Azure Kinect) with tabletop mobile robots (Sony Toio). Beyond the existing physical telepresence, HoloBots contributes to an exploration of broader design space, such as object actuation, virtual hand physicalization, world-in-miniature exploration, shared tangible interfaces, embodied guidance, and haptic communication. We evaluate our system with twelve participants by comparing it with hologram-only and robot-only conditions. Both quantitative and qualitative results confirm that our system significantly enhances the level of co-presence and shared experience, compared to the other conditions.

{{</citation>}}


### (58/58) Augmented Math: Authoring AR-Based Explorable Explanations by Augmenting Static Math Textbooks (Neil Chulpongsatorn et al., 2023)

{{<citation>}}

Neil Chulpongsatorn, Mille Skovhus Lunding, Nishan Soni, Ryo Suzuki. (2023)  
**Augmented Math: Authoring AR-Based Explorable Explanations by Augmenting Static Math Textbooks**  

---
Primary Category: cs.HC  
Categories: cs-CV, cs-HC, cs.HC  
Keywords: OCR  
[Paper Link](http://arxiv.org/abs/2307.16112v1)  

---


**ABSTRACT**  
We introduce Augmented Math, a machine learning-based approach to authoring AR explorable explanations by augmenting static math textbooks without programming. To augment a static document, our system first extracts mathematical formulas and figures from a given document using optical character recognition (OCR) and computer vision. By binding and manipulating these extracted contents, the user can see the interactive animation overlaid onto the document through mobile AR interfaces. This empowers non-technical users, such as teachers or students, to transform existing math textbooks and handouts into on-demand and personalized explorable explanations. To design our system, we first analyzed existing explorable math explanations to identify common design strategies. Based on the findings, we developed a set of augmentation techniques that can be automatically generated based on the extracted content, which are 1) dynamic values, 2) interactive figures, 3) relationship highlights, 4) concrete examples, and 5) step-by-step hints. To evaluate our system, we conduct two user studies: preliminary user testing and expert interviews. The study results confirm that our system allows more engaging experiences for learning math concepts.

{{</citation>}}
