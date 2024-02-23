---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Structure of activity in multiregion recurrent neural networks"
authors: [david, Manuel Beiran]
date: 2024-02-19
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "Neural circuits are composed of multiple regions, each with rich dynamics and engaging in communication with other regions. The combination of local, within-region dynamics and global, network-level dynamics is thought to provide computational flexibility. However, the nature of such multiregion dynamics and the underlying synaptic connectivity patterns remain poorly understood. Here, we study the dynamics of recurrent neural networks with multiple interconnected regions. Within each region, neurons have a combination of random and structured recurrent connections. Motivated by experimental evidence of communication subspaces between cortical areas, these networks have low-rank connectivity between regions, enabling selective routing of activity. These networks exhibit two interacting forms of dynamics: high-dimensional fluctuations within regions and low-dimensional signal transmission between regions. To characterize this interaction, we develop a dynamical mean-field theory to analyze such networks in the limit where each region contains infinitely many neurons, with cross-region currents as key order parameters. Regions can act as both generators and transmitters of activity, roles that we show are in conflict. Specifically, taming the complexity of activity within a region is necessary for it to route signals to and from other regions. Unlike previous models of routing in neural circuits, which suppressed the activities of neuronal groups to control signal flow, routing in our model is achieved by exciting different high-dimensional activity patterns through a combination of connectivity structure and nonlinear recurrent dynamics. This theory provides insight into the interpretation of both multiregion neural data and trained neural networks."

# Summary. An optional shortened abstract.
summary:
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arXiv
  url: https://arxiv.org/abs/2402.12188
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code: 
url_dataset:
url_poster: 
url_project:
url_slides:
url_source:
url_video:

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
