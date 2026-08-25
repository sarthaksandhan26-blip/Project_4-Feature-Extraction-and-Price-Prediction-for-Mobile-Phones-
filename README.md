# 📱 Feature Extraction and Price Prediction for Mobile Phones

## 📌 Project Overview

This project focuses on analyzing mobile phone specifications and predicting their prices using **Data Science and Machine Learning** techniques.

The main objective is to identify the most influential mobile phone features affecting price and develop a machine learning model capable of estimating the price of a mobile phone based on its specifications.

---
---<img width="1387" height="615" alt="70fdb93e-6c36-482a-a77d-33ee5788edf0" src="https://github.com/user-attachments/assets/2ce7afea-72e1-4956-a72e-5550a675a525" />

## 🎯 Project Objectives

- Explore and understand the mobile phone dataset.
- Clean and preprocess the data.
- Handle missing values, outliers, and inconsistent data.
- Perform feature engineering and feature extraction.
- Analyze relationships between mobile phone features and price.
- Build a machine learning model for price prediction.
- Evaluate model performance using appropriate metrics.
- Identify important features influencing mobile phone prices.
- Generate business recommendations for pricing and marketing decisions.

---

## 📊 Dataset
<img width="1710" height="525" alt="79fd7b68-6b70-4b57-93b3-2c352c42755e" src="https://github.com/user-attachments/assets/49ae4f37-b10f-4838-8fc9-4415ed992d4c" />
The dataset contains information about mobile phones, including:

- Model
- Colour
- Memory
- RAM
- Battery Level
- Rear Camera
- Front Camera
- AI Lens
- Mobile Height
- Processor
- Price

### Dataset Size

**541 rows × 11 original features**

**Target Variable:** `Price`

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the raw CSV dataset.
2. Checked the dataset structure and data types.
3. Identified and handled missing values.
4. Checked and handled outliers.
5. Processed categorical variables.
6. Extracted useful information from Model and Processor.
7. Prepared the dataset for machine learning.

---

## 🔧 Feature Engineering

Additional features were created to improve analysis and prediction.

### Derived Features

- **Price Segment**
- **Total Camera MP**
- **Brand**
- **Processor Brand**
- **Battery per GB**
- **Memory per GB**
- **Gaming Phone**
- **Camera Phone**
- **Performance Phone**
- **Budget Phone**

These features help provide better insights into the relationship between mobile phone specifications and price.

---

## 📈 Exploratory Data Analysis
<img width="1161" height="791" alt="9d2892fb-4aad-4c26-bc39-467d48b3a3aa" src="https://github.com/user-attachments/assets/785f1314-49a0-4ecb-bfa6-98db675a28d2" />

The project includes:

### Univariate Analysis
- Mobile phone price distribution
- Price boxplot
- Brand distribution
- Feature distributions

### Bivariate Analysis
- Feature vs Price relationships
- Brand vs Price
- RAM vs Price
- Memory vs Price
- Battery vs Price
- Camera specifications vs Price

### Multivariate Analysis
- Correlation analysis
- Feature relationships
- Feature importance analysis

---

## 🤖 Machine Learning

The project evaluates machine learning approaches for predicting mobile phone prices.

Possible models include:

- Linear Regression
- Decision Tree
- Random Forest
- Gradient Boosting

The dataset is divided into **training and testing sets** before model development.

---

## 📏 Model Evaluation

Model performance can be evaluated using:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

The best-performing model is selected based on the evaluation results.

> Model performance values should be updated with the final results obtained from the notebook.



## 💼 Business Value

The project can help a mobile phone organization:

- Make more data-driven pricing decisions.
- Understand the specifications associated with higher prices.
- Identify important product characteristics.
- Improve product segmentation.
- Support marketing and pricing strategies.
- Estimate prices for new mobile phone configurations.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

##👨‍💻 Author
---
Sarthak Sandhan

Integrated B.Tech (SY-Computer Science Engineering)

##🔗 LinkedIn
https://www.linkedin.com/in/sarthak-sandhan-19b174378/

##🔗 GitHub
https://github.com/sarthaksandhan26-blip
