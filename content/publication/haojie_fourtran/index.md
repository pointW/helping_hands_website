---
title: "Fourier Transporter: Bi-Equivariant Robotic Manipulation in 3D"
authors:
- Haojie Huang
- Owen Howell
- Dian Wang
- Xupeng Zhu
- Robert Platt
- Robin Walters
date: "2024-03-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ICLR 2023*
publication_short: In *ICLR 2023*

abstract: Many complex robotic manipulation tasks can be decomposed as a sequence of pick and place actions. Training a robotic agent to learn this sequence over many different starting conditions typically requires many iterations or demonstrations, especially in 3D environments. In this work, we propose Fourier Transporter (FourTran), which leverages the two-fold SE(d)xSE(d)  symmetry in the pick-place problem to achieve much higher sample efficiency. FourTran is an open-loop behavior cloning method trained using expert demonstrations to predict pick-place actions on new configurations. FourTran is constrained by the symmetries of the pick and place actions independently. Our method utilizes a fiber space Fourier transformation that allows for memory-efficient computation. Tests on the RLbench benchmark achieve state-of-the-art results across various tasks..

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://haojhuang.github.io/fourtran_page/
url_code: https://haojhuang.github.io/fourtran_page/
url_pdf: https://arxiv.org/pdf/2401.12046.pdf
url_video: https://youtube.com/playlist?list=PLtEvDdcT-Ai8irdlBB7wDsfOuOIZo1ZM2&si=4Ck7K-wnwjHv9P78

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

<meta http-equiv = "refresh" content = " 0.01 ; url = https://haojhuang.github.io/fourtran_page"/>
