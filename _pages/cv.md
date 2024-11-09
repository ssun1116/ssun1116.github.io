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

