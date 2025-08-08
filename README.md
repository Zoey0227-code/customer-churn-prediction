# customer-churn-prediction
Python churn modeling with telecom data
# Customer Churn Prediction

A machine-learning project to predict which customers are most likely to churn (leave) based on demographic and usage data. Trained models can help telecom providers proactively address at-risk customers.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Modeling](#modeling)  
- [Results](#results)  
- [Folder Structure](#folder-structure)  
- [Dependencies](#dependencies)  
- [Contributing](#contributing)  
- [License](#license)  

---

## 🧐 Project Overview

Telecom companies lose revenue every time a subscriber cancels service. In this project, we:

1. **Ingest & clean** two datasets:  
   - Customer demographics (`telecom_demographics.csv`)  
   - Usage statistics (`telecom_usage.csv`)  
2. **Merge** them into a unified DataFrame.  
3. **Preprocess** (handle missing values, encode categoricals, scale features).  
4. **Train & evaluate** classification models (Logistic Regression, Random Forest) to predict churn.  
5. **Analyze** feature importance and model performance to guide retention strategies.

---

## 📂 Dataset

- **`telecom_demographics.csv`**  
  Contains customer ID, age, gender, region, tenure, contract type, etc.

- **`telecom_usage.csv`**  
  Contains customer ID, monthly minutes, data usage, number of calls, etc.

> **Note:** Combine on `customer_id` to build a complete record for each customer.

---

## 🚀 Installation

1. **Clone this repo**  
   ```bash
   git clone https://github.com/Zoey0227-code/customer-churn-prediction.git
   cd customer-churn-prediction
