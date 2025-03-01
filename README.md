# Time-Series-Forecasting-of-Walmart-Sales-Using-ARIMA-SARIMA

### Project Overview  
This project applies **Time Series Forecasting** techniques to predict **Walmart's future sales** using **ARIMA and SARIMA models**. The goal is to identify seasonal trends and improve forecasting accuracy.  

### Tools & Technologies 
- **Python** (Pandas, NumPy, Matplotlib, Statsmodels)  
- **Auto-ARIMA** (pmdarima) for model selection  
- **SARIMA** for capturing seasonality  
- **Evaluation Metrics**: AIC, RMSE, MAE  

### Key Steps  
1. **Data Preprocessing:** Aggregated monthly sales, handled missing values  
2. **Exploratory Analysis:** Visualized trends, performed stationarity tests (ADF)  
3. **Model Selection:** Compared ARIMA & SARIMA using AIC and Auto-ARIMA  
4. **Forecasting:** Predicted sales for the next **12 months**  

### Key Findings 
1. **SARIMA(3,0,1)(1,0,1,12)** outperformed ARIMA in capturing seasonal trends  
2. **Forecasted sales trends** can help optimize inventory planning  

### How to Run the Project 
1️. Clone this repo:  
git clone https://github.com/yourusername/walmart-sales-forecast.git  
2️. Install dependencies:  
pip install pandas numpy statsmodels pmdarima matplotlib
3️3. Run the Jupyter Notebook  
