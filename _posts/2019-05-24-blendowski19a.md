---
section: Contributed Papers
title: Learning interpretable multi-modal features for alignment with supervised iterative
  descent
abstract: Methods for deep learning based medical image registration have only recently
  approached the quality of classical model-based image alignment. The dual challenge
  of both a very large trainable parameter space and often insufficient availability
  of expert supervised correspondence annotations has led to slower progress compared
  to other domains such as image segmentation. Yet, image registration could also
  more directly benefit from an iterative solution than segmentation. We therefore
  believe that significant improvements, in particular for multi-modal registration,
  can be achieved by disentangling appearance-based feature learning and deformation
  estimation. In contrast to most previous approaches, our model does not require
  full deformation fields as supervision but rather only small incremental descent
  targets generated from organ labels during training. By mapping the complex appearance
  to a common feature space in which update steps of a first-order Taylor approximation
  (akin to a regularised Demons iteration) match the supervised descent direction,
  we can train a CNN-model that learns interpretable modality invariant features.
  Our experimental results demonstrate that these features can be plugged into conventional
  iterative optimisers and are more robust than state-of-the-art hand-crafted features
  for aligning MRI and CT images.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: blendowski19a
month: 0
tex_title: Learning interpretable multi-modal features for alignment with supervised
  iterative descent
firstpage: 73
lastpage: 83
page: 73-83
order: 73
cycles: false
bibtex_author: Blendowski, Max and Heinrich, Mattias P.
author:
- given: Max
  family: Blendowski
- given: Mattias P.
  family: Heinrich
date: 2019-05-24
address: 
publisher: PMLR
container-title: Proceedings of The 2nd International Conference on Medical Imaging
  with Deep Learning
volume: '102'
genre: inproceedings
issued:
  date-parts:
  - 2019
  - 5
  - 24
pdf: http://proceedings.mlr.press/v102/blendowski19a/blendowski19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
