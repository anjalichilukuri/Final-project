Solar Power Prediction using Linear Regression

This project predicts solar power generation (kW) using a Linear Regression machine learning model.
It was developed as part of my internship:

AI & Data Analytics Intern | AICTE Green Skills

PROJECT OVERVIEW

Solar power prediction helps in effective energy planning and grid management.
This project applies supervised machine learning to predict solar power output using weather and solar-related parameters.

PROJECT WORKFLOW

Data loading and inspection

Exploratory Data Analysis (EDA)

Correlation and outlier analysis

Feature scaling

Model training using Linear Regression

Model evaluation using error metrics

DATASET INFORMATION

Total Records: 4213

Total Features: 21

Target Variable: generated_power_kw

KEY INPUT FEATURES

Temperature (2m above ground)

Relative humidity

Mean sea level pressure

Cloud cover (low, medium, high)

Shortwave radiation

Wind speed and direction

Solar geometry parameters (zenith, azimuth, angle of incidence)

DATASET QUALITY

No missing values

No duplicate records

EXPLORATORY DATA ANALYSIS (EDA)

The following techniques were applied:

Histograms for feature distribution

Scatter plots between features and target variable

Correlation matrix and heatmap

Box plots for outlier detection

KEY OBSERVATIONS

Solar power is strongly influenced by shortwave radiation

Zenith angle and angle of incidence significantly affect power generation

Higher cloud cover and humidity reduce solar power output

MACHINE LEARNING MODEL

Algorithm: Linear Regression (scikit-learn)

DATA PREPROCESSING

Feature–target split

Train-test split (80% training, 20% testing)

Feature scaling using StandardScaler

LIBRARIES USED

pandas

numpy

matplotlib

scikit-learn

MODEL EVALUATION

Model performance was evaluated using Mean Absolute Error (MAE).

Dataset	MAE (kW)
Training Set	~392.42
Test Set	~391.79
INTERPRETATION

Similar training and testing errors indicate good generalization

Linear Regression serves as a strong baseline model

RESULTS AND CONCLUSION

This project demonstrates the application of machine learning techniques to real-world energy prediction problems.
Future improvements can include advanced regression models to enhance prediction accuracy.
