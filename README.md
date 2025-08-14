# ML-Models — Experiments in Time-Series & Generative Modeling

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](#)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red.svg)](#)
[![Google Colab](https://img.shields.io/badge/Run%20on-Colab-FFCC00.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#license)

A curated collection of my machine-learning projects for teaching and research.  
I primarily **develop and run on Google Colab** (GPU), with ready-to-run notebooks for the Python projects.

> ⚠️ **Disclaimer**  
> Code, models, and outputs are for research/education only. **Not investment advice.**

---

## Colab-first workflow

- Open a notebook with the **Colab badge** below (or from each subfolder’s README).
- In Colab: `Runtime → Change runtime type → GPU` (T4/L4/A100).  
- Install deps at the top of the notebook, e.g.:
  ```python
  !pip -q install yfinance torch torchvision torchaudio scipy statsmodels matplotlib tqdm tensorboard
