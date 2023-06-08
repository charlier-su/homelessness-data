# Homelessness Data

In this project, we will use data science to investigate homelessness in the US.

## Requirements

This project requires the following:

- Python 3
- Some way to run a Python notebook (`.ipynb`)
- The Python libraries listed in `requirements.txt`

## Data Source

The data from this project are from the US Department of Housing and Urban Development. The data set `05b_analysis_file_update.csv` and the data dictionary `HUD TO3 - 05b Analysis File - Data - Dictionary.csv` will be used for the investigation. Details about this data are available in the HUD's report [Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf) in the section titled DATA.

## Data Processing

### Preparation

Several steps were taken to prepare the data:
* The data dictionary was used to determine which columns should be kept for the analysis.
* Measurements that were not from 2017 were removed.
* Entries with missing homelessness statistics were removed.
* Columns using absolute population counts were converted into rates per 10,000.

The prepared data as well as the notebook used for data preparation are available in this repository as `homelessness_data_clean.csv` and `homelessness_data_preparation.ipynb`.

### Analysis

The data analysis was done in the `homelessness_data_analysis.ipynb` notebook, which is available in this repository. Several questions were explored:
* What types of models are most effective for predicting homelessness rates?
* Could federal funding (or lack of federal funding) contribute to homelessness rates?
* What factors have the closest relationship with homelessness rates?
  * More specifically, what predictors are most effective for estimating homelessness rates?

## Authors

- Charlie Robinson ([LinkedIn](https://www.linkedin.com/in/-charlierobinson/))

## License

This project is licensed under the terms of the MIT License.
