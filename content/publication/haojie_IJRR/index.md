---
title: "Leveraging Pick and Place Symmetries"
authors:
- Haojie Huang
- Dian Wang
- Arshi Tangri
- Robin Walters
- Robert Platt
date: "2023-12-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Robotics Research 2023*
publication_short: In *IJRR 2023*

abstract: Robotic pick and place tasks are symmetric under translations and rotations of both the object to be picked and the desired place pose. For example, if the pick object is rotated or translated, then the optimal pick action should also rotate or translate. The same is true for the place pose; if the desired place pose changes, then the place action should also transform accordingly. A recently proposed pick and place framework known as Transporter Net captures some of these symmetries, but not all. This paper analytically studies the symmetries present in planar robotic pick and place and proposes a method of incorporating equivariant neural models into Transporter Net in a way that captures all symmetries. The new model, which we call Equivariant Transporter Net, is equivariant to both pick and place symmetries and can immediately generalize pick and place knowledge to different pick and place poses. We evaluate the new model empirically and show that it is much more sample efficient than the non-symmetric version, resulting in a system that can imitate demonstrated pick and place behavior using very few human demonstrations on a variety of imitation learning tasks.
# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
url_pdf: https://arxiv.org/abs/2308.07948
url_code: https://github.com/HaojHuang/Equivariant-Transporter-Net

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

<meta http-equiv = "refresh" content = " 0.01 ; url = https://haojhuang.github.io/etp_page"/>

