---
layout: page
title: MaxPre
description: preprocessing for maximum satisfiability
img: maxpre.png
importance: 2
category: MaxSAT
code: https://bitbucket.org/coreo-group/maxpre2/src/master/
cite: DBLP:conf/sat/KorhonenBSJ17
---

[MaxPRE](https://bitbucket.org/coreo-group/maxpre2/src/master/) is a preprocessor
capable of simplifying single-, and multiobjective MaxSAT instances in a cost-preserving manner.
MaxPre imnplements a wide-range of different simplification rules, including MaxSAT-liftings of preprocessing rules commonly used in SAT solving (BVE, SE; SCE, BVA etc.) as well as MaxSAT-specific preprocessing rules that we have developed in our group.

MaxPre implements a multitude of the algorithmic techniques proposed by me during my PhD research and after it. MaxPre can be used either as stand-alone, or through an API that allows tight integration with your solver. The first version of MaxPRE was developed by Tuukka Korhonen, The source code of that version is available in open-source on [github](https://github.com/Laakeri/maxpre).

The second version of MaxPRE, dubbed MaxPre 2.0 is currently developed by Hannes Ihalainen. It is available in open-source on [bitbucket](https://bitbucket.org/coreo-group/maxpre2/src/master/). Compared to the first version, MaxPre 2.0 includes a number of quality of life improvements and extended reasoning techniques.
