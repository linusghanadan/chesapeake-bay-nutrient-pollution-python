## Time Series Analysis of Nutrient Concentration in Chesapeake Bay

### [Link to Blog (includes Python code, code output, and written analysis)](https://linusghanadan.github.io/blog/2024-8-20-post/chesapeake-bay-python.html)

### Repository Contents
    chesapeake_bay_nutrient_pollution_python
    └───images
        │   STL visualization for nitrogen: nitrogen.png
        │   STL visualization for phosphorus: phosphorus.png
    │   README.md
    │   .ipynb

### Context

This project was completed as a final project for my Statistics class, taken as part of my Master's program at UC Santa Barbara. I worked independently to find data, pose a statistical question, and carry out analysis using appropriate modeling techniques. Originally, this analysis was conducted in R, but I decided to reproduce this analysis to practice my Python skills working with large datasets and building statistical models with the statsmodels library.

### Question

Since the 2010 introduction of federal water quality requirements, what seasonal and non-seasonal trends are present for nitrogen and phosphorus concentrations in Chesapeake Bay tidal regions?

### Analysis Summary

Proposed statistical question on how nutrient concentrations have changed since Clean Water Act protection measures (implemented in 2010) and found appropriate data for answering the question (used over 43,000 samples from the Bay’s tidal regions). Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct time series analysis of nitrogen and phosphorus concentrations (selected length of seasons based on autocorrelation). For each pollutant, visualized model parameters comparatively. In addition, ran regressions to determine the proportion of variation attributable to seasonality and the 95% confidence interval for change in trend component over the 10-year period.

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.
