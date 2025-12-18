# Solar Power Prediction using Linear Regression

**Solar Power Prediction using Linear Regression**

This project predicts **solar power generation (kW)** using a **Linear Regression** machine learning model.
It was developed and submitted as part of my internship:

**AI & Data Analytics Intern | AICTE Green Skills**

---

**Project Overview**

Solar power prediction helps in better energy planning and grid management. In this project, a supervised machine learning approach is used to predict solar power output based on weather and solar-related parameters.

**Project Workflow**

* Data loading and inspection
* Exploratory Data Analysis (EDA)
* Correlation and outlier analysis
* Feature scaling
* Model training using Linear Regression
* Model evaluation using error metrics

---

**Dataset Information**

* **Total Records:** 4213
* **Total Features:** 21
* **Target Variable:** generated_power_kw

**Key Input Features**

* Temperature (2m above ground)
* Relative humidity
* Mean sea level pressure
* Cloud cover (low, medium, high)
* Shortwave radiation
* Wind speed and direction
* Solar geometry parameters (zenith, azimuth, angle of incidence)

**Dataset Quality**

* No missing values
* No duplicate records

---

**Exploratory Data Analysis (EDA)**

The following EDA techniques were applied:

* Histogram analysis for data distribution
* Scatter plots between features and target variable
* Correlation matrix and heatmap
* Box plots for outlier detection

**Observations**

* Solar power strongly depends on shortwave radiation
* Zenith angle and angle of incidence significantly affect power generation
* High cloud cover and humidity reduce solar power output

---

**Machine Learning Model**

**Model Used**

* Linear Regression (scikit-learn)

**Data Preprocessing**

* Feature and target split
* Train-test split (80% training, 20% testing)
* Feature scaling using StandardScaler

**Libraries Used**

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

**Model Evaluation**

The model performance was evaluated using **Mean Absolute Error (MAE)**.

| Dataset      | MAE (kW) |
| ------------ | -------- |
| Training Set | ~392.42  |
| Test Set     | ~391.79  |

**Interpretation**

* Similar training and testing errors indicate no overfitting
* Linear Regression provides a strong baseline prediction model

---

**Results and Conclusion**

The Linear Regression model successfully captures the relationship between environmental factors and solar power generation. While the performance is reasonable, prediction accuracy can be improved using advanced mod
