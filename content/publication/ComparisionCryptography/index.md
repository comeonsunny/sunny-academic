---
title: "RC5-CBC: Best Matching Combination of Block Cipher and Model of Operation for Implementing ORAM Schemes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Huafeng Ruan

# Author notes (optional)
# author_notes:'' 

date: "2022-08-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2023 2nd International Conference on Cryptography, Network Security and Communication Technology
publication_short: CNSCT 2023

abstract: The encryption and decryption time of semantically secure encryption techniques have a great influence on the total end-to-end delay of an ORAM scheme. However, to the best of our knowledge, there is no work to study the impacts of combinations of block cipher and common model of operation on implementing semantically secure encryption techniques by comparing and analysing their execution time. This paper examines the running time of commonly used combinations of block cipher and model of operation to find the most matchable one for an ORAM scheme. We first selected the candidates of symmetric block encryption algorithms based on the existing block ciphers included in the LibTomCrypt, a popular cryptography toolkit. We second designed a comprehensive experiment in terms of prominent application scenarios of ORAM. We finally analysed the experimental results and found that the encryption algorithm of RC5-CBC outperforms others. In the end, we conclude that the RC5-CBC is the most matchable combination of block cipher and model of operation for implementing an ORAM scheme.
# Summary. An optional shortened abstract.
summary: Accepted by CNSCT 2023

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/comeonsunny/Comparision-of-Combinations-of-Block-Cipher-and-its-models-of-operation-'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
