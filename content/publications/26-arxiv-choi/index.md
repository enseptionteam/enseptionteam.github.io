---
build:
  render: never
  publishResources: true

outputs: []

title: 'CABrain: A Correlation-Aware Brain Foundation Model for EEG Decoding'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it is replaced with their full name and linked to their profile.
authors:
- SuGil Choi
- Mooseop Kim
- Chi Yoon Jeong

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes:
- 'Equal contribution'
- 'Equal contribution'
- ''

date: '2026-11-09'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-16T00:00:00Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- manuscript

# Publication name and optional abbreviated publication name.
publication: '*arXiv preprint arXiv:2611.11782*'
publication_short: 'arXiv 2026'

abstract: >-
  Electroencephalography (EEG) foundation models have emerged as promising
  paradigms for decoding brain activity through large-scale self-supervised
  pretraining. Notably, most existing approaches employ masked patch
  reconstruction, in which randomly selected EEG patches are masked and
  recovered by the network. However, purely random masking may limit
  representation learning as informative patches from highly correlated
  channels often remain unmasked, causing the network to underutilize weakly
  correlated channels or serial dependencies. Furthermore, because these
  models are typically based on transformer architectures, their performance
  is influenced by the choice of positional encoding. Although positional
  encoding has been extensively explored in natural language processing and
  computer vision, few studies have adapted it to the unique characteristics
  of EEG signals. To address these limitations, this study introduces a
  conditional positional encoding method based on graph convolutional networks
  (GCNs) to explicitly model inter-channel correlations, along with an
  adaptive masking strategy that enhances representation learning by
  modulating the difficulty of masked patch reconstruction. To the best of our
  knowledge, this is the first study to integrate graph-based representations
  into conditional positional encoding and introduce adaptive masking within
  EEG foundation model pretraining. Experimental results on ten benchmark
  datasets demonstrate that the proposed GCN-based positional encoding and
  adaptive masking strategies, both individually and in combination, achieve
  state-of-the-art or competitive performance, highlighting their effectiveness
  in EEG foundation modeling.

# Summary. An optional shortened abstract.
summary: ''

tags:
- EEG
- brain foundation model
- self-supervised learning
- positional encoding
- adaptive masking

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2611.11782'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://arxiv.org/abs/2611.11782'
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
projects: []
---
