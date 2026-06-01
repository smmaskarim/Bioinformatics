# Spatial Transcriptomics Analysis

A reproducible pipeline for spatial transcriptomics data analysis, including quality control, normalization, clustering, cell-type annotation, differential expression analysis, and spatial visualization.

## Workflow

1. Quality Control (QC)
2. Normalization
3. Highly Variable Gene Selection
4. PCA & UMAP
5. Clustering & Spatial Mapping
6. Marker Gene Discovery (Differential Expression Analysis)
7. Spatial Neighborhood Enrichment

## Requirements

* Python
* Scanpy
* Squidpy
* Anndata
* Pandas
* NumPy
* Matplotlib


## Usage

Run the notebooks or scripts in the following order:

```text
01_QC
02_Preprocessing
03_Clustering
04_Annotation
05_Differential_Expression
06_Visualization
```

## Output

* Spatial cluster maps
* Marker gene expression plots
* Differentially expressed genes
* MORAN'S I SPATIAL AUTOCORRELATION
