---
title: "Estimating Neighborhood Asking Rents using Scraped Craigslist Rental Listings"
excerpt: "Bayesian forecasting model of Seattle neighborhood rents"
collection: etc
---

Visit the project site [here](http://hesscl.com/smooth-sea).

A working paper that introduces a spatial and non-spatial forecasting models for census tract rent estimates in Seattle, WA. The Bayesian models used as forecasting candidates in this paper draw on different error structures to predict quarterly rent levels among the 134 census tracts in Seattle. All posterior distributions are estimated with integrated nested Laplace approximations (INLA), which indirectly provides a flexible imputation method for tracts with missing data in a given quarter. The model specification with the best accuracy on the current test data (i.e. 2018 Q2) incorporates non-spatial and spatial random effects for tracts along with autoregressive (order 1) and exchangeable random effects for quarters.
