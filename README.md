# Corn-Futres-Capstone
My capstone project at Galvanize, I aimed to predict a range of potential corn prices using data on the corn market and the weather in key producing states. I was able to achieve sufficient results for implementing a hedging strategy, although overall returns would not be high enough to warrant speculation.  For current predictions and a prettier presentation, please visit my website: cooperscorn.com

# Summary
Going into the project, I had two main goals:
* Predict the direction of the price movement to lend farmers confidence for hedging their crop production
* Develop a model that would earn acceptable investment returns for traders

To achieve these objectives, I developed several neural networks, which relied on market data as inputs.  While I largely accomplished my goal of predicting direction, investment returns would be substandard for all but those with a very low cost of capital.

# Technology Used
* Python Packages
    * Keras
    * Pandas
    * Numpy
    * SciPy
    * StatsModels
    * IbPy
    * Flask

* AWS EC2

# Data
While not all datasets collected were used as features for the final models, the following was collected.

### Interactive Brokers (Daily Data)
* Corn Futures Prices
* Soybean Futures Prices
* Oil Futures Prices
* $USD Exchange Rate Index

### USDA (Yearly and Quarterly Data)
* Corn Supply Levels
* Acreage Planted
* Yield Estimates

### NOAA (Daily Data)
* Precipitation and Temperatures for Iowa, Illinois, Nebraska, Minnesota, and Indiana
