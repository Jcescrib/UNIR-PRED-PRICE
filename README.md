# 📊 Cryptocurrency Price Prediction Models Analysis 🚀

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebooks-orange?logo=google)
![Binance API](https://img.shields.io/badge/Binance-API-yellow?logo=binance)
![Prophet](https://img.shields.io/badge/Prophet-Forecasting-green)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?logo=python)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blue?logo=python)
![SciPy](https://img.shields.io/badge/SciPy-Scientific%20Computing-blue?logo=scipy)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikit-learn)
![Pmdarima](https://img.shields.io/badge/Pmdarima-ARIMA-blue)

This project, developed as a **Master's Thesis** for the *Master’s Degree in Big Data Analysis and Visualization* at the **International University of La Rioja**, focuses on predicting the **BTC/USDT** pair prices using time series models. 🎯 The main goal is to select an optimal algorithm for forecasting future Bitcoin values, considering **accuracy**, **complexity**, and **robustness**.

## 🛠️ Methodology

1. **📥 Data Collection**: Historical BTC/USDT data was gathered using the **Binance API**.
2. **🔍 Statistical Analysis**: Comprehensive data analysis was performed, including correlations, seasonality, and stationarity (Dickey-Fuller test).
3. **🤖 Evaluated Models**: **25 models** of machine learning and time series were analyzed, including ARIMA, SARIMA, SARIMAX, VAR, SES, HWES, and **Prophet**.
4. **⚙️ Selection and Optimization**: The most promising models (**AutoARIMA** and **Prophet**) were selected and their hyperparameters optimized.
5. **📈 Results**: The **optimized Prophet model** was chosen for its balance of accuracy (**MAE: 1041.57**, **RMSE: 1096.99**), simplicity, and robustness against missing data.

## 💻 Technologies Used

- **🐍 Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, Scikit-learn, Pmdarima, Prophet.
- **☁️ Environment**: Google Colab for development and analysis.
- **📊 Data**: Binance API for historical BTC/USDT data.

## ✅ Conclusions

The **optimized Prophet model**, with hyperparameters such as `changepoint_prior_scale=0.5`, `holidays_prior_scale=0.2`, and `seasonality_mode='multiplicative'`, provides a **robust and efficient** solution for cryptocurrency price prediction. 💸 Although its results are similar to SARIMA, Prophet stands out for its **simplicity** and ability to handle incomplete data.

## 🔮 Future Work

- 🌐 Real-time data integration with **Apache Kafka** and **Spark**.
- 🗣️ Sentiment analysis on social media (tweets) to enhance predictions.
- 🧠 Exploration of *deep learning* models to enrich the analysis.

## 🌐 Repository

🔗 [**https://github.com/Jcescrib/UNIR-PRED-PRICE**](https://github.com/Jcescrib/UNIR-PRED-PRICE)

---

### 📋 Usage Instructions

1. Clone the repository: `git clone https://github.com/Jcescrib/UNIR-PRED-PRICE.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebooks in **Google Colab** or a local Python environment.
4. Configure **Binance API** credentials to access historical data.
5. Run the notebooks to reproduce the analyses and predictions.

### 🤝 Contributions

Contributions are welcome! 🙌 If you wish to collaborate, please review the [contribution guidelines](CONTRIBUTING.md) and open a *pull request*.

---

⭐ If you like this project, don’t forget to give it a star on GitHub! ⭐
