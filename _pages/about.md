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

I am a first-year Ph.D. student at the ROAS Thrust at the Hong Kong University of Science and Technology (HKUST), Guangzhou campus, advised by [Haoang Li](https://sites.google.com/view/haoangli/homepage). I received my Bachelor's degree in robotics at Harbin Institute of Technology (HIT), Weihai Campus, advised by Minghang Zhao and Bo Huang. I was a visiting student at MiLab, Westlake University, supervised by Donglin Wang. I keep a close connection with [Pengxiang Ding](https://dingpx.github.io/) and [Han Zhao](https://h-zhao1997.github.io/) from then on, who have been teaching me a lot. I also spent time at Monash University, supervised by Zongyuan Ge and Xuelian Cheng.

Goal: Robots that improve everyone's life.

Focus: How to build the data flywheel for robotics to unlock human-level athletic skills and semantic intelligence? How to make robots perform useful tasks with adaptability, generalizability, agility, and safety?

Method: Utilizing learning-based methods that scale with computation and data.

Robots: I love working on humanoids and aim to make them capable of doing everything I can do—and more.

Email: tairanh [AT] andrew.cmu.edu

I am jiayi Chen, a graduate in Automation from Tongji University (Class of 2019). Currently, I am pursuing my Master’s in Computer Science and Technology at Harbin Institute of Technology (HIT). Meanwhile, I serve as a Research Assistant  at the IRPN Lab, Systems Hub, Hong Kong University of Science and Technology (Guangzhou), where my research focuses on Embodied Intelligence.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.06*: &nbsp;🎉 ["Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding"](https://arxiv.org/abs/2503.02310) is accepted by IROS2025.
- *2025.05*: &nbsp;🎉 Our GitHub repository([Embodied-AI-Paper-TopConf
](https://github.com/Songwxuan/Embodied-AI-Paper-TopConf)), which collects academic papers in the field of embodied intelligence, has garnered over 300 stars. 

- *2025.06*: &nbsp;🎉 Our open-source project [LLaVA-VLA](https://github.com/OpenHelix-Team/LLaVA-VLA), a Vision-Language-Action model built upon the popular open-source VLM LLaVA, has received over 70 stars.
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS2025</div><img src='images/PD-VLA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding](https://arxiv.org/pdf/2503.02310)


**Wenxuan Song¹\***, **Jiayi Chen¹\***, **Pengxiang Ding²˒³**, **Han Zhao²˒³**, **Wei Zhao²**,**Zhide Zhong¹**,  **Zongyuan Ge⁴**, **Jun Ma¹**,  **Haoang Li¹‡**

<small>¹ IRPN Lab, HKUST(GZ) ² MiLab, Westlake University ³ Zhejiang University ⁴ Monash University</small>  
<!-- <small>* Equal Contribution  † Project Leader  ‡ Corresponding Author</small> -->

We propose parallel decoding framework for VLA models integrated with action chunking. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/rational-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RationalVLA: A Rational Vision-Language-Action Model with Dual System](https://arxiv.org/pdf/2506.10826)

**Wenxuan Song, Jiayi Chen, Wenxue Li, Xu He, Han Zhao, Can Cui, Pengxiang Ding, Shiyan Su, Feilong Tang,Donglin Wang, Xuelian Cheng, Zongyuan Ge, Xinhu Zheng, Zhe Liu, Hesheng Wang, Haoang Li**

<!-- <small>¹ IRPN Lab, HKUST(GZ) ² MiLab, Westlake University ³ Zhejiang University</small>   -->
<!-- <small>* Equal Contribution  † Project Leader  ‡ Corresponding Author</small> -->
- We introduce a new benchmark, the Rational Manipula-tion (RAMA) with defective instructions in 6 dimensions.
- We propose Rational Vision-Language-Action model (RationalVLA). It is a dual system for the robotic armto perceive the environment, handle unseen and defective instructions effectively, and demonstrate performant manipulation capabilities. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/ceed-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CEED-VLA: Consistency Vision-Language-Action Model with Early-Exit Decoding](https://arxiv.org/pdf/2506.13725)

**Wenxuan Song¹\***, **Jiayi Chen¹\***, **Pengxiang Ding²˒³†**, **Yuxin Huang¹**, **Han Zhao²˒³**, **Donglin Wang²**,  **Haoang Li¹‡**

<small>¹ IRPN Lab, HKUST(GZ) ² MiLab, Westlake University ³ Zhejiang University</small>  

<!-- **Wenxuan Song¹\***, **Jiayi Chen¹\***, **Pengxiang Ding²˒³**, **Han Zhao²˒³**, **Wei Zhao²**,**Zhide Zhong¹**,  **Zongyuan Ge⁴**, **Jun Ma¹**,  **Haoang Li¹‡**

<small>¹ IRPN Lab, HKUST(GZ) ² MiLab, Westlake University ³ Zhejiang University ⁴ Monash University</small>   -->
<!-- <small>* Equal Contribution  † Project Leader  ‡ Corresponding Author</small> -->
- Wepropose CEED-VLA, a universal acceleration method for significant inference speedup while maintaining manipulation performance.
- We conduct a consistency distillation process to unlock the model’s capabilities of fast inference.
- We identify the inefficient iteration as the bottleneck of Jacobi decoding’s speedup and propose the early-exit decoding to solve it.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.06 - 2025.06 (now)*, Pursuing a Master's degree in Computer Science and Technology at Harbin Institute of Technology.
- *2019.09 - 2023.06*, Studied Automation at Tongji University and obtained a Bachelor's degree in Engineering.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.2 - 2024.06*, IO Intelligence, China.
