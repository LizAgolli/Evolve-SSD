**Chapter 2: Artificial Selection on Sexual Size Dimorphism**

This repository contains data and analysis code for Chapter 2 of my thesis, "Artificial Selection on Sexual Size Dimorphism." The chapter describes a 15-generation family selection experiment in Drosophila melanogaster designed to generate lineages with divergent sexual size dimorphism (SSD) as part of an Evolve and Resequence (E&R) study.

### Data

| File | Description |
| :--- | :--- |
| `SSD_Means.xlsx` | Pupal area measurements and SSD calculations for all families across 15 generations. Includes lineage, generation, family ID, sex, and selection status. |
| `Pedigree Data.csv` | Full pedigree of all lineages. |
| `FVW_isogenized` | Measurements of lineages isogenized from the Fenn Valley Winery (FVW) super-colony. Used to estimate standing genetic variation in SSD prior to selection. |

### Code

| File | Description |
| :--- | :--- |
| `Isogenized FVW.Rmd` | Filters and visualizes SSD using the largest 10% of individuals from each isogenized lineage. |
| `Inbreeding.Rmd` | Calculates and visualizes inbreeding coefficient for each family ID. |
| `Morphospace.Rmd` | Plots the movement of lineages under selection through morphospace (female size vs. male size). |
| `UnifiedFigureCode.Rmd` | Bootstrapping and visualization code for SSD, cumulative selection differentials (CSD), and indirect cumulative selection differentials (ICSD) across generations. |
