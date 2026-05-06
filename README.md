# Omics and Bioinformatics Workshop Series

## Overview

This repository contains materials for a three-part workshop series introducing key concepts in omics data analysis and bioinformatics using R and web-based tools. The workshops progress from basic R skills to differential gene expression analysis and functional interpretation of results.

The content is designed for students and researchers with little or no prior experience in R.

## Workshop Structure

### Workshop 1: Introduction to R

This session introduces fundamental R concepts and data structures.

Topics covered:

- Basic mathematical operations in R  
- Creating and using variables  
- Working with vectors  
- Building matrices and data frames  
- Introduction to data visualisation using ggplot2  

Learning outcomes:

- Perform simple calculations in R  
- Store and manipulate data using variables and vectors  
- Structure data using matrices and data frames  
- Create and customise basic plots  

### Workshop 2: Differential Expression Analysis with DESeq2

This session focuses on analysing RNA sequencing data to identify differentially expressed genes.

Topics covered:

- Importing count and metadata files  
- Preparing and checking datasets  
- Running differential expression analysis with DESeq2  
- Processing and filtering results  
- Creating volcano plots using EnhancedVolcano  
- Identifying significantly upregulated genes  
- Exporting gene lists for downstream analysis  

Learning outcomes:

- Understand the structure of RNA sequencing data  
- Perform a basic differential expression analysis  
- Interpret log2 fold change and adjusted p values  
- Generate publication-style visualisations  

### Workshop 3: Gene Ontology Analysis Using StringDB

This session introduces functional analysis of gene lists using an external web tool.

Topics covered:

- Uploading gene lists to StringDB  
- Performing gene set enrichment analysis  
- Exploring Gene Ontology categories  
- Interpreting enriched biological processes  

Learning outcomes:

- Understand the purpose of gene ontology analysis  
- Identify enriched pathways and processes  
- Relate gene expression changes to biological function  
- Develop hypotheses based on analysis results  

## Requirements

To run the R-based sections of this workshop, you will need:

- R (version 4.0 or later recommended)  
- RStudio (recommended)

Required R packages:

- tidyverse  
- DESeq2  
- EnhancedVolcano  
- magick  

You can install missing packages using:

```
install.packages("tidyverse")
install.packages("EnhancedVolcano")
install.packages("magick")
```

For DESeq2, use:

```
if (!requireNamespace("BiocManager", quietly = TRUE))
  install.packages("BiocManager")
BiocManager::install("DESeq2")
```

## Data Files

The workshop uses example datasets located in the `data/` directory:

- RNA sequencing count data  
- Sample metadata  
- Output gene lists generated during analysis  

Ensure these files are present before running the scripts.

## Usage

1. Open the workshop file in RStudio or another compatible environment  
2. Run each code chunk sequentially  
3. Follow along with the explanations and complete challenge tasks  
4. Use the generated outputs for later steps in the workshop  

For Workshop 3:

1. Export the list of upregulated genes  
2. Navigate to the StringDB website  
3. Upload the gene list and follow the on-screen instructions  

## Educational Purpose

This workshop series is designed to build confidence in handling biological data, from basic scripting through to biological interpretation. It emphasises practical skills, reproducibility, and critical thinking.

## Licence

This material is intended for educational use. It may be adapted for teaching and learning purposes.
