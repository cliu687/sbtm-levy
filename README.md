# Lévy Score & EPR‑Lévy

Official JAX implementation for two companion works:

1. **Lévy Score Function and Score-Based Particle Algorithm for Nonlinear Lévy–Fokker–Planck Equations**  
   Y. Huang, C. Liu, X. Zhou, *SIAM Journal on Numerical Analysis* (accepted).  
   Preprint: <https://arxiv.org/abs/2412.19520>

2. **Entropy Production in Non-Gaussian Active Matter: A Unified Fluctuation Theorem and Deep Learning Framework**  
   Y. Huang, C. Liu, B. Miao, X. Zhou, *Physical Review Letters* (accepted).  
   Preprint: <https://arxiv.org/abs/2504.06628>

This repo reproduces the main numerical examples in both papers.

---

## 🔑 At a glance

- **Lévy score & particle solver**  
  Proposes the **Lévy score** for nonlinear Lévy–Fokker–Planck equations with jumps, and a **score-based transport particle algorithm** that realizes the probability-flow equivalence by deterministic particle dynamics, together with **KL-type error bounds** separating time-discretization and Monte Carlo errors.  

- **EPR‑Lévy (built on the Lévy‑score solver)**  
  Uses the same Lévy‑score–based probability-flow framework to  
  - derive a **decomposition** of total entropy production $\Delta s_{\mathrm{tot}}$ in non‑Gaussian active matter,  
  - prove the **integral fluctuation theorem** $\langle \exp[-\Delta s_{\mathrm{tot}} + B_{\mathrm{act}}] \rangle = 1$ and the **generalized second law** $\langle \Delta s_{\mathrm{tot}} \rangle \ge \langle B_{\mathrm{act}} \rangle$, and  
  - design a **deep-learning‑based scheme** (built on the Lévy score) to efficiently compute entropy production in representative active systems.
  
---

## 🗂 Layout

- `levy-score/` – Lévy score + score-based particle solver for Lévy–Fokker–Planck.  
- `EPR-levy/` – EPR‑Lévy framework and experiments.

---
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

