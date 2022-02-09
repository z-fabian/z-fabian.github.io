---
title: "Generalization guarantees for neural networks via harnessing the low-rank structure of the Jacobian"
collection: publications
permalink: /publications/2019-07-04-generalization-guarantees-for-neural-networks
excerpt: 'Oymak, S., Fabian, Z., Li, M. and Soltanolkotabi, M., 2019. <i> arXiv:1906.05392v2 </i>'
date: 2019-07-04
---
Samet Oymak, Zalan Fabian, Mingchen Li, Mahdi Soltanolkotabi <br>
<i>arXiv:1906.05392v2 </i>

Modern neural network architectures often generalize well despite containing many more parameters than the size of the training dataset. This paper explores the generalization capabilities of neural networks trained via gradient descent. We develop a data-dependent optimization and generalization theory which leverages the low-rank structure of the Jacobian matrix associated with the network. Our results help demystify why training and generalization is easier on clean and structured datasets and harder on noisy and unstructured datasets as well as how the network size affects the evolution of the train and test errors during training. Specifically, we use a control knob to split the Jacobian spectum into "information" and "nuisance" spaces associated with the large and small singular values. We show that over the information space learning is fast and one can quickly train a model with zero training loss that can also generalize well. Over the nuisance space training is slower and early stopping can help with generalization at the expense of some bias. We also show that the overall generalization capability of the network is controlled by how well the label vector is aligned with the information space. A key feature of our results is that even constant width neural nets can provably generalize for sufficiently nice datasets. We conduct various numerical experiments on deep networks that corroborate our theoretical findings and demonstrate that: (i) the Jacobian of typical neural networks exhibit low-rank structure with a few large singular values and many small ones leading to a low-dimensional information space, (ii) over the information space learning is fast and most of the label vector falls on this space, and (iii) label noise falls on the nuisance space and impedes optimization/generalization.

<a href="https://arxiv.org/pdf/1906.05392.pdf" class="btn btn--inverse btn--large"><i class="ai ai-arxiv ai-lg "></i> arXiv</a>

<b>Recommended citation</b>
Oymak, S., Fabian, Z., Li, M. and Soltanolkotabi, M., 2019. &quot;Generalization guarantees for neural networks via harnessing the low-rank structure of the Jacobian&quot;. <i>arXiv preprint arXiv:1906.05392v2</i>.
{: .notice}

<b>BibTeX<b>
```bibtex
@article{oymak2019generalization,
  title={Generalization guarantees for neural networks via harnessing the low-rank structure of the jacobian},
  author={Oymak, Samet and Fabian, Zalan and Li, Mingchen and Soltanolkotabi, Mahdi},
  journal={arXiv preprint arXiv:1906.05392},
  year={2019}
}
```
