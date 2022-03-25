---
title: "<font color=blue><u>Classification of document images </u></font>"
collection: expressions
excerpt: "Classification of document images based on superivsed/self-supervised text-visual multimodal learning."
redirect_to: 
---

2020-2022 : This research project aims to explore the multimodal text-visual feature representations to detect the types of documents by classifying the input document images. The chanllenge is to learn a common representation space from the heterogeneous features extracted from the language and visual model respectively. Different multimodal learning methods such as **Vanille Multimodal feature fusion, Mutual learning based on Knowledge Distillation, Cross self-attention between text and visual modality** are applied in this research. 

- Collabration labotories: [L3i](https://l3i.univ-larochelle.fr/), [CVC](http://www.cvc.uab.es/)
- with [Souhail Bakkali](https://scholar.google.fr/citations?user=gO_Q48IAAAAJ&hl=en&oi=sra), [Mickaël Coustaty](https://scholar.google.com/citations?user=Tc8FrWwAAAAJ&hl=en), [Marçal Rusiñol](https://scholar.google.com/citations?user=Uvxu49IAAAAJ&hl=en), [Oriol Ramos Terrades](https://scholar.google.com/citations?user=4Dvggx4AAAAJ&hl=en)

**Reasearch methods**: 

- [Multimodal learning based on cross self-attention for document classification (IJCAI-ECAI2022_submission):]()

*Key words: cross-modal representation, text-visual cross self-attention, Self-supervised contrastive learning, BERT, CNNs, document image classification*

<font size=3>In this work we approach the document classification problem by learning cross-modal representations through language and vision cues, considering intra- and inter-modality relationships. Instead of merging features from different modalities into a common representations space, the proposed method exploits high-level interactions and learns semantic information from effective attention flows within and across modalities. The proposed learning objective enforces the compactness of intra-class representations while separating inter-class features by contrasting positive and negative sample pairs within and across each modality. Extensive experiments on public document classification datasets demonstrate the effectiveness and the generalization capacity of our method on low-scale and large-scale datasets, by including cross-modal pre-training in a unified network..</font>


![avatar](/images/Cross-modalIJCAI.jpg)

- [EAML: ensemble self-attention-based mutual learning network for document image classification (IJDAR):](https://link.springer.com/content/pdf/10.1007/s10032-021-00378-0.pdf)

*Key words: Text document image classification, Self-attention-based fusion, Mutual learning, Multi-modal fusion Ensemble learning*

<font size=3>The main challenge of document image classification is the low inter-class discrimination and high intra-class structural variations of document images. To mitigate this issue, we propose a mutual learning module that serves as a block in our ensemble trainable network which allows the network to simultaneously learn the discriminant features of image and text branches in a mutual learning manner. Specifically, we design a novel mutual learning model, namely positive mutual learning, which enables the current branch to learn the positive knowledge from the other branch instead of the negative knowledge that will weaken the learning capacity for the current branch. To the best of our knowledge, this is the first time to leverage (positive) mutual learning approach for document image classification. The experimental results show the effectiveness of our approach which improves the classification performance of document images for the independent branches.</font>


![avatar](/images/EMAIL.jpg)

- [Cross-Modal Deep Networks For Document Image Classification]() ([ICIP2020](https://ieeexplore.ieee.org/document/9191268), [CVPRW2020](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w34/Bakkali_Visual_and_Textual_Deep_Feature_Fusion_for_Document_Image_Classification_CVPRW_2020_paper.pdf)):

*Key words: Multi-task learning, interactive face authentification, face recognition, facial expression recognition, CNNs*

<font size=3>Existing face verification architectures seldom integrate any liveness detection or keep such stage isolated from face verification as if it was irrelevant. This may potentially result in the system being exposed to spoof attacks between the two stages. This work introduces FaceLiveNet, a holistic endto-end deep networks which can perform face verification and liveness detection simultaneously. An interactive scheme for facial expression recognition is proposed to perform liveness detection, providing better generalization capacity and higher security level. The proposed framework is low-cost as it relies on commodity hardware instead of costly sensors, and lightweight with much fewer parameters comparing to the other popular deep networks such as VGG16 and FaceNet. Experimental results on the benchmarks LFW, YTF, CK+, OuluCASIA, SFEW, FER2013 demonstrate that the proposed FaceLiveNet can achieve state-of art performance or better for both face verification and facial expression recognition. We also introduce a new protocol to evaluate the global performance for face authentication with the fusion of face verification and interactive facial expression-based liveness detection.</font>


![avatar](/images/Fig1.jpg)
   




