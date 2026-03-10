# FractalPK

Open pharmacokinetic platform with fractional diffusion for tumor compartments (GBM focus).

## Why fractional diffusion?

GBM's heterogeneous extracellular matrix creates tortuous diffusion paths that standard ODE models can't capture. FractalPK uses fractional-order diffusion (anomalous transport, α < 1) instead of classical Fick's law.

## What it does

- **Analytical Cp5 engine** — no numerical ODE solver needed
- **Simultaneous fitting** of plasma + tumor concentration curves
- **TCGA-GBM survival analysis** module (Kaplan-Meier, Cox regression)
- **Clinical validation dashboard** vs scipy/lmfit/MCMC

## Validated against

Ahmadi et al. 2017 (PMID 27863186, n=476)

## Live Demo

https://fractalpk-demo.onrender.com

## Stack

Python · Flask

## Status

Pre-publication. Open to feedback, especially from anyone in CNS drug delivery or population PK.
