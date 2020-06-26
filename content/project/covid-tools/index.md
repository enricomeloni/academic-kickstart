---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning SIR/SIDARTHE"
summary: "Learning the epidemiological parameters of COVID-19 through Machine Learning."
authors: [Enrico Meloni]
tags: [sir, sidarthe, machine learning, pytorch, dynamic systems]
categories: [Machine Learning]
date: 2020-06-24T15:47:27+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Predictions on asymptomatic detected infected"
  focal_point: "Smart"
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

The COVID-19 outbreak has stimulated the interest in the proposal of novel epidemiological models to predict the course of the epidemic so as to help planning effective control strategies. In particular, in order to properly interpret the available data, it has become clear that one must go beyond most classic epidemiological models and consider models that, like the recently proposed SIDARTHE, offer a richer description of the stages of infection. The problem of learning the parameters of these models is of crucial importance especially when assuming that they are time-variant, which further enriches their effectiveness. This project focuses on developing a general approach for learning time-variant parameters of dynamic compartmental models from epidemic data.