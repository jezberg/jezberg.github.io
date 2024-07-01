---
layout: post
title: Paper Accepted in JAIR
date: 2024-06-03 10:25:00
description: The Journal of Artificial Intelligence Research
tags: research papers
categories: research
thumbnail: assets/img/bioptsat.png
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bioptsat.png" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>
</div>

I am happy let you know that our paper _From Single-Objective to Bi-Objective Maximum Satisfiability Solving_ has been accepted for publication in the [Journal of Artificial Intelligence Research](https://www.jair.org/index.php/jair), one of the most prestigious journals in my field. The paper is an extension of our [SAT](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.SAT.2022.12) paper from 2022.

In the paper, we present [BiOptSAT](https://bitbucket.org/coreo-group/bioptsat/src/master/), a framework for extending single-objective algorithms for Maximum Satisfiability into the bi-objective setting. In bi-objective optimization, we are looking for a set of solutions that--informally speaking--balance two objectives as well as possible. An example of a bi-objective optimization problem that we often use is the problem of buying a house or an apartment that, on the one hand, should be as close to the center of town as possible but, on the other, should be as affordable as possible. As these two goals conflict, there is no clear single "best" solution. Instead, we seek solutions that can not be improved in "an obvious way". In other words, we are interested only in houses for which all cheaper options are further away or for which all closer options are more expensive. The paper shows how to solve problems like these with declarative, constraint-based methods.

I want to thank all of my co-authors for their excellent work!
