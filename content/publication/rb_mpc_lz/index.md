---
title: 'Dynamic Locomotion through Robust Model Predictive Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
 - Linzhu Yue
 - Weipeng Xia
 - Bike Zhang
 - Siddharth H. Nair
 - Zhongyu Li
 - Zhitao Song
 - Hongbo Zhang
 - Koushil Sreenath
 - Yun-hui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2024-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: ReSubmit to *IJRR 2025*
publication_short: Under reviewer In *IJRR*

abstract: Achieving robust resistance to bounded external disturbances in high-dimensional, complex dynamic systems remains a significant challenge, particularly for legged robots. While Model Predictive Control (MPC) has been widely studied for disturbance rejection, few approaches provide robust stability guarantees for legged locomotion. This paper presents a computationally efficient Tube-based Robust Model Predictive Control (TRMPC) framework for legged robots under bounded disturbances. Unlike traditional methods that rely on polytopic sets, the proposed TRMPC employs minimal invariant ellipsoids (MIE) to design a feedback controller that compensates for state errors induced by disturbances. Robust stability conditions are derived by formulating the MIE as a one-dimensional convex Semi-Definite Programming (SDP) problem subject to Linear Matrix Inequality (LMI) constraints, solved offline. To avoid the computationally intensive Pontryagin Difference and Minkowski Sum, an approximate approach is introduced, enabling efficient Quadratic Programming (QP) solutions for ground reaction forces (GRFs). The framework uses a reduced-order dynamic model and a variation-based linearization method to construct the MPC formulation. Experimental results on a quadrupedal robot demonstrate the effectiveness of the proposed TRMPC in rejecting various external disturbances, including large impulse forces, continuous forces, and rough terrains. Additionally, simulations on a bipedal robot validate the robustness of the proposed approach under different terrain conditions and external disturbances.
# Summary. An optional shortened abstract.
summary: Robust MPC for biepdal and quadrupedal robot

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
url_video: 'https://youtu.be/ixArWh7FUb8?si=6YYQgnU_kkKTGYsI'

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
