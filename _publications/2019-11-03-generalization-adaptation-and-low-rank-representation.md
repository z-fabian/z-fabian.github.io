---
title: "Generalization, adaptation and low-rank representation in neural networks"
collection: publications
permalink: /publications/2019-11-03-generalization-adaptation-and-low-rank-representation
excerpt: 'Oymak, S., Fabian, Z., Li, M. and Soltanolkotabi, M., 2019. <i>Asilomar Conference on Signals, Systems, and Computers</i>'
date: 2019-11-03
---
Samet Oymak, Zalan Fabian, Mingchen Li, Mahdi Soltanolkotabi <br>
Published in <i>Asilomar Conference on Signals, Systems, and Computers</i>, 2019

We develop a data-dependent optimization and generalization theory for neural networks which leverages the lowrankness of the Jacobian matrix associated with the network. Our results help demystify why training and generalization is easier on clean and structured datasets and harder on noisy and unstructured datasets. Specifically, we show that over the principal eigendirections of the Jacobian matrix space learning is fast and one can quickly train a model with zero training loss that can also generalize well. Over the smaller eigendirections, training is slower and early stopping can help with generalization at the expense of some bias. We also discuss how neural networks can learn better representations over time in terms of the Jacobian mapping. We conduct various numerical experiments on deep networks that corroborate our theoretical findings and demonstrate that: (i) the Jacobian of typical neural networks exhibits low-rank structure with a few large singular values and many small ones, (ii) most of the useful label information lies on the principal eigendirections where learning is fast, and (iii) Jacobian adapts over time and learns better representations.

<a href="https://ieeexplore.ieee.org/abstract/document/9048845" class="btn btn--info btn--large">Paper</a>

<b>Recommended citation</b>
Oymak, S., Fabian, Z., Li, M. and Soltanolkotabi, M., 2019. &quot;Generalization, adaptation and low-rank representation in neural networks&quot;. In <i>2019 53rd Asilomar Conference on Signals, Systems, and Computers</i> (pp. 581-585). IEEE.
{: .notice}

<b>BibTeX<b>
```bibtex
@inproceedings{oymak2019generalization,
  title={Generalization, adaptation and low-rank representation in neural networks},
  author={Oymak, Samet and Fabian, Zalan and Li, Mingchen and Soltanolkotabi, Mahdi},
  booktitle={2019 53rd Asilomar Conference on Signals, Systems, and Computers},
  pages={581--585},
  year={2019},
  organization={IEEE}
}
```
