This repo contains my first ever R script in PDF that covers basic EDA in R programing and XGbooxt model for machine learning(ML)

**Data set**

IPAdverising data set(http://bit.ly/IPAdvertisingData)

**Dependencies used**

library(tidyr)

library(tidyverse)

**Analysis procedure**

Loading the dataset 

Performing basic descriptive statistical analysis

Data cleaning:dealing with missing values, outlieres and duplicates 
univariate and bivariate analysis

ML model creation

**ML model used**

XG Boost

**ML dependencies**

install.packages("drat", repos="https://cran.rstudio.com")

drat:::addRepo("dmlc")

install.packages("xgboost", repos="http://dmlc.ml/drat/", type = "source")

