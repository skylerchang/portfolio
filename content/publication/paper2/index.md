---
title: "Odd Distance Anchors for Rapid Clustering"
authors:
- Daniel Ashlock
- admin
- Matthew Stoodley


date: "2020-10-27"
doi: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference paper']

# Publication name and optional abbreviated publication name.
publication: 2020 IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB)

abstract: This paper introduces a rapid clustering algorithm called anchor clustering. The algorithm was invented to permit clustering of lymphocyte antigen receptor sequences for veterinary diagnostic applications. Anchor clustering has a slow off-line and a rapid on-line phase. The off-line portion consists of locating a set of points, called anchors, by packing points into the data space so that they satisfy a minimum distance constraint. This study addresses a problem in the anchor location phase of anchor clustering. When used on discrete data, like DNA under the Hamming metric, there is a problem with data that exhibit tied minimum distances to anchors. This can be addressed by finding sets of anchors in which as many of the small distances between anchors are odd. This study tests four methods for locating sets of anchors enriched for short, odd distances. One method, which explicitly scores anchor sets on avoiding ties, works very poorly. A method that encourages odd distances is somewhat more effective, but two methods that optimize the ratio of short odd distances to short even distances achieve substantial enrichment of short odd distances. The reasons for the observed performance of different techniques are explored and possible next steps are outlined.

# Summary. An optional shortened abstract.
summary: This paper introduces a rapid clustering algorithm called anchor clustering. The algorithm was invented to permit clustering of lymphocyte antigen receptor sequences for veterinary diagnostic applications.  

tags:
  - Machine Learning Algorithm

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9277719&tag=1'



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---