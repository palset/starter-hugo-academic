---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detecting higher-order structural changes from 3D genome organization data" 
event: National Library of Medicine (NLM) Informatics Training Conference 
event_url: https://web.cvent.com/event/1543af76-97cc-4042-b704-d401b3b1b8ac/summary 
location: Virtual/online
address: 
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Three-dimensional (3D) genome organization, which determines how the DNA is packaged inside the nucleus, has emerged as a key regulatory mechanism of cellular processes. High-throughput chromosomal conformation capture (Hi-C) technologies have enabled the study of 3D genome organization by experimentally measuring interactions among genomic regions in 3D space. Analysis of Hi-C data has revealed higher-order organizational units at multiple resolutions: chromosomal territories, compartments, and topologically associating domains (TADs). Changes or disruptions to such structures have been associated with disease, development, and evolution. Therefore, a key problem is to systematically detect higher-order structural changes across Hi-C datasets from multiple conditions. Existing computational methods to detect changes in 3D genome organization either do not model higher-order structural units, specialize only in a specific scale (e.g., TADs), or only compare pairs of Hi-C datasets. We address these limitations with Tree-structured Graph-regularized Integrated Factorization (TGIF), a new multi-task Non-negative Matrix Factorization (NMF) approach. TGIF makes use of complex tree-structured relationships among multiple Hi-C datasets such that closely related tasks, one for each Hi-C matrix, have similar lower-dimensional factors. The factors can be further constrained with task-specific graph regularization and are used to extract clusters of genomic regions with dynamically changing interaction profiles across tasks. We demonstrate our framework effectively recovers ground-truth clusters in simulated data and can detect biologically meaningful structural changes in Hi-C datasets from cancer cell lines and mouse neural development at genome-wide, compartmental, and local TAD scales."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-06-21T16:20:22-06:00
#date_end: 2019-12-10T16:20:22-06:00
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: 2019-12-10T16:20:22-06:00

authors: ["Da-Inn Lee","Sushmita Roy"]
tags: ["Dimension Reduction","3D Genome"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides: 
url_code:
url_pdf:
url_video: 

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
