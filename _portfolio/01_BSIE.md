---
title: "Boltzmann-Shannon Index"
excerpt: "A novel metric for evaluating clustering balance by jointly capturing geometric and frequency-based probability distributions, enabling more reliable assessment of data partitioning and fairness."
collection: portfolio
---

*Pre-Print:*  
👉 [**Boltzmann-Shannon Index: A Geometric-Aware Measure of Clustering Balance**](https://arxiv.org/abs/2512.02397)

---

The **Boltzmann-Shannon Index (BSI)** is introduced as a normalized measure for evaluating the quality of clustering in continuous data. Unlike traditional metrics, BSI jointly captures both **frequency-based probabilities** (how many samples fall into each cluster) and **geometry-based probabilities** (how the state space is partitioned). By comparing these two perspectives, the index quantifies how evenly the data is distributed across clusters in a way that reflects both density and structure.

Clustering is a fundamental task in data analysis, yet existing evaluation metrics often provide **incomplete or misleading signals**. Many approaches focus solely on frequency (e.g., cluster sizes) or geometry (e.g., distances and compactness), failing to capture the interplay between how data is distributed and how space is partitioned.

This limitation becomes particularly critical in:
- **Highly imbalanced datasets**, where cluster sizes differ significantly  
- **Continuous dynamical systems**, where geometric structure carries essential meaning  
- **Resource allocation problems**, where fairness depends on density rather than count  

A more principled metric is needed, one that integrates both perspectives into a single, interpretable quantity.

The Boltzmann-Shannon Index measures the **agreement between two probability distributions** defined over clusters:

- A **frequency-based distribution**, derived from the proportion of samples in each cluster  
- A **geometry-based distribution**, derived from how the continuous space is partitioned  

By quantifying the similarity between these distributions, BSI provides a measure of how well the clustering reflects the underlying data structure.

Importantly, the clustering labels:
- May arise from geometric partitioning  
- But are not restricted to it  
- Making the index broadly applicable across different settings  

We evaluated the Boltzmann-Shannon Index across multiple scenarios:

- **Synthetic Gaussian mixtures**  
  → BSI correctly identifies balanced vs. imbalanced clusterings  

- **Iris benchmark dataset**  
  → Provides consistent interpretation aligned with intuitive structure  

- **High-imbalance resource allocation scenario**  
  → Detects inequality with high sensitivity where traditional metrics fail  

Across these experiments, BSI demonstrated:
- Robustness to imbalance  
- Consistency across different data regimes  
- Smooth numerical behavior  

The Boltzmann-Shannon Index provides a **new lens for evaluating clustering and partitioning**, with several important implications:

- **Fairness-aware resource allocation**  
  → Detects and quantifies inequality in distributions  

- **Optimization and control**  
  → Smooth formulation allows integration as a regularization term  

- **Dynamical systems analysis**  
  → Evaluates the effectiveness of symbolic representations (coarse-graining)  

- **General clustering evaluation**  
  → Offers a more complete alternative to traditional metrics
