---
title: "Adaptive Positional Encoding with Regularization for Robust Edge Computing Applications" 
weight: 9
tags: ["transformer","malware detection", "RoPE"]
author: ["Chiara Camerota" , "Flavio Esposito"]
description: "By adapting the RoPE angle to network and device conditions, our method preserves spatial relationships and stabilizes transformer attention during periods of stress. This work was presented at the ACM SIGCOMM 2025 Networking Women Professional Development Workshop (N2Women’25)." 
summary: "The paper addresses communication bottlenecks in Federated Learning and introduces Selective Compression via Adaptive Lightweight Protocol." 
cover:
    image: "SCALP.png"
    relative: false
editPost:
    #URL: "https://ieeexplore.ieee.org/abstract/document/10584163"
    Text: "ACM SIGCOMM 2025 Networking Women Professional Development Workshop (N2Women’25)"

---

---

##### Download

+ [Paper](SIGCOMM.pdf)

---

##### Abstract

Detecting malware in Internet of Things (IoT) systems is challenging due to resource limitations. As a result, detection and classification models are often deployed in cloud environments or distributed across devices and servers. In distributed scenarios, transferring model weights can create bottlenecks, with packet loss risking training stability. This research presents a modified Visual Transformer (ViT) that utilizes Rotational Positional Encoding (RoPE), which takes into account network bandwidth, quality, and device status. Our model effectively resolves bottleneck issues while ensuring accurate malware detection. Under extreme network stress, our approach on a medium ViT achieves 82.1% classification accuracy, compared to 65.2% for the standard RoPE—a 16.9 percentage point improvement. In micro-scale architectures, Modified RoPE reaches 97.6% accuracy versus 84.0% for Standard RoPE, representing a 13.6 percentage point improvement. These results confirm that our regularization methodology effectively maintains spatial relationships during network degradation while improving positional encoding across various architectural scales.
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

+ [Poster](poster.pdf)
