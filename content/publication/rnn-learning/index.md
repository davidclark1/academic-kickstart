---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Structure, disorder, and dynamics in task-trained recurrent neural circuits"
authors: [david, Blake Bordelon, Jacob Zavatone-Veth, Cengiz Pehlevan]
date: 2026-03-03
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "bioR𝛘iv"
publication_short: ""

abstract: "Across many brain areas, neurons produce heterogeneous, seemingly disordered responses. Yet the circuits these neurons comprise cannot be purely random; they must possess some structure to generate representations and computations underlying behavior. How much structure is present in recurrent connectivity relative to disorder, and how the interaction between them shapes population dynamics and single-neuron responses, remain incompletely understood. Recurrent neural networks trained to perform tasks have become a leading model of such circuits, but conventional training yields a single point in a vast space of task-compatible solutions, with no systematic way to explore this space and no theory of how internal representations vary within it. Without such a theory, the questions above cannot be addressed, and comparisons between trained networks and neural data are difficult to interpret. Here, we introduce a control parameter governing the degree to which learning reshapes recurrent connectivity and permits interpolation between a reservoir regime and one in which recurrent weights are restructured by learning to produce task-relevant internal representations. Varying this parameter generates a family of task-compatible solutions whose internal dynamics differ in a controlled and interpretable way. We derive a dynamical mean-field theory showing how the balance of randomness and structure in connectivity influences both population-level dynamics and single-neuron responses, with the former converging to a deterministic limit and the latter becoming independent samples from a single-neuron response distribution. When connectivity is random, this response distribution is Gaussian; recurrent restructuring drives it toward task-dependent, non-Gaussian forms. In linear networks, restructuring amplifies task-relevant frequencies; in nonlinear networks, it drives a phase transition from chaotic, high-dimensional activity to ordered, low-dimensional dynamics that generalize temporally beyond the training period. We apply this theory to a reaching task in which a recurrent network must reproduce macaque muscle activity. Optimally matching simultaneous motor-cortex recordings requires a relatively small degree of restructuring in which learned structure coexists with random heterogeneity. These results are suggestive of a broader picture in which large recurrent neural circuits are quite random, but contain, to varying degrees, structured recurrent connectivity sufficient for generalizable, task-relevant representations."

# Summary. An optional shortened abstract.
summary:
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: bioR𝛘iv
  url: https://www.biorxiv.org/content/10.64898/2026.03.02.708943
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_dataset:
url_poster: 
url_project:
url_slides:
url_source:
url_video:

url_code: https://github.com/davidclark1/RNN-Learning-Theory


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
