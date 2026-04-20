---
title: "AI-Based Phishing and Spam Detection"
excerpt: "Evaluation of machine learning models for phishing detection under dataset shift, combining public awareness analysis with AI-based classification of evolving cyber threats."
collection: portfolio
level: undergraduate
institution: erau
---

## Project Overview

<table>
  <tr>
    <td><strong>Project</strong></td>
    <td>AI-Based Phishing and Spam Detection</td>
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
    <td><strong>Advisor</strong></td>
    <td>Sameer Abufardeh</td>
  </tr>
  <tr>
    <td><strong>Role</strong></td>
    <td>Software Lead</td>
  </tr>
  <tr>
    <td><strong>Total Award</strong></td>
    <td>$3,529</td>
  </tr>
  <tr>
    <td><strong>Project Dates</strong></td>
    <td>April 2024 – April 2025</td>
  </tr>
</table>

👉 [*Phishing in the Digital Age: Surveying Public Awareness and Leveraging AI for Defense*](/files/NCUR.pdf)  
<span style="font-size: 0.9em; color: #555;">National Conference on Undergraduate Research (NCUR) 2025</span>

## Overview

This project investigated the effectiveness of **machine learning models for phishing and spam detection** in the presence of rapidly evolving cyber threats. The work combined:

- **Public awareness analysis** through surveys and outreach  
- **AI-based classification models** trained on historical datasets  
- **Evaluation under dataset shift**, where modern phishing attacks differ significantly from training data  

## Motivation

Phishing attacks have increased significantly in both **volume and sophistication**, with attackers leveraging automation and AI to generate more convincing messages.

Despite high awareness levels:
- A large portion of users still engage in **risky online behavior**  
- Traditional detection systems struggle to adapt to **new attack patterns**  

This raises a critical question:

> **Can machine learning models trained on historical datasets reliably detect modern, AI-driven phishing attacks?**

## Technical Approach

### Data

- **Training Dataset**  
  - Enron Email Dataset (2004)  
  - ~33,000 emails  

- **Testing Dataset**  
  - Phishing Validation Dataset (2024)  
  - ~2,000 emails (real + AI-generated phishing samples)  

### Feature Engineering

Text-based features were extracted using:
- **Unigrams**
- **Bigrams**
- **Trigrams**

This representation captures local linguistic patterns commonly used in phishing attempts.

### Models Evaluated

- Naïve Bayes  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest  
- XGBoost  

## Key Results

### Training Performance (Enron Dataset)

- Accuracy up to **99%** across multiple models  

### Testing Performance (Modern Phishing Dataset)

- Significant drop in performance:
  - Random Forest: ~78%  
  - Logistic Regression: ~72%  
  - Naïve Bayes: ~70%  

## Key Insight

> **High training accuracy does not translate to real-world robustness.**

The results highlight a fundamental challenge:

- Models trained on outdated datasets fail to generalize to **modern phishing attacks**
- This is due to **dataset shift** and evolving attack strategies  

## Broader Impact

This project emphasizes the need for:

- **Continuously updated datasets**  
- Adaptive and robust learning frameworks  
- Integration of **human awareness and AI-based defenses**  

It also highlights the importance of aligning AI systems with **real-world, evolving threat environments** rather than static benchmarks.
