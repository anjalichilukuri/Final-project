Solar Power Prediction using Linear Regression

This project predicts solar power generation (kW) using a Linear Regression machine learning model.
It was developed and submitted as part of my internship:

AI & Data Analytics Intern | AICTE Green Skills

📌 Project Overview

Solar power prediction helps in better energy planning and grid management.
In this project, I used supervised machine learning to predict solar power output based on weather and solar-related parameters.

Project Workflow

Load and inspect the dataset

Perform Exploratory Data Analysis (EDA)

Analyze correlations and outliers

Scale features

Train a Linear Regression model

Evaluate the model using error metrics

📂 Dataset Information

Total Records: 4213

Total Features: 21

Target Variable: generated_power_kw

Important Features Used

Temperature (2m above ground)

Relative humidity

Mean sea level pressure

Cloud cover (low, medium, high)

Shortwave radiation

Wind speed and direction

Solar angles (zenith, azimuth, angle of incidence)

Dataset Quality

✅ No missing values

✅ No duplicate records

🔍 Exploratory Data Analysis (EDA)

The following EDA techniques were used:

Histograms to understand data distribution

Scatter plots between features and target variable

Correlation matrix and heatmap

Box plots to detect outliers

Key Observations

Solar power strongly depends on:

Shortwave radiation

Zenith angle

Angle of incidence

Higher cloud cover and humidity reduce solar power generation

🧠 Machine Learning Model
Model Used

Linear Regression (scikit-learn)

Data Preprocessing Steps

Split data into features and target

Train-test split (80% training, 20% testing)

Feature scaling using StandardScaler

Libraries Used

pandas

numpy

matplotlib

seaborn

scikit-learn

📊 Model Evaluation

The model was evaluated using Mean Absolute Error (MAE).

Dataset	MAE (kW)
Training Set	~392.42
Test Set	~391.79
Interpretation

Similar training and testing errors show no overfitting

Linear Regression works well as a baseline model

🚀 Results & Conclusion

The model successfully learns the relationship between environmental factors and solar power generation.

Prediction accuracy is reasonable for a basic model.

Performance can be improved by using advanced models such as:

Polynomial Regression

Random Forest Regressor

Gradient Boosting / XGBoost

Neural Networks
