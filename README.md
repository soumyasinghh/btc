# btc
minor and major project: Predicting btc price.

Dataset used: [https://finance.yahoo.com/quote/BTC-USD/history/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAA_R2UUuBAav0WFoPwh9bEeJuZqR8NGP5QAy9ZzRN-2SE6RM_sX4-cHHRAPrIhwh_JKR9OdRlVSbJDkuvibqlq4UK5YBF74cNeRkzIv0SDXL6TCNTAAJP7m6s5gvduZs3x3Vz-uSh5dOhIG7WodQd0-0x453fePVMARBWbstwwHI](https://finance.yahoo.com/quote/BTC-INR/history/?period1=1556880781&period2=1714733559)
[Live data from YahooFinance of year 2019-2024]

use of keras, tensorflow, pandas, numpy, matplotlib, seaborn etc.
various experiments with models to predict most accurately.
* Dense model - horizon 1 window 7
* dense - horizon 1 window 30
* dense - horizon 7 window 30
* Conv1D - horizon 1 window 7
* LSTM - horizon 1 window 7
* dense - horizon 1 window 7 and block reward size
* n - beats algorithm - horizon 1 window 7

* With CONV 1D performing the best almost 85% of the time
