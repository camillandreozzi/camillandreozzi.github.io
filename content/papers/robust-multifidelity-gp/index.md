---
title: "A Simple and Robust Multi-Fidelity Data Fusion Method for Effective Modeling of Citizen-Science Air Pollution Data"
date: 2025-11-20
tags: ["Gaussian processes","multi-fidelity modeling","robust statistics","air pollution","citizen science"]
author: ["Camilla Andreozzi", "Pietro Colombo", "Philipp Otto"]
description: "A robust multi-fidelity Gaussian process that fuses reference air-quality monitors with noisy citizen-science sensors."
summary: "A robust multi-fidelity Gaussian process that combines sparse, high-quality reference monitors with dense but noisy citizen-science sensors, using a Huber loss to bound the influence of contaminated data. Submitted to the Annals of Applied Statistics."
editPost:
    URL: "https://doi.org/10.48550/arXiv.2511.15942"
    Text: "Submitted to the Annals of Applied Statistics"

---

---

##### Download

+ [Paper](https://arxiv.org/pdf/2511.15942)
+ [arXiv page](https://arxiv.org/abs/2511.15942)

---

##### Abstract

We propose a robust multi-fidelity Gaussian process for integrating sparse, high-quality reference monitors with dense but noisy citizen-science sensors. The approach replaces the Gaussian log-likelihood in the high-fidelity channel with a global Huber loss applied to precision-weighted residuals, yielding bounded influence on all parameters, including the cross-fidelity coupling, while retaining the flexibility of co-kriging. We establish attenuation and unbounded influence of the Gaussian maximum likelihood estimator under low-fidelity contamination and derive explicit finite bounds for the proposed estimator that clarify how whitening and mean-shift sensitivity determine robustness. Monte Carlo experiments with controlled contamination show that the robust estimator maintains stable MAE and RMSE as anomaly magnitude and frequency increase, whereas the Gaussian MLE deteriorates rapidly. In an empirical study of PM2.5 concentrations in Hamburg, combining UBA monitors with openSenseMap data, the method consistently improves cross-validated predictive accuracy and yields coherent uncertainty maps without relying on auxiliary covariates. The framework remains computationally scalable through diagonal or low-rank whitening and is fully reproducible with publicly available code.

---

##### Citation

Andreozzi, Camilla, Pietro Colombo, and Philipp Otto. 2025. "A Simple and Robust Multi-Fidelity Data Fusion Method for Effective Modeling of Citizen-Science Air Pollution Data." arXiv:2511.15942. https://doi.org/10.48550/arXiv.2511.15942.

```BibTeX
@misc{ACO25,
author = {Camilla Andreozzi and Pietro Colombo and Philipp Otto},
title = {A Simple and Robust Multi-Fidelity Data Fusion Method for Effective Modeling of Citizen-Science Air Pollution Data},
year = {2025},
eprint = {2511.15942},
archivePrefix = {arXiv},
primaryClass = {stat.ME},
doi = {10.48550/arXiv.2511.15942}}
```
