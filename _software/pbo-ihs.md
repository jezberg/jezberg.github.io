---
layout: page
title: PBO-IHS
description: Pseudo-Boolean Optimization via Implicit Hitting Sets
img: pbo-ihs.jpg
importance: 3
category: pseudo-Boolean optimization
code: https://bitbucket.org/coreo-group/pbo-ihs-solver/
cite: DBLP:conf/sat/0003BJ22
---

[PBO-IHS](https://bitbucket.org/coreo-group/pbo-ihs-solver/) is an implementation
of the implicit hitting set approach to pseudo-Boolean optimization. PBO-IHS
uses the conflict-driven pseudo-Boolean solver [RoundingSAT](https://gitlab.com/MIAOresearch/software/roundingsat) as a core-extractor and the CPLEX mixed-integer programming solver as a hitting-set solver. We have shown that PBO-IHS achieves orthogonal performance compared to other state-of-the-art PBO-solvers and currently represents one of the best performing approaches to PBO.

PBO-IHS was developed by Pavel Smirnov. It is available in open source (as long as you supply your own MIP solver) on [bitbucket](https://bitbucket.org/coreo-group/pbo-ihs-solver/)
