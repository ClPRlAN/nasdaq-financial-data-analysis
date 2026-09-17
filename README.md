# Nasdaq Financial Data Analysis

A data analysis project using Python and the Nasdaq Data Link API.

The project focuses on the **Accrued Expenses Turnover** metric and explores how it changes across companies and countries between 2010 and 2015.

## What I did

* Retrieved financial data from the Nasdaq Data Link API
* Worked with JSON responses
* Converted the data into a Pandas DataFrame
* Selected and cleaned the relevant columns
* Filtered the dataset for Accrued Expenses Turnover
* Analyzed descriptive statistics
* Compared company trends over time
* Compared average values across countries
* Created visualizations with Matplotlib

## Main findings

The Accrued Expenses Turnover values showed significant variation between companies.

The dataset had an average value of approximately **26.91**, while the median was approximately **13.75**, suggesting that some relatively high values influenced the average.

For the 2010–2015 period, the Bahamas had the highest average value in the analyzed dataset, followed by the United States and the United Kingdom.

## Technologies

* Python
* Pandas
* Matplotlib
* Requests
* Nasdaq Data Link API
* Google Colab

## Run the notebook

The analysis is available in:

[Open the notebook](nasdaq_financial_data_analysis.ipynb)

The notebook can be opened directly in Google Colab.

To run it, a Nasdaq Data Link API key is required.

In Google Colab, add the API key under **Secrets** using the name:

`NASDAQ_API_KEY`

The API key is not stored in this repository.
