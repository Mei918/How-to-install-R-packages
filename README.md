# How-to-install-R-packages
How to install R packages

![image](https://github.com/Mei918/How-to-install-R-packages/assets/59069778/b49cfb31-cf88-4790-8b4e-0954bbc22421)

#CRAN

install.packages("ggplot2")

#Bioconductor

BiocManager::install("devtools")

#Github

remotes::install_github("satijalab/seurat", "seurat5", quiet = TRUE)
