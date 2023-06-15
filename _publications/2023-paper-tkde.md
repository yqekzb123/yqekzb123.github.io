---
title: "T-SQL: A Lightweight Implementation to Enable Built-in Temporal Support in RDBMSs"
collection: publications
permalink: /publication/2023-paper-tkde
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023
venue: 'TKDE'
paperurl: 'http://yqekzb123.github.io/files/2021_tkde.pdf'
citation: 'Z. Zhao et al., "T-SQL: A Lightweight Implementation to Enable Built-in Temporal Support in MVCC-Based RDBMSs," in IEEE Transactions on Knowledge and Data Engineering, vol. 35, no. 1, pp. 1028-1042, 1 Jan. 2023, doi: 10.1109/TKDE.2021.3081717.'
---
The adoption of temporal expressions into SQL:2011 has continuously driven the extensions of temporal support in relational database systems (a.b.a. RDBMSs). In this paper, we present T-SQL , a lightweight yet efficient built-in temporal implementation in RDBMSs. T-SQL entirely relies on multi-version concurrency control (MVCC), widely adopted in RDMBSs, to manage temporal data . For temporal data, current records are maintained in legacy databases, and historical records , i.e., previous versions of current records (if any), which used to be periodically reclaimed are separately maintained in KV stores. To enable temporal query processing under SQL:2011, we extend the query engine in legacy RDBMSs to support query processing over either current records or historical records or both. Further, regarding temporal data are ever-increasing, we propose various optimizations to reduce the storage overhead of KV stores while keeping efficient query performance. We elaborate a publicly available implementation on how to integrate T-SQL into both centralized and distributed RDBMSs. We conduct extensive experiments on both YCSB and TPC-series benchmarks by comparing T-SQL with other temporal database systems. The results show that T-SQL is both lightweight and efficient.

[Download paper here](http://yqekzb123.github.io/files/2021_tkde.pdf)

Recommended citation: Z. Zhao et al., "T-SQL: A Lightweight Implementation to Enable Built-in Temporal Support in MVCC-Based RDBMSs," in IEEE Transactions on Knowledge and Data Engineering, vol. 35, no. 1, pp. 1028-1042, 1 Jan. 2023, doi: 10.1109/TKDE.2021.3081717.
