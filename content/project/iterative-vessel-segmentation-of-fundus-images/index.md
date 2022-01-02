---
title: Iterative Vessel Segmentation of Fundus Images
date: 2021-11-13T14:55:56.425Z
draft: false
featured: false
weight: 4
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
This algorithm is based on the work of Nguyen et. Al. The idea behind this approach is that the blood vessel structures can be approximated as piecewise linear, so line detection on multiple scales can be used to separate the blood vessel structure from the background. By using lines of multiple lengths, vessels of different sizes and scales can be detected; problematic features, such as the small-scale vessel central light reflex have limited impact on the result at larger scales.
