## Loandra

Loandra is an any-time MaxsAT solver that implements the so called [core-boosted search algorithm](https://www.cs.helsinki.fi/u/jezberg/papers/CPAIOR2019_Berg_Demirovic_Stuckey.pdf) that we developed during my visit to Melbourne in 2018 and describe in {% cite DBLP:conf/cpaior/BergDS19 %}.
Core-boosted search is a two stage search strategy that starts of in a core-guided (lower bounding) phase and then switches to a linear (upper bounding) phase. Loandra performed very well in the [2019 MaxSAT Evaluation](https://maxsat-evaluations.github.io/2019/rankings.html), placing first and second in the unweighted and weighted incomplete tracks, respectively. The algorithmic ideas underlying Loandra have also been implemented in pseudo-Boolean optimization {% cite DBLP:conf/aaai/DevriendtGDNS21 --file others %}, and constraint programming {% cite DBLP:conf/cpaior/GangeBDS20 %}

In [2021](https://maxsat-evaluations.github.io/2021/rankings.html) Loandra with added preprocessing again did very well, taking first in the weighted 300s category and 4th in all others.

Loandra is mainly developed by me, the source code can be found on [github](https://github.com/jezberg/loandra). Loandra owns much of its existence to the developers of [Open WBO](https://sat.inesc-id.pt/open-wbo/). I'd like to thank them for their hard work.
