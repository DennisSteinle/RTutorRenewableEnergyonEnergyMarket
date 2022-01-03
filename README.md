This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This thesis presents an interactive problem set based on the paper "Setting with the sun: The impacts of renewable energy on wholesale power markets" by Bushnell and Novan (2018). The whole article and data can be found <a href="https://www.journals.uchicago.edu/doi/full/10.1086/713249" target="_blank">on this website</a>. There, we want to see how the electricity development has developed in the following years and whether there has been an effect of renewable energies on the electricity price and the production of conventional energy. 

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("DennisSteinle/RTutorRenewableEnergyonEnergyMarket")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorRenewableEnergyonEnergyMarket)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorRenewableEnergyonEnergyMarket")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorRenewableEnergyonEnergyMarket",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
