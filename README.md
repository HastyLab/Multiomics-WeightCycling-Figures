# 	Multiomics reveals persistence of obesity-associated immune cell phenotypes in adipose tissue during weight loss and weight regain in mice

## Reproducing Figures
This repository provides code to reproduce relevant figures in the following publication: ***Under Review***. If you use code accessed through this github resource, please remember to cite our work.

## Citation Information:

The associated manuscript is currently under peer review, but you can cite our pre-print: 

### Multiomics reveals persistence of obesity-associated immune cell phenotypes in adipose tissue during weight loss and subsequent weight regain.

#### Matthew A Cottam, Heather L Caslin, Nathan C Winn, Alyssa H Hasty 

##### bioRxiv 2021.08.20.455954; **doi:** https://doi.org/10.1101/2021.08.20.455954 

Access to APA or BibTeX formatted citation information can be found on the right panel under "Cite this repository".

## Instructions 

### Downloading the data
To generate any of our figures, you will need our Seurat v4 data object (IntegratedData.rds). This can be accessed from the NCBI GEO at: 

* accession number: GSE182233 
* link: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE182233

Clicking this will allow you to download the integrated date file directly: <a href="https://www.ncbi.nlm.nih.gov/geo/download/?acc=GSE182233&format=file&file=GSE182233%5FIntegratedData%2Erds%2Egz">IntegratedData.rds</a>. You will need to gunzip this file prior to importing it into R.

You can also generate this integrated data file yourself by following <a href="https://github.com/HastyLab/Multiomics-WeightCycling-Vignettes">our vignettes.</a> 

### Downloading R code for figures

To access our code to reproduce figures in the form of R Notebooks AND download necessary files, clone this github repository or download the files as a .zip using this <a href="https://github.com/HastyLab/Multiomics-WeightCycling-Figures/archive/refs/heads/main.zip">download link</a>.

The HTML files contain the results of running the entire notebook. If you'd like to see how we generated our figures without running the code yourself, you can find those HTML files located in the Figure_HTMLs.zip or download them as a .zip using this <a href="https://github.com/HastyLab/Multiomics-WeightCycling-Figures/raw/main/Figure_HTMLs.zip">download link</a>. The HTMLs are also located in each individual figure folder.
