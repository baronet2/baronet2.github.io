---
title: "Multi-aspect reviewed-item retrieval"
date: 2024-05-01
publishDate:  2024-05-01
authors: ["**Ethan Baron**"]
publication_types: ["7"]
abstract: "In this thesis, we explore three extensions to the standard information retrieval setting.

Firstly, in some domains, it is common for users to seek items satisfying multiple independent aspects, expressed through multi-aspect queries. Classical information retrieval algorithms tend to perform poorly on such multi-aspect queries. Previously-proposed methods that explicitly account for multi-aspect structure offer only small improvements in performance over classical methods. We derive a principled algorithm based on a graphical model for multi-aspect retrieval and validate empirically that this algorithm improves performance on multi-aspect queries over classical approaches. Our algorithm offers performance competitive with large language model prompting at a more reasonable computational cost.

Secondly, in many domains, information retrieval systems must leverage vast quantities of user-generated item reviews by effectively combining information about items from multiple user reviews. Past works propose two main branches of algorithms for this reviewed-item retrieval setting, but do not provide theoretical foundations for these algorithms. We formalize reviewed-item retrieval using a graphical model and draw connections between our model and previously-proposed methods, highlighting directions for future research motivated by these theoretical foundations.

Thirdly, we introduce multi-aspect reviewed-item retrieval, which combines the two previous extensions. We show intuitively and formally that multi-aspect queries pose a failure mode for state-of-the-art reviewed-item retrieval methods. We propose a novel reviewed-item retrieval algorithm to address this failure mode, and validate empirically that it achieves improved performance on multi-aspect queries. We also investigate the impact of various design choices for this algorithm."
featured: true
publication: "BASc Thesis, University of Toronto (supervised by Scott Sanner)"
links:
  - icon_pack: fa
    icon: file-pdf
    name: PDF
    url: 'https://github.com/baronet2/MARIR/blob/main/Multi-aspect%20Reviewed-item%20Retrieval.pdf'
  - icon_pack: fab
    icon: github
    name: GitHub
    url: 'https://github.com/baronet2/marir'
---
