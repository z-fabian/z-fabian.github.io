---
title: "[Spotlight] Data augmentation for deep learning based accelerated MRI reconstruction with limited data"
collection: publications
permalink: /publications/2021-07-01-data-augmentation-for-deep-learning
excerpt: 'Fabian, Z., Heckel, R. and Soltanolkotabi, M., ICML 2021'
date: 2021-07-01
---
Zalan Fabian, Reinhard Heckel, Mahdi Soltanolkotabi <br>
Published in <i> International Conference on Machine Learning </i>, 2021

Deep neural networks have emerged as very successful tools for image restoration and reconstruction tasks. These networks are often trained end-to-end to directly reconstruct an image from a noisy or corrupted measurement of that image. To achieve state-of-the-art performance, training on large and diverse sets of images is considered critical. However, it is often difficult and/or expensive to collect large amounts of training images. Inspired by the success of Data Augmentation (DA) for classification problems, in this paper, we propose a pipeline for data augmentation for accelerated MRI reconstruction and study its effectiveness at reducing the required training data in a variety of settings. Our DA pipeline, MRAugment, is specifically designed to utilize the invariances present in medical imaging measurements as naive DA strategies that neglect the physics of the problem fail. Through extensive studies on multiple datasets we demonstrate that in the low-data regime DA prevents overfitting and can match or even surpass the state of the art while using significantly fewer training data, whereas in the high-data regime it has diminishing returns. Furthermore, our findings show that DA improves the robustness of the model against various shifts in the test distribution.

<a href="http://proceedings.mlr.press/v139/fabian21a/fabian21a.pdf" class="btn btn--info btn--large">Paper</a>
<a href="/assets/posters/icml2021_poster.png" class="btn btn--success btn--large">Poster</a>
<a href="/assets/slides/icml2021_slides.pdf" class="btn btn--warning btn--large">Slides</a>
<a href="https://github.com/z-fabian/MRAugment" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Code</a>

<b>Recommended citation</b>

Fabian, Z., Heckel, R. and Soltanolkotabi, M., 2021, July. &quot;Data augmentation for deep learning based accelerated MRI reconstruction with limited data&quot;. In <i>International Conference on Machine Learning</i> (pp. 3057-3067). PMLR.
{: .notice}

<b>BibTeX<b>
```bibtex
@inproceedings{fabian2021data,
  title={Data augmentation for deep learning based accelerated MRI reconstruction with limited data},
  author={Fabian, Zalan and Heckel, Reinhard and Soltanolkotabi, Mahdi},
  booktitle={International Conference on Machine Learning},
  pages={3057--3067},
  year={2021},
  organization={PMLR}
}
```
