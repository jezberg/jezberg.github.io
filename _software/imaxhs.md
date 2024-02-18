---
layout: page
title: IMaxHS
description: incremental optimization with hitting sets
img: inc_hs.jpg
importance: 5
category: MaxSAT
code: https://bitbucket.org/coreo-group/incremental-maxhs/
cite: DBLP:conf/sat/NiskanenBJ22
---

IMaxHS is an incremental version of the MaxHS solver that implements the
implicit hitting set approach to MaxSAT.
IMaxHS is tailored toward applications that require solving a sequence of optimization problems. By maintaining
its internal state we demonstrate that IMaxHS can e.g. learn interpretable classifiers much more efifciently
compared to the naive approach of restaring search from scratch on each iteration.

iMaxHS is primarly developed by Andreas Niskanen.
