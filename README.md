# Wildfire_Analysis_with_NBR
Wildfire analysis with Normalized Burn Ratio(NBR), using ArcGIS API with python.

## Data Collection and area of interest
In May 2023, a wildfire occured in Prince George, BC, Canada. To study the extent and effect of wildfire, sentinel-2 images before,during and after the fire were extracted from ArcGIS Python API. In this study, the AOI is an area located near Donnie Creek (57.2, -122.1), an area north of Fort St John in Pringe George, BC, Canada.

## Quantitative Assessment with Normalized Burn Ratio (NBR)
The Normalized Burn Ratio (NBR) is an index designed to highlight burnt areas in large fire zones. The formula is similar to NDVI, except that the formula combines the use of both near infrared (NIR) and shortwave infrared (SWIR) wavelengths.

![Comparison of the spectral response of healthy vegetation and burned areas](https://un-spider.org/sites/default/files/Spectral_responses.jpg)

And the calculation of NBR has the formula below:

![Calculation of NBR](https://un-spider.org/sites/default/files/NBR_formula.jpg)

In short, a high NBR value indicates healthy vegetation while a low value indicates bare ground and recently burnt areas. You may refer to https://un-spider.org/advisory-support/recommended-practices/recommended-practice-burn-severity/in-detail/normalized-burn-ratio for more details.
