---
title: "High precision grasp pose detection in dense clutter"
authors:
- Marcus Gualtieri
- Andreas ten Pas
- Kate Saenko
- Robert Platt
date: "2016-10-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2016-10-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/RSJ International Conference on Intelligent Robots and Systems*
publication_short: In *IROS 2016*

abstract: "This paper considers the problem of grasp pose detection in point clouds. We follow a general algorithmic structure that first generates a large set of 6-DOF grasp candidates and then classifies each of them as a good or a bad grasp. Our focus in this paper is on improving the second step by using depth sensor scans from large online
datasets to train a convolutional neural network. We propose two new representations of grasp candidates, and we quantify the effect of using prior knowledge of two forms: instance or category knowledge of the object to be grasped, and pretraining the network on simulated depth data obtained from idealized CAD models. Our analysis shows that a more informative grasp candidate representation as well as pretraining and prior knowledge significantly improve grasp detection. We evaluate our approach on a Baxter Research Robot and demonstrate an average grasp success rate of 93% in dense clutter. This is a 20% improvement compared to our prior work."

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: UR5 Video
  url: https://youtu.be/kfe5bNt35ZI
- name: Baxter Video
  url: https://www.youtube.com/watch?v=p4JXpZVxr48
url_pdf: http://www.ccs.neu.edu/home/atp/publications/grasps_cnn_iros2016.pdf
url_code: https://github.com/atenpas/gpd

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

