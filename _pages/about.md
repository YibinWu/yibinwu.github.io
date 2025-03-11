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

I am a PhD candidate at the [Center for Robotics](https://robotik.uni-bonn.de/Home.html) and [Institute of Geodesy and Geoinformation](https://www.igg.uni-bonn.de/en?set_language=en) in the University of Bonn, Bonn, Germany. My research interest focuses on sensor fusion-based robot perception and navigation. 

<!--I obtained my Master's degree in Navigation, Guidance, and Control in [i2Nav Lab](http://i2nav.cn/) at Wuhan University, Wuhan, China in 2020. It was enjoyable and rewarding to be supervised by Prof. [Xiaoji Niu](https://dblp.org/pid/94/652.html) and study within his group. I obtained my Bachelor's degree in Navigation Engineering at the same institute in 2017.-->

I am looking for self-motivated Master students (online/offline) to work on topics about SLAM, multisensor fusion, etc. Please drop me an email.<!--<a href='https://scholar.google.com/citations?user=MKOtRJwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
-->

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 A paper on **GNSS/INS integrated navigation system with a wheel-mounted IMU** ([**Wheel-GINS**](https://github.com/i2Nav-WHU/Wheel-GINS)) has been accepted to IEEE Transactions on Intelligent Transportation Systems!
- *2024.02*: &nbsp;🎉🎉 A paper on **EKF-based high-frequency LiDAR-inertial odometry** ([**LIO-EKF**](https://arxiv.org/pdf/2311.09887.pdf)) has been accepted to ICRA. Try the [code](https://github.com/YibinWu/LIO-EKF)!
- *2023.10*: &nbsp;🎉🎉 A completely new version of the [**Wheel-INS**](https://github.com/i2Nav-WHU/Wheel-INS/tree/master) code supporting both Linux and Windows is released! Check it out!
- *2023.02*: &nbsp;🎉🎉 I am invited by CVlife to give an online presentation about my research on Wheel-IMU. Check out the video in [Bilibili](https://www.bilibili.com/video/BV1y84y1n7PG/?spm_id_from=333.999.0.0&vd_source=b5a4ea43333bf9e59a06f2f4fa10f5a8)! (in Chinese)
- *2022.11*: &nbsp;🎉🎉 A paper on **one wheel-mounted IMU-based SLAM** ([**Wheel-SLAM**](https://arxiv.org/pdf/2211.03174.pdf)) has been accepted to IEEE Robotics and Automation Letters. 
- *2022.11*: &nbsp;🎉🎉 A paper on **multiple IMUs-based wheeled robot localization** ([**Wheel-INS2**](https://arxiv.org/pdf/2012.10593.pdf)) has been accepted to IEEE Transactions on Intelligent Transportation Systems. 

# 📝 Publications 

## Journal papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS 2025</div><img src='images/wheelgins.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Wheel-GINS: A GNSS/INS Integrated Navigation System with a Wheel-mounted IMU** [[PDF]](https://arxiv.org/pdf/2501.03079) [[Code]](https://github.com/i2Nav-WHU/Wheel-GINS)[ ![](https://img.shields.io/github/stars/i2Nav-WHU/Wheel-GINS?style=social)](https://github.com/i2Nav-WHU/Wheel-GINS)
  
**Yibin Wu**, Jian Kuang, Xiaoji Niu, Cyrill Stachniss, Lasse Klingbeil, and Heiner Kuhlmann, **IEEE Transactions on Intelligent Transportation Systems**, 2025 

-  Wheel-GINS is an integrated navigation system that combines GNSS data with a wheel-mounted IMU (Wheel-IMU). It performs a similar information fusion process to conventional GNSS/Odometer/IMU integrated systems using only two sensors. Moreover, all Wheel-IMU installation parameters are estimated online in Wheel-GINS, enhancing the system's practicality and adaptability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE RAL 2022</div><img src='images/wheel-slam_homepage_new.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Wheel-SLAM: Simultaneous Localization and Terrain Mapping Using One Wheel-mounted IMU** [[PDF]](https://arxiv.org/pdf/2211.03174.pdf) [[Code]](https://github.com/i2Nav-WHU/Wheel-SLAM)[ ![](https://img.shields.io/github/stars/i2Nav-WHU/Wheel-SLAM?style=social)](https://github.com/i2Nav-WHU/Wheel-SLAM)
  
**Yibin Wu**, Jian Kuang, Xiaoji Niu, Jens Behley, Lasse Klingbeil, and Heiner Kuhlmann, **IEEE Robotics and Automation Letters**, 2022 

-  A SLAM system using only one low-cost IMU by exploiting the road bank angles (mirrored by the robot roll angles estimated by [Wheel-INS](http://i2nav.cn/ueditor/jsp/upload/file/20210905/1630804325780076093.pdf)) as terrain features to enable the loop closure with a Rao-Blackwellized particle filter. The weights of the particles are updated according to the difference between the currently estimated roll sequence and the terrain map.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS 2022</div><img src='images/wheelins2_homepage_new.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Wheel-INS2: Multiple MEMS IMU-based Dead Reckoning System with Different Configurations for Wheeled Robots** [[PDF]](https://arxiv.org/pdf/2012.10593.pdf)
  
**Yibin Wu**, Jian Kuang, Xiaoji Niu, **IEEE Transactions on Intelligent Transportation Systems**, 2022

- A multiple IMUs-based localization system for wheeled robots by obtaining different dynamic information of the vehicle and taking advantage of the relative spatial constraints among the inertial sensors with a comparison of various configurations, e.g., one body-mounted IMU (Body-IMU) plus one wheel-mounted IMU (Wheel-IMU), dual Wheel-IMUs, and dual Wheel-IMUs plus one Body-IMU.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT 2021</div><img src='images/Wheel-INS_Comp_5_3_homepage.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**A Comparison of Three Measurement Models for the Wheel-mounted MEMS IMU-based Dead Reckoning System** [[PDF]](http://i2nav.cn/ueditor/jsp/upload/file/20210905/1630804728655046341.pdf)
  
**Yibin Wu**, Xiaoji Niu, Jian Kuang, **IEEE Transactions on Vehicular Technology**, 2021

- A thorough and complete comparison of three different measurement models (vehicle velocity information obtained from the wheel-mounted IMU) in Wheel-INS with both theoretical analysis and experimental illustration.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT 2021</div><img src='images/Wheel-INS_5_3_homepage.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**Wheel-INS: A Wheel-mounted MEMS IMU-based Dead Reckoning System** [[PDF]](http://i2nav.cn/ueditor/jsp/upload/file/20210905/1630804325780076093.pdf) [[Code]](https://github.com/i2Nav-WHU/Wheel-INS)[ ![](https://img.shields.io/github/stars/i2Nav-WHU/Wheel-INS?style=social)](https://github.com/i2Nav-WHU/Wheel-INS)
  
Xiaoji Niu, **Yibin Wu**, Jian Kuang, **IEEE Transactions on Vehicular Technology**, 2021 

- A robust and accurate localization system for the wheeled robots using one low-cost wheel-mounted IMU by taking advantage of rotation modulation.
</div>
</div>


- **A MEMS IMU and motion constraint-based positioning algorithm for shared bicycles**, Xiaoji Niu, Longyang Ding, Jian Kuang, **Yibin Wu** (Corresponding author), **Journal of Chinese Inertial Technology**, 2021 (in Chinese)(Longyang Ding was an undergraduate student supervised by me. He won the **Special Prize** of the *12th China Undergraduate Contest on Surveying & Mapping Technical Paper* based on this project.) [[PDF]](https://www.researchgate.net/publication/355757283_A_MEMS_IMU_and_motion_constraint-based_positioning_algorithm_for_shared_bicycles)

- **Artificial Marker and MEMS IMU-Based Pose Estimation Method to Meet Multi-rotor UAV Landing Requirements**, **Yibin Wu**, Xiaoji Niu, Junwei Du, Le Chang, Hailiang Tang, Hongping Zhang, **Sensors**, 2019 [[PDF]](https://www.mdpi.com/1424-8220/19/24/5428)


## Conference papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/lio_ekf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**LIO-EKF: High Frequency LiDAR-Inertial Odometry using Extended Kalman Filters** [[PDF]](https://arxiv.org/pdf/2311.09887.pdf) [[Code]](https://github.com/YibinWu/LIO-EKF)[ ![](https://img.shields.io/github/stars/YibinWu/LIO-EKF)](https://github.com/YibinWu/LIO-EKF)

**Yibin Wu**, Tiziano Guadagnino, Louis Wiesmann, Lasse Klingbeil, Cyrill Stachniss, and Heiner Kuhlmann, **ICRA**, 2024 

-  A high-frequency LiDAR-inertial odometry system based on adaptive point-to-point registration and EKF, achieving comparative accuracy to the state-of-the-art. 
</div>
</div>


## Preprints

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/go2_coordinates.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DogLegs: Robust Proprioceptive State Estimation for Legged Robots Using Multiple Leg-Mounted IMUs** [[PDF]](https://arxiv.org/pdf/2503.04580) 

**Yibin Wu**, Jian Kuang, Shahram Khorshidi, Xiaoji Niu,
Lasse Klingbeil, Maren Bennewitz, Heiner Kuhlmann 

- A state estimation system for legged robots that fuses the measurements from a body-mounted inertial measurement unit (Body-IMU), joint encoders, and multiple leg-mounted IMUs (Leg-IMU) using an extended Kalman filter (EKF). 
</div>
</div>

- [Formula Derivation and Analysis of the VINS-Mono](https://arxiv.org/ftp/arxiv/papers/1912/1912.11986.pdf), **Yibin Wu**, 2019 (A detailed and comprehensive formula derivation of [VINS-Mono](https://github.com/HKUST-Aerial-Robotics/VINS-Mono), one of the state-of-the-art visual-inertial odometry systems.)


# 🎖 Honors and Awards 
- *2020.05* Outstanding Master Graduate <!--of Wuhan University--> 
- *2019.12* Outstanding Postgraduate Student <!--of Wuhan University-->
- *2019.08* **First prize** (1.97%) and **Best Paper Award** (0.41%) in the 14th China Graduate Electronic Design Competition
- *2019.08* Third prize in the 6th China Graduate Contest on Smart-city Technology and Creative Design
- *2016.12* National Encouragement Scholarship (Undergraduate) of China

# 💻 Internships
- *2018.09 - 2018.12*, Research Intern in the HD map group at [Momenta](https://www.momenta.cn/en/), Beijing, China.

<span class='anchor' id='-academic-services'></span>
# 🙋‍♂️ Academic Services
- Conference Reviewer: ICRA
- Journal Reviewer: IEEE T-ITS, IEEE T-SP, IEEE T-VT, IEEE RA-L, Measurement(Elsevier), IEEE Sensors-J
