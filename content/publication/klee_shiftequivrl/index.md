---
title: "Understanding the Mechanism behind Data Augmentation's Success on Image Based RL"
authors:
- David Klee
- Robin Walters
- Robert Platt
date: "2022-06-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *RLDM'22*
publication_short: In *RLDM'22*

abstract: Reinforcement learning for continuous control tasks is challenging with image observations, due to the representation learning problem. A series of recent work has shown that augmenting the observations via random shifts during training significantly improves performance, even matching state-based methods. However, it is not well-understood why augmentation is so beneficial; since the method uses a nearly-shift equivariant convolutional encoder, shifting the input should have little impact on what features are learned. In this work, we investigate why random shifts are useful augmentations for image-based RL and show that it increases both the shift-equivariance and shift-invariance of the encoder. In other words, the visual features learned exhibit spatial continuity, which we show can be partially achieved using dropout. We hypothesize that the spatial continuity of the visual encoding simplifies learning for the subsequent linear layers in the actor-critic networks.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
url_pdf: https://dmklee.github.io/assets/publications/data_aug/paper.pdf
url_poster: https://dmklee.github.io/assets/publications/data_aug/poster.pdf

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

<meta http-equiv = "refresh" content = " 0 ; url = https://dmklee.github.io/assets/publications/data_aug/paper.pdf"/>
