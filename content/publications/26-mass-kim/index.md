---
build:
  render: never
  publishResources: true

outputs: []

title: 'Revisiting Pruning for Edge AI: Latency, Scalability, and OTA Update Costs'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Mooseop Kim
- Chi Yoon Jeong
- SuGil Choi

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-10-21'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-10-30T00:00:00Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*2026 IEEE 23rd International Conference on Mobile Ad-Hoc and Smart Systems (MASS)*'
publication_short: 'IEEE MASS 2026'

abstract: 'Model pruning is widely used to reduce the parameter count and FLOPs of
  deep neural networks, but its system-level effects in edge AI remain unclear. In
  multi-node edge deployments, overall performance is often dominated by communication
  and tail latency rather than mean computation time. This paper revisits structured
  pruning from a system-level perspective through measurement-driven experiments on
  four commodity embedded platforms and trace-driven multi-node analysis using four
  convolutional neural network architectures. Rather than proposing another pruning
  algorithm, this paper asks whether pruning changes the bottlenecks that govern
  deployed edge AI systems, including tail latency, scalability limits, and fleet-wide
  model-update traffic. Our results show that, despite substantial reductions in
  FLOPs and parameter counts, inference-latency improvements remain limited to 5-7%
  on the evaluated commodity embedded platforms, indicating that the algorithmic
  reductions are only weakly reflected in end-to-end runtime. These modest single-node
  gains do not meaningfully reduce tail latency or improve scalability in multi-node
  settings. In contrast, pruning reduces over-the-air (OTA) update traffic almost
  linearly with the pruning ratio, achieving 50-62% transmission savings at high
  pruning levels, independent of sparse-runtime support. These findings suggest that,
  on the evaluated platforms and software stack, pruning is more reliable as a
  communication-oriented optimization than as a latency optimization.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- edge AI
- model pruning
- inference latency
- scalability
- over-the-air updates

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1109/MASS71041.2026.00048'
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
#   E.g. `projects: 'internal-project'` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
hugoblox:
  ids:
    doi: 10.1109/MASS71041.2026.00048
---
