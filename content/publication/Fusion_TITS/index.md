---
title: "Asynchronous Trajectory Matching-Based Multimodal Maritime Data Fusion for Vessel Traffic Surveillance in Inland Waterways"
authors: 
- Yu Guo
- Ryan Wen Liu
- admin
- Yuxu Lu
- Fenghua Zhu
- Yisheng Lv

date: '2023-03-01'

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Intelligent Transportation Systems"
publication_short: "IEEE T-ITS"

abstract: The automatic identification system (AIS) and video cameras have been widely exploited for vessel traffic surveillance in inland waterways. The AIS data could provide vessel identity and dynamic information on vessel position and movements. In contrast, the video data could describe the visual appearances of moving vessels without knowing the information on identity, position, movements, etc. To further improve vessel traffic surveillance, it becomes necessary to fuse the AIS and video data to simultaneously capture the visual features, identity, and dynamic information for the vessels of interest. However, the performance of AIS and video data fusion is susceptible to issues such as data spatial difference, message asynchronous transmission, visual object occlusion, etc. In this work, we propose a deep learning-based simple online and real-time vessel data fusion method (termed DeepSORVF). We first extract the AIS-and video-based vessel trajectories, and then propose an asynchronous trajectory matching method to fuse the AIS-based vessel information with the corresponding visual targets. In addition, by combining the AIS-and video-based movement features, we also present a prior knowledge-driven anti-occlusion method to yield accurate and robust vessel tracking results under occlusion conditions. To validate the efficacy of our DeepSORVF, we have also constructed a new benchmark dataset (termed FVessel) for vessel detection, tracking, and data fusion. It consists of many videos and the corresponding AIS data collected in various weather conditions and locations. The experimental results have demonstrated that our method is capable of guaranteeing high-reliable data fusion and anti-occlusion vessel tracking.

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/10159572
url_code: 'https://github.com/gy65896/DeepSORVF'
url_dataset: 'https://github.com/gy65896/FVessel'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}
