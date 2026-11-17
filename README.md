# Respiratory virus circulation patterns in NYC before and since SARS-COV-2 emergence
This repository contains analysis code and outputs for
Wan Yang, Alice Yeung, Haokun Yuan, Jeffrey Shaman. 2026. 
Circulation patterns of common respiratory viruses before and since the emergence of SARS-CoV-2/COVID-19 in New York City, 2015-2025 

## Data note
Under the Data Use Agreement between Columbia University and New York City Department of Health and Mental Hygiene (DOHMH),
We do not have permission to share the raw data used in this analysis.
Therefore, for testing the methods, we generate a synthetic dataset, by random Poisson sampling of the NYC data.
As such, the outputs are slightly different from those presented in the paper.

data folder: synthetic dataset of weekly test counts and positive counts for different viruses

## Analysis code
scripts folder: main and sensitivity analysis code

## outputs
output_syn_main folder: main results.
output_syn_diff_onset folder: results from the sensitivity analysis on alternative onset cut off.
output_syn_rhino_alt folder: results from the analysis using alternative timing of rhinovirus adjustment.