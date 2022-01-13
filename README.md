# USD-TRY-Currency-Ratio-Forecast
In this project, I made an analysis and forecast of USD/TRY(Turkish Liras) currency ratio by a motivation of current economical crisis Turkey is in. 
Apart from the global crisis, this crisis shows uniqueness with unexpectedly high trend in a short period. 

I scraped daily historical data of USD/TRY Ratio between the years of 2005-2022. There exist libraries for getting data from yahoo finance using API, yet I prefered doing it "manually". After creating csv file of the history, it is updated to most recent daily data. 

It modifies daily data given date intervals as inputs and formats the days as business days excluding weekends. 
Decomposes the timeseries data in 3 parts; trend, seasonality and residuals.
After determining which period does the timeseries data have, determined value is put into prediction function.

This analysis shows that the global peak increase in the ratio at 20th Dec 2022 is biggest outlier data point in history between 2005-2022.

(To be continued)
