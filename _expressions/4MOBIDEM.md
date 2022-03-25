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

- [Simple Triplet Loss Based on Intra/Inter-class Metric Learning for Face Verification:]()[[ICCVW2017]](https://www.lrde.epita.fr/dload/papers/ming.17.iccv-amfg.pdf)[[code]](https://github.com/hengxyz/facenet_class_wise_triplet_loss_pub)

*Key words: Metric learning, class-wise triplet loss, CNNs, face recognition*

<font size=3>In this work, we propose a simple class-wise triplet loss based on the intra/inter-class distance metric learning which can largely reduce the number of the possible triplets to be learned. However the simplification of the classic triplet loss function has not degraded the performance of the proposed approach. The experimental evaluations and the visualization of the distribution of the learned features has also shown the effectiveness of the proposed method comparing to the other state-of-the-art loss function such as cross-entropy loss and centerloss.</font>


![avatar](/images/comparison.png)

- [Dynamic Multi-Task Learning for Face Recognition with Facial Expression :]()[[ICCVW2019]](https://arxiv.org/pdf/1911.03281.pdf)[[code]](https://github.com/hengxyz/Dynamic_multi-task-learning)

*Key words: Multi-task learning, Dynamic task weights, CNNs, face recognition, facial expression recognition*

<font size=3>Benefiting from the joint learning of the multiple tasks in the deep multi-task networks, many applications have shown the promising performance comparing to single-task learning. However, the performance of multi-task learning framework is highly dependant on the relative weights of the tasks. How to assign the weight of each task is a critical issue in the multi-task learning. Instead of tuning the weights manually which is exhausted and time-consuming, in this work we propose an approach which can dynamically adapt the weights of the tasks according to the difficulty for training the task. We demonstrate our approach for face recognition with facial expression and facial expression recognition from a single input image based on a deep multi-task learning Conventional Neural Networks (CNNs). Both the theoretical analysis and the experimental results demonstrate  this multi-task learning with dynamic weights boosts of the performance on the different tasks comparing to the state-of-art methods with single-task learning. </font>


![avatar](/images/DynamicMTL.jpg)

- [FaceLiveNet: End-to-End Networks Combining Face Verification With Interactive Facial Expression-based Liveness Detection (ICPR2018):](https://www.researchgate.net/profile/Zuheng-Ming/publication/325229686_FaceLiveNet_End-to-End_Face_Verification_Networks_Combining_With_Interactive_Facial_Expression-based_Liveness_Detection/links/5aff47b5aca2720ba095e75d/FaceLiveNet-End-to-End-Face-Verification-Networks-Combining-With-Interactive-Facial-Expression-based-Liveness-Detection.pdf)

*Key words: Multi-task learning, interactive face authentification, face recognition, facial expression recognition, CNNs*

<font size=3>Existing face verification architectures seldom integrate any liveness detection or keep such stage isolated from face verification as if it was irrelevant. This may potentially result in the system being exposed to spoof attacks between the two stages. This work introduces FaceLiveNet, a holistic endto-end deep networks which can perform face verification and liveness detection simultaneously. An interactive scheme for facial expression recognition is proposed to perform liveness detection, providing better generalization capacity and higher security level. The proposed framework is low-cost as it relies on commodity hardware instead of costly sensors, and lightweight with much fewer parameters comparing to the other popular deep networks such as VGG16 and FaceNet. Experimental results on the benchmarks LFW, YTF, CK+, OuluCASIA, SFEW, FER2013 demonstrate that the proposed FaceLiveNet can achieve state-of art performance or better for both face verification and facial expression recognition. We also introduce a new protocol to evaluate the global performance for face authentication with the fusion of face verification and interactive facial expression-based liveness detection.</font>


![avatar](/images/Fig1.jpg)
   




