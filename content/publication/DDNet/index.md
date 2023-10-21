---
title: "Double Domain Guided Real-Time Low-Light Image Enhancement for Ultra-High-Definition Transportation Surveillance"
authors: 
- admin
- Ryan Wen Liu
- Yuan Gao
- Yu Guo
- Fenghua Zhu
- Feiyue Wang

date: '2023'

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Arxiv"
publication_short: ""

abstract: Real-time transportation surveillance is an essential part of the intelligent transportation system (ITS). However, images captured under low-light conditions often suffer the poor visibility with types of degradation, such as noise interference and vague edge features, etc. With the development of imaging devices, the quality of the visual surveillance data is continually increasing, like 2K and 4K, which has more strict requirements on the efficiency of image processing. To satisfy the requirements on both enhancement quality and computational speed, this paper proposes a double domain guided real-time low-light image enhancement network (DDNet) for ultra-high-definition (UHD) transportation surveillance. Specifically, we design an encoder-decoder structure as the main architecture of the learning network. In particular, the enhancement processing is divided into two subtasks (i.e., color enhancement and gradient enhancement) via the proposed coarse enhancement module (CEM) and LoG-based gradient enhancement module (GEM), which are embedded in the encoder-decoder structure. It enables the network to enhance the color and edge features simultaneously. Through the decomposition and reconstruction on both color and gradient domains, our DDNet can restore the detailed feature information concealed by the darkness with better visual quality and efficiency. The evaluation experiments on standard and transportation-related datasets demonstrate that our DDNet provides superior enhancement quality and efficiency compared with the state-of-the-art methods. Besides, the object detection and scene segmentation experiments indicate the practical benefits for higher-level image analysis under low-light environments in ITS.

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2309.08382
url_code: 'https://github.com/QuJX/DDNet'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: True

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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
