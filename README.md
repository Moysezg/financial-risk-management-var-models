# Quantitative Financial Risk Management & Value at Risk (VaR) Framework

A comprehensive Python suite for estimating, simulating, and stress-testing **Value at Risk (VaR)** across multiple market conditions using parametric, non-parametric, dynamic econometric, and stochastic methods.

---

## 📌 Risk Methodologies Implemented

* **Parametric & Historical Estimations:** Historical VaR, Normal Parametric VaR, and Exponentially Weighted Moving Average (EWMA) for dynamic variance decay.
* **Econometric & Volatility Modeling:** Dynamic GARCH(1,1) VaR capturing volatility clustering and time-varying variance.
* **Stochastic Simulation & Jump Processes:** Correlated Monte Carlo simulations integrated with Extreme Value Theory (EVT) and Jump-Diffusion processes for heavy-tailed distribution modeling.
* **Dimensionality Reduction:** Portfolio risk decomposition and factor reduction using Principal Component Analysis (PCA).

---

## 🛠️ Tech Stack & Libraries

* **Python 3.x**
* **Quantitative Libraries:** `numpy`, `pandas`, `scipy`, `statsmodels`, `arch`
* **Machine Learning & Linear Algebra:** `scikit-learn` (PCA)
* **Visualization:** `matplotlib`, `seaborn`

---

## 📂 Repository Structure

* `notebooks/`: Individual Google Colab notebooks for each specific VaR estimation model and simulation technique.
