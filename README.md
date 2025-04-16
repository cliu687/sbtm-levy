# L\'{e}vy Score and EPR-L\'{e}vy
This repository provides an efficient implementation in ``jax`` of the score-based transport modeling algorithm for solving the Fokker-Planck equation in high dimension analyzing entropy production in non-Gaussian active matter. This method may also find applications in flow-based solutions of other high-dimensional partial differential equations using machine learning.

# Installation
The implementation is built on Google's [``jax``](https://github.com/google/jax) package for accelerated linear algebra and DeepMind's [``haiku``](https://github.com/deepmind/dm-haiku) package for neural networks. Both can be installed by following the guidelines at the linked repositories.

## Repository Structure

- **`levy-score/`**: Implements the score-based particle algorithm for solving nonlinear L\'{e}vy-Fokker-Planck equations. This method provides efficient solutions to high-dimensional PDEs influenced by non-Gaussian noise.
  
- **`EPR-levy/`**: Provides a deep learning framework for analyzing entropy production in non-Gaussian active matter systems, based on a unified fluctuation theorem.


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
```
@article{huang2025entropy,
  title={Entropy Production in Non-Gaussian Active Matter: A Unified Fluctuation Theorem and Deep Learning Framework},
  author={Huang, Yuanfei and Liu, Chengyu and Miao, Bing and Zhou, Xiang},
  journal={arXiv preprint arXiv:2504.06628},
  year={2025}
}
```

