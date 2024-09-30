---
title: "The Impact of Inverter-Based Resources (IBRs) on Cascading Failures in Power Systems"
authors:
- admin
- Chi Kong TSE
- Ming YI
date: "2023-12-19T00:00:00Z"
doi: "10.1109/TPWRS.2023.3339684"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-05 T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Journal-Article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: In this study, we evaluate the impact of frequency control and the penetration of inverter-based resources (IBRs) on cascading failures in power systems. The modeling of controllers for IBRs requires obtaining realistic state information during cascading failure processes. However, cascading failure events can alter system topologies and the power flow Jacobian, leading to unsolvable power flow even when an equilibrium point exists. To address this, we propose a model that tracks the steady-state voltage profiles across successive cascade generations. This model enables the incorporation of droop controllers for IBRs into the cascading failure model. Additionally, it allows for capturing the effects of the interaction between local primary frequency control and system-level frequency control on cascading failures. Numerical experiments conducted on the IEEE 118- and 300-bus systems demonstrate the effectiveness of increasing primary frequency control reserve in mitigating power outages. However, increasing the droop control coefficients, which aim to enhance system robustness, results in larger power outage sizes.

# Summary. An optional shortened abstract.
summary: Milstone work for incorporating inverter-based resources into cascading failure models in power systems.

tags:
- cascading failures
- power systems
- inverter-based resources
- voltage collapse
featured: false

links:
- name: Link
  url: https://ieeexplore.ieee.org/document/10342811
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

This is a milstone work for incorporating inverter-based resources into cascading failure models in power systems, which also ignite numerous research possibilities. 🦄✨**