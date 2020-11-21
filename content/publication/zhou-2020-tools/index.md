+++
title = "Tools for Top-down Performance Analysis of GPU-Accelerated Applications"
date = 2020-07-01
authors = ["Keren Zhou", "Mark W. Krentel", "John Mellor-Crummey"]
publication_types = ["1"]
abstract = "This paper describes extensions to Rice University's HPCToolkit performance tools to support measurement and analysis of GPU-accelerated applications. To help developers understand the performance of accelerated applications as a whole, HPCToolkit's measurement and analysis tools attribute metrics to calling contexts that span both CPUs and GPUs. To measure GPU-accelerated applications efficiently, HPCToolkit employs a novel wait-free data structure to coordinate monitoring and attribution of GPU performance metrics. To help developers understand the performance of complex GPU code generated from high-level programming models, HPCToolkit's hpcprof constructs sophisticated approximations of call path profiles for GPU computations. To support fine-grain analysis and tuning, HPCToolkit attributes GPU performance metrics to source lines and loops. Also, HPCToolkit uses GPU PC samples to derive and attribute a collection of useful GPU performance metrics. We illustrate HPCToolkit's new capabilities for analyzing GPU- accelerated applications with three case studies."
featured = false
publication = "*Proceedings of the 34th ACM International Conference on Supercomputing* (ICS'20)"
tags = ["calling context tree", "profiler", "roofline", "GPU", "wait-free", "HPC"]
url_pdf = "https://doi.org/10.1145/3392717.3392752"
doi = "10.1145/3392717.3392752"
+++

