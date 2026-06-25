# Introduction aux copules et leur structure de dépendance

Bachelor Thesis in Mathematics  
UCLouvain — Academic Year 2024–2025

## Overview

This thesis provides an introduction to copula theory and its role in modeling dependence between random variables independently of their marginal distributions.

The manuscript presents the fundamental concepts of copulas, including Sklar's theorem, Fréchet–Hoeffding bounds, notions of dependence and concordance, and classical dependence measures such as Kendall's τ and Spearman's ρ.

## Abstract

Copulas are mathematical functions that allow the dependence structure of multivariate distributions to be studied separately from their marginal distributions. Since the publication of Sklar's theorem in 1959, copula theory has become an important tool in probability, statistics, actuarial science, and quantitative finance.

This thesis introduces the theoretical foundations of copula theory, develops the main results concerning dependence and concordance, and presents several classical measures of dependence, with particular emphasis on Kendall's τ and Spearman's ρ.

## Contents

- Introduction
- Introduction to Copulas
- Fundamental Results and Fréchet–Hoeffding Bounds
- Dependence and Concordance
- Measures of Dependence
  - Kendall's τ
  - Spearman's ρ
- Conclusion
- Bibliography

## Repository Structure

```text
.
├── README.md
├── thesis.pdf
├── thesis.tex
├── bibliography.bib
├── chapters/
│   ├── 01-introduction.tex
│   ├── 02-copulas.tex
│   ├── 03-frechet-hoeffding.tex
│   ├── 04-dependence-concordance.tex
│   ├── 05-dependence-measures.tex
│   └── conclusion.tex
└── figures/
```

## Compilation

To compile the thesis locally:

```bash
pdflatex thesis.tex
bibtex thesis
pdflatex thesis.tex
pdflatex thesis.tex
```

Alternatively, the project can be compiled using Overleaf.

## Main References

- Roger B. Nelsen, *An Introduction to Copulas*, 2nd Edition, Springer, 2006.
- Paul Embrechts and Marius Hofert, *A Note on Generalized Inverses*, 2013.
- Allan Gut, *Probability: A Graduate Course*, Springer, 2005.

## Disclaimer

This work was completed as part of the requirements for a Bachelor's degree in Mathematics at UCLouvain.

It is shared for educational, academic, and portfolio purposes only. The content reflects the author's understanding of the subject at the time of writing and has not been revised for journal publication.

## Author

Mateus Felipe Auza Cruz

## Supervisor

Karim Barigou

## License

This repository is provided for academic and educational purposes.

If you wish to reuse substantial portions of this work, please provide appropriate attribution.
