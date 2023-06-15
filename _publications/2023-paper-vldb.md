---
title: "Efficient Distributed Transaction Processing in Heterogeneous Networks"
collection: publications
permalink: /publication/2023-paper-vldb
# excerpt: 'This paper is about the distributed transaction processing in heterogeneous networks that combines the RDMA network and TCP/IP network.'
date: 2023-04-23
venue: 'VLDB'
paperurl: 'http://yqekzb123.github.io/files/p925-lu.pdf'
citation: 'Qian Zhang, Jingyao Li, Hongyao Zhao, Quanqing Xu, Wei Lu, Jinliang Xiao, Fusheng Han, Chuanhui Yang, and Xiaoyong Du. 2023. Efficient Distributed Transaction Processing in Heterogeneous Networks. Proc. VLDB Endow. 16, 6 (February 2023), 1372–1385. https://doi.org/10.14778/3583140.3583153'
---
Countrywide and worldwide business, like gaming and social networks, drives the popularity of inter-data-center transactions. To support inter-data-center transaction processing and data center fault tolerance simultaneously, existing protocols suffer from significant performance degradation due to high-latency and unstable networks. In this paper, we propose RedT, a novel distributed transaction processing protocol that works in heterogeneous networks. In detail, nodes within a data center are inter-connected via the RDMA-capable network and nodes across data centers are inter-connected via TCP/IP networks. RedT extends two-phase commit (2PC) by decomposing transactions into sub-transactions in terms of the data center granularity, and proposing a pre-write-log mechanism that is able to reduce the number of inter-data-center round-trips from a maximal of 6 to 2. Extensive evaluation against state-of-the-art protocols shows that RedT can achieve up to 1.57× higher throughputs and 0.56× lower latency.



[Download paper here](http://yqekzb123.github.io/files/p925-lu.pdf)

Recommended citation: Qian Zhang, Jingyao Li, Hongyao Zhao, Quanqing Xu, Wei Lu, Jinliang Xiao, Fusheng Han, Chuanhui Yang, and Xiaoyong Du. 2023. Efficient Distributed Transaction Processing in Heterogeneous Networks. Proc. VLDB Endow. 16, 6 (February 2023), 1372–1385. https://doi.org/10.14778/3583140.3583153
