---
title: "Nudge: Stochastically Improving upon FCFS"
collection: publications
permalink: /publication/sigmetrics21
# excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2021-05-31
authors: Isaac Grosof, <strong>Kunhe Yang</strong>, Ziv Scully, Mor Harchol-Balter
venue: 'ACM Sigmetrics'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3410220.3460102'
arxivurl: 'https://arxiv.org/abs/2106.01492'
award: 'Sigmetrics 2021 Best Paper Award'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

<a href='https://arxiv.org/pdf/2106.01492.pdf'>Download PDF here</a>

Abstract: The First-Come First-Served (FCFS) scheduling policy is the most popular scheduling algorithm used in practice. Furthermore, its usage is theoretically validated: for light-tailed job size distributions, FCFS has weakly optimal asymptotic tail of response time. But what if we don't just care about the asymptotic tail? What if we also care about the 99th percentile of response time, or the fraction of jobs that complete in under one second? Is FCFS still best? Outside of the asymptotic regime, only loose bounds on the tail of FCFS are known, and optimality is completely open.

In this paper, we introduce a new policy, Nudge, which is the first policy to provably stochastically improve upon FCFS. We prove that Nudge simultaneously improves upon FCFS at every point along the tail, for light-tailed job size distributions. As a result, Nudge outperforms FCFS for every moment and every percentile of response time. Moreover, Nudge provides a multiplicative improvement over FCFS in the asymptotic tail. This resolves a long-standing open problem by showing that, counter to previous conjecture, FCFS is not strongly asymptotically optimal.