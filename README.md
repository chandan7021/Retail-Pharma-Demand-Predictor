# 💊 Retail Pharma Demand Predictor

## 📋 Project Overview
This project implements advanced time-series forecasting techniques to predict pharmaceutical sales for a specific retail pharmacy. By analyzing six years of historical transaction data, the system predicts future demand to help optimize inventory levels, reduce wastage, and prevent stockouts.

The solution benchmarks multiple forecasting strategies—ranging from statistical methods to deep learning—to identify the most accurate model for fluctuating daily, weekly, and monthly sales volume.

## 🚀 Key Features
* **Data Analysis**: Exploratory Data Analysis (EDA) of sales trends across 8 different drug categories (ATC Classification).
* **Statistical Modeling**: Implementation of ARIMA and SARIMA for seasonality detection.
* **Machine Learning**: Utilization of Facebook Prophet for handling holidays and changepoints.
* **Deep Learning**: Application of Long Short-Term Memory (LSTM) networks for capturing long-term dependencies.
* **comparative Analysis**: automated benchmarking of model performance using MSE (Mean Squared Error).

## 📊 Dataset Details
The dataset represents 600,000 transaction records collected over a 6-year period (2014-2019). The raw transactional data was transformed and aggregated into time-series formats (hourly, daily, weekly, and monthly).

**Target Categories:**
The analysis focuses on 8 specific Anatomical Therapeutic Chemical (ATC) classes, including:
* **M01AB/M01AE**: Anti-inflammatory and antirheumatic products.
* **N02BA/N02BE**: Analgesics and antipyretics.
* **R03/R06**: Respiratory drugs and antihistamines.

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **Libraries**:
    * `Pandas` & `NumPy`: Data manipulation and time-series aggregation.
    * `Statsmodels`: ARIMA/SARIMA modeling and stationarity tests (ADF).
    * `FbProphet`: Additive regression models for forecasting.
    * `Keras/TensorFlow`: LSTM Neural Networks.
    * `Matplotlib` & `Seaborn`: Visualization of trends and seasonality.

## 📈 Methodology
1.  **Preprocessing**: Handling missing values, down-sampling to specific time intervals, and normalizing data.
2.  **Stationarity Check**: Applying the Augmented Dickey-Fuller (ADF) test to ensure data is suitable for linear models.
3.  **Decomposition**: Breaking down the series into Trend, Seasonality, and Residual components.
4.  **Model Training**:
    * *Baseline*: Naïve and Seasonal Naïve approaches.
    * *Advanced*: Tuning ARIMA parameters (p,d,q) and Prophet hyperparameters.
5.  **Evaluation**: Comparing actual vs. predicted values using Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE).

## 🏁 Getting Started

### Prerequisites
Ensure you have Python installed. You can install the required dependencies using:

```bash
pip install pandas numpy matplotlib seaborn statsmodels fbprophet tensorflow
	
	
	
	
	
	
	
	
	
	
