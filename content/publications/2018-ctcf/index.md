---
title: "[5] Predicting CTCF-mediated chromatin interactions by integrating genomic and epigenomic features"
featured_title: "Predicting the 3D Genome with Machine Learning"
authors: ["me", "J Andricovich", "Z Zeng", "J Zhu", "A Tzatsos", "W Peng"]
date: "2018-09-01"
weight: 20
publication_types: ["article-journal"]
publication: "*Nature Communications* 9 (1), 4221"
url_pdf: "https://pubmed.ncbi.nlm.nih.gov/30310060/"
url_code: "https://github.com/ykai16/Lollipop"
featured: true
image:
  caption: 'CTCF Prediction Model'
  focal_point: ""
  preview_only: false
summary: "We developed a machine learning framework to predict 3D chromatin loops mediated by CTCF, integrating genomic motif orientation with epigenomic features."
---

CTCF (CCCTC-binding factor) is often called the "master weaver" of the genome, creating the 3D loops and domains that organize our DNA. While there are thousands of CTCF binding sites, only a fraction of them form loops. Predicting which pairs of CTCF sites interact is a major challenge in understanding 3D genome architecture.

We addressed this by developing a predictive model that integrates:
1.  **Motif Orientation**: The convergent orientation of CTCF motifs is a strong predictor, but not sufficient on its own.
2.  **Epigenomic Features**: We incorporated histone modification data, chromatin accessibility, and co-factor binding.
3.  **Genomic Distance**: The distance between sites is a key constraint.

Our model accurately predicts chromatin loops in varying cell types and highlighted the importance of RNA Polymerase II and Cohesin in stabilizing these structures. This work represented a step forward in "in silico" folding of the genome, allowing us to predict the impact of mutations on 3D structure and gene regulation.
