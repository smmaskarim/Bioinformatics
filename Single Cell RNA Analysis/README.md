# Single-Cell RNA-Seq Analysis Pipeline

## Overview

This repository contains a comprehensive single-cell RNA sequencing (scRNA-seq) analysis workflow using **Seurat** (R) and **Scanpy** (Python) for the analysis of **10x Genomics** datasets. The pipeline covers data preprocessing, quality control, dimensionality reduction, clustering, cell type annotation, differential expression analysis, and visualization.

## Workflow

```text
10x Genomics Raw Data
        │
        ▼
Data Import
(Seurat / Scanpy)
        │
        ▼
Quality Control
(Filter low-quality cells and genes)
        │
        ▼
Normalization
        │
        ▼
Highly Variable Gene Selection
        │
        ▼
Scaling
        │
        ▼
Dimensionality Reduction
(PCA)
        │
        ▼
Neighborhood Graph Construction
        │
        ▼
Clustering
(Leiden/Louvain)
        │
        ▼
Visualization
(UMAP / t-SNE)
        │
        ▼
Cell Type Annotation
        │
        ▼
Differential Expression Analysis
        │
        ▼
Functional Enrichment Analysis
```

## Features

* Analysis of 10x Genomics scRNA-seq datasets
* Quality control and filtering
* Data normalization and scaling
* Identification of highly variable genes
* PCA, UMAP, and t-SNE visualization
* Cell clustering using Leiden/Louvain algorithms
* Cell type annotation
* Differential gene expression analysis
* Functional enrichment analysis
* Publication-quality visualizations

## Software and Packages

### R

* Seurat
* SingleR
* ggplot2
* dplyr

### Python

* Scanpy
* AnnData
* NumPy
* Pandas
* Matplotlib

## Outputs

* Quality control reports
* UMAP and t-SNE plots
* Cluster annotations
* Marker gene lists
* Differential expression results
* Functional enrichment results
* Publication-ready figures

## Data Source

Single-cell RNA sequencing datasets generated using the 10x Genomics platform.
