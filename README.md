# DemographicCompetence

A guide to the use of the supplied R code (reproduced from the Supplementary Material)

The R code provided in the supplementary materials for the manuscript is modular by design. In order to reproduce the results as displayed in the main text of the article it is necessary to:

1.	Set an appropriate working directory or file path for saving the substantial number of results files produced by the models
2.	Run HwM_MainText_DD.Rmd (provided here as Rmarkdown code)
3.	Run HwM_MainTest_FD.Rmd (provided here as Rmarkdown code)
4.	Run HwM_Plotting.Rmd (provided here as Rmarkdown code)

We additionally provide equivalent code for models with different orders of life history events as detailed in SM2 and age structure as detailed in SM3. The former (SM2) outputs results in the same format as the models from the main text but with slightly different file names. Consequently, the plotting code provided can also be used for these outputs once the names of the input files in the plotting code file have been changed appropriately. The latter (SM3) outputs results in a slightly different format and we provide separate plotting code for these results.
