---
title: "Addressing Data Security in IoT: Minimum Sample Size and Denoising Diffusion Models for Improved Malware Detection" 
tags: ["malware detection"," traffic classification", "deep learning"]
author: ["Chiara Camerota", "Lorenzo Pappone", "Tommaso Pecorella", "Flavio Esposito"]
description: "This paper investigates on how to define the miimum sample siz and improving the data agumentation for Traffic Images. Published 20th International Conference on Network and Service Management, 2024." 
summary: "This paper investigates on how to define the miimum sample siz and improving the data agumentation for Traffic Images." 
cover:
    image: "paper23.png"
    relative: false
editPost:
    #URL: "https://ieeexplore.ieee.org/abstract/document/10584163"
    Text: "20th International Conference on Network and Service Management"

---

---

##### Download

+ [Paper](paperSampe.pdf)

---

##### Abstract

Machine learning (ML) has emerged as a compelling approach to identify attacks in network traffic security. 
Existing malware detection strategies often concentrate on specific facets, such as efficient data collection, particular types of malware, or handling data scarcity. While valid, these strategies typically overlook the potential for minimizing sample size, focusing instead on data augmentation. This work introduces a novel method to determine the minimum sample size necessary to achieve a specified accuracy level, measured by the F1 score derived from the confusion matrix. We focus on TCP header traffic data transformed into images through flow-splitting techniques for multi-class traffic classification. In addition, we introduce a diffusion model to generate new synthetic traffic images and show that our method outperforms existing techniques in terms of stability and predictability. This study also compares the effectiveness of synthetic image augmentation using Generative Adversarial Networks (GANs) and Denoising Diffusion Probabilistic Models (DDPM) in improving image recognition and classification accuracy. 

---


##### Citation

*NOT PUBLISHED YET*

```BibTeX
@inproceedings{camerota2024addressing,
  title={Addressing Data Security in IoT: Minimum Sample Size and Denoising Diffusion Models for Improved Malware Detection},
  author={Camerota, Chiara and Pappone, Lorenzo and Pecorella, Tommaso and Esposito, Flavio},
  booktitle={20th International Conference on Network and Service Management},
  year={2024},
  doi={TBD}
}
```
---
##### Related material

+ [Presentation slides](PRes.pdf)
