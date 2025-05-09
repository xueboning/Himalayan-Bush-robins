# Himalayan-Bush-robins

Scripts for Xue et al. (2025): *Phenotypic plasticity co-varies with the elevation range of Himalayan elevational migrants*

**CODE OVERVIEW**
- We used two species, *Tarsiger chrysaeus* and *Tarsiger indicus*, in our study. The prefixes for species-related codes and data were abbreviated as TC and TI, respectively.
- We used four tissues (heart, flight muscle, lung and liver) in our study.
- R version 4.2.0 was used to conduct R analyses.
---

- **R-script-for-DEG analysis_v1.r**: This script is used to quantify the number of differentially expressed genes (DEGs) and to provide an overview of gene expression plasticity across different treatments and species. The filtered expression count matrices for both species and grouping data are used as input files.
*Note: Since our analysis includes two species and four tissues, for demonstration purposes, this script will focus on the flight muscle of Tarsiger chrysaeus (TC) as an example. The comparison between cold-hypoxia and warm-normoxia (CH vs. WN) will then be used to identify DEGs.

- **R-script-for-WGCNA_v1.r**: This script is used to examine gene expression associated with different treatments across two species, specifically for identifying treatment-related Hub genes. The input files include the log-transformed TPM expression profiles, along with a grouping file containing the treatments.
*Note: Since our analysis includes four tissues, for demonstration purposes, this script will focus on the flight muscle of Tarsiger chrysaeus (TC) and Tarsiger indicus (TI) across the four treatments as an example.

- **R-script-for-vector analysis_v1.r**: This script is used to represent the direction and magnitude of divergence between the centroids of vectors for different acclimation conditions. The input files include the log-transformed TPM expression profiles of Hub genes identified through WGCNA, as well as a grouping file containing species and treatments.
*Note: Since we analyzed four tissues, for simplicity, this script will focus on the flight muscle of Tarsiger chrysaeus (TC) and Tarsiger indicus (TI) as an example, using data from the four treatment conditions.

---
In part of the code, some variables related to the four treatments (cold/hypoxia, cold/normoxia, warm/hypoxia, warm/normoxia) will be abbreviated as CH, CN, WH, WN (or A, B, C, D in R-script-for-vector analysis_v1.r).

