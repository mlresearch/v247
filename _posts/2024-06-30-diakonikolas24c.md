---
title: Efficiently Learning One-Hidden-Layer ReLU Networks via SchurPolynomials
section: Original Papers
abstract: We study the problem of PAC learning a linear combination of $k$ ReLU activations  under
  the standard Gaussian distribution on $\mathbb{R}^d$ with respect to the square
  loss.  Our main result is an efficient algorithm for this learning task with sample
  and  computational complexity $(dk/\epsilon)^{O(k)}$, where $\epsilon>0$ is the
  target accuracy.  Prior work had given an algorithm for this problem with complexity
  $(dk/\epsilon)^{h(k)}$,  where the function $h(k)$ scales super-polynomially in
  $k$. Interestingly,  the complexity of our algorithm is near-optimal within the
  class of  Correlational Statistical Query algorithms.  At a high-level, our algorithm
  uses tensor decomposition to identify a subspace such that all the $O(k)$-order
  moments are small in the orthogonal directions.  Its analysis makes essential use
  of the theory of Schur polynomials  to show that the higher-moment error tensors
  are small given that the lower-order ones are.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: diakonikolas24c
month: 0
tex_title: Efficiently Learning One-Hidden-Layer ReLU Networks via SchurPolynomials
firstpage: 1364
lastpage: 1378
page: 1364-1378
order: 1364
cycles: false
bibtex_author: Diakonikolas, Ilias and Kane, Daniel M.
author:
- given: Ilias
  family: Diakonikolas
- given: Daniel M.
  family: Kane
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
pdf: https://proceedings.mlr.press/v247/diakonikolas24c/diakonikolas24c.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
