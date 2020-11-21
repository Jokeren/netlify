+++
title = "GVProf: A Value Profiler for GPU-Based Clusters"
date = 2020-11

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Keren Zhou", "Yueming Hao", "John Mellor-Crummey", "Xiaozhu Meng", "Xu Liu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Proceedings of the International Conference for High Performance Computing, Networking, Storage and Analysis"
publication_short = "SC"

# Abstract.
abstract = "GPGPUs are widely used in high-performance computing systems to accelerate scientific and machine learning workloads. Developing efficient GPU kernels is critically important to obtain "bare-metal" performance on GPU-based clusters. In this paper, we describe the design and implementation of GVProf, the first value profiler that pinpoints value-related inefficiencies in applications running on NVIDIA GPU-based clusters. The novelty of GVProf resides in its ability to detect temporal and spatial value redundancies, which provides useful information to guide code optimization. GVProf can monitor production multi-node multi-GPU executions in clusters. Our experiments with well-known GPU benchmarks and HPC applications show that GVProf incurs acceptable overhead and scales to large executions. Using GVProf, we optimized several HPC and machine learning workloads on one NVIDIA V100 GPU. In one case study of LAMMPS, optimizations based on information from GVProf led to whole-program speedups ranging from 1.37x on a single GPU to 1.08x on 64 GPUs."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://dl.acm.org/doi/10.5555/3433701.3433819"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
