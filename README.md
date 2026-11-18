# Respiratory virus circulation patterns in NYC before and since SARS-COV-2 emergence
This repository contains analysis code and outputs for
Wan Yang, Alice Yeung, Haokun Yuan, Jeffrey Shaman. 2026. 
*Circulation patterns of common respiratory viruses before and since the emergence of SARS-CoV-2/COVID-19 in New York City, 2015-2025* 

## Data note
The primary data used in the study are included in the paper (Fig S1).  
For method verification, we generate a test dataset via random Poisson sampling of the NYC data. 

See data folder: synthetic dataset of weekly test counts and positive counts for different viruses

Note, as such, the outputs may be slightly different from those presented in the paper.

## Analysis code
scripts folder: main and sensitivity analysis code

## Outputs
output_syn_main folder: main results.

output_syn_diff_onset folder: results from the sensitivity analysis on alternative onset cut off.

output_syn_rhino_alt folder: results from the analysis using alternative timing of rhinovirus adjustment.