# Functional Connectivity (FC) Methods

This package offers a suite of tools for assessing functional connectivity (FC) using both bivariate and multivariate techniques. Designed for neuroscientific data analysis, it can be applied to a range of brain signal modalities but is also adaptable to any dynamical network.

## Getting Started
No installation is required. Simply open and run the `FC_Methods.ipynb` notebook.

## Features
The notebook provides the following FC assessment methods, organized by type:

1. **Full Correlation** (`Corr_func`)
2. **Partial Correlation** (`PCorr_func`)
3. **Regularized Inverse Covariance / Precision** (`Prec_func`)
4. **[Magnitude Squared] Coherence** (`Coh_func`)
5. **Mutual Information** (`MI_func`)
6. **Zero-Lag Regression** (`ZeroLagReg_func`)
7. **Pair-Wise Granger Causality** (`pwGC_func`)
8. **Geweke’s Granger Causality** (`GGC_func`)
9. **[Transfer Function-Based] Coherence** (`CohTF_func`)
10. **Partial Coherence** (`PCoh_func`)
11. **Directed Coherence** (`DCoh_func`)
12. **Partial Directed Coherence** (`PDCoh_func`)
13. **Directed Transfer Function** (`DTF_func`)
14. **Psychophysiological Interaction (PPI)**
15. **Dynamic Causal Modeling (DCM)** *(not yet tested)*

### Tutorial
For guidance on using the methods, refer to the `FC_Methods_tutorial.ipynb` file. Each function also includes a brief description of its parameters for easy customization.

## Applications
While initially developed for analyzing FC in brain signals, this package can be used for any dynamic network.

## Citation
If you use this package in your work, please cite the associated paper:  
[Link to paper](https://www.biorxiv.org/content/10.1101/2024.09.29.615715v1.abstract)

## Support
For further help or to discuss interesting use cases, feel free to reach out via email.
