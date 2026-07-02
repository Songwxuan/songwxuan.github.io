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

I am Wenxuan Song (宋文轩), a second-year Ph.D. student in the ROAS Thrust at the Hong Kong University of Science and Technology (Guangzhou), advised by [Haoang Li](https://sites.google.com/view/haoangli/homepage). My research focuses on foundation models for embodied intelligence.
I have been conducting research in embodied intelligence and robot learning, with publications in top-tier venues including ICLR, ECCV, CVPR, and the IEEE Transactions series. So far, I have published 20 papers, including **10** first-author or co-first-author papers.

My work *ReconVLA: Reconstructive Vision–Language–Action Model as Effective Robot Perceiver* received the **AAAI 2026 Best Paper Award**. To the best of my knowledge, it is the first embodied AI work to receive a best paper award at a top-tier machine learning conference. This work also initiated the research direction of robot visual representation alignment. Follow-up work in this line, *Spatial Forcing*, was adopted in the runner-up solution of the IROS 2025 Agibot World Challenge and was later accepted to ICLR 2026. I was also honored as an ICML 2026 Gold Reviewer.

Beyond research, I am a co-founder of the open-source organization OpenHelix Team, where the repositories I have substantially led or contributed to have collectively gained over **4,000** GitHub stars. My work has been adopted in industrial models by companies such as Robbyant and Xiaomi, and has been widely recognized both in academia and industry. Related work has also been featured by MIT Technology Review.

Previously, I received my Bachelor's degree in Robotics at Harbin Institute of Technology (HIT), Weihai Campus, advised by Minghang Zhao and Bo Huang. I was also a visiting student at MiLab, Westlake University, supervised by Donglin Wang, and I have maintained close connections with [Pengxiang Ding](https://dingpx.github.io/) and [Han Zhao](https://h-zhao1997.github.io/), from whom I have learned a great deal. I also spent time at Monash University, supervised by Zongyuan Ge and Xuelian Cheng.

Goal: Advancing toward robotics' GPT-3.5 moment.

Focus: Building dexterous and generalizable robotic systems through **Vision-Language-Action** models and **world models**.

Email: songwenxuan0115 [AT] gmail.com

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🏆 Honors
- **<span style="color:red;">Best Paper Award</span>**, The 40th Annual AAAI Conference on Artificial Intelligence (AAAI-26), **(5/30948)**, 2026
- [**Champion**, ICRA-26 WBCD Competition (Deformable Track)](https://mp.weixin.qq.com/s/jJLwNItTH3EQKAnQdG4jlQ), 2026
- **Champion**, ICRA-26 WBCD Competition (Logistic Picking Track), 2026
- [**Innovibe Rising Star Award**, Beijing Academy of Artificial Intelligence (BAAI)](https://mp.weixin.qq.com/s/VwzvuyToY79B2DtWmenjVQ), **(20 selected annually)**, 2026
- [**Next-20 Award**, Embodied AI 100 in China](https://www.modelscope.cn/learn/6060), **(20 selected annually)**, 2026
- **Golden Reviewer**, International Conference of Machine Learning (ICML-26), 2026


# 🔥 Projects
- [Embodied-AI-Paper-TopConf](https://github.com/Songwxuan/Embodied-AI-Paper-TopConf) ![GitHub stars](https://img.shields.io/github/stars/Songwxuan/Embodied-AI-Paper-TopConf?style=social): We collect published papers in the field of embodied intelligence.
- [VLA-Adapter](https://github.com/OpenHelix-Team/VLA-Adapter) ![GitHub stars](https://img.shields.io/github/stars/OpenHelix-Team/VLA-Adapter?style=social): We propose a simple but effective VLA baseline.
- [OpenHelix](https://github.com/OpenHelix-robot/OpenHelix) ![GitHub stars](https://img.shields.io/github/stars/OpenHelix-robot/OpenHelix?style=social): We propose an open-source dual-system VLA model for robotic manipulation.

# 📝 Selected Publications 

- For full publications, please refer to my Google Scholar.

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">ECCV 2026</div>
      <video width="100%" autoplay loop muted playsinline>
        <source src="images/fast-dvla.mp4" type="video/mp4">
      </video>
    </div>
  </div>
  <div class='paper-box-text' markdown="1"> 

[Fast-dVLA: Accelerating Discrete Diffusion VLA to Real-Time Performance](https://arxiv.org/abs/2603.25661)

**Wenxuan Song**, **Jiayi Chen**, **Shuai Chen**, **Jingbo Wang**, **Pengxiang Ding**, **Han Zhao**, **Yikai Qin**, **Xinhu Zheng**, **Donglin Wang**, **Yan Wang**, **Haoang Li**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2026</div><img src='images/ceed-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

[CEED-VLA: Consistency Vision-Language-Action Model with Early-Exit Decoding](https://arxiv.org/pdf/2506.13725)

**Wenxuan Song**, **Jiayi Chen**, **Pengxiang Ding**, **Yuxin Huang**, **Han Zhao**, **Yinchuan Li**, **Ying-Cong Chen**, **Donglin Wang**, **Haoang Li**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/spatial_forcing.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Spatial Forcing: Implicit Spatial Representation Alignment for Vision–Language–Action Models](#)

**Fuhao Li\***, **Wenxuan Song\***, Han Zhao, Jingbo Wang, Pengxiang Ding, Donglin Wang, Long Zeng, Haoang Li

*\* denotes equal contribution, ‡ denotes project lead*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/udvla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unified Diffusion VLA: Vision–Language–Action Model via Joint Discrete Denoising Diffusion Process](#)

**Jiayi Chen**, **Wenxuan Song**, Pengxiang Ding, Ziyang Zhou, Han Zhao, Feilong Tang, Donglin Wang, Haoang Li

*\* denotes equal contribution, ‡ denotes project lead*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 (Best Paper)</div><img src='images/reconvla.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 


[ReconVLA: Reconstructive Vision\textendash Language\textendash Action Model as Effective Robot Perceiver](https://zionchow.github.io/ReconVLA/)

**Wenxuan Song**, Ziyang Zhou, Han Zhao, Jiayi Chen, Pengxiang Ding, Haodong Yan, Yuxin Huang, Feilong Tang, Donglin Wang, Haoang Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 (Oral)</div><img src='images/vla_adapter.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VLA-Adapter: An Effective Paradigm for Tiny-Scale Vision–Language–Action Models](#)

Yihao Wang, Pengxiang Ding, Lingxiao Li, Can Cui, Zirui Ge, Xinyang Tong, **Wenxuan Song**, Han Zhao, Wei Zhao, Pengxu Hou, Siteng Huang, Yifan Tang, Wenhui Wang, Ru Zhang, Jianyi Liu, Donglin Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2026</div><img src='images/llava_vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking the Practicality of Vision–Language–Action Models: A Comprehensive Benchmark and an Improved Baseline](#)

**Wenxuan Song**, Jiayi Chen, Xiaoquan Sun, Huashuo Lei, Yikai Qin, Wei Zhao, Pengxiang Ding, Han Zhao, Tongxin Wang, Pengxu Hou, Zhide Zhong, Haodong Yan, Donglin Wang, Jun Ma, Haoang Li

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TRO</div><img src='images/flowvla_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

[FlowVLA: Thinking in Motion with a Visual Chain of Thought](https://irpn-lab.github.io/FlowVLA/)

**Zhide Zhong**, **Haodong Yan**, **Junfeng Li**, **Xiangchen Liu**, **Xin Gong**, **Wenxuan Song**, **Jiayi Chen**, **Haoang Li**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS2025</div><img src='images/PD-VLA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PD-VLA: Accelerating Vision-Language-Action Model Integrated with Action Chunking via Parallel Decoding](https://arxiv.org/pdf/2503.02310)

**Wenxuan Song**, **Jiayi Chen**, **Pengxiang Ding**, **Han Zhao**, **Wei Zhao**,**Zhide Zhong**, **Zongyuan Ge**, **Jun Ma**, **Haoang Li**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/openhelix.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

[OpenHelix: A Short Survey, Empirical Analysis, and Open-Source Dual-System VLA Model for Robotic Manipulation](https://openhelix-robot.github.io/)

**Can Cui**, **Pengxiang Ding**, **Wenxuan Song**, **Shuanghao Bai**, **Xinyang Tong**, **Zirui Ge**, **Runze Suo**,  
**Wanqi Zhou**, **Yang Liu**, **Bofang Jia**, **Han Zhao**, **Siteng Huang**, **Donglin Wang**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/ASME Transactions on Mechatronics (TMech)</div><img src='images/rational-vla.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RationalVLA: A Rational Vision-Language-Action Model with Dual System](https://arxiv.org/pdf/2506.10826)

**Wenxuan Song**, **Jiayi Chen**, **Wenxue Li**, **Xu He**, **Han Zhao**, **Can Cui**, **Pengxiang Ding**, **Shiyan Su**, **Feilong Tang**, **Donglin Wang**, **Xuelian Cheng**, **Zongyuan Ge**, **Xinhu Zheng**, **Zhe Liu**, **Hesheng Wang**, **Haoang Li**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2025</div><img src='images/more.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

[MoRE: Unlocking Scalability in Reinforcement Learning for Quadruped Vision-Language-Action Models](https://arxiv.org/abs/2503.08007)

**Han Zhao**, **Wenxuan Song**, **Donglin Wang**, **Xinyang Tong**, **Pengxiang Ding**, **Xuelian Cheng**, **Zongyuan Ge**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2024</div><img src='images/germ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 

[GeRM: A Generalist Robotic Model with Mixture-of-experts for Quadruped Robots](https://songwxuan.github.io/GeRM/)

**Wenxuan Song**, **Han Zhao**, **Pengxiang Ding**, **Can Cui**, **Shangke Lyu**, **Yaning Fan**, **Donglin Wang**  

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/quart.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> 
  
[QUAR-VLA: Vision-Language-Action Model for Quadruped Robots](https://quart-robot.github.io/)

**Pengxiang Ding**, **Han Zhao**, **Wenxuan Song**, **Wenjie Zhang**, **Min Zhang**, **Siteng Huang**, **Ningxi Yang**, **Donglin Wang**

</div>
</div>
  
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- *2023.06 - 2025.06 (now)*, Pursuing a Master's degree in Computer Science and Technology at Harbin Institute of Technology.
- *2019.09 - 2023.06*, Studied Automation at Tongji University and obtained a Bachelor's degree in Engineering. -->

# 💬 Invited Talks
- Invited talks at the **Pine Lab, Nanyang Technological University** (group led by Prof. Ziwei Wang),  
**AIR, Tsinghua University** (group led by Prof. Yan Wang),  
**Auto Lab, Shanghai Jiao Tong University** (group led by Prof. Zhipeng Zhang),  
**Zhejiang University** (group led by Prof. Chunhua Shen),  
**The Hong Kong University of Science and Technology (Guangzhou)** (group led by Prof. Jia Li),  
and the **BAAI Innovation Center**, among others.

