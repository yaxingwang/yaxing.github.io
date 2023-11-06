```yaml
title: "Integrated Variational Fourier Features for Fast Spatial Modelling with Gaussian Processes"
collection: publications
permalink: /publication/preprint2023
excerpt: ''
date: 2023-08-27
authors:
  - 'SELF'
  - 'Carl Edward Rasmussen'
paperurl: 'https://arxiv.org/abs/2308.14142'
rawciteurl: 'http://talayCh.github.io/files/2023_preprint/citation.txt'
```

Sparse variational approximations are popular methods for scaling up inference and learning in Gaussian processes to larger datasets. For N training points, exact inference has $O(N^3)$ cost; with $M \ll N$ features, state of the art sparse variational methods have $O(NM^2)$ cost. Recently, methods have been proposed using more sophisticated features; these promise $O(M^3)$ cost, with good performance in low dimensional tasks such as spatial modelling, but they only work with a very limited class of kernels, excluding some of the most commonly used. In this work, we propose integrated Fourier features, which extends these performance benefits to a very broad class of stationary covariance functions. We motivate the method and choice of parameters from a convergence analysis and empirical exploration, and show practical speedup in synthetic and real world spatial regression tasks.
