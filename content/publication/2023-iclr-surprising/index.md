---
title: "The Surprising Effectiveness of Equivariant Models in Domains with Latent Symmetry"
authors: 
  - Dian Wang
  - admin
  - Neel Sortur
  - Lawson L.S. Wong
  - Robin Walters
  - Robert Platt

date: 2023-01-21
publishdate: ''
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Learning Representations"
publication_short: In *ICLR*, **(notable-top-25%)**

abstract: "Extensive work has demonstrated that equivariant neural networks can significantly improve sample efficiency and generalization by enforcing an inductive bias in the network architecture. These applications typically assume that the domain symmetry is fully described by explicit transformations of the model inputs and outputs. However, many real-life applications contain only latent or partial symmetries which cannot be easily described by simple transformations of the input. In these cases, it is necessary to learn symmetry in the environment instead of imposing it mathematically on the network architecture. We discover, surprisingly, that imposing equivariance constraints that do not exactly match the domain symmetry is very helpful in learning the true symmetry in the environment. We differentiate between extrinsic and incorrect symmetry constraints and show that while imposing incorrect symmetry can impede the model's performance, imposing extrinsic symmetry can actually improve performance. We demonstrate that an equivariant model can significantly outperform non-equivariant methods on domains with latent symmetries both in supervised learning and in reinforcement learning for robotic manipulation and control problems."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

links:
- name: Website
  url: 'https://pointw.github.io/extrinsic_page/'

url_pdf: 'https://arxiv.org/abs/2211.09231'
url_code: 'https://github.com/pointW/extrinsic_equi'
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: 'https://www.youtube.com/watch?v=US4uWndGx9I'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 1
  caption: ''
  focal_point: "Smart"
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
