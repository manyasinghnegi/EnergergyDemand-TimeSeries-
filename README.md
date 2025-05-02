# ⚡ Energy Demand Forecasting using Deep Learning and Classical Models

This project focuses on forecasting daily energy consumption (`AEP_MW`) using a combination of traditional statistical models and modern machine learning/deep learning approaches. Accurate energy demand forecasting is crucial for power grid reliability, planning, and cost efficiency.

---

## 🔍 Objective

To develop and compare multiple forecasting models for short-term energy demand prediction and evaluate them using real-world historical energy consumption data.

---

## 📂 Dataset

- **Source**: US Energy Information Administration (EIA)  
- **Feature Used**: `AEP_MW` – Energy consumption in megawatts  
- **Time Span**: 2004–2018 (daily data)

---

## 🧠 Models Implemented

### 🔸 LSTM (Long Short-Term Memory Neural Network)
- Deep RNN-based model with 4 stacked LSTM layers and dropout regularization  
- Handles temporal dependencies effectively  
- Trained on past 60-day windows to predict future values

### 🔸 Linear Regression
- Simple lag-based model using the previous day’s value as a feature  
- Easy to interpret but limited in capturing complex patterns

### 🔸 Random Forest Regressor
- Tree-based ensemble model using previous value as a feature  
- Capable of modeling non-linear dependencies with high accuracy

### 🔸 ARIMA (AutoRegressive Integrated Moving Average)
- Traditional time series model with order (5,1,0)  
- Efficient for trend-based forecasting in stationary data

---

## 📊 Evaluation Metrics

- **RMSE**: Root Mean Squared Error  
- **MAE**: Mean Absolute Error  
- **Error Distribution Analysis**: Histogram of residuals

---

## 📈 Visualizations

- Forecasted vs Actual plots for each model  
- Residual (error) distribution comparison  
- Energy consumption trends over time

---

## 📝 Conclusion

- ✅ **LSTM** outperformed other models in capturing temporal patterns, especially non-linear fluctuations  
- ✅ **Random Forest** showed competitive performance with fast inference and robustness  
- ⚠️ **ARIMA** and **Linear Regression** were limited in long-term forecasting but served as effective baselines  
- 📉 Error distribution analysis helped highlight model biases and variance patterns

---

## 🚀 Tech Stack

- **Languages**: Python  
- **Libraries**:  
  - NumPy  
  - Pandas  
  - Scikit-learn  
  - Statsmodels  
  - TensorFlow / Keras  
  - Matplotlib  
  - Seaborn

---

## 📌 Project Highlights

- 🧪 Comparative study of traditional and deep learning models  
- 📊 Visual and statistical analysis of performance  
- 📦 Clean code structure with modular training and evaluation

---



