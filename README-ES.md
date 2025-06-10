# 📊 Análisis de Modelos de Predicción de Precios de Criptomonedas 🚀

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

Este proyecto, desarrollado como **Trabajo Fin de Máster** en el *Máster Universitario en Análisis y Visualización de Datos Masivos* de la **Universidad Internacional de La Rioja**, se centra en la predicción de precios del par **BTC/USDT** utilizando modelos de series temporales. 🎯 El objetivo principal es seleccionar un algoritmo óptimo para predecir valores futuros de Bitcoin, considerando **precisión**, **complejidad** y **robustez**.

## 🛠️ Metodología

1. **📥 Obtención de datos**: Se recopilaron datos históricos de BTC/USDT mediante la **API de Binance**.
2. **🔍 Análisis estadístico**: Se realizó un análisis exhaustivo de los datos, incluyendo correlaciones, estacionalidad y estacionariedad (prueba Dickey-Fuller).
3. **🤖 Modelos evaluados**: Se analizaron **25 modelos** de machine learning y series temporales, incluyendo ARIMA, SARIMA, SARIMAX, VAR, SES, HWES y **Prophet**.
4. **⚙️ Selección y optimización**: Se seleccionaron los modelos más prometedores (**AutoARIMA** y **Prophet**) y se optimizaron sus hiperparámetros.
5. **📈 Resultados**: El modelo **Prophet optimizado** fue seleccionado por su balance entre precisión (**MAE: 1041.57**, **RMSE: 1096.99**), simplicidad y robustez frente a datos faltantes.

## 💻 Tecnologías Utilizadas

- **🐍 Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy, Statsmodels, Scikit-learn, Pmdarima, Prophet.
- **☁️ Entorno**: Google Colab para desarrollo y análisis.
- **📊 Datos**: API de Binance para datos históricos de BTC/USDT.

## ✅ Conclusiones

El modelo **Prophet optimizado**, con hiperparámetros como `changepoint_prior_scale=0.5`, `holidays_prior_scale=0.2`, y `seasonality_mode='multiplicative'`, ofrece una solución **robusta y eficiente** para la predicción de precios de criptomonedas. 💸 Aunque los resultados son similares a SARIMA, Prophet destaca por su **simplicidad** y capacidad para manejar datos incompletos.

## 🔮 Trabajo Futuro

- 🌐 Integración de datos en tiempo real con **Apache Kafka** y **Spark**.
- 🗣️ Análisis de sentimientos en redes sociales (tweets) para mejorar predicciones.
- 🧠 Exploración de modelos de *deep learning* para enriquecer el análisis.

## 🌐 Repositorio

🔗 [**https://github.com/Jcescrib/UNIR-PRED-PRICE**](https://github.com/Jcescrib/UNIR-PRED-PRICE)

---

### 📋 Instrucciones para el Uso

1. Clona el repositorio: `git clone https://github.com/Jcescrib/UNIR-PRED-PRICE.git`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Abre los notebooks en **Google Colab** o un entorno local con Python.
4. Configura las credenciales de la **API de Binance** para obtener datos históricos.
5. Ejecuta los notebooks para reproducir los análisis y predicciones.


---

⭐ ¡Si te gusta este proyecto, no olvides darle una estrella en GitHub! ⭐
