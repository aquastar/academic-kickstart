---
title: "Estimating the Circuit Deobfuscating Runtime based on Graph Deep Learning"
authors:
- admin
- Gaurav Kolhe
- Setareh Rafatirad
- Chang-Tien Lu
- Sai Manoj Pudukotai Dinakarrao
- Houman Homayoun
- Liang Zhao
date: "2020-03-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-11-07T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Design, Automation and Test in Europe Conference
publication_short:  DATE

abstract: "Circuit obfuscation has been proposed to protect digital integrated circuits (ICs) from different security threats such as reverse engineering by introducing ambiguity in the circuit i.e., addition of the logic gates whose functionality cannot be
determined easily by the attacker. In order to conquer such defenses, techniques such as Boolean satisfiability-checking (SAT)-based attacks were introduced. SAT-attack can potentially decrypt the obfuscated circuits but the deobfuscation runtime could have a large span ranging from few milliseconds to few years or more, depending on the number and location of obfuscated gates, the topology of the obfuscated circuit and obfuscation technique used. To ensure the security of the deployed obfuscation mechanism, it is essential to accurately pre-estimate the deobfuscation time, thereby one can optimize the deployed defense in order to maximize the deobfuscation runtime. However, estimating the deobfuscation runtime is a challenging task due to 1) the complexity and heterogeneity of graph-structured circuit, 2) the unknown and sophisticated mechanisms of the attackers for deobfuscation, 3) efficiency and scalability requirement in practice. To address the above mentioned challenges, this work proposes the first machine-learning framework that predicts the deobfuscation runtime based on graph deep learning. Specifically, we design a new model, ICNet with new input and convolution layers to characterize circuit's topology, which are then integrated by heterogeneous deep fully-connected layers to obtain the deobfuscation runtime. The proposed ICNet is an end-to-end framework which can automatically extract the determinant features required for deobfuscation runtime prediction. Extensive experiments on standard benchmarks demonstrate its effectiveness and efficiency beyond many competitive baselines."

# Summary. An optional shortened abstract.
summary: Apply graph convolutional network to estimate runtime of circuit decryption.

tags:
- circuit
featured: false

#links:
#- name:
#  url:
url_pdf : ""
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
