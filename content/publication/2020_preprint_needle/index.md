---
title: "Dynamic Spatial Verification for Large-Scale Object-Level Image Retrieval"
authors:
- Joel Brogan
- Daniel Moreira
- Aparna Bharati
- Kevin Bowyer
- Patrick Flynn
- Anderson Rocha
- Walter Scheirer
date: "2020-01-01"
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: "Needle-Haystack scoring"
# publication_short: "NH score"

abstract: Images from social media can reflect diverse viewpoints, heated arguments, and expressions of creativity, adding new complexity to retrieval tasks. Researchers working on Content-Based Image Retrieval (CBIR) have traditionally tuned their algorithms to match filtered results with user search intent. However, we are now bombarded with composite images of unknown origin, authenticity, and even meaning. With such uncertainty, users may not have an initial idea of what the results of a search query should look like. For instance, hidden people, spliced objects, and subtly altered scenes can be difficult for a user to detect initially in a meme image, but may contribute significantly to its composition. We propose a new approach for spatial verification that aims at modeling object-level regions dynamically clustering keypoints in a 2D Hough space, which are then used to accurately weight small contributing objects within the results, without the need for costly object detection steps. We call this method Objects in Scene to Objects in Scene (OS2OS) score, and it is optimized for fast matrix operations on CPUs. OS2OS performs comparably to stateof-the-art methods in classic CBIR problems, on the Oxford 5K, Paris 6K, and Google-Landmarks datasets, without the need for bounding boxes. It also succeeds in emerging retrieval tasks such as image composite matching in the NIST MFC2018 dataset and meme-style composite imagery from Reddit.

# Summary. An optional shortened abstract.
summary: 2020 ArXiv Preprint

tags:
- CBIR
- Media Forensics
- Provenance Analysis
- Provenance Filtering
featured: false

links:
- name: Web
  url: https://arxiv.org/abs/1903.10019
url_pdf: https://arxiv.org/pdf/1903.10019.pdf
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
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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
