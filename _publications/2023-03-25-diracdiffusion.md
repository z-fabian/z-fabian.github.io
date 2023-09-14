---
title: "DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency"
collection: publications
permalink: /publications/2023-03-25-diracdiffusion
excerpt: 'Fabian, Z., Tinaz, B. and Soltanolkotabi, M., 2023, <i> arXiv:2303.14353</i>'
date: 2023-03-25

---

Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi <br>
<i>arXiv:2303.14353</i>

Diffusion models have established new state of the art in a multitude of computer vision tasks, including image restoration. Diffusion-based inverse problem solvers generate reconstructions of exceptional visual quality from heavily corrupted measurements. However, in what is widely known as the perception-distortion trade-off, the price of perceptually appealing reconstructions is often paid in declined distortion metrics, such as PSNR. Distortion metrics measure faithfulness to the observation, a crucial requirement in inverse problems. In this work, we propose a novel framework for inverse problem solving, namely we assume that the observation comes from a stochastic degradation process that gradually degrades and noises the original clean image. We learn to reverse the degradation process in order to recover the clean image. Our technique maintains consistency with the original measurement throughout the reverse process, and allows for great flexibility in trading off perceptual quality for improved distortion metrics and sampling speedup via early-stopping. We demonstrate the efficiency of our method on different high-resolution datasets and inverse problems, achieving great improvements over other state-of-the-art diffusion-based methods with respect to both perceptual and distortion metrics. Source code and pre-trained models will be released soon. 

<a href="https://arxiv.org/pdf/2303.14353.pdf" class="btn btn--inverse btn--large">
<i class="ai ai-arxiv ai-lg "></i> arXiv</a>

<b>Recommended citation</b>

Fabian, Z. Tinaz, B. and Soltanolkotabi, M., 2023, December. &quot;DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency&quot;.  <i> arXiv:2303.14353</i>
{: .notice}

<b>BibTeX<b>

```bibtex
@article{fabian2023diracdiffusion,
  title={DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency},
  author={Fabian, Zalan and Tinaz, Berk and Soltanolkotabi, Mahdi},
  journal={arXiv preprint arXiv:2303.14353},
  year={2023}
}
```
