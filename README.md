# L\'{e}vy Score and Score-Based Particle Algorithm
This repository provides an efficient implementation in ``jax`` of the score-based transport modeling algorithm for solving the Fokker-Planck equation in high dimension analyzing entropy production in non-Gaussian active matter. This method may also find applications in flow-based solutions of other high-dimensional partial differential equations using machine learning.

# Installation
The implementation is built on Google's [``jax``](https://github.com/google/jax) package for accelerated linear algebra and DeepMind's [``haiku``](https://github.com/deepmind/dm-haiku) package for neural networks. Both can be installed by following the guidelines at the linked repositories.


# Referencing
If you found this repository useful, please consider citing

[1] Huang, Yuanfei, Chengyu Liu, and Xiang Zhou. "L\'{e} vy Score Function and Score-Based Particle Algorithm for Nonlinear L\'{e} vy--Fokker--Planck Equations." arXiv preprint arXiv:2412.19520 (2024).
```
@article{huang2024vy,
  title={L$\backslash$'$\{$e$\}$ vy Score Function and Score-Based Particle Algorithm for Nonlinear L$\backslash$'$\{$e$\}$ vy--Fokker--Planck Equations},
  author={Huang, Yuanfei and Liu, Chengyu and Zhou, Xiang},
  journal={arXiv preprint arXiv:2412.19520},
  year={2024}
}
```

[2] Huang, Yuanfei, Chengyu Liu, Bing Miao, and Xiang Zhou.
"Entropy Production in Non-Gaussian Active Matter: A Unified Fluctuation Theorem and Deep Learning Framework."
arXiv preprint arXiv:2504.06628 (2025).
