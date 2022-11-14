---
title: 'Topographic DCNNs trained on a single
self-supervised task capture the functional
organization of cortex into visual processing streams'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Eshed Margalit
  - Daniel L. K. Yamins
  - Kendrick Kay
  - Kalanit Grill-Spector

date: '2021-04-15T00:00:00Z'
doi: '10.32470/CCN.2022.1219-0'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *SVRHM 2022 Workshop @ NeurIPS*
#publication_short: In *ICW*

abstract: A key organizing principle of visual cortex is functional specialization, whether locally in the context of category-selective patches, or on a broader scale in the case of visual processing streams. Primate visual cortex has traditionally been divided into two such processing streams, though recent research suggests that there may be at least three functionally and anatomically distinct streams, extending along the ventral, lateral, and parietal surfaces of the brain. While processing streams are typically thought of within the framework of what downstream behaviors/tasks they support, we ask instead whether anatomical constraints may be sufficient to produce this differentiation, even within the context of just one task objective. Comparing directly to human fMRI responses, we show that a model trained on a single task, and with novel anatomical constraints (Topographic DCNN), can capture not only the functional responses but also the segregation of visual cortex into distinct processing streams. The match to human data is strongest for a self-supervised vs. supervised objective and when the anatomical constraint, which encourages local response correlations as proxy for minimizing wiring length, is appropriately weighted. These results suggest that the broad-scale functional organization of visual cortex into parallel processing streams may be explained by the pressure to minimize biophysical costs such as wiring length, and that local spatial constraints can surprisingly percolate to create broad-scale structure.

# Summary. An optional shortened abstract.
summary: A model trained with a spatial constraint, on a single self-supervised task, can recapitulate the functional organization of visual cortex into multiple processing streams.

tags: [processing streams, vision, neuroscience, fMRI, topography, convolutional neural networks, self-supervised learning]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://openreview.net/forum?id=E1iY-d13smd'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---