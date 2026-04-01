---
title: "Don’t Bother the Driver: Sensor-Scheduling for Cognitive State Estimation During Automated Driving"
excerpt: "A hybrid dynamical systems and machine learning framework for predicting driver reliance on automation, combined with an adaptive sensor-scheduling strategy that reduces intrusive self-reports while improving prediction accuracy."
collection: portfolio
---


👉 *A Sensor-Scheduling Approach to Predict Human Reliance on Automation During Automated Driving*  
  <span style="font-size: 0.9em; color: #555;">Submitted to IFAC World Congress 2026</span>

👉 *Identifying Informative Psychophysiological Indicators and Time Scales for Inferring Human Cognition During Automated Driving: An Information-Theoretic Approach*  
  <span style="font-size: 0.9em; color: #555;">Submitted to ASPIRE 2026 (HFES Annual Meeting)</span>

## Main Work

Safe and effective automated driving requires continuous awareness of the driver’s cognitive state. However, key variables such as trust, workload, and perceived risk are not directly observable and must be inferred from indirect measurements. This work introduces a hybrid modeling framework that combines dynamical systems and machine learning to estimate driver reliance on automation in real time, while minimizing the need for intrusive self-reports.

Human behavior in automated driving is dynamic, uncertain, and highly individual. Existing approaches typically fall into two categories:

- **Data-driven models**, which rely on physiological or behavioral signals but lack interpretability and temporal structure  
- **Cognitive models**, which capture dynamics but are often static and difficult to adapt online  

A major limitation across both is the reliance on **frequent self-reports**, which are:
- intrusive  
- impractical in real-time settings  
- cognitively disruptive  

The key question becomes:

**How can we accurately estimate human cognitive states while minimizing the need to query the driver?**

## Key Idea

We model human cognition as a **time-varying dynamical system** coupled with a data-driven decision mechanism.

**1. Hybrid Cognitive Model**

- Cognitive states (trust, risk, workload) evolve as continuous dynamical variables  
- Reliance on automation is modeled as a discrete decision  
- A decision-tree classifier replaces rigid threshold rules, capturing individual behavior more flexibly  

**2. Online Adaptation**

- Model parameters are updated in real time as new data becomes available  
- A lightweight structure enables fast re-identification (~260 ms per update)

**3. Sensor Scheduling**

- Self-reports are treated as **costly sensors**  
- A scheduling policy triggers them only when prediction accuracy degrades  
- This creates a closed-loop estimation system balancing accuracy and intrusiveness  

The framework was validated on a human-subject study with 16 participants in a driving simulator.

Key findings:

- **+10% accuracy improvement** using decision-tree models over threshold-based approaches  
- **~76% average prediction accuracy** with online adaptation  
- **Only ~27% of self-reports required**, significantly reducing driver burden  

Importantly, selectively using fewer self-reports maintained performance while improving user experience.

---

## Information-Theoretic Extension

In a complementary study, we investigate which physiological signals are most informative for cognitive inference using **mutual information**.

Key insights:

- No single physiological feature is universally optimal across individuals  
- Informative signals emerge at **intermediate time scales (≈50–70 seconds)**  
- Strong **inter-subject variability** suggests the need for personalized sensing strategies  

This analysis provides a principled foundation for selecting sensors and time windows in real-world systems.

## Impact & Applications

This work enables a new class of **cognition-aware autonomous systems**:

- **Adaptive human-autonomy interaction**  
  → systems that respond to user state in real time  

- **Reduced sensing burden**  
  → fewer interruptions while maintaining performance  

- **Personalized automation**  
  → models tailored to individual behavior  

- **Control integration**  
  → foundation for closed-loop systems that manage driver engagement  
