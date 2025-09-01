---
title: "Taming Bandwidth Bottlenecks in Federated Learning via ECN-based Gradient Compression" 
weight: 35
tags: ["federated learning","ECN", "deep learning"]
author: ["Javier Palomares, Jr", "Chiara Camerota" , "Flavio Esposito", "Estefania Coronado" , "Cristina Cervelló-Pastor", "Muhammad Shuaib Siddiqui "]
description: "The paper addresses communication bottlenecks in Federated Learning and introduces Selective Compression via Adaptive Lightweight Protocol, which dynamically selects compression levels based on local gradient variance and uplink bandwidth. Published on 2025 21st International Conference on Network and Service Management (CNSM)." 
summary: "The paper addresses communication bottlenecks in Federated Learning and introduces Selective Compression via Adaptive Lightweight Protocol." 
cover:
    image: "SCALP.png"
    relative: false
editPost:
    #URL: "https://ieeexplore.ieee.org/abstract/document/10584163"
    Text: "2025 21st International Conference on Network and Service Management (CNSM)"

---

---

##### Download

+ [Paper](CNSM.pdf)

---

##### Abstract


Communication bottlenecks remain a key challenge in Federated Learning (FL), particularly in dynamic and resource-constrained environments. While compression strategies such as sparsification and quantization reduce communication overhead, they are typically agnostic to runtime variability and the semantic relevance of updates. This paper introduces SCALP (Selective Compression via Adaptive Lightweight Protocol), a novel hybrid communication compression mechanism that jointly considers local gradient variance and uplink bandwidth to guide adaptive filtering decisions. Each worker dynamically selects a compression level mapped to a tunable filtering ratio, balancing communication reduction and update relevance. The selected compression level is encoded as a 2-bit signal embedded in the Explicit Congestion Notification (ECN) field of the IP header, enabling stateless, lightweight signaling without modifying transport-layer protocols. Experimental results on CNN and CNN-LSTM models over the CMAPSS dataset show that SCALP reduces transmitted data by over 25% while maintaining convergence time within 2% and achieving up to 2.15% higher final accuracy compared to baseline methods. Comparative analysis against Deep Gradient Compression (DGC) and bandwidth-aware filtering confirms SCALP’s ability to integrate gradient-level relevance and network conditions for robust, efficient training in bandwidth-constrained FL scenarios.

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
