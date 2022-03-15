---
title: "Learning a visuomotor controller for real world robotic grasping using simulated depth images"
authors:
- Ulrich Viereck
- Andreas ten Pas
- Kate Saenko
- Robert Platt
date: "2017-11-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning*
publication_short: In *CoRL 2017*

abstract: We want to build robots that are useful in unstructured real world applications, such as doing work in the household. Grasping in particular is an important skill in this domain, yet it remains a challenge. One of the key hurdles is handling unexpected changes or motion in the objects being grasped and kinematic noise or other errors in the robot. This paper proposes an approach to learning a closed-loop controller for robotic grasping that dynamically guides the gripper to the object. We use a wrist-mounted sensor to acquire depth images in front of the gripper and train a convolutional neural network to learn a distance function to true grasps for grasp configurations over an image. The training sensor data is generated in simulation, a major advantage over previous work that uses real robot experience, which is costly to obtain. Despite being trained in simulation, our approach works well on real noisy sensor images. We compare our controller in simulated and real robot experiments to a strong baseline for grasp pose detection, and find that our approach significantly outperforms the baseline in the presence of kinematic noise, perceptual errors and disturbances of the object during grasping.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Video
  url: https://www.youtube.com/watch?v=WkVM3dRWWN8
url_pdf: https://arxiv.org/pdf/1706.04652.pdf
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

