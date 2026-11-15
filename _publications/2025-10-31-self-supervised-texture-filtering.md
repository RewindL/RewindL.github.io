---
title: "Self-supervised Texture Filtering"
collection: publications
category: manuscripts
permalink: /publication/self-supervised-texture-filtering/
date: 2025-10-31
venue: "ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia)"
paperurl: "https://dl.acm.org/doi/10.1145/3744899"
order: 6
teaser: "overview_self_supervised.png"
badge: "TOG · SIGGRAPH Asia 2025"
authors: '<strong>Jiang, H.</strong>, Zheng, R., Nie, Y., Xiao, C., Zheng, W., Zhang, Q.'
excerpt: >-
  Decomposing an image I into the combination of structure S and texture T components is an
  important problem in computational photography and image analysis. Traditional solutions
  are basically non-learning based, because it is difficult to construct datasets containing
  ground-truth decompositions or find effective structure/texture supervisions. In this
  article, we present a self-supervised framework for smoothing out textures while maintaining
  the image structures. At the core of our method is a texture-inversion observation — if
  structure S and texture T are well disentangled, then S-T will produce a texture-inverted
  image that is symmetric to the input image I=S+T and the two will be visually highly
  similar, while for other conditions that structure and texture are not effectively
  separated, the generated texture-inverted images will be less similar to the input. Based
  on the observation, we propose to learn texture filtering from unlabeled data by encouraging
  the texture inverted image generated from the filtering output to be visually more similar
  to the input via contrastive learning. Experiments show that our method can robustly produce
  high-quality texture smoothing results, and also enables various applications.
citation: 'Jiang, H., Zheng, R., Nie, Y., Xiao, C., Zheng, W., Zhang, Q. (2025). "Self-supervised Texture Filtering." <i>ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2025)</i>, 44(5), 1-13.'
---

[Paper](https://dl.acm.org/doi/10.1145/3744899)

## Abstract

Decomposing an image I into the combination of structure S and texture T components is an important problem in computational photography and image analysis. Traditional solutions are basically non-learning based, because it is difficult to construct datasets containing ground-truth decompositions or find effective structure/texture supervisions. In this article, we present a self-supervised framework for smoothing out textures while maintaining the image structures. At the core of our method is a texture-inversion observation — if structure S and texture T are well disentangled, then S-T will produce a texture-inverted image that is symmetric to the input image I=S+T and the two will be visually highly similar, while for other conditions that structure and texture are not effectively separated, the generated texture-inverted images will be less similar to the input. Based on the observation, we propose to learn texture filtering from unlabeled data by encouraging the texture inverted image generated from the filtering output to be visually more similar to the input via contrastive learning. Experiments show that our method can robustly produce high-quality texture smoothing results, and also enables various applications.