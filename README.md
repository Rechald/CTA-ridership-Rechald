# CTA-ridership-Rechald

Ziyao Chen CTA-ridership Source Document Description

1. "Ziyao_Chen_CTA_Ridership.ipynb": a runnable script with all the code and explanations
    
    Part I Data Quality check
        Problems found
        A General Function for Data Quality Check
        
    Part II Exploratory Data Analysis
        1. Date
        2. daytype
        3. rides
        4. station_id & stationname
        
    Part III Daily Rides Forecasting
        SARIMA
        LSTM
            step 1 load data for total rides
            step 2 Pre-process the data
            step 3 Train the model and Predict
            Step 4 Store prediction into a dataframe
    
    Part IV Result Discussion
        1. Prediction for Different Stations
        2. Model Evaluation
        3. Aspects to consider for the Model

2. "Ziyao_Chen_CTA_Ridership.html": html version of my script (interactive plot viewable)

3. "CTA_report.html": data quality check report generated using pandas profiling

4. "predict2017.csv": my prediction and actual total daily rides in 2017
  
