---
layout: paper
title: "Tunable Kinematic Smoothness for Generative Mechanism Synthesis"
image: /images/papers/2026-IDETC-bolanos-pareto.png
authors: Bolaños D, Ataei M, and Goucher-Lambert K.
year: 2026
ref: Bolanos et al. <i>ASME IDETC</i> 2026
journal: Proceedings of the ASME International Design Engineering Technical Conferences (2026).
pdf: /pdfs/papers/bolanos-kinematics-idetc.pdf
---


# Abstract
Mechanism synthesis is well established for path, motion, and function generation tasks, with recent generative approaches achieving state-of-the-art curve-following accuracy. Yet geometric path fidelity captures only one dimension of mechanism quality. In many engineering applications, the kinematic character of the coupler trajectory, how smoothly and uniformly the end-effector moves through its arc, is equally consequential. A mechanism that traces the desired path but exhibits velocity spikes or high jerk may be unsuitable wherever motion regularity directly affects performance. We present a post-generation selection framework that introduces kinematic smoothness as a tunable design objective atop a pretrained generative synthesis model, requiring no retraining. Given a target coupler curve, the framework generates a pool of candidate mechanisms via two complementary sampling strategies: affine input-space sampling and crank prefix conditioning. Each candidate is then scored on geometric fidelity and a composite speed-invariant smoothness loss. A user-specified weighting then combines the two objectives, exposing the Pareto trade-off between path accuracy and kinematic smoothness. The framework operates entirely at inference time and generalizes to any synthesis method that produces multiple simulable candidates. Evaluated across 56,000 candidate mechanisms spanning 500 validation samples, combining both sampling strategies reduces median smoothness loss by 91% relative to an unguided baseline, while the balanced preset reduces smoothness loss to roughly one-third of the curve-only value at a cost of only 0.24 additional DTW units.
