---
title: 'Online Omnidirectional Jumping Trajectory Planning for Quadrupedal Robots on Uneven Terrains'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Linzhu Yue 
  - Zhitao Song
  - Jinghu Dong
  - Zhongyu Li
  - Hongbo Zhang
  - Lingwei Zhang
  - Xuanqi Zeng
  - Koushil Sreenath
  - Yunhui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2024-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Submit to *IJRR 2024*
publication_short: In *IJRR*

abstract: Natural terrain complexity often necessitates agile movements like jumping in animals to improve traversal efficiency. To enable similar capabilities in quadruped robots, complex real-time jumping maneuvers are required. Current research does not adequately address the problem of online omnidirectional jumping and neglects the robot's kinodynamic constraints during trajectory generation. This paper proposes a general and complete cascade online optimization framework for omnidirectional jumping for quadruped robots. Our solution systematically encompasses jumping trajectory generation, a trajectory tracking controller, and a landing controller. It also incorporates environmental perception to navigate obstacles that standard locomotion cannot bypass, such as jumping from high platforms. We introduce a novel jumping plane to parameterize omnidirectional jumping motion and formulate a tightly coupled optimization problem accounting for the kinodynamic constraints, simultaneously optimizing CoM trajectory, Ground Reaction Forces (GRFs), and joint states. To meet the online requirements, we propose an accelerated evolutionary algorithm as the trajectory optimizer to address the complexity of kinodynamic constraints. To ensure stability and accuracy in environmental perception post-landing, we introduce a coarse-to-fine relocalization method that combines global Branch and Bound (BnB) search with Maximum a Posteriori (MAP) estimation for precise positioning during navigation and jumping. The proposed framework achieves jump trajectory generation in approximately 0.1 seconds with a warm start and has been successfully validated on two quadruped robots on uneven terrains. Additionally, we extend the framework's versatility to humanoid robots.
# Summary. An optional shortened abstract.
summary: Online Omnidirectional Jumping Trajectory Planning 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2411.04494'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=fDye1gVxoMQ&feature=youtu.be'

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
  - omnidirectional jumping 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
