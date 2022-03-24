---
title: "<font color=blue><u>IDECYS+ : MOBile IDEntity for the Masses (FUI 25)</u></font>"
collection: expressions
excerpt: "The IDECYS+ project aims to develop a new flexible and secure digital solution integrating into the facial identification system for detecting facial attacks presented by printed photo, video or 3D masks."
redirect_to: 
---

2020-2022 : The IDECYS+ project aims to develop a new flexible and secure digital identity solution for facial anti-spoofing for European legal entities, and primarily for the 3 million French TPE/PME. This project proposed a solution based on deep learning to distinguish facial attacks by printed photo, video or 3D mask by integrating into the facial identification system:

- Collabration labotories: [L3i](https://l3i.univ-larochelle.fr/), [AriadNext](https://www.ariadnext.com/)
- with [Burie Jean-Christophe](https://l3i.univ-larochelle.fr/Burie-Jean-Christophe-MCF-HDR), [Muriel Visani](https://pageperso.univ-lr.fr/mvisani/), [Petra Gomez-Krämer](https://pageperso.univ-lr.fr/petra.gomez/), [Muhammad Muzzamil LUQMAN](https://scholar.google.com/citations?user=ACfqR3UAAAAJ&hl=en), [Marchand Sylvain](http://sylvain-marchand.info/), [Ahmad Montaser Awal](https://scholar.google.fr/citations?user=lADqsksAAAAJ&hl=fr)

**Reasearch methods**: Face Anti-Spoofing (FAS) / Presentation Attack Detection (PAD) is an important measure to prevent spoof attacks for face biometric systems. The challenges of face anti-spoofing is to distinguish the real presentation from the presentation attacks with fine difference in terms of image texture. The methods based on fine-grained classification, multimodal learning and long-term attention have applied for face anti-spoofing. 

- [VitTransPAD: Video Transformer using Convolution and Self-attention for Face Presentation Attack Detection:](https://arxiv.org/pdf/2203.01562.pdf)

*Key words: Video-based transformer, multi-scale multi-head self-attention, face presentation attack detection*

Many works based on Convolution Neural Networks (CNNs) for face PAD formulate the problem as an image-level binary classification task without considering the context. Alternatively, Vision Transformers (ViT) using self-attention to attend the context of an image become the mainstreams in face PAD. Inspired by ViT, we design a Video-based Transformer for face PAD with short/long-range spatio-temporal attention which can not only focus on local details but also the context of a video. The proposed Multi-scale Multi-Head Self-Attention enables the model to learn a fine-grained representation to perform pixel level discrimination required by face PAD. We also introduce convolutions to our ViTransPAD to integrate desirable proprieties of CNNs which can gain a good computation-accuracy balance. To the best of our knowledge, this is the first approach using video-based transformer for face PAD which can serve as a new backbone for further study.


![avatar](/images/vittranspad.png)
   



