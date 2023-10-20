---
title: "Reinforcement Learning from Multiple Sensors via Joint Representations"
authors: "Philipp Becker, Sebastian Markgraf, Fabian Otto, Gerhard Neumann"
conference: arXiv preprint
categories:
  - arXiv
tags: 
  - Representation Learning
link: https://arxiv.org/abs/2302.05342
bibtex: /assets/data/cite/becker2023reinforcement.bib
---

# Abstract

In many scenarios, observations from more than one sensor modality are available for reinforcement learning (RL). For example, many agents can perceive their internal state via proprioceptive sensors but must infer the environment's state from high-dimensional observations such as images. For image-based RL, a variety of self-supervised representation learning approaches exist to improve performance and sample complexity. These approaches learn the image representation in isolation. However, including proprioception can help representation learning algorithms to focus on relevant aspects and guide them toward finding better representations. Hence, in this work, we propose using Recurrent State Space Models to fuse all available sensory information into a single consistent representation. We combine reconstruction-based and contrastive approaches for training, which allows using the most appropriate method for each sensor modality. For example, we can use reconstruction for proprioception and a contrastive loss for images. We demonstrate the benefits of utilizing proprioception in learning representations for RL on a large set of experiments. Furthermore, we show that our joint representations significantly improve performance compared to a post hoc combination of image representations and proprioception.