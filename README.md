# StarCAT analysis for post transplant CD34+ genes

Using the existing nature methods GEP dataset, we want to analyze the post-transplant CD34+ dataset. The resulting dataset should show the usage scores for each of the GEPs.

### Current Issues:
    - Errors converting seurat R to python
    - Visualizing plots on R and python

### Files
    - seu.integrated.resolution_search.rds (dataset)
    - starcat_analysis.ipynb (analysis notebook, R)
    - starcat_visualization.ipynb (visualization notebook, python)
    - cNMF4.gene_spectra_score.k_35.dt_0_15.csv (reference, 2k genes [csv file])
    - cNMF4.spectra.k_35.dt_0_15.consensus.txt (reference, 2k genes [txt file]) <= Used for starCAT analysis
    - cNMF4.spectra.k_35.dt_0_15.consensus.csv (reference, 40k genes [csv file])
    - cNMF4.spectra.k_35.dt_0_15.consensus.txt (reference, 40k genes [txt file])
    - postTrans_starCAT.rf_usage_normalized.txt (starCAT first run)
    - postTrans_common_starCAT.rf_usage_normalized.txt (starCAT second run with common genes)

Research under the [Li Lab](https://www.hlilab.org/), University of California, San Diego

> Work in progress
