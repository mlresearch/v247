---
title: Closing the Computational-Query Depth Gap in Parallel Stochastic Convex Optimization
section: Original Papers
abstract: We develop a new parallel algorithm for minimizing Lipschitz, convex functions
  with a stochastic subgradient oracle. The total number of queries made and the query
  depth, i.e., the number of parallel rounds of queries, match the prior state-of-the-art,
  [CJJLLST23], while improving upon the computational depth by a polynomial factor
  for sufficiently small accuracy. When combined with previous state-of-the-art methods
  our result closes a gap between the best-known query depth and the best-known computational
  depth of parallel algorithms.  Our method starts with a \emph{ball acceleration}
  framework of previous parallel methods, i.e., [CJJJLST20, ACJJS21], which reduce
  the problem to minimizing a regularized Gaussian convolution of the function constrained
  to Euclidean balls. By developing and leveraging new stability properties of the
  Hessian of this induced function, we depart from prior parallel algorithms and reduce
  these ball-constrained optimization problems to stochastic unconstrained quadratic
  minimization problems. Although we are unable to prove concentration of the asymmetric
  matrices that we use to approximate this Hessian, we nevertheless develop an efficient
  parallel method for solving these quadratics. Interestingly, our algorithms can
  be improved using fast matrix multiplication and run in nearly-linear time if the
  matrix multiplication exponent is 2.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jambulapati24b
month: 0
tex_title: Closing the Computational-Query Depth Gap in Parallel Stochastic Convex
  Optimization
firstpage: 2608
lastpage: 2643
page: 2608-2643
order: 2608
cycles: false
bibtex_author: Jambulapati, Arun and Sidford, Aaron and Tian, Kevin
author:
- given: Arun
  family: Jambulapati
- given: Aaron
  family: Sidford
- given: Kevin
  family: Tian
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
pdf: https://proceedings.mlr.press/v247/jambulapati24b/jambulapati24b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
