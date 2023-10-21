---
title: "Intelligent Maritime Surveillance Framework Driven by Fusion of Camera-Based Vessel Detection and AIS Data"
authors: 
- admin
- Yu Guo
- Yuxu Lu
- et al.

date: '2023'

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-conference"]

# Publication name and optional abbreviated publication name.
publication: "2022 IEEE 25th International Conference on Intelligent Transportation Systems"
publication_short: "ITSC"

abstract: Efficient maritime surveillance is necessary for navigation, which usually uses cameras to capture the vessels. However, the information in camera-based data is limited. In this work, we propose a novel intelligent maritime surveillance framework driven by the fusion of camera-based vessel detection and Automatic Identification System (AIS) data. Firstly, we employ a vessel detection network to get the relative positions of the vessels from the calibrated camera-based data. Meanwhile, we design a series of filters based on data completeness, detection range, and vessel course to exclude the invalid AIS data. In the end, we propose a data fusion module based on estimating the time when the vessel arrive at the specific position. According to the experiment on our collected dataset, the proposed framework performs competitively in diversified scenes. The mean absolute distance deviation of the estimation is less than 30 meters, and the accuracy of data fusion is 81.423%.

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9921786'
url_code: ''
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}
