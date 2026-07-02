---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Binglin (Kevin) Ji, a graduated master's student in `Electrical Engineering` and `Computer Engineering` at [Washington University in St. Louis](https://washu.edu). My research focuses on probabilistic inference and generative modeling in high dimension space. 

I was advised by Prof. [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/) on AI inference and collaborated with [Yevgeniy Vorobeychik](https://engineering.washu.edu/faculty/Yevgeniy-Vorobeychik.html) on generative AI and sampling. Before coming to WashU, I worked at National Laboratory of Pattern Recognition, [Institute of Automation, Chinese Academy of Sciences](http://english.ia.cas.cn) and [Lenovo Research](https://research.lenovo.com/webapp/view_English/index.html).

# Research
My research goal is to design **probabilistic AI models** and **sampling algorithms** that efficiently address high-dimensional inference while remaining mathematically and computationally tractable. My research interests lie in:

**🌟 Probabilistic Inference**: Inference-time controlled sampling and posterior inference for probabilistic generative models (Diffusion/Flow/Consistency Models), variational inference, distribution shift.
  - [**Controlled Measure Transport**](https://arxiv.org/abs/2607.01144) (Variational Inference, Optimal Control on Flow Model)
  - [**Sampling**](https://arxiv.org/abs/2607.01144) (SDE, Feynman-Kac Corrector)
  - **MCTS for Search** <!--(MCTS, Flow/Consistency Model)-->
  - **Applied Stochastic Process** <!--(Lévy Process)-->

**Generative Modeling**: Probabilistic generative models and their applications in active discovery/decision making.
  - [**Diffusion Model**](https://neurips.cc/virtual/2025/loc/san-diego/poster/116694) (Tweedie's Estimate, Sequential Decision Making)
  - [**EM-Adaptation**](https://neurips.cc/virtual/2025/loc/san-diego/poster/115332) (Doob's *h*-transform, Expectation-Maximization)

**Parallel AI Inference**: Accelerating AI computation (Neural Networks and Graph structures).
  - **Matrix Computation** (Parallel Computing, GNN, GEMM)
  - [**Graph Processing**](https://ieeexplore.ieee.org/document/11105982) (Graph Structure Operation)

😃 I am always excited to collaborate, including but not limited to areas such as **AI for Science**, **Scientific Computing** and **Variational Inference**.


# Projects

## 🌟 Probabilistic Inference and Sampling

### Interaction, Control, and Sampling in Particle Systems
We propose Sequentially-Controlled Interactive Multi-Particle Flow-Maps (IMPFM), a framework for sample-efficient online feedback-driven search. IMPFM introduces a principled, efficient and and variationally grounded posterior sample sharing mechanism across particles powered by flow maps, progressively transports a group of interactive particles toward the target distribution, maintaining the broad coverage essential for heterogeneous preference alignment.

<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/images/impfm.png" width="95%"> </p>

## 🔍 Online Active Discovery with Diffusion Model

Strategic sampling within a limited sampling budget from unobserved regions is essential in various scientific and engineering domains. We model this problem as Active Target Discovery(*ATD*) and introduce novel frameworks that leverage diffusion dynamics to solve *ATD* problems. *Key Words: Diffusion Models, Tweedie's Estimate, Doob's h-transform.*

### Active Target Discovery under Uninformative Prior  

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/EM_PTDM)  With weak prior, we leverage *Doob's h-transform* and introduce *EM-PTDM* to solve the online feedback *ATD* problem. More details: [**Active Target Discovery under Uninformative Prior: The Power of Permanent and Transient Memory**](https://arxiv.org/abs/2510.16676) ***(NeurIPS 2025)*** 🚀


<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/emptdm.png" width="95%"> </p>

### Diffusion-guided Active Target Discovery

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/DiffATD) With prior (domain knowledge), we introduce *DiffATD* to solve Online Feedback Active Target Discovery problem in Partially Observable Environments. More details: [**Online Feedback Efficient Active Target Discovery in Partially Observable Environments**](https://www.arxiv.org/abs/2505.06535) ***(NeurIPS 2025)*** 🚀 


<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/diffatd.png" width="85%"> </p>


## ⚙️ Parallel AI Inference

*Key Words: Graph Neural Networks, Sparse Matrix, Multi-threaded Programming.*

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/FGI-Fast-GNN-Inference-on-Multi-Core-Systems)  Graph structures are widly used in scientific computing and AI applications. Existing graph processing systems face challenges in performance and scalability, especially for very large graphs (more than 100,000 vertices) with heavy embeddings. We optimized graph processing in GCN inference with different parallel strategies according to the graph properties. As a result, we achieved up to **2.64x** inference speed compared to `DGL v2.4.0` (Deep Graph Library) and **3.36x** compared to `PyG v2.6.1` (PyTorch-Geometric), both of which used `PyTorch v2.3.1` as the backend. More details in our paper: [**FGI: Fast GNN Inference on Multi-Core Systems**](https://sbs.wustl.edu/pubs/jzc25.pdf) ***(IPDPS 2025 Workshops)*** 🚀


<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/fgi.png" width="85%"> </p>

### 🎧 Outside of research, I enjoy Rock Music
You should check this out — one of my all-time favorites: [Bon Jovi - Livin' on a Prayer (Hyde Park 2011)](https://www.youtube.com/watch?v=keZ0vigZz3Y)

<!-- ## Past Project
### Computer Vision Based Sports Motion Analysis System
Computer vision is increasingly being adopted in sports motion analysis. However, widely used systems like Dartfish rely on classic computer vision algorithms, requiring extensive manual calibration for quantitative metrics and often resulting in significant errors. We have developed an intelligent analysis system with deep learning based 2D and 3D human pose estimation algorithms. Users simply need to upload raw videos, the system will compute sequence data of multiple key quantitative indicators and conduct a comprehensive analysis.

Invention Patent Granted: CN202110916792.7
-->


