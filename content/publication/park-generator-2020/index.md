---
title: "Generator Surgery for Compressed Sensing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors: 
- Jung Yeon Park
- Niklas Smedemark-Margulies
- Max Daniels
- Rose Yu
- Jan-Willem van de Meent
- Paul Hand

date: "2020-10-23T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-23T22:17:22.420747Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*NeurIPS 2020 Workshop on Deep Learning and Inverse Problems*"
publication_short: In *NeurIPS Workshop 2020*

abstract: "Recent work has explored the use of generator networks with low latent dimension as signal priors for image recovery in compressed sensing. However, the recovery performance of such models is limited by high representation error. We introduce a method to reduce the representation error of such generator signal priors by cutting one or more initial blocks at test time and optimizing over the resulting higher- dimensional latent space. Experiments demonstrate significantly improved recovery for a variety of architectures. This approach also works well for out-of-training- distribution images and is competitive with other state-of-the-art methods. Our experiments show that test-time architectural modifications can greatly improve the recovery quality of generator signal priors for compressed sensing."

tags: 
- NeurIPS 2020

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: arXiv
  url: 'https://arxiv.org/pdf/2102.11163.pdf'

url_pdf: 'https://openreview.net/forum?id=s2EucjZ6d2s'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  placement: 1
  caption: ''
  focal_point: "Center"
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
