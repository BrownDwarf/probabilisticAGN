Jupyter Notebooks
--

This directory houses interactive Jupyter notebooks used in this research.

### Table of Contents


0. Overview of goals and introduction to methods  
  - Introduction to AGN analysis
  - FFT versus Lomb-Scargle and PSD normalization
  - The effect of missing data on the PSD
  - Importance of pixel aperture mask choice
  - The Matern Kernel and EVEREST
  - Clustering in EVEREST kernel properties  
  - Read noise floor


1. Simulating AGN signals  
  - Introduction to scope  
  - Making the TPF-like fits file with scope
  - "Round trip" the simulated signal with detrending to quantify bias


2. GP Kernel flexibility and the power law slope  
  - Gaussian process kernels map directly to PSDs
  - Introdution to celerite
  - What power law slopes can celerite achieve out-of-the-box?
  - What power law slopes can celerite achieve through sums of sines?  
  - CARMA?
  - Achieving other power law slopes with PyTorch/George
  - What metric do we care about? Power law slope versus kernel parameters
  - Extra slope artifact in steep, noise-free powerlaws


3. K2 long-term instrumental signals  
  - Getting the PSD of the instrumental artifacts I: empty pixels
  - Getting the PSD of the instrumental artifacts II: Flat sources
  - Towards an artifact kernel


4. Tuning the kernel "by eye"
  - Hand-tuning GP kernels on OJ 287 long cadence
  - Hand-tuning GP kernels on OJ 287 short cadence
  - Hand-tuning GP kernels on low S/N sources


5. Optimizing, and sampling the kernel in OJ 287
  - Introduction to pymc3, xo, and gradients
  - Introduction to profile likelihood
  - Inferring PSD slope on idealized synthetic lightcurves
  - Inferring PSD slope on noised-up synthetic lightcurves
  - Inferring PSD slope with the wrong kernel model
  - Inferring PSD slope with genuine K2 data
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending with wrong kernel model
  - Inferring PSD slope with genuine lightcurves with simultaneous PLD detrending

6. Optimizing, and sampling the kernel in low S/N sources
  - Inferring PSD slope on idealized synthetic lightcurves
  - Inferring PSD slope on noised-up synthetic lightcurves
  - Inferring PSD slope with the wrong kernel model
  - Inferring PSD slope with genuine K2 data
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending with wrong kernel model
  - Inferring PSD slope with genuine lightcurves with simultaneous PLD detrending


Appendix:
  - Periodogram units and celerite units
