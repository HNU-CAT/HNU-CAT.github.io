---
title: "Safe and Reliable Distributed Fault-Tolerant Formation Control for Quadrotor Swarms"
authors:
- Yang Hu
- Zhiqiang Miao
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-0-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-0-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: This paper addresses formation control of quadrotor swarms subject to external time-varying disturbances and actuator failures, while ensuring collision avoidance. Firstly, a complete dynamics model incorporating translational movement, rotation, motor, and actuator failures was developed for each quadrotor. Then, nominal controllers for the position and attitude subsystems are designed separately to achieve formation control under ideal conditions. A higher-order sliding mode (HOSM) observer is implemented to effectively estimate and compensate for external disturbances and actuator bias faults, thereby improving the stability of the system. Next, a potential energy function-based collision avoidance mechanism is implemented to ensure inter-quadrotor collision avoidance. Furthermore, a fault detection and fault-tolerant control(FTC) method is designed to estimate the lift coefficient of actuator partial failures online in real time by employing Newtons correction method, which ensures the safe and reliable flight of the system. The stability of the closed-loop system is analyzed using Lyapunov stability theory. Finally, numerical simulations and hardware-in-the-loop (HIL) experiment results are performed to validate the approach's effectiveness and performance in quadrotor swarm formation control.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
