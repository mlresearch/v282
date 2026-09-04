---
title: 'BiEquiFormer: Bi-Equivariant Representations for Global Point Cloud Registration'
abstract: The goal of this paper is to address the problem of \textit{global} point
  cloud registration (PCR) i.e., finding the optimal alignment between point clouds
  irrespective of the initial poses of the scans. This problem is notoriously challenging
  for classical optimization methods due to computational constraints. First, we show
  that many state-of-the-art deep learning methods suffer from huge performance degradation
  when the point clouds are arbitrarily placed in space. We propose that \textit{equivariant
  deep learning} should be utilized for solving this task and we characterize the
  specific type of bi-equivariance of PCR. Then, we design BiEquiformer a novel and
  scalable \textit{bi-equivariant} pipeline i.e. equivariant to the independent transformations
  of the input point clouds. While a naive approach would process the point clouds
  independently we design expressive bi-equivariant layers that fuse the information
  from both point clouds. This allows us to extract high-quality superpoint correspondences
  and in turn, robust point-cloud registration. Extensive comparisons against state-of-the-art
  methods show that our method achieves comparable performance in the canonical setting
  and superior performance in the robust setting in both the 3DMatch and the challenging
  low-overlap 3DLoMatch dataset.
section: NeurReps 2024
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pertigkiozoglou26a
month: 0
tex_title: 'BiEquiFormer: Bi-Equivariant Representations for Global Point Cloud Registration'
firstpage: 1136
lastpage: 1161
page: 1136-1161
order: 1136
cycles: false
bibtex_author: Pertigkiozoglou, Stefanos and Chatzipantazis, Evangelos and Daniilidis,
  Kostas
author:
- given: Stefanos
  family: Pertigkiozoglou
- given: Evangelos
  family: Chatzipantazis
- given: Kostas
  family: Daniilidis
date: 2026-09-04
address:
container-title: Proceedings of the 4th (2025) and 3rd (2024) NeurIPS Workshops on
  Symmetry and Geometry in Neural Representations
volume: '282'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 9
  - 4
pdf: https://raw.githubusercontent.com/mlresearch/v282/main/assets/pertigkiozoglou26a/pertigkiozoglou26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
