---
title: "Boltzmann-Shannon Index"
excerpt: "Defintion of the Boltzmann-Shannon Index, an indicator of how well the data is spread based on both frequency-based probability and geometric-based probability; in other words, we are introducing an index that will give a sense of how well the state-space is partitioned."
collection: portfolio
---

*Pre-Print:* [**Boltzmann-Shannon Index: A Geometric-Aware Measure of Clustering Balance**](https://arxiv.org/abs/2512.02397)

The **Boltzmann-Shannon Index** (BSI) for clustered continuous data is introduced as a normalized measure that captures the relationship between geometry-based and frequency-based probability distributions defined over the clusters. In essence, it quantifies the similarity across densities of the clusters, which are defined by a given labeling. This labeling may originate from a geometric partitioning of the state space itself, but need not in general. We illustrate its performance on synthetic Gaussian mixtures, the Iris benchmark data set, and a high-imbalance resource-allocation scenario, showing that the BSI provides a coherent assessment in cases where traditional metrics give incomplete or misleading signals. Moreover, in the resource-allocation setting where equal density may be associated with a "fair" distribution, we demonstrate that BSI not only detects inequality with high sensitivity, but also offers a numerically smooth measure that can be easily embedded in optimization frameworks as a regularization term for modern policy-making. Finally, the BSI also offers a new measure of the effectiveness for a given symbolic representation, i.e. coarse-grain states, for continuous-valued data recorded from complex dynamical systems.
