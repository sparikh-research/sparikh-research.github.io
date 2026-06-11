---
layout: single
title: "Research Journey"
permalink: /research/
author_profile: true
---

My research focuses on building mathematically grounded, interpretable representation learning models for structured systems. Below are the key pillars of my active research journey.

---

## 1. Hierarchical Predictive World Models for Surgical Video
*MSc Thesis Project, LMU Munich*

### Motivation
Standard generative models operating in pixel space spend excessive capacity modeling irrelevant visual details (such as blood flow, tissue textures, or lighting changes). For robotic surgery and downstream task planning, the agent needs to model the underlying state transitions and multi-granular action hierarchies. By learning representation abstractions through predictive objectives (e.g., latent prediction models), we aim to build robust world models that avoid pixel-space failure and capture the true underlying causal transitions.

### Current Status
- Designing the hierarchical predictive network architecture.
- Prototyping state abstraction and latent temporal planning objectives.

### Open Questions
- How do we guarantee representation sufficiency without collapse under varying action temporal granularities?
- What are the mathematical conditions for robust state abstraction in highly non-stationary environments like clinical surgery?

### Resources
- [Master's Thesis Project Overview](/projects/surgical-world-models)

---

## 2. Cross-Modal JEPA for Binary Analysis
*Hiwi Research (Research Assistant), LMU Munich*

### Motivation
Understanding and verifying machine-compiled binaries (assembly code) is critical for system security and safety. However, assembly representations and compiler optimizations introduce non-trivial structural variations. We aim to learn cross-modal representations mapping assembly instructions to high-level semantic graphs using a Joint-Embedding Predictive Architecture (JEPA), ensuring structural properties of control flow graphs are preserved.

### Current Status
- Developed a cross-modal JEPA mapper to align control flow graph structure with sequence-level representations.
- Successfully distilled a 1.3B parameter LLM into a 6× smaller encoder while maintaining state-of-the-art representation quality.

### Open Questions
- How can we formally verify that structural algebraic properties (gadgets) are preserved during latent cross-modal projection?
- Can we steer binary representations to highlight specific vulnerabilities using activation space modifications?

### Resources
- [Cross-Modal JEPA Project Page](/projects/cross-modal-jepa)

---

## 3. Formal Verification & AI for Science
*Theoretical & Experimental Projects*

### Motivation
As machine learning models scale and solve increasingly complex mathematical and scientific tasks, empirical validation is no longer sufficient. My goal is to use formal verification methods (such as interactive theorem proving in Lean) and algebraic structure preservation to guarantee correctness in both compiler optimizations and downstream mathematical assertions.

### Current Status
- **Interactive Theorem Proving:** Formally verified the Ford-Fulkerson maximum flow algorithm in Lean 4.
- **Quantum Compiler Optimization:** Designed a graph-partitioning compiler phase for the AlphaTensor-Quantum framework using METIS, demonstrating a 35.3% reduction in quantum T-count by preserving local gadget structures.

### Open Questions
- How can we build neuro-symbolic models that bridge formal interactive theorem proving with deep learning search spaces?
- How do we define curvature-based metrics that evaluate structural generalization versus memory lookup in protein language models?
