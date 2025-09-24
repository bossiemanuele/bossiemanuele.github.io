---
title: "Don't Bother The Driver: Sensor-Scheduling for Cognitive State Estimation During Automated Driving"
excerpt: "State Estimation, Machine Learning, Sensor Scheduling, Human-Autonomy Interaction, Automated Driving.
<br/><img src='/images/SURF - FigureDraft.png' width='300' height='500'>"
collection: portfolio
---

1. *In Preparation. Topic: Physiologial Signals Analysis in Dynamic Driving Environment (venue: Conference Paper).*
2. *In Preparation: Topic: Multimodal Cognitive State Estimaton and Sensor Scheduling (venue: Journal Paper).*

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGujyHH9tA/JSHWUrUArVrKniXcT9h-5Q/watch?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGujyHH9tA&#x2F;JSHWUrUArVrKniXcT9h-5Q&#x2F;watch?utm_content=DAGujyHH9tA&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">

This research project has been completed during Summer 2025 at the [**Jain Research Lab**](https://engineering.purdue.edu/JainResearchLab/), the research laboratory of Dr. Jain at **Purdue University**.
The PI for this project is **Dr. Jain**, Associate Professor of Mechanical Engineering (by courtesy in Aeronautics & Astronautics). The Ph.D. Mentor for this project is
**S. Jeevanandam**, Ph.D. candidate in Mechanical Engineering.
This project have been funded by NSF Career Award (Dr. Jain) and through the **2025 Summer Undergraduate Research Fellowship (SURF)** program at Purdue University.

As part of the program, I have been selected to give a talk about this research at the **Purdue University Summer Symposium** on July 30, 2025. At the top of this page you can find a 15-minutes overview of the research project, aimed at a *general, non-technical, audience*.

## Abstract

Estimating human cognitive states is increasingly important for enabling safe and efficient human–autonomy interaction, particularly in safety-critical settings such as automated driving. Cognitive states, such as trust, workload, and perceived risk, are known to influence driver behavior but are not directly observable; instead, they must be inferred from behavioral data, physiological data, and intermittent self-reports of these states. Prior work on cognitive state estimation in human–autonomy interaction—--particularly in automated driving--—has predominantly used static, categorical models based on unimodal inputs, with limited support for real-time updates, uncertainty quantification, or adaptive querying of human input.

This paper introduces a novel modeling framework that treats cognitive states as continuous-valued, time-varying latent variables and automation reliance as a discrete, observable output. The framework facilitates combining self-reports and psychophysiological measurements in state estimation framework that utilizes a hybrid dynamical system model. Crucially, the framework also quantifies predictive uncertainty, enabling the system to identify when to actively solicit human input. This allows for adaptive self-report scheduling to improve sample efficiency while minimizing user burden. The central research question is: *How can online machine learning and dynamical systems theory be combined to enable real-time, participant-specific estimation of automation reliance—--while quantifying uncertainty to guide when adaptive systems should actively seek human input during automated driving?*

Our approach involves predicting a human's trust, workload, and perceived risk using a affine dynamical model. These latent states are then used to predict reliance through a tree-based classifier. Model uncertainty informs whether to incorporate new self-reports; when unavailable but needed, a particle filter fuses selected physiological and gaze features via an auxiliary tree-based ensemble model to refine predictions under non-stationary conditions.

Experimental results show improved prediction and estimation accuracy over static or purely data-driven baselines, underscoring the advantages of integrating dynamical systems with machine learning in an online framework to account for the time-varying nature of human behavior. This approach enables individualized, continuous cognitive state estimation and lays the groundwork for closed-loop decision-making. Future work will focus on incorporating these estimates into controllers that intelligently manage driver engagement in complex, dynamic environments.
