# vector-database
A collection of vector database topics. Refer to this notion [link](https://scratched-quarter-776.notion.site/1508376d3abf80eb8650d7164a7e4841?v=eaed6e6412ab4b3780f14de000568a24).

##  Quantization
  - Product Quantization for Nearest Neighbor Search (IEEE Transactions on Pattern Analysis and Machine Intelligence'11) [[pdf](https://ieeexplore.ieee.org/document/5432202)]
  - Optimized product quantization (IEEE Transactions on Pattern Analysis and Machine Intelligence'13) [[pdf](https://www.microsoft.com/en-us/research/wp-content/uploads/2013/11/pami13opq.pdf)]
  - RaBitQ: Quantizing High-Dimensional Vectors with a Theoretical Error Bound for Approximate Nearest Neighbor Search (SIGMOD'24)  [[pdf](https://arxiv.org/pdf/2405.12497)]

## Index
### Graph
  - (HNSW) Efficient and robust approximate nearest neighbor search using Hierarchical Navigable Small World graphs (IEEE transactions on pattern analysis and machine intelligence'18) [[pdf](https://arxiv.org/pdf/1603.09320)]
  - (NSG) Fast Approximate Nearest Neighbor Search With The Navigating Spreading-out Graph[[pdf](https://www.vldb.org/pvldb/vol12/p461-fu.pdf)]
  - (𝜏-MNG) Efficient Approximate Nearest Neighbor Search in Multi-dimensional Databases (SIGMOD’23) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3588908)]
  - Revisiting the Index Construction of Proximity Graph-Based Approximate Nearest Neighbor Search (Arxiv'24) [[pdf](https://arxiv.org/pdf/2410.01231)]

### Tree
- Cover Trees for Nearest Neighbor (ICML’06) [[pdf](https://dl.acm.org/doi/pdf/10.1145/1143844.1143857)]

### Cluster

### Locality-Sensitive Hash

### Etc
- GleanVec: Accelerating vector search with minimalist nonlinear dimensionality reduction (Arxiv'24) [[pdf](https://arxiv.org/pdf/2410.22347)]

### Billion-Scale
  - DiskANN: Fast Accurate Billion-point Nearest Neighbor Search on a Single Node (NeurIPS’19) [[pdf]( https://papers.nips.cc/paper_files/paper/2019/hash/09853c7fb1d3f8ee67a61b6bf4a7f8e6-Abstract.html)]
  - SPANN: Highly-efficient Billion-scale Approximate Nearest Neighbor Search (NeurIPS’21) [[pdf](https://arxiv.org/pdf/2111.08566)]
  - Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment (SIGMOD’24) [[pdf](https://arxiv.org/pdf/2401.02116)]

## Advanced Query Processing
### Hybrid query
  - Filtered − DiskANN: Graph Algorithms for Approximate Nearest
Neighbor Search with Filters (WWW'23) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3543507.3583552)]
  - ACORN: Performant and Predicate-Agnostic Search Over Vector Embeddings and Structured Data (SIGMOD’24) [[pdf](https://dl.acm.org/doi/abs/10.1145/3654923?casa_token=zv7AdTpdLrEAAAAA:ZZ6DEAjfqA-2vUtTPTzWrXXlW-N3yUgVXWKekeyOuIwxMwDfQgWPfTKyhjKQI5rGxzV4Ptq-qig3vg)]
### Multi-vector query
  - DESSERT: An Efficient Algorithm for Vector Set Search with Vector Set Queries (NeurIPS’23) [[pdf](https://proceedings.neurips.cc/paper_files/paper/2023/hash/d6cc45de2e2dea14b96c1eba88fd8ef7-Abstract-Conference.html)]
  - MUVERA: Multi-Vector Retrieval via Fixed Dimensional Encodings (Arxiv’24) [[pdf](https://arxiv.org/pdf/2405.19504)]
  - Approximate Vector Set Search: A Bio-Inspired Approach for High-Dimensional Spaces (Arxiv’24) [[pdf](https://arxiv.org/pdf/2412.03301)]
### Out-of-distribution query
  - RoarGraph: A Projected Bipartite Graph for Efficient Cross-Modal Approximate Nearest Neighbor Search (VLDB’24) [[pdf](https://kay21s.github.io/RoarGraph-VLDB2024.pdf)]
  - OOD-DiskANN: Efficient and Scalable Graph ANNS for
Out-of-Distribution Queries (Arxiv'24) [[pdf](https://arxiv.org/pdf/2211.12850)]
### Cross-modal query
  - Test-time Adaptation for Cross-modal Retrieval with Query Shift (Arxiv'24) [[pdf](https://openreview.net/forum?id=BmG88rONaU)]

## Library
  - VBASE: Unifying Online Vector Similarity Search and Relational Queries via Relaxed Monotonicity (USENIX'17) [[pdf](https://www.usenix.org/system/files/osdi23-zhang-qianxi_1.pdf)]
  - The Faiss library (Arxiv'24) [[pdf](https://arxiv.org/pdf/2401.08281)]

## System
  - Milvus: A Purpose-Built Vector Data Management System (SIGMOD’21) [[pdf](https://www.cs.purdue.edu/homes/csjgwang/pubs/SIGMOD21_Milvus.pdf)]
