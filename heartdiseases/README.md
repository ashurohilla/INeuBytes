# INeuBytes

This report presents the development of a Heart Disease Prediction Model using Exploratory Data Analysis (EDA) with Seaborn and an automated machine learning (AutoML) approach with the AutoGluon library. The dataset used for training and testing the model contains various features related to heart health and includes a target variable indicating the presence or absence of heart disease. The EDA process involves visualizing and analyzing the dataset to gain insights into the data distribution and correlations between features. Subsequently, the AutoGluon library is utilized to automate the model selection and tuning process for predicting heart disease, enabling accurate predictions while minimizing manual intervention.

# ! Introduction:
Heart disease is one of the leading causes of mortality worldwide. Predicting heart disease using machine learning techniques can be of great importance in early diagnosis and timely intervention, leading to improved patient outcomes. In this report, we explore the process of building a heart disease prediction model through the utilization of EDA with Seaborn and an AutoML approach with the AutoGluon library.

# 2. Data Description:
The dataset used for this project contains features related to heart health, such as age, sex, cholesterol levels, blood pressure, and electrocardiographic measurements, among others. The target variable indicates the presence (1) or absence (0) of heart disease. The dataset is divided into a training set and a test set to evaluate the performance of the model accurately.

 # 3. Exploratory Data Analysis (EDA) with Seaborn:
EDA is an essential step in understanding the underlying structure and patterns within the data. Seaborn, a Python data visualization library, is employed to create insightful visualizations, including histograms, box plots, correlation matrices, and scatter plots. These visualizations help us gain a better understanding of the distribution of features and identify potential relationships and correlations between them.

# 4. Data Preprocessing:
Before feeding the data into the AutoML pipeline, preprocessing steps such as handling missing values, encoding categorical variables, and feature scaling are performed. The data is split into features (X) and the target variable (y) for model training.

# 5. AutoML using AutoGluon:
AutoML automates the machine learning process, enabling faster and more accurate model selection and tuning. The AutoGluon library is utilized in this report due to its user-friendly interface and its ability to handle various machine learning tasks.

AutoGluon automatically searches through a range of algorithms and hyperparameters to identify the best-performing model. The library provides tools for binary classification tasks like heart disease prediction. The selected model is then trained on the training data and evaluated on the test data.

# 6. Model Evaluation:
The performance of the model is assessed using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and ROC
