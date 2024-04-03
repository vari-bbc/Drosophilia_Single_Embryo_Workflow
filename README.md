# Drosophilia_Single_Embryo_Workflow

This .Rmd file contains code to run WGCNA for Drosophilia single embryo rna-seq data as well as correlating module eigen genes with mass-spec metabolic data. 
Data contain male and female flies in pseduo-time order. Generalized additve models are used to both remove large outliers in the metabolic data to focus regression estimates closer to the population mean.
Genearlized additive models are also used to identify the transcription activation (the earliest pseudotime with 95% confidence the mean gene expression is >1).
The workflow can take awhile to run. Also be sure to see the soft power and type of correlation (eg signed-hybrid) that best suits your data.
The workflow will output a series of .csvs that make plotting in other softwares easier.  
