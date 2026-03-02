# phi4-one-loop-beta-repro

Reproducible derivation and numerical cutoff verification of the one-loop beta function in Euclidean scalar φ⁴ theory.

This repository accompanies the manuscript:
**“A reproducible derivation of the one-loop β(λ) function in Euclidean φ⁴ theory with numerical cutoff verification.”**

## Contents
- `notebooks/numerical_cutoff_verification.ipynb` — computes the cutoff integral, performs the fit-window robustness check, and generates the plots.
- `figures/Fig1_I_vs_logLambda2.pdf` — \(I(\Lambda,m)\) vs \(\ln(\Lambda^2/m^2)\) with linear fit.
- `figures/Fig2_Delta_vs_invLambda2.pdf` — residual \(\Delta(\Lambda)\) vs \(1/\Lambda^2\) with asymptote.

## Reproduce the figures
### Option A: Python + pip (recommended)
```bash
python -m venv .venv
# activate:
# Windows: .venv\Scripts\activate
# Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
