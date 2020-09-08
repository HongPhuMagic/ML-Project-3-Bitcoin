# ML-Project-3-Bitcoin


#### Project Goal

The goal of this project was to predict bitcoin (btc) prices using ARIMA (Auto Regressive Integrated Moving Average), a form of linear model, and RNN. 
One thing to note is that; bitcoin is known to be very manipulated so I did not expect my model to perform well. 

#### Conclusion

I have completed my RNN model to predict bitcoin prices. However, the performance was poor which could be due to many reasons. So it was clear that this model was not able to forecast bitcoin's prices which I had expected. As the model tried to forecast further into the future, the errors that it may picked up while trying to forecasting will be magnified the further we try to forecast because the model will be forecasting the forecast. 

![](Pictures/bt.JPG)

I have yet to finish this project due to my limited knowledge of ARIMA. I plan on finishing this project as soon as I gain more knowledge. When I obtain enough knowledge, I will also try to use RNN to predict not too far into the future and hopfully get a better performing model.

Bitcoin is a very volatile and manipulated asset. Predicting bitcoin's price from past history's data will not be enough to accurately predict bitcoin prices. 

#### Data Source

I have created my own dataset by webscraping coinmarketcap using Selenium and <xpath>. I then created the CSV file which contains all of the lists/arrrays I scraped. I chose Selenium over faster methods such as scrapy or beautiful soup due to its capabilities in htlm interaction. I plan on making a trading bot in the future. 
  
#### Data Description

This dataset has 6 different columns, all object data types. I intend to convert them into different data types; 1 datetime and 4 float, with 2660 rows/entries. Each float data type column describes candle properties except for the 'Volume' column. 


