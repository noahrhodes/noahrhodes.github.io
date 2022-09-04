---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: 'University of Wisconsin-Madison'
    company_url: 'https://www.wisc.edu'
    company_logo: wisc
    location: Wisconsin
    date_start: '2019-09-01'
    date_end: ''
    description:  |2-
      - Develop methods and software tools for research in power systems optimization modeling
      - Research focus in modeling decisions for topology change, such as grid restoration and public saftey power shutoffs
      - Projects include PowerModelsRestoration.jl, PowerModelsWildfire.jl, PowerPlots.jl, and PGLib.jl


  - title: Research Intern
    company: Los Alamos National Laboratory
    company_url: 'https://www.lanl.gov/'
    company_logo: lanl
    location: New Mexico
    date_start: '2019-05-01'
    date_end: ''
    description: |2-
        - Develop optimization framework for power grid restoration
        - Create algorithm heuristics for grid restoration planning
        - Analyze test systems for validation on HPC system

  - title: Teaching Assistant
    company: 'University of Wisconsin-Madison'
    company_url: 'https://www.wisc.edu'
    company_logo: wisc
    location: Wisconsin
    date_start: '2022-01-18'
    date_end: '2022-05-07'
    description: |2-
         Teaching Assistant for ECE 524: Introduction to Optimization

  - title: Research Intern
    company: National Renewable Energy Laboratory
    company_url: 'https://www.nrel.gov/'
    company_logo: nrel
    location: Colorado
    date_start: '2018-08-01'
    date_end: '2018-12-23'
    description: |2-
        - Develop standardized model for mixed AC and DC microgrid analysis
        - Present a report to the Department of Energy on potential energy savings

design:
  columns: '2'
---
