# breastcancer-subtype-expression
Gene expression analysis of breast cancer subtypes using public GEO data
# Breast Cancer Gene Expression Analysis (GSE45827)
This repository contains a comprehensive analysis of the breast cancer gene expression dataset GSE45827 from GEO. The goal was to identify subtype-specific molecular signatures and explore differentially expressed genes between Basal and Luminal A breast cancer samples.
## Project Overview
- **Dataset:** GSE45827 (Breast cancer gene expression microarray)  
- **Samples:** 150+ tumor and control samples categorized into subtypes (Basal, Luminal A/B, etc.)  
- **Analysis:**  
  - Performed unsupervised Principal Component Analysis (PCA) to visualize clustering of breast cancer subtypes.  
  - Conducted differential expression analysis comparing Basal vs Luminal A subtypes using t-tests.  
  - Mapped probe IDs to gene symbols for biological interpretation.  
  - Generated heatmaps for top differentially expressed genes.  
  - Performed gene set enrichment analysis (GSEA) for pathway insights.
## Files
- `breast-cancer-analysis.ipynb` — Jupyter notebook with the full step-by-step code and commentary.  
- `breast-cancer-analysis.html` — Exported HTML version of the notebook for easy viewing.  
- `data/` — Folder containing raw data files (GEO series matrix, annotation files).  
- `enrichr_results/` — Results from gene set enrichment analysis.
## Dependencies
* Python 3.8+
* pandas
* numpy
* scipy
* matplotlib
* seaborn
* gseapy
* jupyter
## Data
* Raw data files downloaded from GEO and annotation databases are included in the `data/` folder.
* Original dataset: [GSE45827 on GEO](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE45827)
## Results Summary
* PCA visualization revealed clear clustering of breast cancer subtypes.
* Differential expression analysis identified top genes distinguishing Basal vs Luminal A subtypes.
* Heatmaps illustrate expression patterns of key genes.
* Gene set enrichment highlighted pathways relevant to breast cancer biology.
## Author
Sana Younes
