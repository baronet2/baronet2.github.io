---
title: "A diffusion model to shrink proteins while maintaining their function"
date: 2025-07-19
publishDate:  2025-07-19
authors: ["**Ethan Baron***, Alan Nawzad Amin*, Ruben Weitzman, Debora Susan Marks, Andrew Gordon Wilson"]
publication_types: ["2"]
abstract: "Many proteins useful in modern medicine or bioengineering are challenging to make in the lab, fuse with other proteins in cells, or deliver to tissues in the body because their sequences are too long. Shortening these sequences typically involves costly, time-consuming experimental campaigns. Ideally, we could instead use modern models of massive databases of sequences from nature to learn how to propose shrunken proteins that resemble sequences found in nature. Unfortunately, these models struggle to efficiently search the combinatorial space of all deletions, and are not trained with inductive biases to learn how to delete. To address this gap, we propose SCISOR, a novel discrete diffusion model that deletes letters from sequences to generate protein samples that resemble those found in nature. To do so, SCISOR trains a de-noiser to reverse a forward noising process that adds random insertions to natural sequences. As a generative model, SCISOR fits evolutionary sequence data competitively with previous large models. In evaluation, SCISOR achieves state-of-the-art predictions of the functional effects of deletions on ProteinGym. Finally, we use the SCISOR de-noiser to shrink long protein sequences, and show that its suggested deletions result in significantly more realistic proteins and more often preserve functional motifs than previous models of evolutionary sequences."
featured: true
publication: "ICML Workshop on Exploration in AI Today, Vancouver, Canada"
links:
  - icon_pack: fas
    icon: trophy
    name: Best Paper, EXAIT @ ICML
    url: 'https://exait-workshop.github.io/ap/'
  - icon_pack: fa
    icon: file-pdf
    name: PDF
    url: 'https://openreview.net/pdf?id=YqQoNJWY22'
---
