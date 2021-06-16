---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Unsupervised discovery of temporal structure in noisy data with dynamical components analysis"
authors: [David Clark, Jesse Livezey, Kristofer Bouchard]
date: 2019-12-05
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Advances in Neural Information Processing Systems"
publication_short: "NeurIPS 2019"

abstract: "Linear dimensionality reduction methods are commonly used to extract low-dimensional structure from high-dimensional data. However, popular methods disregard temporal structure, rendering them prone to extracting noise rather than meaningful dynamics when applied to time series data. At the same time, many successful unsupervised learning methods for temporal, sequential and spatial data extract features which are predictive of their surrounding context. Combining these approaches, we introduce Dynamical Components Analysis (DCA), a linear dimensionality reduction method which discovers a subspace of high-dimensional time series data with maximal predictive information, defined as the mutual information between the past and future. We test DCA on synthetic examples and demonstrate its superior ability to extract dynamical structure compared to commonly used linear methods. We also apply DCA to several real-world datasets, showing that the dimensions extracted by DCA are more useful than those extracted by other methods for predicting future states and decoding auxiliary variables. Overall, DCA robustly extracts dynamical structure in noisy, high-dimensional data while retaining the computational efficiency and geometric interpretability of linear dimensionality reduction methods."

# Summary. An optional shortened abstract.
summary: "Dynamical components analysis (DCA) is a linear dimensionality reduction method for high-dimensional time-series data that extracts dynamical structure by maximizing an information-theoretic objective. DCA outperforms methods such as Principal Components Analysis and Slow Feature Analysis in extracting dynamical structure in several datasets."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1905.09944
url_code: https://github.com/BouchardLab/DynamicalComponentsAnalysis
url_dataset:
url_poster: https://github.com/BouchardLab/DynamicalComponentsAnalysis/blob/master/NeuripsPoster.pdf
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
