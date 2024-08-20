---
title: "ClientShield: Malicious Clients Avoidance in Federated Learning with the Help of an Ant"
collection: publications
category: manuscripts
permalink: /publication/clientshield
excerpt: 'Malicious Client detection system inspired by Ant System'
date: 2024-08-01
venue: 'GECCO conference (poster)'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://dl.acm.org/doi/10.1145/3638530.3654435'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Abstract: Federated learning (FL) has garnered significant attention for its potential to enable collaborative model training across decentralized devices while preserving data privacy. However, the presence of some malicious clients, who deliberately add random noise to their local weights, seriously hampers the overall training process. We address this challenge by introducing a specialized client selection problem and proposing the ClientShield algorithm, which subsamples a fraction of honest clients based on the pheromone profile maintained by the Ant System. It employs a reinforcement phase to reward clients demonstrating improved accuracy while penalizing malevolent clients selectively. Our approach significantly outperforms random client selection methods, achieving approximately 60% accuracy in the presence of 10% malicious clients, compared to a mere 10% accuracy with random selection. This research contributes to the advancement of FL, enhancing its applicability and security in real-world scenarios.