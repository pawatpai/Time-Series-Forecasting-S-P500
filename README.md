
# Time Series Forecasting with S&P 500 Data

## Overview

This project focuses on time series forecasting using S&P 500 closing prices. The objective is to apply various forecasting models to predict future stock prices based on historical data. The analysis includes steps for data preprocessing, model selection, and evaluation.

## Getting Started

### Prerequisites

Before running the notebook, ensure you have the necessary libraries installed. You can install them using the following pip commands:

```bash
pip install numpy==1.26.4
pip install pandas matplotlib seaborn statsmodels scikit-learn pmdarima ipywidgets
```

### Files Required

- **sp500_close.csv**: Historical closing prices for the S&P 500 stocks. Ensure this file is located in the correct directory as specified in the notebook.
- **economic_indicators.csv**: (Optional) Economic indicators data to be used in conjunction with the stock data.

### How to Use the Notebook

1. **Set Up Your Environment**: 
   - Make sure your Python environment has the required packages installed.
   - Load the necessary datasets (`sp500_close.csv` and `economic_indicators.csv` if used).
   - Adjust the file paths in the notebook to match your local setup.

2. **Running the Notebook**:
   - Open the notebook in Jupyter or any compatible platform.
   - Run each cell in sequence to execute the analysis.
   - Modify the stock symbol in the notebook (e.g., replace 'AAPL' with 'GOOGL') if you want to analyze a different stock.

3. **Analysis Steps**:
   - **Data Loading**: The first step involves loading and inspecting the data.
   - **Exploratory Data Analysis (EDA)**: Visualize the time series data to understand patterns such as trends, seasonality, and noise.
   - **Modeling**: Apply various time series models such as ARIMA, SARIMAX, and Exponential Smoothing to forecast future stock prices.
   - **Evaluation**: Evaluate model performance using metrics like Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Results

The notebook will produce several visualizations and statistical outputs that help in understanding the time series characteristics and the forecasting model's performance.

## Customization

- **Changing the Stock**: You can change the stock you want to forecast by updating the stock symbol in the data processing steps.
- **Adding Indicators**: If you wish to include additional economic indicators or other datasets, ensure they are properly formatted and update the code accordingly.

## Contribution

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Any improvements or new models are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or suggestions, please contact Pawat Jiangthiranan at pawatpai@gmail.com.
