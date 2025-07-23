---
title: "HyperCore: The Core Framework for Building Hyperbolic Foundation Models with Comprehensive Modules"
collection: publications
category: conferences
permalink: /publication/2025-5-hypercore
excerpt: 'HyperCore is an easy-to-use, open source library for building hyperbolic deep learning networks, especially hyperbolic foundation models. This paper details the library components and builds the several novel hyperbolic foundation models with it, such as hyperbolic CLIP, ViT, and GraphRAG.'
date: 2025-06-01
venue: 'TheWebConf NEGEL Workshop'
paperurl: 'https://arxiv.org/abs/2504.08912'
codeurl: 'https://github.com/Graph-and-Geometric-Learning/HyperCore'
citation: 'Neil He, Menglin Yang, and Rex Ying. &quot;HyperCore: The Core Framework for Building Hyperbolic Foundation Models with Comprehensive Modules.&quot; <i>TheWebConf NEGEL Workshop</i>. 2025.'
---

Hyperbolic neural networks have emerged as a powerful tool for modeling hierarchical data across diverse modalities. Recent studies show that token distributions in foundation models exhibit scale-free properties, suggesting that hyperbolic space is a more suitable ambient space than Euclidean space for many pre-training and downstream tasks. However, existing tools lack essential components for building hyperbolic foundation models, making it difficult to leverage recent advancements. We introduce HyperCore, a comprehensive open-source framework that provides core modules for constructing hyperbolic foundation models across multiple modalities. HyperCore's modules can be effortlessly combined to develop novel hyperbolic foundation models, eliminating the need to extensively modify Euclidean modules from scratch and possible redundant research efforts. To demonstrate its versatility, we build and test the first fully hyperbolic vision transformers (LViT) with a fine-tuning pipeline, the first fully hyperbolic multimodal CLIP model (L-CLIP), and a hybrid Graph RAG with a hyperbolic graph encoder. Our experiments demonstrate that LViT outperforms its Euclidean counterpart. Additionally, we benchmark and reproduce experiments across hyperbolic GNNs, CNNs, Transformers, and vision Transformers to highlight HyperCore's advantages.