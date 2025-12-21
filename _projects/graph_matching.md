---
title: "Graph Matching"
excerpt: " Graph Matching aims to find node correspondence between two graphs, where a node in one graph can be matched with at most one node in the other graph. It has applications in many domains including computer vision and bio-informatics. <img src='/images/gm.pdf'>"
collection: projects
---


## A Theoretical and Empirical Analysis on Applicability of Stable Matching for Partial Graph Matching Learning
This work explores how stable matching algorithms can be applied to partial graph matching within a supervised learning framework. Although classical stable matching methods are computationally efficient, they generally yield optimal outcomes for only one side of a bipartite matching problem.  This work begins by discussing on the optimality of a matching in partial graph matching and show that it is possible to overcome one-sided optimality constraint of stable matching in a learning setting. Building on this insight, we introduce a new partial graph matching framework grounded in stable matching principles and assess its performance on standard benchmark datasets. Our experiments demonstrate that the proposed framework delivers results comparable to state-of-the-art partial graph matching methods while preserving computational efficiency.
- **Paper**: [Solving Partial Graph Matching as a Stable Matching Problem (AI 2025 / AJCAI 2025)](https://link.springer.com/chapter/10.1007/978-981-95-4969-6_35)  
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/SPGM)

## An Optimization Framework for Partial Graph Matching Learning based on Optimal Partial Transport 
Partial graph matching is a more generalized form of the graph matching problem in which both graphs may contain nodes that remain unmatched. This added flexibility makes graph matching applicable to more complex real-world scenarios, but also makes the problem more challenging. A key limitation in existing partial graph matching literature is the absence of an optimization objective that both captures the intrinsic nature of the problem and enables efficient solutions. In this work, we address this limitation by proposing a novel optimization objective for partial graph matching. We further introduce a solver with cubic worst-case time complexity to solve the proposed optimization problem. Finally, we develop a learning framework built upon the proposed formulation. Empirical evaluations on standard partial graph matching benchmarks demonstrate the effectiveness of our approach.

- **Paper**: [Learning Partial Graph Matching via Optimal Partial Transport (ICLR 2025)](https://openreview.net/pdf?id=uDXFOurrHM)
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/OPGMrs)  

## A Contrastive Learning Framework for Supervised Total Graph Matching 
In this work, we propose a novel learning framework for total graph matching based on contrastive learning and stable matching. Specifically, we formulate deep graph matching as a contrastive learning problem by treating matching node pairs as positives and non-matching pairs as negatives. We introduce a contrastive matching loss that exploits the relationships between positive and negative pairs using a hardness attention mechanism. Furthermore, we show how the stable marriage algorithm can be adapted to obtain the final one-to-one assignment between two graphs in a total graph matching setting. Empirical evaluations demonstrate the efficacy of the proposed approach.

- **Paper**: [Contrastive Learning for Supervised Graph Matching (UAI 2023)](https://proceedings.mlr.press/v216/ratnayaka23a.html)
- **GitHub Code**: [Link to Code](https://github.com/Gathika94/StableGM)  

