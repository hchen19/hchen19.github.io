---
title: 'From Deep Additive Kernel Learning to Last-Layer Bayesian Neural Networks via Induced Prior Approximation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Wenyuan Zhao
  - admin
  - Tie Liu
  - Rui Tuo
  - Chao Tian
  

# Author notes (optional)
author_notes:
  - '' #'Equal contribution'
  - '' #'Equal contribution'
  - ''
  - ''
  - ''

date: '2025-01-05T00:00:00Z'
doi: ''
math: true

# Schedule page publish date (NOT publication's date).
publishDate: '2025-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 28th International Conference on Artificial Intelligence and Statistics (AISTATS) 2025*, Mai Khao, Thailand. PMLR: Volume 258."
publication_short: International Conference on Artificial Intelligence and Statistics (AISTATS) 2025

abstract: With the strengths of both deep learning and kernel methods like Gaussian Processes (GPs), Deep Kernel Learning (DKL) has gained considerable attention in recent years. From the computational perspective, however, DKL becomes challenging when the input dimension of the last-layer GP is high. To address this challenge, we propose the Deep Additive Kernel (DAK) model, which incorporates i) an additive structure for the last-layer GP; and ii) induced prior approximation for each GP component. This naturally leads to a last-layer Bayesian neural network (BNN) architecture. The proposed method enjoys the interpretability of DKL as well as the computational advantages of BNN. Empirical results show that the proposed approach outperforms state-of-the-art DKL methods in both regression and classification tasks.

# Summary. An optional shortened abstract.
summary: ""

tags: #[]
- GP
- deep kernel learning
- Bayesian neural network

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2502.10540'
url_code: 'https://github.com/warrenzha/dak2bnn'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://proceedings.mlr.press/v258/zhao25d.html'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Wenyuan Zhao**](https://github.com/warrenzha)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" #example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->