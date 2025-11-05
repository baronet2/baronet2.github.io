---
title: "Efficiently generating correlated sample paths from multi-step time series foundation models"
date: 2025-10-07
publishDate:  2025-10-02
authors: ["**Ethan Baron**, Boris Oreshkin, Ruijun Ma, Hanyu Zhang, Kari Torkkola, Michael W. Mahoney, Andrew Gordon Wilson, Tatiana Konstantinova"]
publication_types: ["1"]
abstract: "Many time series applications require access to multi-step forecast trajectories in the form of sample paths. Recently, time series foundation models have leveraged multi-step lookahead predictions to improve the quality and efficiency of multi-step forecasts. However, these models only predict independent marginal distributions for each time step, rather than a full joint predictive distribution. To generate forecast sample paths with realistic correlation structures, one typically resorts to autoregressive sampling, which can be extremely expensive. In this paper, we present a copula-based approach to efficiently generate accurate, correlated sample paths from existing multi-step time series foundation models in one forward pass. Our copula-based approach generates correlated sample paths orders of magnitude faster than autoregressive sampling, and it yields improved sample path quality by mitigating the snowballing error phenomenon."

featured: true
publication: "NeurIPS Workshop on Recent Advances in Time Series Foundation Models **(Oral)**"
links:
  - icon_pack: fas
    icon: star
    name: Oral, BERT<sup>2</sup>S @ NeurIPS
    url: 'https://berts-workshop.github.io/accepted-papers/'
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: 'https://arxiv.org/abs/2510.02224'
---

