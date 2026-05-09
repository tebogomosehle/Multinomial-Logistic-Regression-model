# Overview

This project explores the use of Multinomial Logistic Regression to analyse household coping strategy choices in response to fruit and vegetable price fluctuations in Mankweng, Polokwane Local Municipality.

The project uses primary household survey data collected during my honours research and demonstrates key data science concepts including data preprocessing, categorical variable encoding, multiclass classification, and model evaluation.

# Dataset

Source: Primary household survey data collected during honours research

Study area: Mankweng, Polokwane Local Municipality, Limpopo Province, South Africa

Target variable: Household coping strategy choice (Multiclass classification)

Preparation:

* Renamed and cleaned variables
* Investigated potential outliers using boxplots, then treated them
* Encoded categorical variables using get_dummies()
* Encoded target classes using LabelEncoder
* Performed train-test split before model training

# Tools & Libraries Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

# Model Development

## Classification Model

Model: Multinomial Logistic Regression

The model was trained to classify household coping strategy choices based on socio-economic and market-related variables such as:

* Household size
* Household income
* Distance to market
* Education level
* Employment status
* Fruit and vegetable consumption behaviour

## Model Evaluation

The following evaluation methods were used:

* Accuracy score
* Confusion Matrix
* Classification analysis

# Model Performance

Multinomial Logistic Regression Accuracy: 27%

The relatively low predictive accuracy may largely be attributed to the small sample size, which limited the model’s ability to learn strong and consistent relationships between household characteristics and coping strategy choices.

# Key Insights

* Household coping behaviour proved difficult to predict due to overlapping socio-economic characteristics among households.
* Small sample size and multiple coping strategy categories limited model performance.
* Data preprocessing and categorical encoding played an important role in preparing survey data for machine learning analysis.

# Visualizations Used

* Boxplots for outlier detection
* Confusion Matrix

# Conclusion

This project demonstrates the practical application of machine learning classification techniques on real-world household survey data. Although the model achieved modest predictive performance, the project provided valuable experience in preprocessing survey data, handling multiclass classification problems, and evaluating machine learning models using Python.

# Future Improvements
* Test alternative classification models such as Decision Trees and Random Forests
Author: Tebogo Mosehle
