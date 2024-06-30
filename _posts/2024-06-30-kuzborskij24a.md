---
title: Better-than-KL PAC-Bayes Bounds
section: Original Papers
abstract: " Let $f(\\theta, X_1),$ $ …,$ $ f(\\theta, X_n)$ be a sequence of random
  elements, where $f$ is a fixed scalar function, $X_1, …, X_n$ are independent random
  variables (data), and $\\theta$ is a random parameter distributed according to some
  data-dependent \\emph{posterior} distribution $P_n$. In this paper, we consider
  the problem of proving concentration inequalities to estimate the mean of the sequence.
  An example of such a problem is the estimation of the generalization error of some
  predictor trained by a stochastic algorithm, such as a neural network, where $f$
  is a loss function. Classically, this problem is approached through a \\emph{PAC-Bayes}
  analysis where, in addition to the posterior, we choose a \\emph{prior} distribution
  which captures our belief about the inductive bias of the learning problem. Then,
  the key quantity in PAC-Bayes concentration bounds is a divergence that captures
  the \\emph{complexity} of the learning problem where the de facto standard choice
  is the Kullback-Leibler (KL) divergence. However, the tightness of this choice has
  rarely been  questioned.   In this paper, we challenge the tightness of the KL-divergence-based
  bounds by showing that it is possible to achieve a strictly tighter bound. In particular,
  we demonstrate new \\emph{high-probability} PAC-Bayes bounds with a novel and \\emph{better-than-KL}
  divergence that is inspired by Zhang et al. (2022). Our proof is inspired by recent
  advances in regret analysis of gambling algorithms, and its use to derive concentration
  inequalities. Our result is first-of-its-kind in that existing PAC-Bayes bounds
  with non-KL divergences are not known to be strictly better than KL. Thus, we believe
  our work marks the first step towards identifying optimal rates of PAC-Bayes bounds."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kuzborskij24a
month: 0
tex_title: Better-than-{KL} {PAC}-{B}ayes {B}ounds
firstpage: 3325
lastpage: 3352
page: 3325-3352
order: 3325
cycles: false
bibtex_author: Kuzborskij, Ilja and Jun, Kwang-Sung and Wu, Yulian and Jang, Kyoungseok
  and Orabona, Francesco
author:
- given: Ilja
  family: Kuzborskij
- given: Kwang-Sung
  family: Jun
- given: Yulian
  family: Wu
- given: Kyoungseok
  family: Jang
- given: Francesco
  family: Orabona
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
pdf: https://proceedings.mlr.press/v247/kuzborskij24a/kuzborskij24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
