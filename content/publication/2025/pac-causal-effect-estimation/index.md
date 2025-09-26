---
title: "Probably Approximately Correct High-dimensional Causal Effect Estimation Given a Valid Adjustment Set"
authors:
- admin
- Davin Choo
- Arnab Bhattacharyya
- David Sontag
date: "2025-05-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "The Conference on Causal Learning and Reasoning"
publication_short: "CLeaR 2025"

abstract: Accurate estimates of causal effects play a key role in decision-making across applications such as healthcare, economics, and operations. In the absence of randomized experiments, a common approach to estimating causal effects uses *covariate adjustment*. In this paper, we study covariate adjustment for discrete distributions from the PAC learning perspective, assuming knowledge of a valid adjustment set $\bZ$, which might be high-dimensional. Our first main result PAC-bounds the estimation error of covariate adjustment by a term that is exponential in the size of the adjustment set; it is known that such a dependency is unavoidable even if one only aims to minimize the mean squared error. Motivated by this result, we introduce the notion of an \emph{$\eps$-Markov blanket}, give bounds on the misspecification error of using such a set for covariate adjustment, and provide an algorithm for $\eps$-Markov blanket discovery; our second main result upper bounds the sample complexity of this algorithm. Furthermore, we provide a misspecification error bound and a constraint-based algorithm that allow us to go beyond $\eps$-Markov blankets to even smaller adjustment sets. Our third main result upper bounds the sample complexity of this algorithm, and our final result combines the first three into an overall PAC bound. Altogether, our results highlight that one does not need to perfectly recover causal structure in order to ensure accurate estimates of causal effects.
 

# Summary. An optional shortened abstract.

tags:
- Causal Structure Learning 
featured: true

links:
url_pdf: https://arxiv.org/pdf/2411.08141?
url_code: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

