---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Linear equivalence of nonlinear recurrent neural networks"
authors: [david]
date: 2026-04-26
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

abstract: "Large nonlinear recurrent neural networks with random couplings generate high-dimensional, potentially chaotic activity whose structure is of interest in neuroscience, machine learning, ecology, and other fields. A fundamental object encoding the collective structure of this activity is the N×N covariance matrix. Prior analytical work on the covariance matrix has been limited to low-dimensional summary statistics, not the full high-dimensional object for a specific realization of the couplings. Recent work proposed an ansatz in which, at large N, the covariance matrix for a typical quenched realization takes the same form as that of a linear network with the same couplings, driven by independent noise, with mean-field order parameters setting the effective transfer function and the noise spectrum. Here, we derive this ansatz using the two-site cavity method, providing two distinct derivations that offer complementary perspectives. The first decomposes each unit's activity into a linear component and a nonlinear residual, and shows that cross-covariances between residuals at distinct sites are strongly suppressed, so that residuals act as independent noise within a linear network. The second writes a self-consistent matrix equation for the covariance matrix. A naive Gaussian closure for the joint statistics of activity at distinct sites gives the wrong equation; the cavity method separates Gaussian and non-Gaussian contributions, which enter at the same order, and produces the correct one. We verify the predictions numerically across a range of network sizes. These results extend linear equivalence from feedforward high-dimensional nonlinear systems, where the weights being analyzed are independent of their inputs, to recurrent networks, where the activities depend on the same couplings that generate them."

# Summary. An optional shortened abstract.
summary:
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arXiv
  url: https://arxiv.org/abs/2604.23489
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
