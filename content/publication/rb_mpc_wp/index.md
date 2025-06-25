---
title: 'Robust Model Predictive Control for Quadruped Locomotion Under Model Uncertainties and External Disturbances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
 - Weipeng Xia
 - Linzhu Yue
 - Yun-hui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2025-06-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Accept to *IROS 2025*
publication_short: Accept to *IROS 2025*

abstract: Model Predictive Control (MPC) enables agile and robust locomotion in quadruped robots but is sensitive to model uncertainties and environmental variations. This paper presents a Tube-based Robust MPC (TR-MPC) framework for quadruped locomotion under uncertainties, modeled as parameter mismatches and additive disturbances. TR-MPC constructs an Invariant Ellipsoid to bound errors induced by uncertainties, ensuring convergent error trajectories. A Semi-Definite Programming (SDP) problem with Linear Matrix Inequality (LMI) constraints is solved offline to minimize the ellipsoid size, while a linear feedback term stabilizes error dynamics, guaranteeing stability within uncertainty bounds. Simulations and experiments demonstrate TR-MPC’s robustness, the robot achieves stable trotting under a 14 kg load (123\% of its weight) and recovers from a 1.4 m/s impact while carrying 10 kg (88\% of its weight). This framework significantly enhances robustness in dynamic and uncertain environments.
# Summary. An optional shortened abstract.
summary: Robust MPC for quadrupedal robot

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/4c--po4hs0k?si=l3vW7YFxwgKvBfwG'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Linzhu**](https://www.zhihu.com/people/yuexiaozhu)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
research:
  - Dynamic Locomotion 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
