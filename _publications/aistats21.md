---
title: "Q-learning with Logarithmic Regret"
collection: publications
permalink: /publication/aistats21
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-04-13
authors: '<strong>Kunhe Yang</strong>, Lin Yang, Simon Du'
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'https://proceedings.mlr.press/v130/yang21b.html'
arxivurl: 'https://arxiv.org/abs/2006.09118'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper presents the first non-asymptotic result showing that a model-free algorithm can achieve a logarithmic cumulative regret for episodic tabular reinforcement learning if there exists a strictly positive sub-optimality gap in the optimal Q-function. We prove that the optimistic Q-learning studied in [Jin et al. 2018] enjoys a $\frac{SA\text{poly}(H)}{\Delta_{\min}}\log(SAT)$ cumulative regret bound, where $S$ is the number of states, $A$ is the number of actions, $H$ is the planning horizon, $T$ is the total number of steps, and $\Delta_{\min}$ is the minimum sub-optimality gap. This bound matches the information theoretical lower bound in terms of S,A,T up to a $\log(SA)$ factor. We further extend our analysis to the discounted setting and obtain a similar logarithmic cumulative regret bound.