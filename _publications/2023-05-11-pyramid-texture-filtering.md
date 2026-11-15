---
title: "Pyramid Texture Filtering"
collection: publications
category: conferences
permalink: /publication/pyramid-texture-filtering/
date: 2023-05-11
venue: "ACM Transactions on Graphics (Proceedings of SIGGRAPH)"
paperurl: "https://dl.acm.org/doi/10.1145/3592120"
codeurl: "https://github.com/RewindL/pyramid_texture_filtering"
projecturl: "https://rewindl.github.io/pyramid_texture_filtering/"
order: 8
teaser: "overview_ptf.png"
badge: "TOG · SIGGRAPH 2023"
authors: 'Zhang, Q., <strong>Jiang, H.<sup>♣</sup></strong>, Nie, Y., Zheng, W.'
authornote: '<sup>♣</sup> First Student Author'
excerpt: >-
  We present a simple but effective technique to smooth out textures while preserving the
  prominent structures. Our method is built upon a key observation — the coarsest level in a
  Gaussian pyramid often naturally eliminates textures and summarizes the main image
  structures. This inspires our central idea for texture filtering, which is to progressively
  upsample the very low-resolution coarsest Gaussian pyramid level to a full-resolution
  texture smoothing result with well-preserved structures, under the guidance of each
  fine-scale Gaussian pyramid level and its associated Laplacian pyramid level. We show that
  our approach is effective to separate structure from texture of different scales, local
  contrasts, and forms, without degrading structures or introducing visual artifacts. We also
  demonstrate the applicability of our method on various applications including detail
  enhancement, image abstraction, HDR tone mapping, inverse halftoning, and LDR image
  enhancement.
citation: 'Zhang, Q., Jiang, H., Nie, Y., Zheng, W. (2023). "Pyramid Texture Filtering." <i>ACM Transactions on Graphics (Proceedings of SIGGRAPH 2023)</i>, 42(4), 1-11.'
---

[Paper](https://dl.acm.org/doi/10.1145/3592120) · [Code](https://github.com/RewindL/pyramid_texture_filtering) · [Project](https://rewindl.github.io/pyramid_texture_filtering/)

## Abstract

We present a simple but effective technique to smooth out textures while preserving the prominent structures. Our method is built upon a key observation — the coarsest level in a Gaussian pyramid often naturally eliminates textures and summarizes the main image structures. This inspires our central idea for texture filtering, which is to progressively upsample the very low-resolution coarsest Gaussian pyramid level to a full-resolution texture smoothing result with well-preserved structures, under the guidance of each fine-scale Gaussian pyramid level and its associated Laplacian pyramid level. We show that our approach is effective to separate structure from texture of different scales, local contrasts, and forms, without degrading structures or introducing visual artifacts. We also demonstrate the applicability of our method on various applications including detail enhancement, image abstraction, HDR tone mapping, inverse halftoning, and LDR image enhancement.