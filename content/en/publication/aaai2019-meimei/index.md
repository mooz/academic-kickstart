---
title: "Meimei: An Efficient Probabilistic Approach for Semantically Annotating Tables"
date: 2019-01-01
publishDate: 2019-11-24T07:22:01.363610Z
authors: ["Kunihiro Takeoka", "Masafumi Oyamada", "Shinji Nakadai", "Takeshi Okadome"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "AAAI 2019"
url_pdf: "https://aaai.org/ojs/index.php/AAAI/article/view/3796/3674"
doi: "10.1609/aaai.v33i01.3301281"
---

Given a large amount of table data, how can we find the tables that contain the
contents we want? A naive search fails when the column names are ambiguous, such
as if columns containing stock price information are named “Close” in one table
and named “P” in another table.

One way of dealing with this problem that has been gaining attention is the
semantic annotation of table data columns by using canonical knowledge. While
previous studies successfully dealt with this problem for specific types of
table data such as web tables, it still remains for various other types of table
data: (1) most approaches do not handle table data with numerical values, and
(2) their predictive performance is not satisfactory.

This paper presents a novel approach for table data annotation that combines a
latent probabilistic model with multilabel classifiers. It features three
advantages over previous approaches due to using highly predictive multi-label
classifiers in the probabilistic computation of semantic annotation. (1) It is
more versatile due to using multi-label classifiers in the probabilistic model,
which enables various types of data such as numerical values to be supported.
(2) It is more accurate due to the multi-label classifiers and probabilistic
model working together to improve predictive performance. (3) It is more
efficient due to potential functions based on multi-label classifiers reducing
the computational cost for annotation.

Extensive experiments demonstrated the superiority of the proposed approach over
state-of-the-art approaches for semantic annotation of real data (183
human-annotated tables obtained from the UCI Machine Learning Repository).
