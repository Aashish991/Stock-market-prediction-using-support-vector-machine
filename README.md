# Stock-market-prediction-using-support-vector-machine

here i will do predictive modelling to help make trade calls

share/stock- part of public company which we can buy or sell
trading- one person willing to sell another willing to buy
price fluctuation- based on demand of stock compared to supply
simple moving average(rolling mean)[ SMA ]-mean of only selected range of values
	= adding recent prices/number of period
	4th day= pvs 3 day avg
Bollinger Bonds-identify overbought and oversold signals
	has 3 lines- upper band, middle band, lower band
	middle band- is SMA
	upper band and lower band - 2 pos & neg standard deviation away from SMA
	n - SMA +/- k*[n - SD]
	k - no. of SD
	SMA - n period SMA 	-usually 20 period and 2 SD
identify trading signals-
squeeze situation- upper band and lower band close to SMA 
	means market volatility(S.D.) is low - people believe increase in
	volatility after this- opportunities for trading
	
	overbought- closing price near to upper band
	oversold- closing price near to lower band
	
trade call- cheap- price breaks lower bollinger band
	- BUY- closing price < lower band
 	- SELL- closing price > upper band
	- HOLD- upper band > closing price > lower band
