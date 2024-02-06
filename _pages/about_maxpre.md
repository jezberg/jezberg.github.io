## MaxPre - Preprocessing for (multiobjective) MaxSAT

[MaxPRE](https://bitbucket.org/coreo-group/maxpre2/src/master/) is a stand-alone preprocessor
capable of simplifying single, and multiobjective MaxSAT instances in a cost-preserving manner.
MaxPre imnplements a wide-range of different simplification rules, including MaxSAT-liftings of preprocessing rules commonly used in SAT solving (BVE, SE; SCE, BVA etc.) as well as MaxSAT-specific preprocessing rules that we have developed in our group. See {% cite DBLP:conf/cade/IhalainenBJ22 DBLP:conf/cp/JabsBIJ23 DBLP:conf/sat/KorhonenBSJ17 %} for more details.

MaxPre implements a multitude of the algorithmic techniques proposed by me during my PhD research and after it. Furthermore, as it is developed by people much more capable than me, it is also user friendly. It can be used either as stand-alone, or through an API that allows tight integration with your solver. The first version of MaxPRE was developed by Tuukka Korhonen, The source code is available in open-source on [github](https://github.com/Laakeri/maxpre).

The second version of MaxPRE, dubbed MaxPre 2.0 is currently developed by Hannes Ihalainen. It is available in open-source on [bitbucket](https://bitbucket.org/coreo-group/maxpre2/src/master/). Compared to the first version, MaxPre 2.0 includes a number of quality of life changes and a number of extended reasoning techniques.
