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
# author_notes:'' 

date: "2020-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE International Conference on Computer Communications (INFOCOM 2023)
publication_short: INFOCOM 2023

abstract: The ORAM is a cryptographic protocol that hides client access patterns from leaking. Prior works suffer the cost of logarithmic communication blowup or server-side computing overhead. In this paper, we present an ORAM scheme named Jump-ORAM that achieves constant bandwidth blowup without server-side computing overhead. To achieve above goal, we map a request for one block into the corresponding request for a given number of blocks. To implement above mapping, we first propose a data structure named position map to convert the accessed block's logical-ID into its physical-ID, and then design a selection algorithm to map the accessed block's physical-ID to a given number of physical-IDs. To ensure the security of the Jump-ORAM, we periodically and randomly rewrite accessed blocks back to the server without leaking their new assigned physical-IDs. Specifically, we propose a data structure named the data cache to temporarily store accessed blocks. We design a swap algorithm to rewrite accessed blocks back to the server without leaking their new assigned physical-IDs. We proved that our scheme is secure under a statistical model. We compared Jump-ORAM's performance with its counterparts. Experimental results demonstrate the efficiency of Jump-ORAM.

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
