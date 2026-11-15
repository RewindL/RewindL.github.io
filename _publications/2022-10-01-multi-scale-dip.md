---
title: "Learning Multi-Scale Deep Image Prior for High-Quality Unsupervised Image Denoising"
collection: publications
category: manuscripts
permalink: /publication/multi-scale-dip/
date: 2022-10-01
venue: "Computer Graphics Forum (CGF)"
paperurl: "https://doi.org/10.1111/cgf.14680"
order: 9
teaser: "overview_double_dip.png"
badge: "CGF 2022"
authors: '<strong>Jiang, H.</strong>, Zhang, Q., Nie, Y., Zhu, L., Zheng, W.'
excerpt: >-
  Recent methods on image denoising have achieved remarkable progress, benefiting mostly from
  supervised learning on massive noisy/clean image pairs and unsupervised learning on external
  noisy images. However, due to the domain gap between the training and testing images, these
  methods typically have limited applicability on unseen images. Although several attempts
  have been made to avoid the domain gap issue by learning denoising from single noisy image
  itself, they are less effective in handling real-world noise because of assuming the noise
  corruptions are independent and zero mean. In this paper, we go step further beyond prior
  work by presenting a novel unsupervised image denoising framework trained from single noisy
  image without making any explicit assumptions on the noise statistics. Our approach is built
  upon the deep image prior (DIP), which enables diverse image restoration tasks. However, as
  is, the denoising performance of DIP will significantly deteriorate on nonzero-mean noise and
  is sensitive to the number of iterations. To overcome this problem, we propose to utilize
  multi-scale deep image prior by imposing DIP across different image scales under the
  constraint of a scale consistency. Experiments on synthetic and real datasets demonstrate
  that our method performs favorably against the state-of-the-art methods for image denoising.
citation: 'Jiang, H., Zhang, Q., Nie, Y., Zhu, L., Zheng, W. (2022). "Learning Multi-Scale Deep Image Prior for High-Quality Unsupervised Image Denoising." <i>Computer Graphics Forum</i>, 41(7), 323-334.'
---

[Paper](https://doi.org/10.1111/cgf.14680)

## Abstract

Recent methods on image denoising have achieved remarkable progress, benefiting mostly from supervised learning on massive noisy/clean image pairs and unsupervised learning on external noisy images. However, due to the domain gap between the training and testing images, these methods typically have limited applicability on unseen images. Although several attempts have been made to avoid the domain gap issue by learning denoising from single noisy image itself, they are less effective in handling real-world noise because of assuming the noise corruptions are independent and zero mean. In this paper, we go step further beyond prior work by presenting a novel unsupervised image denoising framework trained from single noisy image without making any explicit assumptions on the noise statistics. Our approach is built upon the deep image prior (DIP), which enables diverse image restoration tasks. However, as is, the denoising performance of DIP will significantly deteriorate on nonzero-mean noise and is sensitive to the number of iterations. To overcome this problem, we propose to utilize multi-scale deep image prior by imposing DIP across different image scales under the constraint of a scale consistency. Experiments on synthetic and real datasets demonstrate that our method performs favorably against the state-of-the-art methods for image denoising.