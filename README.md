# 📈 USCPI-reconstruction & Forecast

Reconstructing U.S. CPI-U from detailed component indexes and historical expenditure weights using Python. This project also features a custom-built forecast model for US CPI.

---

## Current Models & Methodology
After experimenting with various approaches, I have selected and kept two models that yield the most promising results:
* **SARIMAX** (Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors)
* **MARS** (Multivariate Adaptive Regression Splines)

### 📊 Exogenous Variables Tested
I have integrated and tested a wide range of exogenous features. So far, the best-performing predictors capturing the core volatility are:
* 🛢️ **Oil Prices** (WTI crude oil with 1 month lag)
* 🏠 **Housing Markets Data** (HPI with 6 & 9 months lag, for MARS only).
  Data coming from FRED.

---

## 🚧 Work in Progress & Current Bottleneck
> 💡 **I seem to have hit a wall at the moment.** 
> While the current setup does a good-ish job, this is highly experimental and needs structural and performance improvements. I get rather large MAE and RMSE (respectfully 0.5 & 0.67 with SARIMAX and 0.41 & 0.53 with MARS.

---

## 📬 Keen to get Feedbacks!
If you have experience in macro-forecasting, time-series analysis, or feature engineering, **I would be keen to hear your feedbacks**

* **Have ideas for alternative exogenous variables?**
* **Want to suggest a different model architecture?**

👉 **Please share your thoughts in our [Discussions Tab](https://github.com) or open an Issue**

P.S.: it may be obvious, but I'm still very new on Github. So I'm still figuring it all out.
