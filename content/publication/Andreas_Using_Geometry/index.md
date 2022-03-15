---
title: "Using Geometry to Detect Grasp Poses in 3D Point Clouds."
authors:
- Andreas ten Pas
- Robert Platt
date: "2015-09-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2015-09-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Robotics Research*
publication_short: In *ISRR 2015*

abstract: This paper proposes a new approach to using machine learning to detect grasp poses on novel objects presented in clutter. The input to our algorithm is a point cloud and the geometric parameters of the robot hand. The output is a set of hand poses that are expected to be good grasps. There are two main contributions. First, we identify a set of necessary conditions on the geometry of a grasp that can be used to generate a set of grasp hypotheses. This helps focus grasp detection away from regions where no grasp can exist. Second, we show how geometric grasp conditions can be used to generate labeled datasets for the purpose of training the machine learning algorithm. This enables us to generate large amounts of training data and it grounds our training labels in grasp mechanics. Overall, our method achieves an average grasp success rate of 88% when grasping novels objects presented in isolation and an average success rate of 73% when grasping novel objects presented in dense clutter. This system is available as a ROS package at http://wiki.ros.org/agile_grasp.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Video
  url: https://www.youtube.com/watch?v=Dm64UC3uGVY
- name: ROS
  url: http://wiki.ros.org/agile_grasp
url_pdf: http://www.ccs.neu.edu/home/atp/publications/grasp_poses_isrr2015.pdf
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

