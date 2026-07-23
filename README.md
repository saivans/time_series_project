### Time Series Forecasting: Global Internet Adoption

**Overview**
This project explores and forecasts global internet adoption trends, with a specific focus on estimating daily Internet Penetration Rates. By leveraging a comprehensive dataset of macroeconomic, technological, and demographic indicators, this project aims to build robust time-series forecasting models to predict future connectivity trends.

**Dataset**
The analysis utilizes **data.csv**, a rich dataset spanning from January 2015 to July 2025.
Key attributes include:

* **Scope:** 50 distinct countries, featuring 191,900 total observations.
* **Target Variable:** `Internet_Penetration (%)`
* **Features:** 28 columns capturing diverse metrics such as `Broadband_Speed (Mbps)`, `GDP_Per_Capita (USD)`, `AI_Adoption_Index (%)`, and `Cloud_Service_Adoption (%)`.

**Project Workflow**

1. **Data Loading & Preprocessing:** Importing the raw data, converting date columns to datetime objects, setting datetime indexes, and isolating the United States for the primary time-series track.
2. **Exploratory Data Analysis (EDA):** Verifying time-dimension consistency, checking for missing dates, and ensuring target variable continuity (zero sparsity).
3. **Data Visualization:** Uncovering trends, seasonality, and correlations using time-series specific visual diagnostics (Lag plots, Autocorrelation, etc.).
4. **Model Building:** Implementing and benchmarking various forecasting algorithms.

**Tech Stack**

* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Linear Regression, Random Forest, TimeSeriesSplit)
* **Advanced Boosting:** `xgboost`, `lightgbm`

**Setup & Installation**
Ensure you have the required Python libraries installed before running the Jupyter Notebook:
`pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm`

