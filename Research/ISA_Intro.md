---
author: Hunter Carroll
subtitle: Defining the Problem
---

# Introduction 

The applicative motivation is thin structures and shells, common in engineering for their advantageous properties of being lightweight, efficient on material cost, and are used to assemble large stuctures. However, "Despite their ubiquity, they remain challenging from the point-of-view of computational mechanics. One of the reasons for this is their sensitivity to perturbations in materials, kinematic constraints, and shell geometry itself due to manufacturing imperfections." @RoperHakulaButler2025.

# Uncertainty Quantification

Uncertainty quantification is utilized to "predict the behaviour of systems under uncertain conditions" @CU_UQ_group. Classified as the following two types of errors, 

1. **Epistemic Uncertainty**: Incomplete knowledge of a system.
2. **Aleatoric Uncertainty**: Inherent variability in the system.

# Uncertainty Quantification as a Probabilistic Quantity




The authors go on to present a method
for uncertainty quantification (UQ) as a probabilistic quantity where one makes “many” observations and corresponding predictions
of a particular scalar quantity of interest, forming the ratio of observations to predictions as a measure of discrepancy, and utilizing

both the mean and variance of this ratio to perform the UQ analysis. While we consider a distinct measure-theoretic UQ framework,
the perspective provided in [2] nonetheless proves prescient in this work.

At a high-level, we present novel developments within a
machine learning-enabled data-to-distribution pipeline to transform (noisy) observed and predicted spatio-temporal data clouds into
samples of (vector-valued) quantities of interest (QoI) that enables the construction of a data-consistent update to initially assumed
distributions on model parameters via the ratio of (non-parametric) observed and predicted distributions of the QoI


