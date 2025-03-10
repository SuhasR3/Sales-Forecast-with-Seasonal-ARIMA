# Sales Forecasting with Seasonal ARIMA

![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)

## Overview
This project demonstrates the application of the **ARIMA (AutoRegressive Integrated Moving Average), Seasonal ARIMA** models to forecast sales trends using time series data and is built in Python.

## Features
- **End-to-End Pipeline**: From data import to future predictions.
- **Model Comparison**: Evaluates both ARIMA and SARIMA for optimal forecasting.
- **Visualization**: Plots to assess data trends, stationarity, and forecast accuracy.
- **Scalable Approach**: Extensible for other time series datasets.

---

## Skills Demonstrated
- **Data Analysis**: Cleaning, visualizing, and testing time series data.
- **Statistical Modeling**: Implementing ARIMA and SARIMA models.
- **Programming**: Python scripting with libraries like Statsmodels and Matplotlib.
- **Problem-Solving**: Addressing non-stationarity and seasonality in data.
- **Communication**: Clear documentation and interpretable results.

---

## Tech Stack
- **Python**: Core programming language.
- **Pandas**: Data manipulation and preprocessing.
- **NumPy**: Numerical computations.
- **Tableau/Matplotlib/Seaborn**: Data visualization.
- **Statsmodels**: Time series analysis and ARIMA implementation.
- **Jupyter Notebook**: Interactive development and documentation.
 

---

## Project Structure
```
sales-forecasting-arima/
├── Sales-Forecast-with-Seasonal-ARIMA     # Main Python script file
├── datasets/
│   └── monthly-sales-data.csv             # Input dataset
└── output/                                # Folder for output plots (e.g., forecast graphs)
│   ├── arima_output                       # Input dataset
│   └── Screenshots                        # Data exploration Results
├── README.md                              # Project overview
├── License.md                             # MIT License
└── .ipynb checkpoints/                    # Folder for ipynb checkpoints

```

---

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/time-series-forecasting.git
   cd time-series-forecasting
   ```
   
2. **Install Dependencies and Set up environment**: Ensure you have Python 3.7+ and install required libraries:
```bash
pip install numpy pandas matplotlib statsmodels
```

3. **Prepare Data**: Place monthly-sales-data.csv in the Datasets folder or update the script path to dataset location.
  
4. **Run the Notebook**: Launch Jupyter Notebook and open Sales_Forecasting_ARIMA.ipynb::
   ```bash
   jupyter notebook
   ```
   
5. **Explore the Code**: Follow the notebook for a detailed walkthrough of data preparation, model building, and forecasting.

## Results
![](https://github.com/SuhasR3/Sales-Forecast-using-ARIMA-Model/blob/main/outputs/arima_output.png)
Based on the SARIMA model, we have generated a sales forecast for the next two years. We can see that the model understands the trends and patterns and is successful at predicting the expected sales.

#### ARIMA(1,1,1) Model:
**Coefficients**: ar.L1 = 0.4545, ma.L1 = -0.9666 (both significant, p<0.001).
**Fit Metrics**: AIC = 1911.627, BIC = 1919.560.
**Diagnostics**: Random residuals (Ljung-Box p=0.34), normal distribution (Jarque-Bera p=0.27)
In-sample forecasts aligned reasonably with actual sales.


## Contributing
Feel free to fork this repository, submit issues, or propose enhancements! I welcome feedback to refine my skills and this project.

## License
This project is licensed under the MIT License. Feel free to use and adapt the code for your purposes.
