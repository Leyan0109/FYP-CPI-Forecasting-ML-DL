# 📈 Forecasting the Consumer Price Index of Malaysia  
## A Comparative Study of Machine & Deep Learning Approaches

Accurate forecasting of the Consumer Price Index (CPI) is significant for informed economic planning and decision-making. This project compares the performance of four machine and deep learning models in predicting Malaysia's CPI using various input structures.

### 🧠 Models Compared
- **Support Vector Regression (SVR)**
- **Random Forest (RF)**
- **XGBoost**
- **Neural Networks (NN)**

### 📊 Input Structures
1. **Univariate Input**: CPI only  
2. **Multivariate Input**: 12 economic indicators  
3. **Simple Multivariate Input**: Top 3 most correlated indicators

---

## 🔍 Key Findings

- **SVR consistently outperformed** other models across all input settings, particularly when using 12 multivariate indicators.
- In the **multivariate setting**, SVR achieved the best metrics:
  - **MAE:** 0.0584
  - **RMSE:** 0.0710
  - **R²:** 0.99997
- **Random Forest (RF)** also showed strong performance in univariate and simplified multivariate configurations.
- **Neural Networks (NN)** demonstrated the **weakest performance**, particularly in multivariate settings (MAE up to 1.05).

### 🌏 Regional Adaptability
SVR was applied to CPI datasets from **Cambodia**, **Myanmar**, and **Laos** to test cross-country performance.  
It maintained:
- **R² > 0.99**
- **MAE < 0.2**

These results highlight SVR’s robustness across Southeast Asian economies.

---

## 🛠️ Tools & Libraries Used
- Python, Jupyter Notebook
- pandas, numpy, seaborn, matplotlib
- scikit-learn, XGBoost, Keras
- statsmodels, scikit-plot

---

## 📁 Repository Structure
FYP-CPI-Forecasting
1. data/ # Datasets (Malaysia, Cambodia, Laos, Myanmar)
2. notebooks/ # Model development and testing
3. results/ # Visualizations and metrics
4. README.md # Project documentation

## 📌 Conclusion

This study demonstrates that machine learning—particularly Support Vector Regression (SVR) is highly effective in forecasting CPI, outperforming deep learning in both accuracy and consistency. The model's success across neighboring countries suggests its broader regional applicability.



