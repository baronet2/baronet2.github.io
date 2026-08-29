---
title: "Deep generative models for phylogenetic inference with complex evolutionary processes"
date: 2026-05-25
publishDate:  2025-05-25
authors: ["**Ethan Baron***, Alan Nawzad Amin*, Andrew Gordon Wilson"]
publication_types: ["1"]
abstract: "Phylogenetic inference plays a central role in understanding evolutionary relationships, with applications ranging from tracking pathogen spread to reconstructing the history of life. Conventionally, practitioners obtain posteriors over the phylogenetic tree of species using MCMC methods. However, such likelihood-based methods are only tractable for simple evolutionary models with restrictive assumptions. For more complex and realistic evolutionary models, conventional methods are prohibitively expensive, inaccurate, or even impossible. We instead advocate for a simulation-based inference approach, by using simulated data from an evolutionary model to train a neural network that predicts tree topologies conditioned on sequences. To accurately represent the complex posterior distributions over tree topologies that can arise, we present flexible models that iteratively generate trees using three natural paradigms: top-down, middle-out, and bottom-up. We use a discrete diffusion framework to train these models efficiently on large-scale simulated datasets of phylogenetic trees. For all three generative paradigms, our models fit the data substantially better than the previous state-of-the-art simulation-based method, Phyloformer 2, and obtain more accurate posteriors on real datasets. Finally, our models outperform misspecified conventional methods on data following complex evolutionary processes."

featured: true
publication: "Machine Learning in Computational Biology **(Oral)**"

links:
  - icon_pack: fas
    icon: star
    name: Oral, MLCB
    url: 'https://www.mlcb.org/posters'
  - icon_pack: fas
    icon: star
    name: Spotlight, GenBio @ ICML
    url: 'https://openreview.net/forum?id=C3G6LfaLFE'
  - icon_pack: fas
    icon: book
    name: SPIGM @ ICML
    url: 'https://openreview.net/forum?id=ps2NvoNKo3'
  - icon_pack: fas
    icon: book
    name: GFM @ ICML
    url: 'https://openreview.net/forum?id=6w2TCV7wTn'
---

