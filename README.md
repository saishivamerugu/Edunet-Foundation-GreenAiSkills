# Edunet-Foundation-GreenAiSkills
Air Quality Index Prediction Using Python

Project Overview
--------------------------
This project analyzes air pollution data and predicts the Air Quality Index (AQI) using machine learning models. The goal is to clean the data, explore its patterns, and build models that help in forecasting air pollution levels.

Project Steps
-------------------------
1. Data Collection
The dataset contains information on various air pollutants like PM10, NH3, Xylene, and other environmental factors.
It is loaded into a Pandas DataFrame for analysis.

2. Data Cleaning
Handling Missing Values: Some pollutants (like Xylene) had missing values, which were either filled or removed to ensure data accuracy.
Removing Duplicates: Duplicate records were identified and deleted to avoid biased results.
Checking Data Types: Ensured that numerical and categorical data were correctly formatted.

3. Exploratory Data Analysis (EDA)
Understanding Data Distribution: Used histograms and scatter plots to see how different pollutants vary.
Identifying Skewness: Checked for left-skewed or right-skewed data to understand the distribution of pollutants.
Correlation Analysis: Analyzed relationships between different pollutants and AQI values.

5. Data Visualization
Seaborn and Matplotlib were used to create:
Heatmaps for correlation between pollutants
Line charts to see AQI trends over time
Bar charts showing the impact of different pollutants on AQI

5. Feature Engineering
Selected Important Features: Chose key pollutants that had the most impact on AQI prediction.
Removed Less Relevant Features: Dropped columns that did not significantly contribute to predictions.

6. Machine Learning Model Implementation
Decision Tree Regressor and Random Forest Regressor were used to predict AQI values.
Model Training: The dataset was split into training and testing sets to ensure the models learn effectively.
Performance Evaluation: Checked model accuracy using metrics like Mean Squared Error (MSE) and R-Squared values.

7. Model Optimization
Hyperparameter Tuning: Adjusted parameters in models to improve accuracy.
Cross-Validation: Used different training/testing splits to ensure stable performance.

8. Deployment and Future Improvements
Possible Enhancements:
Adding real-time data integration
Using deep learning models for better prediction
Creating a web or mobile application to display AQI trends

-> Tools and Libraries Used
----------------------------
Programming Language: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

Conclusion
--------------------------
This project provides insights into air pollution levels and predicts AQI using machine learning models. By cleaning the data, visualizing patterns, and training models, we can better understand and forecast air quality trends.

