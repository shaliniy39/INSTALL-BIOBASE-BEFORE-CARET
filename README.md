# INSTALL-BIOBASE-BEFORE-CARET
Loading error in caret package "Required package Biobase is not available" 

if (!requireNamespace("BiocManager", quietly = TRUE))
  install.packages("BiocManager")
BiocManager::install("Biobase", version = "3.8")

library(Biobase)
library(caret)
