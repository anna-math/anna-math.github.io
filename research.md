---
layout: homepage
permalink: /research/
---

My research focuses on problems arising in mathematical data science. I am particularly interested in designing and analyzing iterative algorithms for large-scale data and in developing tools from numerical linear algebra, signal processing, machine learning, and probability.

Below, I highlight some recent works and provide code, when available, associated with the manuscript.

**A complete list of my publications can be found on [Google Scholar](https://scholar.google.com/citations?user=o4EFl3YAAAAJ&hl=en).**

## Preprints

- **[Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations](https://arxiv.org/abs/2604.01757)**  
  M. F. Serret, A. Cortinovis, Y. Dong, D. Halikias, A. Ma, F. Matti, D. Needell, K. J. Pearce, E. Rebrova, D. Shur, R. Smith, H.-X. Wang, and L. Grigori, 2026.  
  [Code](https://github.com/rnla-transformers/qkv_extractor)

- **[Where Have All the Kaczmarz Iterates Gone?](https://arxiv.org/abs/2510.08563)**  
  E. H. Bergou, S. Boucherouite, A. Dutta, X. Li, and A. Ma, 2025.  
  [Code](https://github.com/SoumiaBouch/Where-Have-All-the-Kaczmarz-Iterates-Gone)

## Research Areas

### Randomized Iterative Methods

Randomized iterative methods solve large-scale linear systems through a sequence of inexpensive updates based on randomly selected equations, blocks, or sketches. This approach can reduce memory and computational costs while remaining effective when data are noisy, inconsistent, or corrupted.

**Paper highlights**

- **On the Subsample Size of Quantile-Based Randomized Kaczmarz**  
  J.-F. Cai, J. Chen, A. Ma, and T. Wu.  
  [arXiv](https://arxiv.org/abs/2507.15185) · [*SIAM Journal on Matrix Analysis and Applications*](https://epubs.siam.org/doi/full/10.1137/25M1785678)
- **A Note on the Randomized Kaczmarz Algorithm for Solving Doubly-Noisy Linear Systems**  
  E. H. Bergou, S. Boucherouite, A. Dutta, X. Li, and A. Ma.  
  [arXiv](https://arxiv.org/abs/2308.16904) · [*SIAM Journal on Matrix Analysis and Applications*](https://doi.org/10.1137/23M155712X) · [Code](https://github.com/SoumiaBouch/doubly_Noisy_Randomized_Kaczmarz)
- **Greed Works: An Improved Analysis of Sampling Kaczmarz-Motzkin**  
  J. Haddock and A. Ma.  
  [arXiv](https://arxiv.org/abs/1912.03544) · [*SIAM Journal on Mathematics of Data Science*](https://doi.org/10.1137/19M1307044)

### Tensor Methods

Tensor methods preserve the multiway structure found in data such as images, videos, and scientific measurements. Low-rank models, structured sampling, and tensor linear algebra make it possible to recover and process these datasets efficiently, even when observations are incomplete or noisy.

**Paper highlights**

- **Wedge Sampling: Efficient Tensor Completion with Nearly-Linear Sample Complexity**  
  H. Luo, A. Ma, L. Stephan, and Y. Zhu.  
  [arXiv](https://arxiv.org/abs/2602.05869) · [Conference on Learning Theory (COLT)](https://proceedings.mlr.press/v336/luo26a.html)
- **Stochastic Gradient Descent for Incomplete Tensor Linear Systems**  
  A. Ma, D. Needell, and A. Xue.  
  [arXiv](https://arxiv.org/abs/2510.07630) · [*BIT Numerical Mathematics*](https://doi.org/10.1007/s10543-026-01140-w) · [Code](https://github.com/alexxue99/mSGDT)
- **Robust Recovery of Low-Rank Matrices and Low-Tubal-Rank Tensors from Noisy Sketches**  
  A. Ma, D. Stöger, and Y. Zhu.  
  [arXiv](https://arxiv.org/abs/2206.00803) · [*SIAM Journal on Matrix Analysis and Applications*](https://doi.org/10.1137/22M150071X) · [Code](https://github.com/anna-math/doublesketch)

### Data Visualization and Machine Learning

Data visualization transforms high-dimensional information into interpretable low-dimensional representations, while machine learning identifies structure and patterns within complex datasets. Numerical linear algebra and optimization provide the tools needed to make these methods scalable, stable, and efficient.

**Paper highlights**

- **Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations**  
  M. F. Serret, A. Cortinovis, Y. Dong, D. Halikias, A. Ma, F. Matti, D. Needell, K. J. Pearce, E. Rebrova, D. Shur, R. Smith, H.-X. Wang, and L. Grigori.  
  [arXiv](https://arxiv.org/abs/2604.01757) · [Code](https://github.com/rnla-transformers/qkv_extractor)
- **Efficient and Robust Bayesian Selection of Hyperparameters in Dimension Reduction for Visualization**  
  Y.-T. Liao, H. Luo, and A. Ma.  
  [arXiv](https://arxiv.org/abs/2306.00357)
- **AVIDA: An Alternating Method for Visualizing and Integrating Data**  
  K. Dover, Z. Cang, A. Ma, Q. Nie, and R. Vershynin.  
  [arXiv](https://arxiv.org/abs/2206.00135) · [*Journal of Computational Science*](https://doi.org/10.1016/j.jocs.2023.101998) · [Code](https://github.com/kat-dover/AVIDA/tree/main/data)
