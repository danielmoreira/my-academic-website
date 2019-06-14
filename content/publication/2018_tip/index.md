---
title: "Image Provenance Analysis at Scale"
authors:
- Daniel Moreira
- Aparna Bharati
- Joel Brogan
- Allan Pinto
- Michael Parowski
- Kevin Bowyer
- Patrick Flynn
- Anderson Rocha
- Walter Scheirer
date: "2018-08-16"
doi: "https://doi.org/10.1109/TIP.2018.2865674"

# Schedule page publish date (NOT publication's date).
# cpublishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: "T-IP"

abstract: Prior art has shown it is possible to estimate, through image processing and computer vision techniques, the types and parameters of transformations that have been applied to the content of individual images to obtain new images. Given a large corpus of images and a query image, an interesting further step is to retrieve the set of original images whose content is present in the query image, as well as the detailed sequences of transformations that yield the query image, given the original images. This is a problem that recently has received the name of image provenance analysis. In these times of public media manipulation (e.g., fake news and meme sharing), obtaining the history of image transformations is relevant for fact checking and authorship verification, among many other applications. This paper presents an end-to-end processing pipeline for image provenance analysis which works at real-world scale. It employs a cutting-edge image filtering solution that is custom-tailored for the problem at hand, as well as novel techniques for obtaining the provenance graph that expresses how the images, as nodes, are ancestrally connected. A comprehensive set of experiments for each stage of the pipeline is provided, comparing the proposed solution with the state-of-the-art results, employing previously published data sets. In addition, this paper introduces a new data set of real-world provenance cases from the social media site Reddit, along with baseline results.

# Summary. An optional shortened abstract.
summary: 2018 IEEE Transactions on Image Processing

tags:
- CBIR
- Media Forensics
- Provenance Analysis
- Provenance Filtering
- Provenance Graph Construction
featured: false

# links:
# - name: Web
#  url: 
url_pdf: https://arxiv.org/pdf/1801.06510.pdf
url_code: 'https://github.com/CVRL/Scalable_Provenance/tree/master/graph_building'
url_dataset: 'https://github.com/CVRL/Reddit_Provenance_Datasets'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: ''
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
# slides: example
---
