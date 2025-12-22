---
title: An Improved YOLOF for Scale Imbalance with Dilated Attention

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Tsatsral Amarbayasgalan
- Mooseop Kim
- Chi Yoon Jeong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-12-03'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-11-19T06:41:11.029177Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Pattern Recognition*'
publication_short: ''


abstract: Scale imbalance, where objects of different sizes are not equally represented
  in a dataset, is a common problem in real-world object detection scenarios that
  leads to significant performance degradation of object detection methods. Although
  several solutions have been proposed based on multilevel feature maps, these methods
  may not be suitable in real-time applications owing to their low speed and memory
  consumption. Recently, you only look one-level feature (YOLOF) was proposed based
  on a single-in-single-out (SiSo) architecture; the SiSo architecture is well suited
  for real-time applications with performance comparable to that of methods based on
  multilevel feature maps. However, they show limited performance when applied to
  real-world object detection scenarios with scale imbalance problems. Therefore,
  we propose a lightweight object detection method that can handle the scale imbalance
  problem while retaining the advantages of the SiSo framework. To mitigate the scale
  imbalance, we use dilated attention to extend the SiSo architecture and learn the
  scale range of objects. Extensive experiments on public datasets show the effectiveness
  of a dilated attention-based proposed method in scale-imbalanced scenarios. Our
  method achieves results comparable to those of the original YOLOF on the MS COCO
  and PASCAL VOC datasets. In particular, for imbalanced datasets, the proposed method
  outperforms the original YOLOF by 4.78% on the first-person-walking-livingroom dataset
  and by 1.38% on the imbalanced PASCAL VOC dataset in terms of average precision
  (AP)50.

# Summary. An optional shortened abstract.
summary: ''

tags: []

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
hugoblox:
  ids:
    doi: https://doi.org/10.1007/978-3-031-78447-7_11
---

<!-- Add the **full text** or **supplementary notes** for the publication here using Markdown formatting. -->
