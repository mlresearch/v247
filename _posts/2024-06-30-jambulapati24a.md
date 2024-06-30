---
title: 'Black-Box k-to-1-PCA Reductions: Theory and Applications'
section: Original Papers
abstract: The $k$-principal component analysis ($k$-PCA) problem is a fundamental
  algorithmic primitive that is widely-used in data analysis and dimensionality reduction
  applications. In statistical settings, the goal of $k$-PCA is to identify a top
  eigenspace of the covariance matrix of a distribution, which we only have black-box
  access to via samples. Motivated by these  settings, we analyze black-box deflation
  methods as a framework for designing $k$-PCA algorithms, where we model access to
  the unknown target matrix via a black-box $1$-PCA oracle which returns an approximate
  top eigenvector, under two popular notions of approximation. Despite being arguably
  the most natural reduction-based approach to $k$-PCA algorithm design, such black-box
  methods, which recursively call a $1$-PCA oracle $k$ times, were previously poorly-understood.  Our
  main contribution is significantly sharper bounds on the approximation parameter
  degradation of deflation methods for $k$-PCA. For a quadratic form notion of approximation
  we term ePCA (energy PCA), we show deflation methods suffer no parameter loss. For
  an alternative well-studied approximation notion we term cPCA (correlation PCA),
  we tightly characterize the parameter regimes where deflation methods are feasible.
  Moreover, we show that in all feasible regimes, $k$-cPCA deflation algorithms suffer
  no asymptotic parameter loss for any constant $k$. We apply our framework to obtain
  state-of-the-art $k$-PCA algorithms robust to dataset contamination, improving prior
  work in sample complexity by a $\mathsf{poly}(k)$ factor.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: jambulapati24a
month: 0
tex_title: 'Black-Box k-to-1-PCA Reductions: Theory and Applications'
firstpage: 2564
lastpage: 2607
page: 2564-2607
order: 2564
cycles: false
bibtex_author: Jambulapati, Arun and Kumar, Syamantak and Li, Jerry and Pandey, Shourya
  and Pensia, Ankit and Tian, Kevin
author:
- given: Arun
  family: Jambulapati
- given: Syamantak
  family: Kumar
- given: Jerry
  family: Li
- given: Shourya
  family: Pandey
- given: Ankit
  family: Pensia
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
pdf: https://proceedings.mlr.press/v247/jambulapati24a/jambulapati24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
