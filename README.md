# Course on omic data analysis with R 
This is a short course on omic data analysis with R (2 hours) that is part of the ALEXS [Alpine Exposome Summer School](https://exposomesummerschool.com/) organized by Inserm (IAB Grenoble and IRSET Rennes) and supported by Région Auvergne Rhône-Alpes and [ATHLETE H2020 Project](https://athleteproject.eu/) (Grant agreement No 874583).

The course include three tutorials that can be found here:

- [Dealing with omic data in Bioconductor]
- [Dealing with omic data in Bioconductor]


# Prerequisites

## R environment

For a friendly R environment and being able to run the proposed examples, [Rstudio](https://rstudio.com/products/rstudio/) is highly recommended.

Recommended readings from this wiki:

* [Introduction to R and the R tutorial](https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/1722122263/2020-21+Winter+DataSHIELD+beginners+workshops+including+ATHLETE+GA+workshop)
* [Become familiar with R Studio and basic concepts of R](https://data2knowledge.atlassian.net/wiki/spaces/DSDEV/pages/707428353/Become+familiar+with+R+Studio+and+basic+concepts+of+R)

## Required packages

Open RStudio and execute these R instructions 

```
install.packages(c("readr", "dplyr", "ssh", "resourcer", "DSOpal", "ggrepel"))
install.packages("dsBaseClient", repos = c("https://cran.obiba.org"))
devtools::install_github("isglobal-brge/dsOmicsClient")
```

Maybe for those working in Windows [Rtools](https://cran.r-project.org/bin/windows/Rtools/) could be needed.



