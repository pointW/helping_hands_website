---
title: "Image to Icosahedral Projection for SO(3) Object Reasoning from Single-View Images"
authors:
- David Klee
- Ondrej Biza
- Robert Platt
- Robin Walters
date: "2022-11-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *PMLR Volume on Symmetry and Geometry in Neural Representations*
publication_short: In *PMLR*

abstract: Reasoning about 3D objects based on 2D images is challenging due to variations in appearance caused by viewing the object from different orientations. Tasks such as object classification are invariant to 3D rotations and other such as pose estimation are equivariant. However, imposing equivariance as a model constraint is typically not possible with 2D image input because we do not have an a priori model of how the image changes under out-of-plane object rotations. The only $\mathrm{SO}(3)$-equivariant models that currently exist require point cloud or voxel input rather than 2D images. In this paper, we propose a novel architecture based on icosahedral group convolutions that reasons in $\mathrm{SO(3)}$ by learning a projection of the input image onto an icosahedron. The resulting model is approximately equivariant to rotation in $\mathrm{SO}(3)$. We apply this model to object pose estimation and shape classification tasks and find that it outperforms reasonable baselines. 


# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://dmklee.github.io/image2icosahedral
url_pdf: https://arxiv.org/abs/2207.08925

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

<meta http-equiv = "refresh" content = " 0 ; url = https://arxiv.org/abs/2207.08925"/>
