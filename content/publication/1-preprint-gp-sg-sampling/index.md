---
title: "Gaussian Processes Sampling with Sparse Grids under Additive Schwarz Preconditioner"
authors:
- admin
- Rui Tuo
date: "2024-01-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: ""

abstract: Gaussian processes (GPs) are widely used in non-parametric Bayesian modeling, and play an important role in various statistical and machine learning applications. In a variety tasks of uncertainty quantification, generating random sample paths of GPs is of interest. As GP sampling requires generating high-dimensional Gaussian random vectors, it is computationally challenging if a direct method, such as the Cholesky decomposition, is used. In this paper, we propose a scalable algorithm for sampling random realizations of the prior and posterior of GP models. The proposed algorithm leverages inducing points approximation with sparse grids, as well as additive Schwarz preconditioners, which reduce computational complexity, and ensure fast convergence. We demonstrate the efficacy and accuracy of the proposed method through a series of experiments and comparisons with other recent works.

# Summary. An optional shortened abstract.
summary: ""

tags:
- GP
- sampling
- sparse grids
- additive Schwarz preconditioner
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2408.00206
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
  caption: 'Image credit: [**James T. Wilson**](https://github.com/j-wilson/GPflowSampling/blob/develop/examples/1_model_api.ipynb)'
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
