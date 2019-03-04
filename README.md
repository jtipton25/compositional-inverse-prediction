# Compositional-inverse-predciction Repository

This repository contains code and data from the paper

To reproduce the results from:
Tipton, John., Hooten, M.B., Nolan, C., Booth, R.K., McLachlan, J. (In Review).  Predicting Unobserved Climate from Compositional Data using Multivariate Gaussian Process Inverse Prediction. 
    
1) install the BayesComposition `R` package using `devtools` as

```
library(devtools)
install_github("jtipton25/BayesComposition")
```

2) To generate the simulation study results using the BUMMER data model, run the `Rmarkdown` document

```
simulation-dm-bummer.Rmd
```

3) To generate the simulation study results using the MVGP data model, run the `Rmarkdown` document

```
simulation-dm.Rmd
```


4) To generate the results for the analysis of the testate amoebae data, run the `RMarkdown` document

```
testate-appendix.Rmd
```

5) To generate the results for the analysis of the pollen data, run the `RMarkdown` document

```
pollen-appendix.Rmd
```

6) To generate the results for the analysis of the no-analog experiment, run the `RMarkdown` document

```
no-analog-appendix.Rmd
```
