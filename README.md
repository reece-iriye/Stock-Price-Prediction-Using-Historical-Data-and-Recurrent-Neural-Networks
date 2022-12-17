# **Stock Price Prediction Using Historical Data and Recurrent Neural Networks (RNNs)**
**Author:** Reece Iriye



**Course:** MATH 4377 (Math of Machine Learning)



**Section:** Fall 2022, TTh 12:30-1:50PM, 001-LEC



**Department:** Mathematics



## **Project Description**
This project studies the usage of historical data and recurrent neural network to predict a stock price or an index. I will choose to use regression to predict a stock price or an index, instead of classification to predict whether or not there exists an overall upward or downward trend.
### **Data Generation**
1. Go to http://finance.yahoo.com
2. Search one (or several, depending on the need for your model) of the stocks from a company (apple, amazon, microsoft, etc.) or one or several stock indices (S&P 500, Dow 30, Nasdaq, Russell 2000, Crude Oil, etc.)
3. Once the stock or index’s quote page is shown, click the “Historic Data” tab and change “the time period” as needed. Note normally we prefer more data for a neural network.
4. Click “Apply” and then click “download” below the “Apply” button and a CSV data will be generated and downloaded to your computer.


*Note*: I will need to pick a time period and decide how many data points to produce. I will need to rearrange the data into time series by lagging the data to obtain percentage returns instead of raw closing price data. I will also need to split my data into a training set and a testing set thus the validation can be performed. 


### **Recurrent Neural Network (RNN)**


I need to setup a RNN model and use the obtained data to predict stock prices. I will consider the following questions when you setup the RNN:


1. What's the overall dimension of the RNN?
2. What is the number of time steps for returns? In predicting n-day returns, what am I specifying as n?
3. How many neurons are in the hidden layer?
4. Did I use the LSTM, if so what are the related parameters?
5. What is my choice of activation function? Why?


### **Research Objective**

Through this project, I will demonstrate:
1. Cleaning and rearranging data in the form that a neural network can be applied on.
2. Setting up a RNN model that is working.
3. Further tuning the model by modifying model parameters to finalize an optimized model.
4. Getting *creative* based on accumulated knowledge and skills.


## **Project Implementation**

See `main.ipynb` for complete project.
