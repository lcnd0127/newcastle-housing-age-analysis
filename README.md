# Newcastle Housing Age Analysis
Assignment for *Programming for Spatial Data Science*

## Overview
This repository contains code and data that can be used to explore the relationship between median house prices and the percentage of residents aged 20-29 across LSOAs in Newcastle upon Tyne. The project contains the results of OLS regression, and both spatial and non-spatial visulisations of findings, which have been tailored to different audiences. The project workflow is documented in a Jupyter notebook which can be used to reproduce the results.

## Data
Two of the datasets uploaded to this repo have already been filtered and exported out of the notebook (newcastle_lsoa.geojson & newcastle_house_prices.csv), due to the original data used being too large to upload to GitHub. The notebook contains download links to the original datasets so that the project can be reproduced in full, however, the smaller files found here can be used to carry out the analysis after the pre-processing stage, with minor adjustments to the code (filenames etc).

## Worflow Outline
The notebook is structured according to the following structure, with all analysis carried out in this project being contained in the notebook:
* Introduction
  * Project background, motivation, and why it's important for public good
* Data Overview
  * Introduction to the datasets, download links, and limitations present with the data chosen
* Data Import
  * Importing required packages, loading in the data, and completing initial inspections
* Data Cleaning & Merge
  * Checking for missing values, standardising data, and merging before analysis 
    * Creating Newcastle shapefile
    * Subsetting/Preparing Age Dataset
    * Subsetting/Preparing House Price Data
* Regression
  * Fitting an OLS regression model & interpreting results
* Visualisation
  * Creating plots to communicate the regression results 
    * Non-Spatial - Academic Audience
    * Spatial - Policy Maker / Public Audience
* Conclusion
    * Final thoughts on insights gained from the analysis 
* References
* Data Sources

## How to run this notebook
To ensure the notebook runs from top to bottom, use the provided links to download the original data files. Else, use the filtered data included in the repository, editing filepaths/names as needed after the preprocessing stage to create the visualisations.
