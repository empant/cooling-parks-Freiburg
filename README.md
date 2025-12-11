# Cooling Effects and Rates of Parks in Freiburg WIP
Temporal analysis of urban park cooling effects in Freiburg, Germany, using hourly air temperature data from 2023.


*Caution: code and repo in progress!*

## Table of Content
1. [Processing datasets](R_notebooks/import_data_into_smaller.Rmd)
Following datasets were used:
- Air temperature data from weather-measuring stations [Plein et al. (2024)](https://doi.org/10.5281/zenodo.1273255)
- Cloud cover - [DWD data](https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/subdaily/cloudiness) and [cloud camera images](https://zenodo.org/records/14603730)
- Wind speed - Internal dataset from University of Freiburg
- Heat warning days - [DWD dataset](https://opendata.dwd.de/climate_environment/health/historical_alerts/heat_warnings/)
- Phenophase - [PhenoCam Hartheim](https://phenocam.nau.edu/webcam/roi/hartheim3/DB_1000/)

3. [Temperature differences by phenophase (built-up area-park)](R_notebooks/visualisations/temp_diff_boxplots)
4. [Bootstrapping nighttime cooling rates, park vs. built-up area](R_notebooks/analysis/BS_CR_builtup_areas.Rmd)
5. [ANOVA on nighttime cooling rates between parks](R_notebooks/analysis/anova_CR.Rmd)
6. Impact of meteorological conditions on cooling rates of parks
7. [Heatwave analysis on nighttime cooling](R_notebooks/visualisations/heatwave_analysis)
