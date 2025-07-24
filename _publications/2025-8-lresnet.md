---
title: "Lorentzian Residual Neural Networks"
collection: publications
category: conferences
permalink: /publication/2025-8-lresnet
excerpt: 'This paper proposes an efficient, stable, and effective residual neural network framework in hyperbolic space.'
date: 2025-08-03
venue: 'ACM SIGKDD International Conference on Knowledge Discovery and Data Mining'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2412.14695'
codeurl: 'https://github.com/Graph-and-Geometric-Learning/LResNet'
citation: '<ins>Neil He</ins>, Menglin Yang, and Rex Ying. 2025. Lorentzian Residual Neural Networks. In <i> KDD </i>.'
---
Hyperbolic neural networks have emerged as a powerful tool for modeling hierarchical data structures prevalent in real-world datasets. Notably, residual connections, which facilitate the direct flow of information across layers, have been instrumental in the success of deep neural networks. However, current methods for constructing hyperbolic residual networks suffer from limitations such as increased model complexity, numerical instability, and errors due to multiple mappings to and from the tangent space. To address these limitations, we introduce LResNet, a novel Lorentzian residual neural network based on the weighted Lorentzian centroid in the Lorentz model of hyperbolic geometry. Our method enables the efficient integration of residual connections in Lorentz hyperbolic neural networks while preserving their hierarchical representation capabilities. We demonstrate that our method can theoretically derive previous methods while offering improved stability, efficiency, and effectiveness. Extensive experiments on both graph and vision tasks showcase the superior performance and robustness of our method compared to state-of-the-art Euclidean and hyperbolic alternatives. Our findings highlight the potential of LResNet for building more expressive neural networks in hyperbolic embedding space as a generally applicable method to multiple architectures, including CNNs, GNNs, and graph Transformers.
