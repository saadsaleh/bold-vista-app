---
title: "An example preprint / working paper"
authors:
- admin
- Anouk Goossens
- Sunny Shu
- Tamalika Banerjee
- Boris Koldehofe
date: "2019-04-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: | 
Current network functions consume a significant amount of energy and lack the capacity to support more expressive learning models like neuromorphic functions. The major reason is the underlying transistor-based components that require continuous energy-intensive data movements between the storage and computational units. In this research, we propose the use of a novel component, called Memristor, which can colocalize computation and storage, and provide computational capabilities. Building on memristors, we propose the concept of match-compute processing for supporting energy efficient network functions. Considering the analog processing of memristors, we propose a Probabilistic Content Addressable Memory (pCAM) abstraction which can provide analog match functions. pCAM provides deterministic and probabilistic outputs
depending upon the closeness of match of an incoming query with the specified network policy. pCAM uses a crossbar array for line rate matrix multiplications on the match outputs. We proposed a match-compute packet processing architecture and developed the programming abstractions for a baseline network function, i.e., Active Queue Management, which drops packets based upon the higher-order derivatives of sojourn times and buffer sizes. The analysis of match-compute processing over a physically fabricated memristor chip showed only 0.01 fJ/bit/cell of energy consumption, which is 50 times less than the traditional match-action processing.

# Summary. An optional shortened abstract.
summary: We propose a memristor-based analog match-compute architecture for energy-efficient, expressive network functions, achieving 50× lower energy than digital systems.

tags:
- Artificial Intelligence
- Analog Computing
- Cognitive functions
- Neuromorphic computing

featured: true

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
- type: DOI
  provider: DOI
  id: https://doi.org/10.1109/INFOCOM52122.2024.10621228



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---

