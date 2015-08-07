# FIRDeconvolution
Python class that performs finite impulse response fitting on time series data, in order to estimate event-related activations. 
It is possible to add covariates to the events, to estimate not just the impulse response function, but also correlation timecourses with other variables. This latter functionality hasn't fully been tested yet, so proceed with caution.

Example use cases are fMRI and pupil analysis. The package performs the linear least squares analysis using numpy.linalg as a backend. 

## Dependencies
numpy, scipy, matplotlib
statsmodels for fitting functionality extension

TODO
- debug the covariate functionality (!)
- bootstrapping the residuals for single-channel data
- extend fitting to ridge regression, using sklearn cross validation

