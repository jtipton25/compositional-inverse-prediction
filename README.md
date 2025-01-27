# Compositional-inverse-prediction Repository

This repository contains code and data from the paper:

Tipton, John., Hooten, M.B., Nolan, C., Booth, R.K., McLachlan, J. (In Review).  Predicting paleoclimate from compositional data using multivariate Gaussian process inverse prediction.



To reproduce the results in the manuscript, clone this repository and open the RStudio project using the file `compositional-inverse-prediction.Rproj`. Then:
    
1) Install the BayesComposition `R` package using `devtools` as

```
library(devtools)
install_github("jtipton25/BayesComposition")
```

2) To generate the simulation study results using the BUMMER data model, run the `Rmarkdown` document

```
appendix-simulation-dm-bummer.Rmd
```

3) To generate the simulation study results using the MVGP data model, run the `Rmarkdown` document

```
appendix-simulation-dm.Rmd
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
