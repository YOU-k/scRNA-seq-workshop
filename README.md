# scRNA-seq analysis workshop

![.github/workflows/basic_checks.yaml](https://github.com/YOU-k/scRNA-seq-workshop/workflows/.github/workflows/basic_checks.yaml/badge.svg)

# Workshop Description

In this workshop (presented in Mandarin), you will learn how to analyse single-cell RNA-sequencing count data produced by the Chromium 10x platform using R/Bioconductor. This will include reading the data into R, pre-processing data, normalization, feature selection, dimensionality reduction and downstream analysis, such as clustering and cell type annotation. 

Expectation: You will learn how to generate common plots for analysis and visualisation of single cell gene expfression data, such as diagnostic plots to assess the data quality as well as dimensionality reduction techniques such as principal components analysis and t-distributed stochastic neighbourhood embedding (t-SNE). The material we will be covering on single-cell RNA-sequencing analysis is a subset of the work of Amerzquita et al. (2020) Nature Methods,17:137–145 available at https://osca.bioconductor.org. 

# Pre-requisites 

The course is aimed at PhD students, Master’s students, and third & fourth year undergraduate students. Some basic R knowledge is assumed - this is not an introduction to R course. If you are not familiar with the R statistical programming language it is compulsory that you work through an introductory R course before you attend this workshop.


# Participation

After the lecture, participants are expected to follow along the hands-on session. we highly recommend participants bringing your own laptop.

# _R_ / _Bioconductor_ packages used

The following R/Bioconductor packages will be explicitly used: 

* DropletUtils
* scran
* scater
* singleR

# Time outline

| Activity                         | Time |
|----------------------------------|------|
| Introduction to scRNA-seq        | 10m  |
| Analysis workflow                | 20m  |
| Hands on session                 | 15m  |
| Q & A                            | 10m  |

# Workshop goals and objectives

## Learning goals

 - Understand how scRNA-seq data are generated.
 - Learn of existing packages and functions used in this workshop. 
 - Become familiar with the fundamental concepts of normalization, dimension reduction, clustering.

## Learning objectives

 - Analyze a 10x dataset which contains 4K cells. 
 - Run basic steps included in scRNA-seq analysis.
 - Learn how to interpret on scRNA-seq analysis generated results.
 - Take away some tips and tricks on generating related plots.