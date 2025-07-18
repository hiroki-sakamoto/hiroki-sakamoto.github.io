---
title: "Data-driven h2 model reduction for linear discrete-time systems"
authors:
- admin
- Kazuhiro Sato
date: "2025-06-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2025-07-13T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "conditionally accepted for publication in *IEEE Transactions on Automatic Control*"
publication_short: ""

abstract: We present a new framework of h2 optimal model reduction for linear discrete-time systems. Our main contribution is to create optimal reduced-order models in the h2-norm sense directly from the measurement data alone, without using the information of the original system. In particular, we focus on the fact that the gradient of the h2 model reduction problem is expressed using the discrete-time Lyapunov equation and the discrete-time Sylvester equation, and derive the data-driven gradient. In the proposed algorithm, the initial point can be chosen as the output of the existing data-driven methods. In numerical experiments, we demonstrate that, for a modeling task in neuroscience, our method constructs a reduced-order model that outperforms DMDc in terms of the h2-norm.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Data-driven model order reduction, Discretetime dynamical systems
featured: true

links:
- name: "link"
  url: "https://arxiv.org/abs/2401.05774"
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects: []

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
