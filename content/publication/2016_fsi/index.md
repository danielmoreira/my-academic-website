---
title: "Pornography classification: The hidden clues in video space–time"
authors:
- Daniel Moreira
- Sandra Avila
- Mauricio Perez
- Daniel Moraes
- Vanessa Testoni
- Eduardo Valle
- Siome Goldenstein
- Anderson Rocha
date: "2016-11-01"
doi: "https://doi.org/10.1016/j.forsciint.2016.09.010"

# Schedule page publish date (NOT publication's date).
# cpublishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Elsevier Forensic Science International"
publication_short: "FSI"

abstract: As web technologies and social networks become part of the general public's life, the problem of automatically detecting pornography is into every parent's mind — nobody feels completely safe when their children go online. In this paper, we focus on video-pornography classification, a hard problem in which traditional methods often employ still-image techniques — labeling frames individually prior to a global decision. Frame-based approaches, however, ignore significant cogent information brought by motion. Here, we introduce a space-temporal interest point detector and descriptor called Temporal Robust Features (TRoF). TRoF was custom-tailored for efficient (low processing time and memory footprint) and effective (high classification accuracy and low false negative rate) motion description, particularly suited to the task at hand. We aggregate local information extracted by TRoF into a mid-level representation using Fisher Vectors, the state-of-the-art model of Bags of Visual Words (BoVW). We evaluate our original strategy, contrasting it both to commercial pornography detection solutions, and to BoVW solutions based upon other space-temporal features from the scientific literature. The performance is assessed using the Pornography-2k dataset, a new challenging pornographic benchmark, comprising 2000 web videos and 140 h of video footage. The dataset is also a contribution of this work and is very assorted, including both professional and amateur content, and it depicts several genres of pornography, from cartoon to live action, with diverse behavior and ethnicity. The best approach, based on a dense application of TRoF, yields a classification error reduction of almost 79% when compared to the best commercial classifier. A sparse description relying on TRoF detector is also noteworthy, for yielding a classification error reduction of over 69%, with 19× less memory footprint than the dense solution, and yet can also be implemented to meet real-time requirements.

# Summary. An optional shortened abstract.
summary: 2016 Elsevier Forensic Science International

tags:
- Sensitive Media Analysis
- Pornography Detection
- TRoF
featured: false

# links:
# - name: Web
#  url: 
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=ZfaW5kvXjMo&t=21s'

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
- sma
- trof

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
{{< youtube ZfaW5kvXjMo >}}