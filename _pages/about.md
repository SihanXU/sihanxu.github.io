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

Welcome to my homepage! I'm a junior student of Computer Science at the University of Michigan and an Undergraduate Research Assistant at [SLED lab](https://sled.eecs.umich.edu/) and [VisionX](https://www.sainingxie.com/). Before transferring to the University of Michigan, I'm a student at the University of Nottingham, pursuing B.S. CS with AI. I'm interested in unsupervised/self-supervised learning and generative models, also interested in doing stupid things. [Feedbacks](https://forms.gle/kpGov9XbjaQoSiyh7) are always welcome~

My research journey began with a strong focus on generative models in computer vision, particularly in generative adversarial networks (GANs) and diffusion models. Currently, my work has expanded to encompass a broader range of topics, including computer vision, natural language processing, 3D models and robotics. 

I think I will focus on the following topics from **first principles** and **Occam's razor** in the future:

- **Multimodal Representation Learning, especially in unsupervised methods.**

- **Causal Generative Model, not only just about autoregressive models or diffusion models.**

- **Machine Learning, something more than current learning approaches.**

### <span style="color: red;"> I am actively looking for PhD position to start in 2025 Fall. </span>

# News

- *2024.09*: &nbsp; One paper get accepted by NeurIPS2024.
- *2024.04*: &nbsp; Join VisionX advised by Prof. [Saining Xie](https://www.sainingxie.com/) as a Research Intern.
- *2024.03*: &nbsp; Preprint of [UniCtrl](https://arxiv.org/abs/2403.02332) is available.
- *2024.02*: &nbsp; [InfEdit](https://sled-group.github.io/InfEdit/) to appear in CVPR 2024.
- *2024.01*: &nbsp; Join [Mewtant inc.](https://mewtant.io/) and [PixAI.art](https://pixai.art/) as a ML Research Engineer.
- *2023.10*: &nbsp; [CycleNet](https://cyclenetweb.github.io/) to appear in NeurIPS 2023, and the preprint is available.
- *2022.11*: &nbsp; The preprint version and demos of ACE are available.

# Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/prompting_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="color: red;">**[NeurIPS2024]**</span>[Multi-Object Hallucination in Vision-Language Models](https://multi-object-hallucination.github.io/)

Xuweiyi Chen\*, Ziqiao Ma\*, Xuejun Zhang\*, **Sihan XU**, Shengyi Qian, Jianing Yang, David F. Fouhey, Joyce Chai

\[[**Project**](https://multi-object-hallucination.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2407.06192)\]\[[**Code**](https://github.com/sled-group/moh)\]\[[**Dataset**](https://huggingface.co/datasets/sled-umich/ROPE)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/UniCtrlTeaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[UniCtrl: Improving the Spatiotemporal Consistency of Text-to-Video Diffusion Models via Training-Free Unified Attention Control](https://unified-attention-control.github.io/)

Xuweiyi Chen\*, Tian Xia\*, **Sihan XU**<span style="color: red;">**†**</span>

<span style="color: red;">**†Correspondence**</span>

\[[**Project**](https://unified-attention-control.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2403.02332)\]\[[**Demo**](https://huggingface.co/spaces/Xuweiyi/UniCtrl)\]\[[**Code**](https://github.com/XuweiyiChen/UniCtrl)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/infedit_gif.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="color: red;">**[CVPR2024]**</span>[Inversion-Free Image Editing with Natural Language](https://openaccess.thecvf.com/content/CVPR2024/html/Xu_Inversion-Free_Image_Editing_with_Language-Guided_Diffusion_Models_CVPR_2024_paper.html)

**Sihan XU\***, Yidong Huan\*, Jiayi Pan, Ziqiao Ma, Joyce Chai

<span style="color: red;">**\*First author**</span>

\[[**Project**](https://sled-group.github.io/InfEdit/)\]\[[**Arxiv**](https://arxiv.org/abs/2312.04965)\]\[[**Demo**](https://huggingface.co/spaces/sled-umich/InfEdit)\]\[[**Code**](https://github.com/sled-group/InfEdit)\]

\[[<span style="color: red;">**UMich CSE News Coverage**</span>](https://cse.engin.umich.edu/stories/fifteen-papers-by-cse-researchers-at-cvpr-2024)\]

\[[<span style="color: red;">**🏆Top2 at GenAI-Arena Leaderboard**</span>](https://huggingface.co/spaces/TIGER-Lab/GenAI-Arena)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/cycle.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="color: red;">**[NeurIPS2023]**</span>[CycleNet: Rethinking Cycle Consistency in Text-Guided Diffusion for Image Manipulation](https://proceedings.neurips.cc/paper_files/paper/2023/hash/21293a43d0321c5602dd893be2c2332b-Abstract-Conference.html)

**Sihan XU\***, Ziqiao Ma\*, Yidong Huang, Honglak Lee, Joyce Chai

<span style="color: red;">**\*First author**</span>

\[[**Project**](https://cyclenetweb.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2310.13165)\]\[[**Code**](https://github.com/sled-group/CycleNet)\]

\[[<span style="color: red;">**UMich CSE News Coverage**</span>](https://cse.engin.umich.edu/stories/thirteen-papers-by-cse-researchers-presented-at-neurips-2023)\]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Michigan AI Symposium 2022</div><img src='images/ace-model.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[ACE: Zero-Shot Image to Image Translation via Pretrained Auto-Contrastive-Encoder](https://raw.githubusercontent.com/SihanXU/sihanxu.github.io/main/docs/ACE-Preprint.pdf)

**Sihan XU**\*<span style="color: red;">**†**</span>, Zelong Jiang\*, Ruisi Liu\*, Kaikai Yang, Zhijie Huang

<span style="color: red;">**\*First author and †Correspondence**</span>

\[[**Arxiv**](https://arxiv.org/abs/2302.11705)\]\[[**Demo**](https://github.com/SihanXU/ACE/tree/main/Zero%20shot%20Image%20to%20Image%20Translation)\]
</div>
</div>

# Projects

- [PixAI.art Anime Video Model](https://x.com/PixAI_Official/status/1755180853645459554)

  Large scale and state of the art anime video model (at that time).
  
- [Transferwiki](https://transferwiki.com/) - Founder
  
  TransferWiki is a platform created to assist students from mainland China who are planning to transfer to universities abroad, particularly in the United States, Canada, and the United Kingdom. This platform addresses the challenges and information asymmetry faced by students during the transfer process.

# Experience
- *2024.04 - present*, Research Intern @ VisionX advised by Prof. [Saining Xie](https://www.sainingxie.com/)
- *2024.01 - 2024.05*, Research Lead @ [Mewtant inc.](https://mewtant.io/) and [PixAI.art](https://pixai.art/)
- *2023.02 - present*, Undergraduate Research Assistant @ [SLED Research Lab](https://sled.eecs.umich.edu/) advised by Prof. [Joyce Chai](https://web.eecs.umich.edu/~chaijy/)

# Honors and Awards
- University Honors
- Silver (TOP 4%) at Google Smartphone Decimeter Challenge Competition.
- TOP 1 at UoN Hackathon.

# Educations
- *2022.09 - 2025.06*, B.S Computer Science with AI, University of Michigan, Ann Arbor (Pursuing **Honor Degree**)
- *2020.09 - 2022.06*, BSc Hons Computer Science with AI, University of Nottingham, Ningbo China (**First Class Honor**)

# Service
- Conference reviewer: CVPR, EMNLP, ICLR

<div style="width: 200px; height: 200px;">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=z4YwVPEqLess2QRcopfZP470E6z9y3FHwqrYKv6f2AM&cl=ffffff&w=a"></script>
</div>
<p align="left" style="display: none;"> <img src="https://komarev.com/ghpvc/?username=sihanxu&label=Profile%20views&color=0e75b6&style=flat" alt="sihanxu" /> </p>
