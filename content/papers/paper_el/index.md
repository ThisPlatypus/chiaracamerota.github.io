---
title: "Load Profile Generation for Robust Optimization:  A Stochastic Approach Based on Conditional Probability Approximation" 
weight: 40
tags: ["profile generation"," robust optimization", "stochastic approximation"]
author: ["Lorenzo Becchi", "Chiara Camerota", "Matteo Intravaia", "Marco Bindi", "Antonio Luchetta" , "Tommaso Pecorella"]
description: "This paper investigates the generation of load profiles using a stochastic approach, focusing on creating robust estimations that rely solely on CPU resources. The methodology outlined emphasizes computational efficiency and is designed for practical implementation in resource-constrained environments. This work will be presented at the 2025 IEEE International Conference on Environment and Electrical Engineering and the 2025 IEEE Industrial and Commercial Power Systems Europe (EEEIC / I&CPS Europe), highlighting its relevance in the context of renewable energy management and optimization." 
summary: "This paper investigates on how to generate load profile with stochastic approach." 
cover:
    image: "hist.png"
    relative: false
editPost:
    #URL: "https://ieeexplore.ieee.org/abstract/document/10584163"
    Text: "22025 IEEE International Conference on Environment and Electrical Engineering and 2025 IEEE Industrial and Commercial Power Systems Europe (EEEIC / I&CPS Europe)"

---

---

##### Download

+ [Paper](Load.pdf)

---

##### Abstract
With the growing integration of renewable energy sources into distributed grids, accurate household‐level load forecasting becomes essential for robust energy management and optimization. This paper proposes a lightweight stochastic profile generation method grounded in conditional probability approximation. First, empirical conditional distributions are mined from historical load data via hourly histogram binning and correlation analysis. Second, a Monte Carlo‐inspired “flock” of plausible future load trajectories is generated iteratively, each endowed with an occurrence probability. Validation on the Ausgrid dataset (127 prosumer profiles over one year) shows that the probabilistic mining step requires only 0.5–0.6 s for history depths of 30–180 days, while generating 200 scenarios takes merely 8.1 ms, with a total memory footprint of approximately 200 KB. These computational and storage efficiencies render the approach suitable for online deployment on edge devices, enabling robust optimization under uncertainty in renewable energy communities.

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

