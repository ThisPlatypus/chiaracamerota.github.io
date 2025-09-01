
---
title: "Work in Progress"
description: "My current reading list."
---
<div class="image-container">
    <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWwza3EyY3hqYmY4aHd2enUxMzU1enZzNW91Nm51bmFwYjRlZnVheSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oz8xTUmZABI3PGwDe/giphy.gif" alt="Image 1"></div>

##### Work in Progress


  
-  **Communication-Efficient Federated Learning with Top K selection** (Joint with Javier Palomares, Estefanía Coronado and Flavio Esposito) -- [Under submission: ACM SIGCOMM 2025]
      _ABSTRACT: Communication bottlenecks hinder faster convergence in Federated Learning (FL) architectures. Several model compression techniques have been proposed to cope with this problem, e.g., sparsification or quantization. Although sound, these solutions are network-agnostic and rarely consider each worker's contributions to learning convergence.   
To this aim, we introduce SCALP, a network-aware compression strategy that reduces gradient exchange overhead by selectively transmitting the most informative updates based on the statistical deviation of each worker's contribution and current bandwidth conditions. Workers locally adapt compression levels using a probabilistic filtering strategy and encode this state with minimal overhead into the TCP header using 2-bit ECN signaling. We evaluated SCALP on CNN and CNN-LSTM models on the CMAPSS data set, and show how we gain a reduction in communication cost by more than 25\%,  maintaining convergence performance comparable to centralized training at the beginning of the study._
  
    <div class="image-container"><img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExa2ZtdTliMm9wcnNpYXZwenA2YWdmazMxYmhkaTFodHloZHd3cGptbSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/lizSDX8mHfbstV0GKw/giphy.gif" alt="Image 2">
</div>

