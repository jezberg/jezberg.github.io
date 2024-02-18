---
layout: page
title: Abstract Cores
description: for implicit hitting sets
img: maxhs-abs.jpg
importance: 1
category: MaxSAT
code: http://www.maxhs.org/downloads.html
cite: DBLP:conf/sat/BergBP20
---

During my visit to Toronto in 2019. We worked on extending the implicit hitting set (IHS) algorithm
for MaxSAT with abstract cores, which can be seen as a hybridization between core-guided and hitting set-based algorithms, as well as symmetry
breaking. The work was recognized with a paper award at the 2020 SAT conferece, the flagship conference of the research field of Boolean satisfiability.

We show how adding abstract cores into the MaxSAT solver [MaxHS](http://www.maxhs.org/)
significantly improves its performance. The solver took top positions in the 2020 and 2021 [MaxSAT Evaluations](https://maxsat-evaluations.github.io/). More recently, we have shown how abstract cores can be used as a basis for a framework that unifies most of the existing SAT-based MaxSAT algorithms.

MaxHS is available in open source [here](http://www.maxhs.org/downloads.html), as long as you have a MIP solver to use for the hitting set computations.
