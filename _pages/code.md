---
layout: page
permalink: /code/
title: code
description: Research code releases.
---

<h3 class="code">{{"Global Convergence in Differentiable Games"}}</h3>

Here is a <a href="https://github.com/aletcher/impossibility-global-convergence" target="_blank">notebook</a> to accompany my recent paper: <a href="https://arxiv.org/pdf/2005.12649.pdf" target="_blank">On the Impossibility of Global Convergence in Differentiable Games</a>. Implements a number of multi-loss optimization methods that are shown to enter limit cycles instead of converging in a two-parameter zero-sum game, despite being weakly-coercive, analytic and nondegenerate. This includes GD, AGD, EG, OMD, CO, SGA, LA, LOLA, SOS, and CGD.

This undesirable phenomenom is shown to apply more generally to any 'reasonable' algorithm in the paper, ruling out the possibility of global convergence guarantees in multi-loss optimization.

<h3 class="code">{{"Learning in Differentiable Games"}}</h3>

Over the last few years, different communities (multi-agent, optimization & control) have worked on learning in differentiable games. I released a <a href="https://github.com/aletcher/stable-opponent-shaping" target="_blank">notebook</a> implementing Stable Opponent Shaping (<a href="https://openreview.net/pdf?id=SyGjjsC5tQ" target="_blank">SOS</a>) along with other popular optimization methods (LOLA, LA, SGA, CO, EG, CGD, LSS). A number of games including matching pennies and the iterated prisoner’s dilemma are included, but feel free to define any n-player game and compare the algorithms yourself.
