---
title: Robust Regularized Regression Using a Modified ADMM
authors:
- N. Luiken
- M. Ravasi
- J. Romero
date: '2022-06-01'
publishDate: '2025-08-07T10:39:03.350148Z'
publication_types:
- paper-conference
publication: '*European Association of Geoscientists & Engineers*'
doi: 10.3997/2214-4609.202210263
abstract: Summary Geophysical data are notoriously contaminated by noise, some of
  which may behave as outlier to the rest of the data. Least absolute deviations can
  successfully handle such outliers, however it requires the L1-norm of the data to
  be minimized, which is much harder to minimize than the L2- norm commonly used in
  least-squares. The problem lies in the non-differentiability of the L1-norm, which
  prohibits the efficient use of gradient based methods. In recent years, algorithms
  based on the proximal operator have gained great popularity in the mathematical
  community, due to their ability to efficiently minimize objective function consisting
  of both a smooth and a non-smooth part. The Alternating Direction Method of Multipliers
  (ADMM) is one such algorithms that is able to solve a large class of problems. In
  this work, we present a new ADMM-type solver that can handle objective functions
  that are the sum of an L1 data fidelity term and an L1 regularization term. We apply
  our algorithm to the problem of seismic deblending and compare it against the IRLS
  method of Ibrahim and Sacchi (2014) .
links:
- name: URL
  url: https://www.earthdoc.org/content/papers/10.3997/2214-4609.202210263
---
