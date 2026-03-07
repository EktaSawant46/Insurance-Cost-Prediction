# 🏥 Insurance Cost Prediction – Data Analysis & Machine Learning

## 📌 Project Overview

This project focuses on analyzing an insurance dataset to understand the factors that influence **medical insurance charges**.

The project includes **data exploration, feature engineering, statistical testing, and a baseline machine learning model (Linear Regression)** to predict insurance costs.

The goal of this project is to build a strong foundation in **data analysis and machine learning workflows**.

---

## 🎯 Project Objectives

* Perform **Exploratory Data Analysis (EDA)** to understand the dataset
* Apply **Feature Engineering techniques**
* Conduct **statistical hypothesis testing**
* Prepare the dataset for machine learning
* Build a **Linear Regression model** to predict insurance charges

---

## 📊 Dataset Description

The dataset contains demographic and lifestyle information of individuals along with their medical insurance costs.

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the individual                       |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of dependents covered by insurance   |
| smoker   | Whether the individual is a smoker          |
| region   | Residential region                          |
| charges  | Medical insurance charges (Target Variable) |

---

## 🔎 Exploratory Data Analysis

The dataset was explored to understand distributions, relationships, and potential patterns.

Analysis included:

* Dataset structure and data types
* Summary statistics
* Missing value check
* Distribution of numerical variables
* Visualization of feature relationships

---

## ⚙️ Feature Engineering

Several feature engineering steps were applied to improve data usability:

* Cleaning and preparing dataset
* Transforming features where necessary
* Binning insurance charges using **quantile-based binning (`pd.qcut`)**
* Preparing categorical variables for statistical testing

These steps help improve interpretability and prepare the dataset for machine learning models.

---

## 🧪 Statistical Testing

A **Chi-Square Test of Independence** was performed to analyze relationships between categorical features and insurance charge categories.

### Hypothesis

* **Null Hypothesis (H₀):** No association between the feature and insurance charges.
* **Alternative Hypothesis (H₁):** A significant association exists.

This step helps identify which categorical features significantly influence insurance charges.

---

## 🤖 Machine Learning Model

A **Linear Regression model** was implemented to predict insurance charges based on the available features.

Steps included:

* Train–test split
* Model training
* Prediction
* Model evaluation

Linear Regression was used as a **baseline model** for this dataset.

---

## 📈 Key Insights

Some important observations from the analysis include:

* **Smoking status strongly impacts insurance charges**
* **Age and BMI show moderate relationships with medical costs**
* Some demographic factors have weaker influence compared to lifestyle factors

These insights help in understanding cost drivers in insurance pricing.

---

## 📂 Project Structure

```
Insurance-Cost-Prediction
│
├── notebooks
│   └── insurance_eda.ipynb
│
├── data
│   └── insurance_feature_engineered.csv
│
└── README.md
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## 🚧 Future Improvements

This project will be extended as part of my machine learning learning journey.

Planned improvements include:

* Implementing additional models such as **Decision Tree and Random Forest**
* Model performance comparison
* Feature importance analysis
* Building an interactive **data dashboard**
* Deploying a simple prediction application

---

## 👩‍💻 Author

**Ekta Sawant**

Aspiring Data Analyst / Machine Learning Enthusiast
Learning Python, Data Analysis, and Machine Learning.

