---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


|2024| Learning interactions across sentiment and emotion with graph attention network and position encodings, A Jia, Y Zhang, **S Uprety**, D Song - Pattern Recognition Letters, 2024 [Link] (https://www.sciencedirect.com/science/article/pii/S0167865524000461)| 
|2023| CMMA: Benchmarking Multi-Affection Detection in Chinese Multi-Modal Conversations, Y Zhang, Y Yu, Q Guo, B Wang, D Zhao, **S Uprety**, Dawei Song, Qiuchi Li, Jing Qin - Advances in Neural Information Processing Systems, 2024 [Link](https://proceedings.neurips.cc/paper_files/paper/2023/file/3be60b4a739b95a07a944a1a2c41e05e-Paper-Datasets_and_Benchmarks.pdf)
|2023| MIP-GAT: A Multi-Task Interactive Graph Attention Network with Position Encodings for Joint Sentiment Classification and Emotion Recognition
A Jia, Y Zhang, **S Uprety**, D Song - Proceedings of the 45th Annual Conference of the Cognitive ScienceSociety, 2023 [Link](https://escholarship.org/uc/item/1wg7x26w)
|2022| Beyond emotion: A multi-modal dataset for human desire understanding
A Jia, Y He, Y Zhang, **S Uprety**, D Song, C Lioma - Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics (NAACL) [Link](https://aclanthology.org/2022.naacl-main.108.pdf)

|-|-|
