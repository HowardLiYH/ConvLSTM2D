# A Forcasting project on China's 50 ETF option market done during Quantitative Research Internship at QTG Capital in Spring 2023
Status: Onging

## 1) Full cycle modeling operation on forecasting future option price movements on China’s options market inferred through at-the-money volatility win ratio.
1. Constructed over 80 features such as Skew, Kurtosis, at-the-money volatility (based on 25 Delta, 10 Delta, and 50 Delta), Open Interest PCR, Volatility PCR, underlying asset MA, turnovers, and more as model inputs.
2. Attempted on GARCH model as benchmark to compare with RF and LGBM.



## 2) Attempted ConvLSTM2D + Conv2D Deep Learning structure to forecast At-The-Money implied volatility return on Chinese 50ETF option market.

The Implied Volatility Surface is constructed by 
1. Skew calculated by 25 Delta
2. Skew calculated by 10 Delta
3. Kurtosis calculated by 25 Delta
4. Kurtosis calculated by 10 Delta
5. At-The-Money Volatility

The input data includes all the trading days' Call, Put, Strike price in between Jan 2015 and Mar 2023 with respect to three due days (This month, Next Month, Next Quarter)

The forcasting was initially done on the daily basis and later dived into hourly and minutely time frame.
