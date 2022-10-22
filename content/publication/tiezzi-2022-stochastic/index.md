---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Stochastic Coherence Over Attention Trajectory For Continuous Learning In Video
  Streams'
subtitle: ''
summary: ''
authors:
- Matteo Tiezzi
- Simone Marullo
- Lapo Faggi
- Enrico Meloni
- Alessandro Betti
- Stefano Melacci
tags:
- virtual environments
- continuous learning
- computer vision
- lifelong learning
categories: [Machine Learning, Virtual Environments, Computer Vision]
date: '2022-04-26'
lastmod: 2022-05-31T16:11:55+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Example of the learning protocol'
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-04-26T14:11:53.981152Z'
publication_types:
- '1'
abstract: 'Devising intelligent agents able to live in an environment and learn by observing the surroundings is a longstanding goal of Artificial Intelligence. From a bare Machine Learning perspective, challenges arise when the agent is prevented from leveraging large fully-annotated dataset, but rather the interactions with supervisory signals are sparsely distributed over space and time. This paper proposes a novel neural-network-based approach to progressively and autonomously develop pixel-wise representations in a video stream. The proposed method is based on a human-like attention mechanism that allows the agent to learn by observing what is moving in the attended locations. Spatio-temporal stochastic coherence along the attention trajectory, paired with a contrastive term, leads to an unsupervised learning criterion that naturally copes with the considered setting. Differently from most existing works, the learned representations are used in open-set class-incremental classification of each frame pixel, relying on few supervisions. Our experiments leverage 3D virtual environments and they show that the proposed agents can learn to distinguish objects just by observing the video stream. Inheriting features from state-of-the art models is not as powerful as one might expect.'
publication: '31st International Joint Conference on Artificial Intelligence (IJCAI-ECAI 2022)'
links:
  - icon_pack: ai
    icon: arxiv
    name: arXiv
    url: https://arxiv.org/abs/2204.12193
---
