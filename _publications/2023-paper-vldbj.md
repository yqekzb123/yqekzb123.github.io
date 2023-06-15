---
title: "RCBench: An RDMA-based Framework For Analyzing Concurrency Control Algorithms"
collection: publications
permalink: /publication/2023-paper-vldbj
# excerpt: 'This paper is about the distributed transaction processing in heterogeneous networks that combines the RDMA network and TCP/IP network.'
date: in revision.
venue: 'VLDBJ'
paperurl: 'http://yqekzb123.github.io/files/RCBench.pdf'
citation: ''
---
Distributed transaction processing over the TCP/IP network suffers from the weak transaction scalability problem, i.e., its performance drops significantly
when the number of involved data nodes per transaction increases. Although quite a few of works over the high-performance RDMA-capable network are proposed, they mainly focus on accelerating distributed transaction processing, rather than solving the weak transaction scalability problem. In this paper, we propose RCBench, an RDMA-enabled transaction framework, which serves as a unified evaluation tool for assessing the transaction scalability of various concurrency control algorithms. The usability and advancement
of RCBench primarily come from the proposed concurrency control primitives , which facilitate the convenient implementation of RDMA-enabled concurrency control algorithms. Various optimization principles are proposed to ensure that concurrency control algorithms
in RCBench can fully benefit from the advantages offered by RDMA-capable networks. We conduct extensive experiments to evaluate the scalability of mainstream concurrency control algorithms. The results show that by exploiting the capabilities of RDMA, concurrency control algorithms in RCBench can obtain 42X performance improvement, and transaction scalability can be achieved in RCBench.

[Download paper here](http://yqekzb123.github.io/files/RCBench.pdf)

<!-- Recommended citation: Qian Zhang, Jingyao Li, Hongyao Zhao, Quanqing Xu, Wei Lu, Jinliang Xiao, Fusheng Han, Chuanhui Yang, and Xiaoyong Du. 2023. Efficient Distributed Transaction Processing in Heterogeneous Networks. Proc. VLDB Endow. 16, 6 (February 2023), 1372–1385. https://doi.org/10.14778/3583140.3583153 -->
