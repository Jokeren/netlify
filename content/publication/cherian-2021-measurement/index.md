+++
title = "Measurement and Analysis of GPU-Accelerated OpenCL Computations on Intel GPUs"
date = 2021-10-01T20:15:56-07:00
authors = ["Keren Zhou", "Laksono Adhianto", "Jonathon Anderson", "Aaron Cherian", "Dejan Grubisic", "Mark Krentel", "Yumeng Liu", "Xiaozhu Meng", "John Mellor-Crummey"]
publication_types = ["2"]
abstract = "Graphics Processing Units (GPUs) have become a key technology for accelerating node performance in supercomputers, including the US Department of Energy’s forthcoming exascale systems. Since the execution model for GPUs differs from that for conventional processors, applications need to be rewritten to exploit GPU parallelism. Performance tools are needed for such GPU-accelerated systems to help developers assess how well applications offload computation onto GPUs.In this paper, we describe extensions to Rice University’s HPC-Toolkit performance tools that support measurement and analysis of Intel’s DPC++ programming model for GPU-accelerated systems atop an implementation of the industry-standard OpenCL framework for heterogeneous parallelism on Intel GPUs. HPCToolkit supports three techniques for performance analysis of programs atop OpenCL on Intel GPUs. First, HPC-Toolkit supports profiling and tracing of OpenCL kernels. Second, HPCToolkit supports CPU-GPU blame shifting for OpenCL kernel executions—a profiling technique that can identify code that executes on one or more CPUs while GPUs are idle. Third, HPCToolkit supports fine-grained measurement, analysis, and attribution of performance metrics to OpenCL GPU kernels, including instruction counts, execution latency, and SIMD waste. The paper describes these capabilities and then illustrates their application in case studies with two applications that offload computations onto Intel GPUs."
featured = false
publication = "*2021 IEEE/ACM International Workshop on Programming and Performance Visualization Tools* (ProTools'21)"
tags = ["GPU", "HPC", "Instrumentation", "Intel", "Profiler"]
url_source = "https://ieeexplore.ieee.org/document/9651230"
projects = ["hpctoolkit"]
+++

