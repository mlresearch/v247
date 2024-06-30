---
title: Metalearning with Very Few Samples Per Task
section: Original Papers
abstract: "    Metalearning and multitask learning are two frameworks for solving
  a group of related learning tasks more efficiently than we could hope to solve each
  of the individual tasks on their own.  In multitask learning, we are given a fixed
  set of related learning tasks and need to output one accurate model per task, whereas
  in metalearning we are given tasks that are drawn i.i.d. from a metadistribution
  and need to output some common information that can be easily specialized to new,
  previously unseen tasks from the metadistribution. In this work, we consider a binary
  classification setting where tasks are related by a shared representation, that
  is, every task $P$ of interest can be solved by a classifier of the form $f_{P}
  \\circ h$ where $h \\in \\mathcal{H}$ is a map from features to some representation
  space that is shared across tasks, and $f_{P} \\in \\mathcal{F}$ is a task-specific
  classifier from the representation space to labels.  The main question we ask in
  this work is how much data do we need to metalearn a good representation? Here,
  the amount of data is measured in terms of both the number of tasks $t$ that we
  need to see and the number of samples $n$ per task. We focus on the regime where
  the number of samples per task is extremely small. Our main result shows that, in
  a distribution-free setting where the feature vectors are in $\\mathbb{R}^d$, the
  representation is a linear map from $\\mathbb{R}^d \\to \\mathbb{R}^k$, and the
  task-specific classifiers are halfspaces in $\\mathbb{R}^k$, we can metalearn a
  representation with error $\\varepsilon$ using just $n = k+2$ samples per task,
  and $d \\cdot (1/\\varepsilon)^{O(k)}$ tasks.  Learning with so few samples per
  task is remarkable because metalearning would be impossible with $k+1$ samples per
  task, and because we cannot even hope to learn an accurate task-specific classifier
  with just $k+2$ samples per task.  To obtain this result, we develop a sample-and-task-complexity
  theory for distribution-free metalearning and multitask learning, which identifies
  what properties of $\\mathcal{F}$ and $\\mathcal{H}$ make metalearning possible
  with few samples per task.  Our theory also yields a simple characterization of
  distribution-free multitask learning.  Finally, we give sample-efficient reductions
  between metalearning and multitask learning, which, when combined with our characterization
  of multitask learning, give a characterization of metalearning in certain parameter
  regimes."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aliakbarpour24a
month: 0
tex_title: Metalearning with Very Few Samples Per Task
firstpage: 46
lastpage: 93
page: 46-93
order: 46
cycles: false
bibtex_author: Aliakbarpour, Maryam and Bairaktari, Konstantina and Brown, Gavin and
  Smith, Adam and Srebro, Nathan and Ullman, Jonathan
author:
- given: Maryam
  family: Aliakbarpour
- given: Konstantina
  family: Bairaktari
- given: Gavin
  family: Brown
- given: Adam
  family: Smith
- given: Nathan
  family: Srebro
- given: Jonathan
  family: Ullman
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
pdf: https://proceedings.mlr.press/v247/aliakbarpour24a/aliakbarpour24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
