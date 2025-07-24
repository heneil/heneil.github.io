---
title: "PyPOD-GP: Using PyTorch for accelerated chip-level thermal simulation of the GPU"
collection: publications
category: manuscripts
permalink: /publication/2025-5-pypodgp
excerpt: 'PyPOD-GP is a Pytorch-based, GPU-optimized software for accurate and efficient core-level thermal simulation on many-core processor chips.'
date: 2024-05-17
venue: 'SoftwareX'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2352711025001141'
codeurl: 'https://github.com/784956494/PyPOD-GP/tree/main'
citation: '<ins>Neil He</ins>, Ming-Cheng Cheng, Yu Liu. &quot;PyPOD-GP: Using PyTorch for accelerated chip-level thermal simulation of the GPU &quot; in <i>SoftwareX</i>. Vol.30, p.102147.'
---

The rising demand for high-performance computing (HPC) has made full-chip dynamic thermal simulation in many-core GPUs critical for optimizing performance and extending device lifespans. Proper orthogonal decomposition (POD) with Galerkin projection (GP) has shown to offer high accuracy and massive runtime improvements over direct numerical simulation (DNS). However, previous implementations of POD-GP use MPI-based libraries like PETSc and FEniCS and face significant runtime bottlenecks. We propose a PyTorch-based POD-GP library (PyPOD-GP), a GPU-optimized library for chip-level thermal simulation. PyPOD-GP achieves over 23.4X speedup in training and over 10X speedup in inference on a GPU with over 13,000 cores, with just 1.2% error over the device layer.
