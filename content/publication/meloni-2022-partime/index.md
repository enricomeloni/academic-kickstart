---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'PARTIME: Scalable and Parallel Processing Over Time with Deep Neural Networks'
subtitle: ''
summary: ''
authors:
- Enrico Meloni
- Lapo Faggi
- Simone Marullo
- Alessandro Betti
- Matteo Tiezzi
- Marco Gori
- Stefano Melacci
tags: [computer vision, continual learning, lifelong learning, multi-gpu, parallelization]
categories: [Machine Learning, Continual Learning, Parallelization]
date: '2022-10-22'
lastmod: 2022-10-22T16:43:06+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Captures of Optical Flow estimation on a given frame (4a) by the vanilla sequential network (4b), compared with the Optical Flow computed by the network handled by PARTIME (4c, 4d).'
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-10-22T14:43:06.599962Z'
publication_types:
- '1'
abstract: 'In this paper, we present PARTIME, a software library written in Python and based on PyTorch, designed specifically to speed up neural networks whenever data is continuously streamed over time, for both learning and inference.
Existing libraries are designed to exploit data-level parallelism, assuming that samples are batched, a condition that is not naturally met in applications that are based on streamed data. Differently, PARTIME starts processing each data sample at the time in which it becomes available from the stream. PARTIME wraps the code that implements a feed-forward multi-layer network and it distributes the layer-wise processing among multiple devices, such as Graphics Processing Units (GPUs). Thanks to its pipeline-based computational scheme, PARTIME allows the devices to perform computations in parallel. At inference time this results in scaling capabilities that are theoretically linear with respect to the number of devices. During the learning stage, PARTIME can leverage the non-i.i.d. nature of the streamed data with samples that are smoothly evolving over time for efficient gradient computations. Experiments are performed in order to empirically compare PARTIME with classic non-parallel neural computations in online learning, distributing operations on up to 8 NVIDIA GPUs, showing significant speedups that are almost linear in the number of devices, mitigating the impact of the data transfer overhead.'
publication: 'IEEE International Conference on Machine
Learning and Applications (ICMLA) 2022'

links:
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: https://arxiv.org/abs/2210.09147
---