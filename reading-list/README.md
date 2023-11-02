# Selected reading material for the project

The analysis of the dataset is mainly focused on *Generalised linear models*. These are regression models that can be used when the outcome variable can**not** be safely assumed to be generated from a process described by a Normal distribution. Instead, relevant cases are when the data are binary (modelled using a Binomial or Bernoulli distribution) or counts (modelled using a Poisson distribution).

Here are some relevant supporting material that you can have a look at

## Bayesian GLM and Bayesian modelling in general

- [Chapter 12 of *Bayes Rule*](https://www.bayesrulesbook.com/chapter-12). This is a very good book on Bayesian modelling and it's useful in general. This chapter is specifically about Poisson regression. 
- [Chapter 13 of *An Introduction to Bayesian Reasoning and Methods*](https://bookdown.org/kevin_davisross/bayesian-reasoning-and-methods/poisson.html). This is also a relevant book guiding you through the basics of Bayesian analysis and specifically looking at Poisson regression.
- [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.
- 

## GLM 

- [Chapter 8 of *Data analysis in `R`*](https://bookdown.org/steve_midway/DAR/glms-generalized-linear-models.html). A good book on modelling using `R`, mainly using frequentist procedures. This can be helpful to understand how to manipulate the data and using `R` to prepare and analyse them.

## General stats

- [*Introduction to statistical concepts*](https://gianluca.statistica.it/teaching/intro-stats/). A basic description of fundamental statistical concepts (from both Bayesian and frequentist perspective). Chapter 5 does contain some brief introduction to regression analysis and GLMs.

## Spatio-temporal modelling
- [Bayesian inference with INLA (specifically chapters 7 and 8](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.
- [Spatial and Spatio‐temporal Bayesian Models with R‐INLA](https://onlinelibrary-wiley-com.libproxy.ucl.ac.uk/doi/book/10.1002/9781118950203). This book provides a presentation of the combination of Bayesian methodology and spatial statistics, with a series of practical examples which allow the reader to link the statistical theory presented to real data problems. 

## Hierarchical/multilevel modelling
- [Bayesian inference with INLA (specifically chapters 3 and 4](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.

[Data Analysis Using Regression and Multilevel/Hierarchical Models ](https://www-cambridge-org.libproxy.ucl.ac.uk/highereducation/books/data-analysis-using-regression-and-multilevel-hierarchical-models/32A29531C7FD730C3A68951A17C9D983). This is a comprehensive manual for the applied researcher who wants to perform data analysis using linear and nonlinear regression and multilevel models. 

## Covid papers
- [A framework for estimating and visualising excess mortality during the COVID-19 pandemic](https://arxiv.org/abs/2201.06458)
- [Regional excess mortality during the 2020 COVID-19 pandemic: a study of five European countries](https://www.nature.com/articles/s41467-022-28157-3). See also the GitHub repository with data and scripts [here](https://github.com/gkonstantinoudis/ExcessDeathsCOVID)
- [Estimating weekly excess mortality at sub-national level in Italy during the COVID-19 pandemic](https://doi.org/10.1371/journal.pone.0240286)
