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

Hi, I am Zihang. I am a researcher at [UC Berkeley](https://eecs.berkeley.edu/) and [International Computer Science Institute](https://www.icsi.berkeley.edu/), advised by [Prof. Michael Mahoney](https://www.stat.berkeley.edu/~mmahoney/). I also have the privilege to work closely with [Prof. Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/) from [Dartmouth College](https://web.cs.dartmouth.edu/). I previously obtained my Master's degree in [EECS](https://eecs.berkeley.edu/) at UC Berkeley.

**My research focus** is to understand and improve the **transparency and efficiency of learning models**. I am particularly interested in understanding phenomena such as low-rank structures, sparsity, and the geometry of weight matrices in deep learning models, with inspirations from high-dimensional statistics, random matrix theory and randomized linear algebra. I also use these techniques in discovering new (numerical) algorithms.


<!-- Previous versions -->
<!-- My research focus is to improve the robustness and efficiency of learning models from the perspectives of weight matrices, high-dimensional feature space, and loss landscapes. I also use these techniques in applications like vision and scientific problems. -->


<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.06*: &nbsp; Started my research engineer position at [ICSI](https://www.icsi.berkeley.edu/), UC Berkeley, to work on numerical algorithm discovery with deep learning.
- *2025.05*: &nbsp; Our paper "Principal Weights Emerge after Rank Reduction for Reasoning-Focused Supervised Fine-Tuning" has been accepted to [ICML 2025](https://icml.cc/Conferences/2025).
- *2024.11*: &nbsp; Gave a presentation at EMNLP 2024 on [foundation model diagnosis](https://aclanthology.org/2024.emnlp-main.78/), check out the live recording [here](https://us06web.zoom.us/rec/play/5RHeJiEVuG-yw_Ytt9cHPMzqEIm2xWenwjhHjJ4yt7camtmQObTndJ56YgBBw0A1TlNRGiwZ2MAw5klz.7Xm2WgzcHdxPjGqm?autoplay=true).
- *2024.09*: &nbsp; Excited to share that our work "Model Balancing Helps Low-data Training and Fine-tuning" is accepted by [EMNLP 2024](https://2024.emnlp.org/) as **Oral Presentation**.

# 📝 Publications 

Authors within {} are equal contributors.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/ICML_LIFT_teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LIFT the Veil for the Truth: Principal Weights Emerge after Rank Reduction for Reasoning-Focused Supervised Fine-Tuning**

**Zihang Liu**, [Tianyu Pang](https://tdcsz327.github.io/), [Oleg Balabanov](https://obalabanov.github.io/), [Chaoqun Yang](), [Tianjin Huang](https://tianjinyellow.github.io/), [Lu Yin](https://luuyin.com/), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/), [Shiwei Liu](https://shiweiliuiiiiiii.github.io/)

[**Paper**](https://arxiv.org/abs/2506.00772) \| [**Code**](https://github.com/zihanghliu/LIFT)

**ICML 2025**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/EMNLP_2024_Teaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Model Balancing Helps Low-data Training and Fine-tuning**

\{**Zihang Liu**\*, [Yuanzhe Hu](https://hust-ai-hyz.github.io/)\*\}, [Tianyu Pang](https://tdcsz327.github.io/), [Yefan Zhou](yefanzhou.github.io), [Pu Ren](https://paulpuren.github.io/), [Yaoqing Yang](https://sites.google.com/site/yangyaoqingcmu/)

[**Paper**](https://arxiv.org/abs/2410.12178) \| [**Code**](https://github.com/ZihangHLiu/ModelBalancing) \| [**Video**](https://drive.google.com/file/d/1JtYKVhZBslAEZUrH6Z7UEVCq-1cSz1Ot/view?usp=sharing)

**EMNLP 2024 <span style="color:red">Oral</span>**

</div>
</div>

<!-- # Acknowledgements
I am extremely fortunate to work with and learn from many great researchers and mentors. In addition to my supervisors, I would like to thank the following researchers for their guidance and support (in alphabetical order of last name): [Oleg Balabanov](https://obalabanov.github.io/), [Yuanzhe Hu](https://hust-ai-hyz.github.io/), [Tianyu Pang](https://tdcsz327.github.io/), [Pu Ren](https://paulpuren.github.io/), [Yefan Zhou](https://yefanzhou.github.io/). -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->