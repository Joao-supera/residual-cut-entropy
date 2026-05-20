# 📘 SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION™

<div align="center">

## Residual Cut Entropy for Tseitin Formulas

### An Information-Theoretic Perspective on Exponential OBDD Lower Bounds

<br>

[![DOI](https://zenodo.org/badge/1243877803.svg)](https://doi.org/10.5281/zenodo.20300225)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/Joao-supera/SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION)](https://github.com/Joao-supera/SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION/releases)
[![GitHub Stars](https://img.shields.io/github/stars/Joao-supera/SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION?style=social)](https://github.com/Joao-supera/SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION)

<br>

**DOI:** https://doi.org/10.5281/zenodo.20300225  
**Repository:** https://github.com/Joao-supera/SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION

</div>

---

> **A mathematical contribution to the SUP3RA research program introducing Residual Cut Entropy (RCE), an information-theoretic quantity that yields exponential lower bounds for Ordered Binary Decision Diagrams (OBDDs).**

---

## 🌌 Overview

This repository contains the manuscript:

> **Residual Cut Entropy for Tseitin Formulas**  
> *An Information-Theoretic Perspective on Exponential OBDD Lower Bounds*

The paper introduces **Residual Cut Entropy (RCE)**, a structural information measure that quantifies the number of semantically distinct residual Boolean functions induced by a variable partition.

This perspective provides:

- A general lower bound for OBDD width;
- An exact formula for Tseitin formulas;
- A concise derivation of classical exponential lower bounds;
- A conceptual bridge between information theory and proof complexity.

---

## 📄 Abstract

Residual Cut Entropy is defined as the logarithm of the number of distinct residual functions across a cut. For every variable ordering and every cut, the width of an Ordered Binary Decision Diagram (OBDD) is at least the corresponding residual count.

For Tseitin formulas, this quantity admits an exact graph-theoretic characterization:

\[
H_C^{\mathrm{res}}(F_G) = c(T) - 1
\]

where \(c(T)\) is the number of connected components of the residual graph.

As a consequence, every OBDD representing a Tseitin formula on a bounded-degree expander graph requires exponential size.

---

## 📐 Main Results

### General OBDD Lower Bound

\[
\mathrm{width}_C(F) \ge 2^{H_C^{\mathrm{res}}(F)}
\]

### Exact Formula for Tseitin Formulas

\[
H_C^{\mathrm{res}}(F_G) = c(T) - 1
\]

### Exponential Lower Bound

\[
\mathrm{OBDD}(F_G) \ge 2^{n/4 - 1}
\]

for 3-regular expander graphs with \(n\) vertices.

---

## 🧠 Relation to SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION™

This repository is part of the broader **SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION™** research program, which integrates:

- Computational Complexity Theory;
- Information Theory;
- Statistical Physics;
- AI Governance;
- Responsible AI;
- Cognitive Decision Systems.

### Core Principle

> A solution may be easy to verify while remaining fundamentally difficult to discover.

---

## 🛡️ Related Frameworks

### SUP3RA VECTRA™

Framework for AI Governance and Responsible AI.

### Governability Score (GS)

Quantitative metric for evaluating AI response governability.

### SUP3RA CORE Benchmark

Adversarial benchmark with 150 tests.

### GDLE Core Engine

Hybrid optimization architecture for NP-hard problems.

---

## 📂 Repository Structure

```text
SUP3RA-CORE-P-VS-NP-THE-NEXT-GENERATION/
├── paper.tex
├── Paper.pdf
├── README.md
├── CITATION.cff
└── LICENSE

📥 Access the Paper
📄 PDF: Paper.pdf
📝 LaTeX source: paper.tex
🔗 DOI: https://doi.org/10.5281/zenodo.20300225

@misc{batista2026residual,
  author = {João Henrique de Souza Batista},
  title = {Residual Cut Entropy for Tseitin Formulas:
           An Information-Theoretic Perspective on Exponential OBDD Lower Bounds},
  year = {2026},
  doi = {10.5281/zenodo.20300225},
  url = {https://doi.org/10.5281/zenodo.20300225}
}

👤 Author

João Henrique de Souza Batista
Cognitive Architect of AI Systems
Independent Researcher — Brazil

LinkedIn: https://www.linkedin.com/in/joaohenriquedigital/
GitHub: https://github.com/Joao-supera
DOI: https://doi.org/10.5281/zenodo.20300225
🔗 Related Resources
SUP3RA VECTRA™ Benchmark
https://github.com/Joao-supera/sup3ra-vectra-benchmark
Professional Profile
https://www.linkedin.com/in/joaohenriquedigital/
📜 License

This work is licensed under the
Creative Commons Attribution 4.0 International License (CC BY 4.0).

<div align="center">
🚀 Research Vision

Transforming theoretical limits into practical frameworks for governable AI and trustworthy decision systems.

</div> ```
