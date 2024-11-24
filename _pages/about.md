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

Welcome to my homepage! I'm a undergraduate student of Computer Science at the University of Michigan and an Undergraduate Research Assistant at [SLED lab](https://sled.eecs.umich.edu/) and [VisionX](https://www.sainingxie.com/). Before transferring to the University of Michigan, I'm a student at the University of Nottingham, pursuing B.S. CS with AI. I'm interested in unsupervised/self-supervised learning and generative models, also interested in doing stupid things. [Feedbacks](https://forms.gle/kpGov9XbjaQoSiyh7) are always welcome~

I view artificial intelligence (AI) not as a follower of predefined human priors but as a dynamic learner --- similar to Searle’s Chinese Room, but free from rigid instructions. AI design reflects both the creativity and constraints of its creators, showcasing their vision while revealing their boundaries. My approach to AI emphasizes simplicity and clarity. Instead of small, incremental improvements, I aim to reimagine solutions from first principles. Inspired by Occam’s razor, I strive to minimize unnecessary complexity and supervision while ensuring consistent, meaningful understanding. My work aspires to **develop systems that learn meaning representations and generate consistent semantics autonomously with minimal supervision involved**.  My philosophy is to pursue minimal parameterizations that effectively represent the maximal information within the input data distribution. By embracing this vision, I design algorithms for 

1. self-supervised learning or learning with minimal semantic supervision and
2. generate consistent semantics given multimodal conditioning, with a primary application to visual generation (for now).

### <span style="color: red;"> I am actively looking for PhD position to start in 2025 Fall. </span>

# Group Members

[Ziqiao Ma](https://mars-tin.github.io/), [Xuweiyi Chen](https://xuweiyichen.github.io/), [Tian Xia](https://tianx-ia.github.io/)<span style="color: red;">(looking for PhD of 25 fall)</span>.

# News

- *2024.11*: &nbsp; One paper get accepted by TMLR.
- *2024.09*: &nbsp; One paper get accepted by NeurIPS2024.
- *2024.02*: &nbsp; [InfEdit](https://sled-group.github.io/InfEdit/) to appear in CVPR 2024.
- *2023.10*: &nbsp; [CycleNet](https://cyclenetweb.github.io/) to appear in NeurIPS 2023, and the preprint is available.
- *2022.11*: &nbsp; The preprint version and demos of ACE are available.

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/sab3r.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SAB3R: Semantic-Augmented Backbone in 3D Reconstruction

Xuweiyi Chen\*, Tian Xia\*, **Sihan XU**, Jianing Yang, Joyce Chai, Zezhou Cheng

Coming soon.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR</div><img src='images/UniCtrlTeaser.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="color: red;">**[TMLR]**</span>[UniCtrl: Improving the Spatiotemporal Consistency of Text-to-Video Diffusion Models via Training-Free Unified Attention Control](https://openreview.net/forum?id=x2uFJ79OjK)

Tian Xia\*, Xuweiyi Chen\*, **Sihan XU**<span style="color: red;">**†**</span>

<span style="color: red;">**†Correspondence**</span>

\[[**Project**](https://unified-attention-control.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2403.02332)\]\[[**Demo**](https://huggingface.co/spaces/Xuweiyi/UniCtrl)\]\[[**Code**](https://github.com/XuweiyiChen/UniCtrl)\]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/prompting_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<span style="color: red;">**[NeurIPS2024]**</span>[Multi-Object Hallucination in Vision-Language Models](https://multi-object-hallucination.github.io/)

Xuweiyi Chen\*, Ziqiao Ma\*, Xuejun Zhang\*, **Sihan XU**, Shengyi Qian, Jianing Yang, David F. Fouhey, Joyce Chai

\[[**Project**](https://multi-object-hallucination.github.io/)\]\[[**Arxiv**](https://arxiv.org/abs/2407.06192)\]\[[**Code**](https://github.com/sled-group/moh)\]\[[**Dataset**](https://huggingface.co/datasets/sled-umich/ROPE)\]
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PIXAI.ART</div><img src='images/pixai.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[PixAI.Art: Introducing A Versatile, Stable and High-Quality Anime Video Model](https://x.com/PixAI_Official/status/1755180853645459554)

Large scale and state of the art anime video model (at that time).
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EECS442</div><img src='images/442.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Rethink the Noise Prior of Initialization Gap in Video Diffusion Models](https://github.com/SihanXU/sihanxu.github.io/blob/main/docs/EECS_442_Project.pdf)

EECS 442 Cource Project
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TransferWiki</div><img src='images/transferwiki.com_.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Transferwiki](https://transferwiki.com/) - Founder

TransferWiki is a platform created to assist students from mainland China who are planning to transfer to universities abroad, particularly in the United States, Canada, and the United Kingdom. This platform addresses the challenges and information asymmetry faced by students during the transfer process.
  
</div>
</div> 

# Experience
- *2024.04 - present*, Research Intern @ VisionX advised by Prof. [Saining Xie](https://www.sainingxie.com/)
- *2024.01 - 2024.05*, Research Lead @ [Mewtant inc.](https://mewtant.io/) and [PixAI.art](https://pixai.art/)
- *2023.02 - present*, Undergraduate Research Assistant @ [SLED Research Lab](https://sled.eecs.umich.edu/) advised by Prof. [Joyce Chai](https://web.eecs.umich.edu/~chaijy/)

# Talks
- *2023.12*, Open Vocabulary Image Processing via Diffusion Models @ SLED.

# Honors and Awards
- University Honors.
- Silver (TOP 4%) at Google Smartphone Decimeter Challenge Competition.
- TOP 1 at UoN Hackathon.

# Educations
- *2022.09 - 2025.06*, B.S Computer Science with AI, University of Michigan (Pursuing **Honor Degree**)
- *2020.09 - 2022.06*, BSc Hons Computer Science with AI, University of Nottingham (**First Class Honor**)

# Service
- Conference reviewer: CVPR, EMNLP, ICLR

<div style="width: 200px; height: 200px; display: flex; justify-content: center; align-items: center; background-color: #f0f0f0; border: 1px solid #e0e0e0; border-radius: 8px;">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=z4YwVPEqLess2QRcopfZP470E6z9y3FHwqrYKv6f2AM&cl=000000&w=a"></script>
</div>
<p align="left" style="display: none;"> <img src="https://komarev.com/ghpvc/?username=sihanxu&label=Profile%20views&color=0e75b6&style=flat" alt="sihanxu" /> </p>
