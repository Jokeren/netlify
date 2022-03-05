+++
title = "Accelerating High-Order Stencils on GPUs"
date = 2021-08-22
authors = ["Ryuichi Sai", "John Mellor-Crummey", "Xiaozhu Meng", "Keren Zhou", "Mauricio Araya-Polo", "Jie Meng"]
publication_types = ["1"]
abstract = "Finite-difference methods based on high-order stencils are commonly used for modeling of seismic wave propagation, weather forecasting, computational fluid dynamics, convolutional neural networks, and others. Nowadays, the community commonly employs graphics processing units (GPUs) to accelerate such stencil computations. As a result, knowing how to write efficient stencil computations for GPUs is of significant interest. While high-performance, low-order stencils on GPUs have been studied extensively in the literature, not all proposed approaches work well for high-order stencils. Furthermore, coping with boundary conditions used with stencils for seismic modeling makes it challenging to efficiently exploit thread-level parallelism on GPUs. In this article, we describe several implementations of a 25-point stencil. We evaluate our stencil code shapes, memory hierarchy usage, data access patterns, and other performance attributes on several modern GPUs and compare them with machine rooflines. On average, our top-performing kernels achieve six times the performance of a 25-point stencil code developed in C and mapped to GPUs using OpenACC. Several of our implementations have excellent performance portability across multiple generations of both NVIDIA and AMD GPUs. "
featured = false
publication = "*Concurrency and Computation: Practice and Experience* (CPE'21)"
tags = ["GPU", "HPC", "Stencils", "NVIDIA", "AMD"]
url_source = "https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.6467"
projects = ["GPA"]
+++

