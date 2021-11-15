+++
title = "Measurement and analysis of GPU-accelerated applications with HPCToolkit"
date = 2021-10-01T20:15:56-07:00
authors = ["Keren Zhou", "Laksono Adhianto", "Jonathon Anderson", "Aaron Cherian", "Dejan Grubisic", "Mark Krentel", "Yumeng Liu", "Xiaozhu Meng", "John Mellor-Crummey"]
publication_types = ["1"]
abstract = "To address the challenge of performance analysis on the US DOE’s forthcoming exascale supercomputers, Rice University has been extending its HPCToolkit performance tools to support measurement and analysis of GPU-accelerated applications. To help developers understand the performance of accelerated applications as a whole, HPCToolkit’s measurement and analysis tools attribute metrics to calling contexts that span both CPUs and GPUs. To measure GPU-accelerated applications efficiently, HPCToolkit employs a novel wait-free data structure to coordinate monitoring and attribution of GPU performance. To help developers understand the performance of complex GPU code generated from high-level programming models, HPCToolkit constructs sophisticated approximations of call path profiles for GPU computations. To support fine-grained analysis and tuning, HPCToolkit uses PC sampling and instrumentation to measure and attribute GPU performance metrics to source lines, loops, and inlined code. To supplement fine-grained measurements, HPCToolkit can measure GPU kernel executions using hardware performance counters. To provide a view of how an execution evolves over time, HPCToolkit can collect, analyze, and visualize call path traces within and across nodes. Finally, on NVIDIA GPUs, HPCToolkit can derive and attribute a collection of useful performance metrics based on measurements using GPU PC samples. We illustrate HPCToolkit’s new capabilities for analyzing GPU-accelerated applications with several codes developed as part of the Exascale Computing Project. "
featured = false
publication = "*Parallel Computing* (PARCO'21)"
tags = ["GPU", "HPC", "Instrumentation", "Deep Learning", "Profiler"]
url_source = "https://www.sciencedirect.com/science/article/pii/S0167819121000843"
projects = ["hpctoolkit"]
+++

