---
title: "Continuous Query Processing with Concurrency Control: Reading Updatable Resources Consistently"
date: 2013-01-01
publishDate: 2019-11-24T07:22:01.365725Z
authors: ["Masafumi Oyamada", "Hideyuki Kawashima", "Hiroyuki Kitagawa"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "ACM SAC 2013"
url_pdf: "https://doi.org/10.1145/2480362.2480514"
doi: "10.1145/2480362.2480514"
---

A recent trend in data stream processing shows the use of advanced continuous
queries (CQs) that reference non-streaming resources such as relational data in
databases and machine learning models. Since non-streaming resources could be
shared among multiple systems, resources may be updated by the systems during
the CQ execution. As a consequence, CQs may reference resources inconsistently,
and lead to a wide range of problems from inappropriate results to fatal system
failures. We address this inconsistency problem by introducing the concept of
transaction processing onto data stream processing. We introduce CQ-derived
transaction, a concept that derives read-only transactions from CQs, and
illustrate that the inconsistency problem is solved by ensuring serializability
of derived transactions and resource updating transactions. To ensure
serializability, we propose three CQ-processing strategies based on concurrency
control techniques: two-phase lock strategy, snapshot strategy, and optimistic
strategy. Experimental study shows our CQ-processing strategies guarantee proper
results, and their performances are comparable to the performance of
conventional strategy that could produce improper results.
