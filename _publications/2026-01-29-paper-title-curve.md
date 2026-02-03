---
title: "CURVE: Learning Causality-Inspired Invariant Representations for Robust Scene Understanding via Uncertainty-Guided Regularization"
collection: publications
category: manuscripts
permalink: /publication/2026-01-29-paper-title-curve
excerpt: 'Out-of-Distribution Generalization, Robust Representation Learning, Uncertainty-Aware Learning, Scene Graphs, Autonomous Driving.'
date: 2026-01-29
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2601.20355'
citation: '@misc{liang2026curve,
      title={CURVE: Learning Causality-Inspired Invariant Representations for Robust Scene Understanding via Uncertainty-Guided Regularization}, 
      author={Yue Liang and Jiatong Du and Ziyi Yang and Yanjun Huang and Hong Chen},
      year={2026},
      eprint={2601.20355},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2601.20355}, 
}'
---
Scene graphs provide structured abstractions for scene understanding, yet they often overfit to spurious correlations, severely hindering out-of-distribution generalization. To address this limitation, we propose CURVE, a causality-inspired framework that integrates variational uncertainty modeling with uncertainty-guided structural regularization to suppress high-variance, environment-specific relations. Specifically, we apply prototype-conditioned debiasing to disentangle invariant interaction dynamics from environment-dependent variations, promoting a sparse and domain-stable topology. Empirically, we evaluate CURVE in zero-shot transfer and low-data sim-to-real adaptation, verifying its ability to learn domain-stable sparse topologies and provide reliable uncertainty estimates to support risk prediction under distribution shifts
