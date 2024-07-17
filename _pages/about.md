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
# About me

Hello! My name is Xijun Wang, an undergraduate student at Xidian University. If you are interested in me and seek for cooperation, feel free to contact me.

My research interest includes Deep Learning and Computer Vision.

<!-- My research interest includes deep learning, computer vision and diffusion models. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.12*: 🎉 Our paper (Adv-Diffusion) is accepted by AAAI 2024.

# 📝 Publications 

<!-- Adv-Diffusion -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/adv-diffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adv-Diffusion: Imperceptible Adversarial Face Identity Attack via Latent Diffusion Model](https://arxiv.org/abs/2312.11285)

Decheng Liu*, **Xijun Wang\***, Chunlei Peng<sup>†</sup>, Nannan Wang, Ruimin Hu, Xinbo Gao

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=ppPYO_EAAAAJ&citation_for_view=ppPYO_EAAAAJ:d1gkVwhDpl0C) | [**Code**](https://github.com/kopper-xdu/Adv-Diffusion)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>
<!-- Adv-Diffusion -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.09 - 2025.06*, undergraduate student at Xidian University.

# 💻 Internships
- *2024.04 - now*, intern at Shanghai AI Lab.