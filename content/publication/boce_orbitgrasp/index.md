---
title: "OrbitGrasp: SE(3)-Equivariant Grasp Learning"
authors:
- Boce Hu
- Xupeng Zhu
- Dian Wang
- Zihao Dong
- Haojie Huang
- Chenghao Wang
- Robert Platt
- Robin Walters
date: "2025-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Robot Learning 2024*
publication_short: In *CoRL 2024*

abstract: While grasp detection is an important part of any robotic manipulation pipeline, reliable and accurate grasp detection in SE(3) remains a research challenge. Many robotics applications in unstructured environments such as the home or warehouse would benefit a lot from better grasp performance. This paper proposes a novel framework for detecting SE(3) grasp poses based on point cloud input. Our main contribution is to propose an SE(3)-equivariant model that maps each point in the cloud to a continuous grasp quality function over the 2-sphere S2 using a spherical harmonic basis. Compared with reasoning about a finite set of samples, this formulation improves the accuracy and efficiency of our model when a large number of samples would otherwise be needed. In order to accomplish this, we propose a novel variation on EquiFormerV2 that leverages a UNet-style encoder-decoder architecture to enlarge the number of points the model can handle. Our resulting method, which we name OrbitGrasp, significantly outperforms baselines in both simulation and physical experiments.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://orbitgrasp.github.io/
url_code: https://github.com/BoceHu/orbitgrasp
url_pdf: https://arxiv.org/pdf/2407.03531
url_video: https://www.youtube.com/watch?v=Y3UxZMPc0ms

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<meta http-equiv = "refresh" content = " 0.01 ; url = https://orbitgrasp.github.io/"/>
