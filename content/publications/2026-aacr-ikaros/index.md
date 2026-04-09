---
title: "[24] Development of a novel Ikaros/Aiolos transcriptional signature and correlation with patient response in multiple myeloma patients treated with CELMoDs"
featured_title: "An RNA-seq Biomarker for CELMoD Response in Multiple Myeloma"
authors: ["S Tamim", "N Stong", "Y Kai", "D Jankeel", "B Gaffney", "A Kurtova", "AR Perez", "C Fontanillo", "TT Chow", "PR Hagner", "D Jeyaraju", "CC Bjorklund", "M Amatangelo", "K Wang", "A Gandhi", "M Ortiz-Estevez"]
date: "2026-04-08"
weight: 1
publication_types: ["paper-conference"]
publication: "*Cancer Research* 86 (7 Suppl), Abstract nr 2714. AACR Annual Meeting 2026; San Diego, CA"
abstract: ""
featured: true
image:
  caption: 'Ikaros/Aiolos Transcriptional Signature in Multiple Myeloma'
  focal_point: ""
  preview_only: false
summary: "We developed a quantitative RNA-seq based Ikaros/Aiolos activity score that is significantly associated with patient progression-free survival in multiple myeloma patients treated with CELMoD agents."
---

Multiple myeloma (MM) is a neoplasm characterized by the clonal proliferation of malignant plasma cells in the bone marrow. CELMoD™ agents—including iberdomide (IBER) and mezigdomide (MEZI)—modulate Cereblon to induce the degradation of the hematologic transcription factors Ikaros (Ik) and Aiolos (Ai), exerting anti-proliferative and pro-apoptotic effects on MM cells. While Ik/Ai protein degradation can be semi-quantified by immunohistochemistry (IHC), clinical responses are not always correlated with IHC readouts, motivating a more quantitative genomic approach.

We performed **CUT&RUN and ChIP-seq** on the H929 MM cell line to map Ik binding targets genome-wide. By intersecting these targets with differential expression analysis (DESeq2) across multiple CELMoD treatments (LEN, POM, MEZI, IBER) at multiple timepoints, we compiled a high-confidence **Ik regulon** consisting of 115 up-regulated and 95 down-regulated target genes.

**Gene Set Variation Analysis (GSVA)** was then applied to this regulon to derive a sample-level **Ik activity score**. Key findings include:

- **On-treatment decrease**: RNA-seq paired samples from MEZI-treated (N=7) and IBER-treated (N=41) patients showed significantly lower Ik activity scores at cycle 2 day 15 compared to screening.
- **Association with survival**: Using an optimal cutpoint, greater on-treatment reduction in Ik activity score was significantly associated with longer **progression-free survival (PFS)** in IBER-treated patients.
- **Concordance with IHC**: The RNA-seq based score showed significant agreement with IHC-based Ik degradation scores in a validation cohort (N=22), supporting its use as a complementary or standalone biomarker.

This work establishes a robust transcriptomic framework for monitoring Ik/Ai target engagement and predicting clinical outcomes in MM patients receiving CELMoD therapy.
