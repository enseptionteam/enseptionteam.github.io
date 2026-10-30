---
build:
  render: never
  publishResources: true

outputs: []

title: 'A Lightweight Multimodal Network with Modality-Consistent Temporal Encoding for Real-Time Driver Cognitive Load Classification on Embedded Devices'

authors:
- Hyeju Lee
- SuGil Choi
- Mooseop Kim
- Chi Yoon Jeong

author_notes: []

date: '2026-10-26'

publishDate: '2026-10-30T00:00:00Z'

publication_types:
- article-journal

publication: '*IEEE Access*'
publication_short: ''

doi: 10.1109/ACCESS.2026.3746997

abstract: >-
  Real-time classification of driver cognitive load is essential for driving
  safety, as cognitive load can impair attention, delay responses, and compromise
  decision-making during driving. Physiological signals can be used to estimate
  cognitive load, and their multimodal integration can improve robustness by
  exploiting complementary information across modalities. However, existing
  fusion models often rely on modality-specific encoder designs and hand-tuned
  hyperparameters, increasing architectural complexity and reducing efficiency
  in embedded environments. To address these limitations, this study presents a
  lightweight multimodal network with modality-consistent temporal encoding for
  real-time driver cognitive load classification on resource-constrained
  embedded devices. The proposed model employs a temporal convolutional network
  (TCN) to reduce complexity while effectively capturing temporal and multiscale
  features from heterogeneous physiological modalities. Adaptive average pooling
  and a lightweight attention module align and fuse the modality features,
  followed by a compact TCN and fully connected layers for the final
  classification. Experiments on the CL-Drive dataset demonstrated that a
  TCN-based feature extractor with a fixed kernel size can effectively capture
  the temporal characteristics of each modality without parameter tuning or
  network redesign. The proposed model achieved 86.22% accuracy in binary
  classification under 10-fold cross-validation, a 7.6% relative improvement
  over UniPhyNet, the state-of-the-art method, while minimizing parameters and
  floating-point operations by over 90%. On a Jetson Orin Nano (TensorRT FP32),
  it achieves a 2.3 ms inference latency, which is approximately 3.4x faster
  than the SOTA method, demonstrating suitability for real-time driver-state
  monitoring on resource-constrained systems.

summary: ''

tags:
- cognitive load
- physiological signals
- multimodal
- embedded devices

featured: false

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/document/11753539'
url_video: ''

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
---
