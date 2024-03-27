---
title: 'A Fast Online Omnidirectional Quadrupedal Jumping Framework Via Virtual-Model Control and Minimum Jerk Trajectory Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Linzhu Yue 
  - Lingwei Zhang
  - Zhitao Song
  - Hongbo Zhang
  - Jinghu Dong
  - Xuanqi Zeng
  - Yunhui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2024-03-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IROS 2024*
publication_short: In *IROS*

abstract: Exploring the limits of quadruped robot agility, particularly in the context of rapid and real-time planning and execution of omnidirectional jump trajectories, presents significant challenges due to the complex dynamics involved, especially when considering significant impulse contacts. This paper introduces a new framework to enable fast, omnidirectional jumping capabilities for quadruped robots. Utilizing minimum jerk technology, the proposed framework efficiently generates jump trajectories that exploit its analytical solutions, ensuring numerical stability and dynamic compatibility with minimal computational resources. The virtual model control is employed to formulate a Quadratic Programming (QP) optimization problem to accurately track the Center of Mass (CoM) trajectories during the jump phase. In contrast, whole-body control strategies facilitate precise and compliant landing motion. The framework's efficacy is demonstrated through its implementation on an enhanced version of the open-source Mini Cheetah robot. Omnidirectional jumps—including forward, backward, and other directional—were successfully executed, showcasing the robot's capability to perform rapid and consecutive jumps with an average trajectory generation and tracking solution time of merely 50 microseconds.
# Summary. An optional shortened abstract.
summary: Rapid Jumping framework for quadrupedal

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

#url_pdf: 'https://arxiv.org/abs/2207.12002'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
#url_video: 'https://www.youtube.com/watch?v=AJ37eS8sjS8&t=2s'

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
  - vmc jumping 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
