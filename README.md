
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `osca_LIIGH_UNAM_2020`

<!-- badges: start -->

<!-- badges: end -->

Here you can find the files for the march 2020 single cell
RNA-sequencing (scRNA-seq) course for
[LCG-EJ-UNAM](https://lcgej.unam.mx/) at
[LIIGH-UNAM](https://liigh.unam.mx/) based on the book [Orchestrating
Single Cell Analysis with Bioconductor](https://osca.bioconductor.org/)
and [WEHI’s scRNA-seq
course](https://drive.google.com/drive/folders/1cn5d-Ey7-kkMiex8-74qxvxtCQT6o72h)
by [Peter Hickey](https://www.peterhickey.org/).

Instructor: [Leonardo Collado-Torres](http://lcolladotor.github.io/).

## Install required packages

``` r
## For installing Bioconductor packages
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

## Install required packages
BiocManager::install(c(
    'SingleCellExperiment'
))
```

## Course files

1.  Introduction
2.  Data Infrastructure and Import
3.  Quality Control
4.  Normalization
5.  Feature Selection
6.  Dimensionality Reduction
7.  Clustering
8.  Marker gene detection
9.  Cell Annotation
10. Data Integration
11. Multi-Sample Comparisons
12. Spatial Transcriptomics
