## MaxHS with Abstract Cores

During my visit to Toronto in 2019. We worked on extending the implicit hitting set (IHS) algorithm
for MaxSAT with abstract cores. The resulting algorithm is presented in {% cite DBLP:conf/sat/BergBP20 %}
which won the best paper award at the 2020 SAT conferece, the flagship conference of the research field of
Boolean satisfiability.

Our implementation abstract cores into the MaxSAT solver [MaxHS](http://www.maxhs.org/)
{% cite DBLP:conf/sat/DaviesB13 --file others %} was shown to significantly
improve its performance. The solver took top positions in the 2020 and 2021 [MaxSAT Evaluations](https://maxsat-evaluations.github.io/). More recently, in {% cite DBLP:conf/ijcai/IhalainenBJ23 %}, we have shown how abstract cores can be used as a basis for a framework that unifies most of the existing SAT-based MaxSAT algorithms.

MaxHS is available in open source [here](http://www.maxhs.org/downloads.html), as long as you have a MIP solver to use for the hitting set computations.
