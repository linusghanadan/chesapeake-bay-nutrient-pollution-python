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

For this final project in my master’s statistics course at UC Santa Barbara, I worked independently to find data, pose a question, and carry out analysis using statistical modeling and Python.

### Central Question

Over the ten years that followed the onset of new regulations, what linear trends best capture how average nitrogen and phosphorus concentrations have changed in the Chespeake Bay?

### Summary of Analysis

Proposed statistical question on possible underlying linear trends in average nitrogen and phosphorus concentrations across the Chesapeake Bay since 2010 (when new Clean Water Act regulations were implemented for the Bay) and found appropriate data for answering the question (over 43,000 samples from the Bay’s tidal regions). Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct time series analysis of nitrogen and phosphorus concentrations (selected length of seasons based on autocorrelation). For each pollutant, visualized model parameters comparatively and ran regressions of parameters (to determine proportion of variation attributable to seasonality and 95% confidence interval for 10-year linear trend component).

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.
