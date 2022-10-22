---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Messing Up 3D Virtual Environments: Transferable Adversarial 3D Objects'
subtitle: ''
summary: ''
authors:
- Enrico Meloni
- Matteo Tiezzi
- Luca Pasqualini
- Marco Gori
- Stefano Melacci
tags: [sailenv, virtual environments, unity, 3d, computer vision, adversarial learning]
categories: [Machine Learning, Virtual Environments, Adversarial Learning]
date: '2021-09-17'
lastmod: 2021-09-20T14:11:30+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Example of attacked object with pipeline architecture'
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-20T12:11:27.373732Z'
publication_types:
- '1'
abstract: 'In the last few years, the scientific community showed a remarkable and increasing interest towards 3D Virtual Environments, training and testing Machine Learning-based models in realistic virtual worlds. On one hand, these environments could also become a mean to study the weaknesses of Machine Learning algorithms, or to simulate training settings that allow Machine Learning models to gain robustness to 3D adversarial attacks. On the other hand, their growing popularity might also attract those that aim at creating adversarial conditions to invalidate the benchmarking process, especially in the case of public environments that allow the contribution from a large community of people. Most of the existing Adversarial Machine Learning approaches are focused on static images, and little work has been done in studying how to deal with 3D environments and how a 3D object should be altered to fool a classifier that observes it. In this paper, we study how to craft adversarial 3D objects by altering their textures, using a tool chain composed of easily accessible elements. We show that it is possible, and indeed simple, to create adversarial objects using off-the-shelf limited surrogate renderers that can compute gradients with respect to the parameters of the rendering process, and, to a certain extent, to transfer the attacks to more advanced 3D engines. We propose a saliency-based attack that intersects the two classes of renderers in order to focus the alteration to those texture elements that are estimated to be effective in the target engine, evaluating its impact in popular neural classifiers.'
publication: 'IEEE International Conference on Machine
Learning and Applications (ICMLA) 2021'

links:
  - icon_pack: ai
    icon: ieee
    name: IEEE Xplore
    url: 'https://ieeexplore.ieee.org/abstract/document/9680120'
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: https://arxiv.org/abs/2109.08465
---
