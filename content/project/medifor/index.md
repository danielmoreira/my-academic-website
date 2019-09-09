---
title: MediFor
summary: Integrity assessment of digital images through content provenance analysis.
tags:
- Media Forensics
- Provenance Analysis
- Provenance Filtering
- Provenance Graph Construction
date: "2019-06-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  #caption: Photo by rawpixel on Unsplash
  focal_point: Center

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "project/medifor/provenance.pdf"
url_video: "https://www.youtube.com/watch?v=Na43QFKW9PE"
url_dataset: 'https://github.com/CVRL/Reddit_Provenance_Datasets'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
**Status:** Ongoing, **Funded by:** DARPA   
**Advisor:** Prof. [Walter Scheirer](https://www.wjscheirer.com/)

The Media Forensics research project ([MediFor](https://www.darpa.mil/program/media-forensics)) is an endeavor funded by the Defense Advanced Research Projects Agency (DARPA) and the Air Force Research Laboratory (AFRL), whose goal is to develop solutions for the automated assessment of the integrity of digital images.

Working together with the Universities of Purdue, South California (USC), New York (NYU), Siena, Campinas (Unicamp), and the Politécnico di Milano, our team leads the development of solutions to the problem of Provenance Analysis. Given a questioned image, namely a probe, and a large corpus of images (such as the Internet), Provenance Analysis aims at two major tasks:

1. Finding the images that directly and transitively share content with the probe (a task we call Provenance Filtering).

2. Building the directed acyclic graph whose nodes individually represent the probe and related images, and whose edges express the edition and content-donation history (e.g., cropping, blurring, removal, splicing, etc.) between pairs of images, linking seminal to generated elements (a task we call Provenance Graph Construction).

{{< youtube Na43QFKW9PE >}}
&NewLine;

By combining ideas from the areas of image retrieval, digital image forensics, and graph theory, Provenance Analysis constitutes an interesting interdisciplinary topic that spans the fields of image processing and computer vision.


## Research Team
- Prof. Walter Scheirer (PI)
- Prof. Anderson Rocha (PI)
- Prof. Kevin Bowyer (PI)
- Prof. Patrick Flynn (PI)
- Daniel Moreira (Postdoc)
- Aparna Bharati (PhD Student)
- Joel Brogan (PhD Student)
- Allan Pinto (PhD Student)
- Michael Parowski (Undergrad Student)
- Patricia Hale (Undergrad Student)
- William Badart (Undergrad Student)
