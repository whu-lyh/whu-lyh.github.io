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

I am currently working toward the Ph.D degree in the State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing ([LIESMARS](http://www.lmars.whu.edu.cn/en/)), [Wuhan University](https://en.whu.edu.cn/), supervised by [Prof. BiSheng Yang](https://3s.whu.edu.cn/ybs/index.htm) and [Prof. Zhen Dong](https://dongzhenwhu.github.io/).  Before this, I received the M.S. degree in School of Geodesy and Geomatics, Wuhan University in 2019, supervised by A. Prof. Li Zheng and A. Prof. Zheng Ji. Prior to WHU, I received the B.S. degree in Tai Yuan University of Technology in 2017. 

My research interests include Mobile Laser Scanning Point Cloud, LiDAR SLAM, Multi-modality Fusion, Place Recognition, Retrieval and Localization. I have published several papers <a href='https://scholar.google.com/citations?user=rB0h2ocAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top journals, such as ISPRS J and JAG.


# 🔥 News
- *2023.09*: 🎉 🎉🎉  One paper is accepted by ISPRS J. (SCI1-TOP, IF:  12.7).
- *2022.12*: 🎉 🎉🎉  Science and Technology Progress Award for Geographic Information, **Second** Class Prize, awarded by CAGIS.
- *2022.10*: 🎉 🎉 🎉 One paper is accepted by JAG. (SCI1-TOP, IF:  7.5).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS J 2023</div><img src='images/publications/ISPRS20230921.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MuCoGraph: A Multi-scale Constraint Enhanced Pose Graph Framework for MLS Point Cloud Inconsistency  Correction](https://authors.elsevier.com/c/1hqt73I9x1mzdd).

**Yuhao Li**, Xianghong Zou, Tian Li, Sihan Sun, Yuan Wang, Fuxun Liang, Jianping Li, Bisheng Yang, Zhen Dong. (SCI1-TOP, IF:12.7).  \| [Wechat](https://mp.weixin.qq.com/s/9dgklKTO97EI210vnNedog) \| [Youtube](https://www.youtube.com/watch?v=57h50gP84mQ) \| [Bilibili](https://www.bilibili.com/video/BV1Lj411C7NV/?share_source=copy_web&vd_source=824f51136eb80b5d06dddf1729586c4a).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 2022</div><img src='images/publications/JAG20221026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automatic registration of point cloud and panoramic images in urban scenes based on pole matching](https://www.sciencedirect.com/science/article/pii/S1569843222002710). 

Yuan Wang, **Yuhao Li**, Yiping Chen,  Mingjun Peng, Haiting Li, Bisheng Yang,  Chi Chen, Zhen Dong. (SCI1-TOP, IF:7.5). 

</div>
</div>

+ ``ISPRS J 2022`` [3D-CSTM: A 3D continuous spatio-temporal mapping method](https://www.sciencedirect.com/science/article/pii/S0924271622000399). Yangzi Cong, Chi Chen, Bisheng Yang, Jianping Li, Weitong Wu, **Yuhao Li**, Yandi Yang. (SCI1-TOP, IF:12.7). 
+ ``ISPRS Archives 2020`` [A marker-free calibration method for mobile laser scanning point clouds correction](https://isprs-archives.copernicus.org/articles/XLIII-B2-2020/347/2020/isprs-archives-XLIII-B2-2020-347-2020.html). Bisheng Yang, **Yuhao Li**, Xianghong Zou, Zhen Dong. (EI). 
+ ``RS 2019`` [Non-Rigid Vehicle-Borne LiDAR-Assisted Aerotriangulation](https://doi.org/10.3390/rs11101188). Li Zheng, **Yuhao Li**, Meng Sun, Zheng Ji, Manzhu Yu, Qingbo Shu.  (SCI2, IF:5.8).

# 💻 Selected Projects

+ Point cloud pre-processing tool, *2022.12-2023.03*, \| `C++`.

<div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Point2Model 2021</div><img src='images/projects/Point2Model.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


Point2Model development, *2021.07-2021.12*. \| `C++` \| `Microstation`\| [Commercial Software Page](http://www.dynspai.com/dydwswtqyyyjjfa).

+ **Feature**: MLS position inconsistency correction module, Cloud2Cloud distance check module.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Powerline Simulation 2021</div><img src='images/projects/PowerlineSimulation.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Powerline inspection software development, *2021.03-2021.06*, \| `C++` \| `Qt` \| `Matlab`.

+ **Feature**: Automatic point cloud division of power corridor, Individual powerline coefficient estimation, Transmission line sag simulation, Point cloud and aerial image fusion, Risk detection and report print.

</div>
</div>

+ MLS point cloud position correction UI, *2019.07-2019.09*. \| `C++` \| `Qt`.

# 🎖 Selected Honors and Awards
- *2022.12*, China Association for Geographic Information Society (CAGIS), Science and Technology Progress Award for Geographic Information, **Second** Class Prize, Rank **three**.
- *2018.08*, The Fifth China Graduate Context on Smart-city Technology and Creative Design, **Third** Class Prize.

# 📖 Educations
- *2019.09 - (now)*, Ph.D, LIESMARS, Wuhan University, Wuhan.
- *2017.09 - 2019.06*, M.S., School of Geodesy and Geomatics, Wuhan University, Wuhan.
- *2013.06 - 2017.06*, B.S., Tai Yuan University of Technology, Taiyuan.
