---
title: "Where Should Inverter-Based Resources Be Located in Power Networks?"
authors:
- admin
- Chi Kong TSE
date: "2023-12-19T00:00:00Z"
doi: "10.1109/TCSI.2023.3336069"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-05 T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal-Article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In this paper, we investigate the influence of the locations of inverter-based resources (IBRs) on the synchronization performance of power networks. We propose two indexes to measure the distribution of inertia in power networks, considering the distribution of control parameters and the topological factors jointly. The first index is the inertia clustering coefficient, which measures how densely the neighbors of each node are connected in a power network. The second index is the inertia centrality coefficient, which captures whether the distribution of inertia in a power network is centralized or peripheral. We characterize synchronous generators (SGs), grid-following inverters (GFLs), and grid-forming inverters (GFMs) by their damping and inertial properties. We evaluate the synchronization performance of the system after disturbances by adopting the settling time and hertz-sec metric. Both the frequency response and the trajectories of eigenvalues show that the location of IBRs has a significant impact on the synchronization performance of the system. Monte Carlo simulations are conducted on two test networks, the results of the IEEE 30-, 57-, and 118-bus systems demonstrate a strong correlation between synchronization performance and the two inertia distribution indexes. 

# Summary. An optional shortened abstract.
summary: Analyzing the synchronization performance of IBRs using compelex network indexes.

tags:
- complex network
- power systems
- inverter-based resources
- synchronization
featured: false

links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10339867
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

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

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

## Author Comment

I took the risk of applying complex network analysis to the synchronization performance of inverter-based resources. I made several simplifications to highlight the key issues. 🦄✨**