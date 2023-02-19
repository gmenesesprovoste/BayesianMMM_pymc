# BayesianMMM_pymc

This jupyter notebook contains the steps to build a basic bayesian mixed-media model (MMM) using the python library PyMC. 
Other libraries used: pandas, numpy, matplotlib, seaborn, arviz and pytensor.

This model includes the carry over effect (the effect of marketing actions is not only immediate, but lasts for several weeks). Shape effects or seasonality are not included.

Dataset fields:
start of the week - weekly revenue - spend in the different channels (in this case are 7)

* adstock_delayed function based on the one created by Dr. Robert Kuebler (article: https://towardsdatascience.com/bayesian-marketing-mix-modeling-in-python-via-pymc3-7b2071f6001a)
