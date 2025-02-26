---
draft: false
title: "DeBERTa: Decoding-Enhanced BERT with Disentangled Attention"
date: 2022-05-03
author: "akitenkrad"
description: ""
tags: ["At:Round-1", "Published:2020", "BERT", "Attention", "Disentangled Attention", "Virtual Adversarial Training", "DS:GLUE", "DS:SuperGLUE", "DS:SQuAD", "DS:RACE", "DS:ReCoRD", "DS:SWAG", "DS:MultiNLI", "DS:CoNLL"]
menu:
  sidebar:
    name: "DeBERTa: Decoding-Enhanced BERT with Disentangled Attention"
    identifier: 20220503
    parent: 202205
    weight: 10
math: true
---

- [x] Round-1: Overview
- [ ] Round-2: Model Implementation Details
- [ ] Round-3: Experiments

## Citation

{{< citation >}}
He, P., Liu, X., Gao, J., & Chen, W. (2020).  
**DeBERTa: Decoding-enhanced BERT with Disentangled Attention**  
[Paper Link](https://doi.org/10.48550/arxiv.2006.03654)
{{< /citation >}}

## Abstract

> Recent progress in pre-trained neural language models has significantly
> improved the performance of many natural language processing (NLP) tasks. In
> this paper we propose a new model architecture DeBERTa (Decoding-enhanced BERT
> with disentangled attention) that improves the BERT and RoBERTa models using
> two novel techniques. The first is the disentangled attention mechanism, where
> each word is represented using two vectors that encode its content and
> position, respectively, and the attention weights among words are computed
> using disentangled matrices on their contents and relative positions,
> respectively. Second, an enhanced mask decoder is used to incorporate absolute
> positions in the decoding layer to predict the masked tokens in model
> pre-training. In addition, a new virtual adversarial training method is used
> for fine-tuning to improve models' generalization. We show that these
> techniques significantly improve the efficiency of model pre-training and the
> performance of both natural language understanding (NLU) and natural langauge
> generation (NLG) downstream tasks. Compared to RoBERTa-Large, a DeBERTa model
> trained on half of the training data performs consistently better on a wide
> range of NLP tasks, achieving improvements on MNLI by +0.9% (90.2% vs. 91.1%),
> on SQuAD v2.0 by +2.3% (88.4% vs. 90.7%) and RACE by +3.6% (83.2% vs. 86.8%).
> Notably, we scale up DeBERTa by training a larger version that consists of 48
> Transform layers with 1.5 billion parameters. The significant performance boost
> makes the single DeBERTa model surpass the human performance on the SuperGLUE
> benchmark (Wang et al., 2019a) for the first time in terms of macro-average
> score (89.9 versus 89.8), and the ensemble DeBERTa model sits atop the
> SuperGLUE leaderboard as of January 6, 2021, out performing the human baseline
> by a decent margin (90.3 versus 89.8).

## Background & Wat's New

- 2つの新しいテクニックを使ってBERTとRoBERTaを精度改善
  - **Disentangled Attention**  
    - トークンの分散表現は，その内容だけではなく文書内での相対的な位置にも依存している
    - テキストの内容とトークンの相対的な位置情報をそれぞれベクトル化し，組み合わせて分散表現を構成
    - Attention Weightは2つのベクトルの共起行列（disentangled matrices）によって計算される
  - **Enhanced Mask Decoder**  
    - 事前学習のデコーダで絶対的な位置情報を加味してマスクされたトークンを予測する  
    - Disentangled Attentionでも相対的な位置情報を利用しているが，予測時には絶対的な位置情報も重要となる
- 学習には新しいVirtual Adversarial Training (Miyato et al., 2017; Jiang et al., 2020) の学習方法 **Scale-invariant-Fine-Tuning** (SiFT) を提案
- GitHub <i class="fa-solid fa-arrow-right"></i> https://github.com/microsoft/DeBERTa

## Dataset

{{< ci-details summary="GLUE" >}}
Alex Wang, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, Samuel R. Bowman. (2018)  
**GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding**  
BlackboxNLP@EMNLP  
https://www.semanticscholar.org/paper/93b8da28d006415866bf48f9a6e06b5242129195  
{{< /ci-details >}}

{{< ci-details summary="SuperGLUE" >}}
Alex Wang, Yada Pruksachatkun, Nikita Nangia, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, Samuel R. Bowman. (2019)  
**SuperGLUE: A Stickier Benchmark for General-Purpose Language Understanding Systems**  
NeurIPS  
https://www.semanticscholar.org/paper/d9f6ada77448664b71128bb19df15765336974a6  
{{< /ci-details >}}

{{< ci-details summary="SQuAD v1.1" >}}
Rajpurkar, P., Zhang, J., Lopyrev, K., & Liang, P. (2016).  
**SQuAD: 100,000+ Questions for Machine Comprehension of Text.**  
EMNLP 2016 - Conference on Empirical Methods in Natural Language Processing, Proceedings, 2383–2392.  
https://doi.org/10.18653/V1/D16-1264
{{< /ci-details >}}

{{< ci-details summary="RACE" >}}
Guokun Lai, Qizhe Xie, Hanxiao Liu, Yiming Yang, E. Hovy. (2017)  
**RACE: Large-scale ReAding Comprehension Dataset From Examinations**  
EMNLP  
https://www.semanticscholar.org/paper/636a79420d838eabe4af7fb25d6437de45ab64e8  
{{< /ci-details >}}

{{< ci-details summary="ReCoRD">}}
Sheng Zhang, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Kevin Duh, Benjamin Van Durme. (2018)  
**ReCoRD: Bridging the Gap between Human and Machine Commonsense Reading Comprehension**  
ArXiv  
https://www.semanticscholar.org/paper/a5b66ee341cb990f7f70a124b5fab3316d3b7e27  
{{< /ci-details >}}

{{< ci-details summary="SWAG" >}}
Rowan Zellers, Yonatan Bisk, Roy Schwartz, Yejin Choi. (2018)  
**SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference**  
EMNLP  
https://www.semanticscholar.org/paper/af5c4b80fbf847f69a202ba5a780a3dd18c1a027  
{{< /ci-details >}}

{{< ci-details summary="MultiNLI" >}}
Adina Williams, Nikita Nangia, Samuel R. Bowman. (2017)  
**A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/5ded2b8c64491b4a67f6d39ce473d4b9347a672e)  
{{< /ci-details >}}

{{< ci-details summary="CoNLL-2003" >}}
Sang, E. F. T. K., & de Meulder, F. (2003).  
Introduction to the CoNLL-2003 Shared Task: Language-Independent Named Entity Recognition.  
[Paper Link](https://doi.org/10.48550/arxiv.cs/0306050)
{{< /ci-details >}}


## Model Description
TBD

### Training Settings

- 学習データ
  - Wikipedia ([English Wikipedia dump](https://dumps.wikimedia.org/enwiki/))
  - BookCorpus
{{< ci-details summary="Zhu et al. (2015)" >}}
Yukun Zhu, Ryan Kiros, R. Zemel, R. Salakhutdinov, R. Urtasun, A. Torralba, S. Fidler. (2015)  
**Aligning Books and Movies: Towards Story-Like Visual Explanations by Watching Movies and Reading Books**  
2015 IEEE International Conference on Computer Vision (ICCV)  
[Paper Link](https://www.semanticscholar.org/paper/0e6824e137847be0599bb0032e37042ed2ef5045)
{{< /ci-details >}}
  - OPENWEBTEXT
{{< ci-details summary="Gokaslan & Cohen (2019)" >}}
Aaron Gokaslan and Vanya Cohen. (2019)  
**Openwebtext corpus.**  
[Dataset Link](http://Skylion007.github.io)
{{< /ci-details >}}
  - STORIES
{{< ci-details summary="Trinh et al. (2018)" >}}
Trieu H. Trinh, Quoc V. Le. (2018)  
**A Simple Method for Commonsense Reasoning**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/d7b6753a2d4a2b286c396854063bde3a91b75535)
{{< /ci-details >}}

モデルごとの学習データ使用状況
<img src="pre-train-ds-table7.png"/>

## Results

##### Comparison results on the GLUE dev set

<img src="result-table1.png"/>

- RoBERTaやXLNet，ELECTRAなどの事前学習モデルは160GBの学習データを必要としたが，DeBERTaは78GBだけで学習が可能
- ほぼ全てのタスクにおいて，DeBERTaが他のモデルよりも良い精度を達成している

##### Results on NLP Datasets

<img src="result-table2.png"/>

## References


{{< ci-details summary="ERNIE: Enhanced Representation through Knowledge Integration (Yu Sun et al., 2019)">}}

Yu Sun, Shuohuan Wang, Yukun Li, Shikun Feng, Xuyi Chen, Han Zhang, Xin Tian, Danxiang Zhu, Hao Tian, Hua Wu. (2019)  
**ERNIE: Enhanced Representation through Knowledge Integration**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/031e4e43aaffd7a479738dcea69a2d5be7957aa3)  
Influential Citation Count (63), SS-ID (031e4e43aaffd7a479738dcea69a2d5be7957aa3)  

**ABSTRACT**  
We present a novel language representation model enhanced by knowledge called ERNIE (Enhanced Representation through kNowledge IntEgration). Inspired by the masking strategy of BERT, ERNIE is designed to learn language representation enhanced by knowledge masking strategies, which includes entity-level masking and phrase-level masking. Entity-level strategy masks entities which are usually composed of multiple words.Phrase-level strategy masks the whole phrase which is composed of several words standing together as a conceptual unit.Experimental results show that ERNIE outperforms other baseline methods, achieving new state-of-the-art results on five Chinese natural language processing tasks including natural language inference, semantic similarity, named entity recognition, sentiment analysis and question answering. We also demonstrate that ERNIE has more powerful knowledge inference capacity on a cloze test.

{{< /ci-details >}}

{{< ci-details summary="Reformer: The Efficient Transformer (Nikita Kitaev et al., 2020)">}}

Nikita Kitaev, Lukasz Kaiser, Anselm Levskaya. (2020)  
**Reformer: The Efficient Transformer**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/055fd6a9f7293269f1b22c1470e63bd02d8d9500)  
Influential Citation Count (103), SS-ID (055fd6a9f7293269f1b22c1470e63bd02d8d9500)  

**ABSTRACT**  
Large Transformer models routinely achieve state-of-the-art results on a number of tasks but training these models can be prohibitively costly, especially on long sequences. We introduce two techniques to improve the efficiency of Transformers. For one, we replace dot-product attention by one that uses locality-sensitive hashing, changing its complexity from O($L^2$) to O($L\log L$), where $L$ is the length of the sequence. Furthermore, we use reversible residual layers instead of the standard residuals, which allows storing activations only once in the training process instead of $N$ times, where $N$ is the number of layers. The resulting model, the Reformer, performs on par with Transformer models while being much more memory-efficient and much faster on long sequences.

{{< /ci-details >}}

{{< ci-details summary="SQuAD: 100,000+ Questions for Machine Comprehension of Text (Pranav Rajpurkar et al., 2016)">}}

Pranav Rajpurkar, Jian Zhang, Konstantin Lopyrev, Percy Liang. (2016)  
**SQuAD: 100,000+ Questions for Machine Comprehension of Text**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/05dd7254b632376973f3a1b4d39485da17814df5)  
Influential Citation Count (1063), SS-ID (05dd7254b632376973f3a1b4d39485da17814df5)  

**ABSTRACT**  
We present the Stanford Question Answering Dataset (SQuAD), a new reading comprehension dataset consisting of 100,000+ questions posed by crowdworkers on a set of Wikipedia articles, where the answer to each question is a segment of text from the corresponding reading passage. We analyze the dataset to understand the types of reasoning required to answer the questions, leaning heavily on dependency and constituency trees. We build a strong logistic regression model, which achieves an F1 score of 51.0%, a significant improvement over a simple baseline (20%). However, human performance (86.8%) is much higher, indicating that the dataset presents a good challenge problem for future research.  The dataset is freely available at this https URL

{{< /ci-details >}}

{{< ci-details summary="RoBERTa: A Robustly Optimized BERT Pretraining Approach (Yinhan Liu et al., 2019)">}}

Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, M. Lewis, Luke Zettlemoyer, Veselin Stoyanov. (2019)  
**RoBERTa: A Robustly Optimized BERT Pretraining Approach**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/077f8329a7b6fa3b7c877a57b81eb6c18b5f87de)  
Influential Citation Count (2015), SS-ID (077f8329a7b6fa3b7c877a57b81eb6c18b5f87de)  

**ABSTRACT**  
Language model pretraining has led to significant performance gains but careful comparison between different approaches is challenging. Training is computationally expensive, often done on private datasets of different sizes, and, as we will show, hyperparameter choices have significant impact on the final results. We present a replication study of BERT pretraining (Devlin et al., 2019) that carefully measures the impact of many key hyperparameters and training data size. We find that BERT was significantly undertrained, and can match or exceed the performance of every model published after it. Our best model achieves state-of-the-art results on GLUE, RACE and SQuAD. These results highlight the importance of previously overlooked design choices, and raise questions about the source of recently reported improvements. We release our models and code.

{{< /ci-details >}}

{{< ci-details summary="Aligning Books and Movies: Towards Story-Like Visual Explanations by Watching Movies and Reading Books (Yukun Zhu et al., 2015)">}}

Yukun Zhu, Ryan Kiros, R. Zemel, R. Salakhutdinov, R. Urtasun, A. Torralba, S. Fidler. (2015)  
**Aligning Books and Movies: Towards Story-Like Visual Explanations by Watching Movies and Reading Books**  
2015 IEEE International Conference on Computer Vision (ICCV)  
[Paper Link](https://www.semanticscholar.org/paper/0e6824e137847be0599bb0032e37042ed2ef5045)  
Influential Citation Count (167), SS-ID (0e6824e137847be0599bb0032e37042ed2ef5045)  

**ABSTRACT**  
Books are a rich source of both fine-grained information, how a character, an object or a scene looks like, as well as high-level semantics, what someone is thinking, feeling and how these states evolve through a story. This paper aims to align books to their movie releases in order to provide rich descriptive explanations for visual content that go semantically far beyond the captions available in the current datasets. To align movies and books we propose a neural sentence embedding that is trained in an unsupervised way from a large corpus of books, as well as a video-text neural embedding for computing similarities between movie clips and sentences in the book. We propose a context-aware CNN to combine information from multiple sources. We demonstrate good quantitative performance for movie/book alignment and show several qualitative examples that showcase the diversity of tasks our model can be used for.

{{< /ci-details >}}

{{< ci-details summary="The Seventh PASCAL Recognizing Textual Entailment Challenge (L. Bentivogli et al., 2011)">}}

L. Bentivogli, Peter Clark, Ido Dagan, Danilo Giampiccolo. (2011)  
**The Seventh PASCAL Recognizing Textual Entailment Challenge**  
TAC  
[Paper Link](https://www.semanticscholar.org/paper/0f8468de03ee9f12d693237bec87916311bf1c24)  
Influential Citation Count (16), SS-ID (0f8468de03ee9f12d693237bec87916311bf1c24)  

**ABSTRACT**  
This paper presents the Seventh Recognizing Textual Entailment (RTE-7) challenge. This year’s challenge replicated the exercise proposed in RTE-6, consisting of a Main Task, in which Textual Entailment is performed on a real corpus in the Update Summarization scenario; a Main subtask aimed at detecting novel information; and a KBP Validation Task, in which RTE systems had to validate the output of systems participating in the KBP Slot Filling Task. Thirteen teams participated in the Main Task (submitting 33 runs) and 5 in the Novelty Detection Subtask (submitting 13 runs). The KBP Validation Task was undertaken by 2 participants which submitted 5 runs. The ablation test experiment, introduced in RTE-5 to evaluate the impact of knowledge resources used by the systems participating in the Main Task and extended also to tools in RTE-6, was also repeated in RTE-7.

{{< /ci-details >}}

{{< ci-details summary="The Winograd Schema Challenge (H. Levesque et al., 2011)">}}

H. Levesque, E. Davis, L. Morgenstern. (2011)  
**The Winograd Schema Challenge**  
KR  
[Paper Link](https://www.semanticscholar.org/paper/128cb6b891aee1b5df099acb48e2efecfcff689f)  
Influential Citation Count (146), SS-ID (128cb6b891aee1b5df099acb48e2efecfcff689f)  

**ABSTRACT**  
In this paper, we present an alternative to the Turing Test that has some conceptual and practical advantages. Like the original, it involves responding to typed English sentences, and English-speaking adults will have no difficulty with it. Unlike the original, the subject is not required to engage in a conversation and fool an interrogator into believing she is dealing with a person. Moreover, the test is arranged in such a way that having full access to a large corpus of English text might not help much. Finally, the interrogator or a third party will be able to decide unambiguously after a few minutes whether or not a subject has passed the test.

{{< /ci-details >}}

{{< ci-details summary="The Second PASCAL Recognising Textual Entailment Challenge (Roy Bar-Haim et al., 2006)">}}

Roy Bar-Haim, Ido Dagan, Bill Dolan, L. Ferro, Danilo Giampiccolo, B. Magnini. (2006)  
**The Second PASCAL Recognising Textual Entailment Challenge**  
  
[Paper Link](https://www.semanticscholar.org/paper/136326377c122560768db674e35f5bcd6de3bc40)  
Influential Citation Count (49), SS-ID (136326377c122560768db674e35f5bcd6de3bc40)  

**ABSTRACT**  
This paper describes the Second PASCAL Recognising Textual Entailment Challenge (RTE-2). 1 We describe the RTE2 dataset and overview the submissions for the challenge. One of the main goals for this year’s dataset was to provide more “realistic” text-hypothesis examples, based mostly on outputs of actual systems. The 23 submissions for the challenge present diverse approaches and research directions, and the best results achieved this year are considerably higher than last year’s state of the art.

{{< /ci-details >}}

{{< ci-details summary="COCO-LM: Correcting and Contrasting Text Sequences for Language Model Pretraining (Yu Meng et al., 2021)">}}

Yu Meng, Chenyan Xiong, Payal Bajaj, Saurabh Tiwary, Paul Bennett, Jiawei Han, Xia Song. (2021)  
**COCO-LM: Correcting and Contrasting Text Sequences for Language Model Pretraining**  
NeurIPS  
[Paper Link](https://www.semanticscholar.org/paper/19537be34dbadbcaa4fffcf028a8ada5095b1b5c)  
Influential Citation Count (7), SS-ID (19537be34dbadbcaa4fffcf028a8ada5095b1b5c)  

**ABSTRACT**  
We present a self-supervised learning framework, COCO-LM, that pretrains Language Models by COrrecting and COntrasting corrupted text sequences. Following ELECTRA-style pretraining, COCO-LM employs an auxiliary language model to corrupt text sequences, upon which it constructs two new tasks for pretraining the main model. The first token-level task, Corrective Language Modeling, is to detect and correct tokens replaced by the auxiliary model, in order to better capture token-level semantics. The second sequence-level task, Sequence Contrastive Learning, is to align text sequences originated from the same source input while ensuring uniformity in the representation space. Experiments on GLUE and SQuAD demonstrate that COCO-LM not only outperforms recent state-of-the-art pretrained models in accuracy, but also improves pretraining efficiency. It achieves the MNLI accuracy of ELECTRA with 50% of its pretraining GPU hours. With the same pretraining steps of standard base/large-sized models, COCO-LM outperforms the previous best models by 1+ GLUE average points.

{{< /ci-details >}}

{{< ci-details summary="Unified Language Model Pre-training for Natural Language Understanding and Generation (Li Dong et al., 2019)">}}

Li Dong, Nan Yang, Wenhui Wang, Furu Wei, Xiaodong Liu, Yu Wang, Jianfeng Gao, M. Zhou, H. Hon. (2019)  
**Unified Language Model Pre-training for Natural Language Understanding and Generation**  
NeurIPS  
[Paper Link](https://www.semanticscholar.org/paper/1c71771c701aadfd72c5866170a9f5d71464bb88)  
Influential Citation Count (106), SS-ID (1c71771c701aadfd72c5866170a9f5d71464bb88)  

**ABSTRACT**  
This paper presents a new Unified pre-trained Language Model (UniLM) that can be fine-tuned for both natural language understanding and generation tasks. The model is pre-trained using three types of language modeling tasks: unidirectional, bidirectional, and sequence-to-sequence prediction. The unified modeling is achieved by employing a shared Transformer network and utilizing specific self-attention masks to control what context the prediction conditions on. UniLM compares favorably with BERT on the GLUE benchmark, and the SQuAD 2.0 and CoQA question answering tasks. Moreover, UniLM achieves new state-of-the-art results on five natural language generation datasets, including improving the CNN/DailyMail abstractive summarization ROUGE-L to 40.51 (2.04 absolute improvement), the Gigaword abstractive summarization ROUGE-L to 35.75 (0.86 absolute improvement), the CoQA generative question answering F1 score to 82.5 (37.1 absolute improvement), the SQuAD question generation BLEU-4 to 22.12 (3.75 absolute improvement), and the DSTC7 document-grounded dialog response generation NIST-4 to 2.67 (human performance is 2.65). The code and pre-trained models are available at this https URL.

{{< /ci-details >}}

{{< ci-details summary="Attention is All you Need (Ashish Vaswani et al., 2017)">}}

Ashish Vaswani, Noam M. Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser, Illia Polosukhin. (2017)  
**Attention is All you Need**  
NIPS  
[Paper Link](https://www.semanticscholar.org/paper/204e3073870fae3d05bcbc2f6a8e263d9b72e776)  
Influential Citation Count (7570), SS-ID (204e3073870fae3d05bcbc2f6a8e263d9b72e776)  

**ABSTRACT**  
The dominant sequence transduction models are based on complex recurrent or convolutional neural networks in an encoder-decoder configuration. The best performing models also connect the encoder and decoder through an attention mechanism. We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely. Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train. Our model achieves 28.4 BLEU on the WMT 2014 English-to-German translation task, improving over the existing best results, including ensembles by over 2 BLEU. On the WMT 2014 English-to-French translation task, our model establishes a new single-model state-of-the-art BLEU score of 41.8 after training for 3.5 days on eight GPUs, a small fraction of the training costs of the best models from the literature. We show that the Transformer generalizes well to other tasks by applying it successfully to English constituency parsing both with large and limited training data.

{{< /ci-details >}}

{{< ci-details summary="Natural- to formal-language generation using Tensor Product Representations (Kezhen Chen et al., 2019)">}}

Kezhen Chen, Qiuyuan Huang, H. Palangi, P. Smolensky, Kenneth D. Forbus, Jianfeng Gao. (2019)  
**Natural- to formal-language generation using Tensor Product Representations**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/219e09984a2a71f54dbd86c15d31c7b0f53e1837)  
Influential Citation Count (0), SS-ID (219e09984a2a71f54dbd86c15d31c7b0f53e1837)  

**ABSTRACT**  
Generating formal-language represented by relational tuples, such as Lisp programs or mathematical expressions, from a natural-language input is an extremely challenging task because it requires to explicitly capture discrete symbolic structural information from the input to generate the output. Most state-of-the-art neural sequence models do not explicitly capture such structure information, and thus do not perform well on these tasks. In this paper, we propose a new encoder-decoder model based on Tensor Product Representations (TPRs) for Natural- to Formal-language generation, called TP-N2F. The encoder of TP-N2F employs TPR 'binding' to encode natural-language symbolic structure in vector space and the decoder uses TPR 'unbinding' to generate a sequence of relational tuples, each consisting of a relation (or operation) and a number of arguments, in symbolic space. TP-N2F considerably outperforms LSTM-based Seq2Seq models, creating a new state of the art results on two benchmarks: the MathQA dataset for math problem solving, and the AlgoList dataset for program synthesis. Ablation studies show that improvements are mainly attributed to the use of TPRs in both the encoder and decoder to explicitly capture relational structure information for symbolic reasoning.

{{< /ci-details >}}

{{< ci-details summary="Generating Long Sequences with Sparse Transformers (Rewon Child et al., 2019)">}}

Rewon Child, Scott Gray, Alec Radford, Ilya Sutskever. (2019)  
**Generating Long Sequences with Sparse Transformers**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/21da617a0f79aabf94272107184606cefe90ab75)  
Influential Citation Count (79), SS-ID (21da617a0f79aabf94272107184606cefe90ab75)  

**ABSTRACT**  
Transformers are powerful sequence models, but require time and memory that grows quadratically with the sequence length. In this paper we introduce sparse factorizations of the attention matrix which reduce this to $O(n \sqrt{n})$. We also introduce a) a variation on architecture and initialization to train deeper networks, b) the recomputation of attention matrices to save memory, and c) fast attention kernels for training. We call networks with these changes Sparse Transformers, and show they can model sequences tens of thousands of timesteps long using hundreds of layers. We use the same architecture to model images, audio, and text from raw bytes, setting a new state of the art for density modeling of Enwik8, CIFAR-10, and ImageNet-64. We generate unconditional samples that demonstrate global coherence and great diversity, and show it is possible in principle to use self-attention to model sequences of length one million or more.

{{< /ci-details >}}

{{< ci-details summary="Adversarial Training for Large Neural Language Models (Xiaodong Liu et al., 2020)">}}

Xiaodong Liu, Hao Cheng, Pengcheng He, Weizhu Chen, Yu Wang, Hoifung Poon, Jianfeng Gao. (2020)  
**Adversarial Training for Large Neural Language Models**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/2ffcf8352223c95ae8cef4daaec995525ecc926b)  
Influential Citation Count (9), SS-ID (2ffcf8352223c95ae8cef4daaec995525ecc926b)  

**ABSTRACT**  
Generalization and robustness are both key desiderata for designing machine learning methods. Adversarial training can enhance robustness, but past work often finds it hurts generalization. In natural language processing (NLP), pre-training large neural language models such as BERT have demonstrated impressive gain in generalization for a variety of tasks, with further improvement from adversarial fine-tuning. However, these models are still vulnerable to adversarial attacks. In this paper, we show that adversarial pre-training can improve both generalization and robustness. We propose a general algorithm ALUM (Adversarial training for large neural LangUage Models), which regularizes the training objective by applying perturbations in the embedding space that maximizes the adversarial loss. We present the first comprehensive study of adversarial training in all stages, including pre-training from scratch, continual pre-training on a well-trained model, and task-specific fine-tuning. ALUM obtains substantial gains over BERT on a wide range of NLP tasks, in both regular and adversarial scenarios. Even for models that have been well trained on extremely large text corpora, such as RoBERTa, ALUM can still produce significant gains from continual pre-training, whereas conventional non-adversarial methods can not. ALUM can be further combined with task-specific fine-tuning to attain additional gains. The ALUM code is publicly available at this https URL.

{{< /ci-details >}}

{{< ci-details summary="Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer (Colin Raffel et al., 2019)">}}

Colin Raffel, Noam M. Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li, Peter J. Liu. (2019)  
**Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**  
J. Mach. Learn. Res.  
[Paper Link](https://www.semanticscholar.org/paper/3cfb319689f06bf04c2e28399361f414ca32c4b3)  
Influential Citation Count (615), SS-ID (3cfb319689f06bf04c2e28399361f414ca32c4b3)  

**ABSTRACT**  
Transfer learning, where a model is first pre-trained on a data-rich task before being fine-tuned on a downstream task, has emerged as a powerful technique in natural language processing (NLP). The effectiveness of transfer learning has given rise to a diversity of approaches, methodology, and practice. In this paper, we explore the landscape of transfer learning techniques for NLP by introducing a unified framework that converts every language problem into a text-to-text format. Our systematic study compares pre-training objectives, architectures, unlabeled datasets, transfer approaches, and other factors on dozens of language understanding tasks. By combining the insights from our exploration with scale and our new "Colossal Clean Crawled Corpus", we achieve state-of-the-art results on many benchmarks covering summarization, question answering, text classification, and more. To facilitate future work on transfer learning for NLP, we release our dataset, pre-trained models, and code.

{{< /ci-details >}}

{{< ci-details summary="Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity (W. Fedus et al., 2021)">}}

W. Fedus, Barret Zoph, Noam M. Shazeer. (2021)  
**Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/3fd0f34117cf9395130e08c3f02ac2dadcca7206)  
Influential Citation Count (69), SS-ID (3fd0f34117cf9395130e08c3f02ac2dadcca7206)  

**ABSTRACT**  
In deep learning, models typically reuse the same parameters for all inputs. Mixture of Experts (MoE) models defy this and instead select diﬀerent parameters for each incoming example. The result is a sparsely-activated model—with an outrageous number of parameters—but a constant computational cost. However, despite several notable successes of MoE, widespread adoption has been hindered by complexity, communication costs, and training instability. We address these with the introduction of the Switch Transformer. We simplify the MoE routing algorithm and design intuitive improved models with reduced communication and computational costs. Our proposed training techniques mitigate the instabilities, and we show large sparse models may be trained, for the ﬁrst time, with lower precision (bﬂoat16) formats. We design models based oﬀ T5-Base and T5-Large (Raﬀel et al., 2019) to obtain up to 7x increases in pre-training speed with the same computational resources. These improvements extend into multilingual settings where we measure gains over the mT5-Base version across all 101 languages. Finally, we advance the current scale of language models by pre-training up to trillion parameter models on the “Colossal Clean Crawled Corpus”, and achieve a 4x speedup over the T5-XXL model. 1 fourth axis: increase the parameter count while keeping the ﬂoating point operations (FLOPs) per example constant. Our hypothesis is that the parameter count, independent of total computation performed, is a separately important axis on which to scale. We achieve this by designing a sparsely activated model that eﬃciently uses hardware designed for dense matrix multiplications such as GPUs and TPUs. Our work here focuses on TPU architectures, but these class of models may be similarly trained on GPU clusters. In our distributed training setup, our sparsely activated layers split unique weights on diﬀerent devices. Therefore, the weights of the model increase with the number of devices, all while maintaining a manageable memory and computational footprint on each device.

{{< /ci-details >}}

{{< ci-details summary="Fixing Weight Decay Regularization in Adam (I. Loshchilov et al., 2017)">}}

I. Loshchilov, F. Hutter. (2017)  
**Fixing Weight Decay Regularization in Adam**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/45dfef0cc1ed96558c1c650432ce39d6a1050b6a)  
Influential Citation Count (93), SS-ID (45dfef0cc1ed96558c1c650432ce39d6a1050b6a)  

**ABSTRACT**  
We note that common implementations of adaptive gradient algorithms, such as Adam, limit the potential benefit of weight decay regularization, because the weights do not decay multiplicatively (as would be expected for standard weight decay) but by an additive constant factor. We propose a simple way to resolve this issue by decoupling weight decay and the optimization steps taken w.r.t. the loss function. We provide empirical evidence that our proposed modification (i) decouples the optimal choice of weight decay factor from the setting of the learning rate for both standard SGD and Adam, and (ii) substantially improves Adam's generalization performance, allowing it to compete with SGD with momentum on image classification datasets (on which it was previously typically outperformed by the latter). We also demonstrate that longer optimization runs require smaller weight decay values for optimal results and introduce a normalized variant of weight decay to reduce this dependence. Finally, we propose a version of Adam with warm restarts (AdamWR) that has strong anytime performance while achieving state-of-the-art results on CIFAR-10 and ImageNet32x32. Our source code will become available after the review process.

{{< /ci-details >}}

{{< ci-details summary="Automatically Constructing a Corpus of Sentential Paraphrases (W. Dolan et al., 2005)">}}

W. Dolan, Chris Brockett. (2005)  
**Automatically Constructing a Corpus of Sentential Paraphrases**  
IJCNLP  
[Paper Link](https://www.semanticscholar.org/paper/475354f10798f110d34792b6d88f31d6d5cb099e)  
Influential Citation Count (132), SS-ID (475354f10798f110d34792b6d88f31d6d5cb099e)  

**ABSTRACT**  
An obstacle to research in automatic paraphrase identification and generation is the lack of large-scale, publiclyavailable labeled corpora of sentential paraphrases. This paper describes the creation of the recently-released Microsoft Research Paraphrase Corpus, which contains 5801 sentence pairs, each hand-labeled with a binary judgment as to whether the pair constitutes a paraphrase. The corpus was created using heuristic extraction techniques in conjunction with an SVM-based classifier to select likely sentence-level paraphrases from a large corpus of topicclustered news data. These pairs were then submitted to human judges, who confirmed that 67% were in fact semantically equivalent. In addition to describing the corpus itself, we explore a number of issues that arose in defining guidelines for the human raters.

{{< /ci-details >}}

{{< ci-details summary="Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning (Takeru Miyato et al., 2017)">}}

Takeru Miyato, S. Maeda, Masanori Koyama, S. Ishii. (2017)  
**Virtual Adversarial Training: A Regularization Method for Supervised and Semi-Supervised Learning**  
IEEE Transactions on Pattern Analysis and Machine Intelligence  
[Paper Link](https://www.semanticscholar.org/paper/4b1c6f6521da545892f3f5dc39461584d4a27ec0)  
Influential Citation Count (281), SS-ID (4b1c6f6521da545892f3f5dc39461584d4a27ec0)  

**ABSTRACT**  
We propose a new regularization method based on virtual adversarial loss: a new measure of local smoothness of the conditional label distribution given input. Virtual adversarial loss is defined as the robustness of the conditional label distribution around each input data point against local perturbation. Unlike adversarial training, our method defines the adversarial direction without label information and is hence applicable to semi-supervised learning. Because the directions in which we smooth the model are only “virtually” adversarial, we call our method virtual adversarial training (VAT). The computational cost of VAT is relatively low. For neural networks, the approximated gradient of virtual adversarial loss can be computed with no more than two pairs of forward- and back-propagations. In our experiments, we applied VAT to supervised and semi-supervised learning tasks on multiple benchmark datasets. With a simple enhancement of the algorithm based on the entropy minimization principle, our VAT achieves state-of-the-art performance for semi-supervised learning tasks on SVHN and CIFAR-10.

{{< /ci-details >}}

{{< ci-details summary="Know What You Don’t Know: Unanswerable Questions for SQuAD (Pranav Rajpurkar et al., 2018)">}}

Pranav Rajpurkar, Robin Jia, Percy Liang. (2018)  
**Know What You Don’t Know: Unanswerable Questions for SQuAD**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/4d1c856275744c0284312a3a50efb6ca9dc4cd4c)  
Influential Citation Count (339), SS-ID (4d1c856275744c0284312a3a50efb6ca9dc4cd4c)  

**ABSTRACT**  
Extractive reading comprehension systems can often locate the correct answer to a question in a context document, but they also tend to make unreliable guesses on questions for which the correct answer is not stated in the context. Existing datasets either focus exclusively on answerable questions, or use automatically generated unanswerable questions that are easy to identify. To address these weaknesses, we present SQuADRUn, a new dataset that combines the existing Stanford Question Answering Dataset (SQuAD) with over 50,000 unanswerable questions written adversarially by crowdworkers to look similar to answerable ones. To do well on SQuADRUn, systems must not only answer questions when possible, but also determine when no answer is supported by the paragraph and abstain from answering. SQuADRUn is a challenging natural language understanding task for existing models: a strong neural system that gets 86% F1 on SQuAD achieves only 66% F1 on SQuADRUn. We release SQuADRUn to the community as the successor to SQuAD.

{{< /ci-details >}}

{{< ci-details summary="Exploiting Structured Knowledge in Text via Graph-Guided Representation Learning (Tao Shen et al., 2020)">}}

Tao Shen, Yi Mao, Pengcheng He, Guodong Long, Adam Trischler, Weizhu Chen. (2020)  
**Exploiting Structured Knowledge in Text via Graph-Guided Representation Learning**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/4f42a0782f8b25fff62214e70bc43ce88f914c19)  
Influential Citation Count (2), SS-ID (4f42a0782f8b25fff62214e70bc43ce88f914c19)  

**ABSTRACT**  
In this work, we aim at equipping pre-trained language models with structured knowledge. We present two self-supervised tasks learning over raw text with the guidance from knowledge graphs. Building upon entity-level masked language models, our first contribution is an entity masking scheme that exploits relational knowledge underlying the text. This is fulfilled by using a linked knowledge graph to select informative entities and then masking their mentions. In addition we use knowledge graphs to obtain distractors for the masked entities, and propose a novel distractor-suppressed ranking objective which is optimized jointly with masked language model. In contrast to existing paradigms, our approach uses knowledge graphs implicitly, only during pre-training, to inject language models with structured knowledge via learning from raw text. It is more efficient than retrieval-based methods that perform entity linking and integration during finetuning and inference, and generalizes more effectively than the methods that directly learn from concatenated graph triples. Experiments show that our proposed model achieves improved performance on five benchmark datasets, including question answering and knowledge base completion tasks.

{{< /ci-details >}}

{{< ci-details summary="On the Variance of the Adaptive Learning Rate and Beyond (Liyuan Liu et al., 2019)">}}

Liyuan Liu, Haoming Jiang, Pengcheng He, Weizhu Chen, Xiaodong Liu, Jianfeng Gao, Jiawei Han. (2019)  
**On the Variance of the Adaptive Learning Rate and Beyond**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/5759a53418ae3fe74ce96c531617914e7656e45e)  
Influential Citation Count (139), SS-ID (5759a53418ae3fe74ce96c531617914e7656e45e)  

**ABSTRACT**  
The learning rate warmup heuristic achieves remarkable success in stabilizing training, accelerating convergence and improving generalization for adaptive stochastic optimization algorithms like RMSprop and Adam. Here, we study its mechanism in details. Pursuing the theory behind warmup, we identify a problem of the adaptive learning rate (i.e., it has problematically large variance in the early stage), suggest warmup works as a variance reduction technique, and provide both empirical and theoretical evidence to verify our hypothesis. We further propose RAdam, a new variant of Adam, by introducing a term to rectify the variance of the adaptive learning rate. Extensive experimental results on image classification, language modeling, and neural machine translation verify our intuition and demonstrate the effectiveness and robustness of our proposed method. All implementations are available at: this https URL.

{{< /ci-details >}}

{{< ci-details summary="A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference (Adina Williams et al., 2017)">}}

Adina Williams, Nikita Nangia, Samuel R. Bowman. (2017)  
**A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/5ded2b8c64491b4a67f6d39ce473d4b9347a672e)  
Influential Citation Count (438), SS-ID (5ded2b8c64491b4a67f6d39ce473d4b9347a672e)  

**ABSTRACT**  
This paper introduces the Multi-Genre Natural Language Inference (MultiNLI) corpus, a dataset designed for use in the development and evaluation of machine learning models for sentence understanding. At 433k examples, this resource is one of the largest corpora available for natural language inference (a.k.a. recognizing textual entailment), improving upon available resources in both its coverage and difficulty. MultiNLI accomplishes this by offering data from ten distinct genres of written and spoken English, making it possible to evaluate systems on nearly the full complexity of the language, while supplying an explicit setting for evaluating cross-genre domain adaptation. In addition, an evaluation using existing machine learning models designed for the Stanford NLI corpus shows that it represents a substantially more difficult task than does that corpus, despite the two showing similar levels of inter-annotator agreement.

{{< /ci-details >}}

{{< ci-details summary="RACE: Large-scale ReAding Comprehension Dataset From Examinations (Guokun Lai et al., 2017)">}}

Guokun Lai, Qizhe Xie, Hanxiao Liu, Yiming Yang, E. Hovy. (2017)  
**RACE: Large-scale ReAding Comprehension Dataset From Examinations**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/636a79420d838eabe4af7fb25d6437de45ab64e8)  
Influential Citation Count (179), SS-ID (636a79420d838eabe4af7fb25d6437de45ab64e8)  

**ABSTRACT**  
We present RACE, a new dataset for benchmark evaluation of methods in the reading comprehension task. Collected from the English exams for middle and high school Chinese students in the age range between 12 to 18, RACE consists of near 28,000 passages and near 100,000 questions generated by human experts (English instructors), and covers a variety of topics which are carefully designed for evaluating the students’ ability in understanding and reasoning. In particular, the proportion of questions that requires reasoning is much larger in RACE than that in other benchmark datasets for reading comprehension, and there is a significant gap between the performance of the state-of-the-art models (43%) and the ceiling human performance (95%). We hope this new dataset can serve as a valuable resource for research and evaluation in machine comprehension. The dataset is freely available at http://www.cs.cmu.edu/~glai1/data/race/ and the code is available at https://github.com/qizhex/RACE_AR_baselines.

{{< /ci-details >}}

{{< ci-details summary="Multi-Task Deep Neural Networks for Natural Language Understanding (Xiaodong Liu et al., 2019)">}}

Xiaodong Liu, Pengcheng He, Weizhu Chen, Jianfeng Gao. (2019)  
**Multi-Task Deep Neural Networks for Natural Language Understanding**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/658721bc13b0fa97366d38c05a96bf0a9f4bb0ac)  
Influential Citation Count (168), SS-ID (658721bc13b0fa97366d38c05a96bf0a9f4bb0ac)  

**ABSTRACT**  
In this paper, we present a Multi-Task Deep Neural Network (MT-DNN) for learning representations across multiple natural language understanding (NLU) tasks. MT-DNN not only leverages large amounts of cross-task data, but also benefits from a regularization effect that leads to more general representations to help adapt to new tasks and domains. MT-DNN extends the model proposed in Liu et al. (2015) by incorporating a pre-trained bidirectional transformer language model, known as BERT (Devlin et al., 2018). MT-DNN obtains new state-of-the-art results on ten NLU tasks, including SNLI, SciTail, and eight out of nine GLUE tasks, pushing the GLUE benchmark to 82.7% (2.2% absolute improvement) as of February 25, 2019 on the latest GLUE test set. We also demonstrate using the SNLI and SciTail datasets that the representations learned by MT-DNN allow domain adaptation with substantially fewer in-domain labels than the pre-trained BERT representations. Our code and pre-trained models will be made publicly available.

{{< /ci-details >}}

{{< ci-details summary="X-SQL: reinforce schema representation with context (Pengcheng He et al., 2019)">}}

Pengcheng He, Yi Mao, K. Chakrabarti, Weizhu Chen. (2019)  
**X-SQL: reinforce schema representation with context**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/658d6885db65a82d6b2eff926f5c4017bf99c9da)  
Influential Citation Count (11), SS-ID (658d6885db65a82d6b2eff926f5c4017bf99c9da)  

**ABSTRACT**  
In this work, we present X-SQL, a new network architecture for the problem of parsing natural language to SQL query. X-SQL proposes to enhance the structural schema representation with the contextual output from BERT-style pre-training model, and together with type information to learn a new schema representation for down-stream tasks. We evaluated X-SQL on the WikiSQL dataset and show its new state-of-the-art performance.

{{< /ci-details >}}

{{< ci-details summary="Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank (R. Socher et al., 2013)">}}

R. Socher, Alex Perelygin, Jean Wu, Jason Chuang, Christopher D. Manning, A. Ng, Christopher Potts. (2013)  
**Recursive Deep Models for Semantic Compositionality Over a Sentiment Treebank**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/687bac2d3320083eb4530bf18bb8f8f721477600)  
Influential Citation Count (861), SS-ID (687bac2d3320083eb4530bf18bb8f8f721477600)  

**ABSTRACT**  
Semantic word spaces have been very useful but cannot express the meaning of longer phrases in a principled way. Further progress towards understanding compositionality in tasks such as sentiment detection requires richer supervised training and evaluation resources and more powerful models of composition. To remedy this, we introduce a Sentiment Treebank. It includes fine grained sentiment labels for 215,154 phrases in the parse trees of 11,855 sentences and presents new challenges for sentiment compositionality. To address them, we introduce the Recursive Neural Tensor Network. When trained on the new treebank, this model outperforms all previous methods on several metrics. It pushes the state of the art in single sentence positive/negative classification from 80% up to 85.4%. The accuracy of predicting fine-grained sentiment labels for all phrases reaches 80.7%, an improvement of 9.7% over bag of features baselines. Lastly, it is the only model that can accurately capture the effects of negation and its scope at various tree levels for both positive and negative phrases.

{{< /ci-details >}}

{{< ci-details summary="Language Models are Few-Shot Learners (Tom B. Brown et al., 2020)">}}

Tom B. Brown, Benjamin Mann, Nick Ryder, Melanie Subbiah, J. Kaplan, Prafulla Dhariwal, Arvind Neelakantan, Pranav Shyam, Girish Sastry, Amanda Askell, Sandhini Agarwal, Ariel Herbert-Voss, Gretchen Krueger, T. Henighan, Rewon Child, A. Ramesh, Daniel M. Ziegler, Jeff Wu, Clemens Winter, Christopher Hesse, Mark Chen, Eric Sigler, Mateusz Litwin, Scott Gray, Benjamin Chess, Jack Clark, Christopher Berner, Sam McCandlish, Alec Radford, Ilya Sutskever, Dario Amodei. (2020)  
**Language Models are Few-Shot Learners**  
NeurIPS  
[Paper Link](https://www.semanticscholar.org/paper/6b85b63579a916f705a8e10a49bd8d849d91b1fc)  
Influential Citation Count (428), SS-ID (6b85b63579a916f705a8e10a49bd8d849d91b1fc)  

**ABSTRACT**  
Recent work has demonstrated substantial gains on many NLP tasks and benchmarks by pre-training on a large corpus of text followed by fine-tuning on a specific task. While typically task-agnostic in architecture, this method still requires task-specific fine-tuning datasets of thousands or tens of thousands of examples. By contrast, humans can generally perform a new language task from only a few examples or from simple instructions - something which current NLP systems still largely struggle to do. Here we show that scaling up language models greatly improves task-agnostic, few-shot performance, sometimes even reaching competitiveness with prior state-of-the-art fine-tuning approaches. Specifically, we train GPT-3, an autoregressive language model with 175 billion parameters, 10x more than any previous non-sparse language model, and test its performance in the few-shot setting. For all tasks, GPT-3 is applied without any gradient updates or fine-tuning, with tasks and few-shot demonstrations specified purely via text interaction with the model. GPT-3 achieves strong performance on many NLP datasets, including translation, question-answering, and cloze tasks, as well as several tasks that require on-the-fly reasoning or domain adaptation, such as unscrambling words, using a novel word in a sentence, or performing 3-digit arithmetic. At the same time, we also identify some datasets where GPT-3's few-shot learning still struggles, as well as some datasets where GPT-3 faces methodological issues related to training on large web corpora. Finally, we find that GPT-3 can generate samples of news articles which human evaluators have difficulty distinguishing from articles written by humans. We discuss broader societal impacts of this finding and of GPT-3 in general.

{{< /ci-details >}}

{{< ci-details summary="Longformer: The Long-Document Transformer (Iz Beltagy et al., 2020)">}}

Iz Beltagy, Matthew E. Peters, Arman Cohan. (2020)  
**Longformer: The Long-Document Transformer**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/71b6394ad5654f5cd0fba763768ba4e523f7bbca)  
Influential Citation Count (195), SS-ID (71b6394ad5654f5cd0fba763768ba4e523f7bbca)  

**ABSTRACT**  
Transformer-based models are unable to process long sequences due to their self-attention operation, which scales quadratically with the sequence length. To address this limitation, we introduce the Longformer with an attention mechanism that scales linearly with sequence length, making it easy to process documents of thousands of tokens or longer. Longformer's attention mechanism is a drop-in replacement for the standard self-attention and combines a local windowed attention with a task motivated global attention. Following prior work on long-sequence transformers, we evaluate Longformer on character-level language modeling and achieve state-of-the-art results on text8 and enwik8. In contrast to most prior work, we also pretrain Longformer and finetune it on a variety of downstream tasks. Our pretrained Longformer consistently outperforms RoBERTa on long document tasks and sets new state-of-the-art results on WikiHop and TriviaQA. We finally introduce the Longformer-Encoder-Decoder (LED), a Longformer variant for supporting long document generative sequence-to-sequence tasks, and demonstrate its effectiveness on the arXiv summarization dataset.

{{< /ci-details >}}

{{< ci-details summary="ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators (Kevin Clark et al., 2020)">}}

Kevin Clark, Minh-Thang Luong, Quoc V. Le, Christopher D. Manning. (2020)  
**ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/756810258e3419af76aff38c895c20343b0602d0)  
Influential Citation Count (284), SS-ID (756810258e3419af76aff38c895c20343b0602d0)  

**ABSTRACT**  
While masked language modeling (MLM) pre-training methods such as BERT produce excellent results on downstream NLP tasks, they require large amounts of compute to be effective. These approaches corrupt the input by replacing some tokens with [MASK] and then train a model to reconstruct the original tokens. As an alternative, we propose a more sample-efficient pre-training task called replaced token detection. Instead of masking the input, our approach corrupts it by replacing some input tokens with plausible alternatives sampled from a small generator network. Then, instead of training a model that predicts the original identities of the corrupted tokens, we train a discriminative model that predicts whether each token in the corrupted input was replaced by a generator sample or not. Thorough experiments demonstrate this new pre-training task is more efficient than MLM because the model learns from all input tokens rather than just the small subset that was masked out. As a result, the contextual representations learned by our approach substantially outperform the ones learned by methods such as BERT and XLNet given the same model size, data, and compute. The gains are particularly strong for small models; for example, we train a model on one GPU for 4 days that outperforms GPT (trained using 30x more compute) on the GLUE natural language understanding benchmark. Our approach also works well at scale, where we match the performance of RoBERTa, the current state-of-the-art pre-trained transformer, while using less than 1/4 of the compute.

{{< /ci-details >}}

{{< ci-details summary="ALBERT: A Lite BERT for Self-supervised Learning of Language Representations (Zhenzhong Lan et al., 2019)">}}

Zhenzhong Lan, Mingda Chen, Sebastian Goodman, Kevin Gimpel, Piyush Sharma, Radu Soricut. (2019)  
**ALBERT: A Lite BERT for Self-supervised Learning of Language Representations**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/7a064df1aeada7e69e5173f7d4c8606f4470365b)  
Influential Citation Count (573), SS-ID (7a064df1aeada7e69e5173f7d4c8606f4470365b)  

**ABSTRACT**  
Increasing model size when pretraining natural language representations often results in improved performance on downstream tasks. However, at some point further model increases become harder due to GPU/TPU memory limitations and longer training times. To address these problems, we present two parameter-reduction techniques to lower memory consumption and increase the training speed of BERT. Comprehensive empirical evidence shows that our proposed methods lead to models that scale much better compared to the original BERT. We also use a self-supervised loss that focuses on modeling inter-sentence coherence, and show it consistently helps downstream tasks with multi-sentence inputs. As a result, our best model establishes new state-of-the-art results on the GLUE, RACE, and \squad benchmarks while having fewer parameters compared to BERT-large. The code and the pretrained models are available at this https URL.

{{< /ci-details >}}

{{< ci-details summary="SpanBERT: Improving Pre-training by Representing and Predicting Spans (Mandar Joshi et al., 2019)">}}

Mandar Joshi, Danqi Chen, Yinhan Liu, Daniel S. Weld, Luke Zettlemoyer, Omer Levy. (2019)  
**SpanBERT: Improving Pre-training by Representing and Predicting Spans**  
TACL  
[Paper Link](https://www.semanticscholar.org/paper/81f5810fbbab9b7203b9556f4ce3c741875407bc)  
Influential Citation Count (175), SS-ID (81f5810fbbab9b7203b9556f4ce3c741875407bc)  

**ABSTRACT**  
We present SpanBERT, a pre-training method that is designed to better represent and predict spans of text. Our approach extends BERT by (1) masking contiguous random spans, rather than random tokens, and (2) training the span boundary representations to predict the entire content of the masked span, without relying on the individual token representations within it. SpanBERT consistently outperforms BERT and our better-tuned baselines, with substantial gains on span selection tasks such as question answering and coreference resolution. In particular, with the same training data and model size as BERTlarge, our single model obtains 94.6% and 88.7% F1 on SQuAD 1.1 and 2.0 respectively. We also achieve a new state of the art on the OntoNotes coreference resolution task (79.6% F1), strong performance on the TACRED relation extraction benchmark, and even gains on GLUE.1

{{< /ci-details >}}

{{< ci-details summary="Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism (M. Shoeybi et al., 2019)">}}

M. Shoeybi, M. Patwary, Raul Puri, P. LeGresley, J. Casper, Bryan Catanzaro. (2019)  
**Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/8323c591e119eb09b28b29fd6c7bc76bd889df7a)  
Influential Citation Count (70), SS-ID (8323c591e119eb09b28b29fd6c7bc76bd889df7a)  

**ABSTRACT**  
Recent work in language modeling demonstrates that training large transformer models advances the state of the art in Natural Language Processing applications. However, very large models can be quite difficult to train due to memory constraints. In this work, we present our techniques for training very large transformer models and implement a simple, efficient intra-layer model parallel approach that enables training transformer models with billions of parameters. Our approach does not require a new compiler or library changes, is orthogonal and complimentary to pipeline model parallelism, and can be fully implemented with the insertion of a few communication operations in native PyTorch. We illustrate this approach by converging transformer based models up to 8.3 billion parameters using 512 GPUs. We sustain 15.1 PetaFLOPs across the entire application with 76% scaling efficiency when compared to a strong single GPU baseline that sustains 39 TeraFLOPs, which is 30% of peak FLOPs. To demonstrate that large language models can further advance the state of the art (SOTA), we train an 8.3 billion parameter transformer language model similar to GPT-2 and a 3.9 billion parameter model similar to BERT. We show that careful attention to the placement of layer normalization in BERT-like models is critical to achieving increased performance as the model size grows. Using the GPT-2 model we achieve SOTA results on the WikiText103 (10.8 compared to SOTA perplexity of 15.8) and LAMBADA (66.5% compared to SOTA accuracy of 63.2%) datasets. Our BERT model achieves SOTA results on the RACE dataset (90.9% compared to SOTA accuracy of 89.4%).

{{< /ci-details >}}

{{< ci-details summary="GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding (Alex Wang et al., 2018)">}}

Alex Wang, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, Samuel R. Bowman. (2018)  
**GLUE: A Multi-Task Benchmark and Analysis Platform for Natural Language Understanding**  
BlackboxNLP@EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/93b8da28d006415866bf48f9a6e06b5242129195)  
Influential Citation Count (625), SS-ID (93b8da28d006415866bf48f9a6e06b5242129195)  

**ABSTRACT**  
Human ability to understand language is general, flexible, and robust. In contrast, most NLU models above the word level are designed for a specific task and struggle with out-of-domain data. If we aspire to develop models with understanding beyond the detection of superficial correspondences between inputs and outputs, then it is critical to develop a unified model that can execute a range of linguistic tasks across different domains. To facilitate research in this direction, we present the General Language Understanding Evaluation (GLUE, gluebenchmark.com): a benchmark of nine diverse NLU tasks, an auxiliary dataset for probing models for understanding of specific linguistic phenomena, and an online platform for evaluating and comparing models. For some benchmark tasks, training data is plentiful, but for others it is limited or does not match the genre of the test set. GLUE thus favors models that can represent linguistic knowledge in a way that facilitates sample-efficient learning and effective knowledge-transfer across tasks. While none of the datasets in GLUE were created from scratch for the benchmark, four of them feature privately-held test data, which is used to ensure that the benchmark is used fairly. We evaluate baselines that use ELMo (Peters et al., 2018), a powerful transfer learning technique, as well as state-of-the-art sentence representation models. The best models still achieve fairly low absolute scores. Analysis with our diagnostic dataset yields similarly weak performance over all phenomena tested, with some exceptions.

{{< /ci-details >}}

{{< ci-details summary="Language Models are Unsupervised Multitask Learners (Alec Radford et al., 2019)">}}

Alec Radford, Jeff Wu, Rewon Child, D. Luan, Dario Amodei, Ilya Sutskever. (2019)  
**Language Models are Unsupervised Multitask Learners**  
  
[Paper Link](https://www.semanticscholar.org/paper/9405cc0d6169988371b2755e573cc28650d14dfe)  
Influential Citation Count (1306), SS-ID (9405cc0d6169988371b2755e573cc28650d14dfe)  

**ABSTRACT**  
Natural language processing tasks, such as question answering, machine translation, reading comprehension, and summarization, are typically approached with supervised learning on taskspecific datasets. We demonstrate that language models begin to learn these tasks without any explicit supervision when trained on a new dataset of millions of webpages called WebText. When conditioned on a document plus questions, the answers generated by the language model reach 55 F1 on the CoQA dataset matching or exceeding the performance of 3 out of 4 baseline systems without using the 127,000+ training examples. The capacity of the language model is essential to the success of zero-shot task transfer and increasing it improves performance in a log-linear fashion across tasks. Our largest model, GPT-2, is a 1.5B parameter Transformer that achieves state of the art results on 7 out of 8 tested language modeling datasets in a zero-shot setting but still underfits WebText. Samples from the model reflect these improvements and contain coherent paragraphs of text. These findings suggest a promising path towards building language processing systems which learn to perform tasks from their naturally occurring demonstrations.

{{< /ci-details >}}

{{< ci-details summary="Tensor Product Variable Binding and the Representation of Symbolic Structures in Connectionist Systems (Geoffrey E. Hinton, 1991)">}}

Geoffrey E. Hinton. (1991)  
**Tensor Product Variable Binding and the Representation of Symbolic Structures in Connectionist Systems**  
  
[Paper Link](https://www.semanticscholar.org/paper/9438172bfbb74a6a4ea4242b180d4335bb1f18b7)  
Influential Citation Count (52), SS-ID (9438172bfbb74a6a4ea4242b180d4335bb1f18b7)  

**ABSTRACT**  
This chapter contains sections titled: 1. Introduction, 2. Connectionist Representation and Tensor Product Binding: Definition and Examples, 3. Tensor Product Representation: Properties, 4. Conclusion

{{< /ci-details >}}

{{< ci-details summary="Looking Beyond the Surface: A Challenge Set for Reading Comprehension over Multiple Sentences (Daniel Khashabi et al., 2018)">}}

Daniel Khashabi, Snigdha Chaturvedi, Michael Roth, Shyam Upadhyay, D. Roth. (2018)  
**Looking Beyond the Surface: A Challenge Set for Reading Comprehension over Multiple Sentences**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/99ad0533f84c110da2d0713d5798e6e14080b159)  
Influential Citation Count (46), SS-ID (99ad0533f84c110da2d0713d5798e6e14080b159)  

**ABSTRACT**  
We present a reading comprehension challenge in which questions can only be answered by taking into account information from multiple sentences. We solicit and verify questions and answers for this challenge through a 4-step crowdsourcing experiment. Our challenge dataset contains 6,500+ questions for 1000+ paragraphs across 7 different domains (elementary school science, news, travel guides, fiction stories, etc) bringing in linguistic diversity to the texts and to the questions wordings. On a subset of our dataset, we found human solvers to achieve an F1-score of 88.1%. We analyze a range of baselines, including a recent state-of-art reading comprehension system, and demonstrate the difficulty of this challenge, despite a high human performance. The dataset is the first to study multi-sentence inference at scale, with an open-ended set of question types that requires reasoning skills.

{{< /ci-details >}}

{{< ci-details summary="SemEval-2017 Task 1: Semantic Textual Similarity Multilingual and Crosslingual Focused Evaluation (Daniel Matthew Cer et al., 2017)">}}

Daniel Matthew Cer, Mona T. Diab, Eneko Agirre, I. Lopez-Gazpio, Lucia Specia. (2017)  
**SemEval-2017 Task 1: Semantic Textual Similarity Multilingual and Crosslingual Focused Evaluation**  
SemEval@ACL  
[Paper Link](https://www.semanticscholar.org/paper/a23fa96e7217ba0e9405d9e1fe3cdedd57b6e096)  
Influential Citation Count (157), SS-ID (a23fa96e7217ba0e9405d9e1fe3cdedd57b6e096)  

**ABSTRACT**  
Semantic Textual Similarity (STS) measures the meaning similarity of sentences. Applications include machine translation (MT), summarization, generation, question answering (QA), short answer grading, semantic search, dialog and conversational systems. The STS shared task is a venue for assessing the current state-of-the-art. The 2017 task focuses on multilingual and cross-lingual pairs with one sub-track exploring MT quality estimation (MTQE) data. The task obtained strong participation from 31 teams, with 17 participating in all language tracks. We summarize performance and review a selection of well performing methods. Analysis highlights common errors, providing insight into the limitations of existing models. To support ongoing work on semantic representations, the STS Benchmark is introduced as a new shared training and evaluation set carefully selected from the corpus of English STS shared task data (2012-2017).

{{< /ci-details >}}

{{< ci-details summary="ReCoRD: Bridging the Gap between Human and Machine Commonsense Reading Comprehension (Sheng Zhang et al., 2018)">}}

Sheng Zhang, Xiaodong Liu, Jingjing Liu, Jianfeng Gao, Kevin Duh, Benjamin Van Durme. (2018)  
**ReCoRD: Bridging the Gap between Human and Machine Commonsense Reading Comprehension**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/a5b66ee341cb990f7f70a124b5fab3316d3b7e27)  
Influential Citation Count (28), SS-ID (a5b66ee341cb990f7f70a124b5fab3316d3b7e27)  

**ABSTRACT**  
We present a large-scale dataset, ReCoRD, for machine reading comprehension requiring commonsense reasoning. Experiments on this dataset demonstrate that the performance of state-of-the-art MRC systems fall far behind human performance. ReCoRD represents a challenge for future research to bridge the gap between human and machine commonsense reading comprehension. ReCoRD is available at this http URL

{{< /ci-details >}}

{{< ci-details summary="Adam: A Method for Stochastic Optimization (Diederik P. Kingma et al., 2014)">}}

Diederik P. Kingma, Jimmy Ba. (2014)  
**Adam: A Method for Stochastic Optimization**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/a6cb366736791bcccc5c8639de5a8f9636bf87e8)  
Influential Citation Count (14607), SS-ID (a6cb366736791bcccc5c8639de5a8f9636bf87e8)  

**ABSTRACT**  
We introduce Adam, an algorithm for first-order gradient-based optimization of stochastic objective functions, based on adaptive estimates of lower-order moments. The method is straightforward to implement, is computationally efficient, has little memory requirements, is invariant to diagonal rescaling of the gradients, and is well suited for problems that are large in terms of data and/or parameters. The method is also appropriate for non-stationary objectives and problems with very noisy and/or sparse gradients. The hyper-parameters have intuitive interpretations and typically require little tuning. Some connections to related algorithms, on which Adam was inspired, are discussed. We also analyze the theoretical convergence properties of the algorithm and provide a regret bound on the convergence rate that is comparable to the best known results under the online convex optimization framework. Empirical results demonstrate that Adam works well in practice and compares favorably to other stochastic optimization methods. Finally, we discuss AdaMax, a variant of Adam based on the infinity norm.

{{< /ci-details >}}

{{< ci-details summary="WiC: the Word-in-Context Dataset for Evaluating Context-Sensitive Meaning Representations (Mohammad Taher Pilehvar et al., 2018)">}}

Mohammad Taher Pilehvar, José Camacho-Collados. (2018)  
**WiC: the Word-in-Context Dataset for Evaluating Context-Sensitive Meaning Representations**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/a925f818f787e142c5f6bcb7bbd7ede2deb34860)  
Influential Citation Count (7), SS-ID (a925f818f787e142c5f6bcb7bbd7ede2deb34860)  

**ABSTRACT**  
By design, word embeddings are unable to model the dynamic nature of words’ semantics, i.e., the property of words to correspond to potentially different meanings. To address this limitation, dozens of specialized meaning representation techniques such as sense or contextualized embeddings have been proposed. However, despite the popularity of research on this topic, very few evaluation benchmarks exist that specifically focus on the dynamic semantics of words. In this paper we show that existing models have surpassed the performance ceiling of the standard evaluation dataset for the purpose, i.e., Stanford Contextual Word Similarity, and highlight its shortcomings. To address the lack of a suitable benchmark, we put forward a large-scale Word in Context dataset, called WiC, based on annotations curated by experts, for generic evaluation of context-sensitive representations. WiC is released in https://pilehvar.github.io/wic/.

{{< /ci-details >}}

{{< ci-details summary="SMART: Robust and Efficient Fine-Tuning for Pre-trained Natural Language Models through Principled Regularized Optimization (Haoming Jiang et al., 2019)">}}

Haoming Jiang, Pengcheng He, Weizhu Chen, Xiaodong Liu, Jianfeng Gao, T. Zhao. (2019)  
**SMART: Robust and Efficient Fine-Tuning for Pre-trained Natural Language Models through Principled Regularized Optimization**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/ab70853cd5912c470f6ff95e95481980f0a2a41b)  
Influential Citation Count (24), SS-ID (ab70853cd5912c470f6ff95e95481980f0a2a41b)  

**ABSTRACT**  
Transfer learning has fundamentally changed the landscape of natural language processing (NLP). Many state-of-the-art models are first pre-trained on a large text corpus and then fine-tuned on downstream tasks. However, due to limited data resources from downstream tasks and the extremely high complexity of pre-trained models, aggressive fine-tuning often causes the fine-tuned model to overfit the training data of downstream tasks and fail to generalize to unseen data. To address such an issue in a principled manner, we propose a new learning framework for robust and efficient fine-tuning for pre-trained models to attain better generalization performance. The proposed framework contains two important ingredients: 1. Smoothness-inducing regularization, which effectively manages the complexity of the model; 2. Bregman proximal point optimization, which is an instance of trust-region methods and can prevent aggressive updating. Our experiments show that the proposed framework achieves new state-of-the-art performance on a number of NLP tasks including GLUE, SNLI, SciTail and ANLI. Moreover, it also outperforms the state-of-the-art T5 model, which is the largest pre-trained model containing 11 billion parameters, on GLUE.

{{< /ci-details >}}

{{< ci-details summary="Deep Learning Based Text Classification: A Comprehensive Review (Shervin Minaee et al., 2021)">}}

Shervin Minaee, E. Cambria, Jianfeng Gao. (2021)  
**Deep Learning Based Text Classification: A Comprehensive Review**  
  
[Paper Link](https://www.semanticscholar.org/paper/adc61e21eafecfbf6ebecc570f9f913659a2bfb2)  
Influential Citation Count (9), SS-ID (adc61e21eafecfbf6ebecc570f9f913659a2bfb2)  

**ABSTRACT**  
Deep learning basedmodels have surpassed classical machine learning based approaches in various text classification tasks, including sentiment analysis, news categorization, question answering, and natural language inference. In this paper, we provide a comprehensive review of more than 150 deep learning based models for text classification developed in recent years, and discuss their technical contributions, similarities, and strengths. We also provide a summary of more than 40 popular datasets widely used for text classification. Finally, we provide a quantitative analysis of the performance of different deep learning models on popular benchmarks, and discuss future research directions. Additional

{{< /ci-details >}}

{{< ci-details summary="SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference (Rowan Zellers et al., 2018)">}}

Rowan Zellers, Yonatan Bisk, Roy Schwartz, Yejin Choi. (2018)  
**SWAG: A Large-Scale Adversarial Dataset for Grounded Commonsense Inference**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/af5c4b80fbf847f69a202ba5a780a3dd18c1a027)  
Influential Citation Count (78), SS-ID (af5c4b80fbf847f69a202ba5a780a3dd18c1a027)  

**ABSTRACT**  
Given a partial description like “she opened the hood of the car,” humans can reason about the situation and anticipate what might come next (”then, she examined the engine”). In this paper, we introduce the task of grounded commonsense inference, unifying natural language inference and commonsense reasoning. We present SWAG, a new dataset with 113k multiple choice questions about a rich spectrum of grounded situations. To address the recurring challenges of the annotation artifacts and human biases found in many existing datasets, we propose Adversarial Filtering (AF), a novel procedure that constructs a de-biased dataset by iteratively training an ensemble of stylistic classifiers, and using them to filter the data. To account for the aggressive adversarial filtering, we use state-of-the-art language models to massively oversample a diverse set of potential counterfactuals. Empirical results demonstrate that while humans can solve the resulting inference problems with high accuracy (88%), various competitive models struggle on our task. We provide comprehensive analysis that indicates significant opportunities for future research.

{{< /ci-details >}}

{{< ci-details summary="The Third PASCAL Recognizing Textual Entailment Challenge (Danilo Giampiccolo et al., 2007)">}}

Danilo Giampiccolo, B. Magnini, Ido Dagan, W. Dolan. (2007)  
**The Third PASCAL Recognizing Textual Entailment Challenge**  
ACL-PASCAL@ACL  
[Paper Link](https://www.semanticscholar.org/paper/b2815bc4c9e4260227cd7ca0c9d68d41c4c2f58b)  
Influential Citation Count (62), SS-ID (b2815bc4c9e4260227cd7ca0c9d68d41c4c2f58b)  

**ABSTRACT**  


{{< /ci-details >}}

{{< ci-details summary="Transformer-XL: Attentive Language Models beyond a Fixed-Length Context (Zihang Dai et al., 2019)">}}

Zihang Dai, Zhilin Yang, Yiming Yang, J. Carbonell, Quoc V. Le, R. Salakhutdinov. (2019)  
**Transformer-XL: Attentive Language Models beyond a Fixed-Length Context**  
ACL  
[Paper Link](https://www.semanticscholar.org/paper/c4744a7c2bb298e4a52289a1e085c71cc3d37bc6)  
Influential Citation Count (237), SS-ID (c4744a7c2bb298e4a52289a1e085c71cc3d37bc6)  

**ABSTRACT**  
Transformers have a potential of learning longer-term dependency, but are limited by a fixed-length context in the setting of language modeling. We propose a novel neural architecture Transformer-XL that enables learning dependency beyond a fixed length without disrupting temporal coherence. It consists of a segment-level recurrence mechanism and a novel positional encoding scheme. Our method not only enables capturing longer-term dependency, but also resolves the context fragmentation problem. As a result, Transformer-XL learns dependency that is 80% longer than RNNs and 450% longer than vanilla Transformers, achieves better performance on both short and long sequences, and is up to 1,800+ times faster than vanilla Transformers during evaluation. Notably, we improve the state-of-the-art results of bpc/perplexity to 0.99 on enwiki8, 1.08 on text8, 18.3 on WikiText-103, 21.8 on One Billion Word, and 54.5 on Penn Treebank (without finetuning). When trained only on WikiText-103, Transformer-XL manages to generate reasonably coherent, novel text articles with thousands of tokens. Our code, pretrained models, and hyperparameters are available in both Tensorflow and PyTorch.

{{< /ci-details >}}

{{< ci-details summary="Self-Attention with Relative Position Representations (Peter Shaw et al., 2018)">}}

Peter Shaw, Jakob Uszkoreit, Ashish Vaswani. (2018)  
**Self-Attention with Relative Position Representations**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/c8efcc854d97dfc2a42b83316a2109f9d166e43f)  
Influential Citation Count (134), SS-ID (c8efcc854d97dfc2a42b83316a2109f9d166e43f)  

**ABSTRACT**  
Relying entirely on an attention mechanism, the Transformer introduced by Vaswani et al. (2017) achieves state-of-the-art results for machine translation. In contrast to recurrent and convolutional neural networks, it does not explicitly model relative or absolute position information in its structure. Instead, it requires adding representations of absolute positions to its inputs. In this work we present an alternative approach, extending the self-attention mechanism to efficiently consider representations of the relative positions, or distances between sequence elements. On the WMT 2014 English-to-German and English-to-French translation tasks, this approach yields improvements of 1.3 BLEU and 0.3 BLEU over absolute position representations, respectively. Notably, we observe that combining relative and absolute position representations yields no further improvement in translation quality. We describe an efficient implementation of our method and cast it as an instance of relation-aware self-attention mechanisms that can generalize to arbitrary graph-labeled inputs.

{{< /ci-details >}}

{{< ci-details summary="Neural Network Acceptability Judgments (Alex Warstadt et al., 2018)">}}

Alex Warstadt, Amanpreet Singh, Samuel R. Bowman. (2018)  
**Neural Network Acceptability Judgments**  
Transactions of the Association for Computational Linguistics  
[Paper Link](https://www.semanticscholar.org/paper/cb0f3ee1e98faf92429d601cdcd76c69c1e484eb)  
Influential Citation Count (89), SS-ID (cb0f3ee1e98faf92429d601cdcd76c69c1e484eb)  

**ABSTRACT**  
Abstract This paper investigates the ability of artificial neural networks to judge the grammatical acceptability of a sentence, with the goal of testing their linguistic competence. We introduce the Corpus of Linguistic Acceptability (CoLA), a set of 10,657 English sentences labeled as grammatical or ungrammatical from published linguistics literature. As baselines, we train several recurrent neural network models on acceptability classification, and find that our models outperform unsupervised models by Lau et al. (2016) on CoLA. Error-analysis on specific grammatical phenomena reveals that both Lau et al.’s models and ours learn systematic generalizations like subject-verb-object order. However, all models we test perform far below human level on a wide range of grammatical constructions.

{{< /ci-details >}}

{{< ci-details summary="StructBERT: Incorporating Language Structures into Pre-training for Deep Language Understanding (Wei Wang et al., 2019)">}}

Wei Wang, Bin Bi, Ming Yan, Chen Wu, Zuyi Bao, Liwei Peng, Luo Si. (2019)  
**StructBERT: Incorporating Language Structures into Pre-training for Deep Language Understanding**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/d56c1fc337fb07ec004dc846f80582c327af717c)  
Influential Citation Count (21), SS-ID (d56c1fc337fb07ec004dc846f80582c327af717c)  

**ABSTRACT**  
Recently, the pre-trained language model, BERT (and its robustly optimized version RoBERTa), has attracted a lot of attention in natural language understanding (NLU), and achieved state-of-the-art accuracy in various NLU tasks, such as sentiment classification, natural language inference, semantic textual similarity and question answering. Inspired by the linearization exploration work of Elman [8], we extend BERT to a new model, StructBERT, by incorporating language structures into pre-training. Specifically, we pre-train StructBERT with two auxiliary tasks to make the most of the sequential order of words and sentences, which leverage language structures at the word and sentence levels, respectively. As a result, the new model is adapted to different levels of language understanding required by downstream tasks. The StructBERT with structural pre-training gives surprisingly good empirical results on a variety of downstream tasks, including pushing the state-of-the-art on the GLUE benchmark to 89.0 (outperforming all published models), the F1 score on SQuAD v1.1 question answering to 93.0, the accuracy on SNLI to 91.7.

{{< /ci-details >}}

{{< ci-details summary="A Simple Method for Commonsense Reasoning (Trieu H. Trinh et al., 2018)">}}

Trieu H. Trinh, Quoc V. Le. (2018)  
**A Simple Method for Commonsense Reasoning**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/d7b6753a2d4a2b286c396854063bde3a91b75535)  
Influential Citation Count (16), SS-ID (d7b6753a2d4a2b286c396854063bde3a91b75535)  

**ABSTRACT**  
Commonsense reasoning is a long-standing challenge for deep learning. For example, it is difficult to use neural networks to tackle the Winograd Schema dataset (Levesque et al., 2011). In this paper, we present a simple method for commonsense reasoning with neural networks, using unsupervised learning. Key to our method is the use of language models, trained on a massive amount of unlabled data, to score multiple choice questions posed by commonsense reasoning tests. On both Pronoun Disambiguation and Winograd Schema challenges, our models outperform previous state-of-the-art methods by a large margin, without using expensive annotated knowledge bases or hand-engineered features. We train an array of large RNN language models that operate at word or character level on LM-1-Billion, CommonCrawl, SQuAD, Gutenberg Books, and a customized corpus for this task and show that diversity of training data plays an important role in test performance. Further analysis also shows that our system successfully discovers important features of the context that decide the correct answer, indicating a good grasp of commonsense knowledge.

{{< /ci-details >}}

{{< ci-details summary="Enhancing the Transformer with Explicit Relational Encoding for Math Problem Solving (Imanol Schlag et al., 2019)">}}

Imanol Schlag, P. Smolensky, Roland Fernandez, N. Jojic, J. Schmidhuber, Jianfeng Gao. (2019)  
**Enhancing the Transformer with Explicit Relational Encoding for Math Problem Solving**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/d88f31a0091eee02c5a2aa2013914818cdef114e)  
Influential Citation Count (1), SS-ID (d88f31a0091eee02c5a2aa2013914818cdef114e)  

**ABSTRACT**  
We incorporate Tensor-Product Representations within the Transformer in order to better support the explicit representation of relation structure. Our Tensor-Product Transformer (TP-Transformer) sets a new state of the art on the recently-introduced Mathematics Dataset containing 56 categories of free-form math word-problems. The essential component of the model is a novel attention mechanism, called TP-Attention, which explicitly encodes the relations between each Transformer cell and the other cells from which values have been retrieved by attention. TP-Attention goes beyond linear combination of retrieved values, strengthening representation-building and resolving ambiguities introduced by multiple layers of standard attention. The TP-Transformer's attention maps give better insights into how it is capable of solving the Mathematics Dataset's challenging problems. Pretrained models and code will be made available after publication.

{{< /ci-details >}}

{{< ci-details summary="SuperGLUE: A Stickier Benchmark for General-Purpose Language Understanding Systems (Alex Wang et al., 2019)">}}

Alex Wang, Yada Pruksachatkun, Nikita Nangia, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, Samuel R. Bowman. (2019)  
**SuperGLUE: A Stickier Benchmark for General-Purpose Language Understanding Systems**  
NeurIPS  
[Paper Link](https://www.semanticscholar.org/paper/d9f6ada77448664b71128bb19df15765336974a6)  
Influential Citation Count (137), SS-ID (d9f6ada77448664b71128bb19df15765336974a6)  

**ABSTRACT**  
In the last year, new models and methods for pretraining and transfer learning have driven striking performance improvements across a range of language understanding tasks. The GLUE benchmark, introduced a little over one year ago, offers a single-number metric that summarizes progress on a diverse set of such tasks, but performance on the benchmark has recently surpassed the level of non-expert humans, suggesting limited headroom for further research. In this paper we present SuperGLUE, a new benchmark styled after GLUE with a new set of more difficult language understanding tasks, a software toolkit, and a public leaderboard. SuperGLUE is available at this http URL.

{{< /ci-details >}}

{{< ci-details summary="The Sixth PASCAL Recognizing Textual Entailment Challenge (L. Bentivogli et al., 2009)">}}

L. Bentivogli, Peter Clark, Ido Dagan, Danilo Giampiccolo. (2009)  
**The Sixth PASCAL Recognizing Textual Entailment Challenge**  
TAC  
[Paper Link](https://www.semanticscholar.org/paper/db8885a0037fe47d973ade79d696586453710233)  
Influential Citation Count (80), SS-ID (db8885a0037fe47d973ade79d696586453710233)  

**ABSTRACT**  
This paper presents the Sixth Recognizing Textual Entailment (RTE-6) challenge. This year a major innovation was introduced, as the traditional Main Task was replaced by a new task, similar to the RTE-5 Search Pilot, in which Textual Entailment is performed on a real corpus in the Update Summarization scenario. A subtask was also proposed, aimed at detecting novel information. To continue the effort of testing RTE in NLP applications, a KBP Validation Pilot Task was set up, in which RTE systems had to validate the output of systems participating in the KBP Slot Filling Task. Eighteen teams participated in the Main Task (48 submitted runs) and 9 in the Novelty Detection Subtask (22 submitted runs). As for the Pilot, 10 runs were submitted by 3 participants. Finally, the exploratory effort started in RTE-5 to perform resource evaluation through ablation tests was not only reiterated in RTE-6, but also extended to tools.

{{< /ci-details >}}

{{< ci-details summary="The PASCAL Recognising Textual Entailment Challenge (Ido Dagan et al., 2007)">}}

Ido Dagan, Oren Glickman, B. Magnini. (2007)  
**The PASCAL Recognising Textual Entailment Challenge**  
MLCW  
[Paper Link](https://www.semanticscholar.org/paper/de794d50713ea5f91a7c9da3d72041e2f5ef8452)  
Influential Citation Count (229), SS-ID (de794d50713ea5f91a7c9da3d72041e2f5ef8452)  

**ABSTRACT**  
This paper presents the Third PASCAL Recognising Textual Entailment Challenge (RTE-3), providing an overview of the dataset creating methodology and the submitted systems. In creating this year's dataset, a number of longer texts were introduced to make the challenge more oriented to realistic scenarios. Additionally, a pool of resources was offered so that the participants could share common tools. A pilot task was also set up, aimed at differentiating unknown entailments from identified contradictions and providing justifications for overall system decisions. 26 participants submitted 44 runs, using different approaches and generally presenting new entailment models and achieving higher scores than in the previous challenges.

{{< /ci-details >}}

{{< ci-details summary="BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (Jacob Devlin et al., 2019)">}}

Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. (2019)  
**BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding**  
NAACL  
[Paper Link](https://www.semanticscholar.org/paper/df2b0e26d0599ce3e70df8a9da02e51594e0e992)  
Influential Citation Count (9863), SS-ID (df2b0e26d0599ce3e70df8a9da02e51594e0e992)  

**ABSTRACT**  
We introduce a new language representation model called BERT, which stands for Bidirectional Encoder Representations from Transformers. Unlike recent language representation models (Peters et al., 2018a; Radford et al., 2018), BERT is designed to pre-train deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT model can be fine-tuned with just one additional output layer to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial task-specific architecture modifications. BERT is conceptually simple and empirically powerful. It obtains new state-of-the-art results on eleven natural language processing tasks, including pushing the GLUE score to 80.5 (7.7 point absolute improvement), MultiNLI accuracy to 86.7% (4.6% absolute improvement), SQuAD v1.1 question answering Test F1 to 93.2 (1.5 point absolute improvement) and SQuAD v2.0 Test F1 to 83.1 (5.1 point absolute improvement).

{{< /ci-details >}}

{{< ci-details summary="XLNet: Generalized Autoregressive Pretraining for Language Understanding (Zhilin Yang et al., 2019)">}}

Zhilin Yang, Zihang Dai, Yiming Yang, J. Carbonell, R. Salakhutdinov, Quoc V. Le. (2019)  
**XLNet: Generalized Autoregressive Pretraining for Language Understanding**  
NeurIPS  
[Paper Link](https://www.semanticscholar.org/paper/e0c6abdbdecf04ffac65c440da77fb9d66bb474c)  
Influential Citation Count (631), SS-ID (e0c6abdbdecf04ffac65c440da77fb9d66bb474c)  

**ABSTRACT**  
With the capability of modeling bidirectional contexts, denoising autoencoding based pretraining like BERT achieves better performance than pretraining approaches based on autoregressive language modeling. However, relying on corrupting the input with masks, BERT neglects dependency between the masked positions and suffers from a pretrain-finetune discrepancy. In light of these pros and cons, we propose XLNet, a generalized autoregressive pretraining method that (1) enables learning bidirectional contexts by maximizing the expected likelihood over all permutations of the factorization order and (2) overcomes the limitations of BERT thanks to its autoregressive formulation. Furthermore, XLNet integrates ideas from Transformer-XL, the state-of-the-art autoregressive model, into pretraining. Empirically, under comparable experiment settings, XLNet outperforms BERT on 20 tasks, often by a large margin, including question answering, natural language inference, sentiment analysis, and document ranking.

{{< /ci-details >}}

{{< ci-details summary="Small-Bench NLP: Benchmark for small single GPU trained models in Natural Language Processing (Kamal Raj Kanakarajan et al., 2021)">}}

Kamal Raj Kanakarajan, Bhuvana Kundumani, Malaikannan Sankarasubbu. (2021)  
**Small-Bench NLP: Benchmark for small single GPU trained models in Natural Language Processing**  
ArXiv  
[Paper Link](https://www.semanticscholar.org/paper/e762d09783b4cf1fd9907b48b3477eb355dd8690)  
Influential Citation Count (0), SS-ID (e762d09783b4cf1fd9907b48b3477eb355dd8690)  

**ABSTRACT**  
Recent progress in the Natural Language Processing domain has given us several State-ofthe-Art (SOTA) pretrained models which can be finetuned for specific tasks. These large models with billions of parameters trained on numerous GPUs/TPUs over weeks are leading in the benchmark leaderboards. In this paper, we discuss the need for a benchmark for cost and time effective smaller models trained on a single GPU. This will enable researchers with resource constraints experiment with novel and innovative ideas on tokenization, pretraining tasks, architecture, fine tuning methods etc. We set up Small-Bench NLP, a benchmark for small efficient neural language models trained on a single GPU. Small-Bench NLP benchmark comprises of eight NLP tasks on the publicly available GLUE datasets and a leaderboard to track the progress of the community. Our ELECTRA-DeBERTa (15M parameters) small model architecture achieves an average score of 81.53 which is comparable to that of BERT-Base’s 82.20 (110M parameters). Our models, code and leaderboard are available at https://github.com/small

{{< /ci-details >}}

{{< ci-details summary="Pointer Sentinel Mixture Models (Stephen Merity et al., 2016)">}}

Stephen Merity, Caiming Xiong, James Bradbury, R. Socher. (2016)  
**Pointer Sentinel Mixture Models**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/efbd381493bb9636f489b965a2034d529cd56bcd)  
Influential Citation Count (218), SS-ID (efbd381493bb9636f489b965a2034d529cd56bcd)  

**ABSTRACT**  
Recent neural network sequence models with softmax classifiers have achieved their best language modeling performance only with very large hidden states and large vocabularies. Even then they struggle to predict rare or unseen words even if the context makes the prediction unambiguous. We introduce the pointer sentinel mixture architecture for neural sequence models which has the ability to either reproduce a word from the recent context or produce a word from a standard softmax classifier. Our pointer sentinel-LSTM model achieves state of the art language modeling performance on the Penn Treebank (70.9 perplexity) while using far fewer parameters than a standard softmax LSTM. In order to evaluate how well language models can exploit longer contexts and deal with more realistic vocabularies and larger corpora we also introduce the freely available WikiText corpus.

{{< /ci-details >}}

{{< ci-details summary="A Hybrid Neural Network Model for Commonsense Reasoning (Pengcheng He et al., 2019)">}}

Pengcheng He, Xiaodong Liu, Weizhu Chen, Jianfeng Gao. (2019)  
**A Hybrid Neural Network Model for Commonsense Reasoning**  
EMNLP  
[Paper Link](https://www.semanticscholar.org/paper/f5e3990ab9a67f824ef2c28114e2b158d653edca)  
Influential Citation Count (3), SS-ID (f5e3990ab9a67f824ef2c28114e2b158d653edca)  

**ABSTRACT**  
This paper proposes a hybrid neural network(HNN) model for commonsense reasoning. An HNN consists of two component models, a masked language model and a semantic similarity model, which share a BERTbased contextual encoder but use different model-specific input and output layers. HNN obtains new state-of-the-art results on three classic commonsense reasoning tasks, pushing the WNLI benchmark to 89%, the Winograd Schema Challenge (WSC) benchmark to 75.1%, and the PDP60 benchmark to 90.0%. An ablation study shows that language models and semantic similarity models are complementary approaches to commonsense reasoning, and HNN effectively combines the strengths of both. The code and pre-trained models will be publicly available at https: //github.com/namisan/mt-dnn.

{{< /ci-details >}}

{{< ci-details summary="SemEval-2012 Task 7: Choice of Plausible Alternatives: An Evaluation of Commonsense Causal Reasoning (A. Gordon et al., 2011)">}}

A. Gordon, Zornitsa Kozareva, Melissa Roemmele. (2011)  
**SemEval-2012 Task 7: Choice of Plausible Alternatives: An Evaluation of Commonsense Causal Reasoning**  
*SEMEVAL  
[Paper Link](https://www.semanticscholar.org/paper/fb0b11046474b8f1c810f947f313c7c7229a988f)  
Influential Citation Count (56), SS-ID (fb0b11046474b8f1c810f947f313c7c7229a988f)  

**ABSTRACT**  
SemEval-2012 Task 7 presented a deceptively simple challenge: given an English sentence as a premise, select the sentence amongst two alternatives that more plausibly has a causal relation to the premise. In this paper, we describe the development of this task and its motivation. We describe the two systems that competed in this task as part of SemEval-2012, and compare their results to those achieved in previously published research. We discuss the characteristics that make this task so difficult, and offer our thoughts on how progress can be made in the future.

{{< /ci-details >}}

{{< ci-details summary="Music Transformer: Generating Music with Long-Term Structure (Cheng-Zhi Anna Huang et al., 2019)">}}

Cheng-Zhi Anna Huang, Ashish Vaswani, Jakob Uszkoreit, Ian Simon, Curtis Hawthorne, Noam M. Shazeer, Andrew M. Dai, M. Hoffman, Monica Dinculescu, D. Eck. (2019)  
**Music Transformer: Generating Music with Long-Term Structure**  
ICLR  
[Paper Link](https://www.semanticscholar.org/paper/fb507ada871d1e8c29e376dbf7b7879689aa89f9)  
Influential Citation Count (35), SS-ID (fb507ada871d1e8c29e376dbf7b7879689aa89f9)  

**ABSTRACT**  
Music relies heavily on repetition to build structure and meaning. Self-reference occurs on multiple timescales, from motifs to phrases to reusing of entire sections of music, such as in pieces with ABA structure. The Transformer (Vaswani et al., 2017), a sequence model based on self-attention, has achieved compelling results in many generation tasks that require maintaining long-range coherence. This suggests that self-attention might also be well-suited to modeling music. In musical composition and performance, however, relative timing is critically important. Existing approaches for representing relative positional information in the Transformer modulate attention based on pairwise distance (Shaw et al., 2018). This is impractical for long sequences such as musical compositions since their memory complexity for intermediate relative information is quadratic in the sequence length. We propose an algorithm that reduces their intermediate memory requirement to linear in the sequence length. This enables us to demonstrate that a Transformer with our modified relative attention mechanism can generate minutelong compositions (thousands of steps, four times the length modeled in Oore et al. (2018)) with compelling structure, generate continuations that coherently elaborate on a given motif, and in a seq2seq setup generate accompaniments conditioned on melodies1. We evaluate the Transformer with our relative attention mechanism on two datasets, JSB Chorales and Piano-e-Competition, and obtain state-of-the-art results on the latter.

{{< /ci-details >}}

