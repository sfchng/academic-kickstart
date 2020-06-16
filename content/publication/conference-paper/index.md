---
title: "Resolving Marker Pose Ambiguity by Robust Rotation Averaging with Clique Constraints"
authors:
- admin
- Naoya Sogi
- Pulak Purkait
- Tat-Jun Chin
- Kazuhiro Fukui
date: "September 2019"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICRA 2020*
publication_short: In ICRA 2020

abstract: "Planar markers are useful in robotics and computer vision for mapping and localisation. Given a detected marker in an image, a frequent task is to estimate the 6DOF pose of the marker relative to the camera, which is an instance of planar pose estimation (PPE). Although there are mature techniques, PPE suffers from a fundamental ambiguity problem, in that there can be more than one plausible pose solutions for a PPE instance. Especially when localisation of the marker corners is noisy, it is often difficult to disambiguate the pose solutions based on reprojection error alone. Previous methods choose between the possible solutions using a heuristic criterion, or simply ignore ambiguous markers. 
We propose to resolve the ambiguities by examining the consistencies of a set of markers across multiple views. Our specific contributions include a novel rotation averaging formulation that incorporates long-range dependencies between possible marker orientation solutions that arise from PPE ambiguities. We analyse the combinatorial complexity of the problem, and develop a novel lifted algorithm to effectively resolve marker pose ambiguities, without discarding any marker observations. Results on real and synthetic data show that our method is able to handle highly ambiguous inputs, and provides more accurate and/or complete marker-based mapping and localisation."

# Summary. An optional shortened abstract.
summary: We propose an efficient algorithm to resolve marker pose ambiguities using rotation averaging.

tags:
- Source Themes
featured: true

links:
url_pdf: https://arxiv.org/abs/1909.11888
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=LtwavEeCkQ4&t=14s'

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



