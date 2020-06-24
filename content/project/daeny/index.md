---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Object Detection with V-DAENY"
summary: "A Dataset Generator powered by a modded version of GTA V"
authors: [Enrico Meloni, Marco Di Benedetto, Giuseppe Amato, Fabrizio Falchi, Claudio Gennaro]
tags: [virtual environments, computer vision, gta5, c#, YOLO, machine learning, object detection]
categories: [Machine Learning]
date: 2020-06-24T15:48:01+02:00

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

Recently, Deep Neural Networks have seen many successful applications, thanks to the huge amount of data that has steadily become more and more available with the growth of the internet. When annotations are not already available, images must be manually annotated introducing costs that can possibly be very high. Furthermore, in some contexts also gathering valuable images could be impractical for reasons related to privacy, copyright and security.
To overcome these limitations the research community has started to take interest in creating virtual environments for the generation of automatically annotated training samples. In previous literature, using a graphics engine for augmenting a training dataset has been proven a valid solution. 
In this work, we applied the virtual environment to approach to a not yet considered task: the detection of personal protection equipment. The first contribution is V-DAENY, a plugin for GTA-V, a famous videogame. V-DAENY allows the creation of scenario with the possibility of customizing most aspects of it: number of people, their equipment and behavior, weather conditions and time of day. With V-DAENY, we automatically generated over 140,000 annotated images in several locations of the game map and with different weather conditions.

GitHub page: https://github.com/enricomeloni/GTA5_Mods