---
title: "Invariant Slot Attention: Object Discovery with Slot-Centric Reference Frames"
authors: 
- Ondrej Biza
- Sjoerd van Steenkiste
- Mehdi S. M. Sajjadi
- Gamaleldin F. Elsayed
- Aravindh Mahendran
- Thomas Kipf
date: "2023-11-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 40th International Conference on Machine Learning*
publication_short: In *ICML'23*

abstract: Automatically discovering composable abstractions from raw perceptual data is a long-standing challenge in machine learning. Recent slot-based neural networks that learn about objects in a self-supervised manner have made exciting progress in this direction. However, they typically fall short at adequately capturing spatial symmetries present in the visual world, which leads to sample inefficiency, such as when entangling object appearance and pose. In this paper, we present a simple yet highly effective method for incorporating spatial symmetries via slot-centric reference frames. We incorporate equivariance to per-object pose transformations into the attention and generation mechanism of Slot Attention by translating, scaling, and rotating position encodings. These changes result in little computational overhead, are easy to implement, and can result in large gains in terms of data efficiency and overall improvements to object discovery. We evaluate our method on a wide range of synthetic object discovery benchmarks namely CLEVR, Tetrominoes, CLEVRTex, Objects Room and MultiShapeNet, and show promising improvements on the challenging real-world Waymo Open dataset.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
url_pdf: '/publication/ondrej_isa/biza23isa.pdf'
url_code: 'https://invariantsa.github.io'


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

<meta http-equiv = "refresh" content = " 0.01 ; url = https://arxiv.org/pdf/2302.04973.pdf"/>

