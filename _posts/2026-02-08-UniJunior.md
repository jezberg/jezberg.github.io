---
layout: post
title: Uni Junior - Making a game AI with a matchboxes 
date: 2026-02-08 17:39:00
description: Uni Junior Workshop
categories: current-events
tag: unijunior
thumbnail: assets/img/UniJunior-Feb26-4.JPG
---

After a few years’ break, I organized a workshop as part of the [Uni Junior](https://www.helsinki.fi/sv/vetenskapsfostran/barn-unga-och-familjer/unijunior) project, which I’ve been involved with for many years now. This time, the workshop focused on game AIs. Specifically, we looked at the (very simple) game of Hexapawn and two different ways to build an AI for it. One of the AIs was rule-based and required its “developer” to specify an explicit rule for which move the AI should make in any given position. The second was a “training AI” that stored good moves in a set of 24 matchboxes and could be trained by removing moves that led to a defeat.

Hexapawn is a tiny, beginner-friendly strategy game played on a 3×3 board using just pawns. Each player tries to reach the opponent’s back row, capture all opposing pawns, or leave the opponent with no legal moves. Because the game is so small, it’s perfect for exploring basic ideas in game strategy and AI, even if even the younger participants of the workshop managed to find perfect strategies for their AIs.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/UniJunior-Feb26-1.JPG" class="img-fluid rounded z-depth-1" zoomable=true  %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/UniJunior-Feb26-2.JPG" class="img-fluid rounded z-depth-1" zoomable=true  %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/UniJunior-Feb26-3.JPG" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

Thank you to everyone involved in the organization—especially my great assistants, who were fantastic at working with the kids! The Swedish material I made for the lab can (at least for a while) be found on [my Google Drive](https://docs.google.com/document/d/1icn4yblXP7MV41wQyJa0AgU4repSbo5WFzjricFde4c/edit?usp=sharing). The idea for the lab was heavily influenced by a [YouTube video](https://www.youtube.com/watch?v=sw7UAZNgGg8) by Vsauce2 and the [AI Unplugged](<(https://www.aiunplugged.org/)>) materials.
