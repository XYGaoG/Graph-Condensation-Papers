# Graph Condensation Papers 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
<img src="https://img.shields.io/badge/Contributions-Welcome-278ea5" alt="Contrib"/> 



## About
Graph condensation involves the process of simplifying complex graphs while preserving essential structural information. This repository aims to provide a comprehensive resource for researchers and practitioners interested in exploring various aspects of graph condensation.

For a detailed overview of graph condensation techniques and their applications, we recommend reading our survey paper: [Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720). This survey paper serves as an excellent starting point for understanding the fundamentals of graph condensation and exploring its diverse applications.


## Contents
The repository is organized into categories to facilitate easy navigation and exploration of papers related to graph condensation, including effectiveness, efficiency, generalization, fairness and applications.


- [Graph Condensation Papers](#graph-condensation-papers)
  - [About](#about)
  - [Contents](#contents)
  - [Survey](#survey)
  - [Methdology](#methdology)
      - [Effective Graph Condensation](#effective-graph-condensation)
      - [Efficient Graph Condensation](#efficient-graph-condensation)
      - [Generalized Graph Condensation](#generalized-graph-condensation)
      - [Fair Graph Condensation](#fair-graph-condensation)
  - [Applications](#applications)
    - [Graph Continual Learning](#graph-continual-learning)
    - [Hyper-Parameter/Neural Architecture Search](#hyper-parameterneural-architecture-search)
    - [Federated Learning](#federated-learning)
    - [Inference Acceleration](#inference-acceleration)
    - [Heterogeneous Graph](#heterogeneous-graph)
  - [Related Repositories](#related-repositories)
  - [Contribution](#contribution)
  - [Contact](#contact)




<a name="survey" />

## Survey

+ [Graph Condensation: A Survey](https://arxiv.org/abs/2401.11720) (Xinyi Gao et al., Arxiv 2024)
+ [A Comprehensive Survey on Graph Reduction: Sparsification, Coarsening, and Condensation](https://cse.msu.edu/~jinwei2/files/Survey_GraphReduction.pdf) (Mohammad Hashemi & Shengbo Gong et al., Arxiv 2024)
+ [A Survey on Graph Condensation](https://arxiv.org/abs/2402.02000) (Hongjia Xu et al., Arxiv 2024)


<a name="Methdology" />

## Methdology



<a name="Effective Graph Condensation" />

#### Effective Graph Condensation
+ [Graph Condensation for Graph Neural Networks](https://arxiv.org/abs/2110.07580) (Wei Jin et al., ICLR 2022) [:octocat:](https://github.com/chandlerbang/gcond)
+ [Multiple sparse graphs condensation](https://www.sciencedirect.com/science/article/pii/S0950705123006548) (Jian Gao et al., KBS 2023)   
+ [Structure-free Graph Condensation: From Large-scale Graphs to Condensed Graph-free Data](https://arxiv.org/abs/2306.02664) (Xin Zheng et al., NeurIPS 2023) [:octocat:](https://github.com/amanda-zheng/sfgc)
+ [Attend Who is Weak: Enhancing Graph Condensation via Cross-Free Adversarial Training](https://arxiv.org/abs/2311.15772) (Xinglin Li et al., 2023) 
+ [Two Trades is not Baffled: Condensing Graph via Crafting Rational Gradient Matching](https://arxiv.org/abs/2402.04924) (Tianle Zhang & Yuchen Zhang & Kai Wang et al., 2024) [:octocat:](https://github.com/nus-hpc-ai-lab/ctrl) 
+ [Navigating Complexity: Toward Lossless Graph Condensation via Expanding Window Matching](https://arxiv.org/abs/2402.05011) (Yuchen Zhang & Tianle Zhang & Kai Wang et al., 2024) [:octocat:](https://github.com/nus-hpc-ai-lab/geom)
+ [Graph Data Condensation via Self-expressive Graph Structure Reconstruction](https://arxiv.org/abs/2403.07294) (Zhanyu Liu & Chaolv Zeng et al., 2024) [:octocat:](https://www.dropbox.com/scl/fi/2aonyp5ln5gisdqtjimu8/GCSR.zip?rlkey=11cuwfpsf54wxiiktu0klud0x&dl=0)




<a name="Efficient Graph Condensation" />

#### Efficient Graph Condensation
+ [Condensing Graphs via One-Step Gradient Matching](https://arxiv.org/abs/2206.07746) (Wei Jin et al., KDD 2022) [:octocat:](https://github.com/amazon-research/DosCond) 
+ [Graph Condensation via Receptive Field Distribution Matching](https://arxiv.org/abs/2206.13697) (Mengyang Liu et al., 2022)
+ [Kernel Ridge Regression-Based Graph Dataset Distillation](https://dl.acm.org/doi/10.1145/3580305.3599398) (Zhe Xu et al., KDD 2023) [:octocat:](https://github.com/pricexu/KIDD) 
+ [Fast Graph Condensation with Structure-based Neural Tangent Kernel](https://arxiv.org/abs/2310.11046) (Lin Wang et al., 2023) 
+ [Disentangled Condensation for Large-scale Graphs](https://arxiv.org/abs/2401.12231) [:octocat:](https://github.com/BangHonor/DisCo) (Zhenbang Xiao et al.,2024 ) 
+ [EXGC: Bridging Efficiency and Explainability in Graph Condensation](https://arxiv.org/abs/2402.05962) [:octocat:](https://github.com/MangoKiller/EXGC) (
Junfeng Fang et al., WWW 2024) 
+ [Simple Graph Condensation](https://arxiv.org/abs/2403.14951) (Zhenbang Xiao et al., 2024)



<a name="Generalized Graph Condensation" />

#### Generalized Graph Condensation

+ [Does Graph Distillation See Like Vision Dataset Counterpart?](https://arxiv.org/abs/2310.09192) (Beining Yang & Kai Wang et al., NeurIPS 2023) [:octocat:](https://github.com/RingBDStack/SGDD)
+ [Graph Condensation via Eigenbasis Matching](https://arxiv.org/abs/2310.09202) (Yang Liu et al., 2023) 
+ [Mirage: Model-Agnostic Graph Distillation for Graph Classification](https://arxiv.org/abs/2310.09486) [:octocat:](https://anonymous.4open.science/r/Mirage) (Mridul Gupta et al., 2023) 



<a name="Fair Graph Condensation" />

#### Fair Graph Condensation
+ [Fair Graph Distillation](https://openreview.net/forum?id=xW0ayZxPWs) (Qizhang Feng et al., NeurIPS 2023)
+ [GCARe: Mitigating Subgroup Unfairness in Graph Condensation through Adversarial Regularization](https://www.mdpi.com/2076-3417/13/16/9166) (Runze Mao et al., Applied Sciences 2023) 




<a name="Applications" />

## Applications


<a name="Graph Continual Learning" />

### Graph Continual Learning
+ [CaT: Balanced Continual Graph Learning with Graph Condensation](https://arxiv.org/abs/2309.09455) (Yilun Liu et al., ICDM 2023) [:octocat:](https://github.com/superallen13/CaT-CGL) [:book:](./citations/liu2023cat.txt)
+ [PUMA: Efficient Continual Graph Learning with Graph Condensation](https://arxiv.org/abs/2312.14439) [:octocat:](https://github.com/superallen13/puma) (Yilun Liu et al., 2023) 


<a name="Hyper-Parameter/Neural Architecture Search" />

### Hyper-Parameter/Neural Architecture Search
+ [Faster Hyperparameter Search for GNNs via Calibrated Dataset Condensation](https://openreview.net/forum?id=ohQPU2G3r3C) (Mucong Ding et al., 2023) 


<a name="Federated Learning" />

### Federated Learning
+ [FedGKD: Unleashing the Power of Collaboration in Federated Graph Neural Networks](https://arxiv.org/abs/2309.09517) (Qiying Pan et al., 2023) 

<a name="Inference Acceleration" />

### Inference Acceleration
+ [Graph Condensation for Inductive Node Representation Learning](https://arxiv.org/abs/2307.15967) (Xinyi Gao et al., 2023) 


<a name="Heterogeneous Graph" />

### Heterogeneous Graph
+ [Heterogeneous Graph Condensation](https://ieeexplore.ieee.org/abstract/document/10423255) [:octocat:](https://github.com/jianjianGJ/hgcond) (Jian Gao et al., TKDE 2024) 



<a name="Related Repositories" />

## Related Repositories
In addition to this Graph Condensation Papers Repository, you may find the following related repositories valuable for your research and exploration:
+ [awesome-graph-reduction](https://github.com/ChandlerBang/awesome-graph-reduction)
+ [Awesome-Graph-Condensation](https://github.com/Frostland12138/Awesome-Graph-Condensation)
+ [Awesome-Dataset-Distillation](https://github.com/Guang000/Awesome-Dataset-Distillation)




<a name="Contribution" />

## Contribution
We welcome contributions to enhance the breadth and depth of this repository. If you have a paper related to graph condensation that you believe should be included, please feel free to submit a pull request. Together, we can build a valuable resource for the graph condensation community.


<a name="Contact" />

## Contact
For any inquiries or suggestions regarding this repository, please don't hesitate to contact us. You can reach us via email at xinyi.gao@uq.edu.au or by opening an issue on this repository.


Thank you for your interest in the Graph Condensation Papers Repository. We hope you find it valuable for your research and exploration.