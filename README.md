
# Forecasting Weekly Sales for Walmart Retail Stores
![walmart-ecommerce-sales](https://github.com/vatsalmandalia/Time-Forecasting-Retail-Sales/assets/63712490/ce3421ee-7eff-4dac-9c10-f8ecd5816a29)

## **Context**:

Walmart, one of the leading retail stores in the USA, wants to predict the sales for each its 45 stores. We are provided with historical sales data for 45 stores located in different regions - with each store having a number of departments. The company also runs several promotional markdown events throughout the year where they precede prominent holidays, the four largest of which are the Super Bowl, Labour Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

## **Problem Statement**:
1.	Predict the department-wide sales for each store for the following year
2.	Model the effects of markdowns on holiday weeks
3.	Provide recommended actions based on the insights drawn, with prioritization placed on largest business impact

## **Datasets Information**:
1. **Stores**
- Anonymized information about the 45 stores, indicating the type and size of store
2. **Features**
- Contains additional data related to the store, department, and regional activity for the given dates.
- Store - the store number
- Date - the week
- Temperature - average temperature in the region
- Fuel Price - cost of fuel in the region
- MarkDown1-5 - anonymized data related to promotional markdowns. Markdown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
- CPI - the consumer price index
- Unemployment - the unemployment rate
- Is Holiday - whether the week is a special holiday week
3. **Sales**
- Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:
- Store - the store number
- Dept - the department number
- Date - the week
- Weekly Sales - sales for the given department in the given store
- Is Holiday - whether the week is a special holiday week

## Project Flow:
- Understanding the raw data
- Data preprocessing
  - Merging
  - Cleaning the data- dropping duplicates, treating missing values
- Exploratory data analysis- finding insights and trends from sales data for 2010-2012
- Preparing the data for forecasting- transforming data from multivariate to univariate
- Augmented-Dickey Fuller test for checking stationarity of time series
- Autocorrelation Function and Partial Autocorrelation Function plots- to estimate values of parameters p,d,q of ARIMA
- ARIMA model
- SARIMAX model
- Predicting for future dates
- Conclusion

This is the google colab link of the project - [Google Colab](https://colab.research.google.com/drive/1ADuAljjS98ocMcGExwKrLPuRcC1nF9jc?usp=sharing#scrollTo=sLZwvh7JYl1J)
