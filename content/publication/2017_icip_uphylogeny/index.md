---
title: "U-Phylogeny: Undirected provenance graph construction in the wild"
authors:
- Aparna Bharati
- Daniel Moreira
- Allan Pinto
- Joel Brogan
- Kevin Bowyer
- Patrick Flynn
- Walter Scheirer
- Anderson Rocha
date: "2017-09-20"
doi: "10.1109/ICIP.2017.8296535"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Image Processing
publication_short: ICIP

abstract: Deriving relationships between images and tracing back their history of modifications are at the core of Multimedia Phylogeny solutions, which aim to combat misinformation through doctored visual media. Nonetheless, most recent image phylogeny solutions cannot properly address cases of forged composite images with multiple donors, an area known as multiple parenting phylogeny (MPP). This paper presents a preliminary undirected graph construction solution for MPP, without any strict assumptions. The algorithm is underpinned by robust image representative keypoints and different geometric consistency checks among matching regions in both images to provide regions of interest for direct comparison. The paper introduces a novel technique to geometrically filter the most promising matches as well as to aid in the shared region localization task. The strength of the approach is corroborated by experiments with real-world cases, with and without image distractors (unrelated cases).

# Summary. An optional shortened abstract.
summary: 2017 IEEE International Conference on Image Processing

tags:
- Media Forensics
- Provenance Analysis
- Provenance Graph Construction
featured: false

links:
#- name: Web
#  url: https://ieeexplore.ieee.org/document/8296535
url_pdf: https://arxiv.org/pdf/1705.11187.pdf
url_code: 'https://gitlab.com/notredame-provenance/u-phylogeny'
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
