---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Transient dynamics of associative memory models"
authors: [david]
date: 2025-06-05
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

abstract: "Associative memory models such as the Hopfield network and its dense generalizations with higher-order interactions exhibit a \"blackout catastrophe\"--a discontinuous transition where stable memory states abruptly vanish when the number of stored patterns exceeds a critical capacity. This transition is often interpreted as rendering networks unusable beyond capacity limits. We argue that this interpretation is largely an artifact of the equilibrium perspective. We derive dynamical mean-field equations using a bipartite cavity approach for graded-activity dense associative memory models, with the Hopfield model as a special case, and solve them using a numerical scheme. We show that patterns can be transiently retrieved with high accuracy above capacity despite the absence of stable attractors. This occurs because slow regions persist in the above-capacity energy landscape as shallow, unstable remnants of below-capacity stable basins. The same transient-retrieval effect occurs in below-capacity networks initialized outside basins of attraction. \"Transient-recovery curves\" provide a concise visual summary of these effects, revealing graceful, non-catastrophic changes in retrieval behavior above capacity and allowing us to compare the behavior across interaction orders. This dynamical perspective reveals rich energy landscape structure obscured by equilibrium analysis and suggests biological neural circuits may exploit transient dynamics for memory retrieval. Furthermore, our approach suggests ways of understanding computational properties of neural circuits without reference to fixed points, advances the technical repertoire of numerical mean-field solution methods for recurrent neural networks, and yields new theoretical results on generalizations of the Hopfield model."

# Summary. An optional shortened abstract.
summary:
tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: arXiv
  url: https://arxiv.org/abs/2506.05303
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
