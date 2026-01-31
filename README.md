# RemoTnitor MSc Thesis

This repository contains the R code and data processing workflows used in the analysis of fecal microbiota data as part of the **RemoTnitor MSc project**.

The work was conducted as part of a Master’s thesis in Biotechnology at the Norwegian University of Life Sciences (NMBU), in collaboration with the Norwegian Veterinary Institute.

---

## Workflow summary

The repository includes code for:

1. Quality control of sequencing reads  
2. Host DNA removal  
3. Taxonomic profiling using `nf-core/taxprofiler`  
4. Post-processing and integration of taxonomic profiles  
5. Construction and filtering of `phyloseq` objects  
6. Alpha and beta diversity analyses  
7. Ordination, PERMANOVA, and mixed-effects modelling  
8. Differential abundance analysis (ANCOM-BC2)  
9. Figure generation for the MSc thesis

---

## Repository structure

- `code/` – All analysis scripts (R, bash, SLURM)
- `reports/` – Rendered HTML versions of Rmd-files for readability
- `data/` – Metadata and small derived tables (raw data not included)
- `figures/` – Figures generated for the thesis
- `docs/` – Supplementary documentation and workflow notes

Large raw sequencing files are not tracked in this repository.

---

## Contact
For questions:

**Thomas Amble Karlsen**
thomasamblekarlsen@gmail.com
