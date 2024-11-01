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

I am a third-year Ph.D. student in the State Key Laboratory of Information Engineering in Surveying, Mapping, and Remote Sensing, Wuhan University. My advisors are Prof. [Hongyan Zhang](https://scholar.google.com/citations?user=fq7Uqx0AAAAJ&hl=en&oi=ao), Prof. [Wei He](https://prowdiy.github.io/weihe.github.io/), and Prof. [Liangpei Zhang](https://scholar.google.com/citations?user=vzj2hcYAAAAJ&hl=en&oi=ao). I received my B.S. degree in communication engineering in 2020 from Wuhan University. I am currently pursuing a Ph. D. degree and plan to graduate in June 2025. **It has been confirmed that I will join Duke University, USA for my postdoc career in 2025 fall, working with [Prof. Qiu Tong](https://scholar.google.com/citations?user=4JCY7mIAAAAJ&hl=en) and [Prof. James S Clark](https://scholar.google.com/citations?user=t6XVnH8AAAAJ&hl=zh-CN)**

My research interest includes weakly-supervised semantic segmentation, land cover mapping, and large-scale Earth observation applications. 

Email: **ashelee@whu.edu.cn**

# 🔥 News
- *2024.Nov.*: &nbsp;🎉 I got the Postdoc offer from Duke University.  
- *2024.Apr.*: &nbsp;🎉 We won first place in the CVPR 2024 OpenEarthMap Land Cover Mapping challenge. 
- *2024.Apr.*: &nbsp;🎉 The SegLand has been accepted by CVPR 2024 L3D-LIV Workshop.
- *2024.Apr.*: &nbsp;🎉 The Paraformer has been posted as **Highlight** in CVPR 2024.
- *2024.Feb.*: &nbsp;🎉 The Paraformer has been accepted by CVPR 2024 with a score of 5/5/4. 
- *2023.June*: &nbsp;🎉 The SinoLC-1 has been downloaded over 100,000 times. 
- *2023.Mar.*: &nbsp;🎉 SinoLC-1: The first 1-meter resolution national-scale land-cover map of China has been open-accessed.

# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2024</div><img src='images/CVPRW_Paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Generalized Few-Shot Meets Remote Sensing: Discovering Novel Classes in Land Cover Mapping via Hybrid Semantic Segmentation Framework]([https://arxiv.org/pdf/2404.12721])

[**Code and data**](https://github.com/LiZhuoHong/SegLand/)

**Zhuohong Li**, Fangxiao Lu, Jiaqi Zou, Lei Hu, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Learning Without Exact Guidance: Updating Large-scale High-resolution Land Cover Maps from Low-resolution Historical Labels **(Highlight)**](https://arxiv.org/abs/2403.02746)
  
[**Code and data**](https://github.com/LiZhuoHong/Paraformer/) - score:5/5/4.

**Zhuohong Li**, Wei He, Jiepan Li, Fangxiao Lu, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESSD 2023</div><img src='images/SinoLC-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[SinoLC-1: the first 1-meter resolution national-scale land-cover map of China created with the deep learning framework and open-access data **(SCI Q1 TOP, IF=11.4)**](https://essd.copernicus.org/preprints/essd-2023-87/)
  
[**Data download**](https://zenodo.org/record/8105314) - 102,080 Download.

**Zhuohong Li**, Wei He, Mofan Cheng, Jingxin Hu, Guangyi Yang, Hongyan Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS 2022</div><img src='images/L2HNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Breaking the resolution barrier: A low-to-high network for large-scale high-resolution land-cover mapping using low-resolution labels **(SCI Q1 TOP, IF=12.7)**](https://www.sciencedirect.com/science/article/abs/pii/S0924271622002180)
  
**Zhuohong Li**, Hongyan Zhang, Fangxiao Lu, Ruoyao Xue, Guangyi Yang, Liangpei Zhang

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JSTARS 2021</div><img src='images/JSTARS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[The Outcome of the 2021 IEEE GRSS Data Fusion Contest—Track MSD: Multitemporal Semantic Change Detection **(SCI Q2, IF=5.5)**](https://ieeexplore.ieee.org/document/9690575)

**Zhuohong Li**, Fangxiao Lu, Hongyan Zhang, ..., Naoto Yokoya
</div>
</div>
- [Change Cross-Detection Based on Label Improvements and Multi-Model Fusion for Multi-Temporal Remote Sensing Images](https://ieeexplore.ieee.org/abstract/document/9553120), Zhuohong Li, Fangxiao Lu, Hongyan Zhang, Guangyi Yang, Liangpei Zhang, **IGRASS 2020**
- [Multi-stage pseudo-label iteration framework for semi-supervised land-cover mapping](https://ieeexplore.ieee.org/abstract/document/9884345), Zhuohong Li, Jiaqi Zou, Fangxiao Lu, Hongyan Zhang, **IGRASS 2021**
- [Simultaneous Update of High-Resolution Land-Cover Mapping Attempt: Wuhan and the Surrounding Satellite Cities Cartography Using L2HNet](https://arxiv.org/pdf/2303.05305.pdf), Yan Huang, Yuqing Wang, Zhanbo Li, Zhuohong Li, Guangyi Yang, **JSTARS 2023**
- [National-scale 1-m resolution land-cover mapping for the entire China based on a low-cost solution and open-access data](https://arxiv.org/pdf/2303.05305.pdf), Zhuohong Li, Wei He, Hongyan Zhang, **Arxiv**


# 🎖 Honors and Awards
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">First place</div><img src='images/CVPR-1st.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[First place: 2024 CVPR OpenEarthMap Land Cover Mapping Challange](https://codalab.lisn.upsaclay.fr/competitions/17568#participate)
  

**Zhuohong Li**, Fangxiao Lu, Jiaqi Zou, Lei Hu, Hongyan Zhang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">First place</div><img src='images/2021DFC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[First place: 2021 IEEE GRSS Data Fusion Contest—Track MSD: Multitemporal Semantic Change Detection](https://ieeexplore.ieee.org/abstract/document/9553120)
  

**Zhuohong Li**, Fangxiao Lu, Hongyan Zhang, ..., Liangpei Zhang
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Second place</div><img src='images/DFC2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Second place: 2022 IEEE GRSS Data Fusion Contest—Track SLM: Semi-supervised Learning for Land Cover Classification](https://ieeexplore.ieee.org/abstract/document/9884345)
  

**Zhuohong Li**, Jiaqi Zou, Fangxiao Lu, Hongyan Zhang

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Second place</div><img src='images/whisper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Second place: 2023 Cross-city Multimodal Semantic Segmentation Challenge of WHISPER


Jiaqi Zou，**Zhuohong Li**, Fangxiao Lu, Wei He, Hongyan Zhang
</div>
</div>

- *2020* Third place: 2020 Gaofen challenge—Track: Remote-sensing image semantic segmentation 
- *2019* The first prize: China National Undergraduate Electronics Design Contest. 
- *2018* The second prize: China National Undergraduate Embedded Chip and System Design Competition. 
- *2023* The second prize: China National University Students’Opt-Sci-Tech Competition. 

# 💬 Conference oral presentation
- *2024*, The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2024, Seattle, USA.
- *2023*, IEEE 11th International Conference on Agro-Geoinformatics, Wuhan, China.
- *2022*, IEEE International Geoscience and Remote Sensing Symposium (IGRASS), Kuala Lumpur, Malaysia.
- *2022*, Geography of China Information Science Theory and Method Annual Conference, Hangzhou, China.
- *2021*, IEEE International Geoscience and Remote Sensing Symposium (IGRASS), Brussels, Belgium.
- *2020*, China High-Resolution Earth Observation Conference, Changsha, China.
  
# 📖 Daily life
I like to play soccer and travel. Enjoy the sport and life :)

I am the Captain of the LIESMARS soccer team and serve as a national athlete (Goalkeeper).
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Teamwork</div><img src='images/s2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Goalkeeper</div><img src='images/s1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Travel</div><img src='images/4.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
