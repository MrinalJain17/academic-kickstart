---
title: Head and Neck CT image segmentation using deep learning
summary: Segmenting organs in Head and Neck CT scans
tags:
- Deep Learning
- Computer Vision
date: "2020-12-15T00:00:00Z"
weight: 5

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
url_code: "https://github.com/MrinalJain17/CT-image-segmentation"
url_pdf: "https://github.com/MrinalJain17/CT-image-segmentation/blob/master/reports/Report.pdf"
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

- Designed an end-to-end framework for segmenting organs in the head and neck CT images, achieving near-SOTA performance on the MICCAI Auto-segmentation Challenge (72.16 vs. 75.28 dice score).
- Enhanced the baseline U-Net architecture by adding residual connections and a mixup training regime to prevent overfitting on the relatively small dataset (only ~30 CT scans).
- Used Grad-CAM to interpret and understand the model predictions better.
