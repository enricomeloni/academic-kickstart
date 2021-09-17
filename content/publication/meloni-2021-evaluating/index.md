---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Evaluating Continual Learning Algorithms by Generating 3D Virtual Environments
subtitle: ''
summary: ''
authors:
- Enrico Meloni
- Alessandro Betti
- Lapo Faggi
- Simone Marullo
- Matteo Tiezzi
- Stefano Melacci
tags: [sailenv, virtual environments, unity, 3d, computer vision, continual learning]
categories: [Machine Learning, Virtual Environments, Continual Learning]
date: '2021-01-01'
lastmod: 2021-09-17T12:44:41+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Sample scenario created with SAILenv'
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-09-17T10:44:38.452175Z'
publication_types:
- '1'
abstract: 'Continual learning refers to the ability of humans and animals to incrementally learn over time in a given environment. Trying to simulate this learning process in machines is a challenging task, also due to the inherent difficulty in creating conditions for designing continuously evolving dynamics that are typical of the real-world. Many existing research works usually involve training and testing of virtual agents on datasets of static images or short videos, considering sequences of distinct learning tasks. However, in order to devise continual learning algorithms that operate in more realistic conditions, it is fundamental to gain access to rich, fully customizable and controlled experimental playgrounds. Focussing on the specific case of vision, we thus propose to leverage recent advances in 3D virtual environments in order to approach the automatic generation of potentially life-long dynamic scenes with photo-realistic appearance. Scenes are composed of objects that move along variable routes with different and fully customizable timings, and randomness can also be included in their evolution. A novel element of this paper is that scenes are described in a parametric way, thus allowing the user to fully control the visual complexity of the input stream the agent perceives. These general principles are concretely implemented exploiting a recently published 3D virtual environment. The user can generate scenes without the need of having strong skills in computer graphics, since all the generation facilities are exposed through a simple high-level Python interface. We publicly share the proposed generator.'
publication: 'International Workshop on
Continual Semi-Supervised Learning (CSSL) at IJCAI 2021'

links:
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: https://arxiv.org/abs/2109.07855
---
