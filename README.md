# Cooling Effects and Rates of Parks in Freiburg WIP
Temporal analysis of urban park cooling effects in Freiburg, Germany, using hourly air temperature data from 2023.


*Caution: code and repo in progress!*

## Table of Content
1. [Processing datasets](R_notebooks/import_data_into_smaller.Rmd)
Following datasets were used:
For weather condition classification - DWD data on cloud cover (https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/subdaily/cloudiness<img width="468" height="13" alt="image" src="https://github.com/user-attachments/assets/df5b244d-a8e3-40a8-8312-14fd40cf1b7c" />
)

3. [Temperature differences by phenophase (built-up area-park)](R_notebooks/visualisations/temp_diff_boxplots)
4. [Bootstrapping nighttime cooling rates, park vs. built-up area](R_notebooks/analysis/BS_CR_builtup_areas.Rmd)
5. [ANOVA on nighttime cooling rates between parks](R_notebooks/analysis/anova_CR.Rmd)
6. Impact of meteorological conditions on cooling rates of parks
7. [Heatwave analysis on nighttime cooling](R_notebooks/visualisations/heatwave_analysis)
