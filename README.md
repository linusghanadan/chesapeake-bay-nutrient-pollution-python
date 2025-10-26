## Time Series Analysis of Chesapeake Bay Pollution

### [Link to Blog (includes Python code, code output, and written analysis)](https://linusghanadan.github.io/blog/2024-8-20-post/chesapeake-bay-python.html)

### Context

This project was completed as my final project for my Statistics class, taken as part of my Master's program at UC Santa Barbara. The central question, data used, and statistical modeling techniques employed were entirely self-driven. Graded deliverables included a blog post and 10-minute class presentation.

### Repository Contents
    chesapeake_bay_nutrient_pollution_python
    └───images
        │   STL visualization for nitrogen: nitrogen.png
        │   STL visualization for phosphorus: phosphorus.png
    │   README.md
    │   .ipynb

### Central Question

Over the ten years that followed the onset of new regulations in 2010, what linear trends best capture how average nitrogen and phosphorus concentrations have changed in the Chespeake Bay?

### Summary of Analysis

Investigated trends in nitrogen and phosphorus concentrations using 43,000 automated sensor readings from 2010 to 2019. Cleaned and processed time series data, and built STL decomposition models. Tuned season length based on autocorrelation of time lags. Visualized model parameters, ran regressions, and interpreted results.

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.
