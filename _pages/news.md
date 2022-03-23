---
layout: single
title: "News"
permalink: /news/
author_profile: true
classes: wide

feature_row7:
  - image_path: assets/images/humus-net.png
    title: "03/15/2022"
    excerpt: "We published a preprint version of our new work on HUMUS-Net: a Transformer-convolutional hybrid model for accelerated MRI reconstruction. Common deep learning reconstruction techniques in MRI typically utilize convolution layers as the primary processing unit, however convolution kernels struggle to model long-range pixel dependencies in images and are content-independent. On the other hand, Transformer architectures are free from these limitations and are rapidly gaining ground in a range of vision applications. Our proposed architecture combines the benefits of both worlds and [achieves state-of-the-art results](https://fastmri.org/leaderboards) on the [fastMRI dataset](https://fastmri.med.nyu.edu/), the largest publicly available MRI dataset."
    url: "https://arxiv.org/abs/2203.08213"
    btn_label: "Paper"
    btn_class: "btn--primary"
    url2: "/assets/slides/HUMUS_Net_slides.pdf"
    btn_label2: "Slides"
    btn_class2: "btn--primary"
    url3: "https://github.com/z-fabian/HUMUS-Net"
    btn_label3: "Code"
    btn_class3: "btn--primary"

feature_row6:
  - image_path: assets/images/research-festival2021-poster-small.png
    title: "10/29/2021"
    excerpt: "Today we hosted the [11th Annual Research Festival](https://minghsiehece.usc.edu/11th-annual-mhi-research-festival/) at the Ming Hsieh ECE department with close to 100 posters and guided lab tours organized by the [Dynamic Imaging Science Center (DISC)](https://sites.usc.edu/disc/) showcasing their new, unique high-performance low-field MRI scanner. My poster on [MRAugment](/publications/2021-07-01-data-augmentation-for-deep-learning) has won the _Best Poster - Honorable Mention_ award."
    url: "assets/posters/research_festival2021_poster.pdf"
    btn_label: "Poster"
    btn_class: "btn--primary"

feature_row5:
  - image_path: assets/images/mhi-scholars.png
    title: "09/28/2021"
    excerpt: "I have been selected as a [Ming Hsieh PhD Scholar](https://minghsiehece.usc.edu/mhi-home/mhi-mhi-scholars/) for 2021-2022 along with Haleh Akrami, Hefei Liu, Rodrigo Lobos, Qinyi Luo and Qiaochu Zhang. We are going to work together to organize professional events and support our PhD community. You can find the slides for my presentation _Overcoming the data bottleneck in AI for the sciences_ presented at the MHI Scholar Finalist Talk Competition below."
    url: "assets/slides/mhi2021_slides.pdf"
    btn_label: "Finalist Talk Slides"
    btn_class: "btn--primary"

feature_row4:
  - image_path: assets/images/mraugment-flowchart.png
    title: "07/01/2021"
    excerpt: "Our paper [Data augmentation for deep learning based accelerated MRI reconstruction with limited data](/publications/2021-07-01-data-augmentation-for-deep-learning) has been accepted for short talk at ICML 2021. In this work we propose **MRAugment**, a data augmentation pipeline for MRI that improves MRI image reconstruction quality when training data is scarce and helps training more robust deep learning models against various forms of distributions shift (different scanner models, anatomies) and hallucinations.  "
    url: "http://proceedings.mlr.press/v139/fabian21a/fabian21a.pdf"
    btn_label: "Paper"
    btn_class: "btn--primary"
    url2: "https://github.com/z-fabian/MRAugment"
    btn_label2: "Code"
    btn_class2: "btn--primary"

feature_row3:
  - image_path: assets/images/byol-pic.png
    image_caption: "Grill et al., Bootstrap Your Own Latent - A New Approach to Self-Supervised Learning, NeurIPS, 2020"
    title: "03/12/2021"
    excerpt: "I gave a talk on two popular self-supervised learning techniques [BYOL (Grill et al.)](https://proceedings.neurips.cc/paper/2020/hash/f3ada80d5c4ee70142b17b8192b2958e-Abstract.html) and [SimSiam (Chen et al.)](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Exploring_Simple_Siamese_Representation_Learning_CVPR_2021_paper.html) at our _Learning from Signals and Data_ journal club. Self-supervised learning algorithms have been rapidly catching up with supervised methods recently. They typically build upon a siamese architecture that can learn good image representations from unlabelled data. Thus, these methods have great potential in scientific applications where labelled training data is scarce or extremely costly to acquire."
    url: "/assets/slides/BYOL_SimSiam_slides.pdf"
    btn_label: "Slides"
    btn_class: "btn--primary"

feature_row2:
  - image_path: assets/images/3d-recon.png
    title: "01/18/2021"
    excerpt: "Our paper [3D phase retrieval at nano-scale via accelerated Wirtinger flow](/publications/2021-01-18-3d-phase-retrieval-at-nano-scale) has been accepted at EUSIPCO 2020. High-resolution imaging of small 3D structures is an important problem in biology (protein complexes) and microelectronics (chip manufacturing). Our work introduces a fast and accurate algorithm that can recover the 3D structure of such objects more accurately and from fewer projections than previous techniques."
    url: "https://ieeexplore.ieee.org/abstract/document/9287703"
    btn_label: "Conference Paper"
    btn_class: "btn--primary"
    url2: "https://arxiv.org/pdf/2002.11785.pdf"
    btn_label2: "Extended arXiv"
    btn_class2: "btn--primary"

feature_row1:
  - image_path: assets/images/transfer-lowerbounds.png
    title: "12/12/2020"
    excerpt: "Our work [Minimax lower bounds for transfer learning with linear and one-hidden layer neural networks](/publications/2020-12-12-minimax-lower-bounds-for-transfer-learning) has been accepted at NeurIPS 2020 for poster presentation. We investigate how the number of source samples and the distance between datasets impact model generalization on a target dataset. We introduce a novel metric, the so called _transfer distance_, that quantifies how challenging it is to transfer knowledge from one dataset to another. "
    url: "https://proceedings.neurips.cc/paper/2020/file/151d21647527d1079781ba6ae6571ffd-Paper.pdf"
    btn_label: "Paper"
    btn_class: "btn--primary"

feature_row0:
  - image_path: assets/images/cyclegan-pic.png
    image_caption: "Zhu et al., _Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks_, ICCV, 2017"
    title: "10/23/2020"
    excerpt: "I gave a talk on [CycleGAN (Zhu et al.)](https://openaccess.thecvf.com/content_iccv_2017/html/Zhu_Unpaired_Image-To-Image_Translation_ICCV_2017_paper.html) and its applications in medical imaging at our _Learning from Signals and Data_ journal club. CycleGAN is a powerful image-to-image translation network that learns to map images of a certain domain (e.g. landscape photos) to another domain (e.g. paintings) and vice versa *without seeing corresponding pairs from these two domains*. The key idea is to make sure that if we translate an image and then translate it back, we recover the original image. CycleGAN and its variants have been very successful in cross-modal image synthesis in medical tasks. That is it can create synthetic images of a target modality (e.g. MRI) from images of a different source modality (e.g. CT)."
    url: "/assets/slides/cycleGAN_slides.pdf"
    btn_label: "Slides"
    btn_class: "btn--primary"
---
{% include feature_row id="feature_row7" type="left" %}
{% include feature_row id="feature_row6" type="left" %}
{% include feature_row id="feature_row5" type="left" %}
{% include feature_row id="feature_row4" type="left" %}
{% include feature_row id="feature_row3" type="left" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row1" type="left" %}
{% include feature_row id="feature_row0" type="left" %}
