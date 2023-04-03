---
layout: single
author_profile: true
header:
    image: assets/images/mountain.jpeg
title: G'day mate 👋!
---
### About me
---
I am a second-year Ph.D. student of Department of DSAI, Faculty of IT, Monash University, supervised by [Asst. Prof. Bohan Zhuang](https://bohanzhuang.github.io/) and [Prof. Jianfei Cai](https://jianfei-cai.github.io/). Before joining [Zip Group](https://ziplab.github.io/), I obtained my M.Phil. degree from University of Sydney, under the supervision of [Prof. Dacheng Tao](https://www.sydney.edu.au/engineering/about/our-people/academic-staff/dacheng-tao.html) and [Dr. Jing Zhang](https://scholar.google.com/citations?user=9jH5v74AAAAJ&hl=en). 
I am interested in the efficiency problems in deep learning scenarios and segmentation tasks! I am looking for an internship position!  

### News!
---
- [02/2023] Our paper [FASeg](https://github.com/ziplab/spt) got accepted by CVPR 2023!
- [09/2022] Our paper [Ecoformer](https://arxiv.org/abs/2209.09004) got accepted by NeurIPS 2022!
- [12/2021] Our paper [LIT](https://arxiv.org/abs/2105.14217) got accepted by AAAI 2022!
- [07/2021] Our paper [HVT](https://arxiv.org/abs/2103.10619) got accepted by ICCV 2021!
- [12/2020] Our paper [POPNet](https://arxiv.org/abs/2012.11810) got accepted by AAAI 2021!
- [12/2019] Our paper [Grapy-ML](https://arxiv.org/abs/2012.11810) got accepted by AAAI 2020!

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
      <img src="assets/images/spt.jpg" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Sensitivity-Aware Visual Parameter-Efficient Tuning </p>
    <p> <span class="ul">Haoyu He</span>, Jianfei Cai, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2303.08566"> PDF</a> / <a href="https://github.com/ziplab/spt"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/faseg.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Dynamic Focus-aware Positional Queries for Semantic Segmentation (CVPR 2023) </p>
    <p> <span class="ul">Haoyu He</span>, Jianfei Cai, Zizheng Pan, Jing Liu, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2204.01244"> PDF</a> / <a href="https://github.com/ziplab/FASeg"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/ecoformer.jpg" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> EcoFormer: Energy-Saving Attention with Linear Complexity (NeurIPS 2023) </p>
    <p>Jing Liu, Zizheng Pan, <span class="ul">Haoyu He</span>, Jianfei Cai, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2209.09004"> PDF</a> / <a href="https://github.com/ziplab/EcoFormer"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/spvit.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Pruning Self-attentions into Convolutional Layers in Single Path </p>
    <p><span class="ul">Haoyu He</span>, Jing Liu, Zizheng Pan, Jianfei Cai, Jing Zhang, Dacheng Tao, Bohan Zhuang</p>
    <p><a href="https://arxiv.org/abs/2111.11802"> PDF</a> / <a href="https://github.com/ziplab/SPViT"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/lit.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Less is More: Pay Less Attention in Vision Transformers (AAAI 2022) </p>
    <p>Zizheng Pan, Bohan Zhuang, <span class="ul">Haoyu He</span>, Jing Liu, Jianfei Cai</p>
    <p><a href="https://arxiv.org/abs/2105.14217"> PDF</a> / <a href="https://github.com/ziplab/LIT"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/popnet.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Progressive One-shot Human Parsing (AAAI 2021) </p>
    <p><span class="ul">Haoyu He</span>, Bohan Zhuang, Jing Zhang, Jianfei Cai, Dacheng Tao</p>
    <p><a href="https://arxiv.org/abs/2105.01241"> PDF</a> / <a href="https://github.com/Charleshhy/One-shot-Human-Parsing"> Code </a> </p>
  </div>
</div>

<div class="container">
  <div class="block-left">
      <img src="assets/images/grapy.png" alt="Paper image" class="img-fluid">
  </div>
  <div class="block-right">
    <p class="title"> Grapy-ML: Graph Pyramid Mutual Learning for Cross-dataset Human Parsing (AAAI 2020) </p>
    <p><span class="ul">Haoyu He</span>, Jing Zhang, Qiming Zhang, Dacheng Tao</p>
    <p><a href="https://arxiv.org/abs/1911.12053"> PDF</a> / <a href="https://github.com/Charleshhy/Grapy-ML"> Code </a> </p>
  </div>
</div>

### Services
---
Reviewer for CVPR 2022, ECCV 2022, CVPR 2023, ICCV 2023, NeurIPS 2023, TPAMI, and TMM.

### Teaching
---
COMP5318 (USYD), COMP5349 (USYD), FIT5201 (Monash), FIT5047 (Monash).