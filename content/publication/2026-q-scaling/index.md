---
title: "Improving Data-Constrained Scaling with Hyperparameter Transfer and Ensembling"
date: 2026-10-28
publishDate:  2026-10-28
authors: ["**Ethan Baron**, Shmuel Berman, Anirudh Satheesh, Akshay Vegesna, Samip Dahal, Andrew Gordon Wilson"]
publication_types: ["1"]
abstract: "As growing compute budgets outpace the growth of high-quality training data, large language models must be trained with both compute and data constraints in mind. Unfortunately, existing prescriptions for data-constrained scaling suffer from two important limitations. First, past works hold key hyperparameters such as weight decay fixed with scale, despite the fact that optimal hyperparameters vary wildly with model size and number of epochs. Second, past works neglect ensembling, a promising axis for scaling under data constraints. As a surprising consequence, prior prescriptions can lead to loss that increases with compute budget. We address both limitations by fitting power laws that prescribe how to transfer hyperparameters with scale and scaling laws that prescribe how to allocate compute with ensembling. Training on 100M tokens from FineWeb, our recipe reduces validation loss by over 0.15 nats compared to prior recipes, a 14% decrease in perplexity, and achieves monotonic improvements with compute through ensembling. These gains are achieved using prescriptions fit to smaller runs and validated at up to 12× larger compute budgets."

featured: true
weight: 1
publication: "arXiv preprint"

links:
  - icon_pack: ai
    icon: arxiv
    name: 'arXiv'
    alt: "Preprint on arXiv"
    url: 'https://arxiv.org/abs/2610.37842'
  - icon_pack: fab
    icon: github
    name: 'GitHub'
    alt: "Code on GitHub"
    url: 'https://github.com/qlabs-eng/data-constrained-scaling'
---

