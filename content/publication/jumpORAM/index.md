---
title: "Jump-ORAM: An ORAM Scheme Achieving Constant Bandwidth Blowup Without Server-side Computing Overhead"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rui Li
- Huafeng Ruan

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2022-08-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the ECML-PKDD Workshop on Deep Continuous-Discrete Machine Learning (DeCoDeML 2020)
publication_short: DeCoDeML Workshop at ECML-PKDD 2020

abstract: Weighted model integration (WMI) is an appeal-ing framework for probabilistic inference, it allows for expressing the complex dependencies in real-world problems, where variables are both continuous and discrete, via the language of Satisfiability Modulo Theories (SMT), as well as to compute probabilistic queries with complex logical and arithmetic constraints. Yet, existing WMI solvers are not ready to scale to these problems.They either ignore the intrinsic dependency structure of the problem entirely, or they are limited to overly restrictive structures. To narrow this gap,we derive a factorized WMI computation enabling us  to  devise  a  scalable  WMI  solver  based  onmessage passing, called MP-WMI. Namely, MP-WMI is the first WMI solver that can (i) perform exact inference on the full class of tree-structuredWMI problems, and (ii) perform inter-query amortization, e.g., to compute all marginal densities simultaneously.  Experimental results show that our solver dramatically outperforms the existingWMI solvers on a large set of benchmarks.

# Summary. An optional shortened abstract.
summary: DeCoDeML Workshop at ECML-PKDD 2020

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/UCLA-StarAI/recoin'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'slides/ecml20-slides.pdf'
url_source: ''
url_video: 'https://youtu.be/M9Hp6ymsxmI'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Primal Graphs"
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
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
