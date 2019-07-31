---
title: "Domain-Specific Human-Inspired Binarized Statistical Image Features for Iris Recognition"
authors:
- Adam Czajka
- Daniel Moreira
- Kevin Bowyer
- Patrick Flynn
date: "2019-01-07"
doi: "10.1109/WACV.2019.00107"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE Winter Conference on Applications of Computer Vision
publication_short: WACV

abstract: Binarized statistical image features (BSIF) have been successfully used for texture analysis in many computer vision tasks, including iris recognition and biometric presentation attack detection. One important point is that all applications of BSIF in iris recognition have used the original BSIF filters, which were trained on image patches extracted from natural images. This paper tests the question of whether domain-specific BSIF can give better performance than the default BSIF. The second important point is in the selection of image patches to use in training for BSIF. Can image patches derived from eye-tracking experiments, in which humans perform an iris recognition task, give better performance than random patches? Our results say that (1) domain-specific BSIF features can out-perform the default BSIF features, and (2) selecting image patches in a task-specific manner guided by human performance can out-perform selecting random patches. These results are important because BSIF is often regarded as a generic texture tool that does not need any domain adaptation, and human-task-guided selection of patches for training has never (to our knowledge) been done. This paper follows the reproducible research requirements, and the new iris-domain-specific BSIF filters, the patches used in filter training, the database used in testing and the source codes of the designed iris recognition method are made available along with this paper to facilitate applications of this concept.

# Summary. An optional shortened abstract.
summary: 2019 IEEE Winter Conference on Applications of Computer Vision

tags:
- Iris Recognition
- BSIF
- Biometrics
featured: false

links:
#- name: Web
#  url: https://ieeexplore.ieee.org/document/8658238
url_pdf: https://arxiv.org/pdf/1807.05248.pdf
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
  #caption: ''
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- tshepii

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
