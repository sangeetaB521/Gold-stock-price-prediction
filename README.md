# Gold Price Prediction using Prophet

This repository contains a Jupyter Notebook that analyzes historical gold price data and applies the **Prophet** time series forecasting model to predict future gold prices. The project explores trends in gold prices over time, visualizes the data, and uses machine learning techniques to forecast potential future price movements.

## Installation

To run this notebook and replicate the analysis, you'll need to install the following Python libraries:

- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `prophet`: For time series forecasting.

You can install these libraries using `pip`. Open your terminal or command prompt and run the following command:

```bash
pip install pandas numpy matplotlib prophet

Usage
1. Load the Data
The gold price data is loaded from a CSV file. Ensure the Gold Price.csv file is correctly placed in your working directory or update the file path in the code.

2. Data Preprocessing
To properly analyze the data, the Date column is converted into a datetime format for easier manipulation.

3. Data Visualization
We visualize the distribution of the gold price with a histogram to understand its frequency and spread. Additional plots like the time series of the gold prices can be generated to observe trends over time.

4. Time Series Analysis
The notebook performs time series analysis to identify patterns and trends in the gold prices. We compute monthly averages and visualize the price trends.

5. Forecasting with Prophet
Using the Prophet time series model, we forecast future gold prices. The model is trained on historical data and used to predict gold prices for the next 365 days.

6. Interpretation of Results
Weekly Trend: The gold price typically rises on Monday when markets open and again on Friday when markets close.

Yearly Trend: The price tends to rise before May, likely due to the Hindu festival "Akshay Tritiya," and then experiences a constant decline with a mild peak around November.

Forecast for 2025: The model predicts a peak of ₹90,000 and a low of ₹78,000 for the gold price in 2025.

License
This project is licensed under the MIT License - see the LICENSE file for details.
