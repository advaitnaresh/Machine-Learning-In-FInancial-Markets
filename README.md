# Machine-Learning-In-FInancial-Markets

* This repository is for SOP under Prof. JK Sahoo , under the topic Machine Learning in Financial Markets. 
* All the work done in this repository is by : Advait Naresh Jishnani
* Bits Pilani Goa Campus. 

# 5-day Regressive Model

* This model was designed to take the stock prices of 5 days and then create a moving average based on that. This in turn helped us predict the stock prices for the periods to follow. 
* The model could give semi-accurate results. But it was better than the 3 day moving average.
* This in turn led us to follow a different approach and try the ARIMA model.

# Auto Regressive Integrated Moving Average (Arima)

* This is the main outcome of the project. The porject revolved on optimising the results of the ARIMA model. 
* The model is uploaded as a jupyter notebook file and can be viewed accordingly. 
* The model showed promising results and had a good enough accuracy of around 82%.
* The file used gcp ( Google Cloud Platform ) to source its datas using pandas. The data chosen was of Apple stock for the year 2009-2019. Total 10 years worth of stock market data.
* The model was trained on the first two years of market data and then the predictions were made. 
