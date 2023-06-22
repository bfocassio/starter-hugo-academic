---
title: Linear Jacobi-Legendre expansion of the charge density for machine learning-accelerated electronic structure calculations
summary: Fingerprint coding. Data transformation. Regression Analysis. Deployment of regression model to application.
tags:
  - Data transformation
  - Fingerprint coding
  - Machine Learning
  - Regression Analysis
  - Deployment of final model to application
date: '2023-06-22T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://doi.org/10.1038/s41524-023-01053-0'

image:
  caption: ''
  focal_point: Smart

links:
  - icon: 
    icon_pack: fab
    name: Check publication
    url: https://doi.org/10.1038/s41524-023-01053-0
  - icon: 
    icon_pack: fab
    name: Check data on Zenodo
    url: https://doi.org/10.5281/zenodo.7922012
  - icon: github
    icon_pack: fab
    name: Check GitHub tutorial
    url: https://github.com/bfocassio/MLDensity_tutorial
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Kohn–Sham density functional theory (KS-DFT) is a powerful method to obtain key materials’ properties, but the iterative solution of the KS equations is a numerically intensive task, which limits its application to complex systems. To address this issue, machine learning (ML) models can be used as surrogates to find the ground-state charge density and reduce the computational overheads. We develop a grid-centred structural representation, based on Jacobi and Legendre polynomials combined with a linear regression, to accurately learn the converged DFT charge density. This integrates into a ML pipeline that can return any density-dependent observable, including energy and forces, at the quality of a converged DFT calculation, but at a fraction of the computational cost. Fast scanning of energy landscapes and producing starting densities for the DFT self-consistent cycle are among the applications of our scheme.