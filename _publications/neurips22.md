---
title: "Oracle-Efficient Online Learning for Smoothed Adversaries"
collection: publications
permalink: /publication/neurips22
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2022-11-01
venue: 'In Proceedings of the 35th Annual Conference on Neural Information Processing Systems (Neurips 2022)'
authors: 'Nika Haghtalab*, Yanjun Han*, Abhishek Shetty*, <strong>Kunhe Yang</strong>*'
arxivurl: 'https://arxiv.org/abs/2202.08549'
award: 'Oral Presentation'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

\textbf{Abstract}: We study the design of computationally efficient online learning algorithms under smoothed analysis. In this setting, at every step, an adversary generates a sample from an adaptively chosen distribution whose density is upper bounded by $1/\sigma$ times the uniform density. Given access to an offline optimization (ERM) oracle, we give the first computationally efficient online algorithms whose sublinear regret depends only on the pseudo/VC dimension $d$ of the class and the smoothness parameter $\sigma$. In particular, we achieve \emph{oracle-efficient} regret bounds of $ O ( \sqrt{T d\sigma^{-1}} ) $ for learning real-valued functions and $ O ( \sqrt{T d\sigma^{-\frac{1}{2}} } )$ for learning binary-valued functions. Our results establish that online learning is computationally as easy as offline learning, under the smoothed analysis framework. This contrasts the computational separation between online learning with worst-case adversaries and offline learning established by [HK16].Our algorithms also achieve improved bounds for some settings with binary-valued functions and worst-case adversaries. These include an oracle-efficient algorithm with $O ( \sqrt{T(d |\mathcal{X}|)^{1/2} })$ regret that refines the earlier $O ( \sqrt{T|\mathcal{X}|})$ bound of [DS16] for finite domains, and an oracle-efficient algorithm with $O(T^{3/4} d^{1/2})$ regret for the transductive setting.

<a href='https://arxiv.org/pdf/2202.08549.pdf'>Download PDF here</a>