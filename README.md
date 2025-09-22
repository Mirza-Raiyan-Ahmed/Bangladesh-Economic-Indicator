This project analyzes Bangladesh’s economic indicators (GDP, Inflation, Unemployment, Investment, etc.) from 1980–2019, using time series analysis, econometric models, and visualization techniques.

The dataset: BD_economic_indicators.csv

🚀 Features of the Analysis

Data Cleaning & Preprocessing

Removal of commas & percent signs

Conversion to numeric values

Time index (Year) handling

Exploratory Analysis

Line plots of each economic indicator

Correlation heatmap & pairplots

Descriptive statistics

Econometric Modeling

ADF Stationarity Tests

Vector AutoRegression (VAR) with Granger causality

ARIMA Forecasting for GDP growth

Multiple Regression (OLS): GDP growth vs inflation, unemployment, investment

Seasonal Decomposition of GDP growth

Visualization

Time series subplots

Correlation heatmap

Forecast plots with confidence intervals

Regression diagnostic plots

🛠️ Tech Stack

Python 3.10+

Libraries

pandas, numpy

matplotlib, seaborn

statsmodels

scikit-learn

scipy

📂 Project Structure
.
├── BD_economic_indicators.csv   # Dataset
├── analysis.py                  # Main analysis script
├── README.md                    # Project documentation
└── results/                     # Saved plots & outputs

📈 Key Results

Stationarity Tests (ADF): Some variables required differencing before VAR analysis.

VAR Model: Detected potential causal links among GDP growth, inflation, and investment.

ARIMA Forecast: Projected GDP growth for the next 5 years, with confidence intervals.

Multiple Regression: GDP growth explained partly by inflation, unemployment, and investment rates.

Decomposition: GDP growth trend showed cyclical fluctuations with residual shocks.

📊 Sample Visualizations

Time Series of Economic Indicators

Correlation Heatmap

GDP Growth Forecast (ARIMA)

Regression Diagnostics

Seasonal Decomposition

(Add screenshots/plots in results/ and embed here)

![GDP Growth Forecast](results/gdp_forecast.png)
![Correlation Heatmap](results/corr_heatmap.png)

📜 How to Run

Clone the repo:

git clone https://github.com/your-username/bd-economic-analysis.git
cd bd-economic-analysis


Install dependencies:

pip install -r requirements.txt


Run analysis:

python analysis.py

📌 Next Steps

Extend dataset to 2020–present

Compare Bangladesh with South Asian peers

Add Machine Learning forecasting (LSTM/Prophet)
