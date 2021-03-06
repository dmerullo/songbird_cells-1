# Songbird single-cell/nucleus transcriptomics

This repository contains R code for analysis and figure generation for the songbird song motor pathway single-cell and single-nucleus RNA-sequencing project.

## Data

Seurat data objects can be accessed at https://cloud.biohpc.swmed.edu/index.php/s/nLicEtkmjGGmRF8. References to 'HVC_RA.qs', 'HVC_RA_GABA.qs', etc correspond to objects in that directory. To run the analysis, directories will need to be changed.

## Directories

comparative - Comparisons between songbird, mouse, and turtle neurons. Scripts are divided three analysis approaches: correlations, Seurat dataset integration, and spatial analyses (Allen Brain Atlas). 

dataset_comparison - Script that compares the distribution of each cell type between HVC and RA

grn - Gene regulatory network inference using GRNBoost2. Included are the scripts to export data for analysis (export_to_numpy_glut.R), script to run the Arboreto framework (run_grnboost2_np.py), and post-processing analysis (grnboost2_glut.R)

imaging - Cellprofiler pipelines used for Hiplex ISH analysis

marker_gene - Differential expression analysis

reduction_viz - Dimensionality reduction of different subsets of the data (all cells, glutamatergic neurons, GABAergic neurons) and plotting.

trees - Hierarchical clustering of cell clusters

utils - Several files with utility functions used in other scripts

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4289038.svg)](https://doi.org/10.5281/zenodo.4289038)
