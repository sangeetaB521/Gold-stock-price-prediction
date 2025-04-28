# Gold Price Prediction using Prophet
This repository contains a Jupyter Notebook that analyzes historical gold price data and uses the Prophet time series forecasting model to predict future gold prices.


## Installation

To run this notebook, you need to have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `prophet`

### 1. Load the Data

The gold price data is loaded from a CSV file. Make sure the `Gold Price.csv` file is in the appropriate location or update the file path in the code.

```python
gold_df = pd.read_csv('path/to/Gold Price.csv')


#### 5. **Results and Interpretation**
Add the results and any important visualizations.
```markdown
### 6. Interpretation of Results

- **Weekly Trend**: The gold price typically rises on Monday when markets open and again on Friday when markets close.
- **Yearly Trend**: The price tends to rise before May, likely due to the Hindu festival "Akshay Tritiya," and then experiences a constant decline with a mild peak around November.
- **Forecast for 2025**: The model predicts a peak of ₹90,000 and a low of ₹78,000 for the gold price in 2025.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


