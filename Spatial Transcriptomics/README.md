# Spatial Transcriptomics Analysis

A reproducible pipeline for spatial transcriptomics data analysis, including quality control, normalization, clustering, cell-type annotation, differential expression analysis, and spatial visualization.

## Workflow

1. Quality Control (QC)
2. Normalization & Scaling
3. Highly Variable Gene Selection
4. PCA & UMAP
5. Leiden Clustering
6. Cell-Type Annotation
7. Differential Expression Analysis
8. Spatial Visualization

## Requirements

* Python
* Scanpy
* Squidpy
* Anndata
* Pandas
* NumPy
* Matplotlib

## Installation

```bash
git clone https://github.com/username/spatial-transcriptomics.git
cd spatial-transcriptomics
pip install -r requirements.txt
```

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
* Functional enrichment results

## Contact

For questions or collaborations, please open an issue or contact the repository owner.
