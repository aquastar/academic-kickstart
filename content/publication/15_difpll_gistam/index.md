---
title: "DIFPLL: Distributed drone flight path builder system. (Best student paper)"
authors:
- Manu Shukla
- admin
- Chang-Tien Lu
date: "2015-04-17T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference onGeographical Information Systems Theory, Applications and Management*
publication_short: In **GISTAM** 15

abstract: Drones have become ubiquitous in performing risky and labor intensive areal tasks cheaply and safely. To allow them to be autonomous, their flight plan needs to be pre-built for them. Existing works do not precalculate flight paths but instead focus on navigation through camera based image processing techniques, genetic or geometric algorithms to guide the drone during flight. That makes flight navigation complex and risky. In this paper we present automated flight plan builder DIFPL which pre-builds flight plans for drones to survey a large area. The flight plans are built for subregions and fed into drones which allow them to navigate autonomously. DIFPL employs distributed paradigm on Hadoop MapReduce framework. Distribution is achieved by processing sections or subregions in parallel. Experiments performed with network and elevation datasets validate the efficiency of DIFPL in building optimal flight plans.

# Summary. An optional shortened abstract.
summary: a path planing method for drones.

tags:
- unmanned vehicle
featured: true

#links:
#- name:
#  url: 
url_pdf : "http://www.nvc.cs.vt.edu/~ctlu/Publication/2015/GISTAM-2015-Proceedings.pdf"
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

