---
layout: default
permalink: /research/
---

# Research

## Neural-based Constrained Motion Planning

Constrained motion planning, which means finding a collision-free path under some constraints, is still a difficult task for robots. The problem is that the constraint is usually implicit, which makes sampling directly on the constrained manifold impossible.

Hence, we introduce a neural sampler into our project. It can generate informed samples that are close to the manifold, and in turn reduces the number of samples required before finding a path.
[**[video]**](https://sites.google.com/view/constrainedmpnet/home)

## Robot Motion Imitation

Teaching by demonstration is an interesting method that can increase the flexibility of robots. It reduces the requirement of users' programming and robot knowledge. The traditional way, known as "behavior cloning", is to learn a mapping from the state space to the action space.

In this project, however, we adopt "Generative Adversarial Imitation Learning", raised by Jonathan Ho, on top of the behavior cloning. It integrates inverse reinforcement learning and reinforcement learning, so that the agent can extract a criterion from the demonstrations and optimize under it.
