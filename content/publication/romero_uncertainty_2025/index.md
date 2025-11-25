---
title: "Uncertainty Quantification in HSI Reconstruction using Physics-Aware Diffusion Priors and Optics-Encoded Measurements"
authors:
  - Juan Romero
  - Qiang Fu
  - Matteo Ravasi
  - Wolfgang Heidrich
date: 2025-11-25
doi: "10.48550/arXiv.2511.18473"
publication_types: - article-journal
publication: "arXiv"
publication_short: "arXiv"
arxiv_id: "2511.18473"
abstract: >
  Hyperspectral image reconstruction from a compressed measurement is a highly ill-posed inverse problem. Current data-driven methods suffer from hallucination due to the lack of spectral diversity in existing hyperspectral image datasets, particularly when they are evaluated for the metamerism phenomenon. In this work, we formulate hyperspectral image (HSI) reconstruction as a Bayesian inference problem and propose a framework, HSDiff, that utilizes an unconditionally trained, pixel-level diffusion prior and posterior diffusion sampling to generate diverse HSI samples consistent with the measurements of various hyperspectral image formation models. We propose an enhanced metameric augmentation technique using region-based metameric black and partition-of-union spectral upsampling to expand training with physically valid metameric spectra, strengthening the prior diversity and improving uncertainty calibration. We utilize HSDiff to investigate how the studied forward models shape the posterior distribution and demonstrate that guiding with effective spectral encoding provides calibrated informative uncertainty compared to non-encoded models. Through the lens of the Bayesian framework, HSDiff offers a complete, high-performance method for uncertainty-aware HSI reconstruction. Our results also reiterate the significance of effective spectral encoding in snapshot hyperspectral imaging.
featured: true

tags:
  - Hyperspectral imaging
  - Diffusion models
  - Uncertainty quantification
  - Bayesian inference
  - Metamerism

url_pdf: "http://arxiv.org/pdf/2511.18473"

---

