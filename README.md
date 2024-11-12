# Efficient-Frontier-and-CML-with-2-stocks

This repository presents a comprehensive analysis and visualization of the **Efficient Frontier** and **Capital Market Line (CML)** using historical data for two stocks: **Apple Inc. (AAPL)** and **The Coca-Cola Company (KO)**. The data is sourced directly from Yahoo Finance via the `yfinance` API.

## 📊 Overview

This project demonstrates the steps to compute and graph the efficient frontier and the CML using two assets, AAPL and KO. The efficient frontier represents the set of optimal portfolios that provide the highest expected return for a given level of risk. The CML, on the other hand, illustrates the risk-return trade-off in a market that includes a risk-free asset.

## 🔍 Project Steps

1. **Data Collection**  
   - Obtained historical price data for AAPL and KO using the `yfinance` library.

2. **Efficient Frontier Calculation**  
   - Processed the data to calculate expected returns, variances, and covariances.
   - Applied optimization techniques to identify portfolios that lie on the efficient frontier.

3. **Capital Market Line (CML) Calculation**  
   - Incorporated a risk-free rate to calculate the CML.
   - Determined the optimal risk-return combination on the CML.

4. **Graphical Representation**  
   - Visualized both the efficient frontier and CML on the same plot to highlight the relationships between risk and return, with a clear distinction between the two lines.

## 🛠️ Requirements

- **Python** 3.x
- **yfinance**: For data extraction
- **NumPy** and **Pandas**: For data processing
- **Matplotlib**: For plotting

## 🚀 Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/MarcosGrossi/Efficient-Frontier-and-CML-with-2-stocks.git
