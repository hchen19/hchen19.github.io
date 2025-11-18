---
title: "Privacy-aware Gaussian Process Regression"
authors:
- Rui Tuo
- admin
- Raktim Bhattacharya
author_notes:
- ""
- ""
- ""
date: "2025-10-14"
doi: ""
math: true

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Technometrics 1-15"
publication_short: Technometrics

abstract: We propose a novel theoretical and methodological framework for Gaussian process regression subject to privacy constraints. The proposed method can be used when a data owner is unwilling to share a high-fidelity supervised learning model built from their data with the public due to privacy concerns. The key idea of the proposed method is to add synthetic noise to the data until the predictive variance of the Gaussian process model reaches a prespecified privacy level. The optimal covariance matrix of the synthetic noise is formulated in terms of semi-definite programming. We also introduce the formulation of privacy-aware solutions under continuous privacy constraints using kernel-based approaches, and study their theoretical properties. The proposed method is illustrated by considering a model that tracks the trajectories of satellites and a real application on a census dataset.

# Summary. An optional shortened abstract.
summary: ""

tags:
- GP
- privacy preserving
- semi-definite programming
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.tandfonline.com/doi/full/10.1080/00401706.2025.2580637'
url_code: 'https://github.com/hchen19/privacygp'
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
