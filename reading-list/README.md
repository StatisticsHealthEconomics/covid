# Selected reading material for the project

The analysis required for this project is focused mainly on "*meta-analysis*", possibly using binary or count outcomes, which would require generalised linear models. These are regression models that can be used when the outcome variable can**not** be safely assumed to be generated from a process described by a Normal distribution. Instead, relevant cases are when the data are binary (modelled using a Binomial or Bernoulli distribution) or counts (modelled using a Poisson distribution). Other types of models (including "random effects") can and should be explored.

Here are some relevant supporting material that you can have a look at

## Meta-analysis and evidence synthesis
- [*Doing Meta-Analysis in `R`*](https://bookdown.org/MathiasHarrer/Doing_Meta_Analysis_in_R/). A **very** good online book on how to conduct meta-analysis using `R`. Mixes up nicely the theory and the practical application of meta-analysis. Probably the first piece of literature you should concentrate on.
- [Evidence Synthesis for Decision Making in Healthcare](https://onlinelibrary-wiley-com.libproxy.ucl.ac.uk/doi/book/10.1002/9781119942986). A very good book on evidence synthesis (a form of generalised meta-analysis), with applications in healthcare and economic evaluations. Most of the models are applicable to other contexts too. Most of the modelling is under the Bayesian approach, but the general principles apply more widely.
- []()

### `R` packages for meta-analysis and evidence synthesis
- [metafor](https://wviechtb.github.io/metafor/). A comprehensive collection of functions for conducting meta-analyses in `R`.
- [multinna](https://dmphillippo.github.io/multinma/). A more general package that can do more than simple meta-analysis, but can aid with that too --- exclusively under the Bayesian approach.
- [nmaINLA](https://gunhanb.github.io/nmaINLA/). A package to run meta-analysis using Integrated Nested Laplace Approximation (INLA). Helpful to conduct Bayesian analyses and save on computational time.

## Systematic literature review
- [What are systematic reviews? ](https://library-guides.ucl.ac.uk/systematic-reviews/what). This is a UCL webpage explaining the meaning and details of systematic literature reviews (SLRs). It contains several links to other resources --- it will be important for you to familiarise with the general principles of conducting a SLR, even though the data for this particular project will be provided and the SLR has already been conducted. 

### Some `R` packages for SLRs
- [litsearchr](https://elizagrames.github.io/litsearchr/)
- [revtools](https://revtools.net/). A package containing tools for the visualisation of evidence syntheses using `R`


## Bayesian GLM and Bayesian modelling in general

- [*Bayes Rule*](https://www.bayesrulesbook.com/). This is a very good book on Bayesian modelling and it's useful in general. 
- [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.
- 

## GLM 

- [Chapter 8 of *Data analysis in `R`*](https://bookdown.org/steve_midway/DAR/glms-generalized-linear-models.html). A good book on modelling using `R`, mainly using frequentist procedures. This can be helpful to understand how to manipulate the data and using `R` to prepare and analyse them.

## General stats

- [*Introduction to statistical concepts*](https://gianluca.statistica.it/teaching/intro-stats/). A basic description of fundamental statistical concepts (from both Bayesian and frequentist perspective). Chapter 5 does contain some brief introduction to regression analysis and GLMs.

## Hierarchical/multilevel modelling
- [Bayesian inference with INLA (specifically chapters 3 and 4](https://becarioprecario.bitbucket.io/inla-gitbook/index.html). This is a very good book on the basics of Bayesian modelling, but using "Integrated Nested Laplace Approximation" for computation. It may be a bit technical, but useful, particularly when dealing with larger datasets.
- [Data Analysis Using Regression and Multilevel/Hierarchical Models ](https://www-cambridge-org.libproxy.ucl.ac.uk/highereducation/books/data-analysis-using-regression-and-multilevel-hierarchical-models/32A29531C7FD730C3A68951A17C9D983). This is a comprehensive manual for the applied researcher who wants to perform data analysis using linear and nonlinear regression and multilevel models. 


