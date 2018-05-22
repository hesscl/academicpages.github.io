---
title: "Estimating Neighborhood Asking Rents using Scraped Craigslist Rental Listings"
excerpt: "Bayesian forecasting model of Seattle neighborhood rents"
collection: portfolio
---

Visit the `flexdashboard` site [here](http://hesscl.com/smooth-sea)

A working paper that introduces a spatiotemporal forecasting model for census tract rent estimates in Seattle, WA. The Bayesian models used as forecasting candidates in this paper draw on different error structures to predict quarterly rent levels among the 134 census tracts in Seattle. This estimation method is useful given the missingness and low listing counts among some tracts in the panel. The spatiotemporal model with the best accuracy incorporates a local spatial random effect, an autoregressive random effect for the prior quarter, and a space-time interaction random effect for each tract to account for trends different from the average quarterly difference.
