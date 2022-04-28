---
title: "Early Forecasting of the Impact of Traffic Accidents Using a Single Shot Observation"
authors:
- Guangyu Meng
- Qisheng Jiang
- Kaiqun Fu
- Beiyu Lin
- Chang-Tien Lu
- admin
date: "2022-04-01T00:00:00Z"
doi: "10.1109/ICDM.2017.98"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: SIAM International Conference on Data Mining (SDM) 2022
publication_short: SDM

abstract: Predicting and measuring the impact of traffic collisions is crucial for Intelligent Transportation Systems (ITS). Numerous works in this field have successfully applied graph neural networks to ITS. Existing research on graph neural networks mainly relies on the graph Fourier transform, assuming neighborhood homophily. The homophily assumption, on the other hand, makes it difficult to define abrupt signals such as traffic accidents. Our research proposes an abrupt graph wavelet network (AGWN) for forecasting the durations of traffic incidents using a single shot. To begin, graph wavelet (GW) is theoretically examined in terms of linear separability in comparison to graph Fourier (GF), demonstrating its advantage in modeling abrupt graph signals. Sensitivity analysis and admissibility conditions are utilized to further study the behavior of GW in abrupt graph signals, justifying the use of zero sum function as wavelet kernel. The synthetic data results support our proposed wavelet kernel's effectiveness in modeling a variety of abrupt signals, while real-world trials demonstrate that our method significantly outperforms baseline models in forecasting the duration of an accident impact.


# Summary. An optional shortened abstract.
summary: Use one time frame data to predict the duration of traffic accident duration

tags:
- graph
featured: true

#links:
#- name:
#  url:
url_pdf : "https://epubs.siam.org/doi/abs/10.1137/1.9781611977172.12"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.slideshare.net/czq825/early-forecasting-of-the-impact-of-traffic-accidents-using-a-single-shot-observation'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'AGWN structure'
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

