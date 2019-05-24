---
section: Contributed Papers
title: Exploring local rotation invariance in 3D CNNs with steerable filters
abstract: Locally Rotation Invariant (LRI) image analysis was shown to be fundamental
  in many applications and in particular in medical imaging where local structures
  of tissues occur at arbitrary rotations. LRI constituted the cornerstone of several
  breakthroughs in texture analysis, including Local Binary Patterns (LBP), Maximum
  Response 8 (MR8) and steerable filterbanks. Whereas globally rotation invariant
  Convolutional Neural Networks (CNN) were recently proposed, LRI was very little
  investigated in the context of deep learning. We use trainable 3D steerable filters
  in CNNs in order to obtain LRI with directional sensitivity, i.e. non-isotropic
  filters. Pooling across orientation channels after the first convolution layer releases
  the constraint on finite rotation groups as assumed in several recent works. Steerable
  filters are used to achieve a fine and efficient sampling of 3D rotations. We only
  convolve the input volume with a set of Spherical Harmonics (SHs) modulated by trainable
  radial supports and directly steer the responses, resulting in a drastic reduction
  of trainable parameters and of convolution operations, as well as avoiding approximations
  due to interpolation of rotated kernels. The proposed method is evaluated and compared
  to standard CNNs on 3D texture datasets including synthetic volumes with rotated
  patterns and pulmonary nodule classification in CT. The results show the importance
  of LRI in CNNs and the need for a fine rotation sampling.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: andrearczyk19a
month: 0
tex_title: Exploring local rotation invariance in 3D CNNs with steerable filters
firstpage: 15
lastpage: 26
page: 15-26
order: 15
cycles: false
bibtex_author: Andrearczyk, Vincent and Fageot, Julien and Oreiller, Valentin and
  Montet, Xavier and Depeursinge, Adrien
author:
- given: Vincent
  family: Andrearczyk
- given: Julien
  family: Fageot
- given: Valentin
  family: Oreiller
- given: Xavier
  family: Montet
- given: Adrien
  family: Depeursinge
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
pdf: http://proceedings.mlr.press/v102/andrearczyk19a/andrearczyk19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
