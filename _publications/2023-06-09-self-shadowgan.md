---
title: "Learning to Remove Shadows from a Single Image"
collection: publications
category: manuscripts
permalink: /publication/self-shadowgan/
date: 2023-06-09
venue: "International Journal of Computer Vision (IJCV)"
paperurl: "https://link.springer.com/article/10.1007/s11263-023-01823-9"
codeurl: "https://github.com/RewindL/Self-ShadowGAN"
order: 7
teaser: "overview_self_shadowgan_3.png"
badge: "IJCV 2023"
authors: '<strong>Jiang, H.</strong>, Zhang, Q., Nie, Y., Zhu, L., Zheng, W.'
excerpt: >-
  Recent learning-based shadow removal methods have achieved remarkable performance. However,
  they basically require massive paired shadow and shadow-free images for model training,
  which limits their generalization capability since these data are often cumbersome to
  obtain and lack of diversity. To address the problem, we present Self-ShadowGAN, a novel
  adversarial framework that is able to learn to remove shadows in an image by training solely
  on the image itself, using the shadow mask as the only supervision. Our approach is built
  upon the concept of histogram matching, by constraining the deshadowed regions produced by a
  shadow relighting network share similar histograms to the original shadow-free regions via a
  histogram-based discriminator. In order to speed up the single image training, we define the
  shadow relighting network to be lightweight multi-layer perceptions (MLPs) that estimate
  spatially-varying shadow relighting coefficients, where the parameters of the MLPs are
  predicted from a low-resolution input by a fast convolutional network and then upsampled
  back to the original full-resolution. Experimental results show that our method performs
  favorably against the state-of-the-art shadow removal methods, and is effective to process
  previously challenging shadow images.
citation: 'Jiang, H., Zhang, Q., Nie, Y., Zhu, L., Zheng, W. (2023). "Learning to Remove Shadows from a Single Image." <i>International Journal of Computer Vision</i>, 131(9), 2471-2488.'
---

[Paper](https://link.springer.com/article/10.1007/s11263-023-01823-9) · [Code](https://github.com/RewindL/Self-ShadowGAN)

## Abstract

Recent learning-based shadow removal methods have achieved remarkable performance. However, they basically require massive paired shadow and shadow-free images for model training, which limits their generalization capability since these data are often cumbersome to obtain and lack of diversity. To address the problem, we present Self-ShadowGAN, a novel adversarial framework that is able to learn to remove shadows in an image by training solely on the image itself, using the shadow mask as the only supervision. Our approach is built upon the concept of histogram matching, by constraining the deshadowed regions produced by a shadow relighting network share similar histograms to the original shadow-free regions via a histogram-based discriminator. In order to speed up the single image training, we define the shadow relighting network to be lightweight multi-layer perceptions (MLPs) that estimate spatially-varying shadow relighting coefficients, where the parameters of the MLPs are predicted from a low-resolution input by a fast convolutional network and then upsampled back to the original full-resolution. Experimental results show that our method performs favorably against the state-of-the-art shadow removal methods, and is effective to process previously challenging shadow images.