---
title: "Kernel Packet: An Exact and Scalable Algorithm for Gaussian Process Regression with Matérn Correlations"
authors:
- admin
- Liang Ding
- Rui Tuo
author_notes:
- "Equal contribution"
- "Equal contribution"
- ""
date: "2022-04-01"
doi: ""
math: true

# Schedule page publish date (NOT publication's date).
publishDate: "2024-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Machine Learning Research , 23*(127)"
publication_short: Journal of Machine Learning Research (JMLR)

abstract: We develop an exact and scalable algorithm for one-dimensional Gaussian process regression with Matérn correlations whose smoothness parameter 𝜈 is a half-integer. The proposed algorithm only requires 𝒪(𝜈3𝑛) operations and 𝒪(𝜈𝑛) storage. This leads to a linear-cost solver since 𝜈 is chosen to be fixed and usually very small in most applications. The proposed method can be applied to multi-dimensional problems if a full grid or a sparse grid design is used. The proposed method is based on a novel theory for Matérn correlation functions. We find that a suitable rearrangement of these correlation functions can produce a compactly supported function, called a "kernel packet". Using a set of kernel packets as basis functions leads to a sparse representation of the covariance matrix that results in the proposed algorithm. Simulation studies show that the proposed algorithm, when applicable, is significantly superior to the existing alternatives in both the computational time and predictive accuracy.

# Summary. An optional shortened abstract.
summary: ""

tags:
- GP
- regression
- sparse matrices
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://jmlr.org/papers/volume23/21-1232/21-1232.pdf
url_code: 'https://github.com/hchen19/kernel_packet'
url_dataset: ''
url_poster: 'poster-kp.pdf'
url_project: ''
url_slides: 'slides-kp.pdf'
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
