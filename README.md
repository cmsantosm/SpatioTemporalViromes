# README
This repository contains all the data and code used for Santos-Medellin et al., 2020.

The `Analysis` directory holds all the intermediate files (`Data`) and R Notebooks (`Scripts`) needed to generate all the `Figures` and `Tables` in the paper:

- `biochar.Rmd` contains all the code to reproduce **Supplementary Figure 9**
- `differential_abundance.Rmd` contains all the code to reproduce reproduce **Supplementary Tables 6, 7, 9 & 10**
- `experimental_design.Rmd` contains all the code to reproduce **Supplementary Figure 1**
- `nutrients.Rmd` contains all the code to reproduce **Figure 4C** and **Supplementary Table 8**
- `occ_ab.Rmd` contains all the code to reproduce **Figure 2** and **Supplementary Figures 4 & 5**
- `permanova.Rmd` contains all the code to reproduce **Supplementary Tables 4 & 5**
- `spatial.Rmd` contains all the code to reproduce **Figure 5** and **Supplementary Figures 7 & 8**
- `temporal.Rmd` contains all the code to reproduce **Figure 4A-B** and **Supplementary Figure 6**
- `vir_tmg_comparison.Rmd` contains all the code to reproduce **Figure 1**, **Supplementary Figures 2 & 3**, and **Supplementary Table 1**
- `vir_tax_ntwk.Rmd` contains all the code to reproduce **Figure 3**

The `General` directory holds a list of internal functions (`general_functions.R`) that are used in the `Analysis` R Notebooks.

The `Processing` directory holds the raw files (`Data`) from the the SortMeRNA / RDP, vConTACT2, and read recruitment pipelines, and the `Scripts` needed to generate the processed files used in the `Analysis` R Notebooks.

The `vOTU_dereplicated.fa` fasta file holds the sequences for all the dereplicated viral contigs used in this study. 
