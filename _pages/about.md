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

Hi! My name is Mingsheng Li (中文名: 李铭晟). I am currently a second-year Master's student in Artificial Intelligence at Fudan University, advised by Prof. [Tao Chen](https://eetchen.github.io/). I am also fortunate to work closely with Dr. [Hongyuan Zhu](https://hongyuanzhu.github.io/) from A*STAR, Singapore, Dr. [Gang Yu](https://www.skicyyu.org/), Dr. [Xin Chen](https://chenxin.tech/), and Dr. [Chi Zhang](https://icoz69.github.io/) from Tencent, and research scientist [Sijin Chen]([https://eetchen.github.io/](https://ch3cook-fdu.github.io/)) from ByteDance Research. Before this, I received my bachelor’s degree in Electronic Engineering from Fudan University in 2022.



I work in the fields of deep learning and computer vision, with particular focuses on *large models*, *multi-modal learning* and *embodied AI*. My research pursues to develop robust and scalable general-purpose AI systems to solve complex problems. 

📣 <font color="#dd0000">I am actively looking for researcher / Ph.D. opportunities.</font> Please check out my resume [here](resume/Mingsheng Li's Resume.pdf).

<!-- 📣 <font color="#dd0000">I am actively looking for researcher / Ph.D. opportunities.</font> -->

# 🔥 News
- *Jul. 2024*. &nbsp;🎉🎉 [M3DBench](https://arxiv.org/abs/2312.10763) is accepted to ECCV 2024!
- *Jun. 2024*. &nbsp;🚀🚀 We release [WI3D](papers/WI3D__Weakly_Incremental_3D_Detection_via_vision_Foundation_Models.pdf), the first approach that can generalize well-trained 3D detectors to learn novel classes with the aid of foundation models.
- *Jun. 2024*. &nbsp;🎉🎉 Our [LGD](https://arxiv.org/abs/2406.11689), a new method for lightweight model pre-training, is accepted to <font color="#dd0000">T-MM 2024</font>. [Code](https://github.com/mZhenz/LGD) is released now!
- *Apr. 2024*. &nbsp;🎉🎉 Our state-of-the-art 3D dense captioning method [Vote2Cap-DETR++](https://arxiv.org/abs/2309.02999) [![](https://img.shields.io/github/stars/ch3cook-fdu/Vote2Cap-DETR?style=social)](https://github.com/ch3cook-fdu/Vote2Cap-DETR), is accepted to <font color="#dd0000">T-PAMI 2024</font>.
- *Jul. 2024*. &nbsp;🚀🚀 We release [M3DBench](https://arxiv.org/abs/2312.10763) [![](https://img.shields.io/github/stars/OpenM3D/M3DBench?style=social)](https://github.com/OpenM3D/M3DBench), a new 3D instruction-following dataset with interleaved multi-modal prompts and a new benchmark to assess large models across 3D vision-centric tasks.
- *Feb. 2024*. &nbsp;🎉🎉 Our Large Language 3D Assistant, [LL3DA](https://arxiv.org/abs/2311.18651) [![](https://img.shields.io/github/stars/Open3DA/LL3DA?style=social)](https://github.com/Open3DA/LL3DA), is accepted to <font color="#dd0000">CVPR 2024</font>. 





# 📝 Recent Works

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/wi3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>WI3D: Weakly Incremental 3D Detection via Vision Foundation Models</font>**](papers/WI3D__Weakly_Incremental_3D_Detection_via_vision_Foundation_Models.pdf) \\
**<font color="#dd0000">Under Review</font>** \\
**<u>Mingsheng Li</u>**, Sijin Chen, Shengji Tang, Hongyuan Zhu, Yanyan Fang, Xin Chen, Zhuoyuan Li, Fukun Yin, Gang Yu, Tao Chen

[paper](papers/WI3D__Weakly_Incremental_3D_Detection_via_vision_Foundation_Models.pdf)

- Introducing new categories to well-trained 3D detectors with 2D foundation models.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/m3dbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts</font>**](https://arxiv.org/abs/2311.18651) \\
**<font color="#dd0000">ECCV 2024</font>** | [![](https://img.shields.io/github/stars/OpenM3D/M3DBench?style=social)](https://github.com/OpenM3D/M3DBench) \\
**<u>Mingsheng Li</u>**, Xin Chen, Chi Zhang, Sijin Chen, Hongyuan Zhu, Fukun Yin, Gang Yu, Tao Chen

[project](https://m3dbench.github.io/) \| [arXiv](https://arxiv.org/abs/2312.10763) \| [github](https://github.com/OpenM3D/M3DBench) 

- Propose a comprehensive 3D instruction-following dataset with support for interleaved multi-modal prompts.
- Provide a new benchmark to assess large models across 3D vision-centric tasks.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2024</div><img src='images/lgd.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>Lightweight Model Pre-training via Language Guided Knowledge Distillation</font>**](https://arxiv.org/abs/2406.11689) \\
**<font color="#dd0000">T-MM 2024</font>** \\
**<u>Mingsheng Li</u>**, Lin Zhang, Mingzhen Zhu, Zilong Huang, Gang Yu, Jiayuan Fan, Tao Chen

[paper](https://ieeexplore.ieee.org/document/10551493) \| [arXiv](https://arxiv.org/abs/2406.11689) \| [github](https://github.com/mZhenz/LGD)

- Language-guided distillation enhances model pre-training.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-PAMI 2024</div><img src='images/vote2cap-detr++ arXiv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>Vote2Cap-DETR++: Decoupling Localization and Describing for End-to-End 3D Dense Captioning</font>**](https://arxiv.org/abs/2309.02999) \\
**<font color="#dd0000">T-PAMI 2024</font>** | [![](https://img.shields.io/github/stars/ch3cook-fdu/Vote2Cap-DETR?style=social)](https://github.com/ch3cook-fdu/Vote2Cap-DETR) \\
Sijin Chen, Hongyuan Zhu, **<u>Mingsheng Li</u>**, Xin Chen, Peng Guo, Yinjie Lei, Gang Yu, Taihao Li, Tao Chen

[paper](https://ieeexplore.ieee.org/abstract/document/10496863/) \| [arXiv](https://arxiv.org/abs/2309.02999) \| [github](https://github.com/ch3cook-fdu/Vote2Cap-DETR)

- Decoupled feature extraction and task decoding for 3D Dense Captioning.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/LL3DA.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**<font size=4>LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning</font>**](https://arxiv.org/abs/2311.18651) \\
**<font color="#dd0000">CVPR 2024</font>** | [![](https://img.shields.io/github/stars/Open3DA/LL3DA?style=social)](https://github.com/Open3DA/LL3DA) \\
Sijin Chen, Xin Chen, Chi Zhang, **<u>Mingsheng Li</u>**, Gang Yu, Hao Fei, Hongyuan Zhu, Jiayuan Fan, Tao Chen

[project](https://ll3da.github.io/) \| [arXiv](https://arxiv.org/abs/2311.18651) \| [github](https://github.com/Open3DA/LL3DA) \| [youtube](https://www.youtube.com/watch?v=224JzkdHjfg)

- Propose a Large Language 3D Assistant that responds to both visual interactions and textual instructions in complex 3D environments.
</div>
</div>



# 🥇 Awards and Scholarships

- *2023*. **2nd** Prize of Graduate Academic Scholarship. 
- *2022*. **Outstanding Graduate** of Fudan University.
- *2020*. **2nd** Prize of China Undergraduate Mathematical Contest in Modeling.
- *2020*. **STEM** (Science, Technology, Engineering, Mathematics) Scholarship.
- *2019*. **1st** Prize of Chinese Mathematics Competitions (Top 20).
- *2019*. **National Encouragement Scholarship**.




# 📖 Educations

- *Sep. 2022 - Jun. 2025 (expected)*. Master student at Fudan University. 
- *Sep. 2018 - Jun. 2022*. Bachelor student at Fudan University. 




<!-- # 💬 Oral Presentations

- *Oct. 2023*. Winner presentation of the Scan2Cap Challenge in the 3rd Language for 3D Scene Workshop at **<font color="#dd0000">ICCV 2023</font>**. \[[talk](https://www.youtube.com/watch?v=RLrdi-Yhn1o) \| [slides](presentation/[ICCV 2023 workshop talk] Vote2Cap-DETR.pdf)\]
- *Jun. 2023*. Paper presentation for "*End-to-End 3D Dense Captioning with Vote2Cap-DETR*" at the Workshop for Advances in 3D Vision, **<font color="#dd0000">VALSE 2023</font>**, Wuxi, China. -->



<!-- # 💻 Internships

- *2020.07 - 2020.10*. Huawei Technologies Shanghai R&D Center, Shanghai, China. -->
