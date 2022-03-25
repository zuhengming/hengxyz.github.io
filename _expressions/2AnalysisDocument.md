---
title: "<font color=blue><u>Analysis of document images </u></font>"
collection: expressions
excerpt: "Analysis of document images based on superivsed/self-supervised, multimodal learning and multitask learning for document images classification and document attributes classification."
redirect_to: 
---

2020-2022 : This research project aims to explore the multimodal text-visual feature representations to detect the types of documents by classifying the input document images. The chanllenge for text-visual multimodal learning is to learn a common representation space from the heterogeneous features extracted from the language and visual model respectively. Different multimodal methods such as **Vanille Multimodal feature fusion, Mutual learning based on Knowledge Distillation, Cross self-attention between text and visual modality** are applied in this research. 

- Collabration labotories: [L3i](https://l3i.univ-larochelle.fr/), [CVC](http://www.cvc.uab.es/)
- with [Souhail Bakkali](https://scholar.google.fr/citations?user=gO_Q48IAAAAJ&hl=en&oi=sra), [Mickaël Coustaty](https://scholar.google.com/citations?user=Tc8FrWwAAAAJ&hl=en), [Marçal Rusiñol](https://scholar.google.com/citations?user=Uvxu49IAAAAJ&hl=en), [Oriol Ramos Terrades](https://scholar.google.com/citations?user=4Dvggx4AAAAJ&hl=en)

**Reasearch methods**: 

- [Multimodal learning based on cross self-attention for document classification (IJCAI-ECAI2022_submission):]()

*Key words: cross-modal representation, text-visual cross self-attention, Self-supervised contrastive learning, BERT, CNNs, document image classification*

<font size=3>In this work we approach the document classification problem by learning cross-modal representations through language and vision cues, considering intra- and inter-modality relationships. Instead of merging features from different modalities into a common representations space, the proposed method exploits high-level interactions and learns semantic information from effective attention flows within and across modalities. The proposed learning objective enforces the compactness of intra-class representations while separating inter-class features by contrasting positive and negative sample pairs within and across each modality. Unlike the classic uni-modal contrastive learning, we propose cross-modal contrastive learning loss to further explore the relations between vision and text cues. Extensive experiments on public document classification datasets demonstrate the effectiveness and the generalization capacity of our method on low-scale and large-scale datasets, by including cross-modal pre-training in a unified network..</font>


![avatar](/images/Cross-modalIJCAI.jpg)

- [EAML: ensemble self-attention-based mutual learning network for document image classification (IJDAR):](https://link.springer.com/content/pdf/10.1007/s10032-021-00378-0.pdf)

*Key words: Text document image classification, Self-attention-based fusion, Mutual learning, Multi-modal fusion Ensemble learning*

<font size=3>The main challenge of document image classification is the low inter-class discrimination and high intra-class structural variations of document images. To mitigate this issue, we propose a mutual learning module that serves as a block in our ensemble trainable network which allows the network to simultaneously learn the discriminant features of image and text branches in a mutual learning manner. Specifically, we design a novel mutual learning model, namely positive mutual learning, which enables the current branch to learn the positive knowledge from the other branch instead of the negative knowledge that will weaken the learning capacity for the current branch. To the best of our knowledge, this is the first time to leverage (positive) mutual learning approach for document image classification. The experimental results show the effectiveness of our approach which improves the classification performance of document images for the independent branches.</font>


![avatar](/images/EMAIL.jpg)

- [Cross-Modal Deep Networks For Document Image Classification]() ([ICIP2020](https://ieeexplore.ieee.org/document/9191268), [CVPRW2020](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w34/Bakkali_Visual_and_Textual_Deep_Feature_Fusion_for_Document_Image_Classification_CVPRW_2020_paper.pdf)):

*Key words: Text document image classification, cross-modal feature learning, deep CNNs.*

<font size=3>Unlike the general image classification problem in the computer vision field, text document images contain both the visual cues and the corresponding text within the image. However, how to bridge these two different modalities and leverage textual and visual features to classify text document images remains challenging.
In this paper, we present a two-branches based cross-modal deep network that enables to capture both the textual content and the visual information. We conduct an exhaustive investigation of nowadays widely used neural networks such as ResNet, MobileNet, NASNet-Large, Bert and so on as backbone to extract image and text features respectively. Different joint feature learning approaches based on vanille concatenation, equal concatenation and superposition have been introduced to learn the common multimodal features from the language and visual cues.</font>
![avatar](/images/cross_modal_CVPRW2020.PNG)
![avatar](/images/icip2020_b_c_horizontal.jpg)

**<font size=5>Document attributes classification</font>**
- [Exploring Multi-Tasking Learning in Document Attribute Classification]()[[Pattern Recognition Letters]](https://pdf.sciencedirectassets.com/271524/AIP/1-s2.0-S0167865522000599/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIFFESz5JTlWpFA30RrbKKfl71GQmC8y6y1V54tBNnvv5AiEAiJ9HAG3bbwlpMv%2FYppHRD9eFBf%2Bovcv7DUw3mEIJbpgq%2BgMIfBAEGgwwNTkwMDM1NDY4NjUiDM%2F8yRYYDMvANJpJ7SrXA7DUGtFBNGkZMMpbsJVejkuRt9rdzA1Yuq3PFoACLKuEtxFQrCHhz9hoijHoN1h%2BMB3yZm%2FvNLNRFwoePBE138HIUrQDjKVjqV0B%2BE1AKSSsrdPGZTf2gy1BOba1QOFoTXZBmh8bWXX%2BFhZ%2BxnxoGsI9T06NbsmYjwAUuevZihIGRFU9t1MK4giW2qT6w45DFxDMoocQrimSs%2FL1U6TMaI5FUhgyXAgGNOLaDY29a6Hwl3qEKljx7ZZdkKn4Gezy2C6cLu2DMjohPfvoFC8xQJXulb%2FbBJ5rO9%2BTgfbkaJo5Cn6ml0oUXDCRYC5mcDKFWwy8RhLeKy%2BFvgw01BEQPHHJGfP71YdOUIQpNiVzLE6s7fnjP5crL2v8W9RoDraig5pAC6RZQrSWO0rhRhV7mvGwDXkuMGbuLRuLyQgmQYxkK%2BB3y3k54xmgX0t8zg1ZtO%2Fy64%2Bp7NfcPh1EFwD508cd0YeJm%2Fv2uWvoUKRWM48XWiiZCp935poR3iIbtgxAcV9cK6wrEVRT4%2BzmqbPFDIvMYWgWJmon%2F2MWPusCyqjMFfLUz2wLKZhoUlXi%2BYOeBzTox03Na1yU9FnvCcsxOjIgkiDNsuHHOUrSG7RRhfNceFR9g4grnzCxoviRBjqlAe4Mp7w8O6Zz7iufWSGYrxxIFI8oOpTbiA6kDX3IqjSiWlOtXJIu0LhmNyr0I963Cz%2BLzSOsSj5CvbwPHiFU7v3aLeEWF5%2FvNDXexLbbLKofyQNGG8aFsajzds01bMc1Zwtlz%2F%2FA4vdU0Tt3mmHphj8vJHBFXiNxON0cb7m%2FerYvmTWzSYFOfPMZMG4KU7avnlKg5ZKY%2BgSg5dFs68Ue0IDB%2F4u9wA%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220325T201310Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYYJ7CHFHU%2F20220325%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e44d97768b3a73a6d2cff6bd15ca554110422aa6f1b77515f55ea685c3d3e9a6&hash=241794e1aece027ab110e7cbde984c551fda47cea439a66fbe2050fd65cdadf0&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0167865522000599&tid=spdf-1626c408-8091-4b24-bded-d335721e04f4&sid=b33d6b2781bc204c1f3ae44252bd1472ceecgxrqb&type=client&ua=53015206510b565e5807&rr=6f1a4e387c7e91e9) [[code]](https://github.com/tanmayGIT/Document-Attribute-Classification):

    - Collabration labotories: [IMT](https://www.imt-atlantique.fr/fr), [Thapar University](https://www.thapar.edu/)
    - with [Tanmoy Mondal](https://dblp.org/pid/30/10490.html), Abhijit Das

*Key words: Document attributes classification, multi-task learning, hybrid CNNs.* 

<font size=3>In this work, we adhere to explore a Multi-Tasking learning (MTL) based network to perform document attribute classification such as the font type, font size, font emphasis  and  scanning  resolution classification of a document image. To accomplish these tasks, we operate on either segmented word level or on uniformed size patches randomly cropped out of the document. Furthermore, a hybrid convolution neural network (CNN) architecture  "MTL+MI", which is based on the combination of MTL and Multi-Instance (MI) of patch and word is used to accomplish joint learning for the classification of the same document attributes.</font>

![avatar](/images/DocAttributesMTL.png)



