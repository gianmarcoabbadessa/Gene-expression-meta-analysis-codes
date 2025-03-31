Gene-Expression-Meta-Analysis-Codes

This repository contains the code and data used for the paper:
Mapping Molecular Pathways of Multiple Sclerosis: A Gene Prioritization and Network Analysis of White Matter Pathology Transcriptomics
Gianmarco Abbadessa et al. Annals of Neuology 2025

Contents

1) CODE VOTE COUNTING STRATEGY AND MONTECARLO SIMULATION MSvsCONTROL ENG.txt
R code that:
Performs the vote-counting strategy to identify overlapping differentially expressed genes (DEGs) across studies.
Runs Monte Carlo simulations (both random and WGCNA-weighted) to assess the significance of the observed gene overlap.

2) Gene lists mapped (filteredENTREZ-FC).xlsx
Excel file with the differentially expressed genes from multiple sclerosis white matter (vs. control) comparisons across the nine included studies. Each sheet corresponds to a specific lesion type or comparison. Columns include gene symbols, fold change, p-values, sample size, and Entrez IDs.

3) Supplementary method.pdf
Supplementary methods document detailing:
Gene universe definition.
WGCNA-based weighting approach for Monte Carlo simulations.
Sensitivity analyses excluding lower-quality studies.
Additional methodological notes and rationale.

4) README.md
This file.

5) Supplementary files: Table S1, S2, S3, S4, S5, S10. Figure S1-S9.

Usage:
Clone or download the repository.
Open the .txt code file in R or RStudio.
(1)Install required packages, including: WGCNA, readxl, dplyr, tidyr, edgeR, tibble, lme4, ggplot2.
(2)Edit file paths at the top of the code to match your local directory (e.g., the path to Gene lists mapped (filteredENTREZ-FC).xlsx).
(3)Run the script.

Reference
If you use or adapt this code, please cite the paper:
Abbadessa, G., Nagano, A., Hametner, S., Howell, O., Owen, D., Papadaki, A., Srivastava, P., Bonavita, S., Magliozzi, R., Reynolds, R., Rizig, M., & Nicholas, R.
Mapping Molecular Pathways of Multiple Sclerosis: A Gene Prioritization and Network Analysis of White Matter Pathology Transcriptomics.
Annals of Neurology, 2025

License
This repository is released under an open license. Please review any additional usage restrictions for external datasets (e.g., from GEO).
Contact:
gianmarcoabbadessa@gmail.com; gianmarco.abbadessa@unicampania.it; g.abbadessa23@imperial.ac.uk
Last updated: February 2025

