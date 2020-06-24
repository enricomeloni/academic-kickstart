---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Exp Launcher"
summary: "An Electron app for managing and launching batch of experiments"
authors: [Enrico Meloni, Raffaele Zippo, Marco Pinna]
tags: [typescript, electron, experiments, data analysis, data visualization]
categories: [Software Development]
date: 2020-06-24T15:47:38+02:00

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
## WARNING: This is an ongoing project

Experiment Launcher (temporary name) is a scientific utility aimed at storing the experimental results out-putted by a third party software. It allows the user to specify an experiment with a set of parameters andan executable file, and then proceeds to launch the executable and collecting the output. The output is then provided to the user in a human-friendly interface, recording important information such as the date and timewhen the experiment was launched, the parameters, and also the executable version (if version control is used).