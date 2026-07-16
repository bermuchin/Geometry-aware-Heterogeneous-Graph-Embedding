# Awesome Heterogeneous Graph Embedding

A curated collection of papers on heterogeneous graph embedding from the perspective of embedding spaces.

---

## Contents

* Euclidean Space

  * Shallow Embedding
  * Neural Architectures

* Non-Euclidean Space

  * Hyperbolic Space

    * Shallow Embedding
    * Neural Architectures

  * Hyperspherical Space

* Mixed Space

* Applications
    * General Applications
    * Domain-Specific Applications
* Datasets

* Benchmarks

---

# Euclidean Space

## Shallow Embedding

1. **metapath2vec: Scalable representation learning for heterogeneous networks**. - Dong et al.
   <br>Proceedings of the 23rd ACM SIGKDD international conference on knowledge discovery and data mining, 2017
   [[Paper]](https://dl.acm.org/doi/10.1145/3097983.3098036) [[Code]](https://ericdongyx.github.io/metapath2vec/m2v.html)

2. **HIN2Vec: Explore Meta-paths in Heterogeneous Information Networks for Representation Learning**. - Fu et al.
   <br>Proceedings of the 2017 ACM on Conference on Information and Knowledge Management, 2017
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3132847.3132953)

3. **Heterogeneous Information Network Embedding for Recommendation**. - Shi et al.
   <br>IEEE transactions on knowledge and data engineering, 2018
   [[Paper]](https://ieeexplore.ieee.org/abstract/document/8355676) [[Code]](https://github.com/librahu/HERec)

4. **Are meta-paths necessary? revisiting heterogeneous graph embeddings**. - Hussein et al.
   <br>Proceedings of the 27th ACM International Conference on Information and Knowledge Management, 2018
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3269206.3271777) [[Code]](https://github.com/eXascaleInfolab/JUST)

---

## Neural Architectures

## Neural Architectures

1. **Heterogeneous graph attention network**. - Wang et al.
   <br>Proceedings of The Web Conference, 2019
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3308558.3313562) [[Code]](https://github.com/Jhy1993/HAN)

2. **Magnn: Metapath aggregated graph neural network for heterogeneous graph embedding**. - Fu et al.
   <br>Proceedings of The Web Conference, 2020
   [[Paper]](https://arxiv.org/abs/2002.01680) [[Code]](https://github.com/cynricfu/MAGNN)

3. **Graph transformer networks**. - Yun et al.
   <br>Advances in Neural Information Processing Systems, 2019
   [[Paper]](https://arxiv.org/abs/1911.06455) [[Code]](https://github.com/seongjunyun/Graph_Transformer_Networks)

4. **Heterogeneous graph transformer**. - Hu et al.
   <br>Proceedings of The Web Conference, 2020
   [[Paper]](https://arxiv.org/abs/2003.01332) [[Code]](https://github.com/acbull/HGT-DGL)

5. **An attention-based graph neural network for heterogeneous structural learning**. - Hong et al.
   <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2020
   [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/5833) [[Code]](https://github.com/ZacharyChenpk/HetSANN)

6. **Migtnet: metapath instance-based graph transformation network for heterogeneous graph embedding**. - Park et al.
   <br>Future Generation Computer Systems, 2023
   [[Paper]](https://www.sciencedirect.com/science/article/pii/S0167739X23002960)

7. **Heterogeneous graph neural network**. - Zhang et al.
   <br>Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2019
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3330961) [[Code]](https://github.com/chuxuzhang/KDD2019_HetGNN)

8. **Heterogeneous graph structure learning for graph neural networks**. - Zhao et al.
   <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2021
   [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/16600) [[Code]](https://github.com/AndyJZhao/HGSL)

9. **Hgk-gnn: Heterogeneous graph kernel based graph neural networks**. - Long et al.
   <br>Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2021
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3447548.3467429)

10. **Relation structure-aware heterogeneous graph neural network**. - Zhu et al.
    <br>Proceedings of the IEEE International Conference on Data Mining, 2019
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/8970828)

11. **Hagnn: Hybrid aggregation for heterogeneous graph neural networks**. - Zhu et al.
    <br>IEEE Transactions on Neural Networks and Learning Systems, 2024
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/10816727) [[Code]](https://github.com/PasaLab/HAGNN)

12. **Megnn: Meta-path extracted graph neural network for heterogeneous graph representation learning**. - Chang et al.
    <br>Knowledge-Based Systems, 2022
    [[Paper]](https://www.sciencedirect.com/science/article/pii/S095070512100873X) [[Code]](https://github.com/EricWang-CS/MEGNN)

13. **Self-supervised heterogeneous graph neural network with co-contrastive learning**. - Wang et al.
    <br>Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2021
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3447548.3467415) [[Code]](https://github.com/liun-online/HeCo)

14. **Simple and efficient heterogeneous graph neural network**. - Yang et al.
    <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2023
    [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26283) [[Code]](https://github.com/ICT-GIMLab/SeHGNN)
    
15. **Heterogeneous graph propagation network**. - Ji et al.
    <br>IEEE Transactions on Knowledge and Data Engineering, 2023
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/9428609) [[Code]](https://github.com/Jhy1993/HPN)

16. **muxgnn: Multiplex graph neural network for heterogeneous graphs**. - Melton et al.
    <br>IEEE Transactions on Pattern Analysis and Machine Intelligence, 2023
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/10086644) [[Code]](https://github.com/steveazzolin/muxGNN)

17. **Diffmg: Differentiable meta graph search for heterogeneous graph neural networks**. - Ding et al.
    <br>Proceedings of the ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2021
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3447548.3467447) [[Code]](https://github.com/LARS-research/DiffMG)

18. **Adaptive heterogeneous graph neural networks: Bridging heterophily and heterogeneity**. - Chen et al.
    <br>Proceedings of the ACM International Conference on Information and Knowledge Management, 2025
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3746252.3761131)

19. **Hgen: heterogeneous graph ensemble networks**. - Shen et al.
    <br>Proceedings of the International Joint Conference on Artificial Intelligence, 2025
    [[Paper]](https://arxiv.org/abs/2509.09843)
---

# Non-Euclidean Space

## Hyperbolic Space

### Shallow Embedding

1. **HHNE/ HHNE++: Hyperbolic Heterogeneous Information Network Embedding**. - Wang et al.
   <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2022
   [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/20386) [[Code]](https://github.com/ydzhang-stormstout/HHNE)

### Neural Architectures

1. **Hyperbolic Heterogeneous Graph Attention Networks** - Park et al.
   <br>Companion Proceedings of the Web Conference, 2024
   [[Paper]](https://doi.org/10.1145/3589335.3651522)

2. **McH-HGCN: Multi-curvature Hyperbolic Heterogeneous Graph Convolutional Network with Type Triplets** - Liu et al.
   <br>Neural Computing and Applications, 2023
   [[Paper]](https://doi.org/10.1007/s00521-023-08473-5)

3. **Multi-Order Relations Hyperbolic Fusion for Heterogeneous Graphs** - Li et al.
   <br>Proceedings of the 32nd ACM International Conference on Information and Knowledge Management, 2023
   [[Paper]](https://doi.org/10.1145/3583780.3614979)

4. **Multi-Hyperbolic Space-based Heterogeneous Graph Attention Network** - Park et al.
   <br>2024 IEEE International Conference on Data Mining, 2024
   [[Paper]](https://doi.org/10.1109/ICDM59182.2024.00098)

5. **HGCH: A Hyperbolic Graph Convolution Network Model for Heterogeneous Collaborative Graph Recommendation** - Zhang et al.
   <br>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management, 2024
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3627673.3679701)

6. **Metapath-based Hyperbolic Contrastive Learning for Heterogeneous Graph Embedding** - Park et al.
   <br>arXiv, 2025
   [[Paper]](https://arxiv.org/abs/2506.16754)

7. **Hyperbolic Heterogeneous Graph Transformer** - Park et al.
   <br>arXiv, 2026
   [[Paper]](https://arxiv.org/abs/2601.08251)

---

## Hyperspherical Space

1. **Spherical Graph Embedding for Item Retrieval in Recommendation System** - Zhu et al.
   <br>Proceedings of the 31st ACM International Conference on Information and Knowledge Management, 2022
   [[Paper]](https://dl.acm.org/doi/10.1145/3511808.3557704)

2. **Anomaly Detection in Dynamic Networks Using Multi-View Time-Series Hypersphere Learning** - Teng et al.
   <br>Proceedings of the 26th ACM International Conference on Information and Knowledge Management, 2017
   [[Paper]](https://dl.acm.org/doi/10.1145/3132847.3132964)

3. **Anomaly Detection with Dual-Channel Heterogeneous Graph Based on Hypersphere Learning** - Li et al.
   <br>Information Sciences, 2024
   [[Paper]](https://www.sciencedirect.com/science/article/pii/S0020025524011563)

---

# Mixed Space

# Mixed Space

1. **Improving Heterogeneous Graph Learning with Weighted Mixed-Curvature Product Manifold** - Nguyen-Van et al.
   <br>arXiv, 2023
   [[Paper]](https://arxiv.org/abs/2307.04514)

2. **Mixed-Curvature Multi-Relational Graph Neural Network for Knowledge Graph Completion** - Wang et al.
   <br>Proceedings of the Web Conference, 2021
   [[Paper]](https://dl.acm.org/doi/abs/10.1145/3442381.3450118)

3. **Mixed-Curvature Multi-Modal Knowledge Graph Completion** - Gao et al.
   <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2025
   [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/33273)

4. **Mixed-Curvature Knowledge-Enhanced Graph Contrastive Learning for Recommendation** - Zhang et al.
   <br>Expert Systems with Applications, 2024
   [[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417423020717)

5. **HGE: Embedding Temporal Knowledge Graphs in a Product Space of Heterogeneous Geometric Subspaces** - Pan et al.
   <br>Proceedings of the AAAI Conference on Artificial Intelligence, 2024
   [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28739)

---

# Applications

## General Applications

### Recommendation Systems

1. **Heterogeneous Information Network Embedding for Recommendation**. - Shi et al.
    <br>IEEE transactions on knowledge and data engineering, 2018
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/8355676) [[Code]](https://github.com/librahu/HERec)

2. **HeteroGraphRec: A Heterogeneous Graph-Based Neural Network for Social Recommendations** - Salamat et al.
    <br>Knowledge-Based Systems, 2021
    [[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705121000800)

3. **A Heterogeneous Graph Neural Model for Cold-Start Recommendation** - Liu et al.
    <br>Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval, 2020
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3397271.3401252)

4. **Graph Learning Augmented Heterogeneous Graph Neural Network for Social Recommendation** - Zhang et al.
    <br>ACM Transactions on Recommender Systems, 2023
    [[Paper]](https://dl.acm.org/doi/full/10.1145/3610407)

5. **Adversarial Heterogeneous Graph Neural Network for Robust Recommendation** - Sang et al.
    <br>IEEE Transactions on Computational Social Systems, 2023
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/10124876)

6. **Heterogeneous Global Graph Neural Networks for Personalized Session-Based Recommendation** - Pang et al.
    <br>Proceedings of the Fifteenth ACM International Conference on Web Search and Data Mining, 2022
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3488560.3498505)

7. **Metapath-Guided Heterogeneous Graph Neural Network for Intent Recommendation** - Fan et al.
    <br>Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, 2019
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3330673)

8. **Heterogeneous Graph Contrastive Learning for Recommendation** - Chen et al.
    <br>Proceedings of the Sixteenth ACM International Conference on Web Search and Data Mining, 2023
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3539597.3570484)

9. **Heterogeneous Hypergraph Neural Network for Social Recommendation Using Attention Network** - Khan et al.
    <br>ACM Transactions on Recommender Systems, 2025
    [[Paper]](https://dl.acm.org/doi/full/10.1145/3613964)

10. **Mixed-Curvature Knowledge-Enhanced Graph Contrastive Learning for Recommendation** - Zhang et al.
    <br>Expert Systems with Applications, 2024
    [[Paper]](https://www.sciencedirect.com/science/article/pii/S0957417423020717) 

11. **HGCH: A Hyperbolic Graph Convolution Network Model for Heterogeneous Collaborative Graph Recommendation** - Zhang et al.
    <br>Proceedings of the 33rd ACM International Conference on Information and Knowledge Management, 2024
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3627673.3679701)

12. **Poincaré Heterogeneous Graph Neural Networks for Sequential Recommendation** - Guo et al.
    <br>ACM Transactions on Information Systems, 2023
    [[Paper]](https://dl.acm.org/doi/full/10.1145/3568395)
    
13. **Hyperbolic Graph Learning for Social Recommendation** - Yang et al.
    <br>IEEE Transactions on Knowledge and Data Engineering, 2024
    [[Paper]](https://ieeexplore.ieee.org/abstract/document/10361607)

14. **Knowledge Based Hyperbolic Propagation** - Tai et al.
    <br>Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval, 2021
    [[Paper]](https://dl.acm.org/doi/abs/10.1145/3404835.3462980)

15. **Spherical Graph Embedding for Item Retrieval in Recommendation System** - Zhu et al.
    <br>Proceedings of the 31st ACM International Conference on Information and Knowledge Management, 2022
    [[Paper]](https://dl.acm.org/doi/10.1145/3511808.3557704)

### NLP

1. **HeterSumGraph: Heterogeneous Graph Neural Network for Extractive Summarization**.
   [[Paper]]() [[Code]]()

2. **HGN: Hierarchical Graph Network for Multi-hop Question Answering**.
   [[Paper]]() [[Code]]()

3. **HGNNR4FD: Heterogeneous Graph Neural Network based Rumor Detection / Fake News Detection**.
   [[Paper]]() [[Code]]()

4. **QA-GNN: Reasoning with Language Models and Knowledge Graphs for Question Answering**.
   [[Paper]]() [[Code]]()

5. **GreaseLM: Graph Reasoning Enhanced Language Models for Question Answering**.
   [[Paper]]() [[Code]]()

6. **KG-FiD: Knowledge Graph Augmented Fusion-in-Decoder**.
   [[Paper]]() [[Code]]()

### Anomaly Detection

1. **MTHL: Multi-Task Hyperbolic Learning for Heterogeneous Graphs**.
   [[Paper]]() [[Code]]()

2. **HGNF: Heterogeneous Graph Neural Framework for Bioinformatics**.
   [[Paper]]() [[Code]]()

3. **HRGCN: Heterogeneous Relational Graph Convolutional Network**.
   [[Paper]]() [[Code]]()

4. **MulDualGNN: Multi-space Dual Graph Neural Network**.
   [[Paper]]() [[Code]]()

### Computer Vision

1. **HyHE: Hyperbolic Heterogeneous Graph Embedding**.
   [[Paper]]() [[Code]]()

2. **HypStructure: Hyperbolic Structure Learning for Heterogeneous Graphs**.
   [[Paper]]() [[Code]]()

3. **PHGC: Personalized Hyperbolic Graph Convolution**.
   [[Paper]]() [[Code]]()

4. **FedBiGNNs: Federated Bipartite Graph Neural Networks**.
   [[Paper]]() [[Code]]()

## Domain-Specific Applications

### Knowledge Graphs

1. **MuRP: Multi-Relational Poincaré Graph Embeddings**.
   [[Paper]]() [[Code]]()

2. **AttH: Hyperbolic Representation Learning with Hyperbolic Attention**.
   [[Paper]]() [[Code]]()

3. **DyERNIE: Dynamic Evolutionary Representation Learning for Temporal Knowledge Graphs**.
   [[Paper]]() [[Code]]()

4. **IME: Inductive Manifold Embedding for Knowledge Graph Completion**.
   [[Paper]]() [[Code]]()

5. **MCKGC: Multi-Curvature Knowledge Graph Completion**.
   [[Paper]]() [[Code]]()

6. **M2GNN: Multi-Manifold Graph Neural Network for Knowledge Graph Completion**.
   [[Paper]]() [[Code]]()

7. **R-GCN: Modeling Relational Data with Graph Convolutional Networks**.
   [[Paper]]() [[Code]]()

8. **SACN: Structure-Aware Convolutional Networks for Knowledge Base Completion**.
   [[Paper]]() [[Code]]()

9. **KBGAT: Knowledge Base Graph Attention Network**.
   [[Paper]]() [[Code]]()

10. **CompGCN: Composition-based Multi-Relational Graph Convolutional Networks**.
    [[Paper]]() [[Code]]()

11. **StarE: Message Passing for Hyper-Relational Knowledge Graphs**.
    [[Paper]]() [[Code]]()

12. **GraIL: Graph Neural Network based Inductive Learning for Knowledge Graphs**.
    [[Paper]]() [[Code]]()

13. **NBFNet: Neural Bellman-Ford Networks**.
    [[Paper]]() [[Code]]()

14. **RED-GNN: Relational Dependency Graph Neural Network**.
    [[Paper]]() [[Code]]()

### Urban Infrastructure

1. **Traffic: End-to-End Heterogeneous Graph Neural Network for Traffic Prediction**.
   [[Paper]]() [[Code]]()

2. **Land Use: Heterogeneous Graph Networks with Post-hoc Explanations for Urban Land Use Analysis**.
   [[Paper]]() [[Code]]()

3. **Water: Heterogeneous Graph Neural Networks for Water Distribution Network Pressure Estimation**.
   [[Paper]]() [[Code]]()

### Biomedical

1. **FLONE: Federated Learning on Network Embeddings for Biomedical Applications**.
   [[Paper]]() [[Code]]()

2. **Decagon: Modeling Polypharmacy Side Effects with Graph Convolutional Networks**.
   [[Paper]]() [[Code]]()

3. **HGAN: Heterogeneous Graph Attention Network for Biomedical Networks**.
   [[Paper]]() [[Code]]()

4. **MHGNN: Multi-Modal / Multi-View Heterogeneous Graph Neural Network for Biomedical Applications**.
   [[Paper]]() [[Code]]()

5. **Heterogeneous Graph Neural Networks for Biomedical Networks**.
   [[Paper]]() [[Code]]()

### Social Networks Analysis

1. **HSED: Heterogeneous Structure Enhanced Detection for Social Networks**.
   [[Paper]]() [[Code]]()

2. **CP-GNN: Community Preserving Graph Neural Network**.
   [[Paper]]() [[Code]]()

3. **H3GNN: Heterogeneous Hierarchical Hypergraph Neural Network**.
   [[Paper]]() [[Code]]()

---

# Datasets

## Academic Networks

* ACM
* DBLP
* IMDB

## Recommendation

* Yelp
* Amazon

---

# Benchmarks

(To be updated)
