---
title: "Rational Neural Networks for Approximating Jump Discontinuities of Graph Convolution Operator"
authors:
- admin
- Feng Chen
- Rongjie Lai
- Xuchao Zhang
- Chang-Tien Lu
date: "2018-10-01T00:00:00Z"
doi: "10.1109/ICDM.2018.00021"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Data Mining*
publication_short: In **ICDM**

abstract: "For node level graph encoding, a recent important state-of-art method is the graph convolutional networks (GCN), which nicely integrate local vertex features and graph topology in the spectral domain. However, current studies suffer from several drawbacks: (1) graph CNNs relies on Chebyshev polynomial approximation which results in oscillatory approximation at jump discontinuities; (2) Increasing the order of Chebyshev polynomial can reduce the oscillations issue, but also incurs unaffordable computational cost; (3) Chebyshev polynomials require degree Omega(poly(1/e)) to approximate a jump signal, while rational function only needs O(poly log(1/e). However, it's non-trivial to apply rational approximation without increasing computational complexity due to the denominator. In this paper, the superiority of rational approximation is exploited for graph signal recovering. RatioanlNet is proposed to integrate rational function and neural networks. We show that rational function of eigenvalues can be rewritten as a function of graph Laplacian, which can avoid multiplication by the eigenvector matrix. Focusing on the analysis of approximation on graph convolution operation, a graph signal regression task is formulated. Under graph signal regression task, its time complexity can be significantly reduced by graph Fourier transform. To overcome the local minimum problem of neural networks model, a relaxed Remez algorithm is utilized to initialize the weight parameters. Convergence rate of RatioanlNet and polynomial based methods on jump signal is analyzed for a theoretical guarantee. The extensive experimental results demonstrated that our approach could effectively characterize the jump discontinuities, outperforming competing methods by a substantial margin on both synthetic and real-world graphs."


# Summary. An optional shortened abstract.
summary: A rational neural networks for improving graph node-level embeddings.

tags:
- graph neural networks
featured: true

#links:
#- name:
#  url:
url_pdf : "https://arxiv.org/pdf/1808.10073.pdf"
url_code: 'https://github.com/aquastar/RationalGraphNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.slideshare.net/czq825/rational-neural-networks-for-approximating-jump-discontinuities-of-graph-convolution-operatorx'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'FusionGAN'
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
slides: ""
---
