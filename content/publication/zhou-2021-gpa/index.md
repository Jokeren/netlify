+++
title = "GPA: A GPU Performance Advisor Based on Instruction Sampling"
date = 2021-02-01
authors = ["Keren Zhou", "Xiaozhu Meng", "Ryuichi Sai", "John Mellor-Crummey"]
publication_types = ["1"]
abstract = "Developing efficient GPU kernels can be difficult because of the complexity of GPU architectures and programming models. Existing performance tools only provide coarse-grained tuning advice at the kernel level, if any. In this paper, we describe GPA, a performance advisor for NVIDIA GPUs that suggests potential code optimizations at a hierarchy of levels, including individual lines, loops, and functions. To relieve users of the burden of interpreting performance counters and analyzing bottlenecks, GPA uses data flow analysis to approximately attribute measured instruction stalls to their root causes and uses information about a program's structure and the GPU to match inefficiency patterns with optimization strategies. To quantify the potential benefits of each optimization strategy, we developed PC sampling-based performance models to estimate its speedup. Our experiments with benchmarks and applications show that GPA provides insightful reports to guide performance optimization. Using GPA, we obtained speedups on a Volta V100 GPU ranging from 1.01x to 3.58x, with a geometric mean of 1.22x."
featured = false
publication = "*IEEE/ACM International Symposium on Code Generation and Optimization* (CGO'21)"
url_source = "https://ieeexplore.ieee.org/document/9370339"
projects = ["GPA"]
+++
