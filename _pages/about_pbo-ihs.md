## PBO-IHS - Implicit Hitting Sets in Psudo-Boolean Optimization

[PBO-IHS](https://bitbucket.org/coreo-group/pbo-ihs-solver/) is an implementation
of the implicit hitting set approach to pseudo-Boolean optimization. PBO-IHS
uses the conflict-driven pseudo-Boolean solver [RoundingSAT](https://gitlab.com/MIAOresearch/software/roundingsat) {% cite DBLP:conf/ijcai/ElffersN18 --file others %} as a core-extractor and the CPLEX mixed-integer programming solver as a hitting-set solver. Details can be found in {% cite DBLP:conf/cp/SmirnovBJ21 DBLP:conf/sat/0003BJ22 %}. In the paper, we show that PBO-IHS achieves orthogonal performance compared to other state-of-the-art PBO-solvers and currently represents one of the best performing approaches.

PBO-IHS was developed by Pavel SMirnov. It is available in open source (as long as you supply your own MIP solver) on [bitbucket](https://bitbucket.org/coreo-group/pbo-ihs-solver/)
