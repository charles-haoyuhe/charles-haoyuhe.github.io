---
layout: single
author_profile: true
header:
    image: assets/images/mountain.jpeg
title: G'day mate 👋!
---
### About me
---
I am a research engineer at TikTok Sydney. Previously, I completed my PhD at  Monash University, supervised by [Asst. Prof. Bohan Zhuang](https://bohanzhuang.github.io/) and [Prof. Jianfei Cai](https://jianfei-cai.github.io/). Before joining [Zip Lab](https://ziplab.github.io/), I obtained my M.Phil. and Bachelor's degrees from the University of Sydney under the supervision of [Prof. Dacheng Tao](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/dacheng-tao.html) and [Dr. Jing Zhang](https://scholar.google.com/citations?user=9jH5v74AAAAJ&hl=en). 
My research interests include efficiency problems in deep learning scenarios, multi-modal LLMs, and segmentation tasks.

### News!
---
- [03/2024] Our paper [ESTA](https://arxiv.org/abs/2311.17352) on model stitching and adaptation got accepted by CVPR 2024!
- [12/2023] Our paper [SPViT](https://arxiv.org/abs/2111.11802) on visual Transformer pruning got accepted by TPAMI!
- [11/2023] I have joined TikTok Sydney as a research engineer intern working on efficient video LLMs!
- [09/2023] Our paper [MPVSS](https://arxiv.org/abs/2310.18954) on efficient video segmentation got accepted by NeurIPS 2023!
- [08/2023] Our paper [SPT](https://arxiv.org/abs/2303.08566) on adaptive parameter-efficient fine-tuning got accepted by ICCV 2023 for oral presentation!
- [07/2023] Our paper [EOPNet](https://arxiv.org/abs/2105.01241) on data-efficient human parsing got accepted by TPAMI!
- [02/2023] Our [survey paper](https://arxiv.org/abs/2302.01107) on efficient training of transformers got accepted by IJCAI 2023!
- [02/2023] Our paper [FASeg](https://arxiv.org/abs/2204.01244) on adaptive semantic segmentation got accepted by CVPR 2023!
- [09/2022] Our paper [Ecoformer](https://arxiv.org/abs/2209.09004) on energy-saving attentions got accepted by NeurIPS 2022!
- [12/2021] Our paper [LIT](https://arxiv.org/abs/2105.14217) on efficient transformer architectures got accepted by AAAI 2022!
- [07/2021] Our paper [HVT](https://arxiv.org/abs/2103.10619) on efficient transformer architectures got accepted by ICCV 2021!
- [12/2020] Our paper [POPNet](https://arxiv.org/abs/2012.11810) on data-efficient human parsing got accepted by AAAI 2021!
- [12/2019] Our paper [Grapy-ML](https://arxiv.org/abs/2012.11810) on cross-dataset human parsing got accepted by AAAI 2020!

### Papers
---


[comment]: <> (<div class="block">)

[comment]: <> (  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">)

[comment]: <> (  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>)

[comment]: <> (<div class="container">)

[comment]: <> (  <div class="row">)

[comment]: <> (    <div class="col-md-8 mx-auto">)

[comment]: <> (      <div class="row">)

[comment]: <> (        <div class="col-md-4">)

[comment]: <> (          <img src="assets/images/faseg.png" alt="Paper image" class="img-fluid">)

[comment]: <> (        </div>)

[comment]: <> (        <div class="col-md-8 d-flex align-items-center">)

[comment]: <> (          <div>)

[comment]: <> (            <h2>[Title of the paper]</h2>)

[comment]: <> (            <p><i>Author List</i></p>)

[comment]: <> (            <p>[Extra line of text to introduce the paper]</p>)

[comment]: <> (          </div>)

[comment]: <> (        </div>)

[comment]: <> (      </div>)

[comment]: <> (    </div>)

[comment]: <> (  </div>)

[comment]: <> (</div>)

[comment]: <> (</div>)


<head>
  <style>
    /* Set the overall container width and center it */
    .container {
      width: 120%;
      margin: 20px;
      display: flex;
    }

    .title {
    color: white;
    text-decoration: none; /* Remove underline */
    font-weight: bold; /* Make text bold */
    }

    
    /* Set the width and styling of the blocks */
    .block-left {
      width: 25%;
      padding: 2px;
      box-sizing: border-box;
      margin-right: 10px; 
    }

    .block-right {
      width: 50%;
      padding: 10px;
      box-sizing: border-box;
      margin-left: 10px; 
    }
    
    /* Set the margin between the blocks */
    .block + .block {
      margin-left: 30%;
    }
    
    /* Clear any floats after the container */
    .container::after {
      content: "";
      clear: both;
      display: table;
    }
    
    /* Set the styles for the text in the blocks */
    h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }
    
    .block-right p {
      font-size: 16px;
      line-height: 1.8;
      margin-bottom: 1.5px
    }

    .container img {
      width: 220px;
      height: 160px;
    }

    .ul {
    text-decoration: underline;
    }

  </style>
</head>

<div class="container">
  <div class="block-left">
      <img src="assets/images/esta.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Efficient Stitchable Task Adaptation [CVPR 2024] </p>
    <p><span class="ul">Haoyu He</span>, Zizheng Pan, Jing Liu, Jianfei Cai, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2111.11802"> PDF</a> / <a href="https://github.com/ziplab/SPViT"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/spvit.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Pruning Self-attentions into Convolutional Layers in Single Path [TPAMI 2024] </p>
    <p><span class="ul">Haoyu He</span>, Jing Liu, Zizheng Pan, Jianfei Cai, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2111.11802"> PDF</a> / <a href="https://github.com/ziplab/SPViT"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/mpvss.jpg" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Mask Propagation for Efficient Video Semantic Segmentation [NeurIPS 2023] </p>
    <p>Yuetian Weng, Mingfei Han, <span class="ul">Haoyu He</span>, Mingjie Li, Lina Yao, Xiaojun Chang, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2310.18954"> PDF</a> / <a href="https://github.com/ziplab/MPVSS"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/spt.jpg" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Sensitivity-Aware Visual Parameter-Efficient Tuning [ICCV 2023] (oral) </p>
    <p> <span class="ul">Haoyu He</span>, Jianfei Cai, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2303.08566"> PDF</a> / <a href="https://github.com/ziplab/spt"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/eopnet.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> End-to-end One-shot Human Parsing [TPAMI 2023] </p>
    <p> <span class="ul">Haoyu He</span>, Jing Zhang, Bohan Zhuang, Jianfei Cai, Dacheng Tao</p>
    <p><a href="https://arxiv.org/abs/2105.01241"> PDF</a> / <a href="https://github.com/Charleshhy/One-shot-Human-Parsing"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/survey.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> A Survey on Efficient Training of Transformers [IJCAI 2023] </p>
    <p> Bohan Zhuang, Jing Liu, Zizheng Pan, <span class="ul">Haoyu He</span>, Yuetian Weng, Chunhua Shen</p>
    <p><a href="https://arxiv.org/abs/2302.01107"> PDF</a></p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/faseg.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Dynamic Focus-aware Positional Queries for Semantic Segmentation [CVPR 2023] </p>
    <p> <span class="ul">Haoyu He</span>, Jianfei Cai, Zizheng Pan, Jing Liu, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2204.01244"> PDF</a> / <a href="https://github.com/ziplab/FASeg"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/ecoformer.jpg" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> EcoFormer: Energy-Saving Attention with Linear Complexity [NeurIPS 2022] (highlight) </p>
    <p>Jing Liu, Zizheng Pan, <span class="ul">Haoyu He</span>, Jianfei Cai, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2209.09004"> PDF</a> / <a href="https://github.com/ziplab/EcoFormer"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/lit.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Less is More: Pay Less Attention in Vision Transformers [AAAI 2022] </p>
    <p>Zizheng Pan, Bohan Zhuang, <span class="ul">Haoyu He</span>, Jing Liu, Jianfei Cai</p>
    <p><a href="https://arxiv.org/abs/2105.14217"> PDF</a> / <a href="https://github.com/ziplab/LIT"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/oneshot.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Progressive One-shot Human Parsing [AAAI 2021] (oral) </p>
    <p><span class="ul">Haoyu He</span>, Bohan Zhuang, Jing Zhang, Jianfei Cai, Dacheng Tao</p>
    <p><a href="https://arxiv.org/abs/2105.01241"> PDF</a> / <a href="https://github.com/Charleshhy/One-shot-Human-Parsing"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/grapy.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Grapy-ML: Graph Pyramid Mutual Learning for Cross-dataset Human Parsing [AAAI 2020] (oral) </p>
    <p><span class="ul">Haoyu He</span>, Jing Zhang, Qiming Zhang, Dacheng Tao</p>
    <p><a href="https://arxiv.org/abs/1911.12053"> PDF</a> / <a href="https://github.com/Charleshhy/Grapy-ML"> Code </a> </p>
  </div>
</div>

### Services
---
Reviewer for CVPR, ECCV, ICCV, NeurIPS, AAAI, TPAMI, and TMM.

### Teaching
---
Teaching associate for
- COMP5318 - Machine Learning and Data Mining (USYD, 2020)
- COMP5349 - Cloud Computing (USYD, 2020)
- FIT5047 - Fundamentals of Artificial Intelligence (Monash, 2023).
- FIT5201 - Machine Learning (Monash, 2023)
