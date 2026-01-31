# Neutral B Meson Decays — Toy Time-Dependent Mixing and CP Violation Study (PyROOT)

This repository contains a toy Monte Carlo simulation inspired by the LHCb analysis of  
neutral B meson decays:

\[
B^0 \to \pi^+\pi^-\pi^+\pi^-
\]

The project demonstrates key ingredients used in time-dependent flavour and CP violation
measurements:

- Exponential decay-time generation for unstable B mesons  
- Resonant substructure injection via the \(\rho(770)\to\pi^+\pi^-\) peak  
- Flavour-tagged \(B^0\)–\(\bar{B}^0\) oscillations  
- Construction of the mixing asymmetry:

\[
A(t)=\frac{N(B^0)-N(\bar{B}^0)}{N(B^0)+N(\bar{B}^0)}
\]

- Fits to extract oscillation parameters and CP-sensitive coefficients \(S\) and \(C\)

The code is written in **Python + ROOT (PyROOT)** and provides a minimal self-contained
introduction to the core framework behind LHCb time-dependent amplitude analyses.

---

## Tools Used

- ROOT 6 (PyROOT)
- Python 3
- JupyterLab

---

## Contents

- `Neutral_B_Meson_Decays.ipynb` — main notebook simulation and plots
- Time-dependent asymmetry and oscillation fits

---

## Physics Motivation

Neutral meson mixing and CP violation are central to testing the CKM mechanism of the
Standard Model and constraining the unitarity triangle angle \(\alpha\).

