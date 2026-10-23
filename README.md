# 📈 USCPI-reconstruction & Forecast

[![Python](https://shields.io)](https://python.org)
[![GitHub Discussions](https://shields.io)](https://github.com)
[![Contributions Welcome](https://shields.io)](https://github.com)

Reconstructing U.S. CPI-U from detailed component indexes and historical expenditure weights using Python. This project also features a custom-built forecast model for US CPI.

---

## 🤖 Current Models & Methodology
After experimenting with various approaches, I have selected and kept two models that yield the most promising results:
* **SARIMAX** (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors)
* **MARS** (Multivariate Adaptive Regression Splines)

### 📊 Exogenous Variables Tested
I have integrated and tested a wide range of exogenous features. So far, the best-performing predictors capturing the core volatility are:
* 🛢️ **Oil Prices**
* 🏠 **Housing Markets Data**

---

## 🚧 Work in Progress & Current Bottleneck
> 💡 **I seem to have hit a wall at the moment.** 
> While the current setup does a good-ish job, this is highly experimental and needs structural and performance improvements. 

---

## 📬 Keen to get Feedbacks!
If you have experience in macro-forecasting, time-series analysis, or feature engineering, **I would love to hear from you!**

* **Have ideas for alternative exogenous variables?**
* **Want to suggest a different model architecture?**

👉 **Please share your thoughts in our [Discussions Tab](https://github.com) or open an Issue!**
