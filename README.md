## ML-Project-3-Bitcoin

#### Conclusion

I have yet to reach to a conclusion due to my limited knowledge of ARIMA. I plan on eventually finishing this project as soon as I have gain more knowledge. I however, finished using rNN as an alternative model to predict bitcoin prices!

#### Project Goal

The goal of this project is to predict bitcoin (btc) prices using ARIMA (Auto Regressive Integrated Moving Average), a form of linear model, and rNN. 
One thing to note is that; bitcoin is known to be very manipulative so I don't expect my model to perform well. 

#### Data Source

I've created my own dataset by webscraping coinmarketcap using Selenium and <xpath>. I then created the CSV file which contains all of the list/arrrays I scraped. I chose Selenium over faster methods such as scrapy or beautiful soup due to its capabilities, htlm interaction. I plan on making a trading bot in the future. 
  
#### Data Description

This dataset has 6 different columns, all object data types with the intention of converting them into different data types; 1 datetime and 4 float, with 2660 rows/entries. Each float data type columns describes candle properties except for 'Volume' column. 


