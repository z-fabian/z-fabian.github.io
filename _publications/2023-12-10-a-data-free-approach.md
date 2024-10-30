---
title: "A Data-Free Approach to Mitigate Catastrophic Forgetting in Federated Class Incremental Learning for Vision Tasks"
collection: publications
permalink: /publications/2023-12-10-a-data-free-approach
excerpt: 'Babakniya, S., Fabian, Z., He, C., Soltanolkotabi, M. and Avestimehr S., NeurIPS 2023'
date: 2023-12-10

---

Sara Babakniya, Zalan Fabian, Chaoyang He, Mahdi Soltanolkotabi, Salman Avestimehr  <br>
Published in *Advances in Neural Information Processing Systems*, 2023

Deep learning models often suffer from forgetting previously learned information when trained on new data. This problem is exacerbated in federated learning (FL), where the data is distributed and can change independently for each user. Many solutions are proposed to resolve this catastrophic forgetting in a centralized setting. However, they do not apply directly to FL because of its unique complexities, such as privacy concerns and resource limitations. To overcome these challenges, this paper presents a framework for **federated class incremental learning** that utilizes a generative model to synthesize samples from past distributions. This data can be later exploited alongside the training data to mitigate catastrophic forgetting. To preserve privacy, the generative model is trained on the server using data-free methods at the end of each task without requesting data from clients. Moreover, our solution does not demand the users to store old data or models, which gives them the freedom to join/leave the training at any time. Additionally, we introduce SuperImageNet, a new regrouping of the ImageNet dataset specifically tailored for federated continual learning. We demonstrate significant improvements compared to existing baselines through extensive experiments on multiple datasets. 

<a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/d160ea01902c33e30660851dfbac5980-Paper-Conference.pdf" class="btn btn--info btn--large">Paper</a>

<b>Recommended citation</b>

Babakniya, S., Fabian, Z., He, C., Soltanolkotabi, M. and Avestimehr S., 2023, A Data-Free Approach to Mitigate Catastrophic Forgetting in Federated Class Incremental Learning for Vision Tasks, In *Advances in Neural Information Processing Systems*
{: .notice}

<b>BibTeX<b>

```bibtex
@article{babakniya2024data,
  title={A data-free approach to mitigate catastrophic forgetting in federated class incremental learning for vision tasks},
  author={Babakniya, Sara and Fabian, Zalan and He, Chaoyang and Soltanolkotabi, Mahdi and Avestimehr, Salman},
  journal={Advances in Neural Information Processing Systems},
  volume={36},
  year={2024}
}
```
