---
pdf: http://proceedings.mlr.press/v31/guzman-rivera13a.pdf
supplementary: Supplementary:guzman-rivera13a-supp.pdf
title: 'DivMCuts: Faster Training of Structural SVMs with Diverse M-Best Cutting-Planes'
abstract: Training of Structural SVMs involves solving a large Quadratic Program (QP).
  One popular method for solving this QP is a cutting-plane approach, where the most
  violated constraint is iteratively added to a working-set of constraints. Unfortunately,
  training models with a large number of parameters remains a time consuming process.
  This paper shows that significant computational savings can be achieved by adding
  multiple diverse and highly violated constraints at every iteration of the cutting-plane
  algorithm. We show that generation of such diverse cutting-planes involves extracting
  diverse M-Best solutions from the loss-augmented score of the training instances.
  To find these diverse M-Best solutions, we employ a recently proposed algorithm
  [4]. Our experiments on image segmentation and protein side-chain prediction show
  that the proposed approach can lead to significant computational savings, e.g.,
  ∼28% reduction in training time.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: guzman-rivera13a
month: 0
firstpage: 316
lastpage: 324
page: 316-324
sections: 
author:
- given: Abner
  family: Guzman-Rivera
- given: Pushmeet
  family: Kohli
- given: Dhruv
  family: Batra
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
