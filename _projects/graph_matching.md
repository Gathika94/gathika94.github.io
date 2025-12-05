---
title: "Graph Matching"
excerpt: "Graph Matching aims to find node correspondence between two graphs, where a node in one graph can be matched with at most one node in the other graph. It has applications in many domains including computer vision and bio-informatics.
collection: projects
---


## A Theoretical and Empirical Analysis on Applicability of Stable Matching for Partial Graph Matching Learning
This work explores how stable matching algorithms can be applied to partial graph matching within a supervised learning framework. Although classical stable matching methods are computationally efficient, they generally yield optimal outcomes for only one side of a bipartite matching problem.  This work begins by discussing on the optimality of a matching in partial graph matching and show that it is possible to overcome one-sided optimality constraint of stable matching in a learning setting. Building on this insight, we introduce a new partial graph matching framework grounded in stable matching principles and assess its performance on standard benchmark datasets. Our experiments demonstrate that the proposed framework delivers results comparable to state-of-the-art partial graph matching methods while preserving computational efficiency. Although the choice of partial matching strategy may depend on specific task requirements, our theoretical and empirical analyses highlight the promise of integrating stable matching paradigms into future partial graph matching methodologies.

- **Paper**: [Solving Partial Graph Matching as a Stable Matching Problem (AI 2025 / AJCAI 2025)](https://link.springer.com/chapter/10.1007/978-981-95-4969-6_35)  
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/SPGM)

## An Optimization Framework for Partial Graph Matching Learning based on Optimal Partial Transport 
Partial graph matching extends traditional graph matching by allowing some nodes to remain unmatched, enabling applications in more complex scenarios. However, this flexibility introduces additional complexity, as both the subset of nodes to match and the optimal mapping must be determined. While recent studies have explored deep learning techniques for partial graph matching, a significant limitation remains: the absence of an optimization objective that fully captures the problem’s intrinsic nature while enabling efficient solutions. In this paper, we propose a novel optimization framework for partial graph matching, inspired by optimal partial transport. Our approach formulates an objective that enables partial assignments while incorporating matching biases, using weighted total variation as the divergence function to guarantee optimal partial assignments. Our method can achieve efficient, exact solutions within cubic worst case time complexity. Our contributions are threefold: (i) we introduce a novel optimization objective that balances matched and unmatched nodes; (ii) we establish a connection between partial graph matching and linear sum assignment problem, enabling efficient solutions; (iii) we propose a deep graph matching architecture with a novel partial matching loss, providing an end-to-end solution. The empirical evaluations on standard graph matching benchmarks demonstrate the efficacy of the proposed approach.

- **Paper**: [Learning Partial Graph Matching via Optimal Partial Transport (ICLR 2025)](https://openreview.net/pdf?id=uDXFOurrHM)
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/OPGMrs)  

## A Contrastive Learning Framework for Supervised Total Graph Matching 
Deep graph matching techniques have shown promising results in recent years. In this work, we cast deep graph matching as a contrastive learning task and introduce a new objective function for contrastive mapping to exploit the relationships between matches and non-matches. To this end, we develop a hardness attention mechanism to select negative samples which captures the relatedness and informativeness of positive and negative samples. Further, we propose a novel deep graph matching framework, Stable Graph Matching (StableGM), which incorporates Sinkhorn ranking into a stable marriage algorithm to efficiently compute one-to-one node correspondences between graphs. We prove that the proposed objective function for contrastive matching is both positive and negative informative, offering theoretical guarantees to achieve dual-optimality in graph matching. We empirically verify the effectiveness of our proposed approach by conducting experiments on standard graph matching benchmarks.

- **Paper**: [Contrastive Learning for Supervised Graph Matching (UAI 2023)](https://proceedings.mlr.press/v216/ratnayaka23a.html)
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/StableGM)  

