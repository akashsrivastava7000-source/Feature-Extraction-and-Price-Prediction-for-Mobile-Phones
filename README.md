# Feature-Extraction-and-Price-Prediction-for-Mobile-Phones
# 📱 Mobile Phone Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the price of mobile phones using Machine Learning. The dataset contains specifications such as RAM, Storage, Battery Capacity, Cameras, Processor, and other features. The goal is to build a regression model that accurately predicts the price of a mobile phone based on its specifications.

---

## 🎯 Objective

* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Apply feature engineering techniques.
* Train and evaluate Machine Learning models.
* Predict mobile phone prices with high accuracy.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset Information

* Total Records: **541**
* Original Features: **12**
* Features after preprocessing: **11**
* Target Variable: **Price**

### Features

* Brand
* Model
* Colour
* Memory
* RAM
* Battery Capacity
* Rear Camera
* Front Camera
* AI Lens
* Mobile Height
* Processor
* Price (Target)

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Missing Value Analysis
* Duplicate Value Check
* Data Type Conversion
* Univariate Analysis
* Bivariate Analysis
* Correlation Analysis
* Outlier Detection using Boxplots
* Distribution Analysis using Histograms

---

## ⚙️ Feature Engineering

New features were created to improve model performance:

* **Total Camera** = Rear Camera + Front Camera
* **RAM × Memory** interaction feature

Categorical variables were converted into numerical format using One-Hot Encoding.

---

## 🤖 Machine Learning Models

The following regression models were implemented:

* Linear Regression
* Decision Tree Regressor

---

## 📈 Model Evaluation

### Linear Regression

* MAE: **2990.78**
* MSE: **18,233,091.69**
* RMSE: **4270.02**
* R² Score: **0.8282**

### Decision Tree Regressor

Model performance was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 📋 Project Workflow

1. Import Dataset
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Price Prediction

---

## 📁 Project Structure

```
Mobile-Phone-Price-Prediction/
│
├── Feature_Extraction_and_Mobile_Phone_Price_Prediction.ipynb
├── Flipdata.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Mobile-Phone-Price-Prediction.git
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

---

## 📌 Future Improvements

* Random Forest Regressor
* XGBoost Regressor
* Hyperparameter Tuning
* Cross Validation
* Model Deployment using Flask or Streamlit

---

## 👨‍💻 Author

**Akash Srivastava**

* Data Analyst | Machine Learning Enthusiast
* Skills: Python, SQL, Excel, Power BI, Tableau, Machine Learning

