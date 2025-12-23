---
title: Efficient pitch-estimation network for edge devices

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Chi Yoon Jeong
- Youngmi Song
- Sungyong Shin
- Mooseop Kim

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-12-23T07:18:47.547641Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*ETRI Journal*'
publication_short: ''

doi: https://doi.org/10.4218/etrij.2023-0430

abstract: Abstract Pitch estimation is the task of finding the most conspicuous frequency
  in a complex audio signal. Many methods that use deep neural networks have significantly
  increased the accuracy of pitch estimation; however, their real-time performance
  results were achieved on high-performance devices. Because pitch estimation is widely
  used in real-time applications on low-power devices, we propose an efficient method
  for estimating pitch on edge devices. The network architecture of the proposed method
  uses a depth-scaling strategy and fully leverages convolutional networks. We further
  introduce a channel attention mechanism to increase accuracy without increasing
  computational overhead. We compared the proposed model with state-of-the-art (SOTA)
  and conventional methods using two public datasets. The experimental results show
  that the proposed method has a better classification accuracy than FCNF0++, which
  is the best performing SOTA model. Furthermore, it reduces the processing time obtained
  by FCNF0++ on a personal computer and two edge devices by 48% on average. These
  experimental results confirm that the proposed method efficiently classifies pitch
  on edge devices.

# Summary. An optional shortened abstract.
summary: ''

tags:
- channel attention
- edge device
- fully convolutional network
- fundamental frequency estimation
- pitch estimation

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.4218/etrij.2023-0430
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
