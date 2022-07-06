### Chicago Crime Analysis

#### Dataset:
https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

#### Introduction:
The primary goal of this project is to use statistical methods to analyse and compare the patterns of Chicago crime based on historical patterns.
Using the Chicago crime dataset, we developed a prediction model for forecasting crime frequency based on time series, and analysed patterns for when a crime was likely to occur and when it was necessary to be more cautious.

#### Seasonal Plot:
<img width="980" alt="Seasonal_Plot" src="https://user-images.githubusercontent.com/97490301/177656067-40ef7e72-6bb3-4753-a501-457360becc6f.png">

#### Conclusion:
This data analytic research provided us with a scientific perspective on the security and crime rates in Chicago. The frequency of occurrence of the crime trend, according to the analytical results and visualisation, repeats every 12 months. It is also worth noting that volatility has decreased in recent years, and months with low crime rates have been significantly lower than in previous years.
In addition, we looked at the pattern of high peaks in criminal activity in Chicago during the months of June, July, and August. The lockdowns imposed at the start of the COVID-19 pandemic may account for the significant drop in crime in the first few months of 2020. While ARIMA models forecast using the entire time series, exponential smoothing methods prioritize the most recent observations. In this dataset, however, a SARIMA model produced the best results. The 12-month crime rate predictions are well explained by the SARIMA model with ARIMA(2,0,1)(2,0,0)(12).
