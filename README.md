# tcc_IanyMaia
Cement raw meal fineness  modelling: a lag and smoothing study

This project is part of a conclude work developed at Universidade Federal do Ceará - Campus de Russas, and is relate to a study of raw flour granulometry from a cement plant located at Ceará state of Brazil. 

This repository conain:

- Pre-processed data sets used in the analysis;
- R script of the analysis;
- and some results discusses in the manuscript.


```{r message=FALSE, warning=FALSE, include=FALSE, paged.print=FALSE}
if(!require(plyr)) install.packages("plyr");require(plyr)
if(!require(tidyverse)) install.packages("tidyverse");library(tidyverse)
if(!require(dplyr)) install.packages("dplyr");require(dplyr)
if(!require(ggplot2)) install.packages("ggplot2");require(ggplot2)
if(!require(data.table)) install.packages("data.table");require(data.table) 
if(!require(kableExtra)) install.packages("kableExtra");require(kableExtra) 
if(!require(leaps)) install.packages("leaps");require(leaps)
if(!require(DescTools)) install.packages("DescTools");require(DescTools)
if(!require(purrr)) install.packages("purrr");require(purrr) 
if(!require(mgcv)) install.packages("mgcv");require(mgcv) 
if(!require(ggpmisc)) install.packages("ggpmisc");require(ggpmisc)
if(!require(msir)) install.packages("msir");require(msir) 
if(!require(glmnet)) install.packages("glmnet");require(glmnet) 
if(!require(coefplot)) install.packages("coefplot");require(coefplot) 
if(!require(pracma)) install.packages("pracma");require(pracma) 
if(!require(zoo)) install.packages("zoo");require(zoo) 
if(!require(ggcorrplot)) install.packages("ggcorrplot");require(ggcorrplot)
if(!require(caret)) install.packages("caret");require(caret)
```


