---
title: "Open the Black Box: Step-based Policy Updates for Temporally-Correlated Episodic Reinforcement Learning"
authors: "Ge Li, Hongyi Zhou, Dominik Roth, Serges Thilges, Fabian Otto, Rudolf Lioutikov, Gerhard Neumann"
conference: Under Submission
categories:
  - Unpublished
tags: 
  - Trust Regions
  - Movement Primitives
# link:
# bibtex: /assets/data/cite/otto2023open.bib
---

# Abstract

In applying Reinforcement Learning to robot trajectory generation, two key challenges commonly emerge. First, the stochastic exploration strategies of step-based Reinforcement Learning are unable to produce high-order smooth trajectories. Second, existing methods struggle with effectively modeling movement correlations among different time steps and degrees of freedom, which are crucial for complex tasks and safety measures. Episodic Reinforcement Learning methods address these challenges by employing parameterized trajectory generators like Movement Primitives, framing the problem as contextual optimization. While effective in generating smooth trajectories and capturing some movement correlations, these methods lack in utilizing temporal structure within trajectories, resulting in suboptimal sample efficiency. We introduce the Temporally-Correlated Episodic Reinforcement Learning (TCE) method to address these shortcomings. TCE enhances exploration efficiency by sampling multi-second trajectories in a parameterized space, thereby assuring high-order trajectory smoothness and the capture of movement correlations. For policy updates, TCE breaks down the entire trajectory into smaller segments, evaluating each segment on its distinct advantages. This nuanced approach allows us to utilize temporal information obtained during trajectory execution. We validate the effectiveness of TCE through experiments on various robotic manipulation tasks, showing its advantages over step-based and episodic Reinforcement Learning approaches.