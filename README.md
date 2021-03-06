This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

The paper "Industry Compensation under Relocation Risk: A Firm-Level Analysis of the EU Emissions Trading Scheme", written by Ralf Martin,
Mirabelle Mu�ls, Laura B. de Preux and Ulrich J. Wagner (2014), the authors analyze the free permit allocation in the trading phases of the EU ETS
and derive an optimized allocation method. The main results are that significant increases in the effectivness of the policy can be made. 
In this problem set you will recreate their results and gain knowledge about R.

The original paper can be found under https://www.aeaweb.org/articles?id=10.1257/aer.104.8.2482

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)
  
install_github("aunkauf/RTutorOptimalCO2")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorOptimalCO2)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorOptimalCO2")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorOptimalCO2",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
