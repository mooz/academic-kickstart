---
title: "Link Prediction for Isolated Nodes in Heterogeneous Network by Topic-Based Co-clustering"
date: 2017-01-01
publishDate: 2019-11-24T07:22:01.365086Z
authors: ["Katsufumi Tomobe", "Masafumi Oyamada", "Shinji Nakadai"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "PAKDD 2017"
url_pdf: "https://doi.org/10.1007/978-3-319-57454-7_12"
doi: "10.1007/978-3-319-57454-7_12"
---

This paper presents a new probabilistic generative model (PGM) that predicts
links for isolated nodes in a heterogeneous network using textual data. In
conventional PGMs, a link between two nodes is predicted on the basis of the
nodes’ other existing links. This method makes it difficult to predict links for
isolated nodes, which happens when new items are recommended. In this study, we
first naturally expand the relational topic model (RTM) to a heterogeneous
network (Hetero-RTM). However, this simple extension degrades performance in a
link prediction for existing nodes. We present a new model called the Grouped
Hetero-RTM that has both latent topics and latent clusterings. Through intensive
experiments that simulate real recommendation problems, the Grouped Hetero-RTM
outperforms baseline methods at predicting links for isolated nodes. This model,
furthermore, performs as effectively as the stochastic block model in the link
prediction for existing nodes. We also find that the Grouped Hetero-RTM is
effective for various textual data such as item reviews and movie descriptions.
