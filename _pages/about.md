---
layout: archive
title: "About"
permalink: /about/
author_profile: true
---

## About Me

I am **Longge Yuan (袁龙歌)**, a Master's student in Computer Science at **Florida State University (FSU)**.  
My interests are mainly in

- **High-Performance Computing (HPC) & distributed systems**
- **Large Language Model (LLM) optimization** – pruning, compression, and efficient inference
- **Streaming algorithms & probabilistic data structures** – such as Count-Min Sketch
- **Scientific data analysis & compression**
- **Intelligent monitoring systems for power grids**

I enjoy building systems that are not only theoretically sound, but also **engineered and benchmarked end-to-end** — from algorithms and data structures, to APIs, experiments, and visualization.

---

## Research & Technical Interests

- 🔹 **LLM Compression & Pruning**  
  - Structured pruning for LLaMA/Qwen-like models  
  - Hypernetwork-based pruning strategies and sparsity patterns  
  - Balancing model size, speed, and accuracy (perplexity / task performance)

- 🔹 **Streaming Algorithms & Database Systems**  
  - Count-Min Sketch and related sketches for frequency estimation  
  - Approximate query processing under tight memory constraints  
  - Building streaming services (FastAPI, load generators, evaluation pipelines)

- 🔹 **High-Performance Computing**  
  - Parallel and distributed training of deep models  
  - Memory-efficient execution and communication-aware design  

- 🔹 **Power-Grid Monitoring & Multispectral Sensing**  
  - Online monitoring of transmission lines and substations  
  - Infrared / visible / UV multi-spectral fusion for fault detection  
  - Edge deployment on embedded platforms and UAV / robot systems

---

## Selected Projects

- **Database Streaming CMS System (FSU Database Project)**  
  Built a high-throughput streaming frequency estimation service based on **Count-Min Sketch**.  
  Implemented a FastAPI **stream server**, a **load client** for synthetic workloads, and a full evaluation of:
  - error vs. ε under uniform and Zipfian distributions  
  - different estimators (min / mean / CMM)  
  - the effect of **Conservative Update (CU)** on accuracy and throughput.

- **LLM Pruning & Compression**  
  Worked on structured pruning methods for large language models (e.g., LLaMA / Qwen-style models), focusing on:
  - reducing parameter count while preserving perplexity and downstream accuracy  
  - exploring layer-wise importance and sparsity patterns  
  - integrating pruning into practical inference pipelines.

- **Scientific Data Compression Ratio Prediction**  
  Built ML models (Random Forest, XGBoost, etc.) to predict **lossy compression ratios** from field data features such as variance, Hurst exponent, and frequency energy ratios, helping to choose proper compressors and settings for large-scale simulations.

- **Power-Grid Multispectral Monitoring**  
  Participated in industry collaborations around transmission-line monitoring, GIS partial discharge, and transformer vibration / ultrasonic sensing.  
  Focused on data processing, feature extraction, and prototype software for multi-spectral fault diagnosis.

---

## Experience

- 🎓 **Graduate Studies in Computer Science, Florida State University**  
  - Coursework and projects in databases, operating systems, computer vision, HPC, and machine learning.  
  - Hands-on work with large-scale data, streaming systems, and neural network optimization.

- 🏭 **Industry Collaborations with Power-Grid Companies (China)**  
  - Involved in R&D projects on online monitoring of high-voltage equipment.  
  - Worked on multi-sensor fusion, signal processing, and software prototyping for field deployment.

---

## Skills

- **Programming:** Python, C++, Java  
- **ML / Data:** PyTorch, scikit-learn, NumPy, Pandas, MATLAB  
- **Systems & Backend:** FastAPI, REST APIs, basic Docker/Linux usage  
- **Databases & Streaming:** MySQL, basic query optimization, sketch-based data structures  
- **Tools:** Git/GitHub, LaTeX, VS Code, Jupyter, GitHub Pages / Jekyll

---

## Contact

- GitHub: [@longgeY](https://github.com/longgeY)  
- Email: *youremail@fsu.edu*  <!-- 把这里改成你的真实邮箱 -->
- Personal site: [https://longgeY.github.io](https://longgeY.github.io)

If you are interested in my work or potential collaborations (research, internships, or industry projects), feel free to reach out!
