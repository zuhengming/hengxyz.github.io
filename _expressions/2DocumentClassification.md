---
title: "<font color=blue><u>Classification of document images </u></font>"
collection: expressions
excerpt: "Classification of document images based on superivsed/self-supervised text-visual multimodal learning."
redirect_to: 
---

2020-2022 : This research project aims to explore the multimodal text-visual feature representations to detect the types of documents by classifying the input document images. The chanllenge is to learn a multimodal feature representations from the heterogeneous feature spaces of text and visual images. Different multimodal learning methods are applied in this project such as **Vanille Multimodal feature fusion, Mutual learning based on Knowledge Distillation, Cross self-attention between text and visual modality**

- Collabration labotories: [L3i](https://l3i.univ-larochelle.fr/), [CVC](http://www.cvc.uab.es/)
- with [Souhail Bakkali](https://scholar.google.fr/citations?user=gO_Q48IAAAAJ&hl=en&oi=sra), [Mickaël Coustaty](https://scholar.google.com/citations?user=Tc8FrWwAAAAJ&hl=en), [Marçal Rusiñol](https://scholar.google.com/citations?user=Uvxu49IAAAAJ&hl=en), [Oriol Ramos Terrades](https://scholar.google.com/citations?user=4Dvggx4AAAAJ&hl=en)

**Reasearch methods**: 

- [Multimodal learning based on cross self-attention for document classification (IJCAI-ECAI2022_submission):]()

*Key words: Multimodal learning, text-visual cross self-attention, Self-supervised contrastive learning, BERT, CNNs, document image classification*

<font size=3>Many works based on Convolution Neural Networks (CNNs) for face PAD formulate the problem as an image-level binary classification task without considering the context. Alternatively, Vision Transformers (ViT) using self-attention to attend the context of an image become the mainstreams in face PAD. Inspired by ViT, we design a Video-based Transformer for face PAD with short/long-range spatio-temporal attention which can not only focus on local details but also the context of a video. The proposed Multi-scale Multi-Head Self-Attention enables the model to learn a fine-grained representation to perform pixel level discrimination required by face PAD. We also introduce convolutions to our ViTransPAD to integrate desirable proprieties of CNNs which can gain a good computation-accuracy balance. To the best of our knowledge, this is the first approach using video-based transformer for face PAD which can serve as a new backbone for further study.</font>


![avatar](/images/vittranspad.png)

- [Multimodal Face anti-spoofing Based on the Generated Pseudo Face Images:]()

*Key words: Multimodal learning, 3D depth image generalization, CNNs, face presentation attack detection*

<font size=3>Since the real faces and the attacks presented in such as 3D depth images, infrared images or thermal images are very different as shown in <a href="https://www.idiap.ch/en/dataset/wmca" title="WMCA">WMCA</a>, using multimodal learning for face anti-spoofing is a effective way. However, acquiring the images of special modality needs special sensors which is not practical for the current consuming devices. Thus, we propose a method based on CNNs-based encoder-decoder architecture which allows to generate the pseudo multimodal images (e.g., 3D depth image) to detetect by multimodal learning  </font>


![avatar](/images/MultimodalFAS.png)

- [FaceLiveNet: End-to-End Networks Combining Face Verification With Interactive Facial Expression-based Liveness Detection (ICPR2018):](https://www.researchgate.net/profile/Zuheng-Ming/publication/325229686_FaceLiveNet_End-to-End_Face_Verification_Networks_Combining_With_Interactive_Facial_Expression-based_Liveness_Detection/links/5aff47b5aca2720ba095e75d/FaceLiveNet-End-to-End-Face-Verification-Networks-Combining-With-Interactive-Facial-Expression-based-Liveness-Detection.pdf)

*Key words: Multi-task learning, interactive face authentification, face recognition, facial expression recognition, CNNs*

<font size=3>Existing face verification architectures seldom integrate any liveness detection or keep such stage isolated from face verification as if it was irrelevant. This may potentially result in the system being exposed to spoof attacks between the two stages. This work introduces FaceLiveNet, a holistic endto-end deep networks which can perform face verification and liveness detection simultaneously. An interactive scheme for facial expression recognition is proposed to perform liveness detection, providing better generalization capacity and higher security level. The proposed framework is low-cost as it relies on commodity hardware instead of costly sensors, and lightweight with much fewer parameters comparing to the other popular deep networks such as VGG16 and FaceNet. Experimental results on the benchmarks LFW, YTF, CK+, OuluCASIA, SFEW, FER2013 demonstrate that the proposed FaceLiveNet can achieve state-of art performance or better for both face verification and facial expression recognition. We also introduce a new protocol to evaluate the global performance for face authentication with the fusion of face verification and interactive facial expression-based liveness detection.</font>


![avatar](/images/Fig1.jpg)
   




