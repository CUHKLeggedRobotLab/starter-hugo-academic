---
title: 'Evolutionary-Based Online Motion Planning Framework for Quadruped Robot Jumping'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Linzhu Yue
  - Zhitao Song
  - Hongbo Zhang
  - Xuanqi Zeng
  - Lingwei Zhang
  - Yunhui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'



date: '2023-07-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IROS 2023*
publication_short: In *IROS*

abstract: Offline evolutionary-based methodologies have supplied a successful motion planning framework for the quadrupedal jump. However, the time-consuming computation caused by massive population evolution in offline evolutionary-based jumping framework significantly limits the popularity in the quadrupedal field. This paper presents a time-friendly online motion planning framework based on meta-heuristic Differential evolution (DE), Latin hypercube sampling, and  Configuration space (DLC). The DLC framework establishes a multidimensional optimization problem leveraging centroidal dynamics to determine the ideal trajectory of the center of mass (CoM) and ground reaction forces (GRFs). The configuration space is introduced to the evolutionary optimization in order to condense the searching region. Latin hypercube sampling offers more uniform initial populations of DE under limited sampling points, accelerating away from a local minimum. This research also constructs a collection of pre-motion trajectories as a warm start when the objective state is in the neighborhood of the pre-motion state to drastically reduce the solving time. The proposed methodology is successfully validated via real robot experiments for online jumping trajectory optimization with different jumping motions (e.g., ordinary jumping, flipping, and spinning).
# Summary. An optional shortened abstract.
summary: Evolutionary-Based Online Motion Planning jumping framework

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
url_video: ''

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
  - online_quadruped_jumping

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
