---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Face Recognition App"
summary: "A face recognition app for android powered by Machine Learning"
authors: [Enrico Meloni, Raffaele Zippo]
tags: [machine learning, android, app, java, face recognition]
categories: [Machine Learning]
date: 2020-06-24T15:47:45+02:00

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

This Android app performs face recognition and identification through the smartphone's camera. The app uses an internal database containing the known identities, including sample photos. The app allows the user to check the database content, delete or add new identities.

Face Detection is powered by Haar Cascade Classifier. Face Feature are extracted by VGG2 trained on VGGFace2.

Classification is performed by weighted kNN on the extracted face features.

Data processing is powered by OpenCV for Java.

GitHub page: https://github.com/MeloniZippoProjects/MultimediaProject