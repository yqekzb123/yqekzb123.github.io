---
title: "Efficiently Supporting Multi-Level Serializability in Decentralized Database Systems"
collection: publications
permalink: /publication/2023-paper-vldbj
# excerpt: 'This paper is about the distributed transaction processing in heterogeneous networks that combines the RDMA network and TCP/IP network.'
date: 2023
venue: 'TKDE'
paperurl: 'http://yqekzb123.github.io/files/BDTA.pdf'
citation: 'Z. Zhao et al., "Efficiently Supporting Multi-Level Serializability in Decentralized Database Systems," in IEEE Transactions on Knowledge and Data Engineering, doi: 10.1109/TKDE.2023.3277969.'
---
In decentralized database systems, it is reported that serializability could still produce unexpected transaction orderings, leading to the stale read anomaly. To eliminate this anomaly, strict serializability imposes an additional ordering constraint, called the real-time order, which is required to be preserved among serializable transactions. Yet, preserving the real-time order in strict serializability often causes the performance to drop significantly. Because a weaker data consistency often yields better performance, in this paper, we model serializability from different consistency perspectives to properly leverage the performance and consistency. To do this, we first define a group of orderings, based on which we formulate multi-level serializability by preserving a certain set of ordering constraints among transactions. We then propose a bidirectional timestamp adjustment algorithm (abbreviated as BDTA) to support multi-level serializability with various optimizations. Our special design makes ordering constraints among transactions be preserved simply by adjusting timestamp intervals. Finally, we conduct extensive experiments to show the necessity of introducing multi-level serializability and confirm that BDTA achieves up to 1.19× better performance than the state-of-the-art concurrency control algorithms.



[Download paper here](http://yqekzb123.github.io/files/BDTA.pdf)

Recommended citation: Z. Zhao et al., "Efficiently Supporting Multi-Level Serializability in Decentralized Database Systems," in IEEE Transactions on Knowledge and Data Engineering, doi: 10.1109/TKDE.2023.3277969.
