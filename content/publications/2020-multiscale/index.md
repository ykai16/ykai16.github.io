---
title: "[24] Multi-scale annotations of chromatin states in 127 human cell-types"
featured_title: "A Multi-Scale Atlas of Chromatin States"
authors: ["me", "S Tsoucas", "S Suo", "GC Yuan"]
date: "2020-12-22"
publication_types: ["article-journal"]
publication: "*bioRxiv*"
featured: true
image:
  caption: 'Multi-scale Chromatin'
  focal_point: ""
  preview_only: false
summary: "We proposed a multi-scale Hidden Markov Model to annotate chromatin states, revealing a nested hierarchy of genomic domains across 127 human cell types."
---

The genome is organized into distinct chromatin states—combinations of histone modifications that define active promoters, enhancers, and repressed regions. Traditional methods annotate these states at a single, fixed resolution (e.g., 200bp). However, chromatin organization is inherently multi-scale, ranging from nucleasome-level modifications to large topographic domains (TADs).

We developed a **Multi-scale Hidden Markov Model (MHMM)** to capture this complexity. By applying this model to Epigenomics Roadmap data across 127 human cell types, we generated a comprehensive atlas of chromatin states at varying resolutions.

Key insights include:
*   **Hierarchical Organization**: We observed that broad chromatin domains (like Polycomb repression) often contain nested, fine-scale regulatory elements that traditional methods miss.
*   **Context Dependency**: The function of a regulatory element often depends on its broader chromatin context, which our multi-scale annotations explicitly capture.
*   **Universal Grammar**: We defined a "grammar" of chromatin state transitions that is conserved across diverse cell types.

This multi-scale atlas serves as a fundamental resource for interpreting genomic data and understanding the hierarchical nature of epigenetic regulation.
