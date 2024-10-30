---
title: "[Spotlight] Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models"
collection: publications
permalink: /publications/2024-07-20-adapt-and-diffuse
excerpt: 'Fabian, Z., Tinaz, B. and Soltanolkotabi, M., ICML 2024'
date: 2024-07-20

---

Zalan Fabian<sup>*</sup>, Berk Tinaz<sup>*</sup>, Mahdi Soltanolkotabi<br>
Published in <i>International Conference on Machine Learning, 2024</i><br>
<sup>*</sup>equal contribution

Inverse problems arise in a multitude of applications, where the goal is to recover a clean signal from noisy and possibly (non)linear observations. The difficulty of a reconstruction problem depends on multiple factors, such as the ground truth signal structure, the severity of the degradation and the complex interactions between the above. This results in natural sample-by-sample variation in the difficulty of a reconstruction problem. Our key observation is that most existing inverse problem solvers lack the ability to adapt their compute power to the difficulty of the reconstruction task, resulting in subpar performance and wasteful resource allocation. We propose a novel method, *severity encoding*, to estimate the degradation severity of corrupted signals in the latent space of an autoencoder. We show that the estimated severity has strong correlation with the true corruption level and can provide useful hints on the difficulty of reconstruction problems on a sample-by-sample basis. Furthermore, we propose a reconstruction method based on latent diffusion models that leverages the predicted degradation severities to fine-tune the reverse diffusion sampling trajectory and thus achieve sample-adaptive inference times. Our framework, Flash-Diffusion, acts as a wrapper that can be combined with any latent diffusion-based baseline solver, imbuing it with sample-adaptivity and acceleration. We perform experiments on both linear and nonlinear inverse problems and demonstrate that our technique greatly improves the performance of the baseline solver and achieves up to *10x* acceleration in mean sampling speed.

<a href="https://openreview.net/pdf?id=V3OpGwo68Z" class="btn btn--info btn--large">Paper</a>
<a href="/assets/posters/flash_icml2024_poster.pdf" class="btn btn--success btn--large">Poster</a>
<a href="/assets/slides/flash_icml2024_slides.pdf" class="btn btn--warning btn--large">Slides</a>
<a href="https://github.com/z-fabian/flash-diffusion" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Code</a>


<b>Recommended citation</b>

Fabian, Z. Tinaz, B. and Soltanolkotabi, M., 2024, July. &quot;Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models&quot;.  In *International Conference on Machine Learning*
{: .notice}

<b>BibTeX<b>

```bibtex
@inproceedings{fabian2024adapt,
  title={Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models},
  author={Fabian, Zalan and Tinaz, Berk and Soltanolkotabi, Mahdi},
  journal={International Conference on Machine Learning},
  year={2024}
}
```
