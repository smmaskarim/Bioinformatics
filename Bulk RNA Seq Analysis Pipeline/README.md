# Bulk RNA-Seq Analysis

## Overview

This repository contains a comprehensive bulk RNA-sequencing (RNA-seq) analysis workflow, from count matrix to biological interpretation. The pipeline includes differential expression analysis, and functional enrichment analysis.

## Typical Bulk RNA-Seq Analysis Workflow

```text
Raw FASTQ Files
       │
       ▼
Quality Control (FastQC)
       │
       ▼
Read Trimming (Trim Galore / Cutadapt)
       │
       ▼
Post-trimming Quality Check (FastQC)
       │
       ▼
Read Alignment (STAR / HISAT2)
       │
       ▼
Gene Quantification (featureCounts)
       │
       ▼
Count Matrix Generation
       │
       ▼
Quality Assessment & Sample Exploration
(PCA, Sample Correlation, Clustering)
       │
       ▼
Differential Expression Analysis
(DESeq2 / limma-voom / edgeR)
       │
       ▼
Visualization
(Volcano Plot, Heatmap, PCA)
       │
       ▼
Functional Enrichment Analysis
(GO, KEGG, Reactome)
       │
       ▼
Biological Interpretation
```

## Key Analysis Steps

* Quality control of raw sequencing reads
* Adapter and low-quality base trimming
* Alignment to the reference genome
* Gene-level quantification
* Exploratory data analysis and sample quality assessment
* Differential gene expression analysis
* Data visualization and result interpretation
* Functional enrichment and pathway analysis

## Tools and Packages

### Preprocessing
* FastQC
* Trim Galore
* Cutadapt

### Alignment and Quantification
* STAR
* featureCounts

### Differential Expression Analysis
* DESeq2

### Functional Enrichment
* clusterProfiler
* goseq
* ReactomePA

## Outputs
* Gene count matrix
* Differentially expressed genes (DEGs)
* PCA plots
* Volcano plots
* Heatmaps
* GO enrichment results
* KEGG pathway analysis
* Reactome pathway analysis
* Publication-ready figures

