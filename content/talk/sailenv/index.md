---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SAILenv: Learning in Virtual VisualEnvironments Made Simple"
event: SAILab Lab Meeting
event_url:
location: Siena
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Recently, researchers in Machine Learning algorithms, Computer Vision scientists, engineers, and others, showed a growing interest in 3D simulators as a mean to artificially create experimental settings that are remarkably close to those in the real world. However, most of the existing platforms to interface algorithms with 3D environments are often designed to setup navigation-related experiments, to study physical interactions, or to handle ad-hoc cases that are not thought to be customized, sometimes lacking a strong photorealistic appearance and an easy-to-use software interface. In this talk, we will present a platform developed in our lab, SAILenv, that is specifically designed to be simple and customizable, and that allows researchers to experiment visual recognition in virtual 3D scenes. A few lines of code are needed to interface every algorithm with the virtual world, and non-3D-graphics experts can easily customize the 3D environment itself, exploiting a collection of photorealistic objects. Our framework yields pixel-level semantic and instance labeling, depth, and, to the best of our knowledge, it is the only one that provides motion-related information directly inherited from the 3D engine. The client-server communication operates at a low level, avoiding the overhead of HTTP-based data exchanges. We perform experiments using a state-of-the-art object detector trained on real-world images, showing that it is able to recognize the photorealistic 3D objects of our environment. The computational burden of the optical flow compares favorably with the estimation performed using modern GPU-based convolutional networks or more classic implementations."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-09-16T11:00:00+02:00
date_end: 2020-09-16T12:00:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-09-11T19:37:17+02:00

authors: [Enrico Meloni]
tags: [computer vision, virtual environments, visual agents, unity3D]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Sample scene available in SAILenv"
  focal_point: "smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
