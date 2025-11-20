---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Binglin (Kevin) Ji, a second-year master's student in `Electrical Engineering` and `Computer Engineering` at [Washington University in St. Louis](https://washu.edu). I'm currently a member of [Stream Based Supercomputing Lab](https://sbs.wustl.edu), advised by Prof. [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/). My research interests lie in **Machine Learning** (Probabilistic Sampling) and **Parallel Computing** (AI Inference Acceleration), as well as the intersection of these two areas. 

Before coming to WashU, I worked at [Lenovo Research](https://research.lenovo.com/webapp/view_English/index.html), Shanghai, China, where I developed deep learning algorithms to solve computer vision problems in industrial scenarios and built container-based systems to optimize machine learning workflows.


## 🔍 Online Active Target Discovery with Generative Model

Strategic sampling within a limited sampling budget from unobserved regions is essential in various scientific and engineering domains. We model this problem as Active Target Discovery(*ATD*) and introduce novel frameworks that leverage diffusion dynamics to solve *ATD* problems.

### Active Target Discovery under Uninformative Prior  

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/EM_PTDM)  With zero domain knowledge, inspired by neuro-science, we introduce *EM-PTDM* to solve the online feedback *ATD* problem. More details in our paper: [**Active Target Discovery under Uninformative Prior: The Power of Permanent and Transient Memory**](https://arxiv.org/abs/2510.16676) ***(NeurIPS 2025)*** 🚀

<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/emptdm.png" width="77%"> </p>

### Diffusion-guided Active Target Discovery

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/DiffATD) With enough domain knowledge data, we first time introduce *DiffATD* to solve Online Feedback Active Target Discovery problem in Partially Observable Environments. More details in our paper: [**Online Feedback Efficient Active Target Discovery in Partially Observable Environments**](https://www.arxiv.org/abs/2505.06535) ***(NeurIPS 2025)*** 🚀 

<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/diffatd.png" width="75%"> </p>


## ⚙️ Optimizing GCN Inference on Multi-Core Systems

[![Project Page](https://img.shields.io/badge/Project-Website-green)](https://github.com/KevinG396/FGI-Fast-GNN-Inference-on-Multi-Core-Systems)  Existing standard GNN libraries face challenges in performance and scalability on modern multi-core systems, especially for large graphs (more than 100,000 vertices) with heavy embeddings. We optimized GCN inference with different parallel strategies according to the graph properties, considering the design trends of multi-core architectures. As a result, we achieved up to **2.64x** inference speed compared to `DGL v2.4.0` (Deep Graph Library) and **3.36x** compared to `PyG v2.6.1` (PyTorch-Geometric), both of which used `PyTorch v2.3.1` as the backend. More details in our paper: [**FGI: Fast GNN Inference on Multi-Core Systems**](https://sbs.wustl.edu/pubs/jzc25.pdf) ***(IPDPS 2025 Workshops)*** 🚀
<p align="center"> <img src="https://raw.githubusercontent.com/KevinG396/kevinji.github.io/master/assets/imgs/fgi.png" width="78%"> </p>

### 🎧 Outside of research, I enjoy Rock Music
You should check this out — one of my all-time favorites: [Bon Jovi - Livin' on a Prayer (Hyde Park 2011)](https://www.youtube.com/watch?v=keZ0vigZz3Y)

<!-- ## Past Project
### Computer Vision Based Sports Motion Analysis System
Computer vision is increasingly being adopted in sports motion analysis. However, widely used systems like Dartfish rely on classic computer vision algorithms, requiring extensive manual calibration for quantitative metrics and often resulting in significant errors. We have developed an intelligent analysis system with deep learning based 2D and 3D human pose estimation algorithms. Users simply need to upload raw videos, the system will compute sequence data of multiple key quantitative indicators and conduct a comprehensive analysis.

Invention Patent Granted: CN202110916792.7
-->


