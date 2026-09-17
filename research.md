---
layout: homepage
permalink: /research/
---

My research focuses on problems arising in mathematical data science. I am particularly interested in designing and analyzing iterative algorithms for large-scale data and in developing tools from numerical linear algebra, signal processing, machine learning, and probability.

Below, I highlight some recent works and provide code, when available, associated with the manuscript.

**A complete list of my publications can be found on [Google Scholar](https://scholar.google.com/citations?user=o4EFl3YAAAAJ&hl=en).**

## Preprints

- **[Quantile-based Loss Filtering for Outlier-Robust Stochastic Gradient Descent](https://arxiv.org/abs/2609.13040v1)**<br>
  J. Haddock, A. Ma, E. Rebrova, 2026.<br>
  [arXiv](https://arxiv.org/abs/2609.13040v1) · [Code](https://github.com/jamiehadd/QuantileSGD)

- **[Quantile Randomized Kaczmarz for Streaming Linear Systems with Massart Noise](https://arxiv.org/abs/2608.27968)**<br>
  E. Battaglia, J.-F. Cai, J. Chen, A. Ma, D. Needell, and T. Wu, 2026.<br>
  [arXiv](https://arxiv.org/abs/2608.27968) · [Code](https://github.com/wtree101/Explicit-beta-and-D-for-QRK)

- **[Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations](https://arxiv.org/abs/2604.01757)**<br>
  M. F. Serret, A. Cortinovis, Y. Dong, D. Halikias, A. Ma, F. Matti, D. Needell, K. J. Pearce, E. Rebrova, D. Shur, R. Smith, H.-X. Wang, and L. Grigori, 2026.<br>
  [arXiv](https://arxiv.org/abs/2604.01757) · [Code](https://github.com/rnla-transformers/qkv_extractor)

- **[Wedge Sampling: Efficient Tensor Completion with Nearly-Linear Sample Complexity](https://arxiv.org/abs/2602.05869)**<br>
  H. Luo, A. Ma, L. Stephan, and Y. Zhu, 2026.<br>
  [arXiv](https://arxiv.org/abs/2602.05869)

- **[Where Have All the Kaczmarz Iterates Gone?](https://arxiv.org/abs/2510.08563)**<br>
  E. H. Bergou, S. Boucherouite, A. Dutta, X. Li, and A. Ma, 2025.<br>
  [arXiv](https://arxiv.org/abs/2510.08563) · [Code](https://github.com/SoumiaBouch/Where-Have-All-the-Kaczmarz-Iterates-Gone)

- **[Efficient and Robust Bayesian Selection of Hyperparameters in Dimension Reduction for Visualization](https://arxiv.org/abs/2306.00357)**<br>
  Y.-T. Liao, H. Luo, and A. Ma, 2023.<br>
  [arXiv](https://arxiv.org/abs/2306.00357)

## Research Areas

### Randomized Iterative Methods

Randomized iterative methods solve large-scale linear systems through a sequence of inexpensive updates based on randomly selected equations, blocks, or sketches. This approach can reduce memory and computational costs while remaining effective when data are noisy, inconsistent, or corrupted.

**Paper highlights**

- **[On the Subsample Size of Quantile-Based Randomized Kaczmarz](https://arxiv.org/abs/2507.15185)**<br>
  J.-F. Cai, J. Chen, A. Ma, and T. Wu.<br>
  [arXiv](https://arxiv.org/abs/2507.15185) · [*SIAM Journal on Matrix Analysis and Applications*](https://epubs.siam.org/doi/full/10.1137/25M1785678) · [Code](https://github.com/wtree101/matlab-rk-analysis)

- **[Quantile-RK and Double Quantile-RK Error Horizon Analysis](https://arxiv.org/abs/2505.00258)**<br>
  E. Battaglia and A. Ma.<br>
  [arXiv](https://arxiv.org/abs/2505.00258) · [*Linear Algebra and its Applications*](https://doi.org/10.1016/j.laa.2026.01.032)

- **[Greed Works: An Improved Analysis of Sampling Kaczmarz-Motzkin](https://arxiv.org/abs/1912.03544)**<br>
  J. Haddock and A. Ma.<br>
  [arXiv](https://arxiv.org/abs/1912.03544) · [*SIAM Journal on Mathematics of Data Science*](https://doi.org/10.1137/19M1307044)

### Tensor Methods

Tensor methods preserve the multiway structure found in data such as images, videos, and scientific measurements. Low-rank models, structured sampling, and tensor linear algebra make it possible to recover and process these datasets efficiently, even when observations are incomplete or noisy.

**Paper highlights**

- **[Wedge Sampling: Efficient Tensor Completion with Nearly-Linear Sample Complexity](https://arxiv.org/abs/2602.05869)**<br>
  H. Luo, A. Ma, L. Stephan, and Y. Zhu.<br>
  [arXiv](https://arxiv.org/abs/2602.05869) · [Conference on Learning Theory (COLT)](https://proceedings.mlr.press/v336/luo26a.html)

- **[Stochastic Gradient Descent for Incomplete Tensor Linear Systems](https://arxiv.org/abs/2510.07630)**<br>
  A. Ma, D. Needell, and A. Xue.<br>
  [arXiv](https://arxiv.org/abs/2510.07630) · [*BIT Numerical Mathematics*](https://doi.org/10.1007/s10543-026-01140-w) · [Code](https://github.com/alexxue99/mSGDT)

- **[Robust Recovery of Low-Rank Matrices and Low-Tubal-Rank Tensors from Noisy Sketches](https://arxiv.org/abs/2206.00803)**<br>
  A. Ma, D. Stöger, and Y. Zhu.<br>
  [arXiv](https://arxiv.org/abs/2206.00803) · [*SIAM Journal on Matrix Analysis and Applications*](https://doi.org/10.1137/22M150071X) · [Code](https://github.com/anna-math/doublesketch)

### Data Visualization and Machine Learning

Data visualization transforms high-dimensional information into interpretable low-dimensional representations, while machine learning identifies structure and patterns within complex datasets. Numerical linear algebra and optimization provide the tools needed to make these methods scalable, stable, and efficient.

**Paper highlights**

- **[Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations](https://arxiv.org/abs/2604.01757)**<br>
  M. F. Serret, A. Cortinovis, Y. Dong, D. Halikias, A. Ma, F. Matti, D. Needell, K. J. Pearce, E. Rebrova, D. Shur, R. Smith, H.-X. Wang, and L. Grigori.<br>
  [arXiv](https://arxiv.org/abs/2604.01757) · [Code](https://github.com/rnla-transformers/qkv_extractor)

- **[Efficient and Robust Bayesian Selection of Hyperparameters in Dimension Reduction for Visualization](https://arxiv.org/abs/2306.00357)**<br>
  Y.-T. Liao, H. Luo, and A. Ma.<br>
  [arXiv](https://arxiv.org/abs/2306.00357)

- **[AVIDA: An Alternating Method for Visualizing and Integrating Data](https://arxiv.org/abs/2206.00135)**<br>
  K. Dover, Z. Cang, A. Ma, Q. Nie, and R. Vershynin.<br>
  [arXiv](https://arxiv.org/abs/2206.00135) · [*Journal of Computational Science*](https://doi.org/10.1016/j.jocs.2023.101998) · [Code](https://github.com/kat-dover/AVIDA/tree/main/)
