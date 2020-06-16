---
title: "Outlier-Robust Manifold Pre-Integration for INS/GPS Fusion"
authors:
- admin
- Alireza Khosravian
- Anh-Dzung Doan
- Tat-Jun Chin

date: "2019-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems* 2019
publication_short: In *IROS*

abstract: "We tackle the INS/GPS sensor fusion problem for pose estimation, particularly in the common setting where the INS components (IMU and magnetometer) function at much higher frequencies than GPS, and where the magnetometer and GPS are prone to giving erroneous measurements (outliers) due to magnetic disturbances and glitches. Our main contribution is a novel non-linear optimization framework that (1) fuses pre-integrated IMU and magnetometer measurements with GPS, in a manner that respects the manifold structure of the state space; and (2) supports the usage of robust norms and efficient large scale optimization to effectively mitigate the effects of outliers. Through extensive experiments, we demonstrate the superior accuracy and robustness of our approach over filtering methods (which are customarily applied in the target setting) with minimal impact to computational efficiency. Our work further illustrates the strength of optimization approaches in state estimation problems and paves the way for their adoption in the control and navigation communities."

# Summary. An optional shortened abstract.
summary: We propose an efficient outlier-robust algorithm to tackle INS and GPS sensor fusion problem for pose estimation.

tags:
- Source Themes
featured: false

links:
url_pdf: https://ieeexplore.ieee.org/document/8967643
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---



