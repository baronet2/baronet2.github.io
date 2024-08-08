---
title: "Multi-aspect reviewed-item retrieval via LLM query decomposition and aspect fusion"
date: 2024-07-18
publishDate:  2024-07-18
authors: ["Anton Korikov, George Saad, **Ethan Baron**, Mustafa Khan, Manav Shah and Scott Sanner"]
publication_types: ["2"]
abstract: "While user-generated product reviews contain a large amount of information, their utility in addressing natural language product queries has been limited due to the challenges of aggregating information from multiple low-level sources (reviews) to a higher item level during retrieval. Existing methods for reviewed-item retrieval (RIR), recently implemented by retrieval augmented generation (RAG) driven conversational recommendation systems, typically leverage late fusion (LF) – which computes query-item scores by simply averaging the top-K query-review similarity scores for an item. However, we demonstrate that for multi-aspect queries and multi-aspect items, LF is highly sensitive to the distribution of aspects covered by reviews in terms of aspect frequency and the degree of aspect separation across reviews. To address these LF failures, we propose several novel neural aspect fusion (AF) strategies which include LLM query extraction and generative reranking. Our experiments show that for imbalanced review corpora, AF can improve over LF by a 44% MAP increase from 0.36 ± 0.04 to 0.52 ± 0.04, while achieving equivalent performance for balanced review corpora."
featured: true
publication: "Information Retrieval's Role in RAG Systems @ SIGIR 2024"
links:
  - icon_pack: fas
    icon: book
    name: SIGIR
    url: 'https://coda.io/@rstless-group/ir-rag-sigir24#_luMZD'
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: 'https://arxiv.org/abs/2408.00878'
---
