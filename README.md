# living-meta-analysis-of-resistance-training

This repository hosts the data and code for the living meta-analysis of resistance training studies.

## reproducibility

This project uses [`renv`](https://rstudio.github.io/renv/articles/renv.html#reproducibility): 

- `renv::snapshot()` save state
- `renv::restore()` load state  

where state refers to package versions used by the project.  

## targets analysis pipeline

Useful console functions:

- `tar_edit()` opens a the make file
- `tar_make()` to run targets
- `tar_visnetwork()` to view pipeline

