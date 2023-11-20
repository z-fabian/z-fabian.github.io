---
title: "Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models"
collection: publications
permalink: /publications/2023-09-12-adapt-and-diffuse
excerpt: 'Fabian, Z., Tinaz, B., Soltanolkotabi, M., 2023, <i>arXiv:2309.06642</i>'
date: 2023-09-12

---

Zalan Fabian, Berk Tinaz, Mahdi Soltanolkotabi<br>
<i>arXiv:2309.06642</i>, 2023

Inverse problems arise in a multitude of applications, where the goal is to recover a clean signal from noisy and possibly (non)linear observations. The difficulty of a reconstruction problem depends on multiple factors, such as the structure of the ground truth signal, the severity of the degradation, the implicit bias of the reconstruction model and the complex interactions between the above factors. This results in natural sample-by-sample variation in the difficulty of a reconstruction task, which is often overlooked by contemporary techniques. Recently, diffusion-based inverse problem solvers have established new state-of-the-art in various reconstruction tasks. However, they have the drawback of being computationally prohibitive. Our key observation in this paper is that most existing solvers lack the ability to adapt their compute power to the difficulty of the reconstruction task, resulting in long inference times, subpar performance and wasteful resource allocation. We propose a novel method that we call severity encoding, to estimate the degradation severity of noisy, degraded signals in the latent space of an autoencoder. We show that the estimated severity has strong correlation with the true corruption level and can give useful hints at the difficulty of reconstruction problems on a sample-by-sample basis. Furthermore, we propose a reconstruction method based on latent diffusion models that leverages the predicted degradation severities to fine-tune the reverse diffusion sampling trajectory and thus achieve sample-adaptive inference times. We utilize latent diffusion posterior sampling to maintain data consistency with observations. We perform experiments on both linear and nonlinear inverse problems and demonstrate that our technique achieves performance comparable to state-of-the-art diffusion-based techniques, with significant improvements in computational efficiency. 

<a href="https://arxiv.org/pdf/2309.06642.pdf" class="btn btn--inverse btn--large">
<i class="ai ai-arxiv ai-lg "></i> arXiv</a>

<b>Recommended citation</b>

Fabian, Z., Tinaz, B., Soltanolkotabi, M., 2023, Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models, <i> arXiv:2309.06642</i>
{: .notice}

<b>BibTeX<b>

```bibtex
@article{fabian2023adapt,
  title={Adapt and Diffuse: Sample-adaptive Reconstruction via Latent Diffusion Models},
  author={Fabian, Zalan and Tinaz, Berk and Soltanolkotabi, Mahdi},
  journal={arXiv preprint arXiv:2309.06642},
  year={2023}
}
```
