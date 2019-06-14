---
title: "Provenance filtering for multimedia phylogeny"
authors:
- Allan Pinto
- Daniel Moreira
- Aparna Bharati
- Joel Brogan
- Kevin Bowyer
- Patrick Flynn
- Walter Scheirer
- Anderson Rocha
date: "2017-09-20"
doi: "https://doi.org/10.1109/ICIP.2017.8296532"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Image Processing
publication_short: ICIP

abstract: Departing from traditional digital forensics modeling, which seeks to analyze single objects in isolation, multimedia phylogeny analyzes the evolutionary processes that influence digital objects and collections over time. One of its integral pieces is provenance filtering, which consists of searching a potentially large pool of objects for the most related ones with respect to a given query, in terms of possible ancestors (donors or contributors) and descendants. In this paper, we propose a two-tiered provenance filtering approach to find all the potential images that might have contributed to the creation process of a given query q. In our solution, the first (coarse) tier aims to find the most likely “host” images - the major donor or background - contributing to a composite/doctored image. The search is then refined in the second tier, in which we search for more specific (potentially small) parts of the query that might have been extracted from other images and spliced into the query image. Experimental results with a dataset containing more than a million images show that the two-tiered solution underpinned by the context of the query is highly useful for solving this difficult task.

# Summary. An optional shortened abstract.
summary: 2017 IEEE International Conference on Image Processing

tags:
- Media Forensics
- Provenance Analysis
- Provenance Filtering
featured: false

links:
- name: Web
  url: https://ieeexplore.ieee.org/document/8296532
url_pdf: https://arxiv.org/pdf/1706.00447.pdf
url_code: 'https://gitlab.com/notredame-provenance/filtering'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  #caption: ''
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- medifor

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
