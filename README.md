## Time Series Analysis of Chesapeake Bay Pollution

### [Link to Blog (includes Python code, code output, and written analysis)](https://linusghanadan.github.io/blog/2024-8-20-post/chesapeake-bay-python.html)

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

For his final project in his Master's statistics course, Linus conducted a self-guided time series analysis of nitrogen and phosphorus concentrations in the Chesapeake Bay, studying data from over 43,000 automated readings taken between 2010 and 2019.

In 2010, the Chesapeake Bay area began implementing Total Maximum Daily Load (TMDL) under the Clean Water Act. Through isolating seasonal and non-seasonal trends in pollutant concentration data, Linus's goal was to better understand the effectiveness of the TMDL regulation.

STL decomposition models were used to conduct this analysis, which involved tuning season length based on the autocorrelation of time lags. Based on selected season length, STL models use multilinear regression to separate variation in the data into three distinct components: Seasonality, Trend (intra-seasonal variation), and Residual/Randomness (inter-seasonal variation). Using the models, Linus visualized the three model components comparatively, allowing him to identify early 2014 as a localized event with a spike in nitrogen that the model attributed to the Residual/Randomness component.

Moreover, from running regressions with the resulting model parameters, Linus came to the conclusion that the overall non-seasonal trend from 2010 to 2019 was slightly negative for both pollutants. He also found that phosphorus had very distinct seasonality, with seasonality explaining 87% of the variation in concentrations. For nitrogen, seasonality explained 73% of variation.

### Datasets
- 2010-2019 Chesapeake Bay Program (CBP) Traditional Partner Tidal XLSXs

### Data References
- Chesapeake Bay Program DataHub. n.d. “Traditional Partner Tidal (Tier 3) Data.” https://datahub.chesapeakebay.net/FileDownloads.
