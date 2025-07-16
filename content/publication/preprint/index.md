---
title: "Compression Method for Deep Diagonal State Space Model Based on H2 Optimal Reduction"
authors:
- Hiroki Sakamoto and Kazuhiro Sato
date: "2025-07-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Deep learning models incorporating linear SSMs have gained attention for capturing long-range dependencies in sequential data. However, their large parameter sizes pose challenges for deployment on resource-constrained devices. In this study, we propose an efficient parameter reduction method for these models by applying H2 model order reduction techniques from control theory to their linear SSM components. In experiments, the LRA benchmark results show that the model compression based on our proposed method outperforms an existing method using the Balanced Truncation, while successfully reducing the number of parameters in the SSMs to 1/32 without sacrificing the performance of the original models.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Model compression, Diagonal State Space Model, Optimal H2 Model Order Reduction

featured: true

links:
- name: link
  url: https://arxiv.org/abs/2507.10078
# url_pdf: https://arxiv.org/abs/2507.10078
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
