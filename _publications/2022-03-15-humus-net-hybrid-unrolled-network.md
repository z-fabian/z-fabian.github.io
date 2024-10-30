---
title: "HUMUS-Net: Hybrid unrolled multi-scale network architecture for accelerated MRI reconstruction"
collection: publications
permalink: /publications/2022-03-15-humus-net-hybrid-unrolled-network
excerpt: 'Fabian, Z., Tinaz, B. and Soltanolkotabi, M., NeurIPS 2022'
date: 2022-12-01

---

Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi <br>
Published in *Advances in Neural Information Processing Systems*, 2022

In accelerated MRI reconstruction, the anatomy of a patient is recovered from a set of under-sampled and noisy measurements. Deep learning approaches have been proven to be successful in solving this ill-posed inverse problem and are capable of producing very high quality reconstructions. However, current architectures heavily rely on convolutions, that are content-independent and have difficulties modeling long-range dependencies in images. Recently, Transformers, the workhorse of contemporary natural language processing, have emerged as powerful building blocks for a multitude of vision tasks. These models split input images into non-overlapping patches, embed the patches into lower-dimensional tokens and utilize a self-attention mechanism that does not suffer from the aforementioned weaknesses of convolutional architectures. However, Transformers incur extremely high compute and memory cost when 1) the input image resolution is high and 2) when the image needs to be split into a large number of patches to preserve fine detail information, both of which are typical in low-level vision problems such as MRI reconstruction, having a compounding effect. To tackle these challenges, we propose HUMUS-Net, a hybrid architecture that combines the beneficial implicit bias and efficiency of convolutions with the power of Transformer blocks in an unrolled and multi-scale network. HUMUS-Net extracts high-resolution features via convolutional blocks and refines low-resolution features via a novel Transformer-based multi-scale feature extractor. Features from both levels are then synthesized into a high-resolution output reconstruction. Our network establishes new state of the art on the largest publicly available MRI dataset, the fastMRI dataset. We further demonstrate the performance of HUMUS-Net on two other popular MRI datasets and perform fine-grained ablation studies to validate our design.

<a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/a1bb3f96e255ae1e04325ae166bcef0f-Paper-Conference.pdf" class="btn btn--info btn--large">Paper</a>
<a href="/assets/posters/humus_neurips2022_poster.png" class="btn btn--success btn--large">Poster</a>
<a href="/assets/slides/HUMUS_Net_slides.pdf" class="btn btn--warning btn--large">Slides</a>
<a href="https://github.com/z-fabian/HUMUS-Net" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Code</a>

<b>Recommended citation</b>

Fabian, Z. Tinaz, B. and Soltanolkotabi, M., 2022, December. &quot;HUMUS-Net: Hybrid unrolled multi-scale network architecture for accelerated MRI reconstruction&quot;.  In *Advances in Neural Information Processing Systems*
{: .notice}

<b>BibTeX<b>

```bibtex
@article{fabian2022humus,
  title={Humus-net: Hybrid unrolled multi-scale network architecture for accelerated mri reconstruction},
  author={Fabian, Zalan and Tinaz, Berk and Soltanolkotabi, Mahdi},
  journal={Advances in Neural Information Processing Systems},
  volume={35},
  pages={25306--25319},
  year={2022}
}
```
