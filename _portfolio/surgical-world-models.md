---
title: "Hierarchical Predictive World Models for Surgical Video"
excerpt: "Master's Thesis developing temporal and spatial state abstraction models to learn robust predictive dynamics directly in latent spaces, avoiding traditional pixel-space reconstruction collapse."
collection: portfolio
---

### Master's Thesis — Ludwig Maximilian University of Munich (LMU)
*April 2026 – Present (Ongoing)*

#### Overview
Most modern surgical AI models attempt to model complex surgical videos using video generative frameworks or pixel-space reconstruction. However, surgery involves high-frequency visual noise (fluid flows, camera lighting drift, tissue textures) that is irrelevant to decision-making or robotic control. 

This project aims to build **hierarchical predictive world models** that learn directly in a compressed, structured latent space. By leveraging spatial and temporal state abstractions, the agent learns to predict downstream surgical events and tool actions without spending model capacity reconstructing pixel values.

#### Key Focus Areas
* **Predictive Representation Learning:** Training encoder-predictor systems (analogous to Joint-Embedding Predictive Architectures) to predict future latent states from action sequences.
* **Temporal State Abstraction:** Grouping low-level actions into multi-granular macro-actions (hierarchical plan segments) to support long-horizon plans.
* **Avoiding Collapse:** Investigating regularizers and contrastive/non-contrastive objectives to ensure robust representation learning without information collapse.
