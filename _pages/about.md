---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hello! This is Haidong Kang. I’m currently an associate professor at the School of Computational Science and Engineering, Northeastern University, China. He has published more than ten papers in top-tier journals and conferences, including IEEE Transactions on Computers, IEEE Transactions on Mobile Computing, SCIS, ICML 2025, ICCV 2025, NeurIPS 2025, ACM MM 2025, IJCAI 2025, AAAI 2026, and IEEE TNNLS. One of his top-tier journal papers has been recognized as an SCI Highly Cited Paper.

My current research interests include edge computing, machine learning, automated algorithm design, collaborative learning, and trustworthy artificial intelligence, detailed as follows:

- **Edge Computing**: Lightweight neural networks and large models, real-time video analytics systems, industrial vision, AI edge services, and system design
(Supporting publications: IEEE TC / TMC / TCAD, ICCV 2025, IJCAI 2025, one paper under review at CVPR 2026, SCIS 2025)

- **Machine Learning**: Stability and generalization error bounds, few-shot learning, self-supervised learning, AI for Science, and AIGC
(Supporting publications: ICML 2025, ACM MM 2025)

- **utomated Algorithm Design** (new research direction; related concurrent work includes Prof. Qingfu Zhang’s EOP algorithm at CityU):
Neural architecture design, adversarial attack design, training-free metric design, MPQ strategies, MoE decomposition algorithms, black-box optimization, optimizer design, automated software engineering, data augmentation strategy design, multimodal fusion strategies, attention mechanism design, model merging strategies, and interdisciplinary algorithm design for AI for Science
(Supporting publications: NeurIPS 2025, three papers under review at CVPR 2026, one planned submission to ICML 2026)

- **Collaborative Learning**: Large-model inference, distributed machine learning, federated learning, multi-task and continual learning, and model fusion
(Supporting publications: one paper under review at CVPR 2026, TNNLS 2025, two papers under review at ACL 2026, one planned submission to IJCAI 2026)

- **Trustworthy Artificial Intelligence**: Adversarial attacks and defenses, robust training, large-model attacks, AIGC detection, and biologically inspired dendritic neural network research and applications(Supporting publications: one paper under review at CVPR 2026)

I have published more than 15 papers at the top international AI conferences with total <a href='[https://scholar.google.com/citations?user=DhtAFkwAAAAJ](https://scholar.google.com/citations?user=NZqqv20AAAAJ&hl=en)'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='[https://scholar.google.com/citations?user=DhtAFkwAAAAJ](https://scholar.google.com/citations?user=NZqqv20AAAAJ&hl=en)'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

🔥 Our team is seeking self-motivated students (including remote internships, undergraduates, graduate students, and other candidates) to join research on above research direction with the goal of publishing high-quality academic papers. If interested, please email me your resume.



# 🔥 News
- *2025.12*: &nbsp;🎉🎉 Our one paper about MPQ is accepted to SCIS.
- *2025.11*: &nbsp;🎉🎉 Our one paper about NAS is accepted to AAAI 2026.
- *2025.11*: &nbsp;🎉🎉 Our one paper about LLMs's survey is accepted to TNNLS.
- *2025.10*: &nbsp;🎉🎉 Our one paper about NAS for few-shot leanring is accepted to SWEVO.
- *2025.09*: &nbsp;🎉🎉 Our one paper about LLMs is accepted to NeurIPS 2025.
- *2025.07*: &nbsp;🎉🎉 Our one paper about LLMs is accepted to ACM MM 2025.
- *2025.06*: &nbsp;🎉🎉 Our one paper about training-free NAS is accepted to ICCV 2025.
- *2025.05*: &nbsp;🎉🎉 Our one paper about few-shot learning is accepted to ICML 2025.
- *2025.04*: &nbsp;🎉🎉 Our one paper about few-shot learning is accepted to IJCAI 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/eop.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revolutionizing Training-Free NAS: Towards Efficient Automatic Proxy Discovery via Large Language Models](https://openreview.net/pdf?id=3naHyE5klE)

**HaidongKang^{*}**, Lihong Lin, Hanling Wang.

## Conference Papers

### CCF-A

-**<mark>ICML2026 </mark>** Changyu Li, Ming Lei, Haidong Kang*, Lijuan Shen, Xinyu Wang, Fei Luo*,  BARC: Coupling Budget-Adaptive Computation with Anytime-Valid e-Processes for Reliable Streaming Decisions,  ICML2026, under review. (CCF A)
- Haidong Kang*,Menghan Lu, Yifan Shen, xiaoming Yuan, Lihong Lin, Enneng Yang. Teaching LLMs to Think with Humans under Incomplete Information. ACL 2026, under review. (CCF A)
- Haidong Kang, Lianbo Ma*, Guo Yu, Guoyang Xie, Qing Li, Shangce Gao, Zhichao Lu. Understanding and Enhancing Mixed Precision Quantization Search on Target Hardware for Neural Network Accelerators. SCIS 2025. (CCF A, major revision) 
- Haidong Kang, Lihong Lin, Enneng Yang, Hong-Ning Dai, Hao Wang*. Breaking Expert Knowledge Limits: Self-Pruning for Large Language Models. CVPR 2026, under review. (CCF A) https://arxiv.org/abs/2511.15390 
- Kang, Haidong*, Wei Wu, Hanling Wang. Automatic Adversarial Attack Discovery for Few-Shot Class-Incremental Learning via Large Language Models. CVPR 2026. under review. (CCF A) https://arxiv.org/abs/2512.03882
- Haidong Kang*, Shuo Yin, Huiquan Zhang, Qihui Zhao, Yifan Shen, Taolin Zhang, Enneng Yang. Rethinking Open Set Domain Generalization: Learning to generalize via Conditional Diffusion Without Gradient. CVPR 2026, under review. (CCF A)
- Kang, Haidong*, Jun Du, Lihong Lin. Revolutionizing Mixed Precision Quantization: Towards Training-Free Automatic Proxy Discovery via Large Language Models. CVPR 2026. under review. (CCF A)
- Kang, Haidong*, Yi Lu, Ketong Qian. Breaking Forgetting: Training-Free Few-Shot Class-Incremental Learning via Conditional Diffusion. CVPR 2026. under review. (CCF A) https://arxiv.org/pdf/2511.18516
- Taolin Zhang, Kang, Haidong, Dongyang Li, Oizhou Chen, Chengyu Wang*, Xiaofeng He, Richang Hong*. QueueEDIT: Structural Self-Correction for Sequential Model Editing in LLMs. ACL 2026, under review. (CCF A) https://arxiv.org/pdf/2506.17864
- Haidong Kang*, Lihong Lin, etc. Unlocking the Potential of Continual Model Merging via LLMs-guiled Training-Free Proxy. IJCAI 2026, under review. (CCF A)
- Haidong Kang*, Lihong Lin, Enneng Yang, Han Yu, Li Shen, Dacheng Tao. Revolutionizing MoE-based LLMs: Towards Efficient Automatic Low-Rank Decomposition Discovery via Large Language Models. ICML2026, under review. (CCF A)
- Haidong Kang, Ma, Lianbo*, Pengjun Chen, etl. Understanding and Enhancing Differentiable Architecture Search From Information Bottleneck Perspective，AAAI 2026 (CCF A)
- Hanling Wang, Qing Li*, Li Chen, Haidong Kang, Fei Ma, Yong Jiang. HoloTrace: LLM-based Bidirectional Causal Knowledge Graph for Edge-Cloud Video Anomaly Detection. ACM Multimedia 2025.  (CCF A)
- Kang, Haidong*, Lihong Lin, Hanling Wang. Revolutionizing Training-Free NAS: Towards Efficient Automatic Proxy Discovery via Large Language Models.  The Thirty-ninth Annual Conference on Neural Information Processing Systems 2025.(CCF A)
- Haidong Kang, Ma, Lianbo*, Pengjun Chen, Guo Yu, Qing Li. Beyond the Limits: Overcoming Negative Correlations of Activation-Based Training-Free NAS, International Conference on Computer Vision (ICCV), Oct 19, 2025 - Oct 25, 2025, Honolulu, Hawaii.  (CCF A)
- Haidong Kang*. Revisiting Neural Networks for Few-Shot Learning: A Zero-Cost NAS Perspective.  The Forty-second International Conference on Machine Learning (ICML2025), July 13-19, 2025, Vancouver, Canada. (CCF A)
- Haidong Kang, Ma, Lianbo*, Guo Yu, Shangce Gao. Where and How to Enhance: Discovering Bit-Width Contribution for Mixed Precision Quantization.  The 34th International Joint Conference on Artificial Intelligence (IJCAI-25), August 16 to August 22, 2025, Montreal, Canada.  (CCF A)
- Lianbo Ma, Haidong Kang, Guo Yu*, Qing Li, Qiang He*, Single-Domain Generalized Predictor for Neural Architecture Search System, IEEE Transactions on Computers, 2024. (CCF A，ESI高被引)
- HL Wang, Q Li*, H Kang, etc. ParaLoupe: Real-time Video Analytics on Edge Cluster via Mini Model Parallelization,  IEEE Transactions on Mobile Computing. (CCF A)

### CCF-C
- Haidong Kang, etc. When NAS Meets Anomaly Detection: In Search of Resource-Efficient Architectures in Surveillance Video, IJCNN 2024. 
- Tain Zhang, Nan Li, Haidong Kang, etc. Neural Architecture Search Based on Brain Storm Optimization Algorithm for Face Detection, IJCNN 2024.  
- Pengjun Chen, Jian Gao, Haidong Kang, etc. MRT-NAS: Boosting Training-Free NAS via Manifold Regularization, ICANN2025.


## Journal Papers

1. Haidong Kang, Jianming Zhao, Shi Cheng, Kaizhou Gao, Yang Gao, Hongjiang Wang, Shangce Gao, and Lianbo Ma. Evolving Neural Network for Few-Shot Learning via Zero-Cost NAS. Swarm and Evolutionary Computation 2025. (SCI Q1)
2. Jian Cheng, Kang, Haidong, Yuxin Shao, Nan Li, Rui Wang, Saiqin Long, Xiaochun Yang, Lianbo Ma, Pengjun Chen. Survey on Large Language Model Inference Acceleration: Principles, Algorithms, Applications and Open Issues. IEEE TNNLS.(SCI Q1 TOP, equal contribution) https://ieeexplore.ieee.org/abstract/document/11247933/
3. Kang, Haidong* , etc. Enhancing Neural Networks for Diabetic Retinopathy Detection via Heterogeneous Wavelet Transform: An  Architecture Perspective. IEEE TNNLS, under review.  (SCI Q1)
4. Kang, Haidong*, etc. FSEW: A Real-World Few-Shot Benchmark for Extreme Weather Recognition. IEEE TIM, under review. (SCI Q1)
5. Kang, Haidong*, Yuxin Shao, etc. Designing Robust Genetic Programming for Feature Learning in Weak Image Classification, KBS, under review. (SCI Q1)



# 🎖 Honors and Awards
- *2024.10* National Scholarship (Top 1%)


# 📖 Educations
- *2021.09 - 2025.10 *, Ph.D. Student at Northeastern University, China


# 💬 Invited Talks
- *2025.12*, 
- *2025.10*,


# 💻 Services
- **Conference Reviewers**: NeurIPS 2024，ACM MM 2024，ICLR 2025，AISTATS 2025，CVPR 2025, ICML 2025，IJCAI2025, KDD 2025, ICCV 2025, NeurIPS 2025, ACM MM 2025,  AAAI2026, ACM TheWebConf2026, ICLR2026，cvpr26
- **Journal Reviewers**: TPAMI, TIP, IEEE TNNLS, IEEE Transactions on Circuits and Systems for Video Technology, Applied Intelligence，Signal, Image and Video Processing, KBS

