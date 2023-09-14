---
title: "Don't Memorize; Mimic The Past: Federated Class Incremental Learning Without Episodic Memory"
collection: publications
permalink: /publications/2023-07-02-dont-memorize-mimic-the-past
excerpt: 'Babakniya, S., Fabian Z., He, C., Soltanolkotabi, M. and Avestimehr S., 2023, <i> arXiv:2307.00497</i>'
date: 2023-07-02

---

Sara Babakniya, Zalan Fabian, Chaoyang He, Mahdi Soltanolkotabi, Salman Avestimehr  <br>
<i>arXiv:2307.00497</i>, 2023

Deep learning models are prone to forgetting information learned in the past when trained on new data. This problem becomes even more pronounced in the context of federated learning (FL), where data is decentralized and subject to independent changes for each user. Continual Learning (CL) studies this so-called \textit{catastrophic forgetting} phenomenon primarily in centralized settings, where the learner has direct access to the complete training dataset. However, applying CL techniques to FL is not straightforward due to privacy concerns and resource limitations. This paper presents a framework for federated class incremental learning that utilizes a generative model to synthesize samples from past distributions instead of storing part of past data. Then, clients can leverage the generative model to mitigate catastrophic forgetting locally. The generative model is trained on the server using data-free methods at the end of each task without requesting data from clients. Therefore, it reduces the risk of data leakage as opposed to training it on the client's private data. We demonstrate significant improvements for the CIFAR-100 dataset compared to existing baselines. 

<a href="https://arxiv.org/pdf/2307.00497.pdf" class="btn btn--inverse btn--large">
<i class="ai ai-arxiv ai-lg "></i> arXiv</a>

<b>Recommended citation</b>

Babakniya, S., Fabian Z., He, C., Soltanolkotabi, M. and Avestimehr S., 2023, Don't Memorize; Mimic The Past: Federated Class Incremental Learning Without Episodic Memory, <i> arXiv:2307.00497</i>
{: .notice}

<b>BibTeX<b>

```bibtex
@article{babakniya2023don,
  title={Don't Memorize; Mimic The Past: Federated Class Incremental Learning Without Episodic Memory},
  author={Babakniya, Sara and Fabian, Zalan and He, Chaoyang and Soltanolkotabi, Mahdi and Avestimehr, Salman},
  journal={arXiv preprint arXiv:2307.00497},
  year={2023}
}
```
