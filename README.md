# Analysis of the voting results

In this project I use Bayesian approach to study results of US presidential elections in years 2000-2020. The goal of the project is to determine political prefernces (Democratic of Republican) os the US people both on state and county level and try to model this results using some social and political parameters as predictors.



# Data sets

[1] MIT. MIT Election Lab. https://electionlab.mit.edu/data, 2023. Accessed: 2023-11-15.

[2] FRED. Federal Reserve Bank. https://fred.stlouisfed.org/, 2023. Accessed: 2023-11-15.

# Directory Structure

* README.md: this file
* R/: directory whith all R files
    * importData.Rmd: file to import data from Federal Reserve Bank data base
    * byState_all.Rmd: analysis of the election results on the state level
    * byCounty_all.Rmd: analysis of the election results on the county level
    * Ohio_LR_JAGS.Rmd: Linear Regression analysis of the county data in Ohio
    * Massachusetts_LR_JAGS.Rmd: Linear Regression analysis of the county data in Massachusetts
* data/: in this directory all used data is stored
    * Gini/: county data downloaded from FRED by importData.Rmd notebook
    * dataverse_files: state data from MIT
* TeX/: directory for the report document
    * figs/: all figures here are created by Rmd files

