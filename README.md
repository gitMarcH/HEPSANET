## Purpose of this analysis

This repository contains code for Bayesian bivariate random-effects models for the HEPSANET systematic review [PROSPERO registration CRD42020218043] (https://www.crd.york.ac.uk/prospero/display_record.php?ID=CRD42020218043).

The models developed here are similar to those described here:

* [Riley et al (2008)](https://doi.org/10.1002/sim.3441)
* [Reitsma et al (2005)](https://doi.org/10.1016/j.jclinepi.2005.02.022)
* [Owen et al (2018)](https://doi.org/10.1016/j.jclinepi.2018.03.005)

The aim of the analysis is to get meta-analysis estimates of the operational characteristics of diagnostic tests for liver fibrosis and cirrhosis based on different biomarkers.

Specifically we define 4 models, corresponding to those from [Riley et al (2008)](https://doi.org/10.1002/sim.3441).
Each of those models is fitted several times: for each combination of reference diagnostic and experimental diagnostic.

The models are fitted using [R](https://cran.r-project.org) and [JAGS](https://mcmc-jags.sourceforge.io).

The R markdown document (`.Rmd`) contains the general analysis code, while the JAGS model files (`.jags`) contains the JAGS model syntax.
