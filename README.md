# Covid-Cases-and-Death-Forecast
COVID FORECAST
MODEL BUILDING AND OUTCOME

The proposed project to show the expected number of covid19 fatality or cases in the next 12 months and also show where escalation and outbreaks in the future could be.

According to cdc there has been a total of 34,548,847 cases recorded in the last 30 days in the United states and surrounding territories which has shown that there is a new surge of cases likely because of the new Delta variant.

Prior to ETL already performed on CDC dataset, The ARIMA (Autoregressive integrated moving average) was used to build our model. It is a statistical model used to carry out time series analysis and forecasting. 

A grid of p, d and q ARIMA parameters was used for iteration. The performance of the model was evaluated. The AIC(Akaike information criterion) method is used to see how the model best performs and choose the best fit. Several AIC with low values was tested until the best value (4.0) which forecast the fatality and cases for the next 12 months was chosen

MODEL IMPROVEMENT
ARIMA was used for this model but ensemble learning which entails multiple machine learning would have also been to forecast the rate of disease. This method requires a high processor which is not available currently. 
