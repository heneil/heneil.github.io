---
title: "Efficient Diffusion Models for Symmetric Manifolds"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is proposes an efficient diffusion framework for generative modelling on symmetric manifolds, such as the unitary group, with provable convergence guarantees and iteration complexity.'
date: 2025-07-16
venue: 'The Forty-Second International Conference on Machine Learning (ICML)'
paperurl: 'https://arxiv.org/pdf/2505.21640'
codeurl: 'https://github.com/mangoubi/Efficient-Diffusion-Models-for-Symmetric-Manifolds'
citation: 'Oren Mangoubi, <ins>Neil He</ins>, and Nisheeth K. Vishnoi. &quot;Efficient Diffusion Models for Symmetric Manifolds.&quot; in <i>ICML</i>. 2025'
---

Abstract: We introduce a framework for designing efficient diffusion models for $d$-dimensional symmetric-space Riemannian manifolds, including the torus, sphere, special orthogonal group and unitary group. Existing manifold diffusion models often depend on heat kernels, which lack closed-form expressions and require either $d$ gradient evaluations or exponential-in-$d$ arithmetic operations per training step. We introduce a new diffusion model for symmetric manifolds with a spatially-varying covariance, allowing us to leverage a projection of Euclidean Brownian motion to bypass heat kernel computations. Our training algorithm minimizes a novel efficient objective derived via Ito's Lemma, allowing each step to run in $O(1)$ gradient evaluations and nearly-linear-in-$d$ ($O(d^{1.19})$) *arithmetic* operations, reducing the gap between diffusions on symmetric manifolds and Euclidean space. Manifold symmetries ensure the diffusion satisfies an "average-case" Lipschitz condition, enabling accurate and efficient sample generation. Empirically, our model outperforms prior methods in training speed and improves sample quality on synthetic datasets on the torus, special orthogonal group, and unitary group.