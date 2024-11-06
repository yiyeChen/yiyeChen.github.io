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

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, TODO: introduction, paper summary...

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
 - *2024.05*: 🎉Excited to join the <strong>Microsoft</strong> Mixed Reality team as a research scientist intern.
 - *2023.07*: 📝One paper accepted to <strong>ICCV 2023</strong>, on _a feature-based image Out-of-Distribution detection method_.
 - *2023.06*: 📝One paper accepted to <strong>IROS 2023</strong>,on _an improved keypoint-based 6-DoF grasp synthesis strategy_.
 - *2023.05*: 🎉Excited to join the <strong>Amazon Robotics</strong> stow perception team as an applied scientist intern.
 - *2023.01*: 📝One paper accepted to <strong>ICLR 2023</strong>, on _action sequence planning with the transformer model_.
 - *2023.01*: 📝One paper accepted to <strong>ICRA 2023</strong>, on _Keypoint-based 6-DoF grasp detection_.
 - *2021.01*: 📝Two papers accepted to <strong>ICRA 2021</strong>, on _language-conditioned robotic grasping_ and _semantic-based pixel feature learning for the camera relocalization_.

# 📖 Educations
- *2021.01 - 2025.12 (Expected)*: Ph.D. in Electrical and Computer Engineering, Georgia Tech. Advised by Dr. [Patricio A. Vela](https://pvela.gatech.edu/). Atlanta, GA, United States. 
- *2019.08 - 2020.12*: M.S. in Electrical and Computer Engineering, Georgia Tech. Atlanta, GA, United States.
- *2015.09 - 2019.06*: B.E. in Aerospace Engineering, Beihang University. Beijing, China.

# 💻 Industrial Experience 
- *2024.05 - 2024.08*: Research Scientist Internship, [Microsoft Research](https://www.microsoft.com/en-us/research/). Redmond, WA, United States.
- *2023.05 - 2023.08*: Applied Scientist Internship, [Amazon Robotics](https://www.amazon.science/research-areas/robotics). Seattle, WA, United States.

# 📝 Publications 
(\* denotes equal contribution)

<!-- RwR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='images/RwR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RwR: : A Reason-while-Retrieve framework for Reasoning on Scene Graphs with LLMs (_In submission_)**]()

**Yiye Chen**, Harpreet Sawhney, Nicholas Gyde, Yanan Jian, Jack Saunders, Patricio Vela, Benjamin Lundell

[Code(Coming Soon)]() | [Project(Coming Soon)]()
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- WDiscOOD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV2023_WDiscOOD.png' alt="sym" width="85%"></div></div>
<div class='paper-box-text' markdown="1">

[**WDiscOOD: Out-of-Distribution Detection via Whitened Linear Discriminant Analysis**](https://openaccess.thecvf.com/content/ICCV2023/html/Chen_WDiscOOD_Out-of-Distribution_Detection_via_Whitened_Linear_Discriminant_Analysis_ICCV_2023_paper.html)

**Yiye Chen**, Yunzhi Lin, Ruinian Xu, Patricio A. Vela

[Code](https://github.com/ivalab/WDiscOOD) | [Poster](files/poster_WDiscOOD.pdf)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<!-- LEAP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/ICLR2023_LEAP_teaser.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Planning with Language Models through Iterative Energy Minimization**](https://openreview.net/forum?id=cVFD6qE8gnY)

Hongyi Chen\*, Yilun Du\*, **Yiye Chen\***, Patricio A. Vela, Joshua B. Tenenbaum

[Project](https://hychen-naza.github.io/projects/LEAP/index.html) | [Code](https://github.com/ivalab/WDiscOOD)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<!-- KGNv2 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2023</div><img src='images/graphAbs_KGNv2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**KGNv2: Separating Scale and Pose Prediction for Keypoint-based 6-DoF Grasp Synthesis on RGB-D input**](https://ieeexplore.ieee.org/document/10342514)

**Yiye Chen**; Ruinian Xu; Yunzhi Lin; Hongyi Chen; Patricio A. Vela

[Code](https://github.com/ivalab/KGN) | [Presentation](https://youtu.be/gK30iMHPr4I) | [Poster](files/poster_KGNv2.pdf) | [Supplementary](https://youtu.be/XDpdTdHo5eU)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<!-- KGN -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/ICRA23_KGN.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[**Keypoint-GraspNet: Keypoint-based 6-DoF Grasp Generation from the Monocular RGB-D input**](https://ieeexplore.ieee.org/abstract/document/10161284)

**Yiye Chen**; Yunzhi Lin; Ruinian Xu; Patricio A. Vela

[Code](https://github.com/ivalab/KGN) | [Presentation](https://youtu.be/oNHZ05kHBgI) | [Poster](files/poster_KGN.pdf) | [Supplementary](https://youtu.be/cT9lvTajRdA)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<!-- CGNet -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/ICRA21_CGNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A Joint Network for Grasp Detection Conditioned on Natural Language Commands**](https://ieeexplore.ieee.org/abstract/document/9561994)

**Yiye Chen**; Ruinian Xu; Yunzhi Lin; Patricio A. Vela

[Presentation](files/present_KGN.mp4) | [Poster](files/poster_KGN.pdf) | [Supplementary](files/supp_KGN.mp4)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
</div>
</div>

<!-- Papers in a simple list without pictures  -->
- [GASP: Gaussian Avatars with Synthetic Priors](), Jack Saunders, Vinay Namboodiri, Charlie Hewitt, Darren Cosker, Marek Kowalski, Nicholas Gyde, Shideh Rezaeifar, Tadas Baltrusaitis, Virginia Estellers, Yanan Jian, Yiye Chen, Benjamin Lundell, **In Submission 2024**.
- [Simultaneous Multi-Level Descriptor Learning and Semantic Segmentation for Domain-Specific Relocalization](https://ieeexplore.ieee.org/abstract/document/9561964), Xiaolong Wu*, **Yiye Chen\***, Cédric Pradalier, Patricio A. Vela, **ICRA 2021**.

# 📜 Academic Services
- **Conference Reviewer**: IROS’23-24, ICRA’24, CVPR’24-25, ICLR’25
- **Journal Reviewer**: The International Journal of Robotics Research (IJRR), IEEE Robotics and Automation Letters (RA-L), IEEE Transactions on Industrial Electronics (TIE)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->