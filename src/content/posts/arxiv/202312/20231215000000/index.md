---
draft: false
title: "arXiv @ 2023.12.15"
date: 2023-12-15
author: "akitenkrad"
description: ""
tags: ["arXiv", "Published:2023"]
menu:
  sidebar:
    name: "arXiv @ 2023.12.15"
    identifier: arxiv_20231215
    parent: 202312_arxiv
    weight: 10
math: true
---

<figure style="border:none; width:100%; display:flex; justify-content: center">
    <iframe src="pie.html" width=900 height=620 style="border:none"></iframe>
</figure>


## Primary Categories

- [cs.SD (2)](#cssd-2)
- [cs.CV (26)](#cscv-26)
- [cs.LG (23)](#cslg-23)
- [eess.IV (4)](#eessiv-4)
- [eess.AS (3)](#eessas-3)
- [cs.AI (12)](#csai-12)
- [cs.CL (16)](#cscl-16)
- [cs.SE (3)](#csse-3)
- [cs.CY (2)](#cscy-2)
- [cs.DB (2)](#csdb-2)
- [cs.IR (3)](#csir-3)
- [cs.CR (8)](#cscr-8)
- [cs.RO (3)](#csro-3)
- [cs.LO (1)](#cslo-1)
- [cs.SI (1)](#cssi-1)
- [cs.HC (2)](#cshc-2)
- [cs.CE (1)](#csce-1)
- [math.OC (2)](#mathoc-2)
- [quant-ph (2)](#quant-ph-2)
- [cs.NI (1)](#csni-1)
- [eess.SY (1)](#eesssy-1)

## cs.SD (2)



### (1/118) PhasePerturbation: Speech Data Augmentation via Phase Perturbation for Automatic Speech Recognition (Chengxi Lei et al., 2023)

{{<citation>}}

Chengxi Lei, Satwinder Singh, Feng Hou, Xiaoyun Jia, Ruili Wang. (2023)  
**PhasePerturbation: Speech Data Augmentation via Phase Perturbation for Automatic Speech Recognition**  

---
Primary Category: cs.SD  
Categories: cs-AI, cs-SD, cs.SD, eess-AS  
Keywords: Augmentation, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2312.08571v1)  

---


**ABSTRACT**  
Most of the current speech data augmentation methods operate on either the raw waveform or the amplitude spectrum of speech. In this paper, we propose a novel speech data augmentation method called PhasePerturbation that operates dynamically on the phase spectrum of speech. Instead of statically rotating a phase by a constant degree, PhasePerturbation utilizes three dynamic phase spectrum operations, i.e., a randomization operation, a frequency masking operation, and a temporal masking operation, to enhance the diversity of speech data. We conduct experiments on wav2vec2.0 pre-trained ASR models by fine-tuning them with the PhasePerturbation augmented TIMIT corpus. The experimental results demonstrate 10.9\% relative reduction in the word error rate (WER) compared with the baseline model fine-tuned without any augmentation operation. Furthermore, the proposed method achieves additional improvements (12.9\% and 15.9\%) in WER by complementing the Vocal Tract Length Perturbation (VTLP) and the SpecAug, which are both amplitude spectrum-based augmentation methods. The results highlight the capability of PhasePerturbation to improve the current amplitude spectrum-based augmentation methods.

{{</citation>}}


### (2/118) N-Gram Unsupervised Compoundation and Feature Injection for Better Symbolic Music Understanding (Jinhao Tian et al., 2023)

{{<citation>}}

Jinhao Tian, Zuchao Li, Jiajia Li, Ping Wang. (2023)  
**N-Gram Unsupervised Compoundation and Feature Injection for Better Symbolic Music Understanding**  

---
Primary Category: cs.SD  
Categories: 68T07, I-2-7, cs-AI, cs-MM, cs-SD, cs.SD, eess-AS  
Keywords: NLP, Natural Language Processing, Transformer  
[Paper Link](http://arxiv.org/abs/2312.08931v2)  

---


**ABSTRACT**  
The first step to apply deep learning techniques for symbolic music understanding is to transform musical pieces (mainly in MIDI format) into sequences of predefined tokens like note pitch, note velocity, and chords. Subsequently, the sequences are fed into a neural sequence model to accomplish specific tasks. Music sequences exhibit strong correlations between adjacent elements, making them prime candidates for N-gram techniques from Natural Language Processing (NLP). Consider classical piano music: specific melodies might recur throughout a piece, with subtle variations each time. In this paper, we propose a novel method, NG-Midiformer, for understanding symbolic music sequences that leverages the N-gram approach. Our method involves first processing music pieces into word-like sequences with our proposed unsupervised compoundation, followed by using our N-gram Transformer encoder, which can effectively incorporate N-gram information to enhance the primary encoder part for better understanding of music sequences. The pre-training process on large-scale music datasets enables the model to thoroughly learn the N-gram information contained within music sequences, and subsequently apply this information for making inferences during the fine-tuning stage. Experiment on various datasets demonstrate the effectiveness of our method and achieved state-of-the-art performance on a series of music understanding downstream tasks. The code and model weights will be released at https://github.com/CinqueOrigin/NG-Midiformer.

{{</citation>}}


## cs.CV (26)



### (3/118) NViST: In the Wild New View Synthesis from a Single Image with Transformers (Wonbong Jang et al., 2023)

{{<citation>}}

Wonbong Jang, Lourdes Agapito. (2023)  
**NViST: In the Wild New View Synthesis from a Single Image with Transformers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.08568v1)  

---


**ABSTRACT**  
We propose NViST, a transformer-based model for novel-view synthesis from a single image, trained on a large-scale dataset of in-the-wild images with complex backgrounds. NViST transforms image inputs directly into a radiance field, adopting a scalable transformer-based architecture. In practice, NViST exploits the self-supervised features learnt by a masked autoencoder (MAE), and learns a novel decoder that translates features to 3D tokens via cross-attention and adaptive layer normalization. Our model is efficient at inference since only a single forward-pass is needed to predict a 3D representation, unlike methods that require test-time optimization or sampling such as 3D-aware diffusion models. We tackle further limitations of current new-view synthesis models. First, unlike most generative models that are trained in a category-specific manner, often on synthetic datasets or on masked inputs, our model is trained on MVImgNet, a large-scale dataset of real-world, casually-captured videos containing hundreds of object categories with diverse backgrounds. Secondly, our model does not require canonicalization of the training data - i.e. aligning all objects with a frontal view - only needing relative pose at training time which removes a substantial barrier to it being used on casually captured datasets. We show results on unseen objects and categories on MVImgNet and even casual phone captures. We conduct qualitative and quantitative evaluations on MVImgNet and ShapeNet to show that our model represents a step forward towards enabling true in-the-wild novel-view synthesis from a single image.

{{</citation>}}


### (4/118) Vision Transformer-Based Deep Learning for Histologic Classification of Endometrial Cancer (Manu Goyal et al., 2023)

{{<citation>}}

Manu Goyal, Laura J. Tafe, James X. Feng, Kristen E. Muller, Liesbeth Hondelink, Jessica L. Bentz, Saeed Hassanpour. (2023)  
**Vision Transformer-Based Deep Learning for Histologic Classification of Endometrial Cancer**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.08479v1)  

---


**ABSTRACT**  
Endometrial cancer, the sixth most common cancer in females worldwide, presents as a heterogeneous group with certain types prone to recurrence. Precise histologic evaluation of endometrial cancer is essential for effective patient management and determining the best treatment modalities. This study introduces EndoNet, a transformer-based deep learning approach for histologic classification of endometrial cancer. EndoNet uses convolutional neural networks for extracting histologic features and a vision transformer for aggregating these features and classifying slides based on their visual characteristics. The model was trained on 929 digitized hematoxylin and eosin-stained whole slide images of endometrial cancer from hysterectomy cases at Dartmouth Health. It classifies these slides into low grade (Endometroid Grades 1 and 2) and high-grade (endometroid carcinoma FIGO grade 3, uterine serous carcinoma, carcinosarcoma) categories. EndoNet was evaluated on an internal test set of 218 slides and an external test set of 100 random slides from the public TCGA database. The model achieved a weighted average F1-score of 0.92 (95% CI: 0.87-0.95) and an AUC of 0.93 (95% CI: 0.88-0.96) on the internal test, and 0.86 (95% CI: 0.80-0.94) for F1-score and 0.86 (95% CI: 0.75-0.93) for AUC on the external test. Pending further validation, EndoNet has the potential to assist pathologists in classifying challenging gynecologic pathology tumors and enhancing patient care.

{{</citation>}}


### (5/118) PTT: Point-Trajectory Transformer for Efficient Temporal 3D Object Detection (Kuan-Chih Huang et al., 2023)

{{<citation>}}

Kuan-Chih Huang, Weijie Lyu, Ming-Hsuan Yang, Yi-Hsuan Tsai. (2023)  
**PTT: Point-Trajectory Transformer for Efficient Temporal 3D Object Detection**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection, Transformer  
[Paper Link](http://arxiv.org/abs/2312.08371v1)  

---


**ABSTRACT**  
Recent temporal LiDAR-based 3D object detectors achieve promising performance based on the two-stage proposal-based approach. They generate 3D box candidates from the first-stage dense detector, followed by different temporal aggregation methods. However, these approaches require per-frame objects or whole point clouds, posing challenges related to memory bank utilization. Moreover, point clouds and trajectory features are combined solely based on concatenation, which may neglect effective interactions between them. In this paper, we propose a point-trajectory transformer with long short-term memory for efficient temporal 3D object detection. To this end, we only utilize point clouds of current-frame objects and their historical trajectories as input to minimize the memory bank storage requirement. Furthermore, we introduce modules to encode trajectory features, focusing on long short-term and future-aware perspectives, and then effectively aggregate them with point cloud features. We conduct extensive experiments on the large-scale Waymo dataset to demonstrate that our approach performs well against state-of-the-art methods. Code and models will be made publicly available at https://github.com/kuanchihhuang/PTT.

{{</citation>}}


### (6/118) VLAP: Efficient Video-Language Alignment via Frame Prompting and Distilling for Video Question Answering (Xijun Wang et al., 2023)

{{<citation>}}

Xijun Wang, Junbang Liang, Chun-Kai Wang, Kenan Deng, Yu Lou, Ming Lin, Shan Yang. (2023)  
**VLAP: Efficient Video-Language Alignment via Frame Prompting and Distilling for Video Question Answering**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2312.08367v1)  

---


**ABSTRACT**  
In this work, we propose an efficient Video-Language Alignment via Frame-Prompting and Distilling (VLAP) network. Our VLAP model addresses both efficient frame sampling and effective cross-modal alignment in a unified way. In our VLAP network, we design a new learnable question-aware Frame-Prompter together with a new cross-modal distillation (QFormer-Distiller) module. Pre-trained large image-language models have shown promising results on problems such as visual question answering. However, how to efficiently and effectively sample image frames when adapting pre-trained large image-language model to video-language alignment is still the major challenge. Compared with prior work, our VLAP model demonstrates the capability of selecting key frames with critical contents, thus improving the video-language alignment accuracy while reducing the inference latency (+3.3% on NExT-QA Temporal with 3.0X speed up). Overall, our VLAP network outperforms (e.g. +4.6% on STAR Interaction and +2.2% on STAR average with 3.0X speed up, ours 2-frames out-perform SeViLA 4-frames on VLEP with 4.2X speed up) the state-of-the-art methods on the video question-answering benchmarks.

{{</citation>}}


### (7/118) Efficient Multi-Object Pose Estimation using Multi-Resolution Deformable Attention and Query Aggregation (Arul Selvam Periyasamy et al., 2023)

{{<citation>}}

Arul Selvam Periyasamy, Vladimir Tsaturyan, Sven Behnke. (2023)  
**Efficient Multi-Object Pose Estimation using Multi-Resolution Deformable Attention and Query Aggregation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.08268v1)  

---


**ABSTRACT**  
Object pose estimation is a long-standing problem in computer vision. Recently, attention-based vision transformer models have achieved state-of-the-art results in many computer vision applications. Exploiting the permutation-invariant nature of the attention mechanism, a family of vision transformer models formulate multi-object pose estimation as a set prediction problem. However, existing vision transformer models for multi-object pose estimation rely exclusively on the attention mechanism. Convolutional neural networks, on the other hand, hard-wire various inductive biases into their architecture. In this paper, we investigate incorporating inductive biases in vision transformer models for multi-object pose estimation, which facilitates learning long-range dependencies while circumventing the costly global attention. In particular, we use multi-resolution deformable attention, where the attention operation is performed only between a few deformed reference points. Furthermore, we propose a query aggregation mechanism that enables increasing the number of object queries without increasing the computational complexity. We evaluate the proposed model on the challenging YCB-Video dataset and report state-of-the-art results.

{{</citation>}}


### (8/118) Partial Symmetry Detection for 3D Geometry using Contrastive Learning with Geodesic Point Cloud Patches (Gregor Kobsik et al., 2023)

{{<citation>}}

Gregor Kobsik, Isaak Lim, Leif Kobbelt. (2023)  
**Partial Symmetry Detection for 3D Geometry using Contrastive Learning with Geodesic Point Cloud Patches**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.08230v1)  

---


**ABSTRACT**  
Symmetry detection, especially partial and extrinsic symmetry, is essential for various downstream tasks, like 3D geometry completion, segmentation, compression and structure-aware shape encoding or generation. In order to detect partial extrinsic symmetries, we propose to learn rotation, reflection, translation and scale invariant local shape features for geodesic point cloud patches via contrastive learning, which are robust across multiple classes and generalize over different datasets. We show that our approach is able to extract multiple valid solutions for this ambiguous problem. Furthermore, we introduce a novel benchmark test for partial extrinsic symmetry detection to evaluate our method. Lastly, we incorporate the detected symmetries together with a region growing algorithm to demonstrate a downstream task with the goal of computing symmetry-aware partitions of 3D shapes. To our knowledge, we are the first to propose a self-supervised data-driven method for partial extrinsic symmetry detection.

{{</citation>}}


### (9/118) Patch-wise Graph Contrastive Learning for Image Translation (Chanyong Jung et al., 2023)

{{<citation>}}

Chanyong Jung, Gihyun Kwon, Jong Chul Ye. (2023)  
**Patch-wise Graph Contrastive Learning for Image Translation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.08223v1)  

---


**ABSTRACT**  
Recently, patch-wise contrastive learning is drawing attention for the image translation by exploring the semantic correspondence between the input and output images. To further explore the patch-wise topology for high-level semantic understanding, here we exploit the graph neural network to capture the topology-aware features. Specifically, we construct the graph based on the patch-wise similarity from a pretrained encoder, whose adjacency matrix is shared to enhance the consistency of patch-wise relation between the input and the output. Then, we obtain the node feature from the graph neural network, and enhance the correspondence between the nodes by increasing mutual information using the contrastive loss. In order to capture the hierarchical semantic structure, we further propose the graph pooling. Experimental results demonstrate the state-of-art results for the image translation thanks to the semantic encoding by the constructed graphs.

{{</citation>}}


### (10/118) LAMM: Label Alignment for Multi-Modal Prompt Learning (Jingsheng Gao et al., 2023)

{{<citation>}}

Jingsheng Gao, Jiacheng Ruan, Suncheng Xiang, Zefang Yu, Ke Ji, Mingye Xie, Ting Liu, Yuzhuo Fu. (2023)  
**LAMM: Label Alignment for Multi-Modal Prompt Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2312.08212v1)  

---


**ABSTRACT**  
With the success of pre-trained visual-language (VL) models such as CLIP in visual representation tasks, transferring pre-trained models to downstream tasks has become a crucial paradigm. Recently, the prompt tuning paradigm, which draws inspiration from natural language processing (NLP), has made significant progress in VL field. However, preceding methods mainly focus on constructing prompt templates for text and visual inputs, neglecting the gap in class label representations between the VL models and downstream tasks. To address this challenge, we introduce an innovative label alignment method named \textbf{LAMM}, which can dynamically adjust the category embeddings of downstream datasets through end-to-end training. Moreover, to achieve a more appropriate label distribution, we propose a hierarchical loss, encompassing the alignment of the parameter space, feature space, and logits space. We conduct experiments on 11 downstream vision datasets and demonstrate that our method significantly improves the performance of existing multi-modal prompt learning models in few-shot scenarios, exhibiting an average accuracy improvement of 2.31(\%) compared to the state-of-the-art methods on 16 shots. Moreover, our methodology exhibits the preeminence in continual learning compared to other prompt tuning methods. Importantly, our method is synergistic with existing prompt tuning methods and can boost the performance on top of them. Our code and dataset will be publicly available at https://github.com/gaojingsheng/LAMM.

{{</citation>}}


### (11/118) PAD: Self-Supervised Pre-Training with Patchwise-Scale Adapter for Infrared Images (Tao Zhang et al., 2023)

{{<citation>}}

Tao Zhang, Kun Ding, Jinyong Wen, Yu Xiong, Zeyu Zhang, Shiming Xiang, Chunhong Pan. (2023)  
**PAD: Self-Supervised Pre-Training with Patchwise-Scale Adapter for Infrared Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2312.08192v1)  

---


**ABSTRACT**  
Self-supervised learning (SSL) for RGB images has achieved significant success, yet there is still limited research on SSL for infrared images, primarily due to three prominent challenges: 1) the lack of a suitable large-scale infrared pre-training dataset, 2) the distinctiveness of non-iconic infrared images rendering common pre-training tasks like masked image modeling (MIM) less effective, and 3) the scarcity of fine-grained textures making it particularly challenging to learn general image features. To address these issues, we construct a Multi-Scene Infrared Pre-training (MSIP) dataset comprising 178,756 images, and introduce object-sensitive random RoI cropping, an image preprocessing method, to tackle the challenge posed by non-iconic images. To alleviate the impact of weak textures on feature learning, we propose a pre-training paradigm called Pre-training with ADapter (PAD), which uses adapters to learn domain-specific features while freezing parameters pre-trained on ImageNet to retain the general feature extraction capability. This new paradigm is applicable to any transformer-based SSL method. Furthermore, to achieve more flexible coordination between pre-trained and newly-learned features in different layers and patches, a patchwise-scale adapter with dynamically learnable scale factors is introduced. Extensive experiments on three downstream tasks show that PAD, with only 1.23M pre-trainable parameters, outperforms other baseline paradigms including continual full pre-training on MSIP. Our code and dataset are available at https://github.com/casiatao/PAD.

{{</citation>}}


### (12/118) Chat-3D v2: Bridging 3D Scene and Large Language Models with Object Identifiers (Haifeng Huang et al., 2023)

{{<citation>}}

Haifeng Huang, Zehan Wang, Rongjie Huang, Luping Liu, Xize Cheng, Yang Zhao, Tao Jin, Zhou Zhao. (2023)  
**Chat-3D v2: Bridging 3D Scene and Large Language Models with Object Identifiers**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: GPT, GPT-4, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.08168v2)  

---


**ABSTRACT**  
Recent research has evidenced the significant potentials of Large Language Models (LLMs) in handling challenging tasks within 3D scenes. However, current models are constrained to addressing object-centric tasks, where each question-answer pair focuses solely on an individual object. In real-world applications, users may pose queries involving multiple objects or expect for answers that precisely reference various objects. We introduce the use of object identifiers to freely reference objects during a conversation. While this solution appears straightforward, it presents two main challenges: 1) How to establish a reliable one-to-one correspondence between each object and its identifier? 2) How to incorporate complex spatial relationships among dozens of objects into the embedding space of the LLM? To address these challenges, we propose a two-stage alignment method, which involves learning an attribute-aware token and a relation-aware token for each object. These tokens capture the object's attributes and spatial relationships with surrounding objects in the 3D scene. Once the alignment is established, we can fine-tune our model on various downstream tasks using instruction tuning. Experiments conducted on traditional datasets like ScanQA, ScanRefer, and Nr3D/Sr3D showcase the effectiveness of our proposed method. Additionally, we create a 3D scene captioning dataset annotated with rich object identifiers, with the assistant of GPT-4. This dataset aims to further explore the capability of object identifiers in effective object referencing and precise scene understanding.

{{</citation>}}


### (13/118) Mono3DVG: 3D Visual Grounding in Monocular Images (Yang Zhan et al., 2023)

{{<citation>}}

Yang Zhan, Yuan Yuan, Zhitong Xiong. (2023)  
**Mono3DVG: 3D Visual Grounding in Monocular Images**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ChatGPT, GPT  
[Paper Link](http://arxiv.org/abs/2312.08022v1)  

---


**ABSTRACT**  
We introduce a novel task of 3D visual grounding in monocular RGB images using language descriptions with both appearance and geometry information. Specifically, we build a large-scale dataset, Mono3DRefer, which contains 3D object targets with their corresponding geometric text descriptions, generated by ChatGPT and refined manually. To foster this task, we propose Mono3DVG-TR, an end-to-end transformer-based network, which takes advantage of both the appearance and geometry information in text embeddings for multi-modal learning and 3D object localization. Depth predictor is designed to explicitly learn geometry features. The dual text-guided adapter is proposed to refine multiscale visual and geometry features of the referred object. Based on depth-text-visual stacking attention, the decoder fuses object-level geometric cues and visual appearance into a learnable query. Comprehensive benchmarks and some insightful analyses are provided for Mono3DVG. Extensive comparisons and ablation studies show that our method significantly outperforms all baselines. The dataset and code will be publicly available at: https://github.com/ZhanYang-nwpu/Mono3DVG.

{{</citation>}}


### (14/118) AdapEdit: Spatio-Temporal Guided Adaptive Editing Algorithm for Text-Based Continuity-Sensitive Image Editing (Zhiyuan Ma et al., 2023)

{{<citation>}}

Zhiyuan Ma, Guoli Jia, Bowen Zhou. (2023)  
**AdapEdit: Spatio-Temporal Guided Adaptive Editing Algorithm for Text-Based Continuity-Sensitive Image Editing**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08019v1)  

---


**ABSTRACT**  
With the great success of text-conditioned diffusion models in creative text-to-image generation, various text-driven image editing approaches have attracted the attentions of many researchers. However, previous works mainly focus on discreteness-sensitive instructions such as adding, removing or replacing specific objects, background elements or global styles (i.e., hard editing), while generally ignoring subject-binding but semantically fine-changing continuity-sensitive instructions such as actions, poses or adjectives, and so on (i.e., soft editing), which hampers generative AI from generating user-customized visual contents. To mitigate this predicament, we propose a spatio-temporal guided adaptive editing algorithm AdapEdit, which realizes adaptive image editing by introducing a soft-attention strategy to dynamically vary the guiding degree from the editing conditions to visual pixels from both temporal and spatial perspectives. Note our approach has a significant advantage in preserving model priors and does not require model training, fine-tuning, extra data, or optimization. We present our results over a wide variety of raw images and editing instructions, demonstrating competitive performance and showing it significantly outperforms the previous approaches.

{{</citation>}}


### (15/118) Semi-Supervised Class-Agnostic Motion Prediction with Pseudo Label Regeneration and BEVMix (Kewei Wang et al., 2023)

{{<citation>}}

Kewei Wang, Yizheng Wu, Zhiyu Pan, Xingyi Li, Ke Xian, Zhe Wang, Zhiguo Cao, Guosheng Lin. (2023)  
**Semi-Supervised Class-Agnostic Motion Prediction with Pseudo Label Regeneration and BEVMix**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2312.08009v2)  

---


**ABSTRACT**  
Class-agnostic motion prediction methods aim to comprehend motion within open-world scenarios, holding significance for autonomous driving systems. However, training a high-performance model in a fully-supervised manner always requires substantial amounts of manually annotated data, which can be both expensive and time-consuming to obtain. To address this challenge, our study explores the potential of semi-supervised learning (SSL) for class-agnostic motion prediction. Our SSL framework adopts a consistency-based self-training paradigm, enabling the model to learn from unlabeled data by generating pseudo labels through test-time inference. To improve the quality of pseudo labels, we propose a novel motion selection and re-generation module. This module effectively selects reliable pseudo labels and re-generates unreliable ones. Furthermore, we propose two data augmentation strategies: temporal sampling and BEVMix. These strategies facilitate consistency regularization in SSL. Experiments conducted on nuScenes demonstrate that our SSL method can surpass the self-supervised approach by a large margin by utilizing only a tiny fraction of labeled data. Furthermore, our method exhibits comparable performance to weakly and some fully supervised methods. These results highlight the ability of our method to strike a favorable balance between annotation costs and performance. Code will be available at https://github.com/kwwcv/SSMP.

{{</citation>}}


### (16/118) Instance-aware Multi-Camera 3D Object Detection with Structural Priors Mining and Self-Boosting Learning (Yang Jiao et al., 2023)

{{<citation>}}

Yang Jiao, Zequn Jie, Shaoxiang Chen, Lechao Cheng, Jingjing Chen, Lin Ma, Yu-Gang Jiang. (2023)  
**Instance-aware Multi-Camera 3D Object Detection with Structural Priors Mining and Self-Boosting Learning**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2312.08004v1)  

---


**ABSTRACT**  
Camera-based bird-eye-view (BEV) perception paradigm has made significant progress in the autonomous driving field. Under such a paradigm, accurate BEV representation construction relies on reliable depth estimation for multi-camera images. However, existing approaches exhaustively predict depths for every pixel without prioritizing objects, which are precisely the entities requiring detection in the 3D space. To this end, we propose IA-BEV, which integrates image-plane instance awareness into the depth estimation process within a BEV-based detector. First, a category-specific structural priors mining approach is proposed for enhancing the efficacy of monocular depth generation. Besides, a self-boosting learning strategy is further proposed to encourage the model to place more emphasis on challenging objects in computation-expensive temporal stereo matching. Together they provide advanced depth estimation results for high-quality BEV features construction, benefiting the ultimate 3D detection. The proposed method achieves state-of-the-art performances on the challenging nuScenes benchmark, and extensive experimental results demonstrate the effectiveness of our designs.

{{</citation>}}


### (17/118) Challenges of YOLO Series for Object Detection in Extremely Heavy Rain: CALRA Simulator based Synthetic Evaluation Dataset (T. Kim et al., 2023)

{{<citation>}}

T. Kim, H. Jeon, Y. Lim. (2023)  
**Challenges of YOLO Series for Object Detection in Extremely Heavy Rain: CALRA Simulator based Synthetic Evaluation Dataset**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Object Detection  
[Paper Link](http://arxiv.org/abs/2312.07976v2)  

---


**ABSTRACT**  
Recently, as many studies of autonomous vehicles have been achieved for levels 4 and 5, there has been also increasing interest in the advancement of perception, decision, and control technologies, which are the three major aspects of autonomous vehicles. As for the perception technologies achieving reliable maneuvering of autonomous vehicles, object detection by using diverse sensors (e.g., LiDAR, radar, and camera) should be prioritized. These sensors require to detect objects accurately and quickly in diverse weather conditions, but they tend to have challenges to consistently detect objects in bad weather conditions with rain, snow, or fog. Thus, in this study, based on the experimentally obtained raindrop data from precipitation conditions, we constructed a novel dataset that could test diverse network model in various precipitation conditions through the CARLA simulator. Consequently, based on our novel dataset, YOLO series, a one-stage-detector, was used to quantitatively verify how much object detection performance could be decreased under various precipitation conditions from normal to extreme heavy rain situations.

{{</citation>}}


### (18/118) Divide and Conquer: Hybrid Pre-training for Person Search (Yanling Tian et al., 2023)

{{<citation>}}

Yanling Tian, Di Chen, Yunan Liu, Jian Yang, Shanshan Zhang. (2023)  
**Divide and Conquer: Hybrid Pre-training for Person Search**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: ImageNet  
[Paper Link](http://arxiv.org/abs/2312.07970v1)  

---


**ABSTRACT**  
Large-scale pre-training has proven to be an effective method for improving performance across different tasks. Current person search methods use ImageNet pre-trained models for feature extraction, yet it is not an optimal solution due to the gap between the pre-training task and person search task (as a downstream task). Therefore, in this paper, we focus on pre-training for person search, which involves detecting and re-identifying individuals simultaneously. Although labeled data for person search is scarce, datasets for two sub-tasks person detection and re-identification are relatively abundant. To this end, we propose a hybrid pre-training framework specifically designed for person search using sub-task data only. It consists of a hybrid learning paradigm that handles data with different kinds of supervisions, and an intra-task alignment module that alleviates domain discrepancy under limited resources. To the best of our knowledge, this is the first work that investigates how to support full-task pre-training using sub-task data. Extensive experiments demonstrate that our pre-trained model can achieve significant improvements across diverse protocols, such as person search method, fine-tuning data, pre-training data and model backbone. For example, our model improves ResNet50 based NAE by 10.3% relative improvement w.r.t. mAP. Our code and pre-trained models are released for plug-and-play usage to the person search community.

{{</citation>}}


### (19/118) ASLseg: Adapting SAM in the Loop for Semi-supervised Liver Tumor Segmentation (Shiyun Chen et al., 2023)

{{<citation>}}

Shiyun Chen, Li Lin, Pujin Cheng, Xiaoying Tang. (2023)  
**ASLseg: Adapting SAM in the Loop for Semi-supervised Liver Tumor Segmentation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Semi-Supervised  
[Paper Link](http://arxiv.org/abs/2312.07969v1)  

---


**ABSTRACT**  
Liver tumor segmentation is essential for computer-aided diagnosis, surgical planning, and prognosis evaluation. However, obtaining and maintaining a large-scale dataset with dense annotations is challenging. Semi-Supervised Learning (SSL) is a common technique to address these challenges. Recently, Segment Anything Model (SAM) has shown promising performance in some medical image segmentation tasks, but it performs poorly for liver tumor segmentation. In this paper, we propose a novel semi-supervised framework, named ASLseg, which can effectively adapt the SAM to the SSL setting and combine both domain-specific and general knowledge of liver tumors. Specifically, the segmentation model trained with a specific SSL paradigm provides the generated pseudo-labels as prompts to the fine-tuned SAM. An adaptation network is then used to refine the SAM-predictions and generate higher-quality pseudo-labels. Finally, the reliable pseudo-labels are selected to expand the labeled set for iterative training. Extensive experiments on the LiTS dataset demonstrate overwhelming performance of our ASLseg.

{{</citation>}}


### (20/118) Erasing Self-Supervised Learning Backdoor by Cluster Activation Masking (Shengsheng Qian et al., 2023)

{{<citation>}}

Shengsheng Qian, Yifei Wang, Dizhan Xue, Shengjie Zhang, Huaiwen Zhang, Changsheng Xu. (2023)  
**Erasing Self-Supervised Learning Backdoor by Cluster Activation Masking**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CR, cs-CV, cs-LG, cs.CV  
Keywords: ImageNet, Self-Supervised  
[Paper Link](http://arxiv.org/abs/2312.07955v1)  

---


**ABSTRACT**  
Researchers have recently found that Self-Supervised Learning (SSL) is vulnerable to backdoor attacks. The attacker can embed hidden SSL backdoors via a few poisoned examples in the training dataset and maliciously manipulate the behavior of downstream models. To defend against SSL backdoor attacks, a feasible route is to detect and remove the poisonous samples in the training set. However, the existing SSL backdoor defense method fails to detect the poisonous samples precisely. In this paper, we propose to erase the SSL backdoor by cluster activation masking and propose a novel PoisonCAM method. After obtaining the threat model trained on the poisoned dataset, our method can precisely detect poisonous samples based on the assumption that masking the backdoor trigger can effectively change the activation of a downstream clustering model. In experiments, our PoisonCAM achieves 96% accuracy for backdoor trigger detection compared to 3% of the state-of-the-art method on poisoned ImageNet-100. Moreover, our proposed PoisonCAM significantly improves the performance of the trained SSL model under backdoor attacks compared to the state-of-the-art method. Our code will be available at https://github.com/LivXue/PoisonCAM.

{{</citation>}}


### (21/118) Semantic-aware Data Augmentation for Text-to-image Synthesis (Zhaorui Tan et al., 2023)

{{<citation>}}

Zhaorui Tan, Xi Yang, Kaizhu Huang. (2023)  
**Semantic-aware Data Augmentation for Text-to-image Synthesis**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Augmentation  
[Paper Link](http://arxiv.org/abs/2312.07951v1)  

---


**ABSTRACT**  
Data augmentation has been recently leveraged as an effective regularizer in various vision-language deep neural networks. However, in text-to-image synthesis (T2Isyn), current augmentation wisdom still suffers from the semantic mismatch between augmented paired data. Even worse, semantic collapse may occur when generated images are less semantically constrained. In this paper, we develop a novel Semantic-aware Data Augmentation (SADA) framework dedicated to T2Isyn. In particular, we propose to augment texts in the semantic space via an Implicit Textual Semantic Preserving Augmentation ($ITA$), in conjunction with a specifically designed Image Semantic Regularization Loss ($L_r$) as Generated Image Semantic Conservation, to cope well with semantic mismatch and collapse. As one major contribution, we theoretically show that $ITA$ can certify better text-image consistency while $L_r$ regularizing the semantics of generated images would avoid semantic collapse and enhance image quality. Extensive experiments validate that SADA enhances text-image consistency and improves image quality significantly in T2Isyn models across various backbones. Especially, incorporating SADA during the tuning process of Stable Diffusion models also yields performance improvements.

{{</citation>}}


### (22/118) Polar-Doc: One-Stage Document Dewarping with Multi-Scope Constraints under Polar Representation (Weiguang Zhang et al., 2023)

{{<citation>}}

Weiguang Zhang, Qiufeng Wang, Kaizhu Huang. (2023)  
**Polar-Doc: One-Stage Document Dewarping with Multi-Scope Constraints under Polar Representation**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: OCR  
[Paper Link](http://arxiv.org/abs/2312.07925v1)  

---


**ABSTRACT**  
Document dewarping, aiming to eliminate geometric deformation in photographed documents to benefit text recognition, has made great progress in recent years but is still far from being solved. While Cartesian coordinates are typically leveraged by state-of-the-art approaches to learn a group of deformation control points, such representation is not efficient for dewarping model to learn the deformation information. In this work, we explore Polar coordinates representation for each point in document dewarping, namely Polar-Doc. In contrast to most current works adopting a two-stage pipeline typically, Polar representation enables a unified point regression framework for both segmentation and dewarping network in one single stage. Such unification makes the whole model more efficient to learn under an end-to-end optimization pipeline, and also obtains a compact representation. Furthermore, we propose a novel multi-scope Polar-Doc-IOU loss to constrain the relationship among control points as a grid-based regularization under the Polar representation. Visual comparisons and quantitative experiments on two benchmarks show that, with much fewer parameters than the other mainstream counterparts, our one-stage model with multi-scope constraints achieves new state-of-the-art performance on both pixel alignment metrics and OCR metrics. Source codes will be available at \url{*****}.

{{</citation>}}


### (23/118) Mutual-Learning Knowledge Distillation for Nighttime UAV Tracking (Yufeng Liu et al., 2023)

{{<citation>}}

Yufeng Liu, Haobo Zuo, Liangliang Yao, Kunhan Lu, Guangze Zheng, Changhong Fu. (2023)  
**Mutual-Learning Knowledge Distillation for Nighttime UAV Tracking**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2312.07884v1)  

---


**ABSTRACT**  
Nighttime unmanned aerial vehicle (UAV) tracking has been facilitated with indispensable plug-and-play low-light enhancers. However, the introduction of low-light enhancers increases the extra computational burden for the UAV, significantly hindering the development of real-time UAV applications. Meanwhile, these state-of-the-art (SOTA) enhancers lack tight coupling with the advanced daytime UAV tracking approach. To solve the above issues, this work proposes a novel mutual-learning knowledge distillation framework for nighttime UAV tracking, i.e., MLKD. This framework is constructed to learn a compact and fast nighttime tracker via knowledge transferring from the teacher and knowledge sharing among various students. Specifically, an advanced teacher based on a SOTA enhancer and a superior tracking backbone is adopted for guiding the student based only on the tight coupling-aware tracking backbone to directly extract nighttime object features. To address the biased learning of a single student, diverse lightweight students with different distillation methods are constructed to focus on various aspects of the teacher's knowledge. Moreover, an innovative mutual-learning room is designed to elect the superior student candidate to assist the remaining students frame-by-frame in the training phase. Furthermore, the final best student, i.e., MLKD-Track, is selected through the testing dataset. Extensive experiments demonstrate the effectiveness and superiority of MLKD and MLKD-Track. The practicality of the MLKD-Track is verified in real-world tests with different challenging situations. The code is available at https://github.com/vision4robotics/MLKD.

{{</citation>}}


### (24/118) CoIE: Chain-of-Instruct Editing for Multi-Attribute Face Manipulation (Zhenduo Zhang et al., 2023)

{{<citation>}}

Zhenduo Zhang, Bowen Zhang, Guang Liu. (2023)  
**CoIE: Chain-of-Instruct Editing for Multi-Attribute Face Manipulation**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.07879v1)  

---


**ABSTRACT**  
Current text-to-image editing models often encounter challenges with smoothly manipulating multiple attributes using a single instruction. Taking inspiration from the Chain-of-Thought prompting technique utilized in language models, we present an innovative concept known as Chain-of-Instruct Editing (CoIE), which enhances the capabilities of these models through step-by-step editing using a series of instructions. In particular, in the context of face manipulation, we leverage the contextual learning abilities of a pretrained Large Language Model (LLM), such as GPT-4, to generate a sequence of instructions from the original input, utilizing a purpose-designed 1-shot template. To further improve the precision of each editing step, we conduct fine-tuning on the editing models using our self-constructed instruction-guided face editing dataset, Instruct-CelebA. And additionally, we incorporate a super-resolution module to mitigate the adverse effects of editability and quality degradation. Experimental results across various challenging cases confirm the significant boost in multi-attribute facial image manipulation using chain-of-instruct editing. This is evident in enhanced editing success rates, measured by CLIPSim and Coverage metrics, improved by 17.86% and 85.45% respectively, and heightened controllability indicated by Preserve L1 and Quality metrics, improved by 11.58% and 4.93% respectively.

{{</citation>}}


### (25/118) Enhance Sketch Recognition's Explainability via Semantic Component-Level Parsing (Guangming Zhu et al., 2023)

{{<citation>}}

Guangming Zhu, Siyuan Wang, Tianci Wu, Liang Zhang. (2023)  
**Enhance Sketch Recognition's Explainability via Semantic Component-Level Parsing**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Sketch  
[Paper Link](http://arxiv.org/abs/2312.07875v1)  

---


**ABSTRACT**  
Free-hand sketches are appealing for humans as a universal tool to depict the visual world. Humans can recognize varied sketches of a category easily by identifying the concurrence and layout of the intrinsic semantic components of the category, since humans draw free-hand sketches based a common consensus that which types of semantic components constitute each sketch category. For example, an airplane should at least have a fuselage and wings. Based on this analysis, a semantic component-level memory module is constructed and embedded in the proposed structured sketch recognition network in this paper. The memory keys representing semantic components of each sketch category can be self-learned and enhance the recognition network's explainability. Our proposed networks can deal with different situations of sketch recognition, i.e., with or without semantic components labels of strokes. Experiments on the SPG and SketchIME datasets demonstrate the memory module's flexibility and the recognition network's explainability. The code and data are available at https://github.com/GuangmingZhu/SketchESC.

{{</citation>}}


### (26/118) Diffusion Models Enable Zero-Shot Pose Estimation for Lower-Limb Prosthetic Users (Tianxun Zhou et al., 2023)

{{<citation>}}

Tianxun Zhou, Muhammad Nur Shahril Iskandar, Keng-Hwee Chiam. (2023)  
**Diffusion Models Enable Zero-Shot Pose Estimation for Lower-Limb Prosthetic Users**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs-LG, cs.CV  
Keywords: Zero-Shot  
[Paper Link](http://arxiv.org/abs/2312.07854v1)  

---


**ABSTRACT**  
The application of 2D markerless gait analysis has garnered increasing interest and application within clinical settings. However, its effectiveness in the realm of lower-limb amputees has remained less than optimal. In response, this study introduces an innovative zero-shot method employing image generation diffusion models to achieve markerless pose estimation for lower-limb prosthetics, presenting a promising solution to gait analysis for this specific population. Our approach demonstrates an enhancement in detecting key points on prosthetic limbs over existing methods, and enables clinicians to gain invaluable insights into the kinematics of lower-limb amputees across the gait cycle. The outcomes obtained not only serve as a proof-of-concept for the feasibility of this zero-shot approach but also underscore its potential in advancing rehabilitation through gait analysis for this unique population.

{{</citation>}}


### (27/118) Semantic Lens: Instance-Centric Semantic Alignment for Video Super-Resolution (Qi Tang et al., 2023)

{{<citation>}}

Qi Tang, Yao Zhao, Meiqin Liu, Jian Jin, Chao Yao. (2023)  
**Semantic Lens: Instance-Centric Semantic Alignment for Video Super-Resolution**  

---
Primary Category: cs.CV  
Categories: cs-CV, cs.CV  
Keywords: Attention, Embedding  
[Paper Link](http://arxiv.org/abs/2312.07823v2)  

---


**ABSTRACT**  
As a critical clue of video super-resolution (VSR), inter-frame alignment significantly impacts overall performance. However, accurate pixel-level alignment is a challenging task due to the intricate motion interweaving in the video. In response to this issue, we introduce a novel paradigm for VSR named Semantic Lens, predicated on semantic priors drawn from degraded videos. Specifically, video is modeled as instances, events, and scenes via a Semantic Extractor. Those semantics assist the Pixel Enhancer in understanding the recovered contents and generating more realistic visual results. The distilled global semantics embody the scene information of each frame, while the instance-specific semantics assemble the spatial-temporal contexts related to each instance. Furthermore, we devise a Semantics-Powered Attention Cross-Embedding (SPACE) block to bridge the pixel-level features with semantic knowledge, composed of a Global Perspective Shifter (GPS) and an Instance-Specific Semantic Embedding Encoder (ISEE). Concretely, the GPS module generates pairs of affine transformation parameters for pixel-level feature modulation conditioned on global semantics. After that, the ISEE module harnesses the attention mechanism to align the adjacent frames in the instance-centric semantic space. In addition, we incorporate a simple yet effective pre-alignment module to alleviate the difficulty of model training. Extensive experiments demonstrate the superiority of our model over existing state-of-the-art VSR methods.

{{</citation>}}


### (28/118) A Foundational Multimodal Vision Language AI Assistant for Human Pathology (Ming Y. Lu et al., 2023)

{{<citation>}}

Ming Y. Lu, Bowen Chen, Drew F. K. Williamson, Richard J. Chen, Kenji Ikamura, Georg Gerber, Ivy Liang, Long Phi Le, Tong Ding, Anil V Parwani, Faisal Mahmood. (2023)  
**A Foundational Multimodal Vision Language AI Assistant for Human Pathology**  

---
Primary Category: cs.CV  
Categories: cs-AI, cs-CV, cs.CV  
Keywords: AI, ChatGPT, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2312.07814v1)  

---


**ABSTRACT**  
The field of computational pathology has witnessed remarkable progress in the development of both task-specific predictive models and task-agnostic self-supervised vision encoders. However, despite the explosive growth of generative artificial intelligence (AI), there has been limited study on building general purpose, multimodal AI assistants tailored to pathology. Here we present PathChat, a vision-language generalist AI assistant for human pathology using an in-house developed foundational vision encoder pretrained on 100 million histology images from over 100,000 patient cases and 1.18 million pathology image-caption pairs. The vision encoder is then combined with a pretrained large language model and the whole system is finetuned on over 250,000 diverse disease agnostic visual language instructions. We compare PathChat against several multimodal vision language AI assistants as well as GPT4V, which powers the commercially available multimodal general purpose AI assistant ChatGPT-4. When relevant clinical context is provided with the histology image, PathChat achieved a diagnostic accuracy of 87% on multiple-choice questions based on publicly available cases of diverse tissue origins and disease models. Additionally, using open-ended questions and human expert evaluation, we found that overall PathChat produced more accurate and pathologist-preferable responses to diverse queries related to pathology. As an interactive and general vision language AI assistant that can flexibly handle both visual and natural language inputs, PathChat can potentially find impactful applications in pathology education, research, and human-in-the-loop clinical decision making.

{{</citation>}}


## cs.LG (23)



### (29/118) Fair Active Learning in Low-Data Regimes (Romain Camilleri et al., 2023)

{{<citation>}}

Romain Camilleri, Andrew Wagenmaker, Jamie Morgenstern, Lalit Jain, Kevin Jamieson. (2023)  
**Fair Active Learning in Low-Data Regimes**  

---
Primary Category: cs.LG  
Categories: cs-CY, cs-LG, cs.LG, stat-ML  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2312.08559v1)  

---


**ABSTRACT**  
In critical machine learning applications, ensuring fairness is essential to avoid perpetuating social inequities. In this work, we address the challenges of reducing bias and improving accuracy in data-scarce environments, where the cost of collecting labeled data prohibits the use of large, labeled datasets. In such settings, active learning promises to maximize marginal accuracy gains of small amounts of labeled data. However, existing applications of active learning for fairness fail to deliver on this, typically requiring large labeled datasets, or failing to ensure the desired fairness tolerance is met on the population distribution.   To address such limitations, we introduce an innovative active learning framework that combines an exploration procedure inspired by posterior sampling with a fair classification subroutine. We demonstrate that this framework performs effectively in very data-scarce regimes, maximizing accuracy while satisfying fairness constraints with high probability. We evaluate our proposed approach using well-established real-world benchmark datasets and compare it against state-of-the-art methods, demonstrating its effectiveness in producing fair models, and improvement over existing methods.

{{</citation>}}


### (30/118) auto-sktime: Automated Time Series Forecasting (Marc-André Zöller et al., 2023)

{{<citation>}}

Marc-André Zöller, Marius Lindauer, Marco F. Huber. (2023)  
**auto-sktime: Automated Time Series Forecasting**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2312.08528v1)  

---


**ABSTRACT**  
In today's data-driven landscape, time series forecasting is pivotal in decision-making across various sectors. Yet, the proliferation of more diverse time series data, coupled with the expanding landscape of available forecasting methods, poses significant challenges for forecasters. To meet the growing demand for efficient forecasting, we introduce auto-sktime, a novel framework for automated time series forecasting. The proposed framework uses the power of automated machine learning (AutoML) techniques to automate the creation of the entire forecasting pipeline. The framework employs Bayesian optimization, to automatically construct pipelines from statistical, machine learning (ML) and deep neural network (DNN) models. Furthermore, we propose three essential improvements to adapt AutoML to time series data: First, pipeline templates to account for the different supported forecasting models. Second, a novel warm-starting technique to start the optimization from prior optimization runs. Third, we adapt multi-fidelity optimizations to make them applicable to a search space containing statistical, ML and DNN models. Experimental results on 64 diverse real-world time series datasets demonstrate the effectiveness and efficiency of the framework, outperforming traditional methods while requiring minimal human involvement.

{{</citation>}}


### (31/118) Simplicial Representation Learning with Neural $k$-forms (Kelly Maggs et al., 2023)

{{<citation>}}

Kelly Maggs, Celia Hacker, Bastian Rieck. (2023)  
**Simplicial Representation Learning with Neural $k$-forms**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, math-AT  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2312.08515v1)  

---


**ABSTRACT**  
Geometric deep learning extends deep learning to incorporate information about the geometry and topology data, especially in complex domains like graphs. Despite the popularity of message passing in this field, it has limitations such as the need for graph rewiring, ambiguity in interpreting data, and over-smoothing. In this paper, we take a different approach, focusing on leveraging geometric information from simplicial complexes embedded in $\mathbb{R}^n$ using node coordinates. We use differential k-forms in \mathbb{R}^n to create representations of simplices, offering interpretability and geometric consistency without message passing. This approach also enables us to apply differential geometry tools and achieve universal approximation. Our method is efficient, versatile, and applicable to various input complexes, including graphs, simplicial complexes, and cell complexes. It outperforms existing message passing neural networks in harnessing information from geometrical graphs with node features serving as coordinates.

{{</citation>}}


### (32/118) An Invitation to Deep Reinforcement Learning (Bernhard Jaeger et al., 2023)

{{<citation>}}

Bernhard Jaeger, Andreas Geiger. (2023)  
**An Invitation to Deep Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: BLEU, Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.08365v1)  

---


**ABSTRACT**  
Training a deep neural network to maximize a target objective has become the standard recipe for successful machine learning over the last decade. These networks can be optimized with supervised learning, if the target objective is differentiable. For many interesting problems, this is however not the case. Common objectives like intersection over union (IoU), bilingual evaluation understudy (BLEU) score or rewards cannot be optimized with supervised learning. A common workaround is to define differentiable surrogate losses, leading to suboptimal solutions with respect to the actual objective. Reinforcement learning (RL) has emerged as a promising alternative for optimizing deep neural networks to maximize non-differentiable objectives in recent years. Examples include aligning large language models via human feedback, code generation, object detection or control problems. This makes RL techniques relevant to the larger machine learning audience. The subject is, however, time intensive to approach due to the large range of methods, as well as the often very theoretical presentation. In this introduction, we take an alternative approach, different from classic reinforcement learning textbooks. Rather than focusing on tabular problems, we introduce reinforcement learning as a generalization of supervised learning, which we first apply to non-differentiable objectives and later to temporal problems. Assuming only basic knowledge of supervised learning, the reader will be able to understand state-of-the-art deep RL algorithms like proximal policy optimization (PPO) after reading this tutorial.

{{</citation>}}


### (33/118) Distributed Inference and Fine-tuning of Large Language Models Over The Internet (Alexander Borzunov et al., 2023)

{{<citation>}}

Alexander Borzunov, Max Ryabinin, Artem Chumachenko, Dmitry Baranchuk, Tim Dettmers, Younes Belkada, Pavel Samygin, Colin Raffel. (2023)  
**Distributed Inference and Fine-tuning of Large Language Models Over The Internet**  

---
Primary Category: cs.LG  
Categories: cs-DC, cs-LG, cs.LG  
Keywords: BLOOM, Language Model, NLP  
[Paper Link](http://arxiv.org/abs/2312.08361v1)  

---


**ABSTRACT**  
Large language models (LLMs) are useful in many NLP tasks and become more capable with size, with the best open-source models having over 50 billion parameters. However, using these 50B+ models requires high-end hardware, making them inaccessible to most researchers. In this work, we investigate methods for cost-efficient inference and fine-tuning of LLMs, comparing local and distributed strategies. We observe that a large enough model (50B+) can run efficiently even on geodistributed devices in a consumer-grade network. This could allow running LLM efficiently by pooling together idle compute resources of multiple research groups and volunteers. We address two open problems: (1) how to perform inference and fine-tuning reliably if any device can disconnect abruptly and (2) how to partition LLMs between devices with uneven hardware, joining and leaving at will. In order to do that, we develop special fault-tolerant inference algorithms and load-balancing protocols that automatically assign devices to maximize the total system throughput. We showcase these algorithms in Petals - a decentralized system that runs Llama 2 (70B) and BLOOM (176B) over the Internet up to 10x faster than offloading for interactive generation. We evaluate the performance of our system in simulated conditions and a real-world setup spanning two continents.

{{</citation>}}


### (34/118) ERASE: Error-Resilient Representation Learning on Graphs for Label Noise Tolerance (Ling-Hao Chen et al., 2023)

{{<citation>}}

Ling-Hao Chen, Yuanshuo Zhang, Taohua Huang, Liangcai Su, Zeyi Lin, Xi Xiao, Xiaobo Xia, Tongliang Liu. (2023)  
**ERASE: Error-Resilient Representation Learning on Graphs for Label Noise Tolerance**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2312.08852v1)  

---


**ABSTRACT**  
Deep learning has achieved remarkable success in graph-related tasks, yet this accomplishment heavily relies on large-scale high-quality annotated datasets. However, acquiring such datasets can be cost-prohibitive, leading to the practical use of labels obtained from economically efficient sources such as web searches and user tags. Unfortunately, these labels often come with noise, compromising the generalization performance of deep networks. To tackle this challenge and enhance the robustness of deep learning models against label noise in graph-based tasks, we propose a method called ERASE (Error-Resilient representation learning on graphs for lAbel noiSe tolerancE). The core idea of ERASE is to learn representations with error tolerance by maximizing coding rate reduction. Particularly, we introduce a decoupled label propagation method for learning representations. Before training, noisy labels are pre-corrected through structural denoising. During training, ERASE combines prototype pseudo-labels with propagated denoised labels and updates representations with error resilience, which significantly improves the generalization performance in node classification. The proposed method allows us to more effectively withstand errors caused by mislabeled nodes, thereby strengthening the robustness of deep networks in handling noisy graph data. Extensive experimental results show that our method can outperform multiple baselines with clear margins in broad noise levels and enjoy great scalability. Codes are released at https://github.com/eraseai/erase.

{{</citation>}}


### (35/118) Automatic Bug Detection in Games using LSTM Networks (Elham Azizi et al., 2023)

{{<citation>}}

Elham Azizi, Loutfouz Zaman. (2023)  
**Automatic Bug Detection in Games using LSTM Networks**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SE, cs.LG  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2312.08418v1)  

---


**ABSTRACT**  
We introduced a new framework to detect perceptual bugs using a Long Short-Term Memory (LSTM) network, which detects bugs in video games as anomalies. The detected buggy frames are then clustered to determine the category of the occurred bug. The framework was evaluated on two First Person Shooter (FPS) games. Results show the effectiveness of the framework.

{{</citation>}}


### (36/118) On the verification of Embeddings using Hybrid Markov Logic (Anup Shakya et al., 2023)

{{<citation>}}

Anup Shakya, Abisha Thapa Magar, Somdeb Sarkhel, Deepak Venugopal. (2023)  
**On the verification of Embeddings using Hybrid Markov Logic**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: Embedding, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.08287v1)  

---


**ABSTRACT**  
The standard approach to verify representations learned by Deep Neural Networks is to use them in specific tasks such as classification or regression, and measure their performance based on accuracy in such tasks. However, in many cases, we would want to verify more complex properties of a learned representation. To do this, we propose a framework based on a probabilistic first-order language, namely, Hybrid Markov Logic Networks (HMLNs) where we specify properties over embeddings mixed with symbolic domain knowledge. We present an approach to learn parameters for the properties within this framework. Further, we develop a verification method to test embeddings in this framework by encoding this task as a Mixed Integer Linear Program for which we can leverage existing state-of-the-art solvers. We illustrate verification in Graph Neural Networks, Deep Knowledge Tracing and Intelligent Tutoring Systems to demonstrate the generality of our approach.

{{</citation>}}


### (37/118) Curriculum-Enhanced Residual Soft An-Isotropic Normalization for Over-smoothness in Deep GNNs (Jin Li et al., 2023)

{{<citation>}}

Jin Li, Qirong Zhang, Shuling Xu, Xinlong Chen, Longkun Guo, Yang-Geng Fu. (2023)  
**Curriculum-Enhanced Residual Soft An-Isotropic Normalization for Over-smoothness in Deep GNNs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: GNN  
[Paper Link](http://arxiv.org/abs/2312.08221v2)  

---


**ABSTRACT**  
Despite Graph neural networks' significant performance gain over many classic techniques in various graph-related downstream tasks, their successes are restricted in shallow models due to over-smoothness and the difficulties of optimizations among many other issues. In this paper, to alleviate the over-smoothing issue, we propose a soft graph normalization method to preserve the diversities of node embeddings and prevent indiscrimination due to possible over-closeness. Combined with residual connections, we analyze the reason why the method can effectively capture the knowledge in both input graph structures and node features even with deep networks. Additionally, inspired by Curriculum Learning that learns easy examples before the hard ones, we propose a novel label-smoothing-based learning framework to enhance the optimization of deep GNNs, which iteratively smooths labels in an auxiliary graph and constructs many gradual non-smooth tasks for extracting increasingly complex knowledge and gradually discriminating nodes from coarse to fine. The method arguably reduces the risk of overfitting and generalizes better results. Finally, extensive experiments are carried out to demonstrate the effectiveness and potential of the proposed model and learning framework through comparison with twelve existing baselines including the state-of-the-art methods on twelve real-world node classification benchmarks.

{{</citation>}}


### (38/118) Privacy Constrained Fairness Estimation for Decision Trees (Florian van der Steen et al., 2023)

{{<citation>}}

Florian van der Steen, Fré Vink, Heysem Kaya. (2023)  
**Privacy Constrained Fairness Estimation for Decision Trees**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-CY, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08413v1)  

---


**ABSTRACT**  
The protection of sensitive data becomes more vital, as data increases in value and potency. Furthermore, the pressure increases from regulators and society on model developers to make their Artificial Intelligence (AI) models non-discriminatory. To boot, there is a need for interpretable, transparent AI models for high-stakes tasks. In general, measuring the fairness of any AI model requires the sensitive attributes of the individuals in the dataset, thus raising privacy concerns. In this work, the trade-offs between fairness, privacy and interpretability are further explored. We specifically examine the Statistical Parity (SP) of Decision Trees (DTs) with Differential Privacy (DP), that are each popular methods in their respective subfield. We propose a novel method, dubbed Privacy-Aware Fairness Estimation of Rules (PAFER), that can estimate SP in a DP-aware manner for DTs. DP, making use of a third-party legal entity that securely holds this sensitive data, guarantees privacy by adding noise to the sensitive data. We experimentally compare several DP mechanisms. We show that using the Laplacian mechanism, the method is able to estimate SP with low error while guaranteeing the privacy of the individuals in the dataset with high certainty. We further show experimentally and theoretically that the method performs better for DTs that humans generally find easier to interpret.

{{</citation>}}


### (39/118) Read Between the Layers: Leveraging Intra-Layer Representations for Rehearsal-Free Continual Learning with Pre-Trained Models (Kyra Ahrens et al., 2023)

{{<citation>}}

Kyra Ahrens, Hans Hergen Lehmann, Jae Hee Lee, Stefan Wermter. (2023)  
**Read Between the Layers: Leveraging Intra-Layer Representations for Rehearsal-Free Continual Learning with Pre-Trained Models**  

---
Primary Category: cs.LG  
Categories: cs-CV, cs-LG, cs.LG  
Keywords: Pre-Trained Model  
[Paper Link](http://arxiv.org/abs/2312.08888v1)  

---


**ABSTRACT**  
We address the Continual Learning (CL) problem, where a model has to learn a sequence of tasks from non-stationary distributions while preserving prior knowledge as it encounters new experiences. With the advancement of foundation models, CL research has shifted focus from the initial learning-from-scratch paradigm to the use of generic features from large-scale pre-training. However, existing approaches to CL with pre-trained models only focus on separating the class-specific features from the final representation layer and neglect the power of intermediate representations that capture low- and mid-level features naturally more invariant to domain shifts. In this work, we propose LayUP, a new class-prototype-based approach to continual learning that leverages second-order feature statistics from multiple intermediate layers of a pre-trained network. Our method is conceptually simple, does not require any replay buffer, and works out of the box with any foundation model. LayUP improves over the state-of-the-art on four of the seven class-incremental learning settings at a considerably reduced memory and computational footprint compared with the next best baseline. Our results demonstrate that fully exhausting the representational capacities of pre-trained models in CL goes far beyond their final embeddings.

{{</citation>}}


### (40/118) An Incentive Mechanism for Federated Learning Based on Multiple Resource Exchange (Ruonan Dong et al., 2023)

{{<citation>}}

Ruonan Dong, Hui Xu, Han Zhang, GuoPeng Zhang. (2023)  
**An Incentive Mechanism for Federated Learning Based on Multiple Resource Exchange**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2312.08096v1)  

---


**ABSTRACT**  
Federated Learning (FL) is a distributed machine learning paradigm that addresses privacy concerns in machine learning and still guarantees high test accuracy. However, achieving the necessary accuracy by having all clients participate in FL is impractical, given the constraints of client local computing resource. In this paper, we introduce a multi-user collaborative computing framework, categorizing users into two roles: model owners (MOs) and data owner (DOs). Without resorting to monetary incentives, an MO can encourage more DOs to join in FL by allowing the DOs to offload extra local computing tasks to the MO for execution. This exchange of "data" for "computing resources" streamlines the incentives for clients to engage more effectively in FL. We formulate the interaction between MO and DOs as an optimization problem, and the objective is to effectively utilize the communication and computing resource of the MO and DOs to minimize the time to complete an FL task. The proposed problem is a mixed integer nonlinear programming (MINLP) with high computational complexity. We first decompose it into two distinct subproblems, namely the client selection problem and the resource allocation problem to segregate the integer variables from the continuous variables. Then, an effective iterative algorithm is proposed to solve problem. Simulation results demonstrate that the proposed collaborative computing framework can achieve an accuracy of more than 95\% while minimizing the overall time to complete an FL task.

{{</citation>}}


### (41/118) Explainable AI in Grassland Monitoring: Enhancing Model Performance and Domain Adaptability (Shanghua Liu et al., 2023)

{{<citation>}}

Shanghua Liu, Anna Hedström, Deepak Hanike Basavegowda, Cornelia Weltzien, Marina M. -C. Höhne. (2023)  
**Explainable AI in Grassland Monitoring: Enhancing Model Performance and Domain Adaptability**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-CV, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08408v1)  

---


**ABSTRACT**  
Grasslands are known for their high biodiversity and ability to provide multiple ecosystem services. Challenges in automating the identification of indicator plants are key obstacles to large-scale grassland monitoring. These challenges stem from the scarcity of extensive datasets, the distributional shifts between generic and grassland-specific datasets, and the inherent opacity of deep learning models. This paper delves into the latter two challenges, with a specific focus on transfer learning and eXplainable Artificial Intelligence (XAI) approaches to grassland monitoring, highlighting the novelty of XAI in this domain. We analyze various transfer learning methods to bridge the distributional gaps between generic and grassland-specific datasets. Additionally, we showcase how explainable AI techniques can unveil the model's domain adaptation capabilities, employing quantitative assessments to evaluate the model's proficiency in accurately centering relevant input features around the object of interest. This research contributes valuable insights for enhancing model performance through transfer learning and measuring domain adaptability with explainable AI, showing significant promise for broader applications within the agricultural community.

{{</citation>}}


### (42/118) Secure Deep Reinforcement Learning for Dynamic Resource Allocation in Wireless MEC Networks (Xin Hao et al., 2023)

{{<citation>}}

Xin Hao, Phee Lep Yeoh, Changyang She, Branka Vucetic, Yonghui Li. (2023)  
**Secure Deep Reinforcement Learning for Dynamic Resource Allocation in Wireless MEC Networks**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-NI, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.08016v1)  

---


**ABSTRACT**  
This paper proposes a blockchain-secured deep reinforcement learning (BC-DRL) optimization framework for {data management and} resource allocation in decentralized {wireless mobile edge computing (MEC)} networks. In our framework, {we design a low-latency reputation-based proof-of-stake (RPoS) consensus protocol to select highly reliable blockchain-enabled BSs to securely store MEC user requests and prevent data tampering attacks.} {We formulate the MEC resource allocation optimization as a constrained Markov decision process that balances minimum processing latency and denial-of-service (DoS) probability}. {We use the MEC aggregated features as the DRL input to significantly reduce the high-dimensionality input of the remaining service processing time for individual MEC requests. Our designed constrained DRL effectively attains the optimal resource allocations that are adapted to the dynamic DoS requirements. We provide extensive simulation results and analysis to} validate that our BC-DRL framework achieves higher security, reliability, and resource utilization efficiency than benchmark blockchain consensus protocols and {MEC} resource allocation algorithms.

{{</citation>}}


### (43/118) SwitchHead: Accelerating Transformers with Mixture-of-Experts Attention (Róbert Csordás et al., 2023)

{{<citation>}}

Róbert Csordás, Piotr Piękos, Kazuki Irie, Jürgen Schmidhuber. (2023)  
**SwitchHead: Accelerating Transformers with Mixture-of-Experts Attention**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs-NE, cs.LG  
Keywords: Attention, Transformer, Transformers  
[Paper Link](http://arxiv.org/abs/2312.07987v2)  

---


**ABSTRACT**  
The costly self-attention layers in modern Transformers require memory and compute quadratic in sequence length. Existing approximation methods usually underperform and fail to obtain significant speedups in practice. Here we present SwitchHead - a novel method that reduces both compute and memory requirements and achieves wall-clock speedup, while matching the language modeling performance of baseline Transformers with the same parameter budget. SwitchHead uses Mixture-of-Experts (MoE) layers for the value and output projections and requires 4 to 8 times fewer attention matrices than standard Transformers. Our novel attention can also be combined with MoE MLP layers, resulting in an efficient fully-MoE "SwitchAll" Transformer model. Our code is public.

{{</citation>}}


### (44/118) Multi-perspective Feedback-attention Coupling Model for Continuous-time Dynamic Graphs (Xiaobo Zhu et al., 2023)

{{<citation>}}

Xiaobo Zhu, Yan Wu, Zhipeng Li, Hailong Su, Jin Che, Zhanheng Chen, Liying Wang. (2023)  
**Multi-perspective Feedback-attention Coupling Model for Continuous-time Dynamic Graphs**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs-SI, cs.LG  
Keywords: Attention  
[Paper Link](http://arxiv.org/abs/2312.07983v1)  

---


**ABSTRACT**  
Recently, representation learning over graph networks has gained popularity, with various models showing promising results. Despite this, several challenges persist: 1) most methods are designed for static or discrete-time dynamic graphs; 2) existing continuous-time dynamic graph algorithms focus on a single evolving perspective; and 3) many continuous-time dynamic graph approaches necessitate numerous temporal neighbors to capture long-term dependencies. In response, this paper introduces the Multi-Perspective Feedback-Attention Coupling (MPFA) model. MPFA incorporates information from both evolving and raw perspectives, efficiently learning the interleaved dynamics of observed processes. The evolving perspective employs temporal self-attention to distinguish continuously evolving temporal neighbors for information aggregation. Through dynamic updates, this perspective can capture long-term dependencies using a small number of temporal neighbors. Meanwhile, the raw perspective utilizes a feedback attention module with growth characteristic coefficients to aggregate raw neighborhood information. Experimental results on a self-organizing dataset and seven public datasets validate the efficacy and competitiveness of our proposed model.

{{</citation>}}


### (45/118) Time Series Diffusion Method: A Denoising Diffusion Probabilistic Model for Vibration Signal Generation (Haiming Yi et al., 2023)

{{<citation>}}

Haiming Yi, Lei Hou, Yuhong Jin, Nasser A. Saeed. (2023)  
**Time Series Diffusion Method: A Denoising Diffusion Probabilistic Model for Vibration Signal Generation**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SD, cs.LG, eess-SP  
Keywords: Time Series  
[Paper Link](http://arxiv.org/abs/2312.07981v1)  

---


**ABSTRACT**  
Diffusion models have demonstrated robust data generation capabilities in various research fields. In this paper, a Time Series Diffusion Method (TSDM) is proposed for vibration signal generation, leveraging the foundational principles of diffusion models. The TSDM uses an improved U-net architecture with attention block to effectively segment and extract features from one-dimensional time series data. It operates based on forward diffusion and reverse denoising processes for time-series generation. Experimental validation is conducted using single-frequency, multi-frequency datasets, and bearing fault datasets. The results show that TSDM can accurately generate the single-frequency and multi-frequency features in the time series and retain the basic frequency features for the diffusion generation results of the bearing fault series. Finally, TSDM is applied to the small sample fault diagnosis of three public bearing fault datasets, and the results show that the accuracy of small sample fault diagnosis of the three datasets is improved by 32.380%, 18.355% and 9.298% at most, respectively

{{</citation>}}


### (46/118) CBQ: Cross-Block Quantization for Large Language Models (Xin Ding et al., 2023)

{{<citation>}}

Xin Ding, Xiaoyu Liu, Yun Zhang, Zhijun Tu, Wei Li, Jie Hu, Hanting Chen, Yehui Tang, Zhiwei Xiong, Baoqun Yin, Yunhe Wang. (2023)  
**CBQ: Cross-Block Quantization for Large Language Models**  

---
Primary Category: cs.LG  
Categories: cs-CL, cs-LG, cs.LG  
Keywords: Language Model, Quantization  
[Paper Link](http://arxiv.org/abs/2312.07950v1)  

---


**ABSTRACT**  
Post-training quantization (PTQ) has driven attention to producing efficient large language models (LLMs) with ultra-low costs. Since hand-craft quantization parameters lead to low performance in low-bit quantization, recent methods optimize the quantization parameters through block-wise reconstruction between the floating-point and quantized models. However, these methods suffer from two challenges: accumulated errors from independent one-by-one block quantization and reconstruction difficulties from extreme weight and activation outliers. To address these two challenges, we propose CBQ, a cross-block reconstruction-based PTQ method for LLMs. To reduce error accumulation, we introduce a cross-block dependency with the aid of a homologous reconstruction scheme to build the long-range dependency between adjacent multi-blocks with overlapping. To reduce reconstruction difficulty, we design a coarse-to-fine pre-processing (CFP) to truncate weight outliers and dynamically scale activation outliers before optimization, and an adaptive rounding scheme, called LoRA-Rounding, with two low-rank learnable matrixes to further rectify weight quantization errors. Extensive experiments demonstrate that: (1) CBQ pushes both activation and weight quantization to low-bit settings W4A4, W4A8, and W2A16. (2) CBQ achieves better performance than the existing state-of-the-art methods on various LLMs and benchmark datasets.

{{</citation>}}


### (47/118) Levenshtein Distance Embedding with Poisson Regression for DNA Storage (Xiang Wei et al., 2023)

{{<citation>}}

Xiang Wei, Alan J. X. Guo, Sihan Sun, Mengyi Wei, Wei Yu. (2023)  
**Levenshtein Distance Embedding with Poisson Regression for DNA Storage**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs.LG, q-bio-QM  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2312.07931v1)  

---


**ABSTRACT**  
Efficient computation or approximation of Levenshtein distance, a widely-used metric for evaluating sequence similarity, has attracted significant attention with the emergence of DNA storage and other biological applications. Sequence embedding, which maps Levenshtein distance to a conventional distance between embedding vectors, has emerged as a promising solution. In this paper, a novel neural network-based sequence embedding technique using Poisson regression is proposed. We first provide a theoretical analysis of the impact of embedding dimension on model performance and present a criterion for selecting an appropriate embedding dimension. Under this embedding dimension, the Poisson regression is introduced by assuming the Levenshtein distance between sequences of fixed length following a Poisson distribution, which naturally aligns with the definition of Levenshtein distance. Moreover, from the perspective of the distribution of embedding distances, Poisson regression approximates the negative log likelihood of the chi-squared distribution and offers advancements in removing the skewness. Through comprehensive experiments on real DNA storage data, we demonstrate the superior performance of the proposed method compared to state-of-the-art approaches.

{{</citation>}}


### (48/118) GraphGuard: Detecting and Counteracting Training Data Misuse in Graph Neural Networks (Bang Wu et al., 2023)

{{<citation>}}

Bang Wu, He Zhang, Xiangwen Yang, Shuo Wang, Minhui Xue, Shirui Pan, Xingliang Yuan. (2023)  
**GraphGuard: Detecting and Counteracting Training Data Misuse in Graph Neural Networks**  

---
Primary Category: cs.LG  
Categories: cs-CR, cs-LG, cs.LG  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.07861v1)  

---


**ABSTRACT**  
The emergence of Graph Neural Networks (GNNs) in graph data analysis and their deployment on Machine Learning as a Service platforms have raised critical concerns about data misuse during model training. This situation is further exacerbated due to the lack of transparency in local training processes, potentially leading to the unauthorized accumulation of large volumes of graph data, thereby infringing on the intellectual property rights of data owners. Existing methodologies often address either data misuse detection or mitigation, and are primarily designed for local GNN models rather than cloud-based MLaaS platforms. These limitations call for an effective and comprehensive solution that detects and mitigates data misuse without requiring exact training data while respecting the proprietary nature of such data. This paper introduces a pioneering approach called GraphGuard, to tackle these challenges. We propose a training-data-free method that not only detects graph data misuse but also mitigates its impact via targeted unlearning, all without relying on the original training data. Our innovative misuse detection technique employs membership inference with radioactive data, enhancing the distinguishability between member and non-member data distributions. For mitigation, we utilize synthetic graphs that emulate the characteristics previously learned by the target model, enabling effective unlearning even in the absence of exact graph data. We conduct comprehensive experiments utilizing four real-world graph datasets to demonstrate the efficacy of GraphGuard in both detection and unlearning. We show that GraphGuard attains a near-perfect detection rate of approximately 100% across these datasets with various GNN models. In addition, it performs unlearning by eliminating the impact of the unlearned graph with a marginal decrease in accuracy (less than 5%).

{{</citation>}}


### (49/118) Invariant Graph Transformer (Zhe Xu et al., 2023)

{{<citation>}}

Zhe Xu, Menghai Pan, Yuzhong Chen, Huiyuan Chen, Yuchen Yan, Mahashweta Das, Hanghang Tong. (2023)  
**Invariant Graph Transformer**  

---
Primary Category: cs.LG  
Categories: cs-LG, cs-SI, cs.LG  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.07859v2)  

---


**ABSTRACT**  
Rationale discovery is defined as finding a subset of the input data that maximally supports the prediction of downstream tasks. In graph machine learning context, graph rationale is defined to locate the critical subgraph in the given graph topology, which fundamentally determines the prediction results. In contrast to the rationale subgraph, the remaining subgraph is named the environment subgraph. Graph rationalization can enhance the model performance as the mapping between the graph rationale and prediction label is viewed as invariant, by assumption. To ensure the discriminative power of the extracted rationale subgraphs, a key technique named "intervention" is applied. The core idea of intervention is that given any changing environment subgraphs, the semantics from the rationale subgraph is invariant, which guarantees the correct prediction result. However, most, if not all, of the existing rationalization works on graph data develop their intervention strategies on the graph level, which is coarse-grained. In this paper, we propose well-tailored intervention strategies on graph data. Our idea is driven by the development of Transformer models, whose self-attention module provides rich interactions between input nodes. Based on the self-attention module, our proposed invariant graph Transformer (IGT) can achieve fine-grained, more specifically, node-level and virtual node-level intervention. Our comprehensive experiments involve 7 real-world datasets, and the proposed IGT shows significant performance advantages compared to 13 baseline methods.

{{</citation>}}


### (50/118) Prototypical Self-Explainable Models Without Re-training (Srishti Gautam et al., 2023)

{{<citation>}}

Srishti Gautam, Ahcene Boubekki, Marina M. C. Höhne, Michael C. Kampffmeyer. (2023)  
**Prototypical Self-Explainable Models Without Re-training**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-LG, cs.LG  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.07822v1)  

---


**ABSTRACT**  
Explainable AI (XAI) has unfolded in two distinct research directions with, on the one hand, post-hoc methods that explain the predictions of a pre-trained black-box model and, on the other hand, self-explainable models (SEMs) which are trained directly to provide explanations alongside their predictions. While the latter is preferred in most safety-critical scenarios, post-hoc approaches have received the majority of attention until now, owing to their simplicity and ability to explain base models without retraining. Current SEMs instead, require complex architectures and heavily regularized loss functions, thus necessitating specific and costly training. To address this shortcoming and facilitate wider use of SEMs, we propose a simple yet efficient universal method called KMEx (K-Means Explainer), which can convert any existing pre-trained model into a prototypical SEM. The motivation behind KMEx is to push towards more transparent deep learning-based decision-making via class-prototype-based explanations that are guaranteed to be diverse and trustworthy without retraining the base model. We compare models obtained from KMEx to state-of-the-art SEMs using an extensive qualitative evaluation to highlight the strengths and weaknesses of each model, further paving the way toward a more reliable and objective evaluation of SEMs.

{{</citation>}}


### (51/118) Personalized Decision Supports based on Theory of Mind Modeling and Explainable Reinforcement Learning (Huao Li et al., 2023)

{{<citation>}}

Huao Li, Yao Fan, Keyang Zheng, Michael Lewis, Katia Sycara. (2023)  
**Personalized Decision Supports based on Theory of Mind Modeling and Explainable Reinforcement Learning**  

---
Primary Category: cs.LG  
Categories: cs-AI, cs-HC, cs-LG, cs.LG  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.08397v1)  

---


**ABSTRACT**  
In this paper, we propose a novel personalized decision support system that combines Theory of Mind (ToM) modeling and explainable Reinforcement Learning (XRL) to provide effective and interpretable interventions. Our method leverages DRL to provide expert action recommendations while incorporating ToM modeling to understand users' mental states and predict their future actions, enabling appropriate timing for intervention. To explain interventions, we use counterfactual explanations based on RL's feature importance and users' ToM model structure. Our proposed system generates accurate and personalized interventions that are easily interpretable by end-users. We demonstrate the effectiveness of our approach through a series of crowd-sourcing experiments in a simulated team decision-making task, where our system outperforms control baselines in terms of task performance. Our proposed approach is agnostic to task environment and RL model structure, therefore has the potential to be generalized to a wide range of applications.

{{</citation>}}


## eess.IV (4)



### (52/118) KDAS3: Knowledge distillation via Attention Supervision, and Symmetrical structure guiding for Polyp Segmentation (Quoc-Huy Trinh, 2023)

{{<citation>}}

Quoc-Huy Trinh. (2023)  
**KDAS3: Knowledge distillation via Attention Supervision, and Symmetrical structure guiding for Polyp Segmentation**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: Attention, Knowledge Distillation  
[Paper Link](http://arxiv.org/abs/2312.08555v1)  

---


**ABSTRACT**  
Polyp segmentation, a contentious issue in medical imaging, has seen numerous proposed methods aimed at improving the quality of segmented masks. Currently, state-of-the-art techniques yield impressive results. However, the sheer size of these models poses challenges for practical industry applications. To address this, we present a Knowledge Distillation framework, incorporating attention supervision and the symmetrical guiding method. This framework is designed to facilitate knowledge transfer from a teacher model to a more compact student model with fewer parameters. Our experimental evaluation of the framework assesses its effectiveness in enabling the student model to acquire knowledge from the teacher efficiently. Additionally, our method serves to prevent the student model from incorporating redundant features that could lead to inaccurate predictions. Consequently, our method, boasting approximately 5 million parameters, achieves competitive results comparable to the state-of-the-art approaches. The implementation can be found at: https://github.com/huyquoctrinh/KDAS3

{{</citation>}}


### (53/118) Enhancing CT Image synthesis from multi-modal MRI data based on a multi-task neural network framework (Zhuoyao Xin et al., 2023)

{{<citation>}}

Zhuoyao Xin, Christopher Wu, Dong Liu, Chunming Gu, Jia Guo, Jun Hua. (2023)  
**Enhancing CT Image synthesis from multi-modal MRI data based on a multi-task neural network framework**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV, q-bio-QM  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.08343v2)  

---


**ABSTRACT**  
Image segmentation, real-value prediction, and cross-modal translation are critical challenges in medical imaging. In this study, we propose a versatile multi-task neural network framework, based on an enhanced Transformer U-Net architecture, capable of simultaneously, selectively, and adaptively addressing these medical image tasks. Validation is performed on a public repository of human brain MR and CT images. We decompose the traditional problem of synthesizing CT images into distinct subtasks, which include skull segmentation, Hounsfield unit (HU) value prediction, and image sequential reconstruction. To enhance the framework's versatility in handling multi-modal data, we expand the model with multiple image channels. Comparisons between synthesized CT images derived from T1-weighted and T2-Flair images were conducted, evaluating the model's capability to integrate multi-modal information from both morphological and pixel value perspectives.

{{</citation>}}


### (54/118) TABSurfer: a Hybrid Deep Learning Architecture for Subcortical Segmentation (Aaron Cao et al., 2023)

{{<citation>}}

Aaron Cao, Vishwanatha M. Rao, Kejia Liu, Xinru Liu, Andrew F. Laine, Jia Guo. (2023)  
**TABSurfer: a Hybrid Deep Learning Architecture for Subcortical Segmentation**  

---
Primary Category: eess.IV  
Categories: cs-CV, eess-IV, eess.IV, q-bio-QM  
Keywords: Transformer  
[Paper Link](http://arxiv.org/abs/2312.08267v1)  

---


**ABSTRACT**  
Subcortical segmentation remains challenging despite its important applications in quantitative structural analysis of brain MRI scans. The most accurate method, manual segmentation, is highly labor intensive, so automated tools like FreeSurfer have been adopted to handle this task. However, these traditional pipelines are slow and inefficient for processing large datasets. In this study, we propose TABSurfer, a novel 3D patch-based CNN-Transformer hybrid deep learning model designed for superior subcortical segmentation compared to existing state-of-the-art tools. To evaluate, we first demonstrate TABSurfer's consistent performance across various T1w MRI datasets with significantly shorter processing times compared to FreeSurfer. Then, we validate against manual segmentations, where TABSurfer outperforms FreeSurfer based on the manual ground truth. In each test, we also establish TABSurfer's advantage over a leading deep learning benchmark, FastSurferVINN. Together, these studies highlight TABSurfer's utility as a powerful tool for fully automated subcortical segmentation with high fidelity.

{{</citation>}}


### (55/118) Pneumonia Detection on chest X-ray images Using Ensemble of Deep Convolutional Neural Networks (Alhassan Mabrouk et al., 2023)

{{<citation>}}

Alhassan Mabrouk, Rebeca P. Díaz Redondo, Abdelghani Dahou, Mohamed Abd Elaziz, Mohammed Kayed. (2023)  
**Pneumonia Detection on chest X-ray images Using Ensemble of Deep Convolutional Neural Networks**  

---
Primary Category: eess.IV  
Categories: cs-CV, cs-LG, eess-IV, eess.IV  
Keywords: ImageNet, Transformer  
[Paper Link](http://arxiv.org/abs/2312.07965v1)  

---


**ABSTRACT**  
Pneumonia is a life-threatening lung infection resulting from several different viral infections. Identifying and treating pneumonia on chest X-ray images can be difficult due to its similarity to other pulmonary diseases. Thus, the existing methods for predicting pneumonia cannot attain substantial levels of accuracy. Therefore, this paper presents a computer-aided classification of pneumonia, coined as Ensemble Learning (EL), to simplify the diagnosis process on chest X-ray images. Our proposal is based on Convolutional Neural Network (CNN) models, which are pre-trained CNN models that have been recently employed to enhance the performance of many medical tasks instead of training CNN models from scratch. We propose to use three well-known CNN pre-trained (DenseNet169, MobileNetV2 and Vision Transformer) using the ImageNet database. Then, these models are trained on the chest X-ray data set using fine-tuning. Finally, the results are obtained by combining the extracted features from these three models during the experimental phase. The proposed EL approach outperforms other existing state-of-the-art methods, and it obtains an accuracy of 93.91% and a F1-Score of 93.88% on the testing phase.

{{</citation>}}


## eess.AS (3)



### (56/118) USM-Lite: Quantization and Sparsity Aware Fine-tuning for Speech Recognition with Universal Speech Models (Shaojin Ding et al., 2023)

{{<citation>}}

Shaojin Ding, Qiu David, David Rim, Yanzhang He, Oleg Rybakov, Bo Li, Rohit Prabhavalkar, Weiran Wang, Tara N. Sainath, Shivani Agrawal, Zhonglin Han, Jian Li, Amir Yazdanbakhsh. (2023)  
**USM-Lite: Quantization and Sparsity Aware Fine-tuning for Speech Recognition with Universal Speech Models**  

---
Primary Category: eess.AS  
Categories: cs-SD, eess-AS, eess.AS  
Keywords: Quantization, Speech Recognition  
[Paper Link](http://arxiv.org/abs/2312.08553v1)  

---


**ABSTRACT**  
End-to-end automatic speech recognition (ASR) models have seen revolutionary quality gains with the recent development of large-scale universal speech models (USM). However, deploying these massive USMs is extremely expensive due to the enormous memory usage and computational cost. Therefore, model compression is an important research topic to fit USM-based ASR under budget in real-world scenarios. In this study, we propose a USM fine-tuning approach for ASR, with a low-bit quantization and N:M structured sparsity aware paradigm on the model weights, reducing the model complexity from parameter precision and matrix topology perspectives. We conducted extensive experiments with a 2-billion parameter USM on a large-scale voice search dataset to evaluate our proposed method. A series of ablation studies validate the effectiveness of up to int4 quantization and 2:4 sparsity. However, a single compression technique fails to recover the performance well under extreme setups including int2 quantization and 1:4 sparsity. By contrast, our proposed method can compress the model to have 9.4% of the size, at the cost of only 7.3% relative word error rate (WER) regressions. We also provided in-depth analyses on the results and discussions on the limitations and potential solutions, which would be valuable for future studies.

{{</citation>}}


### (57/118) On Robustness to Missing Video for Audiovisual Speech Recognition (Oscar Chang et al., 2023)

{{<citation>}}

Oscar Chang, Otavio Braga, Hank Liao, Dmitriy Serdyuk, Olivier Siohan. (2023)  
**On Robustness to Missing Video for Audiovisual Speech Recognition**  

---
Primary Category: eess.AS  
Categories: cs-CV, cs-LG, cs-SD, eess-AS, eess.AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2312.10088v1)  

---


**ABSTRACT**  
It has been shown that learning audiovisual features can lead to improved speech recognition performance over audio-only features, especially for noisy speech. However, in many common applications, the visual features are partially or entirely missing, e.g.~the speaker might move off screen. Multi-modal models need to be robust: missing video frames should not degrade the performance of an audiovisual model to be worse than that of a single-modality audio-only model. While there have been many attempts at building robust models, there is little consensus on how robustness should be evaluated. To address this, we introduce a framework that allows claims about robustness to be evaluated in a precise and testable way. We also conduct a systematic empirical study of the robustness of common audiovisual speech recognition architectures on a range of acoustic noise conditions and test suites. Finally, we show that an architecture-agnostic solution based on cascades can consistently achieve robustness to missing video, even in settings where existing techniques for robustness like dropout fall short.

{{</citation>}}


### (58/118) Revisiting the Entropy Semiring for Neural Speech Recognition (Oscar Chang et al., 2023)

{{<citation>}}

Oscar Chang, Dongseong Hwang, Olivier Siohan. (2023)  
**Revisiting the Entropy Semiring for Neural Speech Recognition**  

---
Primary Category: eess.AS  
Categories: cs-LG, cs-SD, eess-AS, eess.AS  
Keywords: Speech Recognition  
[Paper Link](http://arxiv.org/abs/2312.10087v1)  

---


**ABSTRACT**  
In streaming settings, speech recognition models have to map sub-sequences of speech to text before the full audio stream becomes available. However, since alignment information between speech and text is rarely available during training, models need to learn it in a completely self-supervised way. In practice, the exponential number of possible alignments makes this extremely challenging, with models often learning peaky or sub-optimal alignments. Prima facie, the exponential nature of the alignment space makes it difficult to even quantify the uncertainty of a model's alignment distribution. Fortunately, it has been known for decades that the entropy of a probabilistic finite state transducer can be computed in time linear to the size of the transducer via a dynamic programming reduction based on semirings. In this work, we revisit the entropy semiring for neural speech recognition models, and show how alignment entropy can be used to supervise models through regularization or distillation. We also contribute an open-source implementation of CTC and RNN-T in the semiring framework that includes numerically stable and highly parallel variants of the entropy semiring. Empirically, we observe that the addition of alignment distillation improves the accuracy and latency of an already well-optimized teacher-student distillation model, achieving state-of-the-art performance on the Librispeech dataset in the streaming scenario.

{{</citation>}}


## cs.AI (12)



### (59/118) Revisiting Recommendation Loss Functions through Contrastive Learning (Technical Report) (Dong Li et al., 2023)

{{<citation>}}

Dong Li, Ruoming Jin, Bin Ren. (2023)  
**Revisiting Recommendation Loss Functions through Contrastive Learning (Technical Report)**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.08520v1)  

---


**ABSTRACT**  
Inspired by the success of contrastive learning, we systematically examine recommendation losses, including listwise (softmax), pairwise (BPR), and pointwise (MSE and CCL) losses. In this endeavor, we introduce InfoNCE+, an optimized generalization of InfoNCE with balance coefficients, and highlight its performance advantages, particularly when aligned with our new decoupled contrastive loss, MINE+. We also leverage debiased InfoNCE to debias pointwise recommendation loss (CCL) as Debiased CCL. Interestingly, our analysis reveals that linear models like iALS and EASE are inherently debiased. Empirical results demonstrates the effectiveness of MINE+ and Debiased-CCL.

{{</citation>}}


### (60/118) (Debiased) Contrastive Learning Loss for Recommendation (Technical Report) (Ruoming Jin et al., 2023)

{{<citation>}}

Ruoming Jin, Dong Li. (2023)  
**(Debiased) Contrastive Learning Loss for Recommendation (Technical Report)**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Contrastive Learning  
[Paper Link](http://arxiv.org/abs/2312.08517v1)  

---


**ABSTRACT**  
In this paper, we perform a systemic examination of the recommendation losses, including listwise (softmax), pairwise(BPR), and pointwise (mean-squared error, MSE, and Cosine Contrastive Loss, CCL) losses through the lens of contrastive learning. We introduce and study both debiased InfoNCE and mutual information neural estimator (MINE), for the first time, under the recommendation setting. We also relate and differentiate these two losses with the BPR loss through the lower bound analysis. Furthermore, we present the debiased pointwise loss (for both MSE and CCL) and theoretically certify both iALS and EASE, two of the most popular linear models, are inherently debiased. The empirical experimental results demonstrate the effectiveness of the debiased losses and newly introduced mutual-information losses outperform the existing (biased) ones.

{{</citation>}}


### (61/118) On Diagnostics for Understanding Agent Training Behaviour in Cooperative MARL (Wiem Khlifi et al., 2023)

{{<citation>}}

Wiem Khlifi, Siddarth Singh, Omayma Mahjoub, Ruan de Kock, Abidine Vall, Rihab Gorsane, Arnu Pretorius. (2023)  
**On Diagnostics for Understanding Agent Training Behaviour in Cooperative MARL**  

---
Primary Category: cs.AI  
Categories: I-2-11, I-2-0, A-0, cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08468v1)  

---


**ABSTRACT**  
Cooperative multi-agent reinforcement learning (MARL) has made substantial strides in addressing the distributed decision-making challenges. However, as multi-agent systems grow in complexity, gaining a comprehensive understanding of their behaviour becomes increasingly challenging. Conventionally, tracking team rewards over time has served as a pragmatic measure to gauge the effectiveness of agents in learning optimal policies. Nevertheless, we argue that relying solely on the empirical returns may obscure crucial insights into agent behaviour. In this paper, we explore the application of explainable AI (XAI) tools to gain profound insights into agent behaviour. We employ these diagnostics tools within the context of Level-Based Foraging and Multi-Robot Warehouse environments and apply them to a diverse array of MARL algorithms. We demonstrate how our diagnostics can enhance the interpretability and explainability of MARL systems, providing a better understanding of agent behaviour.

{{</citation>}}


### (62/118) How much can change in a year? Revisiting Evaluation in Multi-Agent Reinforcement Learning (Siddarth Singh et al., 2023)

{{<citation>}}

Siddarth Singh, Omayma Mahjoub, Ruan de Kock, Wiem Khlifi, Abidine Vall, Kale-ab Tessera, Arnu Pretorius. (2023)  
**How much can change in a year? Revisiting Evaluation in Multi-Agent Reinforcement Learning**  

---
Primary Category: cs.AI  
Categories: I-2-11, I-2-0, A-0, cs-AI, cs.AI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.08463v1)  

---


**ABSTRACT**  
Establishing sound experimental standards and rigour is important in any growing field of research. Deep Multi-Agent Reinforcement Learning (MARL) is one such nascent field. Although exciting progress has been made, MARL has recently come under scrutiny for replicability issues and a lack of standardised evaluation methodology, specifically in the cooperative setting. Although protocols have been proposed to help alleviate the issue, it remains important to actively monitor the health of the field. In this work, we extend the database of evaluation methodology previously published by containing meta-data on MARL publications from top-rated conferences and compare the findings extracted from this updated database to the trends identified in their work. Our analysis shows that many of the worrying trends in performance reporting remain. This includes the omission of uncertainty quantification, not reporting all relevant evaluation details and a narrowing of algorithmic development classes. Promisingly, we do observe a trend towards more difficult scenarios in SMAC-v1, which if continued into SMAC-v2 will encourage novel algorithmic development. Our data indicate that replicability needs to be approached more proactively by the MARL community to ensure trust in the field as we move towards exciting new frontiers.

{{</citation>}}


### (63/118) A Survey of Generative AI for Intelligent Transportation Systems (Huan Yan et al., 2023)

{{<citation>}}

Huan Yan, Yong Li. (2023)  
**A Survey of Generative AI for Intelligent Transportation Systems**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI, Generative AI  
[Paper Link](http://arxiv.org/abs/2312.08248v1)  

---


**ABSTRACT**  
Intelligent transportation systems play a crucial role in modern traffic management and optimization, greatly improving traffic efficiency and safety. With the rapid development of generative artificial intelligence (Generative AI) technologies in the fields of image generation and natural language processing, generative AI has also played a crucial role in addressing key issues in intelligent transportation systems, such as data sparsity, difficulty in observing abnormal scenarios, and in modeling data uncertainty. In this review, we systematically investigate the relevant literature on generative AI techniques in addressing key issues in different types of tasks in intelligent transportation systems. First, we introduce the principles of different generative AI techniques, and their potential applications. Then, we classify tasks in intelligent transportation systems into four types: traffic perception, traffic prediction, traffic simulation, and traffic decision-making. We systematically illustrate how generative AI techniques addresses key issues in these four different types of tasks. Finally, we summarize the challenges faced in applying generative AI to intelligent transportation systems, and discuss future research directions based on different application scenarios.

{{</citation>}}


### (64/118) A Novel Energy based Model Mechanism for Multi-modal Aspect-Based Sentiment Analysis (Tianshuo Peng et al., 2023)

{{<citation>}}

Tianshuo Peng, Zuchao Li, Ping Wang, Lefei Zhang, Hai Zhao. (2023)  
**A Novel Energy based Model Mechanism for Multi-modal Aspect-Based Sentiment Analysis**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Sentiment Analysis  
[Paper Link](http://arxiv.org/abs/2312.08084v2)  

---


**ABSTRACT**  
Multi-modal aspect-based sentiment analysis (MABSA) has recently attracted increasing attention. The span-based extraction methods, such as FSUIE, demonstrate strong performance in sentiment analysis due to their joint modeling of input sequences and target labels. However, previous methods still have certain limitations: (i) They ignore the difference in the focus of visual information between different analysis targets (aspect or sentiment). (ii) Combining features from uni-modal encoders directly may not be sufficient to eliminate the modal gap and can cause difficulties in capturing the image-text pairwise relevance. (iii) Existing span-based methods for MABSA ignore the pairwise relevance of target span boundaries. To tackle these limitations, we propose a novel framework called DQPSA for multi-modal sentiment analysis. Specifically, our model contains a Prompt as Dual Query (PDQ) module that uses the prompt as both a visual query and a language query to extract prompt-aware visual information and strengthen the pairwise relevance between visual information and the analysis target. Additionally, we introduce an Energy-based Pairwise Expert (EPE) module that models the boundaries pairing of the analysis target from the perspective of an Energy-based Model. This expert predicts aspect or sentiment span based on pairwise stability. Experiments on three widely used benchmarks demonstrate that DQPSA outperforms previous approaches and achieves a new state-of-the-art performance.

{{</citation>}}


### (65/118) Exploring the Impact of Lay User Feedback for Improving AI Fairness (Evdoxia Taka et al., 2023)

{{<citation>}}

Evdoxia Taka, Yuri Nakao, Ryosuke Sonoda, Takuya Yokota, Lin Luo, Simone Stumpf. (2023)  
**Exploring the Impact of Lay User Feedback for Improving AI Fairness**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08064v2)  

---


**ABSTRACT**  
Fairness in AI is a growing concern for high-stakes decision making. Engaging stakeholders, especially lay users, in fair AI development is promising yet overlooked. Recent efforts explore enabling lay users to provide AI fairness-related feedback, but there is still a lack of understanding of how to integrate users' feedback into an AI model and the impacts of doing so. To bridge this gap, we collected feedback from 58 lay users on the fairness of a XGBoost model trained on the Home Credit dataset, and conducted offline experiments to investigate the effects of retraining models on accuracy, and individual and group fairness. Our work contributes baseline results of integrating user fairness feedback in XGBoost, and a dataset and code framework to bootstrap research in engaging stakeholders in AI fairness. Our discussion highlights the challenges of employing user feedback in AI fairness and points the way to a future application area of interactive machine learning.

{{</citation>}}


### (66/118) PromptBench: A Unified Library for Evaluation of Large Language Models (Kaijie Zhu et al., 2023)

{{<citation>}}

Kaijie Zhu, Qinlin Zhao, Hao Chen, Jindong Wang, Xing Xie. (2023)  
**PromptBench: A Unified Library for Evaluation of Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs-LG, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.07910v1)  

---


**ABSTRACT**  
The evaluation of large language models (LLMs) is crucial to assess their performance and mitigate potential security risks. In this paper, we introduce PromptBench, a unified library to evaluate LLMs. It consists of several key components that are easily used and extended by researchers: prompt construction, prompt engineering, dataset and model loading, adversarial prompt attack, dynamic evaluation protocols, and analysis tools. PromptBench is designed to be an open, general, and flexible codebase for research purposes that can facilitate original study in creating new benchmarks, deploying downstream applications, and designing new evaluation protocols. The code is available at: https://github.com/microsoft/promptbench and will be continuously supported.

{{</citation>}}


### (67/118) Modality Plug-and-Play: Elastic Modality Adaptation in Multimodal LLMs for Embodied AI (Kai Huang et al., 2023)

{{<citation>}}

Kai Huang, Boyuan Yang, Wei Gao. (2023)  
**Modality Plug-and-Play: Elastic Modality Adaptation in Multimodal LLMs for Embodied AI**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: AI, Language Model, QA  
[Paper Link](http://arxiv.org/abs/2312.07886v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) are capable of reasoning over diverse input data modalities through pre-trained encoders. However, the growing diversity of input data modalities prevents incorporating all modalities into LLMs, especially when LLMs are deployed on resource-constrained edge devices for embodied AI applications. Instead, a better option is to adaptively involve only the useful modalities at runtime, depending on the current environmental contexts and task requirements. For such modality adaptation, existing work adopts fixed connections between encoders and the LLM's input layer, leading to high training cost at runtime and ineffective cross-modal interaction. In this paper, we address these limitations by presenting mPnP-LLM, a new technique that allows fully elastic, automated and prompt runtime modality adaptation, by connecting unimodal encoders to a flexible set of last LLM blocks and making such latent connections fully trainable at runtime. Experiments over the nuScenes-QA dataset show that mPnP-LLM can achieve up to 3.7x FLOPs reduction and 30% GPU memory usage reduction, while retaining on-par accuracy with the existing schemes. Under the same compute budget, mPnP-LLM improves the task accuracy by up to 4% compared to the best existing scheme.

{{</citation>}}


### (68/118) Causality Analysis for Evaluating the Security of Large Language Models (Wei Zhao et al., 2023)

{{<citation>}}

Wei Zhao, Zhe Li, Jun Sun. (2023)  
**Causality Analysis for Evaluating the Security of Large Language Models**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: GPT, Language Model, Security  
[Paper Link](http://arxiv.org/abs/2312.07876v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) such as GPT and Llama2 are increasingly adopted in many safety-critical applications. Their security is thus essential. Even with considerable efforts spent on reinforcement learning from human feedback (RLHF), recent studies have shown that LLMs are still subject to attacks such as adversarial perturbation and Trojan attacks. Further research is thus needed to evaluate their security and/or understand the lack of it. In this work, we propose a framework for conducting light-weight causality-analysis of LLMs at the token, layer, and neuron level. We applied our framework to open-source LLMs such as Llama2 and Vicuna and had multiple interesting discoveries. Based on a layer-level causality analysis, we show that RLHF has the effect of overfitting a model to harmful prompts. It implies that such security can be easily overcome by `unusual' harmful prompts. As evidence, we propose an adversarial perturbation method that achieves 100\% attack success rate on the red-teaming tasks of the Trojan Detection Competition 2023. Furthermore, we show the existence of one mysterious neuron in both Llama2 and Vicuna that has an unreasonably high causal effect on the output. While we are uncertain on why such a neuron exists, we show that it is possible to conduct a ``Trojan'' attack targeting that particular neuron to completely cripple the LLM, i.e., we can generate transferable suffixes to prompts that frequently make the LLM produce meaningless responses.

{{</citation>}}


### (69/118) BESTMVQA: A Benchmark Evaluation System for Medical Visual Question Answering (Xiaojie Hong et al., 2023)

{{<citation>}}

Xiaojie Hong, Zixin Song, Liangzhi Li, Xiaoli Wang, Feiyan Liu. (2023)  
**BESTMVQA: A Benchmark Evaluation System for Medical Visual Question Answering**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs-CL, cs.AI  
Keywords: QA, Question Answering  
[Paper Link](http://arxiv.org/abs/2312.07867v1)  

---


**ABSTRACT**  
Medical Visual Question Answering (Med-VQA) is a very important task in healthcare industry, which answers a natural language question with a medical image. Existing VQA techniques in information systems can be directly applied to solving the task. However, they often suffer from (i) the data insufficient problem, which makes it difficult to train the state of the arts (SOTAs) for the domain-specific task, and (ii) the reproducibility problem, that many existing models have not been thoroughly evaluated in a unified experimental setup. To address these issues, this paper develops a Benchmark Evaluation SysTem for Medical Visual Question Answering, denoted by BESTMVQA. Given self-collected clinical data, our system provides a useful tool for users to automatically build Med-VQA datasets, which helps overcoming the data insufficient problem. Users also can conveniently select a wide spectrum of SOTA models from our model library to perform a comprehensive empirical study. With simple configurations, our system automatically trains and evaluates the selected models over a benchmark dataset, and reports the comprehensive results for users to develop new techniques or perform medical practice. Limitations of existing work are overcome (i) by the data generation tool, which automatically constructs new datasets from unstructured clinical data, and (ii) by evaluating SOTAs on benchmark datasets in a unified experimental setup. The demonstration video of our system can be found at https://youtu.be/QkEeFlu1x4A. Our code and data will be available soon.

{{</citation>}}


### (70/118) Large Language Model Enhanced Multi-Agent Systems for 6G Communications (Feibo Jiang et al., 2023)

{{<citation>}}

Feibo Jiang, Li Dong, Yubo Peng, Kezhi Wang, Kun Yang, Cunhua Pan, Dusit Niyato, Octavia A. Dobre. (2023)  
**Large Language Model Enhanced Multi-Agent Systems for 6G Communications**  

---
Primary Category: cs.AI  
Categories: cs-AI, cs.AI  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.07850v1)  

---


**ABSTRACT**  
The rapid development of the Large Language Model (LLM) presents huge opportunities for 6G communications, e.g., network optimization and management by allowing users to input task requirements to LLMs by nature language. However, directly applying native LLMs in 6G encounters various challenges, such as a lack of private communication data and knowledge, limited logical reasoning, evaluation, and refinement abilities. Integrating LLMs with the capabilities of retrieval, planning, memory, evaluation and reflection in agents can greatly enhance the potential of LLMs for 6G communications. To this end, we propose a multi-agent system with customized communication knowledge and tools for solving communication related tasks using natural language, comprising three components: (1) Multi-agent Data Retrieval (MDR), which employs the condensate and inference agents to refine and summarize communication knowledge from the knowledge base, expanding the knowledge boundaries of LLMs in 6G communications; (2) Multi-agent Collaborative Planning (MCP), which utilizes multiple planning agents to generate feasible solutions for the communication related task from different perspectives based on the retrieved knowledge; (3) Multi-agent Evaluation and Reflecxion (MER), which utilizes the evaluation agent to assess the solutions, and applies the reflexion agent and refinement agent to provide improvement suggestions for current solutions. Finally, we validate the effectiveness of the proposed multi-agent system by designing a semantic communication system, as a case study of 6G communications.

{{</citation>}}


## cs.CL (16)



### (71/118) Beyond Accuracy: Automated De-Identification of Large Real-World Clinical Text Datasets (Veysel Kocaman et al., 2023)

{{<citation>}}

Veysel Kocaman, Hasham Ul Haq, David Talby. (2023)  
**Beyond Accuracy: Automated De-Identification of Large Real-World Clinical Text Datasets**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CR, cs-LG, cs.CL  
Keywords: AWS, Azure, ChatGPT, Clinical, GCP, GPT, NER  
[Paper Link](http://arxiv.org/abs/2312.08495v1)  

---


**ABSTRACT**  
Recent research advances achieve human-level accuracy for de-identifying free-text clinical notes on research datasets, but gaps remain in reproducing this in large real-world settings. This paper summarizes lessons learned from building a system used to de-identify over one billion real clinical notes, in a fully automated way, that was independently certified by multiple organizations for production use. A fully automated solution requires a very high level of accuracy that does not require manual review. A hybrid context-based model architecture is described, which outperforms a Named Entity Recogniton (NER) - only model by 10% on the i2b2-2014 benchmark. The proposed system makes 50%, 475%, and 575% fewer errors than the comparable AWS, Azure, and GCP services respectively while also outperforming ChatGPT by 33%. It exceeds 98% coverage of sensitive data across 7 European languages, without a need for fine tuning. A second set of described models enable data obfuscation -- replacing sensitive data with random surrogates -- while retaining name, date, gender, clinical, and format consistency. Both the practical need and the solution architecture that provides for reliable & linked anonymized documents are described.

{{</citation>}}


### (72/118) Efficient Toxic Content Detection by Bootstrapping and Distilling Large Language Models (Jiang Zhang et al., 2023)

{{<citation>}}

Jiang Zhang, Qiong Wu, Yiming Xu, Cheng Cao, Zheng Du, Konstantinos Psounis. (2023)  
**Efficient Toxic Content Detection by Bootstrapping and Distilling Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.08303v1)  

---


**ABSTRACT**  
Toxic content detection is crucial for online services to remove inappropriate content that violates community standards. To automate the detection process, prior works have proposed varieties of machine learning (ML) approaches to train Language Models (LMs) for toxic content detection. However, both their accuracy and transferability across datasets are limited. Recently, Large Language Models (LLMs) have shown promise in toxic content detection due to their superior zero-shot and few-shot in-context learning ability as well as broad transferability on ML tasks. However, efficiently designing prompts for LLMs remains challenging. Moreover, the high run-time cost of LLMs may hinder their deployments in production. To address these challenges, in this work, we propose BD-LLM, a novel and efficient approach to Bootstrapping and Distilling LLMs for toxic content detection. Specifically, we design a novel prompting method named Decision-Tree-of-Thought (DToT) to bootstrap LLMs' detection performance and extract high-quality rationales. DToT can automatically select more fine-grained context to re-prompt LLMs when their responses lack confidence. Additionally, we use the rationales extracted via DToT to fine-tune student LMs. Our experimental results on various datasets demonstrate that DToT can improve the accuracy of LLMs by up to 4.6%. Furthermore, student LMs fine-tuned with rationales extracted via DToT outperform baselines on all datasets with up to 16.9\% accuracy improvement, while being more than 60x smaller than conventional LLMs. Finally, we observe that student LMs fine-tuned with rationales exhibit better cross-dataset transferability.

{{</citation>}}


### (73/118) Conceptualizing Suicidal Behavior: Utilizing Explanations of Predicted Outcomes to Analyze Longitudinal Social Media Data (Van Minh Nguyen et al., 2023)

{{<citation>}}

Van Minh Nguyen, Nasheen Nur, William Stern, Thomas Mercer, Chiradeep Sen, Siddhartha Bhattacharyya, Victor Tumbiolo, Seng Jhing Goh. (2023)  
**Conceptualizing Suicidal Behavior: Utilizing Explanations of Predicted Outcomes to Analyze Longitudinal Social Media Data**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-CY, cs-SI, cs.CL  
Keywords: AI, Attention, Social Media  
[Paper Link](http://arxiv.org/abs/2312.08299v1)  

---


**ABSTRACT**  
The COVID-19 pandemic has escalated mental health crises worldwide, with social isolation and economic instability contributing to a rise in suicidal behavior. Suicide can result from social factors such as shame, abuse, abandonment, and mental health conditions like depression, Post-Traumatic Stress Disorder (PTSD), Attention-Deficit/Hyperactivity Disorder (ADHD), anxiety disorders, and bipolar disorders. As these conditions develop, signs of suicidal ideation may manifest in social media interactions. Analyzing social media data using artificial intelligence (AI) techniques can help identify patterns of suicidal behavior, providing invaluable insights for suicide prevention agencies, professionals, and broader community awareness initiatives. Machine learning algorithms for this purpose require large volumes of accurately labeled data. Previous research has not fully explored the potential of incorporating explanations in analyzing and labeling longitudinal social media data. In this study, we employed a model explanation method, Layer Integrated Gradients, on top of a fine-tuned state-of-the-art language model, to assign each token from Reddit users' posts an attribution score for predicting suicidal ideation. By extracting and analyzing attributions of tokens from the data, we propose a methodology for preliminary screening of social media posts for suicidal ideation without using large language models during inference.

{{</citation>}}


### (74/118) High-throughput Biomedical Relation Extraction for Semi-Structured Web Articles Empowered by Large Language Models (Songchi Zhou et al., 2023)

{{<citation>}}

Songchi Zhou, Sheng Yu. (2023)  
**High-throughput Biomedical Relation Extraction for Semi-Structured Web Articles Empowered by Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, GPT-4, Language Model, Relation Extraction  
[Paper Link](http://arxiv.org/abs/2312.08274v3)  

---


**ABSTRACT**  
Objective: To develop a high-throughput biomedical relation extraction system that takes advantage of the large language models' (LLMs) reading comprehension ability and biomedical world knowledge in a scalable and evidential manner. Methods: We formulate the relation extraction task as a simple binary classification problem for large language models such as ChatGPT. Specifically, LLMs make the decision based on the external corpus and its world knowledge, giving the reason for the judgment to factual verification. This method is tailored for semi-structured web articles, wherein we designate the main title as the tail entity and explicitly incorporate it into the context, and the potential head entities are matched based on a biomedical thesaurus. Moreover, lengthy contents are sliced into text chunks, embedded, and retrieved with additional embedding models, ensuring compatibility with the context window size constraints of available open-source LLMs. Results: Using an open-source LLM, we extracted 304315 relation triplets of three distinct relation types from four reputable biomedical websites. To assess the efficacy of the basic pipeline employed for biomedical relation extraction, we curated a benchmark dataset annotated by a medical expert. Evaluation results indicate that the pipeline exhibits performance comparable to that of GPT-4. Case studies further illuminate challenges faced by contemporary LLMs in the context of biomedical relation extraction for semi-structured web articles. Conclusion: The proposed method has demonstrated its effectiveness in leveraging the strengths of LLMs for high-throughput biomedical relation extraction. Its adaptability is evident, as it can be seamlessly extended to diverse semi-structured biomedical websites, facilitating the extraction of various types of biomedical relations with ease.

{{</citation>}}


### (75/118) Towards Model-Based Data Acquisition for Subjective Multi-Task NLP Problems (Kamil Kanclerz et al., 2023)

{{<citation>}}

Kamil Kanclerz, Julita Bielaniewicz, Marcin Gruza, Jan Kocon, Stanisław Woźniak, Przemysław Kazienko. (2023)  
**Towards Model-Based Data Acquisition for Subjective Multi-Task NLP Problems**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: NLP  
[Paper Link](http://arxiv.org/abs/2312.08198v1)  

---


**ABSTRACT**  
Data annotated by humans is a source of knowledge by describing the peculiarities of the problem and therefore fueling the decision process of the trained model. Unfortunately, the annotation process for subjective natural language processing (NLP) problems like offensiveness or emotion detection is often very expensive and time-consuming. One of the inevitable risks is to spend some of the funds and annotator effort on annotations that do not provide any additional knowledge about the specific task. To minimize these costs, we propose a new model-based approach that allows the selection of tasks annotated individually for each text in a multi-task scenario. The experiments carried out on three datasets, dozens of NLP tasks, and thousands of annotations show that our method allows up to 40% reduction in the number of annotations with negligible loss of knowledge. The results also emphasize the need to collect a diverse amount of data required to efficiently train a model, depending on the subjectivity of the annotation task. We also focused on measuring the relation between subjective tasks by evaluating the model in single-task and multi-task scenarios. Moreover, for some datasets, training only on the labels predicted by our model improved the efficiency of task selection as a self-supervised learning regularization technique.

{{</citation>}}


### (76/118) CoRTEx: Contrastive Learning for Representing Terms via Explanations with Applications on Constructing Biomedical Knowledge Graphs (Huaiyuan Ying et al., 2023)

{{<citation>}}

Huaiyuan Ying, Zhengyun Zhao, Yang Zhao, Sihang Zeng, Sheng Yu. (2023)  
**CoRTEx: Contrastive Learning for Representing Terms via Explanations with Applications on Constructing Biomedical Knowledge Graphs**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: ChatGPT, Contrastive Learning, GPT, Knowledge Graph, Language Model  
[Paper Link](http://arxiv.org/abs/2312.08036v1)  

---


**ABSTRACT**  
Objective: Biomedical Knowledge Graphs play a pivotal role in various biomedical research domains. Concurrently, term clustering emerges as a crucial step in constructing these knowledge graphs, aiming to identify synonymous terms. Due to a lack of knowledge, previous contrastive learning models trained with Unified Medical Language System (UMLS) synonyms struggle at clustering difficult terms and do not generalize well beyond UMLS terms. In this work, we leverage the world knowledge from Large Language Models (LLMs) and propose Contrastive Learning for Representing Terms via Explanations (CoRTEx) to enhance term representation and significantly improves term clustering. Materials and Methods: The model training involves generating explanations for a cleaned subset of UMLS terms using ChatGPT. We employ contrastive learning, considering term and explanation embeddings simultaneously, and progressively introduce hard negative samples. Additionally, a ChatGPT-assisted BIRCH algorithm is designed for efficient clustering of a new ontology. Results: We established a clustering test set and a hard negative test set, where our model consistently achieves the highest F1 score. With CoRTEx embeddings and the modified BIRCH algorithm, we grouped 35,580,932 terms from the Biomedical Informatics Ontology System (BIOS) into 22,104,559 clusters with O(N) queries to ChatGPT. Case studies highlight the model's efficacy in handling challenging samples, aided by information from explanations. Conclusion: By aligning terms to their explanations, CoRTEx demonstrates superior accuracy over benchmark models and robustness beyond its training set, and it is suitable for clustering terms for large-scale biomedical ontologies.

{{</citation>}}


### (77/118) Helping Language Models Learn More: Multi-dimensional Task Prompt for Few-shot Tuning (Jinta Weng et al., 2023)

{{<citation>}}

Jinta Weng, Jiarui Zhang, Yue Hu, Daidong Fa, Xiaofeng Xuand, Heyan Huang. (2023)  
**Helping Language Models Learn More: Multi-dimensional Task Prompt for Few-shot Tuning**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: ChatGPT, GPT, Language Model  
[Paper Link](http://arxiv.org/abs/2312.08027v1)  

---


**ABSTRACT**  
Large language models (LLMs) can be used as accessible and intelligent chatbots by constructing natural language queries and directly inputting the prompt into the large language model. However, different prompt' constructions often lead to uncertainty in the answers and thus make it hard to utilize the specific knowledge of LLMs (like ChatGPT). To alleviate this, we use an interpretable structure to explain the prompt learning principle in LLMs, which certificates that the effectiveness of language models is determined by position changes of the task's related tokens. Therefore, we propose MTPrompt, a multi-dimensional task prompt learning method consisting based on task-related object, summary, and task description information. By automatically building and searching for appropriate prompts, our proposed MTPrompt achieves the best results on few-shot samples setting and five different datasets. In addition, we demonstrate the effectiveness and stability of our method in different experimental settings and ablation experiments. In interaction with large language models, embedding more task-related information into prompts will make it easier to stimulate knowledge embedded in large language models.

{{</citation>}}


### (78/118) SLJP: Semantic Extraction based Legal Judgment Prediction (Prameela Madambakam et al., 2023)

{{<citation>}}

Prameela Madambakam, Shathanaa Rajmohan, Himangshu Sharma, Tummepalli Anka Chandrahas Purushotham Gupta. (2023)  
**SLJP: Semantic Extraction based Legal Judgment Prediction**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Legal  
[Paper Link](http://arxiv.org/abs/2312.07979v1)  

---


**ABSTRACT**  
Legal Judgment Prediction (LJP) is a judicial assistance system that recommends the legal components such as applicable statues, prison term and penalty term by analyzing the given input case document. Indian legal system is in the need of technical assistance such as artificial intelligence to solve the crores of pending cases in various courts for years and its being increased day to day. Most of the existing Indian models did not adequately concentrate on the semantics embedded in the fact description (FD) that impacts the decision. The proposed semantic extraction based LJP (SLJP) model provides the advantages of pretrained transformers for complex unstructured legal case document understanding and to generate embeddings. The model draws the in-depth semantics of the given FD at multiple levels i.e., chunk and case document level by following the divide and conquer approach. It creates the concise view of the given fact description using the extracted semantics as per the original court case document structure and predicts judgment using attention mechanism. We tested the model performance on two available Indian datasets Indian Legal Documents corpus (ILDC) and Indian Legal Statue Identification (ILSI) and got promising results. Also shown the highest performance and less performance degradation for increased epochs than base models on ILDC dataset.

{{</citation>}}


### (79/118) Robust Few-Shot Named Entity Recognition with Boundary Discrimination and Correlation Purification (Xiaojun Xue et al., 2023)

{{<citation>}}

Xiaojun Xue, Chunxia Zhang, Tianxiang Xu, Zhendong Niu. (2023)  
**Robust Few-Shot Named Entity Recognition with Boundary Discrimination and Correlation Purification**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: Few-Shot, NER, Named Entity Recognition  
[Paper Link](http://arxiv.org/abs/2312.07961v1)  

---


**ABSTRACT**  
Few-shot named entity recognition (NER) aims to recognize novel named entities in low-resource domains utilizing existing knowledge. However, the present few-shot NER models assume that the labeled data are all clean without noise or outliers, and there are few works focusing on the robustness of the cross-domain transfer learning ability to textual adversarial attacks in Few-shot NER. In this work, we comprehensively explore and assess the robustness of few-shot NER models under textual adversarial attack scenario, and found the vulnerability of existing few-shot NER models. Furthermore, we propose a robust two-stage few-shot NER method with Boundary Discrimination and Correlation Purification (BDCP). Specifically, in the span detection stage, the entity boundary discriminative module is introduced to provide a highly distinguishing boundary representation space to detect entity spans. In the entity typing stage, the correlations between entities and contexts are purified by minimizing the interference information and facilitating correlation generalization to alleviate the perturbations caused by textual adversarial attacks. In addition, we construct adversarial examples for few-shot NER based on public datasets Few-NERD and Cross-Dataset. Comprehensive evaluations on those two groups of few-shot NER datasets containing adversarial examples demonstrate the robustness and superiority of the proposed method.

{{</citation>}}


### (80/118) A Survey of Text Watermarking in the Era of Large Language Models (Aiwei Liu et al., 2023)

{{<citation>}}

Aiwei Liu, Leyi Pan, Yijian Lu, Jingjing Li, Xuming Hu, Lijie Wen, Irwin King, Philip S. Yu. (2023)  
**A Survey of Text Watermarking in the Era of Large Language Models**  

---
Primary Category: cs.CL  
Categories: 68T50, I-2-7, cs-CL, cs.CL  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.07913v2)  

---


**ABSTRACT**  
In recent years, significant advancements have been made in the text generation capabilities of Large Language Models (LLMs), demonstrating exceptional performance in downstream tasks such as abstract summarization, dialogue generation, and data-to-text conversion. However, their generative abilities also pose risks such as the rapid spread of fake news, infringement of datasets/LLM copyrights, and challenges to academic integrity. Text watermarking technology emerges as a potential solution. By embedding invisible yet detectable patterns in generated texts, it helps in tracking and verifying text origins, thus preventing misuse and piracy.   This survey aims to comprehensively summarize current text watermarking technologies, covering three main aspects: (1) an overview and comparison of different text watermarking techniques; (2) evaluation methods for text watermarking algorithms, including their success rate, impact on text quality, robustness, and unforgeability; (3) potential applications of text watermarking technologies. This survey aims to help researchers thoroughly understanding the text watermarking technologies, thereby fostering further development.

{{</citation>}}


### (81/118) Beyond English: Evaluating LLMs for Arabic Grammatical Error Correction (Sang Yun Kwon et al., 2023)

{{<citation>}}

Sang Yun Kwon, Gagan Bhatia, El Moatez Billah Nagoudi, Muhammad Abdul-Mageed. (2023)  
**Beyond English: Evaluating LLMs for Arabic Grammatical Error Correction**  

---
Primary Category: cs.CL  
Categories: cs-AI, cs-CL, cs.CL  
Keywords: GPT, GPT-4, NLP, QA  
[Paper Link](http://arxiv.org/abs/2312.08400v1)  

---


**ABSTRACT**  
Large language models (LLMs) finetuned to follow human instruction have recently exhibited significant capabilities in various English NLP tasks. However, their performance in grammatical error correction (GEC), especially on languages other than English, remains significantly unexplored. In this work, we evaluate the abilities of instruction finetuned LLMs in Arabic GEC, a complex task due to Arabic's rich morphology. Our findings suggest that various prompting methods, coupled with (in-context) few-shot learning, demonstrate considerable effectiveness, with GPT-4 achieving up to $65.49$ F$_{1}$ score under expert prompting (approximately $5$ points higher than our established baseline). Despite these positive results, we find that instruction finetuned models, regardless of their size, are still outperformed by fully finetuned ones, even if they are significantly smaller in size. This disparity highlights substantial room for improvements for LLMs. Inspired by methods used in low-resource machine translation, we also develop a method exploiting synthetic data that significantly outperforms previous models on two standard Arabic benchmarks. Our best model achieves a new SOTA on Arabic GEC, with $73.29$ and $73.26$ F$_{1}$ on the 2014 and 2015 QALB datasets, respectively, compared to peer-reviewed published baselines.

{{</citation>}}


### (82/118) Learn or Recall? Revisiting Incremental Learning with Pre-trained Language Models (Junhao Zheng et al., 2023)

{{<citation>}}

Junhao Zheng, Shengjie Qiu, Qianli Ma. (2023)  
**Learn or Recall? Revisiting Incremental Learning with Pre-trained Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: Language Model, NLP, Named Entity Recognition, Natural Language Processing, Relation Extraction, Text Classification  
[Paper Link](http://arxiv.org/abs/2312.07887v1)  

---


**ABSTRACT**  
Incremental Learning (IL) has been a long-standing problem in both vision and Natural Language Processing (NLP) communities. In recent years, as Pre-trained Language Models (PLMs) have achieved remarkable progress in various NLP downstream tasks, utilizing PLMs as backbones has become a common practice in recent research of IL in NLP. Most assume that catastrophic forgetting is the biggest obstacle to achieving superior IL performance and propose various techniques to overcome this issue. However, we find that this assumption is problematic. Specifically, we revisit more than 20 methods on four classification tasks (Text Classification, Intent Classification, Relation Extraction, and Named Entity Recognition) under the two most popular IL settings (Class-Incremental and Task-Incremental) and reveal that most of them severely underestimate the inherent anti-forgetting ability of PLMs. Based on the observation, we propose a frustratingly easy method called SEQ* for IL with PLMs. The results show that SEQ* has competitive or superior performance compared to state-of-the-art (SOTA) IL methods and requires considerably less trainable parameters and training time. These findings urge us to revisit the IL with PLMs and encourage future studies to have a fundamental understanding of the catastrophic forgetting in PLMs. The data, code and scripts are publicly available at https://github.com/zzz47zzz/pretrained-lm-for-incremental-learning.

{{</citation>}}


### (83/118) Graph vs. Sequence: An Empirical Study on Knowledge Forms for Knowledge-Grounded Dialogue (Yizhe Yang et al., 2023)

{{<citation>}}

Yizhe Yang, Heyan Huang, Yihang Liu, Yang Gao. (2023)  
**Graph vs. Sequence: An Empirical Study on Knowledge Forms for Knowledge-Grounded Dialogue**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Dialog, Dialogue  
[Paper Link](http://arxiv.org/abs/2312.07868v1)  

---


**ABSTRACT**  
Knowledge-grounded dialogue is a task of generating an informative response based on both the dialogue history and external knowledge source. In general, there are two forms of knowledge: manually annotated knowledge graphs and knowledge text from website. From various evaluation viewpoints, each type of knowledge has advantages and downsides. To further distinguish the principles and determinants from the intricate factors, we conduct a thorough experiment and study on the task to answer three essential questions. The questions involve the choice of appropriate knowledge form, the degree of mutual effects between knowledge and the model selection, and the few-shot performance of knowledge. Supported by statistical shreds of evidence, we offer conclusive solutions and sensible suggestions for directions and standards of future research.

{{</citation>}}


### (84/118) Abusive Span Detection for Vietnamese Narrative Texts (Nhu-Thanh Nguyen et al., 2023)

{{<citation>}}

Nhu-Thanh Nguyen, Khoa Thi-Kim Phan, Duc-Vu Nguyen, Ngan Luu-Thuy Nguyen. (2023)  
**Abusive Span Detection for Vietnamese Narrative Texts**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs-LG, cs.CL  
Keywords: BERT, LSTM, NLP  
[Paper Link](http://arxiv.org/abs/2312.07831v1)  

---


**ABSTRACT**  
Abuse in its various forms, including physical, psychological, verbal, sexual, financial, and cultural, has a negative impact on mental health. However, there are limited studies on applying natural language processing (NLP) in this field in Vietnam. Therefore, we aim to contribute by building a human-annotated Vietnamese dataset for detecting abusive content in Vietnamese narrative texts. We sourced these texts from VnExpress, Vietnam's popular online newspaper, where readers often share stories containing abusive content. Identifying and categorizing abusive spans in these texts posed significant challenges during dataset creation, but it also motivated our research. We experimented with lightweight baseline models by freezing PhoBERT and XLM-RoBERTa and using their hidden states in a BiLSTM to assess the complexity of the dataset. According to our experimental results, PhoBERT outperforms other models in both labeled and unlabeled abusive span detection tasks. These results indicate that it has the potential for future improvements.

{{</citation>}}


### (85/118) A Deep Learning-Based System for Automatic Case Summarization (Minh Duong et al., 2023)

{{<citation>}}

Minh Duong, Long Nguyen, Yen Vuong, Trong Le, Ha-Thanh Nguyen. (2023)  
**A Deep Learning-Based System for Automatic Case Summarization**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: Summarization  
[Paper Link](http://arxiv.org/abs/2312.07824v1)  

---


**ABSTRACT**  
This paper presents a deep learning-based system for efficient automatic case summarization. Leveraging state-of-the-art natural language processing techniques, the system offers both supervised and unsupervised methods to generate concise and relevant summaries of lengthy legal case documents. The user-friendly interface allows users to browse the system's database of legal case documents, select their desired case, and choose their preferred summarization method. The system generates comprehensive summaries for each subsection of the legal text as well as an overall summary. This demo streamlines legal case document analysis, potentially benefiting legal professionals by reducing workload and increasing efficiency. Future work will focus on refining summarization techniques and exploring the application of our methods to other types of legal texts.

{{</citation>}}


### (86/118) Native Language Identification with Large Language Models (Wei Zhang et al., 2023)

{{<citation>}}

Wei Zhang, Alexandre Salle. (2023)  
**Native Language Identification with Large Language Models**  

---
Primary Category: cs.CL  
Categories: cs-CL, cs.CL  
Keywords: GPT, GPT-4, Language Identification, Language Model, NLI  
[Paper Link](http://arxiv.org/abs/2312.07819v1)  

---


**ABSTRACT**  
We present the first experiments on Native Language Identification (NLI) using LLMs such as GPT-4. NLI is the task of predicting a writer's first language by analyzing their writings in a second language, and is used in second language acquisition and forensic linguistics. Our results show that GPT models are proficient at NLI classification, with GPT-4 setting a new performance record of 91.7% on the benchmark TOEFL11 test set in a zero-shot setting. We also show that unlike previous fully-supervised settings, LLMs can perform NLI without being limited to a set of known classes, which has practical implications for real-world applications. Finally, we also show that LLMs can provide justification for their choices, providing reasoning based on spelling errors, syntactic patterns, and usage of directly translated linguistic patterns.

{{</citation>}}


## cs.SE (3)



### (87/118) E&V: Prompting Large Language Models to Perform Static Analysis by Pseudo-code Execution and Verification (Yu Hao et al., 2023)

{{<citation>}}

Yu Hao, Weiteng Chen, Ziqiao Zhou, Weidong Cui. (2023)  
**E&V: Prompting Large Language Models to Perform Static Analysis by Pseudo-code Execution and Verification**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: GPT, GPT-4, Language Model  
[Paper Link](http://arxiv.org/abs/2312.08477v1)  

---


**ABSTRACT**  
Static analysis, the process of examining code without executing it, is crucial for identifying software issues. Yet, static analysis is hampered by its complexity and the need for customization for different targets. Traditional static analysis tools require extensive human effort and are often limited to specific target programs and programming languages. Recent advancements in Large Language Models (LLMs), such as GPT-4 and Llama, offer new capabilities for software engineering tasks. However, their application in static analysis, especially in understanding complex code structures, remains under-explored. This paper introduces a novel approach named E&V , which leverages LLMs to perform static analysis. Specifically, E&V employs LLMs to simulate the execution of pseudo-code, effectively conducting static analysis encoded in the pseudo-code with minimal human effort, thereby improving the accuracy of results. E&V includes a verification process for pseudo-code execution without needing an external oracle. This process allows E&V to mitigate hallucinations of LLMs and enhance the accuracy of static analysis results. We have implemented E&V in a prototype tool designed for triaging crashes through backward taint analysis. This prototype, paired with GPT-4-32k, has been applied to triage 170 recently fixed Linux kernel bugs across seven bug categories. Our experiments demonstrate that the prototype correctly identifies the blamed function in 81.2% of the cases. Additionally, we observe that our novel verification process significantly improves the accuracy, increasing it from 28.2% to 81.2%.

{{</citation>}}


### (88/118) GuardRails: Automated Suggestions for Clarifying Ambiguous Purpose Statements (Mrigank Pawagi et al., 2023)

{{<citation>}}

Mrigank Pawagi, Viraj Kumar. (2023)  
**GuardRails: Automated Suggestions for Clarifying Ambiguous Purpose Statements**  

---
Primary Category: cs.SE  
Categories: cs-SE, cs.SE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.08189v1)  

---


**ABSTRACT**  
Before implementing a function, programmers are encouraged to write a purpose statement i.e., a short, natural-language explanation of what the function computes. A purpose statement may be ambiguous i.e., it may fail to specify the intended behaviour when two or more inequivalent computations are plausible on certain inputs. Our paper makes four contributions. First, we propose a novel heuristic that suggests such inputs using Large Language Models (LLMs). Using these suggestions, the programmer may choose to clarify the purpose statement (e.g., by providing a functional example that specifies the intended behaviour on such an input). Second, to assess the quality of inputs suggested by our heuristic, and to facilitate future research, we create an open dataset of purpose statements with known ambiguities. Third, we compare our heuristic against GitHub Copilot's Chat feature, which can suggest similar inputs when prompted to generate unit tests. Fourth, we provide an open-source implementation of our heuristic as an extension to Visual Studio Code for the Python programming language, where purpose statements and functional examples are specified as docstrings and doctests respectively. We believe that this tool will be particularly helpful to novice programmers and instructors.

{{</citation>}}


### (89/118) Breaking the Silence: the Threats of Using LLMs in Software Engineering (June Sallou et al., 2023)

{{<citation>}}

June Sallou, Thomas Durieux, Annibale Panichella. (2023)  
**Breaking the Silence: the Threats of Using LLMs in Software Engineering**  

---
Primary Category: cs.SE  
Categories: cs-LG, cs-SE, cs.SE  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.08055v1)  

---


**ABSTRACT**  
Large Language Models (LLMs) have gained considerable traction within the Software Engineering (SE) community, impacting various SE tasks from code completion to test generation, from program repair to code summarization. Despite their promise, researchers must still be careful as numerous intricate factors can influence the outcomes of experiments involving LLMs. This paper initiates an open discussion on potential threats to the validity of LLM-based research including issues such as closed-source models, possible data leakage between LLM training data and research evaluation, and the reproducibility of LLM-based findings. In response, this paper proposes a set of guidelines tailored for SE researchers and Language Model (LM) providers to mitigate these concerns. The implications of the guidelines are illustrated using existing good practices followed by LLM providers and a practical example for SE researchers in the context of test case generation.

{{</citation>}}


## cs.CY (2)



### (90/118) Culturally Responsive Artificial Intelligence -- Problems, Challenges and Solutions (Natalia Ożegalska-Łukasik et al., 2023)

{{<citation>}}

Natalia Ożegalska-Łukasik, Szymon Łukasik. (2023)  
**Culturally Responsive Artificial Intelligence -- Problems, Challenges and Solutions**  

---
Primary Category: cs.CY  
Categories: cs-AI, cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08467v1)  

---


**ABSTRACT**  
In the contemporary interconnected world, the concept of cultural responsibility occupies paramount importance. As the lines between nations become less distinct, it is incumbent upon individuals, communities, and institutions to assume the responsibility of safeguarding and valuing the landscape of diverse cultures that constitute our global society. This paper explores the socio-cultural and ethical challenges stemming from the implementation of AI algorithms and highlights the necessity for their culturally responsive development. It also offers recommendations on essential elements required to enhance AI systems' adaptability to meet the demands of contemporary multicultural societies. The paper highlights the need for further multidisciplinary research to create AI models that effectively address these challenges. It also advocates the significance of AI enculturation and underlines the importance of regulatory measures to promote cultural responsibility in AI systems.

{{</citation>}}


### (91/118) Safeguarding the safeguards: How best to promote AI alignment in the public interest (Oliver Guest et al., 2023)

{{<citation>}}

Oliver Guest, Michael Aird, Seán Ó hÉigeartaigh. (2023)  
**Safeguarding the safeguards: How best to promote AI alignment in the public interest**  

---
Primary Category: cs.CY  
Categories: cs-CY, cs.CY  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08039v2)  

---


**ABSTRACT**  
AI alignment work is important from both a commercial and a safety lens. With this paper, we aim to help actors who support alignment efforts to make these efforts as effective as possible, and to avoid potential adverse effects. We begin by suggesting that institutions that are trying to act in the public interest (such as governments) should aim to support specifically alignment work that reduces accident or misuse risks. We then describe four problems which might cause alignment efforts to be counterproductive, increasing large-scale AI risks. We suggest mitigations for each problem. Finally, we make a broader recommendation that institutions trying to act in the public interest should think systematically about how to make their alignment efforts as effective, and as likely to be beneficial, as possible.

{{</citation>}}


## cs.DB (2)



### (92/118) CUTTANA: Scalable Graph Partitioning for Faster Distributed Graph Databases and Analytics (Milad Rezaei Hajidehi et al., 2023)

{{<citation>}}

Milad Rezaei Hajidehi, Sraavan Sridhar, Margo Seltzer. (2023)  
**CUTTANA: Scalable Graph Partitioning for Faster Distributed Graph Databases and Analytics**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs-DC, cs.DB  
Keywords: Twitter  
[Paper Link](http://arxiv.org/abs/2312.08356v1)  

---


**ABSTRACT**  
Graph partitioning plays a pivotal role in various distributed graph processing applications, including graph analytics, graph neural network training, and distributed graph databases. Graphs that require distributed settings are often too large to fit in the main memory of a single machine. This challenge renders traditional in-memory graph partitioners infeasible, leading to the emergence of streaming solutions. Streaming partitioners produce lower-quality partitions because they work from partial information and must make premature decisions before they have a complete view of a vertex's neighborhood. We introduce CUTTANA, a streaming graph partitioner that partitions massive graphs (Web/Twitter scale) with superior quality compared to existing streaming solutions. CUTTANA uses a novel buffering technique that prevents the premature assignment of vertices to partitions and a scalable coarsening and refinement technique that enables a complete graph view, improving the intermediate assignment made by a streaming partitioner. We implemented a parallel version for CUTTANA that offers nearly the same partitioning latency as existing streaming partitioners.   Our experimental analysis shows that CUTTANA consistently yields better partitioning quality than existing state-of-the-art streaming vertex partitioners in terms of both edge-cut and communication volume metrics. We also evaluate the workload latencies that result from using CUTTANA and other partitioners in distributed graph analytics and databases. CUTTANA outperforms the other methods in most scenarios (algorithms, datasets). In analytics applications, CUTTANA improves runtime performance by up to 59% compared to various streaming partitioners (HDRF, Fennel, Ginger, HeiStream). In graph database tasks, CUTTANA results in higher query throughput by up to 23%, without hurting tail latency.

{{</citation>}}


### (93/118) Combined Approximations for Uniform Operational Consistent Query Answering (Marco Calautti et al., 2023)

{{<citation>}}

Marco Calautti, Ester Livshits, Andreas Pieris, Markus Schneider. (2023)  
**Combined Approximations for Uniform Operational Consistent Query Answering**  

---
Primary Category: cs.DB  
Categories: cs-DB, cs.DB  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.08038v1)  

---


**ABSTRACT**  
Operational consistent query answering (CQA) is a recent framework for CQA based on revised definitions of repairs, which are built by applying a sequence of operations (e.g., fact deletions) starting from an inconsistent database until we reach a database that is consistent w.r.t. the given set of constraints. It has been recently shown that there are efficient approximations for computing the percentage of repairs, as well as of sequences of operations leading to repairs, that entail a given query when we focus on primary keys, conjunctive queries, and assuming the query is fixed (i.e., in data complexity). However, it has been left open whether such approximations exist when the query is part of the input (i.e., in combined complexity). We show that this is the case when we focus on self-join-free conjunctive queries of bounded generelized hypertreewidth. We also show that it is unlikely that efficient approximation schemes exist once we give up one of the adopted syntactic restrictions, i.e., self-join-freeness or bounding the generelized hypertreewidth. Towards the desired approximation schemes, we introduce a novel counting complexity class, called SpanTL, show that each problem in SpanTL admits an efficient approximation scheme by using a recent approximability result in the context of tree automata, and then place the problems of interest in SpanTL.

{{</citation>}}


## cs.IR (3)



### (94/118) Look Before You Leap: A Universal Emergent Decomposition of Retrieval Tasks in Language Models (Alexandre Variengien et al., 2023)

{{<citation>}}

Alexandre Variengien, Eric Winsor. (2023)  
**Look Before You Leap: A Universal Emergent Decomposition of Retrieval Tasks in Language Models**  

---
Primary Category: cs.IR  
Categories: cs-CL, cs-IR, cs-LG, cs.IR  
Keywords: Language Model  
[Paper Link](http://arxiv.org/abs/2312.10091v1)  

---


**ABSTRACT**  
When solving challenging problems, language models (LMs) are able to identify relevant information from long and complicated contexts. To study how LMs solve retrieval tasks in diverse situations, we introduce ORION, a collection of structured retrieval tasks spanning six domains, from text understanding to coding. Each task in ORION can be represented abstractly by a request (e.g. a question) that retrieves an attribute (e.g. the character name) from a context (e.g. a story). We apply causal analysis on 18 open-source language models with sizes ranging from 125 million to 70 billion parameters. We find that LMs internally decompose retrieval tasks in a modular way: middle layers at the last token position process the request, while late layers retrieve the correct entity from the context. After causally enforcing this decomposition, models are still able to solve the original task, preserving 70% of the original correct token probability in 98 of the 106 studied model-task pairs. We connect our macroscopic decomposition with a microscopic description by performing a fine-grained case study of a question-answering task on Pythia-2.8b. Building on our high-level understanding, we demonstrate a proof of concept application for scalable internal oversight of LMs to mitigate prompt-injection while requiring human supervision on only a single input. Our solution improves accuracy drastically (from 15.5% to 97.5% on Pythia-12b). This work presents evidence of a universal emergent modular processing of tasks across varied domains and models and is a pioneering effort in applying interpretability for scalable internal oversight of LMs.

{{</citation>}}


### (95/118) Improving search relevance of Azure Cognitive Search by Bayesian optimization (Nitin Agarwal et al., 2023)

{{<citation>}}

Nitin Agarwal, Ashish Kumar, Kiran R, Manish Gupta, Laurent Boué. (2023)  
**Improving search relevance of Azure Cognitive Search by Bayesian optimization**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs-LG, cs.IR  
Keywords: Azure  
[Paper Link](http://arxiv.org/abs/2312.08021v1)  

---


**ABSTRACT**  
Azure Cognitive Search (ACS) has emerged as a major contender in "Search as a Service" cloud products in recent years. However, one of the major challenges for ACS users is to improve the relevance of the search results for their specific usecases. In this paper, we propose a novel method to find the optimal ACS configuration that maximizes search relevance for a specific usecase (product search, document search...) The proposed solution improves key online marketplace metrics such as click through rates (CTR) by formulating the search relevance problem as hyperparameter tuning. We have observed significant improvements in real-world search call to action (CTA) rate in multiple marketplaces by introducing optimized weights generated from the proposed approach.

{{</citation>}}


### (96/118) Exploring Popularity Bias in Session-based Recommendation (Haowen Wang, 2023)

{{<citation>}}

Haowen Wang. (2023)  
**Exploring Popularity Bias in Session-based Recommendation**  

---
Primary Category: cs.IR  
Categories: cs-AI, cs-IR, cs-LG, cs.IR  
Keywords: Bias  
[Paper Link](http://arxiv.org/abs/2312.07855v1)  

---


**ABSTRACT**  
Existing work has revealed that large-scale offline evaluation of recommender systems for user-item interactions is prone to bias caused by the deployed system itself, as a form of closed loop feedback. Many adopt the \textit{propensity} concept to analyze or mitigate this empirical issue. In this work, we extend the analysis to session-based setup and adapted propensity calculation to the unique characteristics of session-based recommendation tasks. Our experiments incorporate neural models and KNN-based models, and cover both the music and the e-commerce domain. We study the distributions of propensity and different stratification techniques on different datasets and find that propensity-related traits are actually dataset-specific. We then leverage the effect of stratification and achieve promising results compared to the original models.

{{</citation>}}


## cs.CR (8)



### (97/118) Prompt Engineering-assisted Malware Dynamic Analysis Using GPT-4 (Pei Yan et al., 2023)

{{<citation>}}

Pei Yan, Shunquan Tan, Miaohui Wang, Jiwu Huang. (2023)  
**Prompt Engineering-assisted Malware Dynamic Analysis Using GPT-4**  

---
Primary Category: cs.CR  
Categories: cs-AI, cs-CR, cs.CR  
Keywords: BERT, GPT, GPT-4  
[Paper Link](http://arxiv.org/abs/2312.08317v1)  

---


**ABSTRACT**  
Dynamic analysis methods effectively identify shelled, wrapped, or obfuscated malware, thereby preventing them from invading computers. As a significant representation of dynamic malware behavior, the API (Application Programming Interface) sequence, comprised of consecutive API calls, has progressively become the dominant feature of dynamic analysis methods. Though there have been numerous deep learning models for malware detection based on API sequences, the quality of API call representations produced by those models is limited. These models cannot generate representations for unknown API calls, which weakens both the detection performance and the generalization. Further, the concept drift phenomenon of API calls is prominent. To tackle these issues, we introduce a prompt engineering-assisted malware dynamic analysis using GPT-4. In this method, GPT-4 is employed to create explanatory text for each API call within the API sequence. Afterward, the pre-trained language model BERT is used to obtain the representation of the text, from which we derive the representation of the API sequence. Theoretically, this proposed method is capable of generating representations for all API calls, excluding the necessity for dataset training during the generation process. Utilizing the representation, a CNN-based detection model is designed to extract the feature. We adopt five benchmark datasets to validate the performance of the proposed model. The experimental results reveal that the proposed detection algorithm performs better than the state-of-the-art method (TextCNN). Specifically, in cross-database experiments and few-shot learning experiments, the proposed model achieves excellent detection performance and almost a 100% recall rate for malware, verifying its superior generalization performance. The code is available at: github.com/yan-scnu/Prompted_Dynamic_Detection.

{{</citation>}}


### (98/118) Towards Evaluating the Security of Wearable Devices in the Internet of Medical Things (Yas Vaseghi et al., 2023)

{{<citation>}}

Yas Vaseghi, Behnaz Behara, Mehdi Delrobaei. (2023)  
**Towards Evaluating the Security of Wearable Devices in the Internet of Medical Things**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SY, cs.CR, eess-SY  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.08160v1)  

---


**ABSTRACT**  
The Internet of Medical Things (IoMT) offers a promising solution to improve patient health and reduce human error. Wearable smart infusion pumps that accurately administer medication and integrate with electronic health records are an example of technology that can improve healthcare. They can even alert healthcare professionals or remote servers during operational failure, preventing distressing incidents. However, as the number of connected medical devices increases, the risk of cyber threats also increases. Wearable medication devices based on IoT attached to patients' bodies are prone to significant cyber threats. Being connected to the Internet exposes these devices to potential harm, which could disrupt or degrade device performance and harm patients. To ensure patient safety and well-being, it is crucial to establish secure data authentication for internet-connected medical devices. It is also important to note that the wearability option of such devices might downgrade the computational resources, making them more susceptible to security risks. This paper implements a security approach to a wearable infusion pump. We discuss practical challenges in implementing security-enabled devices and propose initial solutions to mitigate cyber threats.

{{</citation>}}


### (99/118) Security aspects in Smart Meters: Analysis and Prevention (Rebeca P. Díaz Redondo et al., 2023)

{{<citation>}}

Rebeca P. Díaz Redondo, Ana Fernández Vilas, Gabriel Fernández dos Reis. (2023)  
**Security aspects in Smart Meters: Analysis and Prevention**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-NI, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.08101v1)  

---


**ABSTRACT**  
Smart meters are of the basic elements in the so-called Smart Grid. These devices, connected to the Internet, keep bidirectional communication with other devices in the Smart Grid structure to allow remote readings and maintenance. As any other device connected to a network, smart meters become vulnerable to attacks with different purposes, like stealing data or altering readings. Nowadays, it is becoming more and more popular to buy and plug-and-play smart meters, additionally to those installed by the energy providers, to directly monitor the energy consumption at home. This option inherently entails security risks that are under the responsibility of householders. In this paper, we focus on an open solution based on Smartpi 2.0 devices with two purposes. On the one hand, we propose a network configuration and different data flows to exchange data (energy readings) in the home. These flows are designed to support collaborative among the devices in order to prevent external attacks and attempts of corrupting the data. On the other hand, we check the vulnerability by performing two kind of attacks (denial of service and stealing and changing data by using a malware). We conclude that, as expected, these devices are vulnerable to these attacks, but we provide mechanisms to detect both of them and to solve, by applying cooperation techniques

{{</citation>}}


### (100/118) Provable Security for the Onion Routing and Mix Network Packet Format Sphinx (Philip Scherer et al., 2023)

{{<citation>}}

Philip Scherer, Christiane Weis, Thorsten Strufe. (2023)  
**Provable Security for the Onion Routing and Mix Network Packet Format Sphinx**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.08028v1)  

---


**ABSTRACT**  
Onion routing and mix networks are fundamental concepts to provide users with anonymous access to the Internet. Various corresponding solutions rely on the efficient Sphinx packet format. However, flaws in Sphinx's underlying proof strategy were found recently. It is thus currently unclear which guarantees Sphinx actually provides, and, even worse, there is no suitable proof strategy available. In this paper, we restore the security foundation for all these works by building a theoretical framework for Sphinx. We discover that the previously-used DDH assumption is insufficient for a security proof and show that the Gap Diffie-Hellman (GDH) assumption is required instead. We apply it to prove that a slightly adapted version of the Sphinx packet format is secure under the GDH assumption. Ours is the first work to provide a detailed, in-depth security proof for Sphinx in this manner. Our adaptations to Sphinx are necessary, as we demonstrate with an attack on sender privacy that would be possible otherwise.

{{</citation>}}


### (101/118) SoK: On the Security of Non-Fungible Tokens (Kai Ma et al., 2023)

{{<citation>}}

Kai Ma, Jintao Huang, Ningyu He, Zhuo Wang, Haoyu Wang. (2023)  
**SoK: On the Security of Non-Fungible Tokens**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.08000v1)  

---


**ABSTRACT**  
Non-fungible tokens (NFTs) drive the prosperity of the Web3 ecosystem. By November 2023, the total market value of NFT projects reached approximately 16 billion USD. Accompanying the success of NFTs are various security issues, i.e., attacks and scams are prevalent in the ecosystem. While NFTs have attracted significant attentions from both industry and academia, there is a lack of understanding of kinds of NFT security issues. The discovery, in-depth analysis, and systematic categorization of these security issues are of significant importance for the prosperous development of the NFT ecosystem. To fill the gap, we performed a systematic literature review related to NFT security, and we have identified 142 incidents from 213 security reports and 18 academic papers until October 1st, 2023. Through manual analysis of the compiled security incidents, we have classified them into 12 major categories. Then we explored potential solutions and mitigation strategies. Drawing from these analyses, we established the first NFT security reference frame. Except, we extracted the characteristics of NFT security issues, i.e., the prevalence, severity, and intractability. We have indicated the gap between industry and academy for NFT security, and provide further research directions for the community. This paper, as the first SoK of NFT security, has systematically explored the security issues within the NFT ecosystem, shedding light on their root causes, real-world attacks, and potential ways to address them. Our findings will contribute to the future research of NFT security.

{{</citation>}}


### (102/118) BinGo: Identifying Security Patches in Binary Code with Graph Representation Learning (Xu He et al., 2023)

{{<citation>}}

Xu He, Shu Wang, Pengbin Feng, Xinda Wang, Shiyu Sun, Qi Li, Kun Sun. (2023)  
**BinGo: Identifying Security Patches in Binary Code with Graph Representation Learning**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs-SE, cs.CR  
Keywords: Representation Learning, Security  
[Paper Link](http://arxiv.org/abs/2312.07921v1)  

---


**ABSTRACT**  
A timely software update is vital to combat the increasing security vulnerabilities. However, some software vendors may secretly patch their vulnerabilities without creating CVE entries or even describing the security issue in their change log. Thus, it is critical to identify these hidden security patches and defeat potential N-day attacks. Researchers have employed various machine learning techniques to identify security patches in open-source software, leveraging the syntax and semantic features of the software changes and commit messages. However, all these solutions cannot be directly applied to the binary code, whose instructions and program flow may dramatically vary due to different compilation configurations. In this paper, we propose BinGo, a new security patch detection system for binary code. The main idea is to present the binary code as code property graphs to enable a comprehensive understanding of program flow and perform a language model over each basic block of binary code to catch the instruction semantics. BinGo consists of four phases, namely, patch data pre-processing, graph extraction, embedding generation, and graph representation learning. Due to the lack of an existing binary security patch dataset, we construct such a dataset by compiling the pre-patch and post-patch source code of the Linux kernel. Our experimental results show BinGo can achieve up to 80.77% accuracy in identifying security patches between two neighboring versions of binary code. Moreover, BinGo can effectively reduce the false positives and false negatives caused by the different compilers and optimization levels.

{{</citation>}}


### (103/118) Ensuring End-to-End Security with Fine-grained Access Control for Connected and Autonomous Vehicles (Donghyun Yu et al., 2023)

{{<citation>}}

Donghyun Yu, Sungho Lee, Ruei-Hau Hsu, Jemin Lee. (2023)  
**Ensuring End-to-End Security with Fine-grained Access Control for Connected and Autonomous Vehicles**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.07898v2)  

---


**ABSTRACT**  
As advanced V2X applications emerge in the connected and autonomous vehicle (CAV), the data communications between in-vehicle end-devices and outside nodes increase, which make the end-to-end (E2E) security to in-vehicle end-devices as the urgent issue to be handled. However, the E2E security with fine-grained access control still remains as a challenging issue for resource-constrained end-devices since the existing security solutions require complicated key management and high resource consumption. Therefore, we propose a practical and secure vehicular communication protocol for the E2E security based on a new attribute-based encryption (ABE) scheme. In our scheme, the outsourced computation is provided for encryption, and the computation cost for decryption constantly remains small, regardless of the number of attributes. The policy privacy can be ensured by the proposed ABE to support privacy-sensitive V2X applications, and the existing identity-based signature for outsourced signing is newly reconstructed. Our scheme achieves the confidentiality, message authentication, identity anonymity, unlinkability, traceability, and reconfigurable outsourced computation, and we also show the practical feasibility of our protocol via the performance evaluation.

{{</citation>}}


### (104/118) Securing Graph Neural Networks in MLaaS: A Comprehensive Realization of Query-based Integrity Verification (Bang Wu et al., 2023)

{{<citation>}}

Bang Wu, Xingliang Yuan, Shuo Wang, Qi Li, Minhui Xue, Shirui Pan. (2023)  
**Securing Graph Neural Networks in MLaaS: A Comprehensive Realization of Query-based Integrity Verification**  

---
Primary Category: cs.CR  
Categories: cs-CR, cs.CR  
Keywords: GNN, Graph Neural Network, Graph Neural Networks  
[Paper Link](http://arxiv.org/abs/2312.07870v1)  

---


**ABSTRACT**  
The deployment of Graph Neural Networks (GNNs) within Machine Learning as a Service (MLaaS) has opened up new attack surfaces and an escalation in security concerns regarding model-centric attacks. These attacks can directly manipulate the GNN model parameters during serving, causing incorrect predictions and posing substantial threats to essential GNN applications. Traditional integrity verification methods falter in this context due to the limitations imposed by MLaaS and the distinct characteristics of GNN models.   In this research, we introduce a groundbreaking approach to protect GNN models in MLaaS from model-centric attacks. Our approach includes a comprehensive verification schema for GNN's integrity, taking into account both transductive and inductive GNNs, and accommodating varying pre-deployment knowledge of the models. We propose a query-based verification technique, fortified with innovative node fingerprint generation algorithms. To deal with advanced attackers who know our mechanisms in advance, we introduce randomized fingerprint nodes within our design. The experimental evaluation demonstrates that our method can detect five representative adversarial model-centric attacks, displaying 2 to 4 times greater efficiency compared to baselines.

{{</citation>}}


## cs.RO (3)



### (105/118) CenterGrasp: Object-Aware Implicit Representation Learning for Simultaneous Shape Reconstruction and 6-DoF Grasp Estimation (Eugenio Chisari et al., 2023)

{{<citation>}}

Eugenio Chisari, Nick Heppert, Tim Welschehold, Wolfram Burgard, Abhinav Valada. (2023)  
**CenterGrasp: Object-Aware Implicit Representation Learning for Simultaneous Shape Reconstruction and 6-DoF Grasp Estimation**  

---
Primary Category: cs.RO  
Categories: cs-CV, cs-RO, cs.RO  
Keywords: Representation Learning  
[Paper Link](http://arxiv.org/abs/2312.08240v1)  

---


**ABSTRACT**  
Reliable object grasping is a crucial capability for autonomous robots. However, many existing grasping approaches focus on general clutter removal without explicitly modeling objects and thus only relying on the visible local geometry. We introduce CenterGrasp, a novel framework that combines object awareness and holistic grasping. CenterGrasp learns a general object prior by encoding shapes and valid grasps in a continuous latent space. It consists of an RGB-D image encoder that leverages recent advances to detect objects and infer their pose and latent code, and a decoder to predict shape and grasps for each object in the scene. We perform extensive experiments on simulated as well as real-world cluttered scenes and demonstrate strong scene reconstruction and 6-DoF grasp-pose estimation performance. Compared to the state of the art, CenterGrasp achieves an improvement of 38.5 mm in shape reconstruction and 33 percentage points on average in grasp success. We make the code and trained models publicly available at http://centergrasp.cs.uni-freiburg.de.

{{</citation>}}


### (106/118) Enhancing Robotic Navigation: An Evaluation of Single and Multi-Objective Reinforcement Learning Strategies (Vicki Young et al., 2023)

{{<citation>}}

Vicki Young, Jumman Hossain, Nirmalya Roy. (2023)  
**Enhancing Robotic Navigation: An Evaluation of Single and Multi-Objective Reinforcement Learning Strategies**  

---
Primary Category: cs.RO  
Categories: cs-LG, cs-RO, cs.RO  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.07953v2)  

---


**ABSTRACT**  
This study presents a comparative analysis between single-objective and multi-objective reinforcement learning methods for training a robot to navigate effectively to an end goal while efficiently avoiding obstacles. Traditional reinforcement learning techniques, namely Deep Q-Network (DQN), Deep Deterministic Policy Gradient (DDPG), and Twin Delayed DDPG (TD3), have been evaluated using the Gazebo simulation framework in a variety of environments with parameters such as random goal and robot starting locations. These methods provide a numerical reward to the robot, offering an indication of action quality in relation to the goal. However, their limitations become apparent in complex settings where multiple, potentially conflicting, objectives are present. To address these limitations, we propose an approach employing Multi-Objective Reinforcement Learning (MORL). By modifying the reward function to return a vector of rewards, each pertaining to a distinct objective, the robot learns a policy that effectively balances the different goals, aiming to achieve a Pareto optimal solution. This comparative study highlights the potential for MORL in complex, dynamic robotic navigation tasks, setting the stage for future investigations into more adaptable and robust robotic behaviors.

{{</citation>}}


### (107/118) Integrated Path Tracking with DYC and MPC using LSTM Based Tire Force Estimator for Four-wheel Independent Steering and Driving Vehicle (Sungjin Lim et al., 2023)

{{<citation>}}

Sungjin Lim, Bilal Sadiq, Yongsik Jin, Sangho Lee, Gyeungho Choi, Kanghyun Nam, Yongseob Lim. (2023)  
**Integrated Path Tracking with DYC and MPC using LSTM Based Tire Force Estimator for Four-wheel Independent Steering and Driving Vehicle**  

---
Primary Category: cs.RO  
Categories: cs-RO, cs-SY, cs.RO, eess-SY  
Keywords: LSTM  
[Paper Link](http://arxiv.org/abs/2312.07826v1)  

---


**ABSTRACT**  
Active collision avoidance system plays a crucial role in ensuring the lateral safety of autonomous vehicles, and it is primarily related to path planning and tracking control algorithms. In particular, the direct yaw-moment control (DYC) system can significantly improve the lateral stability of a vehicle in environments with sudden changes in road conditions. In order to apply the DYC algorithm, it is very important to accurately consider the properties of tire forces with complex nonlinearity for control to ensure the lateral stability of the vehicle. In this study, longitudinal and lateral tire forces for safety path tracking were simultaneously estimated using a long short-term memory (LSTM) neural network based estimator. Furthermore, to improve path tracking performance in case of sudden changes in road conditions, a system has been developed by combining 4-wheel independent steering (4WIS) model predictive control (MPC) and 4-wheel independent drive (4WID) direct yaw-moment control (DYC). The estimation performance of the extended Kalman filter (EKF), which are commonly used for tire force estimation, was compared. In addition, the estimated longitudinal and lateral tire forces of each wheel were applied to the proposed system, and system verification was performed through simulation using a vehicle dynamics simulator. Consequently, the proposed method, the integrated path tracking algorithm with DYC and MPC using the LSTM based estimator, was validated to significantly improve the vehicle stability in suddenly changing road conditions.

{{</citation>}}


## cs.LO (1)



### (108/118) Memory Simulations, Security and Optimization in a Verified Compiler (David Monniaux, 2023)

{{<citation>}}

David Monniaux. (2023)  
**Memory Simulations, Security and Optimization in a Verified Compiler**  

---
Primary Category: cs.LO  
Categories: cs-LO, cs-PL, cs.LO  
Keywords: Security  
[Paper Link](http://arxiv.org/abs/2312.08117v1)  

---


**ABSTRACT**  
Current compilers implement security features and optimizations that require nontrivial semantic reasoning about pointers and memory allocation: the program after the insertion of the security feature, or after applying the optimization, must simulate the original program despite a different memory layout. In this article, we illustrate such reasoning on pointer allocations through memory extensions and injections, as well as fine points on undefined values, by explaining how we implemented and proved correct two security features (stack canaries and pointer authentication) and one optimization (tail recursion elimination) in the CompCert formally verified compiler.

{{</citation>}}


## cs.SI (1)



### (109/118) A hybrid analysis of LBSN data to early detect anomalies in crowd dynamics (Rebeca P. Díaz-Redondo et al., 2023)

{{<citation>}}

Rebeca P. Díaz-Redondo, Carlos Garcia-Rubio, Ana Fernández Vilas, Celeste Campo, Alicia Rodriguez-Carrion. (2023)  
**A hybrid analysis of LBSN data to early detect anomalies in crowd dynamics**  

---
Primary Category: cs.SI  
Categories: cs-AI, cs-SI, cs.SI  
Keywords: Social Network  
[Paper Link](http://arxiv.org/abs/2312.08092v1)  

---


**ABSTRACT**  
Undoubtedly, Location-based Social Networks (LBSNs) provide an interesting source of geo-located data that we have previously used to obtain patterns of the dynamics of crowds throughout urban areas. According to our previous results, activity in LBSNs reflects the real activity in the city. Therefore, unexpected behaviors in the social media activity are a trustful evidence of unexpected changes of the activity in the city. In this paper we introduce a hybrid solution to early detect these changes based on applying a combination of two approaches, the use of entropy analysis and clustering techniques, on the data gathered from LBSNs. In particular, we have performed our experiments over a data set collected from Instagram for seven months in New York City, obtaining promising results.

{{</citation>}}


## cs.HC (2)



### (110/118) The State of Pilot Study Reporting in Crowdsourcing: A Reflection on Best Practices and Guidelines (Jonas Oppenlaender et al., 2023)

{{<citation>}}

Jonas Oppenlaender, Tahir Abbas, Ujwal Gadiraju. (2023)  
**The State of Pilot Study Reporting in Crowdsourcing: A Reflection on Best Practices and Guidelines**  

---
Primary Category: cs.HC  
Categories: cs-CY, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.08090v1)  

---


**ABSTRACT**  
Pilot studies are an essential cornerstone of the design of crowdsourcing campaigns, yet they are often only mentioned in passing in the scholarly literature. A lack of details surrounding pilot studies in crowdsourcing research hinders the replication of studies and the reproduction of findings, stalling potential scientific advances. We conducted a systematic literature review on the current state of pilot study reporting at the intersection of crowdsourcing and HCI research. Our review of ten years of literature included 171 articles published in the proceedings of the Conference on Human Computation and Crowdsourcing (AAAI HCOMP) and the ACM Digital Library. We found that pilot studies in crowdsourcing research (i.e., crowd pilot studies) are often under-reported in the literature. Important details, such as the number of workers and rewards to workers, are often not reported. On the basis of our findings, we reflect on the current state of practice and formulate a set of best practice guidelines for reporting crowd pilot studies in crowdsourcing research. We also provide implications for the design of crowdsourcing platforms and make practical suggestions for supporting crowd pilot study reporting.

{{</citation>}}


### (111/118) Artificial Intelligence Studies in Cartography: A Review and Synthesis of Methods, Applications, and Ethics (Yuhao Kang et al., 2023)

{{<citation>}}

Yuhao Kang, Song Gao, Robert E. Roth. (2023)  
**Artificial Intelligence Studies in Cartography: A Review and Synthesis of Methods, Applications, and Ethics**  

---
Primary Category: cs.HC  
Categories: cs-AI, cs-GR, cs-HC, cs.HC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.07901v1)  

---


**ABSTRACT**  
The past decade has witnessed the rapid development of geospatial artificial intelligence (GeoAI) primarily due to the ground-breaking achievements in deep learning and machine learning. A growing number of scholars from cartography have demonstrated successfully that GeoAI can accelerate previously complex cartographic design tasks and even enable cartographic creativity in new ways. Despite the promise of GeoAI, researchers and practitioners have growing concerns about the ethical issues of GeoAI for cartography. In this paper, we conducted a systematic content analysis and narrative synthesis of research studies integrating GeoAI and cartography to summarize current research and development trends regarding the usage of GeoAI for cartographic design. Based on this review and synthesis, we first identify dimensions of GeoAI methods for cartography such as data sources, data formats, map evaluations, and six contemporary GeoAI models, each of which serves a variety of cartographic tasks. These models include decision trees, knowledge graph and semantic web technologies, deep convolutional neural networks, generative adversarial networks, graph neural networks, and reinforcement learning. Further, we summarize seven cartographic design applications where GeoAI have been effectively employed: generalization, symbolization, typography, map reading, map interpretation, map analysis, and map production. We also raise five potential ethical challenges that need to be addressed in the integration of GeoAI for cartography: commodification, responsibility, privacy, bias, and (together) transparency, explainability, and provenance. We conclude by identifying four potential research directions for future cartographic research with GeoAI: GeoAI-enabled active cartographic symbolism, human-in-the-loop GeoAI for cartography, GeoAI-based mapping-as-a-service, and generative GeoAI for cartography.

{{</citation>}}


## cs.CE (1)



### (112/118) Solving Bayesian Inverse Problems With Expensive Likelihoods Using Constrained Gaussian Processes and Active Learning (Maximilian Dinkel et al., 2023)

{{<citation>}}

Maximilian Dinkel, Carolin M. Geitner, Gil Robalo Rei, Jonas Nitzler, Wolfgang A. Wall. (2023)  
**Solving Bayesian Inverse Problems With Expensive Likelihoods Using Constrained Gaussian Processes and Active Learning**  

---
Primary Category: cs.CE  
Categories: cs-CE, cs.CE  
Keywords: Active Learning  
[Paper Link](http://arxiv.org/abs/2312.08085v1)  

---


**ABSTRACT**  
Solving inverse problems using Bayesian methods can become prohibitively expensive when likelihood evaluations involve complex and large scale numerical models. A common approach to circumvent this issue is to approximate the forward model or the likelihood function with a surrogate model. But also there, due to limited computational resources, only a few training points are available in many practically relevant cases. Thus, it can be advantageous to model the additional uncertainties of the surrogate in order to incorporate the epistemic uncertainty due to limited data. In this paper, we develop a novel approach to approximate the log likelihood by a constrained Gaussian process based on prior knowledge about its boundedness. This improves the accuracy of the surrogate approximation without increasing the number of training samples. Additionally, we introduce a formulation to integrate the epistemic uncertainty due to limited training points into the posterior density approximation. This is combined with a state of the art active learning strategy for selecting training points, which allows to approximate posterior densities in higher dimensions very efficiently. We demonstrate the fast convergence of our approach for a benchmark problem and infer a random field that is discretized by 30 parameters using only about 1000 model evaluations. In a practically relevant example, the parameters of a reduced lung model are calibrated based on flow observations over time and voltage measurements from a coupled electrical impedance tomography simulation.

{{</citation>}}


## math.OC (2)



### (113/118) PySCIPOpt-ML: Embedding Trained Machine Learning Models into Mixed-Integer Programs (Mark Turner et al., 2023)

{{<citation>}}

Mark Turner, Antonia Chmiela, Thorsten Koch, Michael Winkler. (2023)  
**PySCIPOpt-ML: Embedding Trained Machine Learning Models into Mixed-Integer Programs**  

---
Primary Category: math.OC  
Categories: cs-AI, math-OC, math.OC  
Keywords: Embedding  
[Paper Link](http://arxiv.org/abs/2312.08074v1)  

---


**ABSTRACT**  
A standard tool for modelling real-world optimisation problems is mixed-integer programming (MIP). However, for many of these problems there is either incomplete information describing variable relations, or the relations between variables are highly complex. To overcome both these hurdles, machine learning (ML) models are often used and embedded in the MIP as surrogate models to represent these relations. Due to the large amount of available ML frameworks, formulating ML models into MIPs is highly non-trivial. In this paper we propose a tool for the automatic MIP formulation of trained ML models, allowing easy integration of ML constraints into MIPs. In addition, we introduce a library of MIP instances with embedded ML constraints. The project is available at https://github.com/Opt-Mucca/PySCIPOpt-ML.

{{</citation>}}


### (114/118) Adaptive Isogeometric Topology Optimization of Shell Structures based on PHT-splines (Zepeng Wen et al., 2023)

{{<citation>}}

Zepeng Wen, Qiong Pan, Xiaoya Zhai, Hongmei Kang, Falai Chen. (2023)  
**Adaptive Isogeometric Topology Optimization of Shell Structures based on PHT-splines**  

---
Primary Category: math.OC  
Categories: cs-CE, cs-CG, cs-GR, math-OC, math.OC  
Keywords: AI  
[Paper Link](http://arxiv.org/abs/2312.07889v1)  

---


**ABSTRACT**  
This paper proposes an Adaptive Isogeometric Topology Optimization framework for shell structures based on PHT-splines (PHT-AITO). In this framework, the design domain, displacement, and density are represented by PHT-splines. Leveraging the local refinement capability of PHT-splines, mesh elements defining the density function are adaptively refined to achieve a suitable resolution at the interface between solid and void regions. This addresses the issue of excessive degrees of freedom resulting from global refinement. The refinement of the mesh elements is driven by their density. During the optimization of the density on a refined mesh, the initial value of the density is inherited from the optimization results on the previous mesh to accelerate the iteration process and maintain the stability of the optimized structure. Numerical experiments on various shell structures have verified the effectiveness of PHT-AITO. Compared with isogeometric topology optimization based on tensor-product splines, PHT-AITO can significantly reduce the degrees of freedom in the optimization problem, thereby improving computational efficiency.

{{</citation>}}


## quant-ph (2)



### (115/118) A Novel Framework Based on Variational Quantum Algorithms: Revolutionizing Image Classification (Yixiong Chen, 2023)

{{<citation>}}

Yixiong Chen. (2023)  
**A Novel Framework Based on Variational Quantum Algorithms: Revolutionizing Image Classification**  

---
Primary Category: quant-ph  
Categories: cs-AI, cs-CV, quant-ph, quant-ph  
Keywords: Image Classification, QA  
[Paper Link](http://arxiv.org/abs/2312.07932v1)  

---


**ABSTRACT**  
Image classification is a crucial task in machine learning. In recent years, this field has witnessed rapid development, with a series of image classification models being proposed and achieving state-of-the-art (SOTA) results. Parallelly, with the advancement of quantum technologies, quantum machine learning has attracted a lot of interest. In particular, a class of algorithms known as variational quantum algorithms (VQAs) has been extensively studied to improve the performance of classical machine learning. In this paper, we propose a novel image classification framework using VQAs. The major advantage of our framework is the elimination of the need for the global pooling operation typically performed at the end of classical image classification models. While global pooling can help to reduce computational complexity, it often results in a significant loss of information. By removing the global pooling module before the output layer, our approach allows for effectively capturing more discriminative features and fine-grained details in images, leading to improved classification performance. Moreover, employing VQAs enables our framework to have fewer parameters compared to the classical framework, even in the absence of global pooling, which makes it more advantageous in preventing overfitting. We apply our method to different SOTA image classification models and demonstrate the superiority of the proposed quantum architecture over its classical counterpart through a series of experiments on public datasets.

{{</citation>}}


### (116/118) Radio Signal Classification by Adversarially Robust Quantum Machine Learning (Yanqiu Wu et al., 2023)

{{<citation>}}

Yanqiu Wu, Eromanga Adermann, Chandra Thapa, Seyit Camtepe, Hajime Suzuki, Muhammad Usman. (2023)  
**Radio Signal Classification by Adversarially Robust Quantum Machine Learning**  

---
Primary Category: quant-ph  
Categories: cs-LG, quant-ph, quant-ph  
Keywords: QA  
[Paper Link](http://arxiv.org/abs/2312.07821v1)  

---


**ABSTRACT**  
Radio signal classification plays a pivotal role in identifying the modulation scheme used in received radio signals, which is essential for demodulation and proper interpretation of the transmitted information. Researchers have underscored the high susceptibility of ML algorithms for radio signal classification to adversarial attacks. Such vulnerability could result in severe consequences, including misinterpretation of critical messages, interception of classified information, or disruption of communication channels. Recent advancements in quantum computing have revolutionized theories and implementations of computation, bringing the unprecedented development of Quantum Machine Learning (QML). It is shown that quantum variational classifiers (QVCs) provide notably enhanced robustness against classical adversarial attacks in image classification. However, no research has yet explored whether QML can similarly mitigate adversarial threats in the context of radio signal classification. This work applies QVCs to radio signal classification and studies their robustness to various adversarial attacks. We also propose the novel application of the approximate amplitude encoding (AAE) technique to encode radio signal data efficiently. Our extensive simulation results present that attacks generated on QVCs transfer well to CNN models, indicating that these adversarial examples can fool neural networks that they are not explicitly designed to attack. However, the converse is not true. QVCs primarily resist the attacks generated on CNNs. Overall, with comprehensive simulations, our results shed new light on the growing field of QML by bridging knowledge gaps in QAML in radio signal classification and uncovering the advantages of applying QML methods in practical applications.

{{</citation>}}


## cs.NI (1)



### (117/118) On Designing Multi-UAV aided Wireless Powered Dynamic Communication via Hierarchical Deep Reinforcement Learning (Ze Yu Zhao et al., 2023)

{{<citation>}}

Ze Yu Zhao, Yue Ling Che, Sheng Luo, Gege Luo, Kaishun Wu, Victor C. M. Leung. (2023)  
**On Designing Multi-UAV aided Wireless Powered Dynamic Communication via Hierarchical Deep Reinforcement Learning**  

---
Primary Category: cs.NI  
Categories: cs-AI, cs-NI, cs.NI  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.07917v1)  

---


**ABSTRACT**  
This paper proposes a novel design on the wireless powered communication network (WPCN) in dynamic environments under the assistance of multiple unmanned aerial vehicles (UAVs). Unlike the existing studies, where the low-power wireless nodes (WNs) often conform to the coherent harvest-then-transmit protocol, under our newly proposed double-threshold based WN type updating rule, each WN can dynamically and repeatedly update its WN type as an E-node for non-linear energy harvesting over time slots or an I-node for transmitting data over sub-slots. To maximize the total transmission data size of all the WNs over T slots, each of the UAVs individually determines its trajectory and binary wireless energy transmission (WET) decisions over times slots and its binary wireless data collection (WDC) decisions over sub-slots, under the constraints of each UAV's limited on-board energy and each WN's node type updating rule. However, due to the UAVs' tightly-coupled trajectories with their WET and WDC decisions, as well as each WN's time-varying battery energy, this problem is difficult to solve optimally. We then propose a new multi-agent based hierarchical deep reinforcement learning (MAHDRL) framework with two tiers to solve the problem efficiently, where the soft actor critic (SAC) policy is designed in tier-1 to determine each UAV's continuous trajectory and binary WET decision over time slots, and the deep-Q learning (DQN) policy is designed in tier-2 to determine each UAV's binary WDC decisions over sub-slots under the given UAV trajectory from tier-1. Both of the SAC policy and the DQN policy are executed distributively at each UAV. Finally, extensive simulation results are provided to validate the outweighed performance of the proposed MAHDRL approach over various state-of-the-art benchmarks.

{{</citation>}}


## eess.SY (1)



### (118/118) Safe Exploration in Reinforcement Learning: Training Backup Control Barrier Functions with Zero Training Time Safety Violations (Pedram Rabiee et al., 2023)

{{<citation>}}

Pedram Rabiee, Amirsaeid Safari. (2023)  
**Safe Exploration in Reinforcement Learning: Training Backup Control Barrier Functions with Zero Training Time Safety Violations**  

---
Primary Category: eess.SY  
Categories: cs-SY, eess-SY, eess.SY  
Keywords: Reinforcement Learning  
[Paper Link](http://arxiv.org/abs/2312.07828v1)  

---


**ABSTRACT**  
Safe reinforcement learning (RL) aims to satisfy safety constraints during training. However, guaranteeing safety during training remained a challenging problem. This paper presents a novel framework that integrates Backup Control Barrier Functions (BCBFs) with reinforcement learning (RL) to enable safe exploration called RLBUS: Reinforcement Learning Backup Shield. BCBFs incorporate backup controllers that predict a system's finite-time response, facilitating online optimization of a control policy that maintains the forward invariance of a safe subset, while satisfying actuator constraints. Building on the soft-minimum/soft-maximum CBF method from prior work, which ensures feasibility and continuity of the BCBF with multiple backup controllers, this paper proposes integrating these BCBFs with RL. This framework leverages RL to learn a better backup policy to enlarge the forward invariant set, while guaranteeing safety during training. By combining backup controllers and RL, the approach provides safety and feasibility guarantees during training and enables safe online exploration with zero training-time safety violations. The method is demonstrated on an inverted pendulum example, where expanding the forward invariant set through RL allows the pendulum to safely explore larger regions of state space.

{{</citation>}}
