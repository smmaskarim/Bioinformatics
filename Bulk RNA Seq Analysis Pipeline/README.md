# Bulk RNA seq Analysis

## Typical Bulk RNA seq Analysis Workflow

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
