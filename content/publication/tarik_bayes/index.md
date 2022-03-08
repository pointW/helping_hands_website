---
title: "Learning bayes filter models for tactile localization"
authors:
- Tarik Kelestemur
- Colin Keil
- John P Whitney
- Robert Platt
- Taskin Padir
date: "2020-12-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*
publication_short: In *IROS 2020*

abstract: Localizing and tracking the pose of robotic grippers are necessary skills for manipulation tasks. However, the manipulators with imprecise kinematic models (e.g. low-cost arms) or manipulators with unknown world coordinates (e.g. poor camera-arm calibration) cannot locate the gripper with respect to the world. In these circumstances, we can leverage tactile feedback between the gripper and the environment. In this paper, we present learnable Bayes filter models that can localize robotic grippers using tactile feedback. We propose a novel observation model that conditions the tactile feedback on visual maps of the environment along with a motion model to recursively estimate the gripper's location. Our models are trained in simulation with self-supervision and transferred to the real world. Our method is evaluated on a tabletop localization task in which the gripper interacts with objects. We report results in simulation and on a real robot, generalizing over different sizes, shapes, and configurations of the objects.
# Summary. An optional shortened abstract.
summary: 

tags:
- tactile manipulation
featured: true

links:
url_pdf: https://ieeexplore.ieee.org/abstract/document/9341420
# url_code: https://github.com/pointW/asrse3_corl20
# url_project: https://pointw.github.io/asrse3-page
# url_video: https://www.youtube.com/watch?v=FiHoIF1oLZs

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