# **Big Tech Companies and Big Tech Stock Prices Dataset**:
  

## Big Tech Companies Dataset

### Description
This dataset lists major technology companies along with their stock symbols. It is useful for mapping stock symbols to company names in financial analysis.

### Variables and Descriptions
- **`stock_symbol`**: The stock symbol representing the technology company on the stock exchange.
- **`company`**: The full name of the technology company.

### Data Types
- **`stock_symbol`**: String (object in pandas)
- **`company`**: String (object in pandas)

---

## Big Tech Stock Prices Dataset

### Description
This dataset provides detailed daily stock price information for major technology companies. It includes data points such as opening price, high, low, closing price, adjusted closing price, and trading volume, which are essential for financial analysis and modeling.

### Variables and Descriptions
- **`stock_symbol`**: The stock symbol of the technology company, allowing for identification of the company's stock data.
- **`date`**: The date the stock prices were recorded.
- **`open`**: The price at which the stock first traded upon the exchange opening that day.
- **`high`**: The highest price the stock traded during the trading day.
- **`low`**: The lowest price the stock traded during the trading day.
- **`close`**: The final price the stock traded during the trading day.
- **`adj_close`**: The closing price after adjustments for all applicable splits and dividend distributions.
- **`volume`**: The total number of shares traded during the trading day.

### Data Types
- **`stock_symbol`**: String (object in pandas)
- **`date`**: String (object in pandas) should be treated as Date in analyses.
- **`open`**: Floating point number (float64 in pandas)
- **`high`**: Floating point number (float64 in pandas)
- **`low`**: Floating point number (float64 in pandas)
- **`close`**: Floating point number (float64 in pandas)
- **`adj_close`**: Floating point number (float64 in pandas)
- **`volume`**: Integer (int64 in pandas)
