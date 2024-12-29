---
title: "Reinforcement Learning from Multiple Sensors via Joint Representations"
authors: "Philipp Becker, Sebastian Mossburger, Fabian Otto, Gerhard Neumann"
conference: 
    - Reinforcement Learning Conference (RLC)
categories:
  - RLC
tags: 
  - Representation Learning
link: https://arxiv.org/abs/2302.05342
bibtex: /assets/data/cite/becker2024combining.bib
website: https://pbecker93.github.io/coral_pp/
code: https://github.com/pbecker93/CoRAL/
---

# Abstract

Learning self-supervised representations using reconstruction or contrastive losses improves performance and sample complexity of image-based and multimodal reinforcement learning (RL). Here, different self-supervised loss functions have distinct advantages and limitations depending on the information density of the underlying sensor modality. Reconstruction provides strong learning signals but is susceptible to distractions and spurious information. While contrastive approaches can ignore those, they may fail to capture all relevant details and can lead to representation collapse. For multimodal RL, this suggests that different modalities should be treated differently based on the amount of distractions in the signal. We propose Contrastive Reconstructive Aggregated representation Learning (CoRAL), a unified framework enabling us to choose the most appropriate self-supervised loss for each sensor modality and allowing the representation to better focus on relevant aspects. We evaluate CoRAL's benefits on a wide range of tasks with images containing distractions or occlusions, a new locomotion suite, and a challenging manipulation suite with visually realistic distractions. Our results show that learning a multimodal representation by combining contrastive and reconstruction-based losses can significantly improve performance and solve tasks that are out of reach for more naive representation learning approaches and other recent baselines. 