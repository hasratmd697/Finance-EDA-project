# Finance-EDA-project

This project analyzes stock data of major U.S. banks from **2006 to 2016**, using Python libraries such as **pandas, NumPy, seaborn, and yfinance**. It explores stock price trends, returns, and risk metrics.

## Features
- **Data Retrieval:** Fetches historical stock data for **Bank of America, Citigroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley, and Wells Fargo** using `yfinance`.
- **Data Processing:** Organizes stock data into a structured MultiIndex DataFrame.
- **Returns Calculation:** Computes daily percentage returns for each bank.
- **Exploratory Data Analysis (EDA):**
  - Pairplot visualization of stock returns.
  - Identification of **best & worst** single-day returns.
  - Standard deviation analysis to assess risk.
  - Distribution plots for major market events (**2008 financial crisis**).
- **Time-Series Visualization:** Plots stock closing prices over time.
- **Interactive Analysis:** Uses `cufflinks` for offline plotting.

## Libraries Used
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `yfinance`
- `pandas_datareader`
- `cufflinks`

## Getting Started
## Install dependencies:
```bash
pip install pandas numpy seaborn matplotlib yfinance pandas_datareader cufflinks
```
### Run the script:
```bash
python finance_data_analysis_project.py
```

## Insights
- **Citigroup** had the highest risk during the **2008 crisis**.
- **Morgan Stanley's** returns were highly volatile in **2015**.
- Certain banks experienced major fluctuations on **inauguration days**.

