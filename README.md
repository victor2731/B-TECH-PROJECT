# B Tech Project
# FORECASTING HYDROCARBON PRODUCTION FROM FRACTURED WELLS

## 🚀 Overview
This project presents a detailed implementation of **Decline Curve Analysis (DCA)**, specifically utilizing **Arps' Hyperbolic Decline Model**, to forecast hydrocarbon production from fractured wells. The work serves as a foundational tool for petroleum engineers to predict future well performance, estimate reserves, and make informed production decisions.

## ✨ Key Features
* **Arps' Hyperbolic Decline Model:** Implements the key mathematical function for production forecasting: `qi / ((1 + b * Di * t) ** (1 / b))`.
* **Model Fitting:** Uses non-linear regression (`scipy.optimize.curve_fit`) to fit historical production data (time and rate) to the hyperbolic model to determine key parameters like initial rate ($q_i$), initial decline rate ($D_i$), and the hyperbolic exponent ($b$).
* **Production Forecasting:** Extends the time range to predict future production rates over a specified period (e.g., 50 future days).
* **Estimated Ultimate Recovery (EUR) Calculation:** Provides the calculation for the EUR, a critical metric for reservoir evaluation.
* **Visualization:** Generates plots to visualize the historical production data against the forecasted decline curve for specific wells (e.g., Well H1).

## 🛠️ Technology Stack
This project primarily uses **Python** for the analytical and forecasting work, along with standard scientific and data manipulation libraries:

* **Python**
* **Pandas:** For data loading and manipulation (e.g., reading `well3.csv`).
* **NumPy:** For numerical operations and array handling.
* **SciPy (`scipy.optimize.curve_fit`):** For fitting the decline curve model to the data.
* **Matplotlib:** For generating production and forecast plots.

## 🎓 Project Context
This work was submitted in partial fulfillment for the award of a Bachelor of Technology degree in Petroleum Engineering.

* **University:** Jawaharlal Nehru Technological University Kakinada (JNTUK)
* **Year:** 2025

### Authors
* MANDAPALLI VICTOR BABU (21021A2731)
* KANDREGULA JAYA PRAKASH NARAYANA (21021A2738)
* ACHANTA DILEEP KUMAR (21021A2756)

### Supervision
* Mr. D. JASWANTH ROY, Assistant Professor, Department of Petroleum Engineering
