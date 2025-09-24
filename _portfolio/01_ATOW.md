---
title: "An Information-Theoretic Framework for Modeling Aircraft Actual Takeoff Weight "
excerpt: "This research develops an interpretable machine learning framework to estimate aircraft Actual Takeoff Weight (ATOW) using flight metadata and ADS-B data, supported by feature analysis and error correction. The approach improves accuracy, robustness, and transparency over existing methods, enabling safer and more efficient aviation operations.
<br/><img src='/images/Takeoff picture.webp' width='300' height='500'>"
collection: portfolio
---

*"An Information-Theoretic Framework for Modeling Aircraft Actual Takeoff Weight (ATOW)." In AIAA SciTech 2026 Forum. (Accepted)*

This project has been funded through **ERAU-URI Eagle Prize Award** for the AY 2024-2025. The advisor for this project is **Dr. AlMomani**, Assistant Professor of Mathematics and Data Science and Program Director of Data Science. This is an *individual research project* conducted by Emanuele Bossi.

Part of this project consisted in the participation in the **PRC Data Challenge**, competition organized by *EUROCONTROL*. The team submitted a rough draft of their initial solution and ranked in the TOP 25 among 132 teams.

## Abstract

Accurate estimation of an aircraft’s Actual Takeoff Weight (ATOW) is a critical challenge in aviation analytics. ATOW, defined as the aircraft’s total mass at the start of takeoff, directly affects climb performance, fuel burn, runway requirements, emissions, and noise. However, ATOW values are not publicly disclosed and must often be approximated, leading to substantial errors in trajectory prediction and environmental modeling when inaccurate assumptions are used. Existing methods span physics-based models, climb-phase inference, and modern machine learning (ML) approaches, yet each has significant limitations. Physics-based methods require unavailable flight-specific data and rely on idealized assumptions, while climb-based methods are sensitive to unmodeled factors such as thrust variation or turbulence. ML approaches, although promising, depend on noisy or incomplete surveillance data, risk overfitting to training distributions, and often lack interpretability—an important consideration in safety-critical contexts.

This research proposes a three-pronged approach to overcome these challenges. First, we systematically analyze feature sources—including flight metadata and ADS-B trajectory data—using statistical techniques such as singular value decomposition and conditional mutual information to quantify their predictive value for ATOW. Second, we introduce an algorithm to detect and correct erroneous ADS-B measurements, thereby improving data reliability prior to model training. Third, we develop an interpretable ML framework that not only improves estimation accuracy but also provides transparent explanations for weight predictions. Our results highlight the importance of integrating feature selection, data quality control, and interpretable modeling to achieve robust, explainable ATOW estimates, with the ultimate goal of enabling safer and more efficient aviation operations.

<img src='/images/ATOW Flowchart.png'>
