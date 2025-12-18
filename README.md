# **Solar Power Prediction using Linear Regression**

This project predicts **solar power generation (kW)** using a **Linear Regression** machine learning model.
It was developed as part of my internship:

**AI & Data Analytics Intern | AICTE Green Skills**

---

## **Project Overview**

Solar power prediction helps in effective energy planning and grid management.
This project applies **supervised machine learning** to predict solar power output using weather and solar-related parameters.

---

## **Project Workflow**

* Data loading and inspection
* Exploratory Data Analysis (EDA)
* Correlation and outlier analysis
* Feature scaling
* Model training using Linear Regression
* Model evaluation using error metrics

---

## **Dataset Information**

* **Total Records:** 4213
* **Total Features:** 21
* **Target Variable:** generated_power_kw

---

## **Key Input Features**

* Temperature (2m above ground)
* Relative humidity
* Mean sea level pressure
* Cloud cover (low, medium, high)
* Shortwave radiation
* Wind speed and direction
* Solar geometry parameters (zenith, azimuth, angle of incidence)

---

## **Dataset Quality**

* No missing values
* No duplicate records

---

## **Exploratory Data Analysis (EDA)**

The following techniques were applied:

* Histograms for feature distribution
* Scatter plots between features and target variable
* Correlation matrix and heatmap
* Box plots for outlier detection

---

## **Key Observations**

* Solar power is strongly influenced by shortwave radiation
* Zenith angle and angle of incidence significantly affect power generation
* Higher cloud cover and humidity reduce solar power output

---

## **Machine Learning Model**

* **Algorithm:** Linear Regression (scikit-learn)

---

## **Data Preprocessing**

* Feature–target split
* Train-test split (80% training, 20% testing)
* Feature scaling using StandardScaler

---

## **Libraries Used**

* pandas
* numpy
* matplotlib
* scikit-learn

---

## **Model Evaluation**

Model performance was evaluated using **Mean Absolute Error (MAE)**.

| Dataset      | MAE (kW) |
| ------------ | -------- |
| Training Set | ~392.42  |
| Test Set     | ~391.79  |

---

## **Interpretation**

* Similar training and testing errors indicate good generalization
* Linear Regression serves as a strong baseline model

---

## **Results and Conclusion**

This project demonstrates the application of machine learning techniques to real-world energy prediction problems.
Future improvements can include advanced regression models to enhance prediction accuracy.


