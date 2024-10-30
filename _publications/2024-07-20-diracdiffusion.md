---
title: "DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency"
collection: publications
permalink: /publications/2024-07-20-diracdiffusion
excerpt: 'Fabian, Z., Tinaz, B. and Soltanolkotabi, M., ICML 2024'
date: 2024-07-20

---

Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi <br>
Published in <i>International Conference on Machine Learning, 2024</i>

Diffusion models have established a new state of the art in a multitude of computer vision tasks, including image restoration. Diffusion-based inverse problem solvers generate reconstructions of exceptional visual quality from heavily corrupted measurements. However, in what is widely known as the perception-distortion trade-off, the price of perceptually appealing reconstructions is often paid in declined distortion metrics, such as PSNR. Distortion metrics measure faithfulness to the observation, a crucial requirement in inverse problems. In this work, we propose a novel framework for inverse problem solving, assuming that the observation comes from a stochastic degradation process that gradually degrades and adds noise to the original clean image. We learn to reverse the degradation process to recover the clean image. Our technique maintains consistency with the original measurement throughout the reverse process and allows for great flexibility in trading off perceptual quality for improved distortion metrics and sampling speedup via early stopping. We demonstrate the efficiency of our method on different high-resolution datasets and inverse problems, achieving significant improvements over other state-of-the-art diffusion-based methods with respect to both perceptual and distortion metrics.

<a href="https://openreview.net/pdf/2e0d4e76462e0bf7282e6918745a486eb43eae21.pdf" class="btn btn--info btn--large">Paper</a>
<a href="/assets/posters/dirac_icml2024_poster.pdf" class="btn btn--success btn--large">Poster</a>
<a href="https://github.com/z-fabian/dirac-diffusion" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Code</a>

<b>Recommended citation</b>

Fabian, Z. Tinaz, B. and Soltanolkotabi, M., 2024, July. &quot;DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency&quot;.  In *International Conference on Machine Learning*
{: .notice}

<b>BibTeX<b>

```bibtex
@article{fabian2024diracdiffusion,
  title={DiracDiffusion: Denoising and Incremental Reconstruction with Assured Data-Consistency},
  author={Fabian, Zalan and Tinaz, Berk and Soltanolkotabi, Mahdi},
  journal={International Conference on Machine Learning},
  year={2024}
}
```
