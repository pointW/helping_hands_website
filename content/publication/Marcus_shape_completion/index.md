---
title: "Robotic Pick-and-Place With Uncertain Object Instance Segmentation and Shape Completion"
authors:
- Marcus Gualtieri
- Robert Platt
date: "2021-05-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Robotics and Automation Letters*
publication_short: In *RA-L*

abstract: "We consider robotic pick-and-place of partially visible, novel objects, where goal placements are non-trivial, e.g., tightly packed into a bin. One approach is (a) use object instance segmentation and shape completion to model the objects and (b) use a regrasp planner to decide grasps and places displacing the models to their goals. However, it is critical for the planner to account for uncertainty in the perceived models, as object geometries in unobserved areas are just guesses. We account for perceptual uncertainty by incorporating it into the regrasp planner’s cost function. We compare seven different costs. One of these, which uses neural networks to estimate probability of
grasp and place stability, consistently outperforms uncertaintyunaware costs and evaluates faster than Monte Carlo sampling. On a real robot, the proposed cost results in successfully packing objects tightly into a bin 7.8% more often versus the commonly used minimum-number-of-grasps cost."

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: true

links:
- name: Video
  url: https://youtu.be/OBGf7L3iKsM
- name: Supplementary Results
  url: https://www.ccs.neu.edu/home/mgualti/2021-Gualtieri-SupplementaryResultsForRoboticPickAndPlaceWithUncertainObjectInstanceSegmentationAndShapeCompletion.pdf
url_pdf: https://www.ccs.neu.edu/home/mgualti/2021-Gualtieri-RoboticPickAndPlaceWithUncertainObjectInstanceSegmentationAndShapeCompletion.pdf
url_code: https://github.com/mgualti/GeomPickPlace

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

