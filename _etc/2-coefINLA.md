---
title: "coefINLA: high-level graphics for INLA models"
excerpt: "Visualize fixed effect posterior distributions as a ridgeplot"
collection: etc
---

Visit the repository [here](http://github.com/hesscl/coefINLA), or download using `devtools::install_github("hesscl/coefINLA")` from R.

A GitHub repository with a function for visualizing posterior distributions of coefficients estimated using `R-INLA` as a ridgeplot. This `ggplot2`-based graphic provides a visual representation of the coefficient tables returned by `summary()` with models fit using `inla()`, showing the median coefficient value along with 95% credible intervals for each model covariate.
