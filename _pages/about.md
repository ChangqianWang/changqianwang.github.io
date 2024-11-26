---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Changqian Wang! Currently, I am a third-year master's student at Anhui University, under the guidance of Associate Professor [Haiping Ma](https://wky.ahu.edu.cn/2024/0228/c13481a329961/page.htm) and affiliated to the [BIMK](https://bimk.ahu.edu.cn/) Lab. My research interests are data mining and intelligent education, including cognitive diagnosis and computerized adaptive testing. I prefer to seek PhD opportunity after my Master study.

Interests
=======
I have a passion for photography. Currently, I am a contracted photographer for multiple platforms, including DJI(大疆) and [Visual China(视觉中国)](https://500px.com.cn/wcq206). My works have been selected by Chinese National Geography and published in several official media outlets. 
<!-- You can view my photography portfolio under the 'Photography' section in the navigation bar. -->

<!-- Besides that, I have a strong passion for football, and Dalian Professional Football Club is my favorite team. -->

News
=======
1. 2024-9-24: China National Scholarship
2. 2024-1-14: 2023 First Class Scholarship of BIMK Lab (Second place in the year-end assessment).
3. 2023-12-9: One paper([CMES](https://arxiv.org/abs/2312.10110)) accepted in AAAI2024.

<!-- 4. 2023-5-17: Attend the [CCF YOCSEF](https://www.ccf.org.cn/Media_list/YEF/2023-05-19/791750.shtml) conference held in Wenzhou. -->

Publications
=======
<!-- <hr> -->
<!-- **Conference Papers** -->

1. Haiping Ma, Aoqing Xia, **Changqian Wang**, Hai Wang, Xingyi Zhang, <u>"Diffusion-Inspired Cold Start with Sufficient Prior in Computerized Adaptive Testing"</u>, *Proceedings of the 31th SIGKDD Conference on Knowledge Discovery and Data Mining (KDD-2025)*, 2025 [[paper](https://arxiv.org/abs/2411.12182)]
2. Haiping Ma, **Changqian Wang**, Hengshu Zhu, Shangshang Yang, Xiaoming Zhang, Xingyi Zhang, <u>"Enhancing Cognitive Diagnosis using Un-interacted Exercises: A Collaboration-aware Mixed Sampling Approach"</u>, *In Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI-2024)*, 2024 [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/28735)]

<!-- <hr> -->
<!--**Journal Papers** -->

<!-- 1. Coming Soon~ -->
<!-- 2. Coming Soon~ -->

<!-- Awards
=======

1. Coming Soon~
2. Coming Soon~

Academic Services
=======

1. Coming Soon~
2. Coming Soon~ -->

Latest Work Introduction
=======
<hr>
**1. Diffusion-Inspired Cold Start with Sufficient Prior in Computerized Adaptive Testing (KDD2025)**

Computerized Adaptive Testing (CAT) aims to select the most appropriate questions based on the examinee's ability and is widely used in online education. However, existing CAT systems often lack initial understanding of the examinee's ability, requiring random probing questions. In response to this gap, we propose Diffusion Cognitive States TransfeR Framework (DCSR), a novel domain transfer framework based on Diffusion Models (DMs) to address the CSIP task. Specifically, we construct a cognitive state transition bridge between domains, guided by the common cognitive states of examinees, encouraging the model to reconstruct the initial ability state in the target domain. To enrich the expressive power of the generated data, we analyze the causal relationships in the generation process from a causal perspective. Redundant and extraneous cognitive states can lead to limited transfer and negative transfer effects. Our DCSR can seamlessly apply the generated initial ability states in the target domain to existing question selection algorithms, thus improving the cold start performance of the CAT system.

![CMES](/models/dcsr.png)

<hr>
**2. Enhancing Cognitive Diagnosis using Un-interacted Exercises: A Collaboration-aware Mixed Sampling Approach (AAAI2024)**

Cognitive diagnosis is a crucial task in intelligent education, aiming to diagnose students' proficiency in specific knowledge concepts through their answer records. Extracting information from non-interactive exercises and designing potential answer labels for students pose significant challenges, to address them, we innovatively proposed the Collaborative Perception Mixed Exercise Sampling (CMES) framework. Specifically, we cluster students based on their answering abilities and collaborative relationships, sampling exercises from sets interacted with by students from other clusters. Given the rich diagnostic information in interactive exercises and the diverse information inherent in non-interactive exercises, we employ a mixture technique to fuse the information of sampled exercises with that of interactive exercises, obtaining more information-rich samples. Finally, we design an unfed module based on ranking learning to assign potential answer labels to the fused samples.

![CMES](/models/cmes.png)
