---
title: "Miss It Like Messi: Extracting Value from Off-Target Shots in Soccer"
date: 2024-01-01
publishDate:  2024-01-01
authors: ["**Ethan Baron**", "Nathan Sandholtz", "Devin Pleuler", "Timothy C. Y. Chan"]
publication_types: ["2"]
abstract: "Measuring soccer shooting skill is a challenging analytics problem due to the scarcity and highly contextual nature of scoring events. The introduction of more advanced data surrounding soccer shots has given rise to model-based metrics which better cope with these challenges. Specifically, metrics such as expected goals added, goals above expectation, and post-shot expected goals all use advanced data to offer an improvement over the classical conversion rate. However, all metrics developed to date assign a value of zero to off-target shots, which account for almost two-thirds of all shots, since these shots have no probability of scoring. We posit that there is non-negligible shooting skill signal contained in the trajectories of off-target shots and propose two shooting skill metrics that incorporate the signal contained in off-target shots. Specifically, we develop a player-specific generative model for shot trajectories based on a mixture of truncated bivariate Gaussian distributions. We use this generative model to compute metrics that allow us to attach non-zero value to off-target shots. We demonstrate that our proposed metrics are more stable than current state-of-the-art metrics and have increased predictive power."
featured: true
publication: "Journal of Quantitative Analysis in Sports (JQAS). Ahead of print"
links:
  - icon_pack: fas
    icon: book
    name: JQAS
    url: 'https://doi.org/10.1515/jqas-2022-0107'
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: 'https://arxiv.org/abs/2308.01523'
  - icon_pack: fab
    icon: github
    name: GitHub
    url: 'https://github.com/baronet2/shotmissr'
---
