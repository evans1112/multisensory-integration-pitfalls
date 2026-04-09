# Analyzing Multisensory Integration: Do's and Don'ts

Code and simulations accompanying:

> Zhu, H., Beierholm, U., & Shams, L. (2026). *Analyzing multisensory
> integration: do's and don'ts.* .

This repository provides the model-based inference pipeline, simulation
scripts, and figure-generation code used in the paper. The pipeline
disentangles unisensory reliability, amodal priors, and binding tendency
within a Bayesian Causal Inference (BCI) framework, and demonstrates why
behavioral indices such as illusion magnitude and the temporal binding
window cannot be interpreted as direct readouts of "integration strength."

---

## Overview

The code in this repository reproduces:

- **Figure 1.** Simulations of how unisensory reliability and binding
  tendency (`p_common`) jointly shape crossmodal bias and the
  sound-induced flash illusion under BCI.
- **Figure 2.** 
-
- The minimal, reproducible BCI model specification described in
  Section 3 of the paper.
- The model-based inference pipeline (design → unisensory baselines →
  parameter estimation → interpretation).

All simulations are built on top of the BCI Python Toolbox
(Zhu et al., 2024).


