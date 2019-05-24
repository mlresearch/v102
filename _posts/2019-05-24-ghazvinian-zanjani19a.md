---
section: Contributed Papers
title: Deep Learning Approach to Semantic Segmentation in 3D Point Cloud Intra-oral
  Scans of Teeth
abstract: Accurate segmentation of data, derived from intra-oral scans (IOS), is a
  crucial step in a computer-aided design (CAD) system for many clinical tasks, such
  as implantology and orthodontics in modern dentistry. In order to reach the highest
  possible quality, a segmentation model may process a point cloud derived from an
  IOS in its highest available spatial resolution, especially for performing a valid
  analysis in finely detailed regions such as the curvatures in border lines between
  two teeth.  In this paper, we propose an end-to-end deep learning framework for
  semantic segmentation of individual teeth as well as the gingiva from point clouds
  representing IOS. By introducing a non-uniform resampling technique, our proposed
  model is trained and deployed on the highest available spatial resolution where
  it learns the local fine details along with the global coarse structure of IOS.  Furthermore,
  the point-wise cross-entropy loss for semantic segmentation of a point cloud is
  an ill-posed problem, since the relative geometrical structures between the instances
  (e.g. the teeth) are not formulated. By training a secondary simple network as a
  discriminator in an adversarial setting and penalizing unrealistic arrangements
  of assigned labels to the teeth on the dental arch, we improve the segmentation
  results considerably. Hence, a heavy post-processing stage for relational and dependency
  modeling (e.g. iterative energy minimization of a constructed graph) is not required
  anymore.  Our experiments show that the proposed approach improves the performance
  of our baseline network and outperforms the state-of-the-art networks by achieving
  $0.94$ IOU score.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: ghazvinian-zanjani19a
month: 0
tex_title: Deep Learning Approach to Semantic Segmentation in 3D Point Cloud Intra-oral
  Scans of Teeth
firstpage: 557
lastpage: 571
page: 557-571
order: 557
cycles: false
bibtex_author: "{Ghazvinian Zanjani}, Farhad and {Anssari Moin}, David and {Verheij},
  Bas and {Claessen}, Frank and {Cherici}, Teo and {Tan}, Tao and {de With}, {Peter
  H. N.}"
author:
- given: Farhad
  family: Ghazvinian Zanjani
- given: David
  family: Anssari Moin
- given: Bas
  family: Verheij
- given: Frank
  family: Claessen
- given: Teo
  family: Cherici
- given: Tao
  family: Tan
- given: Peter H. N.
  family: de With
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
pdf: http://proceedings.mlr.press/v102/ghazvinian-zanjani19a/ghazvinian-zanjani19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
