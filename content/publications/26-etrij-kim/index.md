---
build:
  render: never
  publishResources: true

outputs: []

title: Operation-level scheduling framework for efficient deep learning inference
  on embedded systems using directed acyclic graphs

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Mooseop Kim
- SuGil Choi
- Sungjun Wang
- Chi Yoon Jeong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-01-30'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-02-02T00:42:40.330932Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*ETRI Journal*'
publication_short: ''

doi: 10.4218/etrij.2025-0201

abstract: 'Abstract This study presents an operation-level scheduling framework for
  efficient deep learning inference on heterogeneous embedded systems. Motivated by
  the observation that deep neural networks comprise diverse operations in which the
  execution latency is highly dependent on the target hardware and input dimensions.
  The framework hypothesizes that accurate latency prediction and fine-grained scheduling
  of individual operations reduce end-to-end inference time. It follows a three-stage
  approach: (i) offline profiling of operation latencies across varying input sizes
  and devices; (ii) training latency prediction models using input-aware features;
  and (iii) directed acyclic graph-based runtime scheduling to assign each operation
  to a central processing unit, graphics processing unit, or both. The framework is
  evaluated on two embedded platforms (Jetson Nano and ODROID-XU4) and demonstrates
  an inference latency reduction of up to 74% across multiple deep learning models.
  These results indicate that the framework is adaptable, lightweight, and effective
  for resource-constrained artificial intelligence deployments.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- central processing unit-graphics processing unit co-execution
- deep learning inference
- embedded system
- heterogeneous computing

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://onlinelibrary.wiley.com/doi/epdf/10.4218/etrij.2025-0201'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'projects/visionaugmentation'
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
  url: https://onlinelibrary.wiley.com/doi/abs/10.4218/etrij.2025-0201
---
