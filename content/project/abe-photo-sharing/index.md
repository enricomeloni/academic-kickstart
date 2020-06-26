---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ABE Photo Sharing"
summary: "Secure Photo Sharing Service powered by KPABE"
authors: [Enrico Meloni, Raffaele Zippo]
tags: [security, kpabe, encryption, c#, windows]
categories: [Software Development]
date: 2020-06-24T15:46:48+02:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "KP-ABE Schema (*)"
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

links:
  - icon_pack: fab
    icon: github
    name: GitHub
    url: "https://github.com/MeloniZippoProjects/ABEPhotoSharing"

---

The application is a secure photo sharing service which uses KPABE encryption to enforce access to pictures exclusively to allowed users. The application is written in C# for the Windows platform and depends on a KPABE command line implementation

(*): The featured image is extracted from [A Work in Progress: Context based Encryption Scheme for Internet of Things](https://www.researchgate.net/publication/282500797_A_Work_in_Progress_Context_based_Encryption_Scheme_for_Internet_of_Things)
