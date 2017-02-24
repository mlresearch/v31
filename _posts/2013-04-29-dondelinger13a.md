---
pdf: http://proceedings.mlr.press/v31/dondelinger13a.pdf
title: ODE parameter inference using adaptive gradient matching with Gaussian processes
abstract: Parameter inference in mechanistic models based on systems of coupled differential
  equations is a topical yet computationally challenging problem, due to the need
  to follow each parameter adaptation with a numerical integration of the differential
  equations. Techniques based on gradient matching, which aim to minimize the discrepancy
  between the slope of a data interpolant and the derivatives predicted from the differential
  equations, offer a computationally appealing shortcut to the inference  problem.
  The present paper discusses a method based on nonparametric Bayesian statistics
  with Gaussian processes due to Calderhead et al. (2008), and shows how inference
  in this model can be substantially improved by consistently sampling from the joint
  distribution of the ODE parameters and GP hyperparameters. We demonstrate the efficiency
  of our adaptive gradient matching technique on three benchmark systems, and perform
  a detailed comparison with the method in Calderhead et al. (2008) and the explicit
  ODE integration approach, both in terms of parameter inference accuracy and in terms
  of computational efficiency.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: dondelinger13a
month: 0
firstpage: 216
lastpage: 228
page: 216-228
sections: 
author:
- given: Frank
  family: Dondelinger
- given: Dirk
  family: Husmeier
- given: Simon
  family: Rogers
- given: Maurizio
  family: Filippone
date: 2013-04-29
address: Scottsdale, Arizona, USA
publisher: PMLR
container-title: Proceedings of the Sixteenth International Conference on Artificial
  Intelligence and Statistics
volume: '31'
genre: inproceedings
issued:
  date-parts:
  - 2013
  - 4
  - 29
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
