---
title: "Passive Military Drone Detection Systems"
excerpt: "Development of a fully passive, real-time acoustic system for UAV detection using signal processing and feature-based classification."
collection: portfolio
level: undergraduate
institution: erau
---

## Project Overview

<table>
  <tr>
    <td><strong>Project</strong></td>
    <td>Passive Military Drone Detection Systems</td>
  </tr>
  <tr>
    <td><strong>Sponsor</strong></td>
    <td>Center for Aerospace Resilient Systems (CARS)</td>
  </tr>
  <tr>
    <td><strong>Institution</strong></td>
    <td>Embry-Riddle Aeronautical University</td>
  </tr>
  <tr>
    <td><strong>Advisor</strong></td>
    <td>Ahmed I. Sulyman</td>
  </tr>
  <tr>
    <td><strong>Role</strong></td>
    <td>Capstone Project Team Lead</td>
  </tr>
  <tr>
    <td><strong>Total Award</strong></td>
    <td>$2,500</td>
  </tr>
  <tr>
    <td><strong>Project Dates</strong></td>
    <td>August 2025 – May 2026</td>
  </tr>
</table>

## Overview

This capstone project focuses on the design and implementation of a **fully passive drone detection system** based on acoustic sensing and real-time signal processing. The goal is to detect the presence of unmanned aerial vehicles (UAVs) without relying on active emissions such as radar, making the system suitable for **stealth and low-power defense applications**.

The system processes environmental audio signals and identifies drone signatures using frequency-domain analysis and feature-based detection logic.

## System Architecture

The detection pipeline is structured as follows:

1. **Signal Acquisition**  
   Environmental audio is captured using a microphone array.

2. **Time-Frequency Analysis**  
   The signal is transformed using Short-Time Fourier Transform (STFT) to obtain a spectrogram representation.

3. **Feature Extraction**  
   Key spectral features are extracted to characterize drone-specific acoustic signatures.

4. **Detection Logic**  
   A threshold-based decision mechanism evaluates the extracted features to determine the presence of a drone.

5. **Post-Processing**  
   Temporal smoothing is applied to reduce false positives and improve detection stability.

This modular architecture enables real-time processing and adaptability to different operational environments.

## My Contributions

As **Team Lead**, I played a central role in both the technical development and coordination of the project:

- Led the **software architecture design** for the detection pipeline  
- Developed components for **STFT-based signal processing and feature extraction**  
- Designed and implemented the **threshold-based detection algorithm**  
- Contributed to **system integration and testing**  
- Coordinated team efforts and supported preparation for **design reviews (PDR, CDR)**  

## Performance

The system was evaluated across multiple scenarios, including varying distances and environmental conditions. Results demonstrate the feasibility of **passive acoustic detection** with competitive accuracy and robustness.

<img src='/images/DroneAccuracy.png'>

## Team

This project was carried out as part of a multidisciplinary capstone team.

<img src='/images/CapstoneTeam.png'>

## Impact

This work contributes to the development of **low-cost, passive UAV detection technologies** with potential applications in:
- Military and defense systems  
- Critical infrastructure protection  
- Airspace monitoring and security  

By avoiding active sensing, the system offers a **covert and energy-efficient alternative** to traditional detection methods such as radar.

## Deliverables

The following key project deliverables document the design, development, and validation of the system throughout the capstone lifecycle:

- **Initial Design Proposal (IDP)**  
  [View Document](/files/IDP.pdf)

- **Preliminary Design Review (PDR)**  
  [View Document](/files/PDR.pdf)

- **Critical Design Review (CDR)**  
  [View Document](/files/CDR.pdf)
