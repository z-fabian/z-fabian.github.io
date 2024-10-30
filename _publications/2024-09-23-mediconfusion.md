---
title: "MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models"
collection: publications
permalink: /publications/2024-09-23-mediconfusion
excerpt: 'Sepehri, M. S., Fabian, Z., Soltanolkotabi, M., Soltanolkotabi, M., 2024, <i>arXiv:2409.15477</i>'
date: 2024-09-23

---

Mohammad Shahab Sepehri, Zalan Fabian, Maryam Soltanolkotabi, Mahdi Soltanolkotabi<br>
<i>arXiv:2409.15477</i>, 2024

Multimodal Large Language Models (MLLMs) have tremendous potential to improve the accuracy, availability, and cost-effectiveness of healthcare by providing automated solutions or serving as aids to medical professionals. Despite promising first steps in developing medical MLLMs in the past few years, their capabilities and limitations are not well-understood. Recently, many benchmark datasets have been proposed that test the general medical knowledge of such models across a variety of medical areas. However, the systematic failure modes and vulnerabilities of such models are severely underexplored with most medical benchmarks failing to expose the shortcomings of existing models in this safety-critical domain. In this paper, we introduce MediConfusion, a challenging medical Visual Question Answering (VQA) benchmark dataset, that probes the failure modes of medical MLLMs from a vision perspective. We reveal that state-of-the-art models are easily confused by image pairs that are otherwise visually dissimilar and clearly distinct for medical experts. Strikingly, all available models (open-source or proprietary) achieve performance below random guessing on MediConfusion, raising serious concerns about the reliability of existing medical MLLMs for healthcare deployment. We also extract common patterns of model failure that may help the design of a new generation of more trustworthy and reliable MLLMs in healthcare. 

<a href="https://arxiv.org/pdf/2409.15477" class="btn btn--inverse btn--large">
<i class="ai ai-arxiv ai-lg "></i> arXiv</a>
<a href="https://github.com/MShahabSepehri/MediConfusion" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Code</a>
<a href="https://sites.usc.edu/aif4s/2024/09/25/mediconfusion/" class="btn btn--warning btn--large">Blog</a>


<b>Recommended citation</b>

Sepehri, M. S., Fabian, Z., Soltanolkotabi, M., Soltanolkotabi, M., 2024, MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models, <i> arXiv:2409.15477</i>
{: .notice}

<b>BibTeX<b>

```bibtex
@article{sepehri2024mediconfusion,
  title={MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models},
  author={Sepehri, Mohammad Shahab and Fabian, Zalan and Soltanolkotabi, Maryam and Soltanolkotabi, Mahdi},
  journal={arXiv preprint arXiv:2409.15477},
  year={2024}
}
```
