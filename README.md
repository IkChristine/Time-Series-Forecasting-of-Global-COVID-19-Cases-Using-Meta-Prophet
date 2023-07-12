# Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet

This project analyzes the transmission of corona virus across the globe and train a time-series forcasting model (prophet) to get the projection of corona virus-related cases for the next month in the United States.

Prophet is a procedure for forcasting time series data based on an additive regression model where non-linear trends are fit with yearly, weekly, and deaily seasonality plus holiday effects.

*Data Source*
- https://www.kaggle.com/datasets/sambelkacem/covid19-algeria-and-world-dataset

- ## INTERACTIVE DATA VISUALIZATION - PART #1
  <img width="731" alt="image" src="https://github.com/IkChristine/Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet/assets/104997783/2c02ca02-f28e-485a-a98c-7554d663f4f3">

- Graph shows that United states had the highest number of covid cases
- India was the second highest
- 
<p>&nbsp;</p>

  <img width="730" alt="image" src="https://github.com/IkChristine/Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet/assets/104997783/aecf7d5c-e342-4a83-b78e-084a6f846e4b">
<p>&nbsp;</p>

<img width="731" alt="image" src="https://github.com/IkChristine/Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet/assets/104997783/ae6f7715-0044-497c-9533-2e60bc5e0557">
Top 5 countries with highest number of deaths
1. United States
2. India
3. Mexico
4. United Kingdom
5. Italy

## INTERACTIVE DATA VISUALIZATION - PART #2

![image](https://github.com/IkChristine/Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet/assets/104997783/3f12fc22-d853-4fe9-b241-13923ca84484)

<p>&nbsp;</p>
## PROPHET MODEL

![image](https://github.com/IkChristine/Time-Series-Forecasting-of-Global-COVID-19-Cases-Using-Meta-Prophet/assets/104997783/785fbd36-dcb4-4832-b608-31823d130f18)

R-Sqaure score is 0.7803935858903059
- coefficient of determination of 0.78 is ok due to limited historical data for prophet to make more accurate predictions.


**Conclusion**
- The prohet model did an ok job in predicting the actual number of corona virus cases. However, it fell a little lower (littel conservative) compared to the actual number. 
- For example, in oct 29, model predicted 8.385 million cases, but in real life, there were actually 8.858 million cases that day.

