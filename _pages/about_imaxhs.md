## Incremental Implicit Hitting Sets

IMaxHS is an incremental version of the MaxHS solver that implements the
implicit hitting set approach to MaxSAT (orginally described in {% cite DBLP:conf/sat/DaviesB13 --file others %}).
IMaxHS is tailored for applications that require solving a sequence of optimization problems. By maintaining
its internal state we demonstrate that IMaxHS can e.g. learn interpretable classifiers much more efifciently
compared to the naive approach of restartign search from scratch. More details on IMaxHS can be found in {% cite DBLP:conf/cp/NiskanenBJ21 DBLP:conf/sat/NiskanenBJ22 %}

We implemented a version of the implicit hitting set based approach to MaxSAT solving that supports changing weights between iterations while maintaining its internal state. In the paper, we demonstrate how maintaining the state greatly improves empirical performance on two applications from the domain of learning interpretable classifiers.

Andreas Niskanen is the primary developer of iMaxHS. The source code can be found [bitbucket](https://bitbucket.org/coreo-group/incremental-maxhs/)
