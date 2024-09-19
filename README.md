# Awesome Survival Analysis

A curated list of awesome resources for survival analysis.

## Packages

### Python Packages

- [lifelines](https://pypi.org/project/lifelines/): A complete survival analysis library, written in pure Python.
- [scikit-survival](https://pypi.org/project/scikit-survival/): A Python module for survival analysis built on top of scikit-learn.
- [PySurvival](https://pypi.org/project/pysurvival/): A Python package for survival analysis, offering 10+ models from Cox PH to Random Survival Forests, with tools for model building, cross-validation, and prediction.

### R Packages
- [CRAN Task View: Survival Analysis](https://cran.r-project.org/web/views/Survival.html): A comprehensive overview of available R packages for survival analysis, including tools for estimation, regression, and multistate models, along with many others aimed at the analysis of time-to-event data.
- [survival](https://cran.r-project.org/web/packages/survival/index.html): Contains the core survival analysis routines, including definition of Surv objects, Kaplan-Meier curves, and Cox models.
- [Cox model predictions](https://stat.ethz.ch/R-manual/R-devel/library/survival/html/predict.coxph.html): Documentation for making predictions from a Cox regression model.
- [Concordance in Survival Analysis](https://rweb.webapps.cla.umn.edu/R/library/survival/doc/concordance.pdf): A document detailing the concept of concordance in survival analysis.
- [dynpred](https://cran.r-project.org/web/packages/dynpred/index.html): Tools for the dynamic prediction in survival analysis.
- [pec](https://search.r-project.org/CRAN/refmans/pec/html/predictSurvProb.html): Prediction error curves for risk prediction models in survival analysis.
- [Landmarking](https://cran.r-project.org/web/packages/Landmarking/index.html): Methods for Landmarking and Survival Analysis.
- [rstanarm](https://cran.r-project.org/web/packages/rstanarm/index.html): Bayesian Applied Regression Modeling via Stan.
- [JM](https://cran.r-project.org/web/packages/JM/index.html): Joint Modeling of Longitudinal and Time-to-Event Data.
- [JMbayes](https://cran.r-project.org/web/packages/JMbayes/index.html): Joint modeling of longitudinal and time-to-event data, employing Bayesian methods with MCMC techniques
- [randomForestSRC](https://cran.r-project.org/web/packages/randomForestSRC/index.html): Random Forests for Survival, Regression, and Classification (RF-SRC).
- [LTRCforests](https://cran.r-project.org/web/packages/LTRCforests/index.html): Analyzes Long-Term, Right-Censored longitudinal data using random forests, suitable for censored data in medical and reliability studies.
- [rms](https://cran.r-project.org/web/packages/rms/index.html): Regression modeling, testing, estimation, validation, graphics, prediction, and typesetting by storing enhanced model design attributes in the fit.
- [survPresmooth](https://cran.r-project.org/web/packages/survPresmooth/index.html): Provides presmoothed estimation in survival analysis, enhancing classical estimators with methods for incorporating all data, including censored observations.
- [survminer](https://cran.r-project.org/web/packages/survminer/index.html): Facilitates the creation of survival plots, featuring 'number at risk' tables, censoring count plots, and options for customized, publication-ready outputs.
- [gwasurvivr](https://bioc.cran.dev/packages/3.16/bioc/html/gwasurvivr.html): Enables efficient analysis of genetic variants' impact on survival outcomes.
- [cenROC](https://cran.r-project.org/web/packages/cenROC/index.html): Provides tools for analyzing time-dependent receiver operating characteristic (ROC) curves with right-censored event time data.
- [survivalmodels](https://cran.r-project.org/web/packages/survivalmodels/index.html): Extensive suite for survival analysis in R, offering a broad array of tools for modeling, prediction, and inference. Features support for time-dependent covariates, multiple types of censoring, and complex survival models.
- [survivalAnalysis](https://cran.r-project.org/web/packages/survivalAnalysis/index.html): High-Level Interface for Survival Analysis and Associated Plots
- [SurvMetrics](https://cran.r-project.org/web/packages/SurvMetrics/index.html): Comprehensive performance metrics for survival models
- [icensBKL](https://cran.r-project.org/web/packages/icensBKL/index.html): Bias-corrected estimation for interval-censored data
- [SmoothHazard](https://cran.r-project.org/web/packages/SmoothHazard/index.html): Smooth hazard models for interval-censored data
- [bayesSurv](https://cran.rstudio.com/web/packages/BayesSUR/index.html): Bayesian Survival Regression with Flexible Error and Random Effects Distributions
- [censored](https://cran.r-project.org/web/packages/censored/index.html): Censored is the backend engines that are used by [parsnip](https://parsnip.tidymodels.org/articles/parsnip.html) which of itself is part of the tidymodels ecosystem.
- [tidymodels](https://www.tidymodels.org): Tidymodels is a collection of packages for modeling and machine learning using tidyverse principles. It includes many ML implementations, including survival analysis. Use the search option to find the survival analysis package (mainly {parsnip} and {censored}) you need.

### Julia Packages

- [Survival.jl](https://juliastats.org/Survival.jl/latest/): Provides types and methods for performing survival analysis in Julia (event times, Kaplan-Meier Estimator, Nelson-Aalen Estimator, Cox Proportional Hazards Model)


## Vignettes

- [Time-dependent covariates in survival analysis](https://cran.r-project.org/web/packages/survival/vignettes/timedep.pdf): A vignette discussing the use of time-dependent covariates in the context of survival analysis.
- [Competing Risks in Survival Analysis](https://cran.r-project.org/web/packages/survival/vignettes/compete.pdf): A vignette covering multi-state models and competing risks from the `survival` package.
- [How to use the Landmarking package](https://cran.r-project.org/web/packages/Landmarking/vignettes/how_to_use.html): A guide on using the Landmarking package in R.
- [Joint Modeling using rstanarm](https://cran.r-project.org/web/packages/rstanarm/vignettes/jm.html): Vignette on joint modeling using the rstanarm package.
- [Survival Analysis using tidymodels](https://www.tidymodels.org/learn/statistics/survival-metrics/): A ‘Get Started’ for event-time based models. 

## Tutorials
- [Survival Analysis Basics](http://www.sthda.com/english/wiki/survival-analysis-basics): A comprehensive tutorial on survival analysis basics by STHDA, covering key concepts, methods, and R implementation.
- [Survival Analysis in R](https://www.emilyzabor.com/tutorials/survival_analysis_in_r_tutorial.html): An extensive tutorial by Emily Zabor on performing survival analysis in R.
- [An Introduction to Joint Modeling in R](https://www.r-bloggers.com/2018/02/an-introduction-to-joint-modeling-in-r/): A tutorial on joint modeling in R from R-bloggers.
- [Survival Analysis in tidymodels](https://www.youtube.com/watch?v=orAlJ321hOc&amp;pp=ygUxc3Vydml2YWwgYW5hbHlzaXMgaW4gdGlkeW1vZGVscyB3aXRoIEp1bGlhIFNpbGdlIA%3D%3D): A brief intro to survival analysis by Max Kuhn (author of the tidymodels).
- [Survival Analysis in tidymodels 2](https://www.youtube.com/watch?v=E5XG1c7tNW0&amp;pp=ygUxc3Vydml2YWwgYW5hbHlzaXMgaW4gdGlkeW1vZGVscyB3aXRoIEp1bGlhIFNpbGdlIA%3D%3D):  A brief intro to survival analysis from the 2022 R conference.

## Papers
- [Prognostic Factor Analysis using Survival Data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3321736/): An academic article from NCBI discussing methods and considerations in prognostic factor analysis using survival data, providing insights into advanced survival analysis techniques.
- [Dynamic Predictions using Joint Modeling and Landmarking](https://www.drizopoulos.com/pdf/papers/BiomJrn_JMvsLM_paper.pdf): Dynamic Predictions with Time-Dependent Covariates in Survival Analysis using Joint Modeling and Landmarking.
- [Concordance for Survival Time Data](https://www.mayo.edu/research/documents/biostat-80pdf/doc-10027891): Concordance in survival analysis with fixed and time-dependent covariates, including methods for dealing with ties in predictor and event times.








