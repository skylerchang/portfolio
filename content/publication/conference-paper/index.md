---
title: 'Anchor Clustering for million-scale immune repertoire sequencing data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Daniel A. Ashlock
  - Steffen P. Graether
  - Stefan M. Keller



date: '2024-01-25T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-25T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: The clustering of immune repertoire data is challenging due to the computational cost associated with a very large number of pairwise sequence comparisons. To overcome this limitation, we developed Anchor Clustering, an unsupervised clustering method designed to identify similar sequences from millions of antigen receptor gene sequences. First, a Point Packing algorithm is used to identify a set of maximally spaced anchor sequences. Then, the genetic distance of the remaining sequences to all anchor sequences is calculated and transformed into distance vectors. Finally, distance vectors are clustered using unsupervised clustering. This process is repeated iteratively until the resulting clusters are small enough so that pairwise distance comparisons can be performed. Our results demonstrate that Anchor Clustering is faster than existing pairwise comparison clustering methods while providing similar clustering quality. With its flexible, memory-saving strategy, Anchor Clustering is capable of clustering millions of antigen receptor gene sequences in just a few minutes. This method enables the meta-analysis of immune-repertoire data from different studies and could contribute to a more comprehensive understanding of the immune repertoire data space.

# Summary. An optional shortened abstract.
summary: We present a novel clustering algorithm that can process million-scale datasets than possible with existing methods, yet still obtain similar clustering quality. Anchor Clustering could facilitate meta-analyses of immune repertoire datasets and help characterize the immune repertoire sequence space in a more comprehensive manner.

tags:
  - Machine Learning algorithm

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://bmcbioinformatics.biomedcentral.com/counter/pdf/10.1186/s12859-024-05659-z.pdf'
url_dataset: 'https://github.com/skylerchang/Anchor_Clustering_Nt.'

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
slides: example
---


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}


