# Calibrating effect size interpretation in ecology and evolution: A quantitative synthesis of 100,000 observations

## Transparency declaration

The authors affirm that the manuscript is an honest, accurate, and transparent account of the study being reported, and no important
aspects of the study have been omitted.

## Reproducibility declaration

This is a repository containing the data and code for reproducing results from:    

> Yang, Y.,  Bartoš, F., Pan, J., Lagisz, M., & Nakagawa, S. (2025). Calibrating effect size interpretation in ecology and evolution: A quantitative synthesis of 100,000 observations.

## Structure

The repository contains the following folders:

- Dat

- Figure

- Script

### `Dat` folder

The `Dat` folder includes the datasets that are necessary for repruducing all anayses and figures reported in our paper. The data are in the format of `.rda` and `.csv`.

- `ecoevo_yefeng.Rds`

The 441 meta-analysis datasets that are retreived from the published meta-analysis papers. 

- `dat_ecoevo_SMD.zr.rds`

The subset of `ecoevo_yefeng.Rds` that use `SMD` (`n = 192`) and `r` (`n = 134`) as the effect size measure. 

- `dat_ecoevo_lnRR.rds`

The subset of `ecoevo_yefeng.Rds` that use `lnRR` (`n = 115`) as the effect size measure. 

- `robma_SMD.zr.csv` and `robma_lnRR.csv`

The model estimates derived from the robust Bayesian meta-analysis approaches. Given that running Bayesian models takes a long while, we pre-extracted the model estimates to save time. All original `R` code to fit models and extract estimates is available at `Script`.


**Credit:**

The datasets were originally compiled by:

> Costello L, Fox J W. Decline effects are rare in ecology. Ecology, 2022, 103(6): e3680.

Owing to journals’ mandatory open data policies and the widespread adoption of FAIR (Findable, Accessible, Interoperable, and Reusable) data-sharing principles, we could easily find and re-use these publicly accessible datasets.


### `Figure`

The `Figure` folder includes all figures that are reported in the main body and supplementary materials.


### `Script` folder

The `Script` folder includes the `R` scripts that reproduce all results and figures in the main body and supplementary materials. 

The scripts are formatted in the format of Rmarkdown (`Rmd`).

- `Main4.Rmd`

The main `R` code replicating all analyses and results (e.g., figures reported in `Figure`).

- `Preprocess.Rmd`

The auxiliary `R` code processing raw data to make them suitable for model fitting.


## Licence

The files in this dataset are licensed under the Creative Commons Attribution 4.0 International License (to view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/).

## Contact

- Dr. Yefeng Yang

School of Biological, Earth and Environmental Sciences, BEES
The University of New South Wales, Sydney, Australia

Email: yefeng.yang1@unsw.edu.au
