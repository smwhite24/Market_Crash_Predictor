# Predicting Stock Market Crashes: A Comprehensive Analysis Using Economic Variables

## Introduction

### Overview of Stock Market Crashes
A stock market crash is defined as a sudden and significant decline in the value of a stock market, typically marked by a drop of 10% or more in a major index, such as the S&P 500, within a short timeframe. These dramatic downturns can be triggered by various factors, including economic downturns, political instability, natural disasters, or abrupt shifts in investor sentiment. Understanding these events is important for understanding the elements of financial markets and their impact on the economy.

### Importance of Predicting Crashes
Predicting stock market crashes holds great importance for stakeholders, including individual investors, financial institutions, policymakers, and the broader economy. By recognizing the potential for market downturns, stakeholders can make more informed decisions and implement proactive measures that mitigate adverse effects. Effective predictions can lead to risk management strategies that preserve capital, enhance economic stability, and promote responsible investment practices.

### Brief Explanation of the S&P 500 Index
The S&P 500, or Standard & Poor's 500, is a stock market index that measures the performance of 500 of the largest publicly traded companies in the United States. It is widely regarded as one of the most accurate representations of the U.S. stock market and serves as a key indicator of the overall health of the economy. The index is market capitalization-weighted, meaning that larger companies have a greater influence on its performance, providing a comprehensive view of market trends and economic conditions.


## Economic Variables

### GDP (Gross Domestic Product)
- **Definition and significance**
GDP is a measure of a country's economic activity, which is the total value of goods and services produced within a country minus the value of the goods and services used to produce them.
- Historical correlation with stock market performance

<img width="1160" alt="Screenshot 2024-11-12 at 8 56 06 AM" src="https://github.com/user-attachments/assets/ef57d245-708f-4598-a6b6-dfeb1295cb9b">

### Inflation
- **Definition and impact on purchasing power**
Inflation is the rate of increase in prices over a given period of time. Inflation is typically a broad measure, such as the overall increase in prices or the increase in the cost of living in a country.
- Relationship between inflation rates and stock market trends
<img width="1150" alt="Screenshot 2024-11-12 at 8 58 05 AM" src="https://github.com/user-attachments/assets/b25b76af-979e-413e-b6bd-1cb2f5abc1bc">


### Interest Rates
- **Explanation of interest rates and their role in the economy**
the proportion of a loan that is charged as interest to the borrower, typically expressed as an annual percentage of the loan outstanding. The rates affect whether or not companies or consumers buy or sell product.
- How changes in interest rates affect stock market investments

<img width="1153" alt="Screenshot 2024-11-12 at 8 51 19 AM" src="https://github.com/user-attachments/assets/334bfe3d-d1cb-424b-8f13-6bb7ff45ca6e">

### Unemployment
- **Definition and implications for economic health**
In economics, unemployment is when someone is able and willing to work but is not currently employed. It's a key indicator of a country's economic health.
- Connection between unemployment rates and market performance

<img width="1153" alt="Screenshot 2024-11-12 at 9 14 43 AM" src="https://github.com/user-attachments/assets/c4d6bc18-ffd2-492f-8f9d-fdee60dcc01f">

## Methodology

### Data Collection
- Sources of economic data
S&P500 Historical data from Yahoo Finance 
Federal Reserve of St. Louis (FRED) 

### Statistical Analysis
- Techniques used (e.g., regression analysis, time series analysis)
- Tools and software for analysis (e.g., Python, R)

## Predictive Model Development

### Model Selection
- Types of models
Linear Regression Model
Random Forest Model
- Justification for chosen model(s)
We wanted to see if one model made more accurate predictions than another so we chose to do both Linear Regression as Random Forest

### Feature Engineering
- Selection of relevant features from economic variables
- Techniques for improving model accuracy

## Results and Discussion

### Model Performance
- Metrics for evaluating model accuracy

- Random Forest
Weighted Precision: 0.98
Weighted Recall: 0.98
F1 Score: 0.98
- Comparison of predicted vs. actual market movements

### Insights
- Key findings from the analysis
- Implications for investors and policymakers

## Conclusion

- Summary of findings
- Limitations of the study
- Recommendations for future research

## References

- https://fred.stlouisfed.org/
- https://finance.yahoo.com/
- class resources
- Xpert Learning Assistant

## Appendices

Charts predicting probability based on logistic regression models (interactive charts can be utilized in script:
## 1987 Crash
<img width="975" alt="Screenshot 2024-11-12 at 4 20 39 PM" src="https://github.com/user-attachments/assets/2554e373-b72e-4c54-aa45-3d9a7026b5c3">


## 2000-2002 Crash

<img width="979" alt="Screenshot 2024-11-12 at 4 21 39 PM" src="https://github.com/user-attachments/assets/2f0fc52e-46c6-4850-9cb1-34eb86e82106">

## 2008 Crash
<img width="988" alt="Screenshot 2024-11-12 at 4 22 24 PM" src="https://github.com/user-attachments/assets/ed832e6a-eb97-490e-93f7-594d91e91d88">

## 2020- COVID

<img width="976" alt="Screenshot 2024-11-12 at 4 23 09 PM" src="https://github.com/user-attachments/assets/2a7491f1-d97d-47e5-81c7-227868e759f4">




