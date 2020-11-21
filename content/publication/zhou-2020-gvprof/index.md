+++
title = "GVProf: A Value Profiler for GPU-Based Clusters"
date = 2020-11
authors = ["Keren Zhou", "Yueming Hao", "John Mellor-Crummey", "Xiaozhu Meng", "Xu Liu"]
publication_types = ["1"]
abstract = "GPGPUs are widely used in high-performance computing systems to accelerate scientific and machine learning workloads. Developing efficient GPU kernels is critically important to obtain "bare-metal" performance on GPU-based clusters. In this paper, we describe the design and implementation of GVProf, the first value profiler that pinpoints value-related inefficiencies in applications running on NVIDIA GPU-based clusters. The novelty of GVProf resides in its ability to detect temporal and spatial value redundancies, which provides useful information to guide code optimization. GVProf can monitor production multi-node multi-GPU executions in clusters. Our experiments with well-known GPU benchmarks and HPC applications show that GVProf incurs acceptable overhead and scales to large executions. Using GVProf, we optimized several HPC and machine learning workloads on one NVIDIA V100 GPU. In one case study of LAMMPS, optimizations based on information from GVProf led to whole-program speedups ranging from 1.37x on a single GPU to 1.08x on 64 GPUs."
featured = false
publication = "*Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis* (SC'20)"
url_source = "https://dl.acm.org/doi/10.5555/3433701.3433819"
+++
