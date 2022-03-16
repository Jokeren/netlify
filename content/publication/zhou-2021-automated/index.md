+++
title = "An Automated Tool for Analysis and Tuning of GPU-accelerated Code in HPC Applications"
date = 2021-08-16T20:15:56-07:00
authors = ["**Keren Zhou**", "Xiaozhu Meng", "Ryuichi Sai", "Dejan Grubisic", "John Mellor-Crummey"]
publication_types = ["2"]
abstract = "The US Department of Energys fastest supercomputers and forthcoming exascale systems employ Graphics Processing Units (GPUs) to increase the computational performance of compute nodes. However, the complexity of GPU architectures makes tailoring sophisticated applications to achieve high performance on GPU-accelerated systems a major challenge. At best, prior performance tools for GPU code only provide coarse-grained tuning advice at the kernel level. In this paper, we describe GPA, a performance advisor that suggests potential code optimizations at a hierarchy of levels, including individual lines, loops, and functions. To gather the fine-grained measurements needed to produce such insights, GPA uses instruction sampling and binary instrumentation to monitor execution of GPU code. At the time of this writing, GPU instruction sampling is only available on NVIDIA GPUs. To understand performance losses, GPA uses data flow analysis to approximately attribute measured instruction stalls back to their causes. GPA then analyzes patterns of stalls using information about a programs structure and the GPU architecture to identify optimization strategies that address inefficiencies observed. GPA then employs detailed performance models to estimate the potential speedup that each optimization might provide. Experiments with benchmarks and applications show that GPA provides useful advice for tuning GPU code. We applied GPA to analyze and tune a collection of codes on NVIDIA V100 and A100 GPUs. GPA suggested a collection of optimizations that it estimates will accelerate performance across the set of codes by a geometric mean of 1.21x. Applying these optimizations suggested by GPA accelerated these codes by a geometric mean of 1.19x."
featured = false
tags = ["GPU", "Feedback-directed Optimization", "HPC", "PC Sampling", "Instrumentation"]
publication = "*IEEE Transactions on Parallel and Distributed Systems* (TPDS'21)"
url_source = "https://ieeexplore.ieee.org/document/9470950"
projects = ["GPA"]
+++
