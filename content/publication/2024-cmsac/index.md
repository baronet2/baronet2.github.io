---
title: "Boulder2Vec: Modeling Climber Performances in Professional Bouldering Competitions"
date: 2024-11-02
publishDate:  2024-10-06
authors: ["**Ethan Baron**, Victor Hau, Zeke Weng"]
publication_types: ["1"]
abstract: "Using data from professional bouldering competitions from 2008 to 2022, we train a logistic regression to predict climber results and measure climber skill. However, this approach is limited, as a single numeric coefficient per climber cannot adequately capture the intricacies of climbers’ varying strengths and weaknesses in different boulder problems. For example, some climbers might prefer more static, technical routes while other climbers may specialize in powerful, dynamic problems.

To this end, we apply Probabilistic Matrix Factorization (PMF), a framework commonly used in recommender systems, to represent the unique characteristics of climbers and problems with latent, multi-dimensional vectors. In this framework, a climber’s performance on a given problem is predicted by taking the dot product of the corresponding climber vector and problem vectors. PMF effectively handles sparse datasets, such as our dataset where only a subset of climbers attempt each particular problem, by extrapolating patterns from similar climbers.

We contrast the empirical performance of PMF to the logistic regression approach and investigate the multivariate representations produced by PMF to gain insights into climber characteristics. Our results show that the multivariate PMF representations improve predictive performance of professional bouldering competitions by capturing both the overall strength of climbers and their specialized skill sets."
featured: true
publication: "Carnegie Mellon Sports Analytics Conference (CMSAC)"
links:
  - icon_pack: fas
    icon: trophy
    name: Winner, Reproducible Research Competition
    url: 'https://www.stat.cmu.edu/cmsac/conference/2024/'
  - icon_pack: fas
    icon: book
    name: CMSAC
    url: 'https://www.stat.cmu.edu/cmsac/conference/2024/#mu-research'
  - icon_pack: fa
    icon: file-pdf
    name: PDF
    url: 'https://www.stat.cmu.edu/cmsac/conference/2024/assets/pdf/Weng24.pdf'
  - icon_pack: fab
    icon: github
    name: GitHub
    url: 'https://github.com/baronet2/boulder2vec'
---
