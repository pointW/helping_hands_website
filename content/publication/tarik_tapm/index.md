---
title: "Tactile Pose Estimation and Policy Learning for Unknown Object Manipulation"
authors:
- Tarik Kelestemur
- Robert Platt
- Taskin Padir
date: "2022-01-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Autonomous Agents and Multiagent Systems*
publication_short: In *AAMAS 2022*

abstract: Object pose estimation methods allow finding locations of objects in unstructured environments. This is a highly desired skill for au- tonomous robot manipulation as robots need to estimate the precise poses of the objects in order to manipulate them. In this paper, we investigate the problems of tactile pose estimation and manipula- tion for category-level objects. Our proposed method uses a Bayes filter with a learned tactile observation model and a deterministic motion model. Later, we train policies using deep reinforcement learning where the agents use the belief estimation from the Bayes filter. Our models are trained in simulation and transferred to the real world. We analyze the reliability and the performance of our framework through a series of simulated and real-world experi- ments and compare our method to the baseline work. Our results show that the learned tactile observation model can localize the pose of novel objects at 2-mm and 1-degree resolution for position and orientation, respectively. Furthermore, we experiment on a bottle opening task where the gripper needs to reach the desired grasp state

# Summary. An optional shortened abstract.
summary: 

tags:
- tactile manipulation
- reinforcement learning
featured: true

links:
- name: Website
  url: https://sites.google.com/view/tpem/
url_pdf: #
# url_code: https://github.com/pointW/asrse3_corl20
# url_project: https://pointw.github.io/asrse3-page
# url_video: https://sites.google.com/view/tpem/

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
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---


<!-- Markdown & HTML begins here  -->

<!-- <meta http-equiv = "refresh" content = " 0.01 ; url = https://pointw.github.io/asrse3-page/"/> -->