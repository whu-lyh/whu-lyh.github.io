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

I am a lecturer in the Department of Intelligent Vehicle Engineering, [School of Mechanical Engineering](https://impe2014.ctbu.edu.cn/), [Chongqing Technology and Business University](https://www.ctbu.edu.cn/). I obtained my Ph.D. in 2024 from the State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing ([LIESMARS](http://www.lmars.whu.edu.cn/en/)), at [Wuhan University](https://en.whu.edu.cn/), where I was supervised by [Prof. BiSheng Yang](https://3s.whu.edu.cn/ybs/index.htm) and [Prof. Zhen Dong](https://dongzhenwhu.github.io/).  During my Ph.D., I collaborated closely with [Dr. Jianping Li](https://kafeiyin00.github.io/), a research fellow at [Nanyang Technological University](https://www.ntu.edu.sg/) and [Dr. Yuan Wang](https://dlxy.jxnu.edu.cn/2024/0402/c7440a259126/page.htm), a lecturer at [Jiangxi Normal University](https://www.jxnu.edu.cn/). Prior to this, I received my M.S. degree in 2019 from the [School of Geodesy and Geomatics](https://www.sgg.whu.edu.cn/), [Wuhan University](https://en.whu.edu.cn/), where I was supervised by [A. Prof. Li Zheng](https://www.sgg.whu.edu.cn/info/1392/1208.htm) and A. Prof. Zheng Ji. 

My research interests span Mobile Laser Scanning Point Clouds processing, Multi-modality Fusion and Localization, and Gaussian Splatting related 3D Reconstruction. I have published several papers in top-tier journals and conferences, including ISPRS Journal, Information Fusion, JAG, IEEE TGRS, and 测绘学报. You can explore my publications and citations on my [Google Scholar profile](https://scholar.google.com/citations?user=rB0h2ocAAAAJ) <a href='https://scholar.google.com/citations?user=rB0h2ocAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- 2025.05: 🎉🎉🎉 One paper (OneStep-GSPE) is accepted by The 13th International Conference on Mobile Mapping Technology (MMT2025) and will be published on ISPRS Annals. (EI, Oral). Glad to meet you at Xiamen.
- 2025.04: 🎉🎉🎉 One paper (CVT Space Warping based Multi-scale Neural Implicit Surface Reconstruction for Outdoor Scenes) is accepted by Acta Geodaetica et Cartographica sinica (测绘学报). (EI, CSCD). Congratulations to Lu.
- 2025.02: 🎉🎉🎉 SaliencyI2PLoc is accepted by Information Fusion. (SCI1-TOP, IF: 14.8).
- 2024.12: 🎉🎉🎉 One paper (SaliencyI2PLoc) is available at [Arxiv](https://arxiv.org/abs/2412.15577).
- 2024.11: 🎉🎉🎉 I have completed my PhD thesis defense.
- 2024.10: 🎉🎉🎉 One paper is accepted by JAG. (SCI1-TOP, IF:  7.6). Congratulations to Yuan.
- *2024.09*: 🎉🎉🎉 One paper (CofiI2P) is accepted by IEEE RAL. (SCI2-TOP, IF:  4.6). Congratulations to [Shuhao](https://kang-1-2-3.github.io/) and [Youqi](https://martin-liao.github.io/).
- *2024.04*: 🎉🎉🎉 One paper is accepted by TGRS. (SCI1-TOP, IF:  7.5). Congratulations to [Xiaochen](https://xc-young.github.io/).
- *2024.04*: 🎉🎉🎉 One paper is accepted by PHOTOGRAMMETRIC RECORD. (SCI3, IF:  2.4). Congratulations to [Xin Zhao](https://xinzhaodc.github.io/).
- *2023.09*: 🎉🎉🎉 One paper (MuCoGraph) is accepted by ISPRS J. (SCI1-TOP, IF:  12.7).
- *2022.12*: 🎉🎉🎉 Science and Technology Progress Award for Geographic Information, **Second** Class Prize, awarded by CAGIS.
- *2022.10*: 🎉🎉🎉 One paper is accepted by JAG. (SCI1-TOP, IF:  7.6).

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MMT 2025</div><img src='images/publications/MMT2025.png' alt="sym" width="101%"></div></div>
<div class='paper-box-text' markdown="1">
[OneStep-GSPE: an Efficient 3D Gaussian Splatting Based Image Pose Estimation]().
**Yuhao Li**, Yipeng Lu, [Jianping Li](https://kafeiyin00.github.io/), Yuan Wang, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), [Zhen Dong](https://dongzhenwhu.github.io/). (EI, Oral). \| [Project Page](https://whu-lyh.github.io/OneStep-GSPE/).
</div>
</div>






<div class='paper-box'><div class='paper-box-image'><div><div class="badge">InF 2025</div><img src='images/publications/IF20241223.png' alt="sym" width="101%"></div></div>
<div class='paper-box-text' markdown="1">
[SaliencyI2PLoc: saliency-guided image-point cloud localization using contrastive learning](https://arxiv.org/abs/2412.15577).
**Yuhao Li**, [Jianping Li](https://kafeiyin00.github.io/), Yuan Wang, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), [Zhen Dong](https://dongzhenwhu.github.io/). (SCI1-TOP, IF: 14.8). \| [Project Page](https://whu-lyh.github.io/SaliencyI2PLoc/) \| [WeChat](https://mp.weixin.qq.com/s/Kqr7cVvgMy0wx7wGzZybqA) \| [Code](https://github.com/whu-lyh/SaliencyI2PLoc) \| [Arxiv](https://arxiv.org/abs/2412.15577) \| [BiliBili](https://www.bilibili.com/video/BV17xgTevE4N?vd_source=824f51136eb80b5d06dddf1729586c4a).
</div>
</div>










<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISPRS J 2023</div><img src='images/publications/ISPRS20230921.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[MuCoGraph: A Multi-scale Constraint Enhanced Pose Graph Framework for MLS Point Cloud Inconsistency  Correction](https://www.sciencedirect.com/science/article/abs/pii/S0924271623002599).
**Yuhao Li**, Xianghong Zou, Tian Li, Sihan Sun, Yuan Wang, [Fuxun Liang](https://liangfxwhu.github.io/), [Jianping Li](https://kafeiyin00.github.io/), [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), [Zhen Dong](https://dongzhenwhu.github.io/). (SCI1-TOP, IF:12.7).  \| [Wechat](https://mp.weixin.qq.com/s/9dgklKTO97EI210vnNedog) \| [Youtube](https://www.youtube.com/watch?v=57h50gP84mQ) \| [BiliBili](https://www.bilibili.com/video/BV1Lj411C7NV/?share_source=copy_web&vd_source=824f51136eb80b5d06dddf1729586c4a).
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 2022</div><img src='images/publications/JAG20221026.png' alt="sym" width="101%"></div></div>
<div class='paper-box-text' markdown="1">

[Automatic registration of point cloud and panoramic images in urban scenes based on pole matching](https://www.sciencedirect.com/science/article/pii/S1569843222002710). 

Yuan Wang, **Yuhao Li**, Yiping Chen,  Mingjun Peng, Haiting Li, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm),  Chi Chen, [Zhen Dong](https://dongzhenwhu.github.io/). (SCI1-TOP, IF:7.6). 

</div>
</div>


+ ``测绘学报 2025`` [CVT Space Warping based Multi-scale Neural Implicit Surface Reconstruction for Outdoor Scenes](http://xb.chinasmp.com/CN/10.11947/j.AGCS.2025.20240280). Yipeng Lu, **Yuhao Li**, [Haiping Wang](https://hpwang-whu.github.io/), [Yuan Liu](https://liuyuan-pal.github.io/), [Zhen Dong](https://dongzhenwhu.github.io/), [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm). (EI, CSCD)
+ ``JAG 2024`` [Efficient Multi-modal High-precision Semantic Segmentation from MLS Point Cloud without 3D Annotation](https://www.sciencedirect.com/science/article/pii/S1569843224005995). Yuan Wang, Pei Sun, Wenbo Chu, **Yuhao Li**, Yiping Chen, Hui Lin, [Zhen Dong](https://dongzhenwhu.github.io/), [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), Chao He. (SCI1-TOP, IF:7.6). 
+ ``RAL 2024 & ICRA 2025``  [CoFiI2P: Coarse-to-Fine Correspondences-Based Image-to-Point Cloud Registration](https://ieeexplore.ieee.org/document/10685082). [Shuhao Kang](https://kang-1-2-3.github.io/), [Youqi Liao](https://martin-liao.github.io/), [Jianping Li](https://kafeiyin00.github.io/), [FuxunLiang](https://liangfxwhu.github.io/), **Yuhao Li**, Xianghong Zou, Fangning Li, Xieyuanli Chen, [Zhen Dong](https://dongzhenwhu.github.io/), [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm). (SCI2-TOP, IF:  4.6).  \| [Arxiv](https://arxiv.org/abs/2309.14660v2) \| [ProjectPage](https://whu-usi3dv.github.io/CoFiI2P/) \| [Code](https://github.com/WHU-USI3DV/CoFiI2P).
+ ``TGRS 2024`` [A novel method for registration of MLS and stereo reconstructed point clouds](https://ieeexplore.ieee.org/abstract/document/10500860). [Xiaochen Yang](https://xc-young.github.io/), [Haiping Wang](https://hpwang-whu.github.io/), [Zhen Dong](https://dongzhenwhu.github.io/), [Yuan Liu](https://liuyuan-pal.github.io/), **Yuhao Li**, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm). (SCI1-TOP, IF:  7.5). \|[Code](https://github.com/WHU-USI3DV/MSReg).
+ ``Phor 2024`` [Coarse-to-fine adjustment for multi-platform point cloud fusion](https://onlinelibrary.wiley.com/doi/abs/10.1111/phor.12513). [Xin Zhao](https://xinzhaodc.github.io/), [Jianping Li](https://kafeiyin00.github.io/), **Yuhao Li**, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), Sihan Sun, Yongfeng Lin, [Zhen Dong](https://dongzhenwhu.github.io/). (SCI3, IF:2.1). \| [WeChat](https://mp.weixin.qq.com/s?__biz=MzIzNzE1NDYwNw==&mid=2648738928&idx=1&sn=5345c71ce5a91510d22796d91872e08e&chksm=f102b78358879e3110b4c83e38e63cd990495f6b615ba0865cf8bc2a8c7d98f4e8491e822e48&scene=126&sessionid=1741678750#rd).
+ ``ISPRS J 2022`` [3D-CSTM: A 3D continuous spatio-temporal mapping method](https://www.sciencedirect.com/science/article/pii/S0924271622000399). Yangzi Cong, Chi Chen, [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), [Jianping Li](https://kafeiyin00.github.io/), Weitong Wu, **Yuhao Li**, Yandi Yang. (SCI1-TOP, IF:11.7). 
+ ``ISPRS Archives 2020`` [A marker-free calibration method for mobile laser scanning point clouds correction](https://isprs-archives.copernicus.org/articles/XLIII-B2-2020/347/2020/isprs-archives-XLIII-B2-2020-347-2020.html). [Bisheng Yang](https://3s.whu.edu.cn/ybs/index.htm), **Yuhao Li**, Xianghong Zou, [Zhen Dong](https://dongzhenwhu.github.io/). (EI). 
+ ``RS 2019`` [Non-Rigid Vehicle-Borne LiDAR-Assisted Aerotriangulation](https://doi.org/10.3390/rs11101188). [Li Zheng](https://www.sgg.whu.edu.cn/info/1392/1208.htm), **Yuhao Li**, Meng Sun, Zheng Ji, Manzhu Yu, Qingbo Shu.  (SCI2, IF:4.2).

# 💻 Selected Projects

+ Point cloud pre-processing tool, *2022.12-2023.03*, \| `C++`.

<div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Point2Model 2021</div><img src='images/projects/Point2Model.gif' alt="sym" width="100%"></div></div>
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
+ Open-Set Face Recognition, *2018.05-2018.08.* \| `C++` \| `Python`.

# ✍️ Services

Reviewer for Conferences: MMT2025

Review for Journals: IEEE TASE, IEEE IoT-J

# 🏫 Teaching

Modern Sensors and Detection Technology 2025

# 🎖 Selected Honors and Awards
- *2022.12*, China Association for Geographic Information Society (CAGIS), Science and Technology Progress Award for Geographic Information, **Second** Class Prize, Rank **three**.
- 2019.06, Outstanding Graduate Student, Wuhan University.
- *2018.08*, The Fifth China Graduate Context on Smart-city Technology and Creative Design, **Third** Class Prize.

# 📖 Educations
- *2020.09 - 2024.12*, Ph.D, LIESMARS, Wuhan University, Wuhan.
- *2019.07 - 2020.08*, Research Assistent, LIESMARS, Wuhan University, Wuhan.
- *2017.09 - 2019.06*, M.S., School of Geodesy and Geomatics, Wuhan University, Wuhan.
- *2013.09 - 2017.06*, B.S., Tai Yuan University of Technology, Taiyuan.
