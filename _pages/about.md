---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Binglin (Kevin) Ji, a second-year master's student in `Electrical Engineering` and `Computer Engineering` at [Washington University in St. Louis](https://washu.edu). I'm currently a member of [Stream Based Supercomputing Lab](https://sbs.wustl.edu), advised by Prof. [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/). My research interests lie in **Machine Learning** (Bayesian Inversion) and **Parallel Computing** (AI Inference Acceleration), as well as the intersection of these two areas. 

Before coming to WashU, I worked at [Lenovo Research](https://research.lenovo.com/webapp/view_English/home.html), Shanghai, China, where I developed deep learning algorithms to solve computer vision problems in industrial scenarios and built container-based systems to optimize machine learning workflows.



## Fast GNN Inference on Multi-Core Systems <br> ( in [IPDPS 2025 Workshops](https://www.ipdps.org/ipdps2025/2025-workshops.html) )

Existing standard Graph Neural Network (GNN) libraries face challenges in performance and scalability on modern multi-core systems, especially for large graphs (more than 100,000 vertices) with heavy embeddings. We optimized GCN inference with different parallel strategies according to the properties of input graphs, considering the design trends of multi-core architectures. As a result, we achieved up to **2.64x** inference speed compared to `DGL v2.4.0` (Deep Graph Library) and **3.36x** compared to `PyG v2.6.1` (PyTorch-Geometric), both of which used `PyTorch v2.3.1` as the backend.





## Past Project
#### Computer Vision Based Sports Motion Analysis System
Computer vision is increasingly being adopted in sports motion analysis. However, widely used systems like Dartfish rely on classic computer vision algorithms, requiring extensive manual calibration for quantitative metrics and often resulting in significant errors. We have developed an intelligent analysis system with deep learning based 2D and 3D human pose estimation algorithms. Users simply need to upload raw videos, the system will compute sequence data of multiple key quantitative indicators and conduct a comprehensive analysis.

Invention Patent: CN202110916792.7




