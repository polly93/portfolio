# Housing Price Variation and Real Estate Broker Location

## Overview
This project examines how information asymmetry in housing markets is associated with housing prices. 
I use real estate broker location as a proxy for information asymmetry, based on the idea that brokers may differ in their local market experience and access to neighborhood-specific information.
Using a hedonic pricing model, the analysis evaluates whether price differences remain after controlling for property characteristics and location-related factors.

## Data
This project uses publicly available apartment transaction(resale) datasets provided by Ministry of Land, Infrastructure and Transport.   
The dataset include transaction prices, property characteristics, transaction records, and broker location information.
- Region: Seoul, South Korea
- Period: Nov 2021 - Dec 2025
  

The raw data are not included in this repository. Users can access the original data from the public data source linked below.   
$\bullet$ [Data source link](https://rt.molit.go.kr/).


## Methods
- Cleaned and preprocessed housing price and broker location data.
- Constructed property-level and location-based variables.
- Conducted exploratory data analysis to compare housing prices across broker-location groups.
- Estimated a hedonic pricing model to examine the association between housing prices, property characteristics, and broker location.
- Interpreted coefficient estimates to evaluate whether price differences remained after controlling for observed housing attributes.
- **Ongoing:** Expanding the dataset through web crawling to collect additional apartment-level characteristics.


## Tools
Python, pandas, statsmodels, matplotlib, Jupyter Notebook


## Results

