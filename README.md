# Sueishi Econometrics Notes

Self-study implementations and mathematical derivations for Sueishi (2015), *Keiryō Keizaigaku* (Nippon Hyoron Sha).

## Overview

This repository contains my self-study notes and Python implementations for Naoya Sueishi's *Keiryō Keizaigaku* (Econometrics, Nippon Hyoron Sha, 2015). The goal is to deepen my understanding of modern econometric theory by (1) rewriting key derivations in my own notation and (2) reproducing estimators from scratch in Python.

I am an undergraduate student at Kobe University, planning to enter the Graduate School of Economics (EDS program). This repository serves as preparation and a long-term reference.

## Chapters covered
- [x] Ch. 1 — Linear Regression and OLS
- [x] Ch. 2 — Instrumental Variable
- [x] Ch. 3 — Program Evaluation
- [x] Ch. 4 — Matrix notation and Asymptotic theory
- [x] Ch. 5 — Orthogonality conditions and GMM
- [x] Ch. 6 — Limited dependent variables and Sample selection
- [ ] Ch. 7 — Quantile regression
- [ ] Ch. 8 — Bootstrap
- [ ] Ch. 9 — Nonparametric methods

(Updated as I progress.)

## Approach

For each chapter, I aim to produce three artifacts:

1. **Derivation notes** — key theorems and proofs rewritten in my own notation, with intermediate steps filled in where the textbook is terse.
2. **From-scratch implementation** — estimators implemented in NumPy/SciPy without relying on high-level libraries like `statsmodels`, to verify my understanding of the underlying computation.
3. **Numerical experiments** — simulations comparing my implementation against `statsmodels` / `linearmodels` on synthetic data, and reproducing textbook examples where possible.

## Usage

```bash
git clone https://github.com/shuhei-kuroiwa/sueishi-econometrics-notes.git
cd sueishi-econometrics-notes
pip install -r requirements.txt
jupyter lab notebooks/
```

## Disclaimer

This repository is a personal study log. All derivations and code are my own work, written while studying the textbook. No figures, problem statements, or original text from the book are reproduced here. For the actual content of the textbook, please refer to:

> 末石直也 (2015)『計量経済学:ミクロデータ分析へのいざない』日本評論社.

If you find errors in my notes or implementations, issues and pull requests are welcome.

## License

Code: MIT License. Notes: CC BY 4.0.

---

*Part of my ongoing study toward a career as a practitioner data scientist with a focus on causal inference. See also: [econometrics-study-log](https://github.com/shuhei-kuroiwa/econometrics-study-log).*
