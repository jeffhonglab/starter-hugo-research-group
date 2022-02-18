---
title: "Option Pricing By Neural Stochastic Differential Equations: A Simulation-optimization Approach"
authors:
- Wang, S. and L. J. Hong
date:
doi: ""

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "#"
date_end: "#"
all_day: true

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 2021 Winter Simulation Conference, forthcoming
publication_short: Proceedings of the 2021 Winter Simulation Conference, forthcoming

abstract: Classical option pricing models rely on prior assumptions made on the dynamics of the underlying assets and the rationality of the market. While empirical evidence showed that these models may explain the option prices to certain extend, their performance may be poor when the actual situation deviates from the assumptions. Neural network models are capable of learning the underlying relationship through the data without prior assumptions. However, to avoid over-fitting, these models often require massive amount of data, which are typically not available for option pricing problems. In this paper we propose a new model by integrating neural networks as components to a classical option pricing model, thus significantly increasing the model flexibility while requiring only a reasonable amount of data. We further show that the training of the model, also known as the calibration in the ﬁeld of financial engineering, may be formulated into a simulation optimization problem, and it may be solved in a way that is compatible to the training of neural networks. Preliminary numerical results show that our approach works well.

# Summary. An optional shortened abstract.
summary:


featured: true

links:
# - name: Preprint
#   url: https://www.researchgate.net/publication/351599800_Option_pricing_by_stochastic_differential_equations_A_simulation_optimization_approach
url_pdf: "/uploads/papers/conferences/WangHongWSC2021.pdf"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ""


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Simulation Optimization
- Monte Carlo methods in financial engineering

tags:
- Monte Carlo methods in financial engineering
- Emerging areas in stochastic simulation


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
