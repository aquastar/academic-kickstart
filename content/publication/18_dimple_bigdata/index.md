---
title: "DIMPL: a distributed in-memory drone flight path builder system"
authors:
- Manu Shukla
- admin
- Chang-Tien Lu
date: "2018-07-30T00:00:00Z"
doi: "10.1186/s40537-018-0134-7"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Journal of Big Data
publication_short: Journal of Big Data

abstract: Drones are increasingly being used to perform risky and labor intensive aerial tasks cheaply and safely. To ensure operating costs are low and ?ights autonomous, their flight plans must be pre-built. In existing techniques drone flight paths are not automatically pre-calculated based on drone capabilities and terrain information. Instead, they focus on adaptive shortest paths, manually determined paths, navigation through camera, images and/or GPS for guidance and genetic or geometric algorithms to guide the drone during ?ight, all of which makes ?ight navigation complex and risky. In this paper we present details of an automated ?ight plan builder DIMPL that pre-builds flight plans for drones tasked with surveying a large area to take photographs of electric poles to identify ones with hazardous vegetation overgrowth. The ?ight plans are built for subregions allowing the drones to navigate autonomously. DIMPL employs a distributed in-memory paradigm to process subregions in parallel and build flight paths in a highly ef?cent manner. Experiments performed with network and elevation datasets validated the effciency of DIMPL in building optimal flight plans for a fleet of different types of drones and demonstrated the tremendous performance improvements possible using the distributed in-memory paradigm.

# Summary. An optional shortened abstract.
summary: an efficient path planning approach for drones.

tags:
- unmanned vehicle
featured: false

#links:
#- name:
#  url:
url_pdf : "https://journalofbigdata.springeropen.com/articles/10.1186/s40537-018-0134-7"
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
