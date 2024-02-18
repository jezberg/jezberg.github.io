---
layout: page
title: CGSS
description: a core-guided MaxSAT solver
img: cgss.jpg
importance: 6
category: MaxSAT
code: https://bitbucket.org/coreo-group/cgss2/
cite: DBLP:conf/cp/IhalainenBJ21
---

[CGSS](https://bitbucket.org/coreo-group/cgss2/) is an effective implementation of the OLL algorithm for MaxSAT. The first version of CGSS was built on top of the [RC2](https://pysathq.github.io/docs/html/api/examples/rc2.html) MaxSAT solver in Python. The current--and much more effective--version is a reimplementation from scratch in C++. Most notably, CGSS extends RC2 with the so called structure sharing (SS) technique that results in more compact encodings of the constraints required for
optimization. More details can be found in {% cite DBLP:conf/cp/IhalainenBJ21 %}.

CGSS is developed by my PhD student Hannes Ihalainen who wrote [his M.Sc. thesis](https://helda.helsinki.fi/items/f77e9a26-87b6-43ae-8e86-3de2af8417be) on it. The implementation is available in open source on [bitbucket](https://bitbucket.org/coreo-group/cgss2/). The first (Python) version of CGSS was further extended with _proof logging_ in 2023 by Andy Oertel. The source code of the proof-logging version can be found on [gitlab](https://gitlab.com/MIAOresearch/software/certified-cgss)
