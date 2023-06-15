---
abstract: Rapid and automated mapping of flood inundation in near real-time conditions is crucial for  effective mitigation  of flood-related risks. While optical satellites offer valuable insights into flood extent and impact, they face limitations such as cloud obstruction, low vegetation penetration, and daytime acquisition constraints, making real-time flood mapping challenging.Synthetic Aperture Radar (SAR) satellites,however, can overcome these limitations and enable flood mapping at high spatial resolutions. In this study, we present a state-of-the-art automated flood segmentation framework based on ensemble deep learning and data fusion techniques. The framework leverages an ensemble of deep learning models trained on large-scale open-source flood data, augmented with terrain and permanent water information. To improve the ensemble generation, we introduce a novel gain algorithm based on the diversity of model outputs. Additionally, we provide uncertainties through pixel-wise probability estimates from the ensemble models. The evaluation on test data yielded an Intersection Over Union (IOU) value of 0.755 and an accuracy of 95%, demonstrating the framework’s generalizability and transferability. Notably, our proposed ensemble framework not only detects flooded regions similar to Sentinel-2 imagery, but also identifies flooded areas covered with light clouds which are missed by Sentinel-2 data. Furthermore, to aid its usage in real-time flood inundation mapping, we have implemented the model in an open source, fully automated, and parallelized python-based tool called DeepSARFlood. This tool is expected to complement upcoming SAR satellite missions such as NISAR and Sentinel 1-C for flood mapping.
author_notes:

authors:
- admin
- Manabendra Saharia
- Hetal P.
date: "2022-09-01T00:00:00Z"
doi: ""
featured: true
image:
  focal_point: ""
  preview_only: false
projects: []
publication: ' '
publication_short: ""
publication_types:
- "2"
publishDate: "2017-01-01T00:00:00Z"
slides: 
summary: Under Review at ISPRS Journal of Photogrammetry and remote sensing
tags:
- Source Themes
title: DeepSARFlood-Operational SAR-based Flood Mapping using Ensemble Deep Learning and a Novel Ensemble Model Selection Algorithm
url_code: https://github.com/der-knight/Deep-Learning-floods
url_dataset: ""
url_pdf: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
