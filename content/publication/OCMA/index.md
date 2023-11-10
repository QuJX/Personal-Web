---
title: "Deep learning-driven surveillance quality enhancement for maritime management promotion under low-visibility weathers"
authors: 
- admin
- Yuan Gao
- Yuxu Lu
- Wenyu Xu
- Ryan Wen Liu

date: '2023-04-01'

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Ocean & Coastal Management"
publication_short: "OCMA"

abstract: Visual sensors are widely employed for real-time maritime surveillance. But they always suffer from some low-visibility problems, typically low light and haze, which greatly reduce the effectiveness of maritime management. In practical applications, the most common strategy is using separate networks to overcome different low-visibility problems. It needs large space for parameter storage. Besides, when the weather changes, the enhancement methods need to be toggled artificially, and the enhancement effect is unsatisfactory due to the lack of maritime dataset. To tackle these problems, we designed a learned parameter sharing (LPS)-based versatile visibility enhancement network (LPSNet) and trained it on the synthetic maritime dataset. It enhances the quality of captured surveillance data under both low-light and hazy environments via a versatile model. Due to the LPS between different low-visibility enhancement tasks, the proposed network performs better on the mutual problems, like noise suppression and detail preservation. Therefore, our LPSNet achieves superior enhancement effect on both low-light enhancement and dehazing. Besides, the running time is shorter than most of the previous methods, which can enhance 800 × 600 images over 18 FPS. Moreover, the comparison experiment on vessel detection task indicates the benefits of the proposed method on maritime management promotion under low-visibility weathers. 

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0964569123000030
url_code: 'https://github.com/YuanGao-YG/LPSNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}
