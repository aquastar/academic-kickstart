---
title: "Distributed self-paced learning in alternating direction method of multipliers"
authors:
- Xuchao Zhang
- Liang Zhao
- admin
- Chang-Tien Lu
date: "2018-04-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the Twenty-seventh International Joint Conference on Artificial Intelligence*
publication_short: In **IJCAI** 18

abstract: Self-paced learning (SPL) mimics the cognitive process of humans, who generally learn from easy samples to hard ones. One key issue in SPL is the training process required for each instance weight depends on the other samples and thus cannot easily be run in a distributed manner in a large-scale dataset. In this paper, we reformulate the self-paced learning problem into a distributed setting and propose a novel Distributed Self-Paced Learning method (DSPL) to handle large scale datasets. Specifically, both the model and instance weights can be optimized in parallel for each batch based on a consensus alternating direction method of multipliers. We also prove the convergence of our algorithm under mild conditions. Extensive experiments on both synthetic and real datasets demonstrate that our approach is superior to those of ex- isting methods..

# Summary. An optional shortened abstract.
summary: ADMM optimized by self-paced learning

tags:
- self-paced learning
featured: false

#links:
#- name:
#  url: 
url_pdf: https://www.ijcai.org/proceedings/2018/0437.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
slides: ""
---
