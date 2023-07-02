# Systematically testing human HMBS missense variants to reveal mechanism and pathogenic variation

_*Necessary notebook/scripts to run near all analysis described in the manuscript.*_

# Dependencies
* R version 3.6.3 or higher
* [OpenPyMol](https://github.com/schrodinger/pymol-open-source/releases) 1.8 or higher

Many of the scripts in this repository depend on the R packages below. Please install them before using.
* beeswarm: Install via CRAN
* data.table: Install via CRAN
* dplyr: Install via CRAN
* ggplot2: Install via CRAN
* ggpubr: Install via CRAN
* mixtools: Install via CRAN
* maveLLR: Install via devtoolsfrom jweile/maveLLR
* pROC: Install via CRAN
* scales: Install via CRAN
* stringi: Install via CRAN
* stringr: Install via CRAN
* tidyverse: Install via CRAN
* yogitools: Install via devtools from jweile/yogitools
* yogiroc: Install via devtoolsfrom jweile/yogiroc
* zoo: Install via CRAN


## File descriptions
* **Computational_Predictor_Scores/**: A folder containing in-silico variant effect predictions from DeMaSk, ESM1b, EVE, REVEL, Provean, SIFT,  and VARITY.
* **HMBS_Biochemistry/**: Curated results from previous studies pertaining to the enzymatic activity of HMBS variants in vitro, FreeSASA and DDGun scores, and information about HMBS structural features. An OpenPyMol script that overlays the combined HMBS map median scores on the crystal structure (Protein Data Bank (PDB) ID: 5M6R or 3ECR) 
* **Reference_Data/**: A folder containing reference datasets, encompassing genotype/phenotype information (files named Age_of_Disease_Onset, Disease_Severity), reference sets of disease- and non-disease-associated variants collected by European expert centres and curated from ClinVar and gnomAD, respectively, and a copy of the UK biobank database entry for HMBS. 
* **HMBS_Functional_Scores/**: Experimentally measured functional impact values from the erythroid-specific, ubiquitous and combined HMBS maps.
* **HMBS_Analysis.Rmd**: Produces near all figures in the manuscript
<hr>
