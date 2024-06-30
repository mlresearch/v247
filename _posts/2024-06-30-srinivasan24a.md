---
title: Fast sampling from constrained spaces using the Metropolis-adjusted Mirror
  Langevin algorithm
section: Original Papers
abstract: We propose a new method called the Metropolis-adjusted Mirror Langevin algorithm
  for approximate sampling from distributions whose support is a compact and convex
  set. This algorithm adds an accept-reject filter to the Markov chain induced by
  a single step of the Mirror Langevin algorithm (Zhang et al, 2020), which is a basic
  discretisation of the Mirror Langevin dynamics. Due to the inclusion of this filter,
  our method is unbiased relative to the target, while known discretisations of the
  Mirror Langevin dynamics including the Mirror Langevin algorithm have an asymptotic
  bias. For this algorithm, we also give upper bounds for the number of iterations
  taken to mix to a constrained distribution whose potential is relatively smooth,
  convex, and Lipschitz continuous with respect to a self-concordant mirror function.
  As a consequence of the reversibility of the Markov chain induced by the inclusion
  of the Metropolis-Hastings filter, we obtain an exponentially better dependence
  on the error tolerance for approximate constrained sampling.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: srinivasan24a
month: 0
tex_title: Fast sampling from constrained spaces using the Metropolis-adjusted Mirror
  Langevin algorithm
firstpage: 4593
lastpage: 4635
page: 4593-4635
order: 4593
cycles: false
bibtex_author: Srinivasan, Vishwak and Wibisono, Andre and Wilson, Ashia
author:
- given: Vishwak
  family: Srinivasan
- given: Andre
  family: Wibisono
- given: Ashia
  family: Wilson
date: 2024-06-30
address:
container-title: Proceedings of Thirty Seventh Conference on Learning Theory
volume: '247'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 6
  - 30
pdf: https://proceedings.mlr.press/v247/srinivasan24a/srinivasan24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
