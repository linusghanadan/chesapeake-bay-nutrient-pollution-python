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

For this final project in my master’s statistics course at UC Santa Barbara, I worked independently to find data, pose a question, and carry out analysis using statistical modeling techniques and Python.

### Central Question

Over the ten years that followed the onset of Chesapeake Bay federal water quality regulation, what **linear trend** best captures the change in the Bay's nitrogen and phosphorus concentrations?

### Summary of Analysis

Proposed statistical question on possible underyling linear trend in Chespeake Bay nutrient concentrations since 2010 (when new Clean Water Act regulation was implemented for the Bay) and found appropriate data for answering the question (used over 43,000 samples from the Bay’s tidal regions). Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct time series analysis of nitrogen and phosphorus concentrations (selected length of seasons based on autocorrelation). For each pollutant, visualized model parameters comparatively. In addition, ran regressions to determine the proportion of variation attributable to seasonality and the 95% confidence interval for 10-year linear trend component.

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.
