---
title: A diffusion-based method for removing background stars from astronomical 
  images
date: '2021-10-01'
draft: false
publishDate: '2026-04-23T13:44:46.623435Z'
authors:
- Maureen Cohen
- Weiping Lu
publication_types:
- '2'
external_link: "https://doi.org/10.1016/j.ascom.2021.100507"
abstract: 'Image processing techniques for background star removal from astronomical images have important applications such as streak detection and star/galaxy differentiation in galaxy morphology classification. Previous star removal methods relied on frame differencing and so required multiple images. In this work we present a new diffusion-based method that can remove stars and noise at the same time, using only a single image. The method measures a parameter called the local asymmetry around each pixel to identify stars and remove them with varying diffusion strength according to the measured parameter. To optimise the balance between signal preservation and star removal, it further incorporates a local stopping function that can adaptively turn the diffusion process on and off by monitoring the image residues. In order to test the method, we constructed a synthetic image that mimics astronomical images of interest and compared the processed images to the ground truth through the measurement of a range of metrics such as mean average error, root mean squared error, peak signal-to-noise ratio and structural similarity index. The results showed clear improvements in all the metrics compared to previous diffusion algorithms. Finally, we applied our method to a dataset of natural images and confirmed its effectiveness at preserving a wide variety of astronomical objects.'
featured: false
publication: '*Astronomy and Computing*'
---

