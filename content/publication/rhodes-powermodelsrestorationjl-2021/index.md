---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PowerModelsRestoration.jl: An open-source framework for exploring power network
  restoration algorithms'
subtitle: ''
summary: ''
authors:
- admin
- David M. Fobes
- Carleton Coffrin
- Line Roald
tags:
- AC power flow
- Convex optimization
- Julia language
- N-k
- Nonlinear optimization
- Open-source
- Power system restoration
categories: []
date: '2021-01-01'
lastmod: 2022-09-03T11:24:14-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
# - PMR

publishDate: '2022-09-03T16:37:30.557013Z'
publication_types:
- '1'
abstract: With the escalating frequency of extreme grid disturbances, such as natural
  disasters, comes an increasing need for efficient recovery plans. Algorithms for
  optimal power restoration play an important role in developing such plans, but also
  give rise to challenging mixed-integer nonlinear optimization problems, where tractable
  solution methods are not yet available. To assist in research on such solution methods,
  this work proposes PowerModelsRestoration, a flexible, open-source software framework
  for rapidly designing and testing power restoration algorithms. PowerModelsRestoration
  constructs a mathematical modeling layer for formalizing core restoration tasks
  that can be combined to develop complex workflows and high performance heuristics.
  The efficacy of the proposed framework is demonstrated by proof-of-concept studies
  on three established cases from the literature, focusing on single-phase positive
  sequence network models. The results demonstrate that PowerModelsRestoration reproduces
  the established literature, and for the first time provide an analysis of restoration
  with nonlinear power flow models, which have not been previously considered.
publication: '*Power Systems Computational Conference*'
doi: 10.1016/j.epsr.2020.106736
---
