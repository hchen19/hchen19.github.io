---
title: Scalable Gaussian Processes
summary: <a href="https://en.wikipedia.org/wiki/Gaussian_process" style="color:blue;">Gaussian processes</a> (GPs) confront significant computational bottlenecks, including the computation of the inversion and log-determinant of the covariance matrix, which limit their scalability to large datasets. These operations scale cubically with the number of data points, making standard GP inference computationally prohibitive for large datasets. Therefore, developing scalable methods for GPs is crucial to unlock their full potential for large-scale applications while preserving their desirable properties of uncertainty quantification and theoretical guarantees.
show_date: false
image:
  preview_only: true
weight: 1
---


- **[Kernel Packet](/publication/0-journal-kernel-packet/)** transforms <a href="https://en.wikipedia.org/wiki/Mat%C3%A9rn_covariance_function" style="color:blue;">Matérn kernels</a> with half-integer smoothness into compactly supported functions via a sparse linear transformation, turning GP regression into banded linear solves that require only 𝒪(𝑛) time for Matérn GP regression.

- **[Sampling with Sparse Grid under Additive Schwarz preconditioner](/publication/1-preprint-gp-sg-sampling/)** generates prior and posterior GP sample paths by coupling <a href="https://proceedings.mlr.press/v5/titsias09a/titsias09a.pdf" style="color:blue;">inducing points</a> on <a href="https://en.wikipedia.org/wiki/Sparse_grid" style="color:blue;">sparse grids</a> with additive Schwarz preconditioning, yielding scalable iterative samplers whose convergence is theoretically guaranteed.

- **[Optimal aggregation for distributed GPs](/publication/3-preprint-distribute-gp/)** introduces correlation-aware weighting schemes for both exact and variational GPs so that <a href="https://proceedings.mlr.press/v37/deisenroth15.pdf" style="color:blue;">distributed GP</a> predictions remain accurate, stable, and efficient for large-scale applications.