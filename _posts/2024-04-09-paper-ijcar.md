---
layout: post
title: Paper Accepted at IJCAR 2024
date: 2024-04-09 10:25:00
description: the international joint conference on automated reasoning
tags: research papers
categories: research
thumbnail: assets/img/maxpre-proofs.jpg
---

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/maxpre-proofs.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

I am happy to report that our paper _Certified MaxSAT Preprocessing_ has been accepted for publication in the International Joint Conference on Automated Reasoning. In the paper we present an approach to _proof log_ most of the reasoning techniques commonly used when solving instances
of Maximum Satisfiability.

Proof logging refers to the production of a formal proof of correctness that can be independently verified, thus
allowing for complete trust in the result output by a MaxSAT preprocessor without having to assume it is correctly implemented.
We complement the description of the preprocessor with an implementation of a proof logging MaxSAT preprocessor and show that
proof-logging and proof verification can be done within a reasonable overhead on the preprocessing process.

I would like to thank all of my co-authors on the project for their great work!
