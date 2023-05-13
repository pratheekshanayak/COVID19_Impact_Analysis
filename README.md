# COVID19_Impact_Analysis
Impact of COVID-19 restriction on air pollution using satellite based remote sensing.

1. `NO2_maps.ipynb` - Computation and visualization NO2 maps over India for 2019 and 2020, change in NO2 corresponding to COVID-19 lockdown period
2. `LULC.ipynb` - Estimation of reduction in NO2 for different land cover categories obtained using Random Forest classifier
3. `population.ipynb` - Analysis of correlation between population density and change in NO2
4. `mobility.ipynb` - Analysis of correlation between mobility and change in NO2

`data/` contains mobility data obtained from [Google mobility change dataset](https://www.google.com/covid19/mobility/).

`results/` contains interactive maps and figures (html format) obtained through the analysis.

`Report.pdf` is a detailed analysis report describing the datasets, methodology and results.

### Environment

Use `conda` or `mamba` to install the environment specified in `environment.yml`