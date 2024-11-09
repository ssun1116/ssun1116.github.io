---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Integrated Biomedical and Life Sciences, Korea University, 2024 (GPA: 4.33 / 4.50)
* B.S. in Biosystem and Biomedical Sciences, Korea University, 2022 (GPA: 4.11 / 4.50)

Research experience
======
* Constructing Human Brain Transcriptome Single-cell (BTS) Atlas
  * Established a comprehensive human brain atlas spanning 7 gestational weeks to 90 years, integrating eight single-cell RNA-seq datasets to trace gene expression dynamics across development.
  * Characterized temporal and cellular specificity of 3,380 neurodevelopmental disorder risk genes.
  * Collaborated with Prof. Xin Jin at Scripps Research Institute in performing sex-specific analysis using the established BTS atlas to assess hormone receptor differences in perinatal and juvenile brains.

* Role of Angiogenesis in Alzheimer’s Disease Identified in ROSMAP Cohort (Collaboration with Prof. Minah Kim, Columbia University Irving Medical Center)
  * Served as a visiting researcher from Feb 5 to Feb 22, 2024, leading transcriptomic analyses in Alzheimer’s Disease and mentoring peers in RNA-seq methodologies.
  * Validated up-regulation of the angiogenesis gene in Alzheimer’s Disease using single-nucleus RNA-seq data from ROSMAP cohort, applying the pseudo-bulk approach to mitigate sample-level variability.

* Profiling RNF146 Dysregulation in Autism Model Induced by Valproic Acid (Collaboration with Prof. Yong-Seok Lee, Seoul National University College of Medicine)
  * Performed proteomic analysis via mass spectrometry to identify differentially expressed proteins in VPA-exposed mice, emphasizing RNF146 upregulation and Wnt/β-catenin pathway dysregulation.
  * Investigated transcriptomic changes associated with Rnf146 overexpression, linking it to autism-associated behavioral impacts.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Skills
======
* Programming Languages
  * C, R, Python
* Operating Systems
  * Unix/Linux
* Data Analysis
  * Single-cell RNA-seq, Transcriptomics, Proteomics, Epigenomics

