---
layout: default
title: Home
---

# ICEGenAI: Improving Computational Efficiency in Modern Generative Models

**Principal Investigator:** Angelo Casolaro
**Institution:** University Parthenope of Naples, Department of Science and Technology  
**Research Area:** AI and data science / Scientific computing

---

## Project Overview
The "Improving Computational Efficiency in Modern Generative Models" (ICEGenAI) project aims to build a new generation of Generative Artificial Intelligence (GenAI) models capable of producing high-quality synthetic data in a reasonable time. Current State-of-the-Art (SOTA) generative models require massive computational resources and time to numerically integrate Differential Equations. 
This project tackles this bottleneck by introducing a novel "High-Order Flow Map Matching" (HO-FMM) framework. Instead of sequentially estimating the probability distribution, this method directly learns the flow map using high-order Taylor series expansions to enable single-step or few-steps generation. 

---

## Main Objectives
* **Develop High-Order FMM Theory:** Integrate high-order time-derivatives (velocity, acceleration, jerk) into the FMM loss function to improve accuracy.
* **Design Inference-Optimized Architectures:** Create specialized neural network models to accurately approximate high-order flow maps.
* **Generalize FMM for Multi-Task Inverse Problems:** Extend the framework using Operator-based interpolants to create a unified Multi-Task HO-FMM model.
* **Demonstrate High-Fidelity Generation:** Achieve fast, high-quality sample generation and validate on large-scale remote sensing environmental datasets.

---

## Milestones & Progress Tracker
This tracker monitors the progress of the 5 Work Packages (WPs) planned over the 24-month project duration.

### WP1: HO-FMM Development (Months 1 - 8)
*Objective:* Theoretical formulation of the HO-FMM framework.
- [ ] **Deliverable 1:** Report on SOTA Limitations.
- [ ] **Deliverable 2:** Mathematical Formulation of HO-FMM.

### WP2: Design of HO-FMM Neural Network architecture (Months 3 - 12)
*Objective:* Design of the neural network architectures.
- [ ] **Deliverable 1:** Baseline Performance Report.
- [ ] **Deliverable 2:** HO-FMM Prototype & Preliminary Validation.

### WP3: Multi-Task HO-FMM Implementation (Months 9 - 18)
*Objective:* Generalization of the framework for multiple tasks.
- [ ] **Deliverable 1:** Report on Multi-Task Framework Extension.
- [ ] **Deliverable 2:** Multi-Task Validation Results.

### WP4: Comprehensive Validation and Benchmarking (Months 13 - 24)
*Objective:* Empirical evaluation of computational efficiency.
- [ ] **Deliverable 1:** Final Benchmarking Report (quantitative tables and visual samples).

### WP5: Dissemination (Months 9 - 24)
*Objective:* Dissemination and release of the open-source code.
- [ ] **Deliverable 1:** Publication of research papers.
- [ ] **Deliverable 2:** Release of open-source code and models.
