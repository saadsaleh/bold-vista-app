---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Boris Koldehofe

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 22nd ACM Workshop on Hot Topics in Networks*
publication_short: In *ACM HotNets*

abstract: Current network functions build heavily on fixed programmed rules and lack capacity to support more expressive learning models, e.g. brain-inspired Cognitive computational models using neuromorphic computations. The major reason for this shortcoming is the huge energy consumption and limitation in expressiveness by the underlying TCAM-based digital packet processors. In this research, we show that recent emerging technologies from the analog domain have a high potential in supporting network functions with energy efficiency and more expressiveness, so called cognitive functions. We propose an analog packet processing architecture building on a novel technology named Memristors. We develop a novel analog match-action memory called Probabilistic Content-Addressable Memory (pCAM) for supporting deterministic and probabilistic match functions. We develop the programming abstractions and show the support of pCAM for an active queue management-based analog network function. The analysis over an experimental dataset of a memristor chip showed only 0.01 fJ/bit/cell of energy consumption for corresponding analog computations which is 50 times less than digital computations.

# Summary. An optional shortened abstract.
summary: We propose an energy-efficient analog packet processor using memristor-based pCAM to enable cognitive network functions. It supports both deterministic and probabilistic matching and consumes 50× less energy than digital systems.

tags:
  - Artificial Intelligence
  - Cognitive network functions
  - Neuromorphic Computing
  - Analog Computing

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: https://doi.org/10.1145/3626111.3628192

# Custom links
links:
  - type: DOI
    url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: ""
---
