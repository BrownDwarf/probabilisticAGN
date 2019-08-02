Jupyter Notebooks
--

This directory houses interactive Jupyter notebooks used in this research.

### Table of Contents


0. Overview of goals and introduction to methods  
  - Introduction to AGN analysis
  - FFT versus Lomb-Scargle
  - PSD normalization
  - The effect of missing data on the PSD
  - The Matern Kernel and EVEREST
  - Clustering in EVEREST kernel properties  


1. Simulating AGN signals  
  - Introduction to scope  
  - Making the TPF-like fits file with scope and celerite  


2. GP Kernel flexibility and the power law slope  
  - Introdution to celerite
  - What power law slopes can celerite achieve out-of-the-box?
  - What power law slopes can celerite achieve through sums of sines?  
  - CARMA?
  - Achieving other power law slopes with PyTorch/George
  - What metric do we care about? Power law slope versus kernel parameters


3. K2 long-term instrumental signals  
  - Getting the PSD of the instrumental artifacts I: empty pixels
  - Getting the PSD of the instrumental artifacts II: Flat sources
  - Towards an artifact kernel


4. Guessing, optimizing, and sampling the kernel  
  - Introduction to pymc3, xo, and gradients
  - Inferring PSD slope on idealized synthetic lightcurves
  - Inferring PSD slope on noised-up synthetic lightcurves
  - Inferring PSD slope with the wrong kernel model
  - Inferring PSD slope with genuine K2 data
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending
  - Inferring PSD slope with scope-produced lightcurves with simultaneous PLD detrending with wrong kernel model
  - Inferring PSD slope with genuine lightcurves with simultaneous PLD detrending
