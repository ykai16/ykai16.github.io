---
title: "[19] Identifying Quantitatively Differential Chromosomal Compartmentalization Changes and Their Biological Significance from Hi-C data using DARIC"
featured_title: "Detecting Compartment Switches in the 3D Genome"
authors: ["me", "N Liu", "SH Orkin", "GC Yuan"]
date: "2023-01-01"
weight: 6
publication_types: ["article-journal"]
publication: "*BMC Genomics*"
url_pdf: "https://pubmed.ncbi.nlm.nih.gov/37833630/"
url_code: "https://github.com/ykai16/DARIC"
url_dataset: "https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116862"
featured: true
image:
  caption: 'DARIC Analysis visualization'
  focal_point: ""
  preview_only: false
summary: "We developed DARIC (Differential Analysis of Regulated In-Compartments) to systematically identify significant chromosomal compartmentalization changes from Hi-C data."
---

Chromosomal compartments are key features of the 3D genome organization, segregating the genome into active (A) and inactive (B) spatial domains. Changes in these compartments are often associated with developmental transitions and disease states, such as cancer. However, systematically identifying and quantifying these changes has been a challenge.

We developed **DARIC** (Differential Analysis of Regulated In-Compartments), a computational method designed to identify statistically significant differential compartmentalization changes between biological conditions. Unlike traditional methods that rely on fixed thresholds or visual inspection, DARIC utilizes a rigorous statistical framework to detect compartment switches (e.g., A-to-B or B-to-A transitions) and subtle quantitative changes in compartment strength.

We applied DARIC to Hi-C data from leukemia cell lines and normal hematopoietic cells, revealing that compartment switching is not just a passive reflection of gene expression but can actively drive oncogenic programs. Specifically, we identified leukemia-specific compartment changes that facilitate the activation of key oncogenes and the repression of tumor suppressors.

This work provides a robust tool for the chromatin biology community to dissect the functional role of 3D genome reorganization in development and disease.
