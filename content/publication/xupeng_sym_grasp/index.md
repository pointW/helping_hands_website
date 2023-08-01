---
title: "On robot grasp learning using equivariant models"
authors:
- Xupeng Zhu
- Dian Wang
- Guanang Su
- Ondrej Biza
- Robin Walters
- Robert Platt
date: "2023-07-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Autonomous Robots*
publication_short: In *Autonomous Robots*

abstract: Real-world grasp detection is challenging due to the stochasticity in grasp dynamics and the noise in hardware. Ideally, the system would adapt to the real world by training directly on physical systems. However, this is generally difficult due to the large amount of training data required by most grasp learning models. In this paper, we note that the planar grasp function is SE(2)-equivariant and demonstrate that this structure can be used to constrain the neural network used during learning. This creates an inductive bias that can significantly improve the sample efficiency of grasp learning and enable end-to-end training from scratch on a physical robot with as few as 600 grasp attempts. We call this method Symmetric Grasp learning (SymGrasp) and show that it can learn to grasp “from scratch” in less that 1.5 h of physical robot time. This paper represents an expanded and revised version of the conference paper Zhu et al. (2022).
# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://zxp-s-works.github.io/equivariant_grasp_site/
url_pdf: https://link.springer.com/article/10.1007/s10514-023-10112-w
url_code: https://github.com/ZXP-S-works/SE2-equivariant-grasp-learning

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

<meta http-equiv = "refresh" content = " 0 ; url = https://link.springer.com/article/10.1007/s10514-023-10112-w"/>

