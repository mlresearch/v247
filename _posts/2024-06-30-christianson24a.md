---
title: Risk-Sensitive Online Algorithms (Extended Abstract)
section: Original Papers
abstract: 'We study the design of risk-sensitive online algorithms, in which risk
  measures are used in the competitive analysis of randomized online algorithms. We
  introduce the CVaR$_\delta$-competitive ratio ($\delta$-CR) using the conditional
  value-at-risk of an algorithm’s cost, which measures the expectation of the $(1-\delta)$-fraction
  of worst outcomes against the offline optimal cost, and use this measure to study
  three online optimization problems: continuous-time ski rental, discrete-time ski
  rental, and one-max search. The structure of the optimal $\delta$-CR and algorithm
  varies significantly between problems: we prove that the optimal $\delta$-CR for
  continuous-time ski rental is $2-2^{-\Theta(\frac{1}{1-\delta})}$, obtained by an
  algorithm described by a delay differential equation. In contrast, in discrete-time
  ski rental with buying cost $B$, there is an abrupt phase transition at $\delta
  = 1 - \Theta(\frac{1}{\log B})$, after which the classic deterministic strategy
  is optimal. Similarly, one-max search exhibits a phase transition at $\delta = \frac{1}{2}$,
  after which the classic deterministic strategy is optimal; we also obtain an algorithm
  that is asymptotically optimal as $\delta \todown 0$ that arises as the solution
  to a delay differential equation.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: christianson24a
month: 0
tex_title: Risk-Sensitive Online Algorithms (Extended Abstract)
firstpage: 1140
lastpage: 1141
page: 1140-1141
order: 1140
cycles: false
bibtex_author: Christianson, Nicolas and Sun, Bo and Low, Steven and Wierman, Adam
author:
- given: Nicolas
  family: Christianson
- given: Bo
  family: Sun
- given: Steven
  family: Low
- given: Adam
  family: Wierman
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
pdf: https://proceedings.mlr.press/v247/christianson24a/christianson24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
