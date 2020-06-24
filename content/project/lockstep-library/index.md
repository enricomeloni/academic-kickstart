---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Lockstep Library"
summary: "A Lockstep Network Synchronization Layer for distributed reliable simulations"
authors: [Enrico Meloni, Raffaele Zippo]
tags: [java, concurrent systems, distributed systems, distributed simulations, lockstep]
categories: [Software Development]
date: 2020-06-24T15:46:57+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
This library was developed as group project for Concurrent and Distributed Systems course.

The idea behind this project was to implement first-hand a synchronization layer like most multiplayer games use nowadays. The simulation (game) in object is collaborative effort where multiple clients generate inputs that drive it. The synchronization layer has to guarantee that each client processes inputs in the correct order so that everyone has a consistent view of the simulation, without ever sharing its state directly.

We chose to implement the most strict version of lockstep, which doesn't allow for the simulation to go on speculatively in case of delays, contrary to most games. We also chose the client-server structure, which should give the lowest delay in most cases. In order to make the library as generic as possible, we chose to use Java Serialization for marshalling/unmarshalling. This gives a huge overhead in terms of bandwidth, and should be reconsidered given the specific application needs.

GitHub page: https://github.com/MeloniZippoProjects/LockstepLibrary