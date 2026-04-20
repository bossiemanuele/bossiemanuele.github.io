---
title: "Uncovering Direct Influence Networks of Takeoff Weight"
excerpt: "An information-theoretic network framework to identify which variables carry direct, non-redundant information about aircraft takeoff weight, improving interpretability and guiding principled model design."
collection: portfolio
level: undergraduate
institution: erau
---

## Project Overview

<table>
  <tr>
    <td><strong>Project</strong></td>
    <td>Uncovering Direct Influence Networks of Takeoff Weight</td>
  </tr>
  <tr>
    <td><strong>Sponsor</strong></td>
    <td>Undergraduate Research Institute (URI)</td>
  </tr>
  <tr>
    <td><strong>Institution</strong></td>
    <td>Embry-Riddle Aeronautical University</td>
  </tr>
  <tr>
    <td><strong>Role</strong></td>
    <td>Lead</td>
  </tr>
  <tr>
    <td><strong>Total Award</strong></td>
    <td>$6,000</td>
  </tr>
  <tr>
    <td><strong>Project Dates</strong></td>
    <td>September 2024 – June 2025</td>
  </tr>
</table>

👉 [*Uncovering Direct Influence Networks of Takeoff Weight: Network Science and Information Theoretic Approach*](https://arc.aiaa.org/doi/10.2514/6.2026-2014)  
<span style="font-size: 0.9em; color: #555;">2026 AIAA Science and Technology Forum</span>

## Motivation

Aircraft **Actual Takeoff Weight (ATOW)** is a fundamental quantity in aviation operations, directly influencing:
- Climb performance and acceleration  
- Fuel consumption and emissions  
- Trajectory prediction and air traffic management decisions  

Despite its importance, **true takeoff weight is rarely available** in open datasets such as ADS-B. As a result, ATOW must be inferred indirectly from observable variables.

While prior work has focused on improving **prediction accuracy** using physics-based models and machine learning, an important question remains largely unanswered:

> **Which variables truly carry information about takeoff weight, and which relationships are merely indirect or redundant?**

## Key Contribution

This work introduces an **information-theoretic network framework** that shifts the focus from prediction accuracy to **interpretability and informational relevance**.

Instead of asking *“how well can we predict takeoff weight?”*, the project asks:

> **Which variables carry unique, non-redundant information about ATOW?**

This perspective provides:
- Interpretability beyond black-box models  
- Insight into dependency structure  
- Guidance for principled feature selection  

## Methodology

The system models flight and operational variables as a **network**:

- **Nodes** → variables (e.g., altitude, velocity, aircraft type)  
- **Edges** → statistical dependencies  

The framework proceeds in two main steps:

### 1. Information Discovery
Pairwise dependencies are identified using **mutual information**, capturing both linear and nonlinear relationships:

\[
I(X; Y)
\]

### 2. Information Refinement
To isolate **direct influences**, the framework applies **conditional mutual information**, removing dependencies explainable by other variables:

\[
I(X; Y \mid Z)
\]

This step:
- Eliminates indirect correlations  
- Reduces redundancy  
- Produces a **sparse network of direct dependencies**

## Key Findings

The resulting **direct influence network** reveals several important insights:

- Strong clustering emerges among physically related variables (e.g., altitude, velocity, vertical rate)  
- The dependency structure reflects underlying **flight dynamics**  
- Most importantly:

> **Takeoff weight exhibits an extremely sparse direct neighborhood**

After removing indirect dependencies:
- Only **aircraft type** and **destination airport** remain directly connected to ATOW  
- Common trajectory-derived features (e.g., average altitude, velocity summaries) **do not carry independent information**

This result highlights a critical limitation:

> **High predictive performance does not imply true informational relevance**

## Implications

This work provides a **diagnostic lens** for takeoff weight estimation:

- Identifies **redundant vs. informative features**  
- Explains why some ML models succeed despite weak physical grounding  
- Guides development of:
  - More interpretable models  
  - Better feature representations  
  - Hybrid physics–ML approaches  

Importantly, the framework does not replace predictive models, but **complements them** by improving their transparency and robustness.

## Future Work

- Develop **richer ADS-B feature representations** capturing fine-grained dynamics  
- Integrate informational insights into **learning-based models**  
- Evaluate robustness across **different aircraft types and operational settings**  
- Explore applications to other **aerospace and networked dynamical systems**
