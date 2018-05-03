# RNA-seq data analysis with DESeq2

# Instructor(s) name(s) and contact information

Michael Love - michaelisaiahlove at gmail

# Workshop Description

In this workshop, we will give a quick overview of the most useful
functions in the DESeq2 package, and a basic RNA-seq analysis. We will
cover: how to quantify transcript expression from FASTQ files using
Salmon, import quantification from Salmon with tximport and tximeta,
generate plots for quality control and exploratory data analysis EDA
(also using MultiQC), perform differential expression (DE) (also using
apeglm), overlap with other experimental data (using AnnotationHub),
and build reports (using ReportingTools and Glimma). We will give a
short example of integration of DESeq2 with the zinbwave package for
single-cell RNA-seq differential expression. The workshop is designed
to be a lab with plenty of time for questions throughout the lab.

## Pre-requisites

* Basic knowledge of R syntax

Non-essential background reading:

* DESeq2 paper: <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4302049/>
* tximport paper: <https://f1000research.com/articles/4-1521/v2>
* apeglm paper: <https://www.biorxiv.org/content/early/2018/04/17/303255>

## Workshop Participation

Students will participate by following along an Rmarkdown document,
and asking questions throughout the workshop.

## _R_ / _Bioconductor_ packages used

* DESeq2
* tximport
* apeglm
* AnnotationHub
* ReportingTools
* Glimma
* zinbwave

## Time outline

| Activity                      | Time |
|-------------------------------|------|
| Overview of packages          | 20m  |
| Quantification and import     | 20m  |
| EDA and DE                    | 20m  |
| Downstream analysis & reports | 20m  |
| ZINB-WaVE integration         | 20m  |
| Additional questions          | 20m  |

# Workshop goals and objectives

Learning goals

* Visually assess quality of RNA-seq data 
* Perform basic differential analysis of RNA-seq data 
* Compare RNA-seq results with other experimental data

Learning objectives

* Quantify transcript expression from FASTQ files
* Import quantification into R/Bioconductor
* Perform quality control and exploratory data analysis
* Perform differential expression
* Overlap with other experimental data
* Build dynamic reports
* Integrate DESeq2 and zinbwave for single-cell RNA-seq data
