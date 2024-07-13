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

<span class="anchor" id="about-me"></span>

<!-- I am currently a Master at [South China University of Techonology (SCUT)](https://www.scut.edu.cn/en/), advised by [Prof. Kui Jia](http://kuijia.site/).  -->
<!-- I received my Master's degree in Electronic Information from [South China University of Techonology (SCUT)](https://www.scut.edu.cn/en/), advised by [Prof. Kui Jia](http://kuijia.site/). 
I received my bachelor degree from the same university (i.e. SCUT) in 2021, and expect to obtain my Master degree in 2024.  -->

I received my Master's degree in Electronic Information from [South China University of Techonology (SCUT)](https://www.scut.edu.cn/en/) in 2024, under the supervision by [Prof. Kui Jia](http://kuijia.site/). 
I obtained my bachelor degree from the same university (i.e. SCUT) in 2021.

I mainly focus on **3D Computer Vision**. My current research interests include Computer Graphics, 3D Shape Modeling and Reconstruction. Recently, I am working on Multi-View Reconstruction.


<!-- # 🔥 News -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">ECCV 2024</div><img src="images/sur2f.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Sur<sup>2</sup>f: A Hybrid Representation for High-Quality and Efficient Surface Reconstruction from Multi-view Images](https://arxiv.org/abs/2401.03704)

 **Zhangjin Huang\***, Zhihao Liang\*, Haojie Zhang, Yangkai Lin, Kui Jia

[**Project**](https://huang-zhangjin.github.io/project-pages/sur2f.html) | [**Code**](https://github.com/Gorilla-Lab-SCUT/Sur2f)
<!-- | [**Code**](https://github.com/Gorilla-Lab-SCUT/HelixSurf) -->
- We propose a new hybrid representation, termed Sur<sup>2</sup>f, that can enjoy the benefits of both explicit and implicit surface representations. This is achieved by learning two parallel streams of an implicit SDF and an explicit surrogate surface mesh, both of which, by rendering, receive supervision from multi-view image observations.
</div>
</div>


<div class="paper-box"><div class="paper-box-image"><div><div class="badge">CVPR 2023</div><img src="images/HelixSurf.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[HelixSurf: A Robust and Efficient Neural Implicit Surface Learning of Indoor Scenes with Iterative Intertwined Regularization](https://arxiv.org/pdf/2302.14340.pdf)

Zhihao Liang\*, **Zhangjin Huang\***, Changxing Ding, Kui Jia

[**Project**](https://lzhnb.github.io/project-pages/helixsurf.html) | [**Code**](https://github.com/Gorilla-Lab-SCUT/HelixSurf)
- We present a novel method of HelixSurf for reconstruction of indoor scene surface from multi-view images. HelixSurf enjoys the complementary benefits of the traditional MVS and the recent neural implicit surface learning, by regularizing the learning/optimization of one strategy iteratively using the intermediate prediction from the other.
</div>
</div>

<div class="paper-box"><div class="paper-box-image"><div><div class="badge">Accepted to TPAMI 2024</div><img src="images/ScutSurf.png" alt="sym" width="100%"></div></div>
<div class="paper-box-text" markdown="1">

[Surface Reconstruction from Point Clouds: A Survey and a Benchmark](https://arxiv.org/pdf/2205.02413.pdf)

**Zhangjin Huang\***, Yuxin Wen*, Zihao Wang, Jinjuan Ren, Kui Jia

[**Project**](https://gorilla-lab-scut.github.io/SurfaceReconstructionBenchmark/) | [**Code**](https://github.com/Gorilla-Lab-SCUT/SCUTSurface-code)
- We review and benchmark existing methods in the new era of deep learning surface reconstruction. We contribute a large-scale benchmarking dataset consisting of both synthetic and real-scanned data; the benchmark includes object- and scene-level surfaces and takes into account various sensing imperfections that are commonly encountered in practical depth scanning. We conduct thorough empirical studies by comparing existing methods on the constructed benchmark. Our studies help identity the best conditions under which different methods work, and suggest some empirical findings.


</div>
</div>


# 📖 Educations
- *2021.09 -  2024.06*, Master, South China University of Technology, Guangzhou.
- *2017.09 - 2021.06*, Undergraduate, South China University of Technology, Guangzhou.
