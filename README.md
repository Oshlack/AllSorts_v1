

<p align="center">
<img src=https://github.com/Oshlack/Baller/blob/master/AllSorts.png height=200 />  
</p>

<p><strong>And we're updating this... But stick around here for the old version! The new ALLSorts can be found here: https://github.com/Oshlack/AllSorts.</strong></p>

Welcome to the All Sorts Readme!

AllSorts is a B-Cell Acute Lymphoblastic Leukemia Classifier, aiming to classify ALL into its various sub-types using RNA-Seq data to observe gene expression profiles. 

The tool is an R package which includes vignettes for you to peruse at your own pace which will explain how to use the classifier.

#Installation
To install an R package from GitHub, first you will need to install the devtools packge. So open an R/RStudio session:

    install.packages("devtools")

Load the devtools package.

    library(devtools)

Then simply use the install_github("author/package") function of devtools. So for AllSorts that would simply be:

    install_github("Oshlack/AllSorts_v1")

Alternatively if one does not have the required BioConductor packages such as edgeR/limma one may wish to install using BiocLite. Note devtools are still required in this case.

    ## try http:// if https:// URLs are not supported
    source("https://bioconductor.org/biocLite.R")
    biocLite("Oshlack/AllSorts")

   
#Manual/Tutorial

To read the manual please read the R vignette after installing the pacakge for the most up-to-date manual and tutorial, alternatively read the package wiki.

https://github.com/Oshlack/AllSorts/wiki
