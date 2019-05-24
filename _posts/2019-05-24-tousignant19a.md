---
section: Contributed Papers
title: Prediction of Disease Progression in Multiple Sclerosis Patients using Deep
  Learning Analysis of MRI Data
abstract: We present the first automatic end-to-end deep learning framework for the
  prediction of future patient disability progression (one year from baseline) based
  on multi-modal brain Magnetic Resonance Images (MRI) of patients with Multiple Sclerosis
  (MS). The model uses parallel convolutional pathways, an idea introduced by the
  popular Inception net {{Szegedy et al.}} ({2015}) and is trained and tested on two
  large proprietary, multi-scanner, multi-center, clinical trial datasets of patients
  with Relapsing-Remitting Multiple Sclerosis (RRMS). Experiments on 465 patients
  on the placebo arms of the trials indicate that the model can accurately predict
  future disease progression, measured by a sustained increase in the extended disability
  status scale (EDSS) score over time.  Using only the multi-modal MRI provided at
  baseline, the model achieves an AUC of 0.66 ± 0.055. However, when supplemental
  lesion label masks are provided as inputs as well, the AUC increases to 0.701 ±
  0.027. Furthermore, we demonstrate that uncertainty estimates based on Monte Carlo
  dropout sample variance correlate with errors made by the model. Clinicians provided
  with the predictions computed by the model can therefore use the associated uncertainty
  estimates to assess which scans require further examination.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: tousignant19a
month: 0
tex_title: Prediction of Disease Progression in Multiple Sclerosis Patients using
  Deep Learning Analysis of MRI Data
firstpage: 483
lastpage: 492
page: 483-492
order: 483
cycles: false
bibtex_author: Tousignant, Adrian and Lema\^itre, Paul and Precup, Doina and Arnold,
  Douglas L. and Arbel, Tal
author:
- given: Adrian
  family: Tousignant
- given: Paul
  family: Lemaître
- given: Doina
  family: Precup
- given: Douglas L.
  family: Arnold
- given: Tal
  family: Arbel
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
pdf: http://proceedings.mlr.press/v102/tousignant19a/tousignant19a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
