---
title: "Virtual Metering: An Efficient Water Disaggregation Algorithm via Non-Intrusive Load Monitoring"
authors:
- Bingsheng Wang
- admin
- Arnold P. Boedihardjo
- Chang-Tien Lu
date: "2018-01-01T00:00:00Z"
doi: "10.1145/3141770"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Intelligent Systems and Technology
publication_short: TIST

abstract:"The scarcity of potable water is a critical challenge in many regions around the world. Previous studies have shown that knowledge of device level water usage can lead to significant conservation. Although there is considerable interest in determining discriminative features via sparse coding for water disaggregation to separate whole house consumption into its component appliances, existing methods lack a mechanism for fitting coefficient distributions and are thus unable to accurately discriminate parallel devices' consumption. This paper proposes a Bayesian discriminative sparse coding model, referred to as Virtual Metering (VM), for this disaggregation task. Mixture-of-Gammas is employed for the prior distribution of coefficients, contributing two benefits: (1) guaranteeing the coefficients' sparseness and non-negativity; and (2) capturing the distribution of active coefficients. The resulting method effectively adapts the bases to aggregated consumption to facilitate discriminative learning in the proposed model, and devices' shape features are formalized and incorporated into Bayesian sparse coding to direct the learning of basis functions. Compact Gibbs Sampling (CGS) is developed to accelerate the inference process by utilizing the sparse structure of coefficients. The empirical results obtained from applying the new model to large-scale real and synthetic datasets revealed that VM significantly outperformed the benchmark methods."


# Summary. An optional shortened abstract.
summary:

tags:
- Beyesian
featured: false

#links:
#- name:
#  url:
url_pdf : "https://dl.acm.org/citation.cfm?id=3141770"
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
  caption: 'FusionGAN structure'
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
