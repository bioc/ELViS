# ELViS 1.1.11
* Added error handling code regarding conda env creation error

# ELViS 1.1.10
* Reflected changes made in 1.1.9 to test scripts
* If conda env creation fails in samtools_reticulate mode, it defaults to Rsamtools for base-level read depth calculation.

# ELViS 1.1.9
* Using reticulate to install and use conda environment

# ELViS 1.1.8
* Fixed some incompatibility issue with basilisk package. basilisk does not support conda package installation at least for now. So partly reverted to reticulate package for samtools installation.

# ELViS 1.1.1-1.1.7
* Build error fix

# ELViS 1.1.0
* Released in Bioconductor

# ELViS 0.99.13
* Fixed missing dependency

# ELViS 0.99.12
* Fixed formatting errors in vignette

# ELViS 0.99.11
* Test fix

# ELViS 0.99.10
* Vignette "installation" section typo correction

# ELViS 0.99.9
* Installation chunk eval=FALSE

# ELViS 0.99.8
* Added an installation instruction to the vignette


# ELViS 0.99.7
* R version dependency update : R (>= 4.5.0)

# ELViS 0.99.6
* Added unit tests for make_baseline_vec, make_col_pal_fin_gene, stopifnot_class_ge1, stopifnot_list_ge1, yaxis_hy

# ELViS 0.99.5

* Fixes according to initial main review from Bioconductor 
  - previous version had issue in updating

# ELViS 0.99.4

* Fixes according to initial main review from Bioconductor 

# ELViS 0.99.3

* Fixed again build failure in Bioconductor server

# ELViS 0.99.2

* Fixed build failure in Bioconductor server

# ELViS 0.99.1

* Fixes according to initial pre-review from Bioconductor

# ELViS 0.99.0

* Initial Bioconductor submission.
