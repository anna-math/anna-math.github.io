---
layout: homepage
permalink: /research/
---

My research focuses on problems arising in mathematical data science. I am particularly interested in designing and analyzing iterative algorithms for large-scale data and in developing tools from numerical linear algebra, signal processing, machine learning, and probability.

Below, I highlight some recent works and provide code, when available, associated with the manuscript.

**A complete list of my publications can be found on [Google Scholar](https://scholar.google.com/citations?user=o4EFl3YAAAAJ&hl=en).**

## Recent Preprints

- **[Attention Mechanisms Through the Lens of Numerical Methods: Approximation Methods and Alternative Formulations](https://arxiv.org/abs/2604.01757)**  
  M. F. Serret, A. Cortinovis, Y. Dong, D. Halikias, A. Ma, F. Matti, D. Needell, K. J. Pearce, E. Rebrova, D. Shur, R. Smith, H.-X. Wang, and L. Grigori, 2026.

- **[Where Have All the Kaczmarz Iterates Gone?](https://arxiv.org/abs/2510.08563)**  
  E. H. Bergou, S. Boucherouite, A. Dutta, X. Li, and A. Ma, 2025.

## Research Areas

### Randomized Iterative Methods

Randomized iterative methods solve large-scale linear systems through a sequence of inexpensive updates based on randomly selected equations, blocks, or sketches. This approach can reduce memory and computational costs while remaining effective when data are noisy, inconsistent, or corrupted.

**Paper highlights**

- **[Where Have All the Kaczmarz Iterates Gone?](https://arxiv.org/abs/2510.08563)** — Studies the asymptotic behavior and convergence horizon of randomized Kaczmarz iterates for noisy, inconsistent systems.
- **[A Note on the Randomized Kaczmarz Algorithm for Solving Doubly-Noisy Linear Systems](https://arxiv.org/abs/2308.16904)** — Provides convergence guarantees when both the coefficient matrix and right-hand side contain noise.
- **[Greed Works: An Improved Analysis of Sampling Kaczmarz-Motzkin](https://arxiv.org/abs/1908.08479)** — Analyzes a greedy randomized method for solving large linear systems.

### Tensor Methods

Tensor methods preserve the multiway structure found in data such as images, videos, and scientific measurements. Low-rank models, structured sampling, and tensor linear algebra make it possible to recover and process these datasets efficiently, even when observations are incomplete or noisy.

**Paper highlights**

- **[Wedge Sampling: Efficient Tensor Completion with Nearly-Linear Sample Complexity](https://proceedings.mlr.press/v336/luo26a.html)** — Introduces a structured sampling scheme that enables efficient low-rank tensor completion with nearly linear sample complexity.
- **[Stochastic Gradient Descent for Incomplete Tensor Linear Systems](https://arxiv.org/abs/2510.07630)** — Extends stochastic-gradient methods for tensor linear systems to broader missing-data models.
- **[Robust Recovery of Low-Rank Matrices and Low-Tubal-Rank Tensors from Noisy Sketches](https://arxiv.org/abs/2206.00803)** — Establishes recovery guarantees for low-rank data from noisy linear sketches.

### Data Visualization and Machine Learning

Data visualization transforms high-dimensional information into interpretable low-dimensional representations, while machine learning identifies structure and patterns within complex datasets. Numerical linear algebra and optimization provide the tools needed to make these methods scalable, stable, and efficient.

**Paper highlights**

- **[Attention Mechanisms Through the Lens of Numerical Methods](https://arxiv.org/abs/2604.01757)** — Surveys fast attention methods through numerical linear algebra, including low-rank approximation, randomized sketching, sparsity, and tensor decompositions.
- **[Efficient and Robust Bayesian Selection of Hyperparameters in Dimension Reduction for Visualization](https://arxiv.org/abs/2306.00357)** — Uses Bayesian optimization to tune visualization methods such as t-SNE and UMAP efficiently.
- **[AVIDA: An Alternating Method for Visualizing and Integrating Data](https://arxiv.org/abs/2206.00135)** — Alternates dimension reduction and data alignment to create joint visualizations of multimodal datasets.
