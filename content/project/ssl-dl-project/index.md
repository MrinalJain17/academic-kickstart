---
title: Generating bird’s-eye view from multi-image scene using self-supervised learning
summary: Self-supervised learning in traffic environment 
tags:
- Deep Learning
- Computer Vision
- Self-supervised Learning
date: "2020-05-15T00:00:00Z"
weight: 10

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/MrinalJain17/ssl-project"
url_pdf: "https://github.com/MrinalJain17/ssl-project/blob/master/docs/Project%20Report.pdf"
url_dataset: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

- Utilized a pre-trained denoising auto-encoder as a feature extractor for the task of road map construction.
- Combined the feature embeddings of the multi-view scene captured from moving vehicles and used a U-Net to generate a top-down view of the binary road map.
- Achieved a threat score of 0.70 on the hold-out test set (with the best score in the intra-class competition being ~0.81).
