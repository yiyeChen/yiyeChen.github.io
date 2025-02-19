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

Hello! I am a final year Ph.D. student at Institute for Robotics and Intelligent Machines, Georgia Institute of Technology, advised by [Prof. Patrico A. Vela](https://pvela.gatech.edu/). 
I am also fortunate to collaborate with [Dr. Benjamin Lundell](https://www.linkedin.com/in/benjamin-lundell) and [Dr. Harpreet Sawhney](https://scholar.google.ca/citations?hl=en&user=73FHLFAAAAAJ&view_op=list_works&sortby=pubdate) from Microsoft.

My research interest lies in computer vision, language processing, and the application of these fields to develop robotic intelligence. Specifically, I am working on Robotic Grasping (including both 6-DoF and planar), Language Command Understanding, and addressing Open World challenges. More recently, I am also developing algorithms that leverage Large Language Models or Vision-Language Models to enable generalizable planning or spatial understanding capacities.

[Here](files/resume.pdf) is my resume/CV (updated October 2024). I am currently open to full-time opportunities in industry. Feel free to reach out!

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
<div class='industrial-box'>
  <div class="industrial-text">
    <ul>
      <li><strong>2024.05 - 2024.08</strong>: Research Scientist Internship, <a href="https://www.microsoft.com/en-us/research/">Microsoft Research</a>.</li>
        <ul>
          <li><strong>Mentor:</strong> Ben Lundell; <strong>Co-Mentor:</strong>Harpreet Sawhney</li>
          <li><strong>Topic:</strong> Reasoning on scene graphs with Large Language Models (LLMs).</li>
          <li>Redmond, WA, United States.</li>
        </ul>
    </ul>
  </div>
  <div class="industrial-image">
    <img src='images/microsoft.png' alt="Microsoft Logo" width="100%">
  </div>
</div>
<div class='industrial-box'>
  <div class="industrial-text">
    <ul>
      <li><strong>2023.05 - 2023.08</strong>: Applied Scientist Internship, <a href="https://www.amazon.science/research-areas/robotics">Amazon Robotics</a>.</li>
        <ul>
          <li><strong>Manager:</strong> Sisir Karumanchi; <strong>Mentor:</strong>Shuai Han</li>
          <li><strong>Topic:</strong> Uncertainty estimation on deep vision models for quantifying the robotic action reliability.</li>
          <li>Seattle, WA, United States.</li>
        </ul>
    </ul>
  </div>
  <div class="industrial-image">
    <img src='images/amazon.png' alt="Microsoft Logo" width="100%">
  </div>
</div>
<!-- - *2024.05 - 2024.08*: Research Scientist Internship, [Microsoft Research](https://www.microsoft.com/en-us/research/). Redmond, WA, United States.
- *2023.05 - 2023.08*: Applied Scientist Internship, [Amazon Robotics](https://www.amazon.science/research-areas/robotics). Seattle, WA, United States. -->

# 📝 Publications 
(\* denotes equal contribution)

<!-- RwR -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='images/RwR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A Schema-Guided Reason-while-Retrieve framework for Reasoning on Scene Graphs with Large-Language-Models (LLMs) (_In submission_)**](https://arxiv.org/abs/2502.03450)

**Yiye Chen**, Harpreet Sawhney, Nicholas Gyde, Yanan Jian, Jack Saunders, Patricio A. Vela, Benjamin Lundell

[Code(Coming Soon)]() | [Project(Coming Soon)]()
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A two-agent LLMs framework for reasoning and planning on scene graphs, leveraging their reasoning, code-writing, and communication skills.
</div>
</div>

<!-- WDiscOOD -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/ICCV2023_WDiscOOD.png' alt="sym" width="85%"></div></div>
<div class='paper-box-text' markdown="1">

[**WDiscOOD: Out-of-Distribution Detection via Whitened Linear Discriminant Analysis**](https://openaccess.thecvf.com/content/ICCV2023/html/Chen_WDiscOOD_Out-of-Distribution_Detection_via_Whitened_Linear_Discriminant_Analysis_ICCV_2023_paper.html)

**Yiye Chen**, Yunzhi Lin, Ruinian Xu, Patricio A. Vela

[Code](https://github.com/ivalab/WDiscOOD) | [Poster](files/poster_WDiscOOD.pdf)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A visual representation analysis approach to identify when a deep learning model doesn't know in the open-world setting.
- Showing effectiveness in various vision backbones, including ResNet, Vision Transformer, and CLIP vision encoder.
</div>
</div>

<!-- LEAP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/ICLR2023_LEAP_teaser.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Planning with Language Models through Iterative Energy Minimization**](https://openreview.net/forum?id=cVFD6qE8gnY)

Hongyi Chen\*, Yilun Du\*, **Yiye Chen\***, Patricio A. Vela, Joshua B. Tenenbaum

[Project](https://hychen-naza.github.io/projects/LEAP/index.html) | [Code](https://github.com/ivalab/WDiscOOD)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- An energy-based learning and interative sampling method for action sequence planning with Transformer model.
</div>
</div>

<!-- KGNv2 -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2023</div><img src='images/graphAbs_KGNv2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**KGNv2: Separating Scale and Pose Prediction for Keypoint-based 6-DoF Grasp Synthesis on RGB-D input**](https://ieeexplore.ieee.org/document/10342514)

**Yiye Chen**; Ruinian Xu; Yunzhi Lin; Hongyi Chen; Patricio A. Vela

[Code](https://github.com/ivalab/KGN) | [Presentation](https://youtu.be/gK30iMHPr4I) | [Poster](files/poster_KGNv2.pdf) | [Supplementary](https://youtu.be/XDpdTdHo5eU)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Enhances Keypoint-GraspNet (see below) by addressing scale-related issues, where scale refers to the distance of a pose towards the single-view camera.
</div>
</div>

<!-- KGN -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2023</div><img src='images/ICRA23_KGN.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[**Keypoint-GraspNet: Keypoint-based 6-DoF Grasp Generation from the Monocular RGB-D input**](https://ieeexplore.ieee.org/abstract/document/10161284)

**Yiye Chen**; Yunzhi Lin; Ruinian Xu; Patricio A. Vela

[Code](https://github.com/ivalab/KGN) | [Presentation](https://youtu.be/oNHZ05kHBgI) | [Poster](files/poster_KGN.pdf) | [Supplementary](https://youtu.be/cT9lvTajRdA)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A keypoint-based approach for generating 6-DoF grasp poses from single-view RGB-D input.
</div>
</div>

<!-- CGNet -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2021</div><img src='images/ICRA21_CGNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A Joint Network for Grasp Detection Conditioned on Natural Language Commands**](https://ieeexplore.ieee.org/abstract/document/9561994)

**Yiye Chen**; Ruinian Xu; Yunzhi Lin; Patricio A. Vela

[Presentation](https://youtu.be/tridtJes7uI) | [Supplementary](https://youtu.be/cpUbk5JBNvY?si=ygHC_R8E-HnS-PcL)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A language-conditioned robotic grasping method by fusing the visual and language embeddings.
</div>
</div>

<!-- Papers in a simple list without pictures  -->
- [GASP: Gaussian Avatars with Synthetic Priors](https://arxiv.org/abs/2412.07739), Jack Saunders, Charlie Hewitt, Yanan Jian, Marek Kowalski, Tadas Baltrusaitis, **Yiye Chen**, Darren Cosker, Virginia Estellers, Nicholas Gydé, Vinay Namboodiri, Benjamin Lundell, **In Submission 2024**.
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