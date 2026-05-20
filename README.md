# 📘 Residual Cut Entropy

**Residual Cut Entropy for Tseitin Formulas:  
An Information-Theoretic Perspective on Exponential OBDD Lower Bounds**

[![DOI](https://zenodo.org/badge/1243877803.svg)](https://doi.org/10.5281/zenodo.20300225)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/Joao-supera/residual-cut-entropy)](https://github.com/Joao-supera/residual-cut-entropy/releases)
[![GitHub stars](https://img.shields.io/github/stars/Joao-supera/residual-cut-entropy?style=social)](https://github.com/Joao-supera/residual-cut-entropy)

---

## Overview

This repository contains the manuscript:

> **Residual Cut Entropy for Tseitin Formulas:  
> An Information-Theoretic Perspective on Exponential OBDD Lower Bounds**

The paper introduces **Residual Cut Entropy (RCE)**, an information-theoretic measure that quantifies the number of semantically distinct residual Boolean functions induced by a variable partition.

This perspective yields:

- A general structural lower bound for OBDD width.
- An exact formula for Tseitin formulas.
- A short derivation of classical exponential lower bounds.

---

## Abstract

Residual Cut Entropy is defined as the logarithm of the number of distinct residual functions across a cut. For every variable ordering and every cut, the width of an Ordered Binary Decision Diagram (OBDD) is at least the corresponding residual count. For Tseitin formulas, this quantity admits an exact graph-theoretic characterization: it equals the number of connected components of the residual graph minus one. As a consequence, every OBDD representing a Tseitin formula on a bounded-degree expander graph requires exponential size.

---

## Main Results

### General OBDD Lower Bound

For every Boolean formula \(F\) and cut \(C\),

\[
\mathrm{width}_C(F) \ge 2^{H^{\mathrm{res}}_C(F)}.
\]

### Exact Formula for Tseitin Formulas

For every connected graph \(G\),

\[
H^{\mathrm{res}}_C(F_G) = c(T) - 1,
\]

where \(c(T)\) is the number of connected components in the residual subgraph.

### Exponential Lower Bound

For 3-regular expander graphs with \(n\) vertices,

\[
\mathrm{OBDD}(F_G) \ge 2^{n/4 - 1}.
\]

---

## Repository Structure

```text
residual-cut-entropy/
├── paper.tex      # LaTeX source
├── Paper.pdf      # Compiled manuscript
├── README.md      # Project overview
└── LICENSE        # CC BY 4.0

@misc{batista2026residual,
  author       = {João Henrique de Souza Batista},
  title        = {Residual Cut Entropy for Tseitin Formulas:
                  An Information-Theoretic Perspective on Exponential OBDD Lower Bounds},
  year         = {2026},
  note         = {Preprint},
  url          = {https://github.com/Joao-supera/residual-cut-entropy}
}

Author

João Henrique de Souza Batista
Independent Researcher
Brazil

GitHub: https://github.com/Joao-supera
LinkedIn: https://www.linkedin.com/in/joaohenriquedigital/
License

This work is licensed under the
Creative Commons Attribution 4.0 International License (CC BY 4.0).
