# Speaker

![Feng Ji]({{ site.baseurl }}/assets/images/fji.png "Feng Ji"){: width="150" }

Dr. Feng Ji\\
Department of Applied Psychology and Human Development\\
University of Toronto\\

Dr. Feng Ji began a tenure stream appointment at the rank of Assistant Professor in the Department of Applied Psychology and Human Development. Dr. Ji received a PhD in Biostatistics from the University of California, Berkeley. Dr. Ji has extensive expertise in applying, evaluating, and developing quantitative and statistical methods in behavioral, educational, and social sciences research. His peer-reviewed articles have appeared in methodology journals such as Psychometrika, Psychological Methods, and Multivariate Behavioral Research, as well as substantive research journals such as Child Development and Applied Linguistics. Dr. Ji’s academic expertise is complemented by considerable industry experience: at Google as a research data scientist and at American College Testing (ACT) as a research psychometrician. He is on the editorial board of several journals such as Behavior Research Methods and Psychological Review.

# Title

Valid standard errors for Bayesian quantile regression with clustered and independent data



# Abstract

In Bayesian quantile regression, the most commonly used likelihood is the asymmetric Laplace (AL) likelihood. The reason for this choice is not that it is a plausible data-generating model but that the corresponding maximum likelihood estimator is identical to the classical estimator by Koenker and Bassett (1978), and in that sense, the AL likelihood can be thought of as a working likelihood. AL-based quantile regression has been shown to produce good finite-sample Bayesian point estimates and to be consistent. However, if the AL distribution does not correspond to the data-generating distribution, credible intervals based on posterior standard deviations can have poor coverage. Yang, Wang, and He (2016) proposed an adjustment to the posterior covariance matrix that produces asymptotically valid intervals. However, we show that this adjustment is sensitive to the choice of scale parameter for the AL likelihood and can lead to poor coverage when the sample size is small to moderate. We therefore propose using Infinitesimal Jackknife (IJ) standard errors (Giordano & Broderick, 2023). These standard errors do not require resampling but can be obtained from a single MCMC run. We also propose a version of IJ standard errors for clustered data. Simulations and applications to real data show that the IJ standard errors have good frequentist properties, both for independent and clustered data. We provide an R-package, IJSE, that computes IJ standard errors for clustered or independent data after estimation with the brms wrapper in R for Stan.
