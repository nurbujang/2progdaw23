# 2progdaw23
Project 2 for Programming for Data Analysis Winter 2023 

## Repository contents:

* .gitignore
* License
* ProgDAProject2.pdf (Project 2 Description)
* project2.ipynb (Jupyter notebook)
    * main report
* df_all.csv
* df_all.json
* data folder
    * unprocessed data
* README.md for Project 2
    * supplementary data of Project 2

## Table of Content for project2.ipynb

* Project Instruction

* Project Title: An Analysis Of Paleo-Present Climate Data

* Abstract

* 1.0 Background

    * 1.1 Climate Change

    * 1.2 Global Warming

    * 1.3 Links Between CO<sub>2</sub>, Temperature, CH<sub>4</sub> And Precipitation In Climate Change

        * 1.3.1 CO<sub>2</sub>

        * 1.3.2 Temperature

        * 1.3.3 CH<sub>4</sub>

        * 1.3.4 Ireland's Temperature And Precipitation

* 2.0 Methods and Implementation

    * 2.1 CO<sub>2</sub> vs Temperature Anomaly From 800kyrs – Present

        * 2.1.1 CO<sub>2</sub>

        * 2.1.2 Temperature

    * 2.2 CH<sub>4</sub> Anomaly From 800kyrs To Present

    * 2.3 Irish Context: Climate Change Signal

        * 2.3.1 Ireland's Temperature

        * 2.3.2 Ireland's Precipitation

    * 2.4 Data Fusion To csv And json

    * 2.5 Analysis Of CO<sub>2</sub>, Temperature, CH<sub>4</sub> and Precipitation

        * 2.5.1 Pearson Correlation

        * 2.5.2 Trend Analysis
            
            * 2.5.2.1 Mann-Kendall Test With MK Z Statistic

            * 2.5.2.2 Fast Fourier Transform (FFT)

            * 2.5.2.3 Multi-Seasonal Time Series Decomposition for Ireland's Temperature and Precipitation

            * 2.5.2.4 Ireland's Temperature Signal to Noise Ratio (SNR)

            * 2.5.2.5 ETCCDI Ireland's Temperature Indices Evaluation

        * 2.5.3 Temporal Lead/Lag Analysis

            * 2.5.3.1 The Granger Causality Test

            * 2.5.3.2 Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF)

            * 2.5.3.3 Time Lagged Cross-Correlation Analysis

        * 2.5.4 Global Temperature Anomaly Prediction

        * 2.5.5 Accelerated Warming

* 4.0 Conclusions

* 5.0 References

## Technologies Used

Python 3.11.5

## Installation Instructions

* conda install scipy matplotlib

* conda install -c conda-forge pymannkendall

* conda install -c conda-forge statsmodels

* conda install -c conda-forge scikit-learn

* pip install icclim

## Usage Instructions

* .ipynb extension file

* markdown for narrative text

* plain text for code

## Support Information

G00426044@atu.ie

## License Information

GNU GENERAL PUBLIC LICENSE, Version 3, 29 June 2007

