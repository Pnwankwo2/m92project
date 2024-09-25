# MODULE 9 - FIRST PROJECT.
# GITHUB Repository name: "m92project.

# TEAM MEMBERS: Patrick Nwankwo, Jesse Poljak, Larry Azar.

# DATA SOURCE:
    # Bank for International Settlements (2024):
    # Effective exchange rates, BIS WS_EER 1.0 (data set):
# https:// data.bis.org/topics/EER/BIS,WS_EER,1.0/D.N.B.US (accessed on 24 September 2024).

# PROJECT AND PURPOSE 
# Our team is going to analyze the United States daily nominal exchange rate from years 1996 to 2024.
# The purpose is to attempt to answer the following questions:
    # how is the data modelled ? 
    # What changes can be identified in the spread of the data? 
    # Do any changes in the spread of the data over time appear to be affected by Seasonality ?
    # Can we make any predictions based on the data and Seasonality?

# EXAMINATION OF THE DATASET 

# What columns are there? 
    # Columns include the daily time period, exchange rate nominal value.
    # The Unit column has a an index, 2020 = 100 as the base year.
    # There is a column for the value of the basket of currencies for 64 
    # economies against which the US Dollar is measured. 

# What unique values do the columns contain?

# Are any columns especially suitable for grouping?

# Are there any interesting questions we have based on the columns available?

# CLEANING THE DATASET 
    # Null values will be dropped, for e.g. for public holidays & weekends. 
    # Static columns will be dropped.

# PERFORMING EXPLORATORY DATA ANALYSIS (EDA)
    # We will create a Prophet model to understand how is the data modelled.
    # We wil fit the Prophet model by providing the future dataset and identifying for any changes due to Seasonality;
    # We will creating a DataFrame for date-times and observations to hold predictions
    # We will conduct a time series forecast for forecasting based on the following Seasonality 
    # The U.S. Presidential Election on the first Tuesday in November every four years
    # The Holiday Season - from end November to beginning of January (for e.g.Thanksgiving, Christmas and New Year) 
    # We are going to compare measurement of central tendency and variability:
        # U.S. Presidential Election Years vs None U.S Presidential Election Years" in 30 days prior and after the election

# ANALYSIS AND CONCLUSIONS 
    


  