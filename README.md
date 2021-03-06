<a href="https://zenodo.org/badge/latestdoi/243003817"><img src="https://zenodo.org/badge/243003817.svg" alt="DOI"></a>
# Tumour Heterogeneity and Intercellular Networks of Nasopharyngeal Carcinoma at Single Cell Resolution
Nasopharyngeal cancer is a diverse cancer characterised by a heterogeneous microenvironment. Here, we used single cell sequencing to analyse the tumour microenvironment 10 nasopharyngeal and identify 53 different cell types including tolerogenic dendritic cells.
## Environment 
Red Hat Enterprise Linux Server release 6.6	
R version 3.6.1	
Python version 3.7.4	
Java version 1.8.0_60	
## Install software
### Install R package Seurat v2.3.4 	
    source("https://z.umn.edu/archived-seurat")
### Install R package DoubletFinder v2.0
    remotes::install_github('chris-mcginnis-ucsf/DoubletFinder')
### Install R package Monocle v2.8 	
    source("http://bioconductor.org/biocLite.R") 
    biocLite("monocle")	
### Install R package STARTRAC v0.1
    install.packages("devtools")	
    devtools::install_github("Japrin/STARTRAC")	
### Install software GSEA v3.0	
    Download from https://www.gsea-msigdb.org/gsea/downloads.jsp	
### Online software Metascape	
    https://metascape.org/gp/index.html	
### Insatll software ARACNe-AP 
    Download from https://github.com/califano-lab/ARACNe-AP
### Insatll software CellPhoneDB v2.06
    Download from https://github.com/Teichlab/cellphonedb
