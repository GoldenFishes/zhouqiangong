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

# About Me

# Educations
- *2020.09 - 2024.06*, Bachelor of Science. in Data Science and Big Data Technology, Beijing Institute of Technology, Zhuhai, China.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Det-SAM2:Technical Report on the Self-Prompting Segmentation Framework Based on Segment Anything Model 2**

[**Paper**](https://arxiv.org/abs/2411.18977)  [**Project**](https://github.com/motern88/Det-SAM2) <strong><span class='show_paper_citations' data='AunSnE4AAAAJ:9yKSN-GCB0IC'></span></strong>

We developed a real-time video stream inference pipeline based on SAM2, which integrates an object detection model to automatically provide conditional prompts for long video segmentation.
This is the first fully functional self-prompted SAM2 framework for long videos. It supports advanced features such as online addition of new categories during inference and preloading a memory bank.
Furthermore, the pipeline maintains constant GPU and CPU memory usage throughout, enabling efficient inference on arbitrarily long videos.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HiLight: Technical Report on the Motern AI Video Language Model**

[**Paper**](https://arxiv.org/abs/2407.07325)  [**Project**](https://github.com/motern88/HiLight) <strong><span class='show_paper_citations' data='AunSnE4AAAAJ:d1gkVwhDpl0C'></span></strong>

We first design a VideoEncoder with finer-grained modality alignment by introducing a contrastive loss between patches and tokens based on CLIP-ViP.
Then, we build a dual-tower vision encoder composed of the improved CLIP-ViP and Long-CLIP, which extracts both video and image features.
The fused visual features are fed into the Gemma-2B language model, enabling video-based dialogue capability.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**FreeV:Free Lunch in MultiModal Diffusion U-ViT**

[**Paper**](https://www.authorea.com/doi/full/10.36227/techrxiv.24633840.v1)  [**Project**](https://github.com/GoldenFishes/FreeV) <strong><span class='show_paper_citations' data='AunSnE4AAAAJ:u-x6o8ySG0sC'></span></strong>

We propose FreeV, an adaptation of the FreeU strategy—originally designed for U-Net—into the Transformer-based U-ViT architecture.
FreeV significantly improves generation quality without additional training or fine-tuning.
The key insight is to balance the contributions from the backbone, skip connections, and fused features within U-ViT, maximizing its strengths while addressing its limitations in feature fusion.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Optimal Use of Attention Mechanisms: Comparative Study in U-Net for Image Segmentation Tasks**

[**Paper**](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13063/130630L/Optimal-use-of-attention-mechanisms--comparative-study-in-U/10.1117/12.3021498.short) <strong><span class='show_paper_citations' data='AunSnE4AAAAJ:u5HHmVD_uO8C'></span></strong>

The study finds that while attention can enhance channel-wise feature weighting, it may negatively affect the backbone's convolutional feature extraction.
However, it effectively complements the encoder-decoder structure by improving high-level semantic representation.
</div>
</div>

