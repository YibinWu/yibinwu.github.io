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

I am a research associate in the Institute of Geodesy and Geoinformation at Bonn University, Bonn, Germany. I obtained my Master degree in Navigation, Guidance, and Control in [i2Nav Lab](http://i2nav.cn/) at Wuhan University in 2020. It was enjoyable and rewarding to be supervised by Prof. [Xiaoji Niu](https://dblp.org/pid/94/652.html) and study within his group. I obtained my Bachelor degree in Navigation Engineering at the same institute in 2017.
<!--
My research interest focuses on sensor fusion-based robot perception and navigation.<a href='https://scholar.google.com/citations?user=MKOtRJwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
-->

# 🔥 News
- *2022.11*: &nbsp;🎉🎉 A paper on multiple IMUs-based wheeled robot localization has been accepted to IEEE Transactions on Intelligent Transportation Systems. 

# 📝 Publications 

## Journal papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS 2022</div><img src='images/Wheel-INS3_5_3_homepage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Wheel-INS2: Multiple MEMS IMU-based Dead Reckoning System with Different Configurations for Wheeled Robots](https://arxiv.org/pdf/2012.10593.pdf)
  
**Yibin Wu**, Jian Kuang, Xiaoji Niu, accepted to **IEEE Transations on Intelligent Transportation Systems**, 2022

- A localization system for wheeled robots using multiple low-cost IMUs with comparison on different configurations, e.g., one body-mounted IMU (Body-IMU) plus one wheel-mounted IMU (Wheel-IMU), dual Wheel-IMUs, and dual Wheel-IMUs plus one Body-IMU.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT 2021</div><img src='images/Wheel-INS_5_3_homepage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Wheel-INS: A Wheel-mounted MEMS IMU-based Dead Reckoning System](http://i2nav.cn/ueditor/jsp/upload/file/20210905/1630804325780076093.pdf)
  
Xiaoji Niu, **Yibin Wu**, Jian Kuang, **IEEE Transations on Vehicular Technology**, 2021 [Wheel-INS ![](https://img.shields.io/github/stars/i2Nav-WHU/Wheel-INS?style=social)](https://github.com/i2Nav-WHU/Wheel-INS)

- A robust and accurate localization system for the wheeled robots using one low-cost wheel-mounted IMU by taking advantage of rotation modulation.
</div>
</div>


- [A Comparison of Three Measurement Models for the Wheel-mounted MEMS IMU-based Dead Reckoning System](http://i2nav.cn/ueditor/jsp/upload/file/20210905/1630804728655046341.pdf), **Yibin Wu**, Xiaoji Niu, Jian Kuang, **IEEE Transations on Vehicular Technology**, 2021

- [A MEMS IMU and motion constraint-based positioning algorithm for shared bicycles](https://www.researchgate.net/publication/355757283_A_MEMS_IMU_and_motion_constraint-based_positioning_algorithm_for_shared_bicycles), Xiaoji Niu, Longyang Ding, Jian Kuang, **Yibin Wu** (Corresponding author), **Journal of Chinese Inertial Technology**, 2021 
(Longyang Ding was a undergraduate student supervised by me. He won the **Special Prize** of the *12th China Undergraduate Contest on Surveying & Mapping Technical Paper* based on this project.

- [Artificial Marker and MEMS IMU-Based Pose Estimation Method to Meet Multi-rotor UAV Landing Requirements](https://www.mdpi.com/1424-8220/19/24/5428), **Yibin Wu**, Xiaoji Niu, Junwei Du, Le Chang, Hailiang Tang, Hongping Zhang, **Sensors**, 2019


## Preprints
- [Formula Derivation and Analysis of the VINS-Mono](https://arxiv.org/ftp/arxiv/papers/1912/1912.11986.pdf), **Yibin Wu**, 2019 (A detailed and com-
prehensive formula derivation of [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono), one of the state-of-the-art visual-inertial odometry systems.)


# 🎖 Honors and Awards 
- *2020.05* Outstanding Master Graduate of Wuhan University 
- *2019.12* Outstanding Postgraduate Student of Wuhan University
- *2019.08* **First prize** (1.97%) and **Best Paper Award** (0.41%) in the 14th China Graduate Electronic Design Competition
- *2019.08* Third prize in the 6th China Graduate Contest on Smart-city Technology and Creative Design
- *2016.12* National Encouragement Scholarship (Undergraduate) of China

# 💻 Internships
- *2018.09 - 2018.12*, Research Intern in the HD map group at [Momenta](https://www.momenta.cn/en/), Beijing, China.

<span class='anchor' id='-academic-services'></span>
# 🙋‍♂️ Academic Services
- Conference Reviewer: ICRA
- Journal Reviewer: IEEE Sensors Journal
