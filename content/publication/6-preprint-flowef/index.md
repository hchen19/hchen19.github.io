---
title: "Improving Ensemble Filters with Flow Matching"
authors:
- admin
- Alexandre Thiéry
date: "2026-09-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: ""

abstract: Data assimilation estimates a dynamical state from partial and noisy observations. Classical ensemble filters are efficient but restrict analysis updates through finite sample covariance and affine Gaussian distribution. We introduce the Flow Ensemble Filter (FlowEF), which uses conditional flow matching to transport the forecast ensemble from a classical baseline filter to an analysis ensemble. FlowEF uses a localized Gaussian source during training, transports forecast ensemble members from a baseline filter at deployment, and conditions its velocity field on ensembles from that baseline filter and the observation. The proposed model therefore learns a nonlinear update while mapping each baseline ensemble independently. For sparsely observed dynamical systems, FlowEF improves both deterministic and probabilistic metrics over all four classical ensemble filters. It also achieves the best performance among the state-of-the-art generative data assimilation models.

# Summary. An optional shortened abstract.
summary: ""

tags:
- data assimilation
- ensemble filtering
- flow matching
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2609.28015
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
  caption: 'Image credit: [**Haoyuan Chen**](https://hchen19.github.io/)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
