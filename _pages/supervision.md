---
layout: page
permalink: /supervision/
title: supervision
description: list of all of the students I have or am supervising
nav: false
nav_order: 6
---

## Master's Theses

At the University of Helsinki, a master's thesis corresponds to 30 ECTS credits
of work.

In total {% bibliography_count --file theses_supervised --template bib_thesis --query @*[type=MSC] %} master's theses supervised.

<div class="publications">
{% bibliography --file theses_supervised --template bib_thesis --query @*[type=MSC] %}
</div>

<hr>

## Bachelor's Theses

At the University of Helsinki, a bachelor's thesis corresponds to 30 ECTS credits
of work. The thesis is meant to be completed at the end of ones studies.

In total {% bibliography_count --file theses_supervised --template bib_thesis --query @*[type=BSC] %} theses supervised.

<div class="publications">
{% bibliography --file theses_supervised --template bib_thesis --query @*[type=BSC] %}
</div>
