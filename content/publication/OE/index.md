---
title: "Improving maritime traffic surveillance in inland waterways using the robust fusion of AIS and visual data"
authors: 
- admin
- Ryan Wen Liu
- Yu Guo
- Yuxu Lu
- Jianlong Su
- Peizheng Li

date: '2023-06-01'

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Ocean Engineering"
publication_short: "OE"

abstract: To guarantee vessel traffic safety in inland waterways, the automatic identification system (AIS) and shore-based cameras have been widely adopted to monitor moving vessels. The AIS data could provide the unique maritime mobile service identity (MMSI), position coordinates (i.e., latitude and longitude), course over ground, and speed over ground for the vessels of interest. In contrast, the cameras could directly display the visual appearance of vessels but fail to accurately grasp the vessels’ identity information and motion parameters. In this paper, we propose to improve the maritime traffic surveillance in inland waterways using the robust fusion of AIS and visual data. It is able to obtain more accurate vessel tracking results and kinematic characteristics. In particular, to robustly track the visual vessels under complex scenarios, we first propose an anti-occlusion vessel tracking method based on the simple online and real-time tracking with a deep association metric (DeepSORT) method. We then preprocess and predict the vessel positions to obtain synchronous AIS and visual data. Before the implementation of AIS and visual data fusion, the AIS position coordinates in the geodetic coordinate system will be projected into the image coordinate system via the coordinate transformation. A multi-feature similarity measurement-based Hungarian algorithm is finally proposed to robustly and accurately fuse the AIS and visual data in the image coordinate system. For the sake of repeating fusion experiments, we have also presented a new multi-sensor dataset containing AIS data and shore-based camera imagery. The quantitative and qualitative experiments show that our fusion method is capable of improving the maritime traffic surveillance in inland waterways. It can overcome the vessel occlusion problem and fully utilizes the advantages of multi-source data to promote the maritime surveillance, resulting in enhanced vessel traffic safety and efficiency.
tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0029801823005826
url_code: 'https://github.com/QuJX/AIS-Visual-Fusion'
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
