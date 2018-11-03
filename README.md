# Practice

## FLOWSOM of sep trans DM27 and DP21 CD4 T cells
## Coded by Millie Perez and modded by Jason M. Grayson
## Revision start 8-21-2018

# This code is used to take scaled surface after FlowTrans and generate a Self Organizing Map(SOM)

## wipe the workspace
rm(list = ls())
setwd("~/Desktop/SOM_KI67 copy")


library(flowCore)
library(flowTrans)
library(tidyverse)
library(RColorBrewer)
library(latticeExtra) ##3d barplot
library(FlowSOM) #FlowSOM
