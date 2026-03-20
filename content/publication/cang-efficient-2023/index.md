---
title: An efficient method for design of lattice core sandwich structures with superior
  buckling strength under compression
authors:
- Mingpei Cang#
- Lei Zhang#
- Yiqiang Wang*
- Jin Fu
- Zhen Luo
- Zhan Kang
- Ming Wang Fu
- Michael Yu Wang
date: '2023-01-01'
publishDate: '2025-07-24T15:47:37.123220Z'
publication_types:
- article-journal
publication: '*Engineering Optimization*'
doi: 10.1080/0305215X.2022.2163239
summary: We proposed an efficient strut-level design method for lattice core sandwich structures under compression. By identifying transferable buckling-resistant non-uniform strut profiles and directly mapping them into different lattice topologies, we achieved 16.63%–20.89% numerical buckling-load gains and at least 10% experimental compressive-strength improvement.
abstract: Buckling failure is a major concern in lightweight lattice core sandwich
  structures (LCSSs). This study proposes an efficient method for designing LCSSs
  with superior buckling strength under uniaxial compression. In this approach, the
  buckling-resistant non-uniform shapes of single struts with different slenderness
  and inclination are first identified, and then they are directly used to replace
  uniform struts in LCSSs. This method can save considerable design time compared
  to conventional methods, which require conducting optimizations on entire LCSSs.
  Numerical results demonstrate that four designed representative non-uniform LCSSs
  can gain over 15% improvement in buckling strength compared to their counterpart
  uniform LCSSs. This improvement is even comparable to the solutions from optimizations
  on entire LCSSs. Two LCSSs with non-uniform struts are 3D printed, and the test
  results validate at least 10% improvement in compressive strength. Based on the
  proposed method, various LCSSs with superior buckling strength could be designed
  for different loadings.
links:
- name: URL
  url: https://www.tandfonline.com/doi/full/10.1080/0305215X.2022.2163239
projects:
- R01
---

## Problem
Lattice core sandwich structures are lightweight and high-performance, but slender struts are vulnerable to buckling under compression. Conventional full-structure optimization can improve stability, yet it is computationally expensive and hard to reuse across different lattice topologies.

## Method
This work proposes an efficient strut-level design strategy:

- Identify buckling-resistant non-uniform strut shapes under different slenderness ratios, inclination angles, and buckling modes.
- Represent smooth strut geometry using a Fourier-series-based model.
- Directly replace uniform struts in target lattices with these non-uniform profiles, avoiding repeated full-core optimization.

The method is demonstrated on Kagome, BCC, BCCZ, and six-fold lattice core sandwich structures.

## Key results

- Non-uniform designs achieved **16.63%–20.89%** higher critical buckling load than uniform counterparts in numerical studies.
- The gains were comparable to full-core optimization solutions, with much lower design effort.
- 3D-printed BCC and six-fold specimens showed **at least 10%** compressive-strength improvement in uniaxial compression tests.

## Impact
This study provides a practical route to rapidly designing buckling-resistant lattice-core sandwich structures by transferring optimized strut shapes across different architectures. It improves design efficiency while preserving high structural performance for additive-manufacturing applications.

## My contribution in this work

### Methodology and Investigation
- Geometric modelling of lattice structures with non-uniform struts based on implicit function.
- Linear buckling analysis of lattice core sandwich panels.
- Optimization pipeline of non-uniform cross-sections of struts to maximize linear buckling strength.
- Nonlinear analysis of the lattice core sandwich structures.
- Experiment design of quasi-static uniaxial compression test.

### Writing
- Original draft.
- Review & editing.
