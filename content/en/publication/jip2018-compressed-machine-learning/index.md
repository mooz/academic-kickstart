---
title: "Compressed Vector Set: A Fast and Space-Efficient Data Mining Framework"
date: 2018-01-01
publishDate: 2019-11-24T07:22:01.364148Z
authors: ["Masafumi Oyamada", "Jianquan Liu", "Shinji Ito", "Kazuyo Narita", "Takuya Araki", "Hiroyuki Kitagawa"]
publication_types: ["2"]
abstract: ""
featured: false
publication: "Journal of Information Processing (JIP)"
url_pdf: "https://doi.org/10.2197/ipsjjip.26.416"
doi: "10.2197/ipsjjip.26.416"
---

In this paper, we present CVS (Compressed Vector Set), a fast and
space-efficient data mining framework that efficiently handles both sparse and
dense datasets. CVS holds a set of vectors in a compressed format and conducts
primitive vector operations, such as lp-norm and dot product, without
decompression. By combining these primitive operations, CVS accelerates
prominent data mining or machine learning algorithms including k-nearest
neighbor algorithm, stochastic gradient descent algorithm on logistic
regression, and kernel methods. In contrast to the commonly used sparse
matrix/vector representation, which is not effective for dense datasets, CVS
efficiently handles sparse datasets and dense datasets in a unified manner. Our
experimental results demonstrate that CVS can process both dense datasets and
sparse datasets faster than conventional sparse vector representation with
smaller memory usage.
