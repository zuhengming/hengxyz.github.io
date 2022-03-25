---
title: "<font color=blue><u>MOBIDEM: MOBile IDEntity for the Masses (FUI 21) </u></font>"
collection: expressions
excerpt: "Realization of an electronic signature platform with mobile telephone based on face recognition using deep learning at a high level of validity."
redirect_to: 
---

2016-2019 : The object of project MOBIDEM is to realize  an electronic platform with an advanced electronic signature capacity for an electronic document provided by a third party, which is easy to use and low-cost. The task of the L3i is to develop a biometric authentification system based on face recogntion:

- Collabration labotories: [L3i](https://l3i.univ-larochelle.fr/), [AriadNext](https://www.ariadnext.com/), [Oodrive](https://www.oodrive.com/fr/), [Oberthur TECHNOLOGIES](https://web.archive.org/web/20121124001819/http://www.oberthur.com/)
- with [Jean-Christophe Burie](https://l3i.univ-larochelle.fr/Burie-Jean-Christophe-MCF-HDR), [Joseph Chazalon](https://scholar.google.fr/citations?user=zu8wSDAAAAAJ&hl=en), [Muhammad Muzzamil LUQMAN](https://scholar.google.com/citations?user=ACfqR3UAAAAJ&hl=en), [Muriel Visani](https://pageperso.univ-lr.fr/mvisani/), [Ahmad Montaser Awal](https://scholar.google.fr/citations?user=lADqsksAAAAJ&hl=fr)

**Reasearch methods**: The challenge of face recognition is to learn a representation being robust to the variation of face pose, gesture, occulussion and illumination in the wild scenarios. It is also required to recognize the heterogeneous faces presented in the different modalities (e.g., natural faces v.s. caricatures). **Metric learning,  Multitask learning and Multimodal learning** are used to develop the **face recognition using large-scale datasets** and the related problems such as **facial expression recognition** and **face detection**. 

- [VitTransPAD: Video Transformer using Convolution and Self-attention for Face Presentation Attack Detection (ICIP2022_submission):](https://arxiv.org/pdf/2203.01562.pdf)

*Key words: Video-based transformer, multi-scale multi-head self-attention, face presentation attack detection*

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
   




