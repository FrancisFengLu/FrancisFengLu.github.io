---
permalink: /
title: "Welcome, my friend!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

*I hope you have found the Dragon Warrior within yourself.*

<p style="font-size:1.25em;margin-bottom:0.3em"><strong>My goal:</strong> to build the next generation of statistical genetics, powered by GPUs.</p>

**Core areas:** Statistical genetics · GWAS · Rare-variant analysis · GPU computing · Applied mathematics<br>
**Background:** Applied Math & Statistics (Johns Hopkins) → Bioinformatics (Dana-Farber) → Statistical Genetics (MGH)

About Me 
======

I am a Research Assistant at Massachusetts General Hospital, supervised by [Dr. Wei Zhou](https://wzhoulab.com/) and collaborating with [Prof. Seunggeun (Shawn) Lee](https://www.leelabsg.org/). Prior to this, I worked at Dana-Farber Cancer Institute in the [Center for Functional Cancer Epigenetics (CFCE)](https://cfce.dana-farber.org/), where I collaborated with many biology labs.

I am dedicated to bringing ideas from AI infrastructure and electrical engineering into statistical genetics, to enable a new era for the field.

I lead the development of **cuSAIGE** (to be generalized as **xSAIGE** to support hardware beyond NVIDIA GPUs), which runs SAIGE, a widely used mixed-model method for genome-wide association studies (GWAS), entirely on the GPU. It is about 3,400× faster than the original SAIGE for binary traits and 15,000× faster for quantitative traits, and substantially faster than all competing methods, at 50× to 4,500× lower cost, while remaining mathematically identical to SAIGE, with results differing only in the last digits. Analyses that were once too expensive to run, such as testing thousands of traits across an entire biobank, are now routine.

Few methods are designed with their statistics, approximations and engineering considered together. cuSAIGE shows how much this can unlock, and suggests that more sophisticated methods are within immediate reach. I want to design such methods, whose assumptions, approximations and computation are developed together, to uncover more of the genetic associations that precision medicine relies on.

**Please feel free to contact me for collaboration.**

My academic background is in **Applied Math/Statistics** and **Computer Science**, and I have trained in **Bioinformatics** at Dana-Farber Cancer Institute.

This journey began in 2024 when, as an applied math student, I sought a research area that could fully leverage my interdisciplinary strengths. I was introduced to a project at the **Center for Functional Cancer Epigenetics (CFCE)**, focusing on clustering cell types using scATAC-seq data—a process strikingly similar to a final project I completed in a high-dimensional statistics course with Prof. Mauro Maggioni at Hopkins.

Through this experience, I saw how much mathematical thinking can contribute to biomedical research, and I learned to make complex, high-dimensional ideas clear to collaborators from different fields. This led me to statistical genetics, where I now combine statistical theory with high-performance computing to make biobank-scale analyses faster and more affordable.

