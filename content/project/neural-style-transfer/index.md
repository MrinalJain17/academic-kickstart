---
title: Neural Style Transfer
summary: Implemented neural style transfer with numerous extensions
tags:
- Deep Learning
- Computer Vision
date: "2020-12-15T00:00:00Z"
weight: 15

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
url_code: "https://github.com/MrinalJain17/neural-style-transfer"
url_pdf: "https://github.com/MrinalJain17/neural-style-transfer/blob/main/report/Report.pdf"
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

- Reimplemented the seminal work by Gatys et al. titled "A Neural Algorithm of Artistic Style" (using PyTorch).
- Programmed numerous extensions to [preserve color](https://arxiv.org/abs/1606.05897) and improve the [algorithm’s quality](https://arxiv.org/abs/1605.04603) (primarily based on the gram matrix characteristics).
- Implemented the fast style transfer method proposed by Johnson et al. working in real-time (~ seconds) compared to the original optimization-based algorithm (~ minutes).
