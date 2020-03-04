# Identification-of-Multiple-Cancers
Generalized Workflow Design for Biomarker  Identification of Multiple Cancers
# Getting Started
To use the codes and relevent files, first we need some datasets and some tools in which you can run these codes. Data Collection Section describes from where data can be collected & Installation Section describes where to get the desired tools. Finally, Working Process Section describes through which sequence the work has been done.
# Data Collection
mRNA microarray datasets and microRNA expression dataset have been used for this experiment. All these datasets were downloaded from GEO.
# Installation
For implementing Student's T-Test, R language & RStudio platform have been used. For additional comparing and counting jobs, Python has been used. Pandas package was used to read csv files. RStudio is available in RStudio Official Website. Anaconda software can be downloaded from Anaconda Official Website as well. Moreover, Pandas Library was intalled by writing following command in Anaconda Prompt:

conda install -c anaconda pandas
# Working Process
The following steps were followed:

1.For each dataset, get the processed data from GEO2R, run R code to evaluate adjusted P-values and select the desired genes. All files can be found in the corresponding folders.
2.For each selected microRNA, get target genes using miRecords online tool.
3.Now run Python files located in 'Python Codes To Compare and Select DEGs, DEMs, Common DEGs among Target Genes' floder to get the desired biomarkers.
