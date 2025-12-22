---
title: Enhancing Multiscale Feature Representation For Object-Level Recognition In
  Masked Image Modeling

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Tsatsral Amarbayasgalan
- Sungjun Wang
- Mooseop Kim
- Chi Yoon Jeong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-09-14'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-12-22T05:18:01.662325Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2025 IEEE International Conference on Image Processing (ICIP)*'
publication_short: ''

doi: 10.1109/ICIP55913.2025.11084319

abstract: Masked image modeling (MIM), which is a self-supervised learning method
  in computer vision, excels in image-and video-level recognition tasks by providing
  robust and generalized feature representations. However, most MIM methods incorporate
  plain Vision Transformers (ViTs), which lack the capability to produce multiscale
  features, thereby limiting their effectiveness in more complex object-level recognition
  tasks. Extracting multiscale hierarchical features using a convolutional stem and
  fully fusing local and global information within all feature representations are
  crucial for applying the MIM framework to object-level recognition. To address this
  issue, we propose an effective multiscale feature extraction mechanism that integrates
  local and global dependencies from the convolutional stem and ViT within the MIM
  framework. Our method was evaluated on object detection and instance segmentation
  tasks using the MS COCO dataset. It exhibits superior performance by effectively
  fusing local and global information across all feature scales, achieving comparable
  results to those of state-of-the-art methods while using 25% fewer training samples.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Training;Computer vision;Image recognition;Limiting;Autoencoders;Object detection;Self-supervised
  learning;Predictive models;Feature extraction;Transformers;Masked image modeling;Masked
  autoencoder;Vision Transformer;Dense prediction

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
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
