# Graph Condensation Papers 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/> 



**Graph condensation** (GC) is a data-centric approach that accelerates GNN model training by creating a compact yet representative graph to replace the original graph. It enables GNNs trained on the condensed graph to match the performance of those trained on the original graph.

<p align="center">
<img src="main.jpg" alt="GC" width="750">
</p>



This repository aims to provide a comprehensive resource for researchers and practitioners interested in exploring various aspects of graph condensation.

For a detailed overview of graph condensation techniques and their applications, we recommend reading our survey paper on **TKDE'25**: 🔥[Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720) and our tutorial at **WWW'25**: [Graph Condensation: Foundations, Methods and Prospects](https://xygaog.github.io/WWW25tut/). The survey paper serves as an excellent starting point for understanding the fundamentals of graph condensation and exploring its diverse applications.


To understand the underlying mechanism of optimization strategies in graph condensation, we highly recommend the paper 🔥🔥🔥[Rethinking and Accelerating Graph Condensation: A Training-Free Approach with Class Partition](https://arxiv.org/abs/2405.13707) as essential reading.



**Note: recommended papers are marked by 📌.**



## Latest Updates
[28/06/2025] [Dynamic Graph Condensation](https://arxiv.org/abs/2506.13099) (Dong Chen et al. ArXiv'25)     
[28/06/2025] [Simple yet Effective Graph Distillation via Clustering](https://arxiv.org/pdf/2505.20807) (Yurui Lai et al. KDD'25)       
[28/06/2025] [GDCK: Efficient Large-Scale Graph Distillation Utilizing a Model-Free Kernelized Approach](https://link.springer.com/chapter/10.1007/978-981-96-8298-0_19) (Yue Zhang et al. PAKDD'25)  
[28/06/2025] [Adapting Precomputed Features for Efficient Graph Condensation](https://openreview.net/forum?id=ThK6o74QLc) (Yuan Li et al. ICML'25)  
[11/05/2025] [ST-GCond: Self-supervised and Transferable Graph Dataset Condensation](https://openreview.net/forum?id=wYWJFLQov9) (Beining Yang et al. ICLR'25)  
[11/05/2025] [Bonsai: Gradient-free Graph Condensation for Node Classification](https://openreview.net/forum?id=5x88lQ2MsH) (Mridul Gupta et al. ICLR'25)  
[11/05/2025] [Bi-Directional Multi-Scale Graph Dataset Condensation via Information Bottleneck](https://ojs.aaai.org/index.php/AAAI/article/view/33832) (Xingcheng Fu et al. AAAI'25)  
[11/05/2025] [Structure Balance and Gradient Matching-Based Signed Graph Condensation](https://ojs.aaai.org/index.php/AAAI/article/view/33320) (Rong Li et al. AAAI'25)  
[11/05/2025] [Rethinking Federated Graph Learning: A Data Condensation Perspective](https://arxiv.org/abs/2505.02573) (Hao Zhang et al. Arxiv'25)  
[11/05/2025] [FedC4: Graph Condensation Meets Client-Client Collaboration for Efficient and Private Federated Graph Learning](https://arxiv.org/abs/2504.14188) (Zekai Chen et al. Arxiv'25)  


<details>
<summary>View More Updates</summary>

[02/03/2025] [Scalable Graph Condensation with Evolving Capabilities](https://arxiv.org/abs/2502.17614) (Shengbo Gong et al. Arxiv'25)  
[02/02/2025] [Exploring Hypergraph Condensation via Variational Hyperedge Generation and Multi-Aspectual Amelioration](https://openreview.net/forum?id=bdaJGj9LPc#discussion) (Zheng Gong et al. WWW'25)  
[01/02/2025] [Random Walk Guided Hyperbolic Graph Distillation](https://arxiv.org/abs/2501.15696) (Yunbo Long et al. Arxiv'25)  
[09/01/2025] [Efficient Graph Condensation via Gaussian Process](https://arxiv.org/abs/2501.02565) (Lin Wang et al. Arxiv'25)  
[09/01/2025] [GraphDART: Graph Distillation for Efficient Advanced Persistent Threat Detection](https://arxiv.org/abs/2501.02796) (Saba Fathi Rabooki et al. Arxiv'25)  
[09/01/2025] [Training-free Heterogeneous Graph Condensation via Data Selection](https://arxiv.org/abs/2412.16250) (Yuxuan Liang et al. ICDE'25)  
[27/11/2024] [Contrastive Graph Condensation: Advancing Data Versatility through Self-Supervised Learning](https://arxiv.org/abs/2411.17063) (Xinyi Gao et al. Arxiv'24)
[05/09/2024] [GSTAM: Efficient Graph Distillation with Structural Attention-Matching](https://arxiv.org/abs/2408.16871) (Arash Rasti-Meymandi et al. ECCV'24)  
[28/08/2024] [Self-Supervised Learning for Graph Dataset Condensation](https://dl.acm.org/doi/10.1145/3637528.3671682) (Yuxiang Wang et al. KDD'24)  
[31/07/2024] [Backdoor Graph Condensation](https://arxiv.org/abs/2407.11025) (Jiahao Wu et al. Arxiv'24)  
[20/07/2024] [TinyGraph: Joint Feature and Node Condensation for Graph Neural Networks](https://arxiv.org/abs/2407.08064) (Yezi Liu et al. Arxiv'24)

</details>

## Contribution
We welcome contributions to enhance the breadth and depth of this repository. If you have a paper related to graph condensation that you believe should be included, please feel free to submit a pull request. Together, we can build a valuable resource for the graph condensation community.
```
| conference/journal'year | [paper_name](paper_link) | Authors | [[code]](code_link) |
```


***
## Contents
The repository is organized into categories to facilitate easy navigation and exploration of papers related to graph condensation, including effectiveness, efficiency, generalization, fairness and applications.



- [Graph Condensation Papers](#graph-condensation-papers)
  - [Latest Updates](#latest-updates)
  - [Contribution](#contribution)
  - [Contents](#contents)
  - [Survey](#survey)
  - [Tutorial](#tutorial)
  - [Methodology](#methodology)
    - [Effective Graph Condensation](#effective-graph-condensation)
    - [Efficient Graph Condensation](#efficient-graph-condensation)
    - [Generalized Graph Condensation](#generalized-graph-condensation)
    - [Fair Graph Condensation](#fair-graph-condensation)
    - [Robust Graph Condensation](#robust-graph-condensation)
  - [Applications](#applications)
    - [Graph Continual Learning](#graph-continual-learning)
    - [Hyper-Parameter/Neural Architecture Search](#hyper-parameterneural-architecture-search)
    - [Federated Learning](#federated-learning)
    - [Inference Acceleration](#inference-acceleration)
    - [Heterogeneous Graph](#heterogeneous-graph)
    - [Hypergraph Graph](#hypergraph-graph)
    - [Signed Graph](#signed-graph)
    - [Dynamic Graph](#dynamic-graph)
    - [Security](#security)
  - [Open-Source Libraries](#open-source-libraries)
  - [Related Repositories](#related-repositories)
  - [Contact](#contact)





***
## Survey

| | | | 
|-|-|-|
| TKDE'25 | 📌[Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720) | Xinyi Gao et al. |
| IJCAI'24 | [A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation](https://arxiv.org/abs/2402.03358) | Mohammad Hashemi & Wei Jin et al. |
| TKDD'25 | [Learning to Reduce the Scale of Large Graphs: A Comprehensive Survey](https://dl.acm.org/doi/abs/10.1145/3729427) | Hongjia Xu et al. |


***
## Tutorial

| | | ||
|-|-|-|-|
| WWW'25 | 📌[Graph Condensation: Foundations, Methods and Prospects](https://dl.acm.org/doi/10.1145/3701716.3715862) | Hongzhi Yin, Xinyi Gao et al. | [[Website]](https://xygaog.github.io/WWW25tut/) |

***
&nbsp;
## Methodology

### Effective Graph Condensation

| | | | | |
|-|-|-|-|-|
| ICLR'22| GCond | 📌[Graph Condensation for Graph Neural Networks](https://arxiv.org/abs/2110.07580) | Wei Jin et al. | [[code]](https://github.com/chandlerbang/gcond) |
| KBS'23| MSGC | [Multiple Sparse Graphs Condensation](https://www.sciencedirect.com/science/article/pii/S0950705123006548) | Jian Gao et al. | |
| NeurIPS'23| SFGC | 📌[Structure-free Graph Condensation: From Large-scale Graphs to Condensed Graph-free Data](https://arxiv.org/abs/2306.02664) | Xin Zheng et al. | [[code]](https://github.com/amanda-zheng/sfgc) |
| Arxiv'23|GroC | [Attend Who is Weak: Enhancing Graph Condensation via Cross-Free Adversarial Training](https://arxiv.org/abs/2311.15772) | Xinglin Li et al. | |
| Arxiv'24| CTRL | [Two Trades is not Baffled: Condensing Graph via Crafting Rational Gradient Matching](https://arxiv.org/abs/2402.04924) | Tianle Zhang et al. | [[code]](https://github.com/nus-hpc-ai-lab/ctrl) |
| ICML'24| GEOM | 📌[Navigating Complexity: Toward Lossless Graph Condensation via Expanding Window Matching](https://arxiv.org/abs/2402.05011) | Yuchen Zhang et al. | [[code]](https://github.com/nus-hpc-ai-lab/geom) |
| KDD'24| GCSR | [Graph Data Condensation via Self-expressive Graph Structure Reconstruction](https://arxiv.org/abs/2403.07294) | Zhanyu Liu et al. | [[code]](https://www.dropbox.com/scl/fi/2aonyp5ln5gisdqtjimu8/GCSR.zip?rlkey=11cuwfpsf54wxiiktu0klud0x&dl=0) |
| KDD'24| SGDC | 📌[Self-Supervised Learning for Graph Dataset Condensation](https://dl.acm.org/doi/10.1145/3637528.3671682) | Yuxiang Wang et al. | [[code]](https://github.com/wyx11112/SGDC) |  
| ECCV'24| GSTAM | [GSTAM: Efficient Graph Distillation with Structural Attention-Matching](https://arxiv.org/abs/2408.16871) | Arash Rasti-Meymandi et al. | [[code]](https://github.com/arashrasti96/GSTAM) |  
| Arxiv'25| HyDRO | [Random Walk Guided Hyperbolic Graph Distillation](https://arxiv.org/abs/2501.15696) | Yunbo Long et al. | |  
| AAAI'25| BiMSGC | [Bi-Directional Multi-Scale Graph Dataset Condensation via Information Bottleneck](https://ojs.aaai.org/index.php/AAAI/article/view/33832) | Xingcheng Fu et al. | |   
| WWW'25| TinyGraph | [Beyond Node Condensation: Learning Tiny Graphs via Joint Graph Condensation](https://dl.acm.org/doi/abs/10.1145/3701716.3715566) | Yezi Liu et al. | |

### Efficient Graph Condensation

| | | | | |
|-|-|-|-|-|
| KDD'22 | DosCond | [Condensing Graphs via One-Step Gradient Matching](https://arxiv.org/abs/2206.07746) | Wei Jin et al. | [[code]](https://github.com/amazon-research/DosCond) |
| Arxiv'22 | GCDM | 📌[Graph Condensation via Receptive Field Distribution Matching](https://arxiv.org/abs/2206.13697) | Mengyang Liu et al. | |
| KDD'23 | KIDD | [Kernel Ridge Regression-Based Graph Dataset Distillation](https://dl.acm.org/doi/10.1145/3580305.3599398) | Zhe Xu et al. | [[code]](https://github.com/pricexu/KIDD) |
| WWW'24 | GC-SNTK | [Fast Graph Condensation with Structure-based Neural Tangent Kernel](https://arxiv.org/abs/2310.11046) | Lin Wang et al. | |
| ICLR'24 | Mirage | [Mirage: Model-Agnostic Graph Distillation for Graph Classification](https://arxiv.org/abs/2310.09486) | Mridul Gupta et al. | [[code]](https://github.com/idea-iitd/Mirage) |
| WWW'25 | DisCo | [Disentangled Condensation for Large-scale Graphs](https://arxiv.org/abs/2401.12231) | Zhenbang Xiao et al. | [[code]](https://github.com/BangHonor/DisCo) |
| WWW'24 | EXGC | [EXGC: Bridging Efficiency and Explainability in Graph Condensation](https://arxiv.org/abs/2402.05962) | Junfeng Fang et al. | [[code]](https://github.com/MangoKiller/EXGC) |
| PKDD'24 | SimGC | [Simple Graph Condensation](https://arxiv.org/abs/2403.14951) | Zhenbang Xiao et al. | [[code]](https://github.com/BangHonor/SimGC) |
| WWW'25 | CGC | 📌[Rethinking and Accelerating Graph Condensation: A Training-Free Approach with Class Partition](https://arxiv.org/abs/2405.13707) | Xinyi Gao et al. | [[code]](https://github.com/XYGaoG/CGC) |   
| Arxiv'25 | GCGP | [Efficient Graph Condensation via Gaussian Process](https://arxiv.org/abs/2501.02565) | Lin Wang et al. | [[code]](https://github.com/WANGLin0126/GCGP) |   
| Arxiv'25 | GECC | [Scalable Graph Condensation with Evolving Capabilities](https://arxiv.org/abs/2502.17614) | Shengbo Gong et al. | |     
| ICLR'25 | Bonsai | [Bonsai: Gradient-free Graph Condensation for Node Classification](https://openreview.net/forum?id=5x88lQ2MsH) | Mridul Gupta et al. | [[code]](https://github.com/idea-iitd/Bonsai)|      
| ICML'25 | GCPA | [Adapting Precomputed Features for Efficient Graph Condensation](https://openreview.net/forum?id=ThK6o74QLc) | Yuan Li et al. | [[code]](https://github.com/Xtra-Computing/GCPA)|      
| KDD'25 | ClustGDD | [Simple yet Effective Graph Distillation via Clustering](https://arxiv.org/abs/2505.20807) | Yurui Lai et al. | [[code]](https://github.com/HKBU-LAGAS/ClustGDD)|   
| PAKDD '25 | GDCK | [GDCK: Efficient Large-Scale Graph Distillation Utilizing a Model-Free Kernelized Approach](https://link.springer.com/chapter/10.1007/978-981-96-8298-0_19) | Yue Zhang et al. |[[code]](https://github.com/SchenbergZY/GDCK)|      




### Generalized Graph Condensation

| | | | | |
|-|-|-|-|-|
| NeurIPS'23| SGDD| [Does Graph Distillation See Like Vision Dataset Counterpart?](https://arxiv.org/abs/2310.09192) | Beining Yang et al. | [[code]](https://github.com/RingBDStack/SGDD) |
| ICML'24 | GDEM| 📌[Graph Distillation with Eigenbasis Matching](https://arxiv.org/abs/2310.09202) | Yang Liu et al. | [[code]](https://github.com/BUPT-GAMMA/GDEM)|
| KDD'24 | OpenGC | [Graph Condensation for Open-World Graph Learning](https://arxiv.org/abs/2405.17003) | Xinyi Gao et al. | |
| KDD'25 | CTGC | [Contrastive Graph Condensation: Advancing Data Versatility through Self-Supervised Learning](https://arxiv.org/abs/2411.17063) | Xinyi Gao et al. | |
| ICLR'25 | ST-GCond | 📌[ST-GCond: Self-supervised and Transferable Graph Dataset Condensation](https://openreview.net/forum?id=wYWJFLQov9) | Beining Yang et al. | [[code]](https://github.com/RingBDStack/ST-GCond)|   

### Fair Graph Condensation

| | | | |
|-|-|-|-|
| NeurIPS'23| FGD| 📌[Fair Graph Distillation](https://openreview.net/forum?id=xW0ayZxPWs) | Qizhang Feng et al. | 
| AS'23 | GCARe| [GCARe: Mitigating Subgroup Unfairness in Graph Condensation through Adversarial Regularization](https://www.mdpi.com/2076-3417/13/16/9166) | Runze Mao et al. | 

### Robust Graph Condensation

| | | | | |
|-|-|-|-|-|
| TKDE'25 | RobGC | [RobGC: Towards Robust Graph Condensation](https://arxiv.org/abs/2406.13200) | Xinyi Gao et al. | [[code]](https://github.com/XYGaoG/RobGC)|



***
&nbsp;
## Applications

### Graph Continual Learning

| | | | | |
|-|-|-|-|-|
| ICDM'23 | CaT | [CaT: Balanced Continual Graph Learning with Graph Condensation](https://arxiv.org/abs/2309.09455) | Yilun Liu et al. | [[code]](https://github.com/superallen13/CaT-CGL) |
| TKDE'24 | PUMA | 📌[PUMA: Efficient Continual Graph Learning with Graph Condensation](https://arxiv.org/abs/2312.14439) | Yilun Liu et al. | [[code]](https://github.com/superallen13/puma) |

### Hyper-Parameter/Neural Architecture Search

| | | | |
|-|-|-|-|
| Arxiv'23 |HCDC | [Faster Hyperparameter Search for GNNs via Calibrated Dataset Condensation](https://openreview.net/forum?id=ohQPU2G3r3C) | Mucong Ding et al. | 

### Federated Learning

| | | | |
|-|-|-|-|
| NeurIPS'23 |FedGKD | 📌[FedGKD: Unleashing the Power of Collaboration in Federated Graph Neural Networks](https://openreview.net/pdf?id=qCgptbOsdS) | Qiying Pan et al. |
| AAAI'25 | FedGC | [Federated Graph Condensation with Information Bottleneck Principles](https://arxiv.org/abs/2405.03911) | Bo Yan |   
| Arxiv'25 | FedC4 | [FedC4: Graph Condensation Meets Client-Client Collaboration for Efficient and Private Federated Graph Learning](https://arxiv.org/abs/2504.14188) | Zekai Chen | 
| Arxiv'25 | FedGM | [Rethinking Federated Graph Learning: A Data Condensation Perspective](https://arxiv.org/abs/2505.02573) | Hao Zhang | 


### Inference Acceleration

| | | | |
|-|-|-|-|
| ICDE'24 |MCond | [Graph Condensation for Inductive Node Representation Learning](https://arxiv.org/abs/2307.15967) | Xinyi Gao et al. | 

### Heterogeneous Graph

| | | | | |
|-|-|-|-|-|
| TKDE'24 |HGCond | [Heterogeneous Graph Condensation](https://ieeexplore.ieee.org/abstract/document/10423255) | Jian Gao et al. | [[code]](https://github.com/jianjianGJ/hgcond) |
| ICDE'25 |FreeHGC | 📌[Training-free Heterogeneous Graph Condensation via Data Selection](https://arxiv.org/abs/2412.16250) | Yuxuan Liang et al. | [[code]](https://github.com/PKU-DAIR/FreeHGC) |

### Hypergraph Graph

| | | | | |
|-|-|-|-|-|
| WWW'25 |HG-Cond | [Exploring Hypergraph Condensation via Variational Hyperedge Generation and Multi-Aspectual Amelioration](https://openreview.net/forum?id=bdaJGj9LPc#discussion) | Zheng Gong et al. | |


### Signed Graph

| | | | | |
|-|-|-|-|-|
| AAAI'25 |SGSGC | [Structure Balance and Gradient Matching-Based Signed Graph Condensation](https://ojs.aaai.org/index.php/AAAI/article/view/33320) | Rong Li et al. | |

### Dynamic Graph

| | | | | |
|-|-|-|-|-|
| ArXiv'25 |DyGC | [Dynamic Graph Condensation](https://arxiv.org/abs/2506.13099) | Dong Chen et al. | |

### Security

| | | | | |
|-|-|-|-|-|
| ICDE'25 |BGC | 📌[Backdoor Graph Condensation](https://arxiv.org/abs/2407.11025) | Jiahao Wu et al. | [[code]](https://github.com/JiahaoWuGit/BGC) |
| Arxiv'25 |GraphDART | [GraphDART: Graph Distillation for Efficient Advanced Persistent Threat Detection](https://arxiv.org/abs/2501.02796) | Saba Fathi Rabooki et al. |


***
&nbsp;
## Open-Source Libraries
| Library | Paper | Implementation | #GC Methods | #Datasets | Tasks |
|-|-|-|-|-|-|
| [GCondenser](https://github.com/superallen13/GCondenser)| [[paper]](https://arxiv.org/abs/2405.14246)| PyG, DGL | 6| 7| Node classification |
| [GC-Bench](https://github.com/RingBDStack/GC-Bench)| [[paper]](https://arxiv.org/abs/2407.00615)|PyG | 9 | 12 | Node classification, graph classification, link prediction, node clustering, anomaly detection |
| [GraphSlim](https://github.com/Emory-Melody/GraphSlim)| [[paper]](https://arxiv.org/abs/2406.16715)|PyG | 7| 5| Node classification | 



***
&nbsp;
## Related Repositories
In addition to this Graph Condensation Papers Repository, you may find the following related repositories valuable for your research and exploration:
+ [Awesome-graph-reduction](https://github.com/ChandlerBang/awesome-graph-reduction)
+ [Awesome-Graph-Scaling](https://github.com/Frostland12138/Awesome-Graph-Scaling)
+ [Awesome-Dataset-Distillation](https://github.com/Guang000/Awesome-Dataset-Distillation)



***
&nbsp;
## Contact
For any inquiries or suggestions regarding this repository, please don't hesitate to contact us by opening an issue on this repository.

Thank you for your interest in the Graph Condensation Papers Repository. We hope you find it valuable for your research and exploration. If you find this repository to be useful, please cite our survey paper.

```
@article{gao2025graph,
  title={Graph condensation: A survey},
  author={Gao, Xinyi and Yu, Junliang and Chen, Tong and Ye, Guanhua and Zhang, Wentao and Yin, Hongzhi},
  journal={IEEE Transactions on Knowledge and Data Engineering},
  year={2025},
  publisher={IEEE}
}
```
