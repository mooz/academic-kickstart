---
title: "Relational Mixture of Experts: Explainable Demographics Prediction with Behavioral Data"
date: 2017-11-01
publishDate: 2019-11-24T07:22:01.364782Z
authors: ["Masafumi Oyamada", "Shinji Nakadai"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "ICDM 2017"
url_pdf: "https://doi.org/10.1109/ICDM.2017.45"
doi: "10.1109/ICDM.2017.45"
---

Given a collection of basic customer demographics (e.g., age and gender) and
their behavioral data (e.g., item purchase histories), how can we predict
sensitive demographics (e.g., income and occupation) that not every customer
makes available? This demographics prediction problem is modeled as a
classification task in which a customer's sensitive demographic y is predicted
from his feature vector x.

So far, two lines of work have tried to produce a "good" feature vector x from
the customer's behavioral data: (1) application-specific feature engineering
using behavioral data and (2) representation learning (such as singular value
decomposition or neuralembedding) on behavioral data. Although these approaches
successfully improve the predictive performance, (1) designing a good feature
requires domain experts to make a great effort and (2) features obtained from
representation learning are hard to interpret.

To overcome these problems, we present a Relational Infinite Support Vector
Machine (R-iSVM), a mixture-of-experts model that can leverage behavioral data.
Instead of augmenting the feature vectors of customers, R-iSVM uses behavioral
data to find out behaviorally similar customerclusters and constructs a local
prediction model at each customer cluster. In doing so, R-iSVM successfully
improves the predictive performance withoutrequiring application-specific
feature designing and hard-to-interpret representations.

Experimental results on three real-world datasets demonstrate the predictive
performance and interpretability of R-iSVM. Furthermore, R-iSVM can co-exist
with previous demographics prediction methods to further improve their
predictive performance.
