---
title: 'Traversability-Aware Legged Navigation by Learning from Real-World Visual Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hongbo Zhang
  - Zhongyu Li
  - Xuanqi Zeng
  - Laura Smith
  - Kyle Stachowicz
  - Dhruv Shah
  - Linzhu Yue
  - Zhitao Song
  - Weipeng Xia
  - Sergey Levine
  - Koushil Sreenath
  - Yun-hui Liu

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'


date: '2024-10-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Submit to *TRO 2024*
publication_short: In *TRO*

abstract: The enhanced mobility brought by legged locomotion empowers quadrupedal robots to navigate through complex and unstructured environments. However, optimizing agile locomotion while accounting for the varying energy costs of traversing different terrains remains an open challenge. Most previous work focuses on planning trajectories with traversability cost estimation based on human-labeled environmental features. However, this human-centric approach is insufficient because it does not account for the varying capabilities of the robot locomotion controllers over challenging terrains. To address this, we develop a novel traversability estimator in a robot-centric manner, based on the value function of the robot’s locomotion controller. This estimator is integrated into a new learningbased RGBD navigation framework. The framework employs multiple training stages to develop a planner that guides the robot in avoiding obstacles and hard-to-traverse terrains while reaching its goals. The training of the navigation planner is directly performed in the real world using a sample efficient reinforcement learning method that utilizes both online data and offline datasets. Through extensive benchmarking, we demonstrate that the proposed framework achieves the best performance in accurate traversability cost estimation and efficient learning from multi-modal data (including the robot’s color and depth vision, as well as proprioceptive feedback) for realworld training. Using the proposed method, a quadrupedal robot learns to perform traversability-aware navigation through trial and error in various real-world environments with challenging terrains that are difficult to classify using depth vision alone. Moreover, the robot demonstrates the ability to generalize the learned navigation skills to unseen scenarios. Video can be found at https://youtu.be/RSqnIWZ1qks.
# Summary. An optional shortened abstract.
summary: Traversability-Aware Legged Navigation by Learning

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.10621'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/RSqnIWZ1qks?si=ALn_A9Yv6NGQlgbd'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**LRL**](https://cuhkleggedrobotlab.github.io/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
research:
  - Reinforcement Learning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
