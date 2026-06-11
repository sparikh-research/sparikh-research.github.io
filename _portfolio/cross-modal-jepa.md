---
title: "Cross-Modal JEPA & Interpretability for Binary Analysis"
excerpt: "Research Assistant project mapping compiled assembly code sequences to high-level semantic graphs using a Joint-Embedding Predictive Architecture (JEPA), including distillation and attention mechanics analysis."
collection: portfolio
---

### Research Assistant (Hiwi) — Ludwig Maximilian University of Munich (LMU)
*April 2026 – September 2026*

#### Overview
Understanding compiled binary machine code (assembly) is essential for security auditing, formal verification, and vulnerability detection. However, assembly instructions are structurally different from high-level source code or abstract syntax trees, and compiler optimizations introduce severe semantic alignment issues.

In this research assistantship, I led two main tracks to build and interpret representation models for compiled binary analysis:

#### 1. Cross-Modal Representation Learning & Distillation
* **Joint-Embedding Predictive Architecture (JEPA):** We developed a cross-modal JEPA that aligns sequential assembly code representations with high-level structural control flow graphs (CFGs). This ensures that structural and semantic properties are preserved in the joint latent space.
* **LLM Distillation:** Distilled a 1.3B parameter LLM encoder into a 6× smaller target encoder, achieving state-of-the-art results on downstream binary similarity and vulnerability detection benchmarks while reducing inference cost dramatically.

#### 2. Mechanistic Interpretability
* **Attention Probing:** Probed cross-modal attention weights and latent alignments to extract human-understandable program semantics.
* **Structural Preservation:** Mathematically and empirically verified that compiling code preserves local control-flow invariants (gadgets) within the model's internal representations.
