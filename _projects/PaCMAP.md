---
layout: page
title: PaCMAP
description: Dimensionality reduction that preserves both local neighborhoods and global structure.
img: assets/img/pacmap_mammoth.png
importance: 2
category: Data visualization
---

PaCMAP (Pairwise Controlled Manifold Approximation Projection) maps high-dimensional data into a low-dimensional space for visualization. It balances nearby, mid-near, and further pairs to preserve local neighborhoods and the broader shape of the data.

{% include figure.liquid path="assets/img/pacmap_mammoth.png" alt="Mammoth dataset visualized with PaCMAP" class="img-fluid rounded" %}

Developed with Yingfan Wang, Cynthia Rudin, and Yaron Shaposhnik, this work appeared in the *Journal of Machine Learning Research* in 2021.

[Read the paper](https://www.jmlr.org/papers/v22/20-1061.html) · [Explore the code and installation guide](https://github.com/YingfanWang/PaCMAP)
